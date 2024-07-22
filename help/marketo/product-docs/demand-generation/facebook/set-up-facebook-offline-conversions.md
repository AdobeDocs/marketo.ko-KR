---
unique-page-id: 11383953
description: facebook 오프라인 전환 설정 - Marketo 문서 - 제품 설명서
title: facebook 오프라인 전환 설정
exl-id: e1974943-8fc8-41f6-be7e-1b594de13db6
feature: Integrations
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '310'
ht-degree: 1%

---

# facebook 오프라인 전환 설정 {#set-up-facebook-offline-conversions}

리드 광고를 통해 만든 사람에 대한 오프라인 전환 데이터를 Facebook으로 다시 보내면 광고 팀이 그 어느 때보다 광고 비용을 최적화할 수 있습니다. 설정 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>* [Facebook 리드 광고를 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md)해야 합니다.
>* [수익 주기 Modeler](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/understanding-revenue-models.md)에 승인된 모델이 있어야 합니다.

## 관리자 구성 {#admin-configuration}

1. Marketo **관리자**(으)로 이동합니다.

   ![](assets/image2016-11-29-13-3a8-3a45.png)

1. **LaunchPoint**(으)로 이동하여 이전에 만든 Facebook 리드 광고 서비스를 두 번 클릭합니다.

   >[!NOTE]
   >
   >아직 수행하지 않았다면 [Facebook 리드 광고를 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md)한 다음 여기로 돌아오십시오.

   ![](assets/image2016-11-29-13-3a10-3a43.png)

1. 오프라인 전환을 포함하도록 **표시 이름**&#x200B;을(를) 편집하세요. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2016-11-29-13-3a12-3a19.png)

1. **오프라인 전환 사용**&#x200B;을 선택하고 **다음**&#x200B;을 클릭합니다.

   ![](assets/image2016-11-29-13-3a13-3a32.png)

1. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2016-11-29-13-3a14-3a17.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2016-11-29-13-3a14-3a52.png)

   잘됐네! facebook 오프라인 전환 활성화가 절반으로 완료되었습니다. 수익 주기 Modeler으로 이동하여 단계를 매핑하겠습니다.

   ![](assets/image2016-11-29-13-3a16-3a55.png)

## 수익 주기 Modeler 구성 {#revenue-cycle-modeler-configuration}

1. **분석**(으)로 이동합니다.

   ![](assets/image2016-11-29-13-3a29-3a23.png)

1. 모델을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/image2016-11-29-13-3a31-3a6.png)

   >[!NOTE]
   >
   >현재 다음과 같이 수익 주기 단계를 매핑할 수 있는 10개의 Facebook 이벤트가 있습니다.
   >
   >* 결제 정보 추가
   >* 장바구니에 추가
   >* 위시리스트에 추가
   >* 등록 완료됨
   >* 체크아웃 시작됨
   >* 개인
   >* 기타
   >* 구매
   >* 검색 결과
   >* 컨텐츠 보기

1. 매핑할 단계를 선택한 다음 **Facebook 전환** 드롭다운에서 매핑할 Facebook 이벤트를 선택합니다. 이 단계를 반복하여 RCM의 모든 단계를 Facebook의 오프라인 변환 단계에 매핑합니다.

   ![](assets/1-1.png)

1. 매핑을 마치면 모델을 닫습니다.

   ![](assets/2.png)

1. 모델을 승인하면 완료됩니다!

   ![](assets/image2016-11-29-15-3a6-3a30.png)

   이제 잠재 고객 광고 잠재 고객이 매핑된 단계에 도달하면 보고를 위해 Facebook으로 전환이 전송됩니다.

   >[!CAUTION]
   >
   >facebook 계정을 확인하고 모든 [광고가 Marketo 오프라인 전환 이벤트 집합에 연결](https://www.facebook.com/business/url/?href=%2Fbusiness%2Fhelp%2Fwww%2F1776828022605281&amp;cmsid&amp;creative=link&amp;creative_detail=advertiser-help-center&amp;create_type&amp;destination_cms_id&amp;orig_http_referrer)되어 있는지 확인하십시오. 그렇지 않으면 광고 속성이 작동하지 않을 수 있습니다.

   >[!NOTE]
   >
   >오프라인 전환 데이터는 Marketo에서 Facebook으로 매일 여러 번 전송됩니다.

>[!MORELIKETHIS]
>
>[Facebook 오프라인 전환 이해](/help/marketo/product-docs/demand-generation/facebook/understanding-facebook-offline-conversions.md)
