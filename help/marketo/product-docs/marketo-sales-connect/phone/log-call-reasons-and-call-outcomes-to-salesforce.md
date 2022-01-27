---
description: Salesforce에 통화 이유 및 호출 결과 기록 - Marketo 문서 - 제품 설명서
title: Salesforce에 통화 이유 및 호출 결과 기록
hide: true
hidefromtoc: true
exl-id: b35acdc2-8ec7-4dec-92b8-58ba7a1ad858
source-git-commit: c71661553ecee07d3f9d7c7e2e1bab240da54d1d
workflow-type: tm+mt
source-wordcount: '467'
ht-degree: 0%

---

# Salesforce에 통화 이유 및 호출 결과 기록 {#log-call-reasons-and-call-outcomes-to-salesforce}

보고 또는 가시성을 위해 Salesforce에 호출 결과를 기록하고 호출 이유를 기록하려는 경우 각각에 대해 사용자 지정 활동 필드를 만들 수 있습니다. 각 필드는 특정 API 이름(Salesforce에서 &quot;필드 이름&quot;이라고 함)을 사용해야 합니다.

* 호출 결과 필드 이름: mktosales_call_result
* 호출 이유 필드 이름: mktosales_call_reason

이러한 필드를 활용하려면 먼저 필드를 사용자 지정 활동 필드로 만들어야 합니다. 사용자가 볼 수 있도록 하려면 작업 개체 페이지 레이아웃에 추가해야 합니다.

## Salesforce Classic {#salesforce-classic}

### Salesforce Classic에서 사용자 지정 활동 필드 만들기  {#create-custom-activity-field-in-salesforce-classic}

1. Salesforce에서 **설정**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-1.png)

1. 빠른 찾기 상자에 &quot;활동&quot;을 입력합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-2.png)

1. 클릭 **활동 사용자 지정 필드**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-3.png)

1. 클릭 **새로 만들기**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-4.png)

1. 데이터 유형 &quot;텍스트&quot;를 선택하고 **다음**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-5.png)

1. 위에 정의된 대로 사용자 지정 필드에 필드 이름을 지정합니다. 필드 길이는 255자로 제한됩니다. 필드 레이블은 영업 팀이 볼 수 있는 필드이며 팀의 요구 사항에 맞게 사용자 지정할 수 있습니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-6.png)

1. 나머지 설정은 선택 사항입니다. 구성을 완료했으면 을 클릭합니다 **다음**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-7.png)

1. 이 필드에 대해 원하는 필드 수준의 보안 설정을 선택하고 을 클릭합니다 **다음** (아래 이미지는 예일 뿐입니다.)

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-8.png)

   >[!NOTE]
   >
   >사용자 정의 필드가 Sales Connect 사용자가 사용하는 프로필과 표시할 다른 프로필이 있는지 확인합니다.

1. 필드를 추가할 페이지 레이아웃을 선택하고 을(를) 클릭합니다 **저장** (선택 사항) **저장 및 새로 만들기** 호출 사유 필드에 대한 프로세스를 반복합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-9.png)

### Salesforce Classic의 작업 페이지 레이아웃에 사용자 지정 활동 필드 추가 {#add-custom-activity-field-to-task-page-layout-in-salesforce-classic}

>[!NOTE]
>
>위의 9단계에서 원하는 페이지 레이아웃을 선택하지 않은 경우에만 다음 단계를 수행해야 합니다.

1. Salesforce에서 **설정**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-10.png)

1. 빠른 찾기 상자에 &quot;작업&quot;을 입력합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-11.png)

1. 클릭 **작업 페이지 레이아웃**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-12.png)

1. 클릭 **편집** 작업 페이지 레이아웃 옆에 이 필드를 추가할 필드를 추가합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-13.png)

1. 필드를 작업 페이지 레이아웃의 원하는 섹션으로 끌어서 놓습니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-14.png)

1. 클릭 **저장**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-15.png)

## Salesforce Lightning {#salesforce-lightning}

### Salesforce Lightning에서 사용자 지정 활동 필드 만들기 {#create-custom-activity-field-in-salesforce-lightning}

1. Salesforce에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-16.png)

1. 클릭 **개체 관리자**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-17.png)

1. 빠른 찾기 상자에 &quot;활동&quot;을 입력합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-18.png)

1. 을(를) 클릭합니다. **활동** 레이블.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-19.png)

1. 클릭 **필드 및 관계**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-20.png)

1. 클릭 **새로 만들기**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-21.png)

## Salesforce Lightning의 작업 페이지 레이아웃에 사용자 지정 활동 필드 추가 {#add-custom-activity-field-to-task-page-layout-in-salesforce-lightning}

1. Salesforce에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-22.png)

1. 클릭 **개체 관리자**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-23.png)

1. 빠른 찾기 상자에 &quot;작업&quot;을 입력합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-24.png)

1. 을(를) 클릭합니다. **작업** 레이블.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-25.png)

1. 클릭 **페이지 레이아웃**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-26.png)

1. 이 필드를 추가할 작업 페이지 레이아웃을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-27.png)

1. 필드를 작업 페이지 레이아웃의 원하는 섹션으로 끌어서 놓습니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-28.png)

1. 클릭 **저장**.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-29.png)

>[!MORELIKETHIS]
>
>[Activity History에 Sales Connect 이벤트 필드 설치](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/install-sales-connect-event-fields-on-activity-history.md)
