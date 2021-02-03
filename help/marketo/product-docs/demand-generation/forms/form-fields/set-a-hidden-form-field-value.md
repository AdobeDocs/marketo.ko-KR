---
unique-page-id: 2359663
description: 숨겨진 양식 필드 값 설정 - 마케팅 문서 - 제품 설명서
title: 숨겨진 양식 필드 값 설정
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '306'
ht-degree: 0%

---


# 숨겨진 양식 필드 값 {#set-a-hidden-form-field-value} 설정

숨겨진 필드는 일반적으로 동적으로 채워집니다. 양식을 작성하는 사람에게 표시되지 않습니다. 값을 설정하는 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>[양식 필드를 숨김으로 설정](/help/marketo/product-docs/demand-generation/forms/form-fields/set-a-form-field-as-hidden.md)

## {#select-the-field} 필드를 선택합니다.

1. 양식에서 숨김 필드를 선택하고 **자동 채우기**&#x200B;에 대해 **편집**&#x200B;을 클릭합니다.

   ![](assets/autofill.png)

## 기본값 사용 {#use-default-value}

기본값 사용을 선택하면 이 양식이 전송될 때 항상 사용할 특정 값을 하드 코딩할 수 있습니다. 기본값을 입력하고 저장을 클릭합니다.

![](assets/image2014-9-15-13-3a5-3a27.png)

## URL 매개 변수 {#url-parameter}

양식을 채울 때 참석자가 있는 페이지에서 URL 매개 변수(쿼리 문자열)를 캡처하려면 **URL 매개 변수**&#x200B;를 사용하여 숨김 필드를 채울 수 있습니다.

>[!NOTE]
>
>매개 변수는 좀 기술적이죠? 하지만 일단 그것들을 얻으면, 그것들은 강력합니다. 이 [쿼리 문자열](https://en.wikipedia.org/wiki/Query_string)의 Wikipedia 페이지가 다소 유용합니다.

1. **값 유형 가져오기**&#x200B;에 대해 **URL 매개 변수**&#x200B;를 선택합니다.

   ![](assets/image2014-9-15-13-3a6-3a48.png)

1. **매개 변수 이름**&#x200B;을 입력하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-15-13-3a7-3a35.png)

>[!TIP]
>
>URL 매개 변수를 찾을 수 없는 경우 기본값을 입력할 수 있습니다.

## 쿠키 값 {#cookie-value}

쿠키에 데이터를 저장하는 경우 양식을 제출할 때 **쿠키 값**&#x200B;을 사용하여 데이터를 수집할 수 있습니다.

1. **Get Value From**&#x200B;에 대해 **쿠키 값**&#x200B;을 선택합니다.

   ![](assets/image2014-9-15-13-3a8-3a21.png)

1. 원하는 쿠키 매개 변수 이름을 입력하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-15-13-3a8-3a43.png)

   >[!TIP]
   >
   >매개 변수/쿠키를 찾을 수 없는 경우 기본값을 입력할 수 있습니다.

## 레퍼러 매개 변수 {#referrer-parameter}

양식을 작성하기 전에 방문자가 가져온 페이지에서 데이터를 캡처하려면 **레퍼러 매개 변수**&#x200B;를 사용할 수 있습니다.

1. **Get Value From**&#x200B;을 **레퍼러 매개 변수**&#x200B;로 설정합니다.

   ![](assets/image2014-9-15-13-3a9-3a31.png)

1. 레퍼러 URL에서 가져올 **매개 변수 이름**&#x200B;을 입력하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-15-13-3a9-3a56.png)

   >[!TIP]
   >
   >레퍼러 매개 변수를 찾을 수 없는 경우 **기본값**&#x200B;을 입력할 수 있습니다.

1. **완료**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-15-13-3a10-3a26.png)

1. **승인 및 닫기**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-15-13-3a10-3a43.png)
