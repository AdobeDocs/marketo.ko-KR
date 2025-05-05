---
unique-page-id: 4720108
description: 콘텐츠 권장 사항 표시줄 - Marketo 문서 - 제품 설명서 활성화
title: 콘텐츠 추천 막대 활성화
exl-id: f2244db1-51a9-4e26-9bf7-b2c79df25552
feature: Predictive Content
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 0%

---

# 콘텐츠 추천 막대 활성화 {#enable-the-content-recommendation-bar}

콘텐츠 추천 엔진은 예측 분석 및 머신 러닝 알고리즘을 사용하여 각 웹 방문자에게 관련 콘텐츠를 전달합니다. 권장 사항 엔진은 방문자당 성과가 가장 좋은 콘텐츠를 예측합니다. 엔진의 콘텐츠는 Recommendations 페이지에서 모니터링 및 제어되므로 콘텐츠 ROI를 최적화할 수 있습니다.

>[!PREREQUISITES]
>
>예측 콘텐츠를 활성화하기 전에 다음을 수행해야 합니다.
>
>* **예측 콘텐츠 준비**
>
>   * [전자 메일에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md) 또는
>   * [리치 미디어에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md) 또는
>   * [권장 사항 표시줄에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md)
>
>* [예측 콘텐츠의 제목 승인](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md)

## 콘텐츠 추천 바 활성화 및 사용자 지정 {#enable-and-customize-the-content-recommendation-bar}

1. **콘텐츠 설정**(으)로 이동합니다.

   ![](assets/settings-dropdown-hand.png)

1. **막대**&#x200B;를 클릭합니다.

   ![](assets/content-settings-bar-hand.png)

1. URL에 대한 권장 사항 표시줄을 사용하려면 **켜짐**&#x200B;을 클릭한 다음 **저장**&#x200B;을 클릭하면 됩니다.

   ![](assets/bar-enable.png)

1. URL을 사용자 지정하려면 색상, 스타일, 서식, 추천 막대의 화살표, 막대를 포함하거나 제외할 페이지를 선택합니다. 웹 사이트 브랜딩에 맞게 사용자 지정합니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/bar-customize-details-hands.png)

   >[!NOTE]
   >
   >**표시 URL 포함/제외**
   >
   >* 표시 URL은 도메인의 경로여야 합니다.
   >* https:// 또는 https://을 포함하지 않음
   >* 와일드카드에 &#42; 사용
   >* 세미콜론을 구분 기호로 사용
   >* 예: /contact_us&#42;; &#42;action=logout&#42;
   >* 이 필드는 대/소문자를 구분합니다.

## 권장 사항 막대 고려 사항 {#recommendation-bar-considerations}

* 권장 사항 엔진이 작동하려면 Recommendations 페이지에서 권장 사항 막대를 **켜짐**(으)로 설정하는 데 하나 이상의 콘텐츠 조각이 필요합니다. 활성화된 컨텐츠가 없고 막대가 **켜짐**(으)로 설정된 경우 웹 페이지의 오른쪽 하단에 화살표 효과가 표시되지만 권장 컨텐츠가 표시되지 않습니다.

* 권장 사항 엔진에서 실행 중인 콘텐츠가 많을수록 알고리즘이 가장 잘 작동하는 콘텐츠를 테스트하고 학습하는 데 도움이 됩니다. 실행 중인 콘텐츠 조각은 10~20개이고 새로운 콘텐츠 조각은 계속 추가하는 것이 좋습니다.
* 권장 사항에 대해 활성화하는 콘텐츠 조각에 RTP Javascript 태그가 포함되어야 합니다. 이렇게 하면 알고리즘이 권장 콘텐츠를 추적하고 최적화하는 데 도움이 됩니다.

>[!MORELIKETHIS]
>
>[웹 리치 미디어에 대한 예측 콘텐츠 사용](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
