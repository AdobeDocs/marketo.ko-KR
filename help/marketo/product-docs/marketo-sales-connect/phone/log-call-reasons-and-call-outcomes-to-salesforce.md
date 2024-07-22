---
description: Salesforce - Marketo 문서 - 제품 설명서에 통화 이유 및 통화 결과 기록
title: Salesforce에 호출 사유 및 호출 결과 기록
exl-id: b35acdc2-8ec7-4dec-92b8-58ba7a1ad858
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '464'
ht-degree: 0%

---

# Salesforce에 호출 사유 및 호출 결과 기록 {#log-call-reasons-and-call-outcomes-to-salesforce}

보고 또는 가시성을 위해 호출 결과 및 호출 사유를 Salesforce에 기록하려는 경우 각각에 대해 사용자 지정 활동 필드를 만들 수 있습니다. 각 필드는 특정 API 이름(Salesforce에서는 &quot;필드 이름&quot;이라고 함)을 사용해야 합니다.

* 통화 결과 필드 이름: mktosales_call_result
* 통화 이유 필드 이름: mktosales_call_reason

이러한 필드를 활용하려면 먼저 필드를 사용자 정의 활동 필드로 만들어야 합니다. 사용자가 볼 수 있도록 하려면 작업 개체 페이지 레이아웃에 추가해야 합니다.

## Salesforce 클래식 {#salesforce-classic}

### Salesforce Classic에서 사용자 지정 활동 필드 만들기  {#create-custom-activity-field-in-salesforce-classic}

1. Salesforce에서 **설정**&#x200B;을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-1.png)

1. 빠른 찾기 상자에 &quot;활동&quot;을 입력합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-2.png)

1. **활동 사용자 지정 필드**&#x200B;를 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-3.png)

1. **새로 만들기**&#x200B;를 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-4.png)

1. 데이터 형식 &quot;텍스트&quot;를 선택하고 **다음**&#x200B;을(를) 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-5.png)

1. 사용자 정의 필드에 위에서 정의한 필드 이름을 지정합니다. 필드 길이는 255자로 제한됩니다. 필드 레이블은 영업팀에 표시되는 필드이며 팀의 요구 사항에 맞게 사용자 정의할 수 있습니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-6.png)

1. 나머지 설정은 선택 사항입니다. 구성을 완료했으면 **다음**&#x200B;을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-7.png)

1. 이 필드에 대해 원하는 필드 수준 보안 설정을 선택하고 **다음**&#x200B;을 클릭합니다(아래 이미지는 예제일 뿐).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-8.png)

   >[!NOTE]
   >
   >사용자 정의 필드가 Sales Connect 사용자가 사용하는 프로필에 표시되고 원하는 다른 항목도 표시되는지 확인하십시오.

1. 필드를 추가할 페이지 레이아웃을 선택하고 **저장**&#x200B;을(를) 클릭합니다(선택적으로 **저장 및 새로 만들기**&#x200B;를 클릭하고 호출 사유 필드에 대한 프로세스를 반복할 수 있음).

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-9.png)

### Salesforce Classic의 작업 페이지 레이아웃에 사용자 정의 활동 필드 추가 {#add-custom-activity-field-to-task-page-layout-in-salesforce-classic}

>[!NOTE]
>
>위의 9단계에서 원하는 페이지 레이아웃을 선택하지 않은 경우 다음 단계만 수행하면 됩니다.

1. Salesforce에서 **설정**&#x200B;을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-10.png)

1. 빠른 찾기 상자에 &quot;Task&quot;를 입력합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-11.png)

1. **작업 페이지 레이아웃**&#x200B;을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-12.png)

1. 이 필드를 추가할 작업 페이지 레이아웃 옆에 있는 **편집**&#x200B;을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-13.png)

1. 필드를 작업 페이지 레이아웃의 원하는 섹션으로 끌어다 놓습니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-14.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-15.png)

## Salesforce Lightning {#salesforce-lightning}

### Salesforce Lightning에서 사용자 지정 활동 필드 만들기 {#create-custom-activity-field-in-salesforce-lightning}

1. Salesforce에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-16.png)

1. **개체 관리자**&#x200B;를 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-17.png)

1. 빠른 찾기 상자에 &quot;활동&quot;을 입력합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-18.png)

1. **활동** 레이블을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-19.png)

1. **필드 및 관계**&#x200B;를 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-20.png)

1. **새로 만들기**&#x200B;를 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-21.png)

### Salesforce Lightning의 작업 페이지 레이아웃에 사용자 지정 활동 필드 추가 {#add-custom-activity-field-to-task-page-layout-in-salesforce-lightning}

1. Salesforce에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-22.png)

1. **개체 관리자**&#x200B;를 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-23.png)

1. 빠른 찾기 상자에 &quot;Task&quot;를 입력합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-24.png)

1. **작업** 레이블을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-25.png)

1. **페이지 레이아웃**&#x200B;을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-26.png)

1. 이 필드를 추가하려는 작업 페이지 레이아웃에서 을(를) 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-27.png)

1. 필드를 작업 페이지 레이아웃의 원하는 섹션으로 끌어다 놓습니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-28.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/log-call-reasons-and-call-outcomes-to-salesforce-29.png)

>[!MORELIKETHIS]
>
>[활동 내역에 Sales Connect 이벤트 필드 설치](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/install-sales-connect-event-fields-on-activity-history.md)
