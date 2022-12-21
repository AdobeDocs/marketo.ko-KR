---
unique-page-id: 2359807
description: 경품 스타일 사용자 지정 - Marketo 문서 - 제품 설명서
title: 경품 스타일 사용자 지정
exl-id: 2b1437d9-a424-4d05-b614-7502c12e6ba2
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 0%

---

# 경품 스타일 사용자 지정 {#customize-sweepstakes-styles}

다음 경우에 [경품 행사 만들기](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md): 랜딩 페이지에서 모양을 사용자 지정할 수 있습니다.

>[!AVAILABILITY]
>
>모든 고객이 이 기능을 구입한 것은 아닙니다. 자세한 내용은 영업 담당자에게 문의하십시오.

1. 이동 **마케팅 활동**.

![](assets/login-marketing-activities-1.png)

1. 경품 이벤트를 선택하고 **초안 편집**.

   ![](assets/image2014-9-25-17-3a51-3a45.png)

1. 경품 편집기에서 **앱 설정** > **모양**.

   ![](assets/image2014-9-25-17-3a51-3a59.png)

1. 등록 단추와 진행 링크의 텍스트를 편집합니다.

   ![](assets/image2014-9-25-17-3a52-3a22.png)

1. 사용자 지정할 각 요소에 대해 사용자 지정 CSS 속성을 입력합니다.

   ![](assets/image2014-9-25-17-3a52-3a37.png)

   CSS 예제 **입력 단추**:
   `<pre>border: 5px solid #7B68EE; background-color: purple; padding: 10px; font: 16px; color: #FFFFFF; text-align: center;</pre>`

   이미지 예 **입력 단추**:
   `<pre>background:url(https://app.marketo.com/images/public-site/button_sign-up-now.png) no-repeat center center; width:275px; height:95px; margin:auto; display:block;</pre>` `<pre>`

   >[!NOTE]
   >
   >텍스트가 있는 이미지를 사용하는 경우 **입력 단추** 위의 텍스트 아래에 있는 필드입니다.

1. 각 변경 작업을 수행하면 결과가 보기 및 편집 미리 보기에 표시됩니다.

   ![](assets/image2014-9-25-17-3a55-3a3.png)

   >[!NOTE]
   >
   >이전 버전을 포함하여 여러 브라우저에서 단추를 테스트합니다.

   >[!MORELIKETHIS]
   >
   >다음 단계는 [구매에 이메일 등록 및 이행](/help/marketo/product-docs/demand-generation/social/social-functions/use-emails-in-social-promotions.md).
