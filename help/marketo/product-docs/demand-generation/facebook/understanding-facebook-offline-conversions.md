---
unique-page-id: 11383945
description: facebook 오프라인 전환 이해 - Marketo 문서 - 제품 설명서
title: facebook 오프라인 전환 이해
exl-id: e0995ebc-47fb-4f10-b767-4fe9f572b2d2
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%

---

# facebook 오프라인 전환 이해 {#understanding-facebook-offline-conversions}

Facebook 리드 광고 캠페인이 리드를 생성하여 마케팅 캠페인에서 사용할 Marketo으로 보냅니다. 그러나 오프라인 전환을 표시하지 않으면 Facebook 광고주가 가장 효과적인 광고를 알 수 없습니다. 예를 들어보겠습니다.

>[!NOTE]
>
>**예**
>
>Facebook 리드 광고는 3개의 광고를 실행합니다.
>
>* 광고 1은 20개의 리드를 생성합니다
>* 광고 2는 30개의 리드를 생성합니다
>* 광고 3은 50개의 리드를 생성합니다
>
>이 숫자들만을 기준으로 하면, 광고 3이 가장 효과적인 것 같다.
>
>하지만 Marketo의 자료를 보면 이야기가 달라진다.
>
>* 광고 1은 10개의 매출을 생성합니다
>* 3은 2개의 매출을 생성합니다
>
>즉, 광고 1은 더 적은 리드를 생성했음에도 불구하고 성공률이 50%에 달했지만 광고 3은 전혀 효과적이지 않았습니다.
>
>오프라인 전환이 없으면 광고주는 광고 3에 더 많은 돈을 투자할 것입니다. 오프라인 전환 데이터를 사용하면 광고주가 광고 1에 더 많이 투자할 수 있습니다.

다음을 수행할 수 있습니다 [facebook 오프라인 전환 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md) 오프라인 광고 성능을 Facebook에 보내려면

1. 다음 사항을 확인하십시오. [Facebook LaunchPoint 통합](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-facebook-custom-audiences-as-a-launchpoint-service.md) 최신 버전입니다.
1. facebook의 매출 주기 모델의 단계를 오프라인 전환 단계에 매핑합니다.
1. facebook 리드가 Facebook 리드 광고에서 생성되고 매핑된 단계에 도달하면 Marketo에서는 보안 자동화된 API를 통해 오프라인 전환 데이터를 하루에 여러 번 Facebook으로 다시 보냅니다. 데이터가 Facebook 광고 관리자 보고서에 표시됩니다.

>[!MORELIKETHIS]
>
>[facebook 오프라인 전환 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md)
