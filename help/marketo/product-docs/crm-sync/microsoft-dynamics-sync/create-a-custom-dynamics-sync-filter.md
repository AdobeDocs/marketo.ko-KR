---
unique-page-id: 9437903
description: 사용자 지정 Dynamics 동기화 필터 만들기 - Marketo 문서 - 제품 설명서
title: 사용자 지정 Dynamics 동기화 필터 만들기
exl-id: 6b0d878a-9c55-4e73-9923-11140e83bb37
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '785'
ht-degree: 0%

---

# 사용자 지정 Dynamics 동기화 필터 만들기 {#create-a-custom-dynamics-sync-filter}

Dynamics CRM의 모든 항목을 Marketo에 동기화하지 않으시겠습니까? 걱정 마! Marketo을 사용하면 동기화 필터를 설정하고 레코드의 일부만 동기화할 수 있습니다.

## 개요 {#overview}

Dynamics 동기화 필터를 설정하려면 다음을 수행하십시오.

1. 모든 개체(리드, 연락처, 계정, 기회 및 기타 사용자 지정 엔티티)에 대해 Dynamics CRM에서 new_synctokto라는 사용자 지정 두 옵션(부울) 필드를 만듭니다.
1. 이 필드에 예/아니오 값을 할당하거나 비워 둡니다.

>[!NOTE]
>
>데이터베이스나 Marketo이 아닌 Dynamics CRM에서 이러한 변경 작업을 수행해야 합니다.

Marketo은 자동 백그라운드 동기화 중에 이 필드를 찾고 이 논리를 기반으로 동기화할 레코드를 결정합니다.

| 필드 값 | Marketo에 동기화하시겠습니까? |
|---|---|
| 필드가 없습니다. | 예 |
| 필드가 비어 있습니다. | 예 |
| 필드에 값이 있습니다. 예 | 예 |
| 필드에 값이 없음 | 아니요 |

>[!CAUTION]
>
>Marketo에서 레코드를 건너뛰도록 하는 유일한 방법은 필드 값을 명시적으로 설정하는 것입니다 **아니요**. 필드 값이 비어 있어도 Marketo은 여전히 레코드를 동기화합니다.

>[!PREREQUISITES]
>
>최신 버전의 Marketo 플러그인(3.0.0.1 이상)을 설치합니다. Marketo > 관리 > Microsoft Dynamics > Marketo 솔루션 다운로드 로 이동합니다.

## SyncToMkto 필드 만들기 {#create-synctomkto-field}

1. Dynamics CRM에 로그인합니다. 클릭 **설정** 을 클릭한 다음 **사용자 지정**.

   ![](assets/image2015-8-10-21-3a40-3a9.png)

1. 클릭 **시스템 사용자 지정**.

   ![](assets/image2015-8-10-21-3a42-3a15.png)

1. 클릭 ![](assets/image2015-8-10-21-3a44-3a23.png) 다음 **엔티티**.

   ![](assets/image2015-8-10-21-3a43-3a39.png)

1. 클릭 ![](assets/image2015-8-10-21-3a44-3a23.png) 다음 **리드** 을(를) 선택합니다. **필드**. 그런 다음 **새로 만들기**.

   ![](assets/image2015-8-10-21-3a49-3a49.png)

1. Enter 키 **SyncToMkto** 에서 **표시 이름** 필드 및 선택 **두 가지 옵션** 로서의 **데이터 유형**. 그런 다음 **저장 후 닫기**.

   ![](assets/image2015-9-8-10-3a25-3a33.png)

   >[!NOTE]
   >
   >이 필드의 표시 이름을 선택합니다. 그러나 이름 필드는 정확히 같아야 합니다 **new_synctomkto**. 를 사용해야 합니다. **새** 를 기본 접두사로 사용합니다. 기본값을 변경한 경우 여기 로 이동하십시오. [사용자 지정 필드 이름에 대한 기본 접두사 재설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/set-a-default-custom-field-prefix.md). 새 필드를 만든 후 다시 변경할 수 있습니다.

   >[!NOTE]
   >
   >비동기 워크플로우 설정을 설정한 경우 레코드가 필드에서 설정한 기본 SyncToMkto 값을 가져오고 워크플로우 실행이 완료되면 몇 초 후에 올바른 값을 가져옵니다. 기본값이 예로 설정되어 있으면 해당 레코드가 Marketo에 생성된 다음 사용되지 않습니다. 사용 **아니요** 를 기본값으로 사용합니다.

