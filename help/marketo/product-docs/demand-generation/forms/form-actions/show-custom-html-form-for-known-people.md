---
unique-page-id: 2359644
description: 알려진 사람의 사용자 지정 HTML 양식 표시 - Marketing To Docs - 제품 설명서
title: 알려진 사람을 위한 사용자 지정 HTML 양식 표시
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '247'
ht-degree: 0%

---


# 알려진 사람을 위한 사용자 지정 HTML 양식 표시 {#show-custom-html-form-for-known-people}

방문자가 쿠키를 사용하는 경우(이전에 이메일 주소를 제공한 것으로 알려진 사람), 왜 양식을 신경 써야 합니까? 다운로드 버튼만 주세요. 방법

1. 마케팅 **활동** 으로 **이동합니다**.

   ![](assets/login-marketing-activities-5.png)

1. 마케팅 **활동** 에서 ******양식을 선택하고** 양식 **편집**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. 양식 **설정********아래에서 설정을**&#x200B;클릭합니다.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. 알려진 **방문자****를**&#x200B;설정하고 다음을표시합니다.을 **사용자 지정** **HTML로**&#x200B;변환

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. 알려진 ![사람에게](assets/image2014-9-25-14-3a1-3a26.png) 표시될 사용자 지정 **** HTML **을 편집하려면** —를 클릭합니다.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. 기본 컨텐츠가 있지만 언제든지 변경할 수 있습니다.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   사용 가능한 토큰:

   | 토큰 | 설명 |
   |---|---|
   | `{{lead.FirstName}}` | 그러면 사람의 이름이 표시됩니다. |
   | `{{lead.LastName}}` | 그러면 사람의 성이 표시됩니다. |
   | `{{form.Button:default=Download}}` | 양식 단추가 표시됩니다. 단추 텍스트를 `=` 변경하려면 영역 뒤에 영역을 바꿉니다. |
   | `{{form.NotYou:default=Not you?}}` | 다른 사람이 있는 경우 링크가 표시됩니다. 링크 텍스트를 `=` 변경할 영역 뒤에 영역을 바꿉니다. |

   >[!CAUTION]
   >
   >위의 4개의 토큰만 사용할 수 있습니다. 다른 토큰은 여기서 작동하지 않습니다.

1. 마침을 **클릭합니다**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. 승인 **및 닫기를 클릭합니다**.

   >[!NOTE]
   >
   >랜딩 페이지에서 사용하려면 양식을 승인해야 합니다.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >**미리 알림**
   >
   >
   >양식 변경 [에 의해 만들어진 랜딩](../../../../product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) 페이지 초안을 승인해야 합니다.

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >양식 후속 페이지를 파일의 URL로 설정하여 단추의 클릭을 자산에 지정할 수 있습니다.

케이크 조각! 동일한 양식으로 다시 돌아왔을 때 어떤 모습을 보게 될지 살펴보십시오.