---
unique-page-id: 4720108
description: 컨텐츠 권장 사항 막대 활성화 - Marketo 문서 - 제품 설명서
title: 컨텐츠 권장 사항 막대 활성화
exl-id: f2244db1-51a9-4e26-9bf7-b2c79df25552
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 0%

---

# 컨텐츠 권장 사항 막대 활성화 {#enable-the-content-recommendation-bar}

컨텐츠 추천 엔진은 예측 분석 및 기계 학습 알고리즘을 사용하여 각 웹 방문자에게 적절한 컨텐츠를 제공합니다. 권장 사항 엔진은 방문자당 가장 성과가 좋은 콘텐츠를 예측합니다. Recommendations 페이지에서 엔진의 컨텐츠를 모니터링하고 제어하므로 컨텐츠 ROI를 최적화할 수 있습니다.

>[!PREREQUISITES]
>
>예측 컨텐츠를 활성화하기 전에 다음을 수행해야 합니다.
>
>* **예측 컨텐츠 준비**
   >
   >   * [이메일에 대한 예측 컨텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md) 또는
   >   * [리치 미디어에 대한 예측 컨텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md) 또는
   >   * [권장 사항 막대에 대한 예측 컨텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md)
>
>* [예측 컨텐츠에 대한 제목 승인](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md)


## 컨텐츠 권장 사항 막대 활성화 및 사용자 지정 {#enable-and-customize-the-content-recommendation-bar}

1. 이동 **콘텐츠 설정**.

   ![](assets/settings-dropdown-hand.png)

1. 클릭 **막대**.

   ![](assets/content-settings-bar-hand.png)

1. URL에 대한 권장 사항 막대를 활성화하려면 를 클릭하면 됩니다 **설정** 그리고 **저장**.

   ![](assets/bar-enable.png)

1. URL을 사용자 지정하려면 권장 사항 막대의 색상, 스타일, 형식, 화살표 및 막대를 포함하거나 제외할 페이지를 선택합니다. 웹 사이트 브랜딩에 맞게 사용자 정의합니다. 클릭 **저장**.

   ![](assets/bar-customize-details-hands.png)

   >[!NOTE]
   >
   >**표시 URL 포함/제외**
   >
   >* 표시 URL은 도메인의 경로여야 합니다.
   >* https:// 또는 https:// 포함 안 함
   >* 사용 &#42; 와일드카드의 경우
   >* 세미콜론을 구분 기호로 사용합니다
   >* 예: /contact_us&#42;; &#42;action=logout&#42;
   >* 이 필드는 대/소문자를 구분합니다


## 권장 사항 막대 고려 사항 {#recommendation-bar-considerations}

* 권장 사항 막대가 로 설정된 경우 하나 이상의 컨텐츠 조각이 필요합니다 **설정** 권장 사항 엔진이 작동하도록 Recommendations 페이지에 표시합니다. 컨텐츠가 활성화되지 않고 막대가 로 설정된 경우 **설정**&#x200B;웹 페이지의 오른쪽 아래에 화살표 효과가 표시되지만 권장 컨텐츠는 표시되지 않습니다.

* 권장 사항 엔진에서 실행되는 컨텐츠가 많을수록 알고리즘에서 가장 잘 작동하는 컨텐츠를 테스트하고 학습하는 것이 좋습니다. 10~20개의 컨텐츠 조각을 실행하고 활성 상태로 유지하고 새 컨텐츠 조각을 계속 추가하는 것이 좋습니다.
* 권장 사항을 위해 활성화하는 컨텐츠 조각에는 RTP Javascript 태그가 포함되어야 합니다. 이렇게 하면 알고리즘이 권장 컨텐츠를 추적하고 최적화하는 데 도움이 됩니다.

>[!MORELIKETHIS]
>
>[웹 리치 미디어용 Predictive Content 활성화](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
