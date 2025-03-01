---
unique-page-id: 9437903
description: 사용자 지정 Dynamics 동기화 필터 만들기 - Marketo 문서 - 제품 설명서
title: 사용자 지정 Dynamics 동기화 필터 만들기
exl-id: 6b0d878a-9c55-4e73-9923-11140e83bb37
feature: Microsoft Dynamics
source-git-commit: cd09ad43c08855af63131aa385c4fd406c963926
workflow-type: tm+mt
source-wordcount: '818'
ht-degree: 0%

---

# 사용자 지정 Dynamics 동기화 필터 만들기 {#create-a-custom-dynamics-sync-filter}

Dynamics CRM의 모든 항목을 Marketo Engage에 동기화하지 않으시겠습니까? 걱정 마! Marketo을 사용하면 동기화 필터를 설정하고 레코드의 일부만 동기화할 수 있습니다.

## 개요 {#overview}

Dynamics 동기화 필터를 설정하려면 다음을 수행하십시오.

1. Dynamics CRM에서 개체(잠재 고객, 연락처, 계정, 기회 및 기타 사용자 지정 엔터티)에 대해 new_synctomkto라는 사용자 지정 두 가지 옵션(부울) 필드를 만듭니다.
1. 이 필드에 예/아니요 값을 지정합니다.

데이터베이스나 Marketo이 아닌 Dynamics CRM에서 이러한 변경 작업을 수행해야 합니다.

>[!CAUTION]
>
>필드를 할당하지 않고 비워 두거나 NULL로 두면 동기화되지만 업데이트되지는 않습니다. Dynamics CRM에서 필드 값이 비어 있거나 NULL인 레코드는 Marketo에서 이 필드 값을 &quot;false&quot;로 표시합니다.

Marketo은 자동 백그라운드 동기화 중에 이 필드를 찾고 이 논리를 기반으로 동기화할 레코드를 결정합니다.

| 필드 값 | Marketo과 동기화하시겠습니까? |
|---|---|
| 필드가 존재하지 않음 | 예 |
| 필드가 비어 있습니다. | 예 |
| 필드에 값이 있음 Yes | 예 |
| 필드에 값이 없음 | 아니요 |

>[!CAUTION]
>
>Marketo이 레코드를 건너뛰도록 하는 유일한 방법은 필드 값을 명시적으로 **아니요**(으)로 설정하는 것입니다. 필드 값이 비어 있더라도 Marketo은 여전히 레코드를 동기화합니다.

>[!PREREQUISITES]
>
>최신 버전의 Marketo 플러그인(3.0.0.1 이상)을 설치합니다. Marketo > 관리 > Microsoft Dynamics > Marketo 솔루션 다운로드로 이동합니다.

## SyncToMkto 필드 만들기 {#create-synctomkto-field}

1. Dynamics CRM에 로그인합니다. **설정**&#x200B;을 클릭한 다음 **사용자 지정**&#x200B;을 클릭합니다.

   ![](assets/image2015-8-10-21-3a40-3a9.png)

1. **시스템 사용자 지정**&#x200B;을 클릭합니다.

   ![](assets/image2015-8-10-21-3a42-3a15.png)

1. **엔터티** 옆의 ![](assets/image2015-8-10-21-3a44-3a23.png)을(를) 클릭합니다.

   ![](assets/image2015-8-10-21-3a43-3a39.png)

1. **리드** 옆에 있는 ![](assets/image2015-8-10-21-3a44-3a23.png)을(를) 클릭하고 **필드**&#x200B;를 선택합니다. **새로 만들기**&#x200B;를 클릭합니다.

   ![](assets/image2015-8-10-21-3a49-3a49.png)

1. **표시 이름** 필드에 **SyncToMkto**&#x200B;을(를) 입력하고 **데이터 형식**(으)로 **두 개의 옵션**&#x200B;을(를) 선택합니다. 그런 다음 **저장 후 닫기**&#x200B;를 클릭합니다.

   ![](assets/image2015-9-8-10-3a25-3a33.png)

   >[!NOTE]
   >
   >이 필드에 대한 표시 이름을 선택하십시오. 그러나 이름 필드는 정확히 **new_synctomkto**&#x200B;이어야 합니다. **new**&#x200B;을(를) 기본 접두사로 사용해야 합니다. 기본값을 변경한 경우 [사용자 지정 필드 이름에 대한 기본 접두사를 다시 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/set-a-default-custom-field-prefix.md){target="_blank"}(으)로 이동하십시오. 새 필드를 만든 후 다시 변경할 수 있습니다.

   >[!NOTE]
   >
   >비동기 워크플로우를 설정한 경우 레코드는 필드에 설정한 기본 SyncToMkto 값을 가져오고 몇 초 후 워크플로우 실행이 완료되면 올바른 값을 가져옵니다. 기본값을 예로 설정하면 해당 레코드가 Marketo에 만들어진 다음 부실해집니다. 이 문제를 방지하려면 **No**&#x200B;을(를) 기본값으로 사용하십시오.

