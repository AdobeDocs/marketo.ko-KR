---
unique-page-id: 2359807
description: 경품 스타일 사용자 지정 - Marketo 문서 - 제품 설명서
title: 경품 스타일 사용자 정의
exl-id: 2b1437d9-a424-4d05-b614-7502c12e6ba2
source-git-commit: 97324d932b65020d041f728928d3792140bea71c
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 1%

---

# 경품 스타일 사용자 정의 {#customize-sweepstakes-styles}

[경품 추첨 만들기](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md)를 수행하면 랜딩 페이지의 모양을 사용자 지정할 수 있습니다.

>[!IMPORTANT]
>
>2024년 7월 31일에 이 기능의 사용 중단 프로세스를 시작했습니다. 새 자산을 만들 수 없습니다. 기존 자산은 2025년 1월 31일까지 계속 작동합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

>[!AVAILABILITY]
>
>일부 Marketo Engage 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

1. **마케팅 활동**(으)로 이동합니다.

![](assets/login-marketing-activities-1.png)

1. 경품권을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-25-17-3a51-3a45.png)

1. 경품 추첨 편집기에서 **앱 설정** > **모양**(으)로 이동합니다.

   ![](assets/image2014-9-25-17-3a51-3a59.png)

1. 등록 버튼의 텍스트와 진행률 링크를 편집합니다.

   ![](assets/image2014-9-25-17-3a52-3a22.png)

1. 맞춤화할 각 요소에 대해 사용자 지정 CSS 속성을 입력합니다.

   ![](assets/image2014-9-25-17-3a52-3a37.png)

   **Enter 단추**에 대한 CSS 예:
   `<pre>border: 5px solid #7B68EE; background-color: purple; padding: 10px; font: 16px; color: #FFFFFF; text-align: center;</pre>`

   **Enter 단추**에 대한 예제 이미지:
   `<pre>background:url(https://app.marketo.com/images/public-site/button_sign-up-now.png) no-repeat center center; width:275px; height:95px; margin:auto; display:block;</pre>` `<pre>`

   >[!NOTE]
   >
   >텍스트가 있는 이미지를 사용하는 경우 위의 텍스트 아래의 **단추 입력** 필드에서 텍스트를 제거해야 합니다.

1. 각각의 변경 작업을 수행하면 결과가 보기 및 편집 미리보기에 표시됩니다.

   ![](assets/image2014-9-25-17-3a55-3a3.png)

   >[!NOTE]
   >
   >이전 버전을 비롯한 여러 브라우저에서 단추를 테스트합니다.

   >[!MORELIKETHIS]
   >
   >다음 단계는 [등록 및 이행 이메일을 경품 추첨에 추가](/help/marketo/product-docs/demand-generation/social/social-functions/use-emails-in-social-promotions.md)하는 것입니다.
