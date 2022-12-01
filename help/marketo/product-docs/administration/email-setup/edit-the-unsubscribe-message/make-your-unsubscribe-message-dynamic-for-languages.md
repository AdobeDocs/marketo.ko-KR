---
unique-page-id: 6848782
description: 언어를 위한 구독 취소 메시지를 동적으로 만들기 - Marketo 문서 - 제품 설명서
title: 언어를 위해 구독 취소 메시지를 동적으로 만들기
exl-id: 953a7fd8-b1f2-4f3f-b889-87d1f0471e0d
source-git-commit: aeaf1f55b81da70ac8415cab265165a3848b5a0e
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 0%

---

# 언어를 위해 구독 취소 메시지를 동적으로 만들기 {#make-your-unsubscribe-message-dynamic-for-languages}

기본 구독 취소 메시지 및 링크는 영어로 되어 있습니다. 동적 콘텐츠를 사용하여 다른 언어로 표시할 수 있습니다.

>[!NOTE]
>
>이 문서는 모범 사례를 나타내지만 다른 방법으로 수행할 수 있습니다.

## 데이터 준비 {#prepare-your-data}

1. [사용자 지정 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md) &quot;기본 언어&quot;라고 명명되었습니다. (이 필드를 동기화하려면 CRM에서 설정합니다.)

   >[!TIP]
   >
   >나중에 다음 경우에 이 필드를 사용합니다 [양식 만들기](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md) 언어 기본 설정을 캡처합니다.

## 세그멘테이션 만들기 {#create-segmentation}

1. 로 이동합니다. **데이터베이스**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-1.png)

1. 에서 **새로 만들기** 드롭다운에서 **새 세그멘테이션**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-2.png)

1. 세그먼테이션 이름을 지정합니다 **기본 언어**. 클릭 **세그먼트 추가**. 언어를 입력합니다.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-3.png)

   >[!NOTE]
   >
   >기본 세그먼트는 영어가 됩니다.

1. 모든 언어가 표시될 때까지 세그먼트를 계속 추가합니다. 클릭 **만들기**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-4.png)

1. 세그먼트를 선택하십시오.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-5.png)

1. 로 이동합니다. **Smart List** 탭. Enter 키 **기본 언어** 검색 필드에 입력할 수 있습니다. 필터를 캔버스에 드래그하여 놓습니다.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-6.png)

1. 적절한 해당 언어를 설정합니다.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-7.png)

1. 다른 모든 언어를 반복합니다. 그런 다음 **세그먼테이션 작업** 드롭다운 및 클릭 **승인**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-8.png)

## 코드 조각 만들기 {#create-a-snippet}

1. 로 이동합니다. **Design Studio**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-9.png)

1. 에서 **새로 만들기** 드롭다운 **새 코드 조각**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-10.png)

1. 코드 조각 이름을 지정합니다 **메시지 구독 취소**. 클릭 **만들기**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-11.png)

1. 기본 구독 취소 메시지를 입력하고 강조 표시한 다음 하이퍼링크 아이콘을 클릭합니다.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-12.png)

1. 다음 토큰을 복사하여 붙여넣습니다. `{{system.unsubscribeLink}}` 로 **URL** 필드. 클릭 **삽입**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-13.png)

1. 선택 **세그먼트 기준** 세분화 섹션에 있습니다.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-14.png)

1. 세그먼테이션 드롭다운에서 을 입력합니다. **기본 설정** 을(를) 선택합니다. **기본 언어**. 클릭 **저장**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-15.png)

1. 트리에서 세그먼트를 선택합니다. 가입 해지 를 클릭한 다음 링크 아이콘을 클릭합니다.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-16.png)

1. 확인 `{{system.unsubscribeLink}}` 는 여전히 URL 필드에 있습니다. 선택한 언어와 일치하도록 텍스트 표시 를 편집합니다. 클릭 **적용**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-17.png)

1. 모든 세그먼트에 대해 을 반복합니다. 그런 다음 Design Studio로 돌아가서 **코드 조각 작업** 드롭다운을 클릭하고 **승인**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-18.png)

끝내줘 거의 다 왔어!

## 이메일에 코드 조각 사용 {#use-snippet-in-an-email}

1. 이메일 편집기 내에서 편집 가능한 요소를 클릭합니다. 그런 다음 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **코드 조각으로 바꾸기**. 편집 가능한 코드 조각 요소를 선택하는 경우 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **편집**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-19.png)

1. 드롭다운에서 코드 조각을 찾아 선택하고 을(를) 클릭합니다. **저장**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-20.png)

1. 테스트하려면 **뒤로**...

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-21.png)

1. ...그러면 **동적** 탭.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-22.png)

1. 다른 언어를 클릭하여 코드 조각 변경을 확인합니다.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-23.png)

   >[!TIP]
   >
   >물론 다이내믹 언어로 나머지 이메일을 편집할 수도 있습니다. 가입 해지 페이지에서 동일한 기술을 수행합니다.

## 동적 콘텐츠를 사용하여 구독 취소 페이지 사용자 지정 {#customizing-your-unsubscribe-page-with-dynamic-content}

사람들이 기본 언어로 가입 해지 페이지를 방문하도록 하려면 랜딩 페이지와 확인 페이지에서 동적 콘텐츠를 사용할 수 있습니다.

1. 로 이동합니다 **Design Studio**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-24.png)

1. 입력 _구독 취소_ 검색 필드에서 원하는 가입 해지 페이지를 선택합니다.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-25.png)

1. 클릭 **초안 편집**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-26.png)

1. 선택 **세그먼트 기준**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-27.png)

1. 기본 언어 세그먼트를 찾습니다. 클릭 **저장**.

   ![](assets/make-your-unsubscribe-message-dynamic-for-languages-28.png)

   각 랜딩 페이지에 대한 콘텐츠를 편집하고 승인하면 쉽게 이동할 수 있습니다.

   >[!NOTE]
   >
   >추가 정보 [다이내믹 콘텐츠](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md) 그리고 당신이 할 수 있는 모든 멋진 것들을.