1. 이 프로세스를 반복하고 연락처, 계정, 기회 및 사용자 지정 엔터티와 같이 동기화를 제한하려는 다른 엔터티에 대해 **SyncToMkto** 필드를 만드십시오.

## Marketo에서 필터 선택 {#select-the-filter-in-marketo}

초기 동기화를 이미 완료했더라도 로 이동하여 Marketo과 동기화할 필드를 선택합니다.

1. 관리자로 이동하여 **[!UICONTROL Microsoft Dynamics]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 필드 동기화 세부 정보에서 **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 필드로 스크롤하여 확인합니다. 실제 이름은 new_synctomkto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2015-10-9-9-3a56-3a23.png)

좋습니다. 이제 Marketo에 대한 동기화 필터를 활성화했습니다.

## 동기화 필터 값을 자동으로 할당할 Dynamics 워크플로 만들기 {#create-a-dynamics-workflow-to-assign-sync-filter-values-automatically}

레코드의 SyncToMkto 필드에 값을 항상 수동으로 할당할 수 있습니다. 그러나 레코드를 만들거나 업데이트할 때 Dynamics Workflow의 기능을 활용하고 SyncToMkto 필드에 값을 자동으로 할당하는 것은 어떻습니까?

>[!NOTE]
>
>데이터베이스 수준에서는 이 작업을 수행할 수 없습니다. CRM에서 수동으로 또는 워크플로우를 사용하여 수행해야 합니다.
>
>Dynamics 워크플로는 향후 생성된 새 레코드에서만 작동하며 이전 데이터에서는 작동하지 않습니다. 배치 업데이트를 사용하여 기존 레코드로 이동합니다.

1. Dynamics CRM으로 이동합니다. **설정**&#x200B;을 클릭한 다음 **프로세스**&#x200B;을 클릭합니다.

   ![](assets/image2015-8-11-8-3a42-3a10.png)

1. **새로 만들기**&#x200B;를 클릭합니다.

   ![](assets/image2015-8-11-8-3a43-3a46.png)

1. 워크플로우 이름을 입력하고 범주로 **워크플로우**&#x200B;를 선택하고 엔터티로 **리드**&#x200B;를 선택합니다. **확인**&#x200B;을 클릭합니다.

   ![](assets/image2015-8-11-8-3a45-3a46.png)

1. 조직의 기본 설정에 따라 **SyncToMkto** 필드에 true 또는 false 값을 할당하는 규칙을 만듭니다. **저장 후 닫기**&#x200B;를 클릭합니다.

   ![](assets/setsynctomkto-fix.png)

   >[!NOTE]
   >
   >**단계 추가**&#x200B;를 클릭하여 확인 조건을 추가한 후 기본 동작을 정의합니다. **아니요**&#x200B;에 동기화하지 않으려는 레코드를 설정합니다. 그렇지 않으면 동기화됩니다.

1. 워크플로우를 선택하고 **활성화**&#x200B;를 클릭합니다.

   ![](assets/image2015-8-11-8-3a57-3a29.png)

   >[!TIP]
   >
   >전자 메일 주소가 있는 사람의 레코드만 동기화하는 규칙을 설정하려면 [전자 메일 주소의 사용자 지정 동기화 필터 규칙](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md){target="_blank"}을 참조하세요.

## 동기화 필터 세부 정보 {#sync-filter-details}

다음은 알고 있어야 하는 몇 가지 구현 세부 정보입니다.

* 동기화 작업 시작

  **SyncToMkto** 값이 **아니요**&#x200B;에서 **예**(으)로 변경되면 Dynamics에서는 이 레코드의 동기화를 시작하도록 Marketo에 즉시 알립니다. 레코드가 이미 있으면 Marketo에서 업데이트합니다. 그렇지 않으면 Marketo이 레코드를 만듭니다.

  >[!TIP]
  >
  >이 경우 `Create [StartSync]` 작업이 Marketo 로그에 추가됩니다.

* 동기화 작업 중지

  레코드의 SyncToMkto 값이 Yes에서 No로 변경되면 이 레코드 동기화를 중지하라는 메시지가 Marketo에 표시됩니다. 그러나 레코드가 삭제되지 않고 대신 업데이트가 더 이상 수신되지 않고 사용되지 않습니다.

>[!MORELIKETHIS]
>
>* [Microsoft Dynamics 동기화 필터: 정규화](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-qualify.md){target="_blank"}
>* [Microsoft Dynamics 동기화 필터: 병합](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-merge.md){target="_blank"}
>* [전자 메일 주소에 대한 사용자 지정 동기화 필터 규칙](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md){target="_blank"}