1. 이 프로세스를 반복하고 **SyncToMkto** 연락처, 계정, 기회 및 사용자 지정 개체 등 동기화를 제한하려는 다른 엔터티에 대한 필드입니다.

## Marketo에서 필터 선택 {#select-the-filter-in-marketo}

초기 동기화를 이미 완료했더라도 로 이동하여 Marketo과 동기화할 필드를 선택합니다.

1. Admin으로 이동하여 를 선택합니다 **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 클릭 **편집** 필드 동기화 세부 정보

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 아래로 스크롤하여 필드를 확인합니다. 실제 이름은 new_synctokto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. 클릭 **저장**.

   ![](assets/image2015-10-9-9-3a56-3a23.png)

좋습니다. 이제 Marketo에 대한 동기화 필터를 활성화했습니다.

## Dynamics 작업 과정을 만들어 동기화 필터 값을 자동으로 할당합니다. {#create-a-dynamics-workflow-to-assign-sync-filter-values-automatically}

항상 레코드의 SyncToMkto 필드에 값을 수동으로 할당할 수 있습니다. 하지만 레코드를 만들거나 업데이트할 때 Dynamics Workflow의 기능을 활용하고 SyncToMkto 필드에 값을 자동으로 할당하면 안 되는 이유는 무엇입니까?

>[!NOTE]
>
>데이터베이스 수준에서 이 작업을 수행할 수 없습니다. CRM에서 수동으로 또는 워크플로우를 사용하여 수행해야 합니다.
>
>Dynamics 워크플로우는 이전 데이터가 아니라 앞으로 만든 새 레코드에서만 작동합니다. 배치 갱신을 사용하여 기존 레코드를 이동합니다.

1. Dynamics CRM으로 이동합니다. 클릭 **설정** 을 클릭한 다음 **프로세스**.

   ![](assets/image2015-8-11-8-3a42-3a10.png)

1. 클릭 **새로 만들기**.

   ![](assets/image2015-8-11-8-3a43-3a46.png)

1. 워크플로우의 이름을 입력하고 을(를) 선택합니다 **워크플로우** 카테고리 및 **리드** 엔티티로 사용. 그런 다음 **확인**.

   ![](assets/image2015-8-11-8-3a45-3a46.png)

1. 규칙에 true 또는 false 값을 **SyncToMkto** 조직의 기본 설정에 따른 필드입니다. 클릭 **저장 후 닫기**.

   ![](assets/setsynctomkto-fix.png)

   >[!NOTE]
   >
   >클릭 후 기본 작업 정의 **단계 추가** 확인 조건을 추가하려면 동기화하지 않으려는 레코드를 설정합니다 **아니요**. 그렇지 않으면 동기화됩니다.

1. 워크플로우를 선택하고 을(를) 클릭합니다 **활성화**.

   ![](assets/image2015-8-11-8-3a57-3a29.png)

   >[!TIP]
   >
   >자세한 내용은 [이메일 주소에 대한 사용자 지정 동기화 필터 규칙](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md) 전자 메일 주소가 있는 사람에 대한 레코드만 동기화하는 규칙을 설정하려면 다음을 수행하십시오.

## 동기화 필터 세부 정보 {#sync-filter-details}

다음은 알아야 할 몇 가지 구현 세부 정보입니다.

1. 동기화 작업 시작

   이 **SyncToMkto** 값 변경 **아니요** to **예**&#x200B;를 사용하면 Dynamics에서 이 레코드 동기화를 시작하도록 Marketo에 즉시 알립니다. 레코드가 이미 있으면 Marketo에서 업데이트합니다. 그렇지 않으면 Marketo이 레코드를 만듭니다.

   >[!TIP]
   >
   >A `Create [StartSync]` 이 경우 작업이 Marketo 로그에 추가됩니다.

1. 동기화 작업 중지

   레코드가 SyncToMkto 값을 Yes에서 No로 변경하면 Marketo에 이 레코드 동기화를 중지하라는 알림이 표시됩니다. 하지만 레코드가 삭제되지 않으면 대신 업데이트가 더 이상 생성되지 않고 오래된 상태가 됩니다.

>[!MORELIKETHIS]
>
>* [Microsoft Dynamics 동기화 필터: 자격 부여](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-qualify.md)
>* [Microsoft Dynamics 동기화 필터: 병합](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/microsoft-dynamics-sync-filter-merge.md)
>* [이메일 주소에 대한 사용자 지정 동기화 필터 규칙](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter/custom-sync-filter-rules-for-an-email-address.md)

