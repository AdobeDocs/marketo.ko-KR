---
unique-page-id: 11385020
description: 이메일에서 예측 컨텐츠 사용 - 마케팅 문서 - 제품 설명서
title: 이메일에서 예측 컨텐츠 사용
translation-type: tm+mt
source-git-commit: 3c24395e55c756184615941327e15e050fa7d0ac
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---


# 이메일 {#enable-predictive-content-in-emails}에서 예측 컨텐츠 사용

이메일 예측 기능을 통해 하나 이상의 이미지를 만들어 각 수신자에게 적합한 경험을 제공할 수 있습니다.

>[!NOTE]
>
>예측 컨텐츠를 테스트하고 사용하기 전에 카테고리 및 소스(이메일, 리치 미디어, 막대)당 5개 이상의 컨텐츠를 활성화하는 것이 좋습니다. 추가 콘텐츠는 예측 가능한 결과를 제공합니다.

>[!PREREQUISITES]
>
>예측 컨텐츠를 활성화하기 전에. 다음을 수행해야 합니다.
>
>* [예측 컨텐츠 준비](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md)
>* [예측 컨텐트에 대한 제목 승인](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md)


## 이메일 2.0 편집기를 사용하여 예측 컨텐츠 추가 {#adding-predictive-content-using-the-email-editor}

1. **마케팅 활동**&#x200B;을 클릭합니다.

   ![](assets/one.png)

1. 전자 메일을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/two.png)

1. 예측하려는 이미지를 클릭합니다. 톱니바퀴 아이콘이 나타나면 아이콘을 클릭하고 **컨텐트 활성화`AI`**(컨텐트`AI`는 예측 컨텐트의 이전 이름)를 선택합니다.

   ![](assets/three.png)

1. 하나 이상의 범주를 선택하려면 **범주** 드롭다운을 클릭하고 원하는 항목을 선택한 다음 **적용**&#x200B;을 클릭합니다.

   ![](assets/four.png)

   >[!NOTE]
   >
   >특정 카테고리를 선택하거나 예측 레이아웃을 변경하는 것은 선택 사항입니다.

1. 이제 이미지가 예측됩니다. 추가 이미지에 대해서는 3-4단계를 반복합니다(원하는 경우).

   ![](assets/five.png)

1. 이메일을 미리 보려면 오른쪽 위 모서리에서 **미리 보기**&#x200B;를 클릭합니다.

   ![](assets/six.png)

1. 가능한 다른 이미지를 보려면 **새로 고침**&#x200B;을 클릭합니다.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >받는 사람이 이메일&#x200B;_**을(를) 열기 전에는**_&#x200B;이 선택되지 않았습니다. 미리 보기에서 볼 수 있는 것은 단지 한 예이며 받는 사람이 볼 수 있는 이미지가 아닐 수도 있습니다.

1. 이메일 미리 보기가 완료되면 **작업 미리 보기** 드롭다운을 클릭하고 **승인 및 닫기**&#x200B;를 선택합니다. 또는 편집해야 하는 경우 오른쪽에 있는 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >샘플을 보낼 때 임의의 이미지가 선택됩니다.

이메일을 승인하면 예측 컨텐츠가 준비되고 바로 전송할 수 있습니다!

>[!CAUTION]
>
>수신자가 이메일을 열면 예측 이미지가 잠깁니다. 콘텐트를 나중에 제거하면 콘텐트가 있었던 손상된 이미지가 수신자에게 표시됩니다.

## 이메일 2.0 편집기를 사용하지 않을 때 예측 컨텐츠 추가 {#adding-predictive-content-when-not-using-the-email-editor}

[이메일 2.0](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md) 템플릿을 사용하지 않는 경우, 예측 컨텐트를 이메일에 추가하는 것은 단순히 템플릿의 이미지를 Marketing to 편집 가능한 이미지 요소로 태깅하여 수행할 수 있습니다.

[마케팅 관련 구문에 대해 ](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md#elements)에서 알아봅니다.

다음은 코드가 어떻게 표시되어야 하는지에 대한 예입니다. 이것은 단지 예로서 아래의 코드를 정확히 복사하지 마십시오.

**예**

```example
<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="http://www.marketo.com">  
<a><img style="border:10px solid red;"></a>  
</div>
```
