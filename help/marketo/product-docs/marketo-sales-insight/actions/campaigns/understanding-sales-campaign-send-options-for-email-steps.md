---
description: 이메일 단계에 대한 판매 캠페인 전송 옵션 이해 - Marketo 문서 - 제품 설명서
title: 이메일 단계에 대한 판매 캠페인 전송 옵션 이해
feature: Sales Insight Actions
exl-id: 775c6401-efb2-4940-a81c-be5d2759c7bd
source-git-commit: 832635c9e029754ce094e4137724bcc956dbcd35
workflow-type: tm+mt
source-wordcount: '750'
ht-degree: 0%

---

# 이메일 단계에 대한 판매 캠페인 전송 옵션 이해 {#understanding-sales-campaign-send-options-for-email-steps}

Sales Campaign 을 생성할 때 Sales Insight Actions에서 이메일 단계를 생성하는 방법에 대한 몇 가지 옵션이 있습니다. 또한 Sales Campaign에서 이메일이 어디에 포함되는지에 따라 옵션도 달라집니다.

## 첫 번째 단계 전송 옵션 {#first-step-send-options}

첫 번째 단계이고 Sales Campaign 첫 번째 날인 경우 다음과 같은 옵션을 사용할 수 있습니다.

![](assets/understanding-sales-campaign-send-options-for-email-steps-1.png)

### 이 이메일을 보낼 시기를 선택합니다. {#first-step-i-will-choose}

* 이 옵션을 사용하면 사람을 추가하여 판매 캠페인을 시작할 때 판매 캠페인에서 첫 번째 이메일에 대해 &quot;전송 시간&quot;을 선택할 수 있습니다.

### 다음 시간에 이 이메일 보내기 {#first-step-following-time}

* Sales Campaign에 사람을 추가하여 시작하면 이 시간으로 이메일을 예약합니다.
* 판매 캠페인을 시작할 때 항상 새로운 &quot;전송 시간&quot;을 선택할 수 있습니다.

### 작업을 만듭니다. 이 전자 메일을 직접 보내겠습니다. {#first-step-create-a-task}

* 이 옵션을 사용하면 편한 시간에 보낼 수 있는 이메일 작업(및 Salesforce과 동기화)이 만들어집니다.
* 이 옵션을 선택하면 Sales Campaign을 시작할 때 명령 센터 및 라이브 피드에 해당 작업이 대기열에 추가됩니다. 그런 다음 각 이메일이 발송되기 전에 개인화하고 전송(또는 예약)할 수 있습니다.

   * 웹 애플리케이션에서 이 작업을 열면 연락처의 이메일 주소, 이메일의 제목 줄 및 선택한 템플릿이 있는 작성 창이 열립니다.
   * Gmail 또는 Outlook에서 이 작업을 열면 기본 작성 창이 열리고 연락처 전자 메일 주소, 전자 메일의 제목 줄 및 선택한 템플릿이 동적으로 채워집니다.

## 후속 단계 전송 옵션 {#subsequent-step-send-options}

Sales Campaign의 이후 며칠/단계에서는 다음과 같은 옵션을 사용할 수 있습니다.

### 이 Sales Campaign의 이전 이메일과 동시에 이 이메일 보내기 {#subsequent-send-at-same-time}

* 이 옵션은 바로 전의 이메일과 동시에 이메일을 전송합니다.
* 연결된 날짜에 계속 전송됩니다.

>[!IMPORTANT]
>
>같은 날 전송된 이메일에는 이전 이메일과 동시에 이메일을 보내는 것이 지원되지 않습니다. 대신 전날부터 전송된 시점에 이메일이 발송된다. 캠페인의 첫날 이메일에 대해 이 옵션을 선택하면(권장되지 않음) 캠페인 시작 시 해당 이메일이 즉시 전송됩니다.

### 다음 시간에 이 이메일 보내기 {#subsequent-send-at-following-time}

* Sales Campaign에 사람을 추가하여 시작하면 이 시간으로 이메일을 예약합니다.
* 판매 캠페인을 시작할 때 항상 새로운 &quot;전송 시간&quot;을 선택할 수 있습니다.

### 작업을 만듭니다. 이 전자 메일을 직접 보내겠습니다. {#subsequent-create-a-task}

* 이 옵션을 사용하면 편한 시간에 보낼 수 있는 이메일 작업(및 Salesforce과 동기화)이 만들어집니다.
* 이 옵션을 선택하면 Sales Campaign을 시작할 때 Sales Insight Actions에서 이러한 작업을 명령 센터 및 라이브 피드에 큐에 추가합니다. 그런 다음 각 이메일이 발송되기 전에 개인화하고 전송(또는 예약)할 수 있습니다.

   * 웹 애플리케이션에서 이 작업을 열면 연락처의 이메일 주소, 이메일의 제목 줄 및 선택한 템플릿이 있는 작성 창이 열립니다.
   * Gmail 또는 Outlook에서 이 작업을 열면 기본 작성 창이 열리고 연락처 전자 메일 주소, 전자 메일의 제목 줄 및 선택한 템플릿이 동적으로 채워집니다.

### 이 캠페인의 이전 이메일에 대한 후속 작업으로 이 이메일 만들기 {#subsequent-create-this-email}

* 판매 캠페인의 이전 이메일을 판매 캠페인이 발송하는 다음 이메일에 추가하려면 이 확인란을 활성화합니다.
* 추가된 이메일 사본의 경우 판매 캠페인의 이메일 템플릿이 항상 전송됩니다. 전송되기 전에 사용자가 편집한 내용은 전송에 포함되지 않습니다.

>[!NOTE]
>
>후속 작업으로 이메일을 만드는 이 옵션은 이전 단계도 이메일인 경우 이메일 단계에서만 사용할 수 있습니다. 이전 단계가 호출, InMail 또는 사용자 지정인 경우 후속 작업을 만드는 옵션이 표시되지 않습니다.

>[!MORELIKETHIS]
>
>[판매 캠페인 만들기](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/create-a-sales-campaign.md){target="_blank"}
>[판매 캠페인 단계 유형 및 미리 알림 작업](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/sales-campaign-step-types-and-reminder-tasks.md){target="_blank"}
>[판매 캠페인 설정](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/sales-campaign-settings.md){target="_blank"}

