---
description: 글로벌 양식 유효성 검사 규칙 - Marketo 문서 - 제품 설명서
title: 글로벌 양식 유효성 검사 규칙
exl-id: a44db893-00b5-40d2-8be3-41d52b2fd7b5
feature: Administration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '240'
ht-degree: 4%

---

# 글로벌 양식 유효성 검사 규칙 {#global-form-validation-rules}

이 기능을 사용하면 특정 도메인이 Marketo Engage 양식으로 제출되지 않도록 차단할 수 있습니다.

## 액세스 활성화 방법 {#how-to-enable-access}

이 기능을 활용하려면 먼저 원하는 역할에 따라 권한을 활성화해야 합니다.

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/global-form-validation-rules-1.png)

1. **[!UICONTROL Users & Roles]**&#x200B;를 클릭합니다.

   ![](assets/global-form-validation-rules-2.png)

1. **[!UICONTROL Roles]** 탭을 클릭합니다.

   ![](assets/global-form-validation-rules-3.png)

1. 권한을 부여하려는 역할을 두 번 클릭합니다.

   ![](assets/global-form-validation-rules-4.png)

1. **관리자 액세스** 옆에 있는 **+** 기호를 클릭합니다.

   ![](assets/global-form-validation-rules-5.png)

1. 아래로 스크롤하여 **[!UICONTROL Access Form Validation Rules]**&#x200B;을(를) 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/global-form-validation-rules-6.png)

## 새 양식 유효성 검사 규칙 만들기 {#create-new-form-validation-rule}

>[!IMPORTANT]
>
>이 규칙은 Marketo Engage 구독의 모든 양식에 적용됩니다.

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/global-form-validation-rules-7.png)

1. **[!UICONTROL Global Form Validation Rule]**&#x200B;를 클릭합니다.

   ![](assets/global-form-validation-rules-8.png)

1. **[!UICONTROL New Form Validation Rule]**&#x200B;를 클릭합니다.

   ![](assets/global-form-validation-rules-9.png)

   >[!NOTE]
   >
   >[!UICONTROL Form Validation Rule Actions] 드롭다운을 사용하면 기존 규칙을 삭제하거나 편집할 수 있습니다.

1. 규칙 이름을 지정하고 선택적 설명을 지정한 다음 양식 방문자에게 표시할 오류 메시지를 입력합니다. 규칙 상자에 차단하려는 도메인을 입력하고 **[!UICONTROL Activate Rule]**&#x200B;을(를) 선택한 다음 **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/global-form-validation-rules-10.png)

>[!NOTE]
>
>Marketo Engage에는 사전 로드된 소비자 이메일 도메인이 &quot;소비자 이메일 도메인 차단 목록에 추가하다&quot; 규칙을 사용할 때 차단되는 차단 목록에 추가하다가 정의되어 있습니다. [여기에서 해당 목록을 봅니다](/help/marketo/product-docs/administration/settings/assets/freemaildomains.csv)(다운로드하려면 브라우저가 최신 상태이고 다운로드를 수락할 수 있는지 확인).

## 양식당 액세스를 비활성화하는 방법{#how-to-disable-access-per-form}

활성화되면 규칙이 모든 양식에 적용됩니다. 그러나 특정 요구 사항이 있는 양식이 있고 거부되지 않도록 하려면 해당 양식의 설정에서 [!UICONTROL Global Form Validation Rules]을(를) 사용하지 않도록 설정할 수 있습니다.

1. 원하는 양식에서 **[!UICONTROL Form Settings]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/global-form-validation-rules-11.png)

1. **[!UICONTROL Global Form Validation Rules]** 드롭다운을 클릭하고 **[!UICONTROL Disabled]**&#x200B;을(를) 선택합니다.

   ![](assets/global-form-validation-rules-12.png)

양식을 승인하고 게시하면 [!UICONTROL Global Form Validation Rules]이(가) 무시됩니다.
