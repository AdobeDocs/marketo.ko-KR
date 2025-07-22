---
unique-page-id: 2359663
description: 숨겨진 양식 필드 값 설정 - Marketo 문서 - 제품 설명서
title: 숨겨진 양식 필드 값 설정
exl-id: acec7de1-8567-42c0-a6ce-a91b0bf69f41
feature: Forms
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 1%

---

# 숨겨진 양식 필드 값 설정 {#set-a-hidden-form-field-value}

숨겨진 필드는 일반적으로 동적으로 채워집니다. 양식을 작성하는 사람에게 표시되지 않습니다. 다음은 값을 설정하는 방법입니다.

>[!PREREQUISITES]
>
>[양식 필드를 숨김으로 설정](/help/marketo/product-docs/demand-generation/forms/form-fields/set-a-form-field-as-hidden.md)

## 필드 선택 {#select-the-field}

1. 양식에서 숨겨진 필드를 선택하고 **[!UICONTROL Edit]**&#x200B;에 대해 **[!UICONTROL Autofill]**&#x200B;을(를) 클릭합니다.

   ![](assets/autofill.png)

## 기본값 사용 {#use-default-value}

**[!UICONTROL Default Value]** 사용 을 선택하면 이 양식을 제출할 때 항상 사용할 특정 값을 하드 코딩할 수 있습니다. **[!UICONTROL Default Value]**&#x200B;을(를) 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

![](assets/image2014-9-15-13-3a5-3a27.png)

## URL 매개 변수 {#url-parameter}

양식을 작성할 때 해당 사용자가 속한 페이지에서 URL 매개 변수(쿼리 문자열)를 캡처하려면 **[!UICONTROL URL Parameters]**&#x200B;을(를) 사용하여 숨겨진 필드를 채울 수 있습니다.

>[!NOTE]
>
>매개 변수는 일종의 기술이죠, 그렇죠? 일단 그것들을 얻으면, 그것들은 강력합니다. 이 [쿼리 문자열의 Wikipedia 페이지](https://en.wikipedia.org/wiki/Query_string)이(가) 도움이 됩니다.

1. **[!UICONTROL URL Parameter]**&#x200B;에 대해 **[!UICONTROL Get Value Type]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2014-9-15-13-3a6-3a48.png)

1. **[!UICONTROL Parameter Name]**&#x200B;을(를) 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-13-3a7-3a35.png)

>[!TIP]
>
>URL 매개 변수를 찾을 수 없는 경우 **[!UICONTROL Default Value]**&#x200B;을(를) 입력할 수 있습니다.

## 쿠키 값 {#cookie-value}

쿠키에 데이터를 저장하는 경우 양식을 제출할 때 **[!UICONTROL Cookie Value]**&#x200B;을(를) 사용하여 데이터를 선택할 수 있습니다.

1. **[!UICONTROL Cookie Value]**&#x200B;에 대해 **[!UICONTROL Get Value From]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2014-9-15-13-3a8-3a21.png)

1. 원하는 쿠키 **[!UICONTROL Parameter Name]**&#x200B;을(를) 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-13-3a8-3a43.png)

   >[!TIP]
   >
   >매개 변수/쿠키가 없는 경우 **[!UICONTROL Default Value]**&#x200B;을(를) 입력할 수 있습니다.

## 레퍼러 매개 변수 {#referrer-parameter}

양식을 작성하기 전에 방문자가 보낸 페이지에서 데이터를 캡처하려면 **[!UICONTROL Referrer Parameter]**&#x200B;을(를) 사용할 수 있습니다.

1. **[!UICONTROL Get Value From]**&#x200B;을(를) **[!UICONTROL Referrer Parameter]**(으)로 설정합니다.

   ![](assets/image2014-9-15-13-3a9-3a31.png)

1. 레퍼러 URL에서 가져올 **[!UICONTROL Parameter Name]**&#x200B;을(를) 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-13-3a9-3a56.png)

   >[!TIP]
   >
   >레퍼러 매개 변수를 찾을 수 없는 경우 **[!UICONTROL Default Value]**&#x200B;을(를) 입력할 수 있습니다.

1. **[!UICONTROL Finish]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-13-3a10-3a26.png)

1. **[!UICONTROL Approve and Close]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-13-3a10-3a43.png)
