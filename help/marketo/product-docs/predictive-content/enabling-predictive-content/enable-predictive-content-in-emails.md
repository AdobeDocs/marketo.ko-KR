---
unique-page-id: 11385020
description: 이메일에서 예측 컨텐츠 활성화 - Marketo 문서 - 제품 설명서
title: 이메일에서 예측 컨텐츠 활성화
exl-id: 7eaefee1-23e8-47ee-afff-adcf49096aa7
source-git-commit: 4b1b91a933a7a6d103fe0d44ece9ea95759edc5f
workflow-type: tm+mt
source-wordcount: '399'
ht-degree: 0%

---

# 이메일에서 예측 컨텐츠 활성화 {#enable-predictive-content-in-emails}

이메일 예측에서 하나 이상의 이미지를 만들어 각 수신자에 대한 경험을 맞춤 설정합니다.

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


## 이메일 2.0 편집기를 사용하여 예측 컨텐츠 추가 {#adding-predictive-content-using-the-email-editor}

1. 클릭 **마케팅 활동**.

   ![](assets/one.png)

1. 이메일을 선택하고 을(를) 클릭합니다 **초안 편집**.

   ![](assets/two.png)

1. 예측을 할 이미지를 클릭합니다. 톱니바퀴 아이콘이 나타나면 톱니바퀴를 클릭하고 을 선택합니다 **ContentAI 활성화** (ContentAI는 예측 컨텐츠의 이전 이름).

   ![](assets/three.png)

1. 하나 이상의 카테고리를 선택하려면 **카테고리** 드롭다운을 선택하고 **적용**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >특정 카테고리를 선택하거나 예측 레이아웃을 변경하는 것은 선택 사항입니다.

1. 이제 이미지가 예측됩니다. 추가 이미지에 대해 3단계와 4단계를 반복합니다(필요한 경우).

   ![](assets/five.png)

1. 이메일을 미리 보려면 **미리 보기** 오른쪽 상단 모서리에서

   ![](assets/six.png)

1. 가능한 다른 이미지를 보려면 **새로 고침**.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >이미지가 선택되어 있지 않습니다 **_수신자가 이메일을 열 때까지_**. 따라서 미리 보기에서 보는 것은 한 예이며 수신자가 보는 이미지가 아닐 수도 있습니다.

1. 전자 메일 미리 보기를 완료하고 나면 **작업 미리 보기** 드롭다운 및 선택 **승인 및 닫기**. 또는 편집해야 할 작업이 있는 경우 **초안 편집** 오른쪽에 있습니다.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >샘플을 보낼 때 무작위 이미지가 선택됩니다.

이메일을 승인하면 예측 콘텐츠가 준비되고 전송할 준비가 됩니다!

>[!CAUTION]
>
>수신자가 이메일을 열면 예측 이미지가 잠깁니다. 나중에 컨텐츠가 제거되면 수신자는 컨텐츠가 있는 손상된 이미지를 보게 됩니다.

## 이메일 2.0 편집기를 사용하지 않을 때 예측 컨텐츠 추가 {#adding-predictive-content-when-not-using-the-email-editor}

를 사용하지 않는 경우 [이메일 2.0](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md){target=&quot;_blank&quot;} 템플릿, 이메일에 예측 컨텐츠를 추가하는 작업은 템플릿의 이미지를 Marketo 편집 가능한 이미지 요소로 태깅하여 간단히 수행할 수 있습니다.

에 대해 알아보기 [Marketo 특정 구문](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md#elements){target=&quot;_blank&quot;}.

다음은 코드가 어떻게 표시되어야 하는지에 대한 예입니다. 예를 들어 아래의 코드를 정확히 복사하지 마십시오.

**예**

```example
<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com">  
<a><img style="border:10px solid red;"></a>  
</div>
```
