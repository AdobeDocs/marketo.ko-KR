---
unique-page-id: 11385020
description: 이메일에서 예측 콘텐츠 활성화 - Marketo 문서 - 제품 설명서
title: 이메일에서 예측 콘텐츠 활성화
exl-id: 7eaefee1-23e8-47ee-afff-adcf49096aa7
feature: Predictive Content
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '375'
ht-degree: 3%

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
>   * [전자 메일에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-emails.md){target="_blank"} 또는
>   * [리치 미디어에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-rich-media.md){target="_blank"} 또는
>   * [권장 사항 표시줄에 대한 예측 콘텐츠 편집](/help/marketo/product-docs/predictive-content/working-with-predictive-content/edit-predictive-content-for-the-recommendation-bar.md){target="_blank"}
>
>* [예측 콘텐츠의 제목 승인](/help/marketo/product-docs/predictive-content/working-with-all-content/approve-a-title-for-predictive-content.md){target="_blank"}

## 이메일 2.0 편집기를 사용하여 예측 콘텐츠 추가 {#adding-predictive-content-using-the-email-editor}

1. **[!UICONTROL Marketing Activities]**&#x200B;를 클릭합니다.

   ![](assets/one.png)

1. 전자 메일을 선택하고 **[!UICONTROL Edit Draft]**&#x200B;을(를) 클릭합니다.

   ![](assets/two.png)

1. 예측하려는 이미지를 클릭합니다. 톱니바퀴 아이콘이 나타나면 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Enable ContentAI]**&#x200B;을(를) 선택합니다(ContentAI는 예측 콘텐츠의 이전 이름).

   ![](assets/three.png)

1. 하나 이상의 범주를 선택하려면 **[!UICONTROL Categories]** 드롭다운을 클릭하고 선택한 다음 **[!UICONTROL Apply]**&#x200B;을(를) 클릭합니다.

   ![](assets/four.png)

   >[!NOTE]
   >
   >특정 범주를 선택하거나 예측 레이아웃을 변경하는 것은 선택 사항입니다.

1. 이제 이미지가 예측됩니다. 추가 이미지에 대해 3단계와 4단계를 반복합니다(원하는 경우).

   ![](assets/five.png)

1. 전자 메일을 미리 보려면 오른쪽 상단의 **[!UICONTROL Preview]**&#x200B;을(를) 클릭합니다.

   ![](assets/six.png)

1. 다른 이미지를 보려면 **[!UICONTROL Refresh]**&#x200B;을(를) 클릭하십시오.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >받는 사람이 전자 메일을 열 때까지&#x200B;**_이미지를 선택하지 않습니다_**. 따라서 미리 보기에서 보는 것은 예시일 뿐이며 수신자가 볼 수 있는 이미지일 필요는 없습니다.

1. 전자 메일 미리 보기가 완료되면 **[!UICONTROL Preview Actions]** 드롭다운을 클릭하고 **[!UICONTROL Approve and Close]**&#x200B;을(를) 선택합니다. 또는 편집할 수 있는 경우 오른쪽의 **[!UICONTROL Edit Draft]**&#x200B;을(를) 클릭합니다.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >샘플을 보낼 때 임의의 이미지가 선택됩니다.

이메일을 승인하면 Predictive Content 가 장착되어 전송할 수 있습니다.

>[!CAUTION]
>
>수신자가 이메일을 열면 예측 이미지가 잠깁니다. 나중에 콘텐츠가 제거되면 수신자는 콘텐츠가 있었던 곳에서 손상된 이미지를 보게 됩니다.

## 이메일 2.0 편집기를 사용하지 않을 때 예측 콘텐츠 추가 {#adding-predictive-content-when-not-using-the-email-editor}

[이메일 2.0](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md){target="_blank"} 템플릿을 사용하지 않는 경우 템플릿의 이미지를 Marketo 편집 가능한 이미지 요소로 태깅하여 이메일에 예측 콘텐츠를 추가할 수 있습니다.

[Marketo 관련 구문에 대한 자세한 내용은 여기](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md#elements){target="_blank"}를 참조하세요.

다음은 코드가 어떤 모습이어야 하는지에 대한 예입니다(예제일 뿐, 아래의 코드를 정확하게 복사하지 마십시오).

**예**

```example
<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com">
<a><img style="border:10px solid red;"></a>
</div>
```
