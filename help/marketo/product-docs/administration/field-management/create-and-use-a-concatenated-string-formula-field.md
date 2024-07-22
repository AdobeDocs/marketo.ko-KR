---
unique-page-id: 2360337
description: 연결된 문자열(수식) 필드 만들기 및 사용 - Marketo 문서 - 제품 설명서
title: 연결된 문자열(공식) 필드 만들기 및 사용
exl-id: 779fbc56-a913-422a-a778-d86cc3ed7d48
feature: Field Management
source-git-commit: 9181a599ae715e9ffcfd84d8316dfa1c094329a6
workflow-type: tm+mt
source-wordcount: '170'
ht-degree: 0%

---

# 연결된 문자열(공식) 필드 만들기 및 사용 {#create-and-use-a-concatenated-string-formula-field}

여러 필드의 값을 결합하거나 Marketo Engage 수식 필드를 사용하여 조건부 값을 만들 수 있습니다.

1. **[!UICONTROL 관리자]** 영역으로 이동합니다.

   ![](assets/create-and-use-a-concatenated-string-formula-field-1.png)

1. **[!UICONTROL 필드 관리]**&#x200B;를 클릭합니다.

   ![](assets/create-and-use-a-concatenated-string-formula-field-2.png)

1. **[!UICONTROL 새 사용자 지정 필드]**&#x200B;를 클릭합니다.

   ![](assets/create-and-use-a-concatenated-string-formula-field-3.png)

1. **[!UICONTROL Type]**&#x200B;에 대해 **[!UICONTROL 수식]**&#x200B;을 선택하세요.

   ![](assets/create-and-use-a-concatenated-string-formula-field-4.png)

1. 필드에 **[!UICONTROL 이름]**&#x200B;을 입력한 다음 **[!UICONTROL 만들기]**&#x200B;를 클릭합니다.

   ![](assets/create-and-use-a-concatenated-string-formula-field-5.png)

1. 수식 필드를 찾아 선택한 다음 **[!UICONTROL 규칙 편집]**&#x200B;을 클릭합니다.

   ![](assets/create-and-use-a-concatenated-string-formula-field-6.png)

1. 두 가지 선택 사항을 추가하고 아래 스크린샷과 같이 정의합니다.

   ![](assets/create-and-use-a-concatenated-string-formula-field-7.png)

   >[!TIP]
   >
   >흐름 단계](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md)에 대한 [토큰에 대해 자세히 알아보세요.

1. 이제 공식 필드를 이메일에 토큰으로 추가할 수 있습니다.

   ![](assets/create-and-use-a-concatenated-string-formula-field-8.png)

>[!NOTE]
>
>공식 필드는 랜딩 페이지, 이메일 및 스마트 목록 열에서 사용할 수 있습니다. 수식 필드가 있는 전자 메일은 일괄 캠페인을 사용하여 _보낼 수 없습니다_. 이 시나리오에서 [전자 메일 스크립트 토큰](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md)을(를) 사용하십시오.

잘했어요! 이제 성별에 따른 인사말이 무엇인지 아는 똑똑한 분야가 생겼습니다. 이것들로 재미있게 놀고 창의적으로 하세요.
