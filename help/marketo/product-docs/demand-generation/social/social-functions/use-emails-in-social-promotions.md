---
unique-page-id: 2359793
description: 소셜 프로모션에서 이메일 사용 - Marketo 문서 - 제품 설명서
title: 소셜 프로모션에서 이메일 사용
exl-id: 633ad86e-d085-420f-8e28-9b722e345852
feature: Social
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# 소셜 프로모션에서 이메일 사용 {#use-emails-in-social-promotions}

다음을 만들 때 [참조 오퍼](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md) 또는 [경품 추첨](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md), 대상자가 등록하면 전송할 이메일과 대상자가 포상을 받은 경우 다시 전송할 이메일을 포함할 수 있습니다.

>[!TIP]
>
>이메일을 만들려면 다음을 참조하십시오. [이메일 전송](/help/marketo/getting-started/quick-wins/send-an-email.md).

이메일에서 다음 토큰을 사용합니다.

* **등록 이메일**: 사용 **`{{social.Share Url}}`** 을 사용하여 각 참여자에게 개인화된 공유 링크를 보낼 수 있습니다.

* **주문 처리 이메일**: 사용 **`{{social.Promo Code}}`** 각 우승자에게 a 보내기 [프로모션 코드](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md).

>[!PREREQUISITES]
>
>소셜 앱에 이메일을 추가하려면 먼저 다음과 같아야 합니다. _작동-_ 및 _승인됨_. 다음을 참조하십시오 [전자 메일 설정 편집](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

1. 다음으로 이동 **마케팅 활동**.

   ![](assets/ma.png)

1. 앱을 선택하고 **초안 편집**.

   ![](assets/image2014-9-19-16-3a12-3a33.png)

1. 소셜 앱 편집기에서 **앱 설정 > 오퍼 세부 정보** (또는 **경품 추첨 세부 정보**).

   ![](assets/image2014-9-19-16-3a12-3a41.png)

1. 등록 이메일을 추가합니다.

   ![](assets/image2014-9-19-16-3a12-3a49.png)

   >[!NOTE]
   >
   >개인이 가입하면 확인 이메일이 자동으로 전송됩니다.

1. 이행 이메일을 추가합니다.

   ![](assets/image2014-9-19-16-3a15-3a26.png)

1. 추천 오퍼에서 이행 이메일을 자동으로 보낼지 수동으로 보낼지 선택합니다.

   ![](assets/image2014-9-19-16-3a15-3a36.png)

>[!NOTE]
>
>경품행사에서는 주문 시 이행 이메일이 항상 자동으로 전송됩니다 [우승자 선택](/help/marketo/product-docs/demand-generation/social/sweepstakes/select-sweepstakes-winners.md).

>[!NOTE]
>
>**정의**
>
>* **목표에 자동**: 각 참가자가 목표를 달성하면 이행 이메일이 자동으로 전송됩니다.
>* **수동으로 보내기**: 사람들이 목표를 충족하기 시작하면 추천 오퍼로 돌아가서 수동으로 [이행 이메일 보내기](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md).
>

>[!MORELIKETHIS]
>
>다음으로, 다음을 수행할 수 있습니다. [공유 URL 선택](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md) 또는 추천 오퍼에서 다음을 수행할 수 있습니다 [프로모션 코드 업로드](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md) 보내게 될 겁니다
