---
unique-page-id: 42762794
description: Salesforce Classic에서 벌크 작업 사용 - Marketo 문서 - 제품 설명서
title: Salesforce Classic에서 벌크 작업 사용
exl-id: f676ba65-6bc9-41e5-aa70-0f10bceedab7
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '372'
ht-degree: 0%

---

# Salesforce Classic에서 벌크 작업 사용 {#using-bulk-actions-in-salesforce-classic}

캠페인에 리드 추가, 대량 이메일 전송 또는 Salesforce에서 Sales Connect로 리드 푸시와 같은 대량 작업을 수행하는 방법을 알아봅니다.

>[!PREREQUISITES]
>
>최신 버전의 Sales Connect 패키지로 업데이트하고 리드/연락처 보기에 대량 작업 버튼을 설치합니다. [지침을 보려면 여기를 클릭하십시오.](https://s3.amazonaws.com/tout-user-store/salesforce/assets/Marketo+Sales+Engage+For+Salesforce_+Installation+and+Success+Guide.pdf).

>[!NOTE]
>
>요약된 단계를 따르려면 먼저 Marketo Sales Connect 계정에 로그인했는지 확인합니다.

## 대량 이메일 {#bulk-email}

1. Salesforce에서 **리드** 탭을 클릭한 다음 **이동** 버튼을 클릭합니다.

   ![](assets/one-5.png)

1. 원하는 리드를 선택하고 **MSC를 사용한 이메일(클래식)** 버튼을 클릭합니다.

   ![](assets/two-5.png)

1. MSC 이메일이 나타납니다. 여기에는 다음 기능이 포함됩니다.

   a. 받는 사람 필드에 &quot;모든 영수증&quot;이 표시됩니다. 이는 리드 목록 보기에서 선택한 리드 목록에 해당합니다\
   나. 이 목록은 &quot;대량 작성&quot;이라는 왼쪽 패널에 표시됩니다. 여기에서 수신자를 추가/제거할 수 있습니다\
   c. 템플릿을 선택하거나 고유한 이메일을 만들 수 있습니다\
   d. 이메일에 채울 동적 필드를 미리 볼 수 있습니다\
   e. 즉시 이메일을 보내거나 나중에 보내도록 예약할 수 있습니다

   ![](assets/three-4.png)

## Campaign에 추가 {#add-to-campaign}

1. Salesforce에서 **리드** 탭을 클릭한 다음 **이동** 버튼을 클릭합니다.

   ![](assets/four-3.png)

1. 원하는 리드를 선택하고 **MSC Campaign에 추가(Classic)** 버튼을 클릭합니다.

   ![](assets/five-3.png)

1. 캠페인에 사람 추가 팝업이 나타납니다. 클릭 **다음** 일반적인 캠페인 플로우를 통해 MSC 캠페인을 트리거합니다.

   ![](assets/six.png)

## Marketo Sales Connect로 푸시 {#push-to-marketo-sales-connect}

1. Salesforce에서 **리드** 탭을 클릭한 다음 **이동** 버튼을 클릭합니다.

   ![](assets/seven-1.png)

1. 원하는 리드를 선택하고 **MSC에 푸시(클래식)** 버튼을 클릭합니다.

   ![](assets/eight-1.png)

1. &quot;Salesforce Bridge&quot;라는 새 탭이 열립니다. 을(를) 클릭합니다. **그룹으로 →** 버튼을 클릭합니다.

   ![](assets/nine-1.png)

1. MSC 계정으로 전송되며, 여기에서 날짜/타임스탬프를 사용하여 만든 그룹이 표시됩니다. 동기화가 완료되고 Salesforce에서 동기화된 리드가 그룹에 포함되면 알림을 받게 됩니다.

   ![](assets/ten.png)

>[!NOTE]
>
>동일한 단계에 따라 연락처 목록 보기에서 대량 작업을 사용할 수도 있습니다.

>[!MORELIKETHIS]
>
>* [그룹 이메일을 통해 이메일 보내기](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/sending-emails-via-group-email.md)
>* [선택 및 보내기로 대량 이메일 작성](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md#sending-emails)

