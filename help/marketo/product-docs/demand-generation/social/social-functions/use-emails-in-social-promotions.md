---
unique-page-id: 2359793
description: 소셜 프로모션에서 이메일 사용 - Marketo 문서 - 제품 설명서
title: 소셜 프로모션에서 이메일 사용
exl-id: 633ad86e-d085-420f-8e28-9b722e345852
feature: Social
source-git-commit: 6c3f803104c550227aec25376778147ff92aaab9
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---

# 소셜 프로모션에서 이메일 사용 {#use-emails-in-social-promotions}

[추천 오퍼](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md) 또는 [경품 행사](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md)를 만들 때, 해당 사용자가 등록했을 때 전송할 전자 메일을 포함하고 해당 사용자가 보상을 획득했을 때 다시 전송할 수 있습니다.

>[!IMPORTANT]
>
>2024년 7월 31일에 이 기능의 사용 중단 프로세스를 시작했습니다. 더 이상 새 자산을 만들 수 없습니다. 기존 자산은 2025년 1월 31일까지 계속 작동합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

>[!TIP]
>
>전자 메일을 만들려면 [전자 메일 전송](/help/marketo/getting-started/quick-wins/send-an-email.md)을 참조하세요.

이메일에서 다음 토큰을 사용합니다.

* **등록 전자 메일**: **`{{social.Share Url}}`**&#x200B;을(를) 사용하여 각 참가자에게 개인화된 공유 링크를 보냅니다.

* **이행 전자 메일**: **`{{social.Promo Code}}`**&#x200B;을(를) 사용하여 각 승자에게 [프로모션 코드](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md)를 보냅니다.

>[!PREREQUISITES]
>
>소셜 앱에 전자 메일을 추가하려면 먼저 _작동_ 및 _승인_&#x200B;이어야 합니다. [전자 메일 설정 편집](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md)을 참조하세요.

1. **마케팅 활동**(으)로 이동합니다.

   ![](assets/ma.png)

1. 앱을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-19-16-3a12-3a33.png)

1. 소셜 앱 편집기에서 **앱 설정 > 오퍼 세부 정보**(또는 **경품 행사 세부 정보**)로 이동합니다.

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
>경품 행사에서는 [우승자를 선택](/help/marketo/product-docs/demand-generation/social/sweepstakes/select-sweepstakes-winners.md)할 때 항상 이행 이메일이 자동으로 전송됩니다.

>[!NOTE]
>
>**정의**
>
>* **목표에서 자동**: 각 참가자가 목표를 달성할 때마다 이행 전자 메일이 자동으로 전송됩니다.
>* **수동으로 보내기**: 사용자가 목표를 충족하기 시작하면 추천 오퍼로 돌아가 수동으로 [이행 이메일을 보내기](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md).
>

>[!MORELIKETHIS]
>
>다음으로 [공유 URL을 선택](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md)하거나 추천 오퍼에서 [프로모션 코드를 업로드](/help/marketo/product-docs/demand-generation/social/social-functions/use-promo-codes-for-offer-fulfillment.md)할 수 있습니다.
