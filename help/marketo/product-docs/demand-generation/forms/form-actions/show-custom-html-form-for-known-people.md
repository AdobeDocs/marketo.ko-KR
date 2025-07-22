---
unique-page-id: 2359644
description: 알려진 사용자를 위한 사용자 지정 HTML 양식 표시 - Marketo 문서 - 제품 설명서
title: 알려진 사용자에 대한 사용자 지정 HTML 양식 표시
exl-id: 668216ea-7c2b-4204-81a5-56547c3baf1d
feature: Forms
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 1%

---

# 알려진 사용자에 대한 사용자 지정 HTML 양식 표시 {#show-custom-html-form-for-known-people}

과거에 방문자가 전체 이름과 이메일 주소를 제공했지만 전체 양식을 받지 못하게 하려는 경우, 일부 사용자 지정 HTML을 표시하는 방법(예: 다운로드 버튼만)을 배웁니다.

1. **[!UICONTROL Marketing Activities]**(으)로 이동합니다.

   ![](assets/login-marketing-activities-5.png)

1. **[!UICONTROL Marketing Activities]**&#x200B;에서 양식을 선택하고 **[!UICONTROL Edit Form]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. **[!UICONTROL Form Settings]**&#x200B;에서 **[!UICONTROL Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. **[!UICONTROL Known Visitor, Show]**&#x200B;인 경우 **[!UICONTROL Custom HTML]**(으)로 설정합니다.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. 알려진 사람들에게 표시될 ![을(를) 편집하려면 ](assets/image2014-9-25-14-3a1-3a26.png)—**[!UICONTROL Custom HTML]**&#x200B;을(를) 클릭하십시오.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. 일부 기본 콘텐츠가 있지만 자유롭게 변경할 수 있습니다.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   사용 가능한 토큰:

   | 토큰 | 설명 |
   |---|---|
   | `{{lead.FirstName}}` | 사용자의 이름이 표시됩니다. |
   | `{{lead.LastName}}` | 개인의 성이 표시됩니다. |
   | `{{form.Button:default=Download}}` | 양식 버튼이 표시됩니다. 단추 텍스트를 변경하려면 `=` 뒤에 있는 영역을 바꾸십시오. |
   | `{{form.NotYou:default=Not you?}}` | 다른 사람인 경우 링크가 표시됩니다. 링크 텍스트를 변경하려면 `=` 뒤에 있는 영역을 바꾸십시오. |

   >[!CAUTION]
   >
   >위의 네 가지 토큰만 사용할 수 있습니다. 다른 토큰은 여기에서 사용할 수 없습니다.

1. **[!UICONTROL Finish]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. **[!UICONTROL Approve and Close]**&#x200B;을(를) 클릭합니다.

   >[!NOTE]
   >
   >양식이 랜딩 페이지에서 사용되도록 승인되어야 합니다.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >양식을 변경하여 만든 랜딩 페이지 초안 [승인](/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md)해야 합니다.

   케이크 한 조각! 동일한 양식으로 돌아왔다면 어떤 결과가 표시될지 확인하십시오.

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >양식 후속 작업 페이지를 파일의 URL로 설정하여 단추를 에셋으로 직접 클릭할 수 있습니다.
