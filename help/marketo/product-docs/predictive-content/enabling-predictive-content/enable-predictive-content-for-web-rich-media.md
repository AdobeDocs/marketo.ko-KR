---
unique-page-id: 7514956
description: 웹 리치 미디어에 대한 예측 콘텐츠 활성화 - Marketo 문서 - 제품 설명서
title: 웹 리치 미디어용 예측 콘텐츠 활성화
exl-id: 030f1dd7-8fe7-4c82-be5e-052f0a259e3c
feature: Predictive Content
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 6%

---

# 웹 리치 미디어용 예측 콘텐츠 활성화 {#enable-predictive-content-for-web-rich-media}

예측 콘텐츠는 웹 방문자를 머신 러닝 및 예측 분석을 통해 제공되는 가장 관련성이 높은 콘텐츠로 유도합니다. Web Rich Media를 사용하면 텍스트 설명 및 이미지로 콘텐츠를 강화하고 웹 사이트에 여러 예측 콘텐츠 권장 사항을 포함할 수 있습니다.

>[!NOTE]
>
>예측 콘텐츠를 테스트하고 사용하기 전에 카테고리 및 소스(이메일, 리치 미디어, 막대)당 5개 이상의 콘텐츠를 활성화하는 것이 좋습니다. 콘텐츠가 많을수록 예측 결과가 향상됩니다.

>[!PREREQUISITES]
>
>예측 콘텐츠를 활성화하기 전에 다음을 수행해야 합니다.
>
>* **예측 콘텐츠 준비**
>
>   * [전자 메일에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md){target="_blank"} 또는
>   * [리치 미디어에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md){target="_blank"} 또는
>   * [권장 사항 표시줄에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md){target="_blank"}
>
>* [예측 콘텐츠의 제목 승인](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md){target="_blank"}

리치 미디어에 대한 컨텐츠 제목, 설명 및 이미지를 준비했으면 개별 또는 여러 컨텐츠 조각을 활성화할 수 있습니다.

1. 개별 제목을 활성화하려면 제목을 클릭하여 편집기를 엽니다. **[!UICONTROL Rich Media]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Enabled for Predictive Content in Rich Media]** 상자를 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2017-10-3-9-3a50-3a29.png)

1. 여러 콘텐츠의 경우 **[!UICONTROL Predictive Content]** 페이지에서 제목 옆에 있는 상자를 선택합니다.

   ![](assets/image2017-10-3-10-3a0-3a42.png)

1. **[!UICONTROL Content Actions]** 드롭다운을 클릭하고 **[!UICONTROL Enable for Web Rich Media]**&#x200B;를 선택합니다.

   ![](assets/image2017-10-3-10-3a2-3a6.png)|

## Javascript 코드 사용자 지정 및 웹 사이트에 포함  {#customize-the-javascript-code-and-embed-it-into-your-website}

Marketo 개발자 사이트[에서 리치 미디어 권장 사항 템플릿 ](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/rich-media-recommendation){target="_blank"}에 대한 설명서를 참조하십시오. 웹 사이트에 맞게 템플릿을 사용자 지정하는 방법을 설명합니다.

템플릿을 표시할 위치에 JavaScript 코드를 웹 사이트에 붙여넣습니다.

**템플릿 예제**

* Template1: 이미지, 헤더 및 설명이 있는 세 개의 가로 콘텐츠 조각
* Template2: 이미지, 헤더 및 설명이 있는 세 개의 수직 콘텐츠 조각

다음은 리치 미디어 추천 템플릿1의 예입니다.

![](assets/image2015-6-1-17-3a8-3a33.png)

다음은 리치 미디어 추천 템플릿2의 예입니다.

![](assets/image2015-12-20-10-3a35-3a12.png)
