---
unique-page-id: 2359663
description: 숨겨진 양식 필드 값 설정 - Marketo 문서 - 제품 설명서
title: 숨겨진 양식 필드 값 설정
exl-id: acec7de1-8567-42c0-a6ce-a91b0bf69f41
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '306'
ht-degree: 0%

---

# 숨겨진 양식 필드 값 설정 {#set-a-hidden-form-field-value}

숨겨진 필드는 일반적으로 동적으로 채워집니다. 양식에 입력한 사람에게 표시되지 않습니다. 다음은 값을 설정하는 방법입니다.

>[!PREREQUISITES]
>
>[양식 필드를 숨김으로 설정](/help/marketo/product-docs/demand-generation/forms/form-fields/set-a-form-field-as-hidden.md)

## 필드를 선택합니다 {#select-the-field}

1. 양식에서 숨김 필드를 선택하고 **편집** 대상 **자동 채우기**.

   ![](assets/autofill.png)

## 기본값 사용 {#use-default-value}

기본값 사용 을 선택하면 이 양식이 제출될 때 항상 사용할 특정 값을 하드 코딩할 수 있습니다. 기본값 을 입력하고 저장 을 클릭합니다.

![](assets/image2014-9-15-13-3a5-3a27.png)

## URL 매개 변수 {#url-parameter}

양식을 작성할 때 사용자가 있는 페이지에서 URL 매개 변수(쿼리 문자열)를 캡처하려면 다음을 사용할 수 있습니다 **URL 매개 변수** 숨김 필드를 채우려면

>[!NOTE]
>
>매개 변수가 좀 기술적이죠? 일단 얻으면 그들은 강력해요 이 [쿼리 문자열의 Wikipedia 페이지](https://en.wikipedia.org/wiki/Query_string) 은 다소 유용합니다.

1. 선택 **URL 매개 변수** 대상 **값 유형 가져오기**.

   ![](assets/image2014-9-15-13-3a6-3a48.png)

1. 을(를) 입력합니다. **매개 변수 이름** 을(를) 클릭합니다. **저장**.

   ![](assets/image2014-9-15-13-3a7-3a35.png)

>[!TIP]
>
>URL 매개 변수를 찾을 수 없는 경우 기본값 을 입력할 수 있습니다.

## 쿠키 값 {#cookie-value}

쿠키에 데이터를 저장하는 경우 **쿠키 값** 양식을 제출할 때 데이터를 선택합니다.

1. 선택 **쿠키 값** 대상 **다음에서 값 가져오기**.

   ![](assets/image2014-9-15-13-3a8-3a21.png)

1. 원하는 쿠키 매개 변수 이름을 입력하고 를 클릭합니다 **저장**.

   ![](assets/image2014-9-15-13-3a8-3a43.png)

   >[!TIP]
   >
   >매개 변수/쿠키를 찾을 수 없는 경우 기본값 을 입력할 수 있습니다.

## 레퍼러 매개 변수 {#referrer-parameter}

방문자가 양식을 작성하기 전에 가져온 페이지에서 데이터를 캡처하려면 다음을 사용할 수 있습니다 **레퍼러 매개 변수**.

1. 설정 **다음에서 값 가져오기** to **레퍼러 매개 변수**.

   ![](assets/image2014-9-15-13-3a9-3a31.png)

1. 을(를) 입력합니다. **매개 변수 이름** 레퍼러 URL에서 가로채려는 **저장**.

   ![](assets/image2014-9-15-13-3a9-3a56.png)

   >[!TIP]
   >
   >을(를) 입력할 수 있습니다 **기본값** 레퍼러 매개 변수를 찾을 수 없는 경우.

1. 클릭 **완료**.

   ![](assets/image2014-9-15-13-3a10-3a26.png)

1. 클릭 **승인 및 닫기**.

   ![](assets/image2014-9-15-13-3a10-3a43.png)
