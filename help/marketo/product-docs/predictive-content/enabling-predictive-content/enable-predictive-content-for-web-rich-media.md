---
unique-page-id: 7514956
description: 웹 리치 미디어용 예측 컨텐츠 활성화 - Marketo 문서 - 제품 설명서
title: 웹 리치 미디어용 Predictive Content 활성화
exl-id: 030f1dd7-8fe7-4c82-be5e-052f0a259e3c
source-git-commit: 4b1b91a933a7a6d103fe0d44ece9ea95759edc5f
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 0%

---

# 웹 리치 미디어용 Predictive Content 활성화 {#enable-predictive-content-for-web-rich-media}

예측 컨텐츠는 머신 러닝 및 예측 분석을 기반으로 가장 연관성 높은 콘텐츠를 웹 방문자에게 제공합니다. Web Rich Media를 사용하면 텍스트 설명 및 이미지로 컨텐츠를 개선하고 웹 사이트에 여러 개의 예측 컨텐츠 권장 사항을 포함할 수 있습니다.

>[!NOTE]
>
>예측 컨텐츠를 테스트하고 사용하기 전에 카테고리 및 소스당(이메일, 리치 미디어, 막대) 5개 이상의 컨텐츠를 활성화하는 것이 좋습니다. 더 많은 컨텐츠를 통해 더 나은 예측 결과를 얻을 수 있습니다.

>[!PREREQUISITES]
>
>예측 컨텐츠를 활성화하기 전에 다음을 수행해야 합니다.
>
>* **예측 컨텐츠 준비**
   >
   >   * [이메일에 대한 예측 컨텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md){target=&quot;_blank&quot;} 또는
   >   * [리치 미디어에 대한 예측 컨텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md){target=&quot;_blank&quot;} 또는
   >   * [권장 사항 막대에 대한 예측 컨텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md){target=&quot;_blank&quot;}
>
>* [예측 컨텐츠에 대한 제목 승인](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md){target=&quot;_blank&quot;}


리치 미디어에 대한 컨텐츠 제목, 설명 및 이미지를 준비하면 개별 또는 여러 컨텐츠 조각을 활성화할 수 있습니다.

1. 개별 제목을 사용하려면 제목을 클릭하여 편집기를 엽니다. 리치 미디어 를 클릭한 다음 **리치 미디어의 예측 컨텐츠에 대해 활성화됨** 상자를 클릭하고 **저장**.

   ![](assets/image2017-10-3-9-3a50-3a29.png)

1. 여러 콘텐츠의 경우 **Predictive Content** 페이지에서 제목 옆에 있는 상자를 선택합니다.

   ![](assets/image2017-10-3-10-3a0-3a42.png)

1. 을(를) 클릭합니다. **컨텐츠 작업** 드롭다운 및 선택 **웹 리치 미디어용 활성화**.

   ![](assets/image2017-10-3-10-3a2-3a6.png)|

## Javascript 코드 사용자 지정 및 웹 사이트에 포함  {#customize-the-javascript-code-and-embed-it-into-your-website}

리치 미디어 권장 사항 템플릿에 대한 설명서를 참조하십시오 [Marketo 개발자 사이트에서](https://developers.marketo.com/documentation/websites/rtp-rich-media-recommendations-api){target=&quot;_blank&quot;}. 이렇게 하면 웹 사이트에 사용할 템플릿을 사용자 지정하는 방법을 설명합니다.

JavaScript 코드를 템플릿을 표시할 위치의 웹 사이트에 붙여넣습니다.

**템플릿 예**

* 템플릿1: 이미지, 헤더 및 설명이 있는 3개의 가로 컨텐츠 조각
* 템플릿2: 이미지, 헤더 및 설명이 있는 세 개의 세로 컨텐츠 조각

다음은 리치 미디어 권장 사항 템플릿1의 예입니다.

![](assets/image2015-6-1-17-3a8-3a33.png)

다음은 리치 미디어 권장 사항 템플릿2의 예입니다.

![](assets/image2015-12-20-10-3a35-3a12.png)
