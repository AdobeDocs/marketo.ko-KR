---
unique-page-id: 2359793
description: 소셜 프로모션에서 이메일 사용 - Marketo 문서 - 제품 설명서
title: 소셜 프로모션에서 이메일 사용
exl-id: 633ad86e-d085-420f-8e28-9b722e345852
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# 소셜 프로모션에서 이메일 사용 {#use-emails-in-social-promotions}

을(를) 만들 때 [추천 오퍼](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md) 또는 [경품](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md), 사용자가 등록할 때 보낼 이메일과 사람이 보상을 받을 때 다시 포함할 수 있습니다.

>[!TIP]
>
>이메일을 만들려면 다음을 참조하십시오 [Email Blast 보내기](/help/marketo/getting-started/quick-wins/send-an-email.md).

이메일에서 다음 토큰을 사용하십시오.

* **등록 이메일**: 사용 **`{{social.Share Url}}`** 을 눌러 각 참여자에게 개인화된 공유 링크를 보냅니다.

* **이행 이메일**: 사용 **`{{social.Promo Code}}`** 각 승자를 [프로모션 코드](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md).

>[!PREREQUISITES]
>
>소셜 앱에 이메일을 추가하려면 먼저 _운영_ 및 _승인됨_. 자세한 내용은 [전자 메일의 설정 편집](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

1. 이동 **마케팅 활동**.

   ![](assets/ma.png)

1. 앱을 선택하고 을(를) 클릭합니다 **초안 편집**.

   ![](assets/image2014-9-19-16-3a12-3a33.png)

1. 소셜 앱 편집기에서 로 이동합니다. **앱 설정 > 오퍼 세부 사항** 또는 **경품 세부 정보**).

   ![](assets/image2014-9-19-16-3a12-3a41.png)

1. 등록 이메일을 추가합니다.

   ![](assets/image2014-9-19-16-3a12-3a49.png)

   >[!NOTE]
   >
   >사용자가 등록하면 확인 이메일이 자동으로 전송됩니다.

1. 이행 이메일을 추가합니다.

   ![](assets/image2014-9-19-16-3a15-3a26.png)

1. 참조 오퍼에서 이행 이메일을 자동으로 전송할지 또는 수동으로 전송할지를 선택합니다.

   ![](assets/image2014-9-19-16-3a15-3a36.png)

>[!NOTE]
>
>경품 이벤트에서 [승자 선택](/help/marketo/product-docs/demand-generation/social/sweepstakes/select-sweepstakes-winners.md).

>[!NOTE]
>
>**정의**
>
>* **목표 자동 설정**: 이행 이메일은 각 참가자가 목표를 만족할 때 자동으로 전송됩니다.
>* **수동으로 보내기**: 사람들이 목표를 충족하기 시작하면 수동으로 참조 오퍼로 돌아갑니다 [이행 이메일 보내기](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md).
>


>[!MORELIKETHIS]
>
>다음 작업을 수행할 수 있습니다. [공유 URL 선택](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md) 또는 참조 오퍼에서 다음을 수행할 수 있습니다 [프로모션 코드 업로드](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md) 보내드리겠습니다.
