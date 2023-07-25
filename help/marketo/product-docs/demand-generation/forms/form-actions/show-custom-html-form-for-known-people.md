---
unique-page-id: 2359644
description: 알려진 사람에 대한 사용자 정의 HTML 양식 표시 - Marketo 문서 - 제품 설명서
title: 알려진 사용자에 대한 사용자 정의 HTML 양식 표시
exl-id: 668216ea-7c2b-4204-81a5-56547c3baf1d
feature: Forms
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '246'
ht-degree: 0%

---

# 알려진 사용자에 대한 사용자 정의 HTML 양식 표시 {#show-custom-html-form-for-known-people}

방문자가 쿠키를 사용하는 경우(과거에 이메일 주소를 제공한 알려진 사람) 양식에 문제가 되는 이유는 무엇입니까? 다운로드 버튼을 주면 됩니다. 방법은 다음과 같습니다.

1. 다음으로 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-5.png)

1. 아래 **마케팅 활동**&#x200B;을(를) 클릭하고 **양식 편집**.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. 아래 **양식 설정**, 클릭 **설정**.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. 다음과 같은 경우 설정 **알려진 방문자, 표시**: 종료 **사용자 지정 HTML**.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. 다음을 클릭합니다. ![—](assets/image2014-9-25-14-3a1-3a26.png) 을(를) 편집하려면 다음을 수행하십시오. **사용자 지정 HTML** 이는 알려진 사람들에게 표시될 것입니다.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. 일부 기본 콘텐츠가 있지만 자유롭게 변경할 수 있습니다.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   사용 가능한 토큰:

   | 토큰 | 설명 |
   |---|---|
   | `{{lead.FirstName}}` | 사용자의 이름이 표시됩니다. |
   | `{{lead.LastName}}` | 개인의 성이 표시됩니다. |
   | `{{form.Button:default=Download}}` | 양식 버튼이 표시됩니다. 다음 뒤의 영역을 바꿉니다. `=` 단추 텍스트를 변경합니다. |
   | `{{form.NotYou:default=Not you?}}` | 다른 사람인 경우 링크가 표시됩니다. 다음 뒤의 영역을 바꿉니다. `=` 링크 텍스트를 변경합니다. |

   >[!CAUTION]
   >
   >위의 네 가지 토큰만 사용할 수 있습니다. 다른 토큰은 여기에서 사용할 수 없습니다.

1. 클릭 **완료**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. 클릭 **승인 및 닫기**.

   >[!NOTE]
   >
   >양식이 랜딩 페이지에서 사용되도록 승인되어야 합니다.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >다음을 잊지 마십시오. [랜딩 페이지 초안 승인](/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) 작성자: 양식 변경 사항.

   케이크 한 조각! 동일한 양식으로 돌아왔다면 어떤 결과가 표시될지 확인하십시오.

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >양식 후속 작업 페이지를 파일의 URL로 설정하여 단추를 에셋으로 직접 클릭할 수 있습니다.
