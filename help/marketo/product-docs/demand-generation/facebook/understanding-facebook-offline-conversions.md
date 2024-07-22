---
unique-page-id: 11383945
description: facebook 오프라인 전환 이해 - Marketo 문서 - 제품 설명서
title: facebook 오프라인 전환 이해
exl-id: e0995ebc-47fb-4f10-b767-4fe9f572b2d2
feature: Integrations
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '238'
ht-degree: 0%

---

# facebook 오프라인 전환 이해 {#understanding-facebook-offline-conversions}

Facebook 리드 광고 캠페인은 리드를 생성하고 마케팅 캠페인에서 사용할 수 있도록 Marketo으로 보냅니다. 그러나 오프라인 전환에 대한 가시성이 없으면 Facebook 광고주는 어떤 광고가 가장 효과적인지 알 수 없습니다. 예를 들어 보겠습니다.

>[!NOTE]
>
>**예**
>
>Facebook 리드 광고는 3개의 광고를 실행합니다.
>
>* Ad 1은 20개의 리드를 생성합니다.
>* Ad 2는 30개의 리드를 생성합니다.
>* Ad 3은 50개의 리드를 생성합니다.
>
>이 숫자만 놓고 보면 광고 3이 가장 효과적인 것 같다.
>
>하지만 Marketo 쪽의 데이터를 보면 다른 이야기가 전개됩니다.
>
>* 광고 1은 10개의 매출을 생성합니다.
>* 광고 3은 2개의 매출을 생성합니다.
>
>즉, 더 적은 리드 생성에도 불구하고 광고 1은 50%의 성공률을 보인 반면 광고 3은 거의 효과적이지 않았다는 의미입니다.
>
>오프라인 전환이 없다면 광고주는 광고 3에 더 많은 돈을 투자할 것입니다. 오프라인 전환 데이터를 사용하면 광고주가 광고 1에 투자할 가능성이 높아집니다.

[Facebook 오프라인 전환을 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md)하여 Facebook에 오프라인 광고 성능을 보낼 수 있습니다.

1. [Facebook LaunchPoint 통합](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-facebook-custom-audiences-as-a-launchpoint-service.md)이 최신 상태인지 확인하세요.
1. 수익 주기 모델의 단계를 Facebook의 오프라인 전환 단계에 매핑합니다.
1. facebook 잠재 고객이 Facebook 잠재 고객 광고에서 생성되고 매핑된 단계에 도달하면 Marketo은 안전하고 자동화된 API를 통해 오프라인 전환 데이터를 하루에 여러 번 Facebook으로 다시 보냅니다. 데이터가 Facebook 광고 관리자 보고서에 나타납니다.

>[!MORELIKETHIS]
>
>[Facebook 오프라인 전환 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md)
