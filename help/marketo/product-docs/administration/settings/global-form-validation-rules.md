---
description: 글로벌 양식 유효성 검사 규칙 - Marketo 문서 - 제품 설명서
title: 글로벌 양식 유효성 검사 규칙
exl-id: a44db893-00b5-40d2-8be3-41d52b2fd7b5
feature: Administration
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 0%

---

# 글로벌 양식 유효성 검사 규칙 {#global-form-validation-rules}

이 기능을 사용하면 특정 도메인이 Marketo Engage 양식으로 제출되지 않도록 차단할 수 있습니다.

## 액세스 활성화 방법 {#how-to-enable-access}

이 기능을 활용하려면 먼저 원하는 역할에 따라 권한을 활성화해야 합니다.

1. Marketo에서 **[!UICONTROL 관리자]**.

   ![](assets/global-form-validation-rules-1.png)

1. 클릭 **[!UICONTROL 사용자 및 역할]**.

   ![](assets/global-form-validation-rules-2.png)

1. 다음을 클릭합니다. **[!UICONTROL 역할]** 탭.

   ![](assets/global-form-validation-rules-3.png)

1. 권한을 부여하려는 역할을 두 번 클릭합니다.

   ![](assets/global-form-validation-rules-4.png)

1. 다음을 클릭합니다. **+** 액세스 관리자 옆에 로그인합니다.

   ![](assets/global-form-validation-rules-5.png)

1. 아래로 스크롤하여 선택 **[!UICONTROL 양식 유효성 검사 규칙 액세스]** 및 클릭 **[!UICONTROL 저장]**.

   ![](assets/global-form-validation-rules-6.png)

## 새 양식 유효성 검사 규칙 만들기 {#create-new-form-validation-rule}

>[!IMPORTANT]
>
>이 규칙은 Marketo Engage 구독의 모든 양식에 적용됩니다.

1. Marketo에서 **[!UICONTROL 관리자]**.

   ![](assets/global-form-validation-rules-7.png)

1. 클릭 **[!UICONTROL 전역 양식 유효성 검사 규칙]**.

   ![](assets/global-form-validation-rules-8.png)

1. 클릭 **[!UICONTROL 새 양식 유효성 검사 규칙]**.

   ![](assets/global-form-validation-rules-9.png)

   >[!NOTE]
   >
   >양식 유효성 검사 규칙 작업 드롭다운에서 기존 규칙을 삭제하거나 편집할 수 있습니다.

1. 규칙 이름을 지정하고 선택적 설명을 지정한 다음 양식 방문자에게 표시할 오류 메시지를 입력합니다. 차단하려는 도메인을 규칙 상자에 입력하고 다음을 선택합니다. **[!UICONTROL 규칙 활성화]**, 및 클릭 **[!UICONTROL 만들기]**.

   ![](assets/global-form-validation-rules-10.png)

>[!NOTE]
>
>Marketo Engage차단 목록에 추가하다 는 사전 로드된 &quot;소비자 이메일 도메인 차단 목록에 추가하다&quot; 규칙을 사용할 때 차단되는 무료 소비자 이메일 도메인의 정의된 도메인을 가지고 있습니다. [여기에서 해당 목록 보기](/help/marketo/product-docs/administration/settings/assets/freemaildomains.csv).

## 양식당 액세스를 비활성화하는 방법{#how-to-disable-access-per-form}

활성화되면 규칙이 모든 양식에 적용됩니다. 그러나 특정 요구 사항이 있는 양식이 있고 어떤 것도 거부하지 않으려는 경우 을 비활성화할 수 있습니다 [!UICONTROL 글로벌 양식 유효성 검사 규칙] 을 클릭합니다.

1. 원하는 양식에서 **[!UICONTROL 양식 설정]**, 그런 다음 **[!UICONTROL 설정]**.

   ![](assets/global-form-validation-rules-11.png)

1. 다음을 클릭합니다. **[!UICONTROL 글로벌 양식 유효성 검사 규칙]** 드롭다운 및 선택 **[!UICONTROL 비활성화됨]**.

   ![](assets/global-form-validation-rules-12.png)

양식을 승인하고 게시하면 양식이 무시됩니다. [!UICONTROL 글로벌 양식 유효성 검사 규칙].
