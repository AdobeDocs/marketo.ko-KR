---
unique-page-id: 11378814
description: 계정 목록 - Marketo 문서 - 제품 설명서
title: 계정 목록
exl-id: 31bb4341-d012-4239-8f40-10a07cd4c51c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---

# 계정 목록 {#account-lists}

계정 목록은 함께 타겟팅할 수 있는 명명된 계정의 컬렉션입니다. 계정 목록을 사용하여 회사 업종, 위치 또는 크기별로 명명된 계정을 타깃팅할 수 있습니다.

계정 목록 외에 공용 CRM 계정 보기에서 생성된 동적 계정 목록을 만들 수도 있습니다. CRM 계정 보기는 계정을 표시할 때 필터 역할을 하는 규칙 세트입니다. 예를 들어, 이 정보를 사용하여 Industry가 Healthcare인 계정을 찾을 수 있습니다 *및* 매출액은 1억 달러가 넘습니다.

![](assets/one.png)

>[!NOTE]
>
>Marketo Target 계정 관리에서 만든 계정 목록은 의 스마트 목록 및 웹 캠페인을 작성할 때 자동으로 사용할 수 있습니다 [웹 개인화](/help/marketo/product-docs/web-personalization/using-web-segments/web-segments.md).

## 새 계정 목록 만들기 {#create-a-new-account-list}

1. 을(를) 클릭합니다. **새로 만들기** 드롭다운 및 선택 **새 계정 목록 만들기**.

   ![](assets/1a.png)

1. 목록에 이름을 지정하고 을(를) 클릭합니다. **만들기**.

   ![](assets/three-0.png)

1. 계정 목록을 만든 후에 시작합니다 [여기에 지정된 계정 추가](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)!

   >[!NOTE]
   >
   >Marketo에는 지정된 계정이 2,000개 이하인 계정 목록에만 인사이트가 표시됩니다.

## 새 동적 계정 목록 만들기 {#create-a-new-dynamic-account-list}

1. 을(를) 클릭합니다. **새로 만들기** 드롭다운 및 선택 **새 동적 목록 만들기**.

   ![](assets/1.png)

1. 대화 상자에서 **CRM 계정 보기** 드롭다운에서 또는 이름을 입력하여 검색합니다.

   ![](assets/image2017-7-18-9-48-23.png)

1. Click **Create**.

   ![](assets/step4.jpg)

   >[!NOTE]
   >
   >Salesforce에서 동기화 사용자에게 목록 보기 개체 권한을 제공해야 합니다.

## 계정 목록 이름 바꾸기 {#rename-an-account-list}

>[!NOTE]
>
>이러한 단계는 계정 목록에만 적용됩니다. _동적_ 계정 목록은 연결된 CRM 계정 보기 이름을 사용합니다.

1. 이름을 바꿀 계정을 선택하고 **계정 목록 작업** 드롭다운 및 선택 **계정 목록 이름 바꾸기**.

   ![](assets/three.png)

1. 새 이름을 입력하고 **이름 변경**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >CRM 계정 보기는 8시간마다 동적 계정 목록에 동기화됩니다. 아직 동기화되지 않은 경우 Marketo이 다음 주기 동안 동기화합니다.

## 계정 목록 삭제 {#delete-an-account-list}

>[!NOTE]
>
>이러한 단계는 계정 목록과 동적 계정 목록에서 동일합니다.

1. 삭제할 계정을 선택하고 **계정 목록 작업** 드롭다운 및 선택 **계정 목록 삭제**.

   ![](assets/five.png)

1. 클릭 **삭제**.

   ![](assets/six.png)

>[!MORELIKETHIS]
>
>* [계정 목록에 기존 명명 계정 추가](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)
>* [계정 목록 통찰력](/help/marketo/product-docs/target-account-management/measure/account-list-insights.md)

