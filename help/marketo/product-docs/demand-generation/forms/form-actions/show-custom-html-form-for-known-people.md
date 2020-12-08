---
unique-page-id: 2359644
description: 알려진 사람의 사용자 지정 HTML 양식 표시 - Marketing Docs - 제품 설명서
title: 알려진 사람을 위한 사용자 지정 HTML 양식 표시
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '298'
ht-degree: 0%

---


# 알려진 사람을 위한 사용자 지정 HTML 양식 표시 {#show-custom-html-form-for-known-people}

방문자가 쿠키를 사용하는 경우(이전에 이메일 주소를 제공한 알려진 사람) 왜 양식을 사용합니까? 그냥 다운로드 버튼만 주세요 방법

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

1. 마케팅 **활동** 으로 **이동합니다**.

   ![](assets/login-marketing-activities-5.png)

1. 마케팅 **활동****아래에서**&#x200B;양식을 선택하고 **양식** 편집을 **클릭합니다**.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. 양식 **설정****에서**&#x200B;설정을 **클릭합니다**.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. 알려진 **방문자** 를 **설정하고 다음을**&#x200B;표시합니다.사용자 **지정** **HTML로**&#x200B;이동했습니다.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. 알려진 사람에게 표시될 ![사용자 지정](assets/image2014-9-25-14-3a1-3a26.png) **** **HTML을** 편집하려면—을 클릭합니다.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. 기본 컨텐츠가 일부 있지만 언제든지 변경할 수 있습니다.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   사용 가능한 토큰:

   | 토큰 | 설명 |
   |---|---|
   | `{{lead.FirstName}}` | 그러면 사람의 이름이 표시됩니다. |
   | `{{lead.LastName}}` | 그러면 사람의 성이 표시됩니다. |
   | `{{form.Button:default=Download}}` | 양식 단추가 표시됩니다. 단추 텍스트를 변경하려면 영역 뒤 `=` 를 대체합니다. |
   | `{{form.NotYou:default=Not you?}}` | 그러면 사용자가 다른 사람인 경우 링크가 표시됩니다. 링크 텍스트를 변경하려면 영역 뒤 `=` 를 대체합니다. |

   >[!CAUTION]
   >
   >위의 네 개의 토큰만 사용할 수 있습니다. 다른 토큰은 여기서 작동하지 않습니다.

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
   >양식 변경에 의해 생성된 랜딩 페이지 초안을 [승인해야](../../../../product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) 합니다.

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >양식 후속 페이지를 파일의 URL로 설정하여 버튼의 클릭을 자산에 지시할 수 있습니다.

케이크 조각! 어떤 사람이 같은 형태로 돌아왔는지 확인해 보십시오.