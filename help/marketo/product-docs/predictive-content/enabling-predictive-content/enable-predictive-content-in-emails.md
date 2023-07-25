---
unique-page-id: 11385020
description: 이메일에서 예측 콘텐츠 활성화 - Marketo 문서 - 제품 설명서
title: 이메일에서 예측 콘텐츠 활성화
exl-id: 7eaefee1-23e8-47ee-afff-adcf49096aa7
feature: Predictive Content
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '387'
ht-degree: 0%

---

# 이메일에서 예측 콘텐츠 활성화 {#enable-predictive-content-in-emails}

이메일에 예측 가능한 이미지를 하나 이상 만들어 각 수신자에 대한 경험을 맞춤화합니다.

>[!NOTE]
>
>예측 콘텐츠를 테스트하고 사용하기 전에 카테고리 및 소스(이메일, 리치 미디어, 막대)당 5개 이상의 콘텐츠를 활성화하는 것이 좋습니다. 콘텐츠가 많을수록 예측 결과가 향상됩니다.

>[!PREREQUISITES]
>
>예측 콘텐츠를 활성화하기 전에 다음을 수행해야 합니다.
>
>* **예측 콘텐츠 준비**
>
>   * [이메일에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md){target="_blank"} 또는
>   * [리치 미디어에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md){target="_blank"} 또는
>   * [권장 사항 막대에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md){target="_blank"}
>
>* [예측 콘텐츠에 대한 제목 승인](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md){target="_blank"}

## 이메일 2.0 편집기를 사용하여 예측 콘텐츠 추가 {#adding-predictive-content-using-the-email-editor}

1. 클릭 **마케팅 활동**.

   ![](assets/one.png)

1. 이메일을 선택하고 **초안 편집**.

   ![](assets/two.png)

1. 예측하려는 이미지를 클릭합니다. 톱니바퀴 아이콘이 나타나면 톱니바퀴 아이콘을 클릭하고 **ContentAI 활성화** (ContentAI는 예측 콘텐츠의 이전 이름입니다.)

   ![](assets/three.png)

1. 하나 이상의 범주를 선택하려면 **카테고리** 드롭다운을 클릭하여 선택하고 **적용**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >특정 범주를 선택하거나 예측 레이아웃을 변경하는 것은 선택 사항입니다.

1. 이제 이미지가 예측됩니다. 추가 이미지에 대해 3단계와 4단계를 반복합니다(원하는 경우).

   ![](assets/five.png)

1. 이메일을 미리 보려면 **미리 보기** 오른쪽 상단 모서리입니다.

   ![](assets/six.png)

1. 가능한 다른 이미지를 보려면 **새로 고침**.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >이미지가 선택되지 않았습니다. **_수신자가 이메일을 열 때까지_**. 따라서 미리 보기에서 보는 것은 예시일 뿐이며 수신자가 볼 수 있는 이미지일 필요는 없습니다.

1. 이메일 미리 보기를 마치면 **작업 미리 보기** 드롭다운 및 선택 **승인 및 닫기**. 또는 편집해야 할 작업이 남아 있는 경우 **초안 편집** 오른쪽.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >샘플을 보낼 때 임의의 이미지가 선택됩니다.

이메일을 승인하면 Predictive Content 가 장착되어 전송할 수 있습니다.

>[!CAUTION]
>
>수신자가 이메일을 열면 예측 이미지가 잠깁니다. 나중에 콘텐츠가 제거되면 수신자는 콘텐츠가 있었던 곳에서 손상된 이미지를 보게 됩니다.

## 이메일 2.0 편집기를 사용하지 않을 때 예측 콘텐츠 추가 {#adding-predictive-content-when-not-using-the-email-editor}

를 사용하지 않는 경우 [이메일 2.0](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md){target="_blank"} 템플릿, 이메일에 예측 콘텐츠를 추가하는 작업은 템플릿에 이미지를 Marketo 편집 가능한 이미지 요소로 태깅하여 수행할 수 있습니다.

에 대해 알아보기 [Marketo 관련 구문 위치](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md#elements){target="_blank"}.

다음은 코드가 어떤 모습이어야 하는지에 대한 예입니다(예제일 뿐, 아래의 코드를 정확하게 복사하지 마십시오).

**예**

```example
<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com">  
<a><img style="border:10px solid red;"></a>  
</div>
```
