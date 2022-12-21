---
unique-page-id: 2359644
description: 알려진 사람의 사용자 지정 HTML 양식 표시 - Marketo 문서 - 제품 설명서
title: 알려진 사용자에 대한 사용자 지정 HTML 양식 표시
exl-id: 668216ea-7c2b-4204-81a5-56547c3baf1d
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '246'
ht-degree: 0%

---

# 알려진 사용자에 대한 사용자 지정 HTML 양식 표시 {#show-custom-html-form-for-known-people}

방문자가 쿠키되어 있는 경우(이전에 이메일 주소를 제공한 알려진 사람), 왜 양식으로 굳이 귀찮게 합니까? 다운로드 버튼만 주세요. 방법은 다음과 같습니다.

1. 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-5.png)

1. 아래 **마케팅 활동**&#x200B;을 클릭하고 양식을 선택하고 을(를) 클릭합니다. **양식 편집**.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. 아래 **양식 설정**&#x200B;를 클릭하고 **설정**.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. 설정 **알려진 방문자, 표시**: to **사용자 지정 HTML**.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. 을(를) 클릭합니다. ![—](assets/image2014-9-25-14-3a1-3a26.png) 를 편집하려면 **사용자 지정 HTML** 알려진 사람들에게 보여질 것입니다.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. 기본 콘텐츠가 있지만 언제든지 변경할 수 있습니다.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   사용 가능한 토큰:

   | 토큰 | 설명 |
   |---|---|
   | `{{lead.FirstName}}` | 사람의 이름이 표시됩니다. |
   | `{{lead.LastName}}` | 개인의 성이 표시됩니다. |
   | `{{form.Button:default=Download}}` | 양식 단추가 표시됩니다. 영역 뒤에 바꾸기 `=` 단추 텍스트를 변경하려면 |
   | `{{form.NotYou:default=Not you?}}` | 사람이 다른 사람인 경우 링크가 표시됩니다. 영역 뒤에 바꾸기 `=` 링크 텍스트를 변경하려면 |

   >[!CAUTION]
   >
   >위의 네 개의 토큰만 사용할 수 있습니다. 다른 토큰은 여기서 작동하지 않습니다.

1. 클릭 **완료**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. 클릭 **승인 및 닫기**.

   >[!NOTE]
   >
   >랜딩 페이지에서 사용하려면 양식을 승인해야 합니다.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >잊지 말고 [랜딩 페이지 초안 승인](/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) 양식 변경에 의해 만들어집니다.

   케이크 한 조각! 한 사람이 동일한 양식으로 돌아왔을 때 어떤 내용을 보게 되는지 확인하십시오.

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >양식 후속 페이지를 파일의 URL에 설정하여 버튼 클릭을 자산으로 보낼 수 있습니다.
