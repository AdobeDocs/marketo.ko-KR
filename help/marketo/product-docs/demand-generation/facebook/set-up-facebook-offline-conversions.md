---
unique-page-id: 11383953
description: facebook 오프라인 전환 설정 - Marketo 문서 - 제품 설명서
title: facebook 오프라인 전환 설정
exl-id: e1974943-8fc8-41f6-be7e-1b594de13db6
source-git-commit: 41d8762203786bac9aea03ac978daa0549ac8e93
workflow-type: tm+mt
source-wordcount: '331'
ht-degree: 0%

---

# facebook 오프라인 전환 설정 {#set-up-facebook-offline-conversions}

리드 광고를 통해 만든 사용자를 위해 오프라인 전환 데이터를 다시 Facebook으로 보내어 광고 팀이 광고 비용을 이전보다 더 효과적으로 최적화할 수 있습니다. 설정 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>* 다음을 수행해야 합니다. [facebook 리드 광고 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md).
>* 에 승인된 모델이 있어야 합니다. [매출 주기 모델러](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/understanding-revenue-models.md).


## 관리 구성 {#admin-configuration}

1. Marketo으로 이동 **관리**.

   ![](assets/image2016-11-29-13-3a8-3a45.png)

1. 이동 **LaunchPoint** 이전에 만든 Facebook 리드 광고 서비스를 두 번 클릭합니다.

   >[!NOTE]
   >
   >아직 안하셨다면, 계속 진행하시고 [facebook 리드 광고 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md)그럼 여기로 다시 오세요

   ![](assets/image2016-11-29-13-3a10-3a43.png)

1. 원한다면 를 편집합니다 **표시 이름** 오프라인 전환을 포함하려면 다음을 수행하십시오. 클릭 **다음**.

   ![](assets/image2016-11-29-13-3a12-3a19.png)

1. 확인 **오프라인 전환 활성화** 을(를) 클릭합니다. **다음**.

   ![](assets/image2016-11-29-13-3a13-3a32.png)

1. 클릭 **다음**.

   ![](assets/image2016-11-29-13-3a14-3a17.png)

1. 클릭 **저장**.

   ![](assets/image2016-11-29-13-3a14-3a52.png)

   달콤해! facebook Offline Conversion 활성화를 반쯤 완료했습니다. Revenue Cycle Modeler로 이동하여 단계를 매핑해 보겠습니다.

   ![](assets/image2016-11-29-13-3a16-3a55.png)

## 매출 주기 모델러 구성 {#revenue-cycle-modeler-configuration}

1. 이동 **Analytics**.

   ![](assets/image2016-11-29-13-3a29-3a23.png)

1. 모델을 선택하고 을(를) 클릭합니다 **초안 편집**.

   ![](assets/image2016-11-29-13-3a31-3a6.png)

   >[!NOTE]
   >
   >현재 매출 주기 단계를 매핑할 수 있는 Facebook 이벤트가 10개 있습니다.
   >
   >* 결제 정보 추가
   >* 장바구니에 추가
   >* 위시 목록에 추가
   >* 등록 완료
   >* 시작된 체크아웃
   >* 개인
   >* 기타
   >* 구매
   >* 검색 결과
   >* 컨텐츠 보기 수


1. 매핑할 단계를 선택한 다음 **Facebook 전환** 드롭다운에서 매핑할 Facebook 이벤트를 선택합니다. 이 단계를 반복하여 RCM의 모든 단계를 Facebook의 오프라인 변환 단계에 매핑합니다.

   ![](assets/1-1.png)

1. 매핑을 마치면 모델을 닫습니다.

   ![](assets/2.png)

1. 모델을 승인하면 됩니다!

   ![](assets/image2016-11-29-15-3a6-3a30.png)

   이제, 리드 광고 리드가 매핑된 단계에 도달하면 전환을 Facebook으로 전송하여 보고할 수 있습니다.

   >[!CAUTION]
   >
   >facebook 계정을 확인하고 모두 확인합니다 [광고가 연결되어 있습니다](https://www.facebook.com/business/url/?href=%2Fbusiness%2Fhelp%2Fwww%2F1776828022605281&amp;cmsid&amp;creative=link&amp;creative_detail=advertiser-help-center&amp;create_type&amp;destination_cms_id&amp;orig_http_referrer) Marketo 오프라인 전환 이벤트 세트에 연결하는 중입니다. 그렇지 않으면 광고 속성이 작동하지 않을 수 있습니다.

   >[!NOTE]
   >
   >오프라인 전환 데이터는 매일 Marketo에서 Facebook으로 여러 번 전송됩니다.

>[!MORELIKETHIS]
>
>[facebook 오프라인 전환 이해](/help/marketo/product-docs/demand-generation/facebook/understanding-facebook-offline-conversions.md)
