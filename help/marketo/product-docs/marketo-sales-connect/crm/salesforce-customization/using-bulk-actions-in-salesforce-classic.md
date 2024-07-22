---
unique-page-id: 42762794
description: Salesforce Classic - Marketo 문서 - 제품 설명서에서 대량 작업 사용
title: Salesforce Classic에서 일괄 작업 사용
exl-id: f676ba65-6bc9-41e5-aa70-0f10bceedab7
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '358'
ht-degree: 0%

---

# Salesforce Classic에서 일괄 작업 사용 {#using-bulk-actions-in-salesforce-classic}

캠페인에 잠재 고객을 추가하거나 벌크 이메일을 보내거나 Salesforce에서 Sales Connect로 잠재 고객을 푸시하는 등의 대량 작업을 수행하는 방법에 대해 알아봅니다.

>[!PREREQUISITES]
>
>Sales Connect 패키지의 최신 버전으로 업데이트하고 리드/연락처 보기에 일괄 작업 버튼을 설치합니다. [지침을 보려면 여기를 클릭하세요](https://s3.amazonaws.com/tout-user-store/salesforce/assets/Marketo+Sales+Engage+For+Salesforce_+Installation+and+Success+Guide.pdf).

>[!NOTE]
>
>설명된 단계를 수행하기 전에 Marketo Sales Connect 계정에 로그인되어 있는지 확인하십시오.

## 벌크 이메일 {#bulk-email}

1. Salesforce에서 **리드** 탭을 클릭한 다음 **이동** 단추를 클릭합니다.

   ![](assets/one-5.png)

1. 원하는 리드를 선택하고 **MSC로 전자 메일 보내기(클래식)** 단추를 클릭합니다.

   ![](assets/two-5.png)

1. MSC 이메일이 표시됩니다. 여기에는 다음 기능이 포함됩니다.

   a. &quot;종료&quot; 필드에는 &quot;모든 입고&quot;가 표시됩니다. 이 수금은 가망 고객 목록 보기에서 선택한 가망 고객 목록에 해당합니다\
   b. 이 목록은 &quot;일괄 작성&quot;이라는 왼쪽 패널에 표시되며 여기에서 수신자를 추가/제거할 수 있습니다.\
   c. 템플릿을 선택하거나 직접 이메일을 만들 수 있습니다\
   d. 이메일에 채워질 동적 필드를 미리 볼 수 있습니다\
   e. 이메일을 즉시 보내거나 나중에 보내도록 예약할 수 있습니다

   ![](assets/three-4.png)

## Campaign에 추가 {#add-to-campaign}

1. Salesforce에서 **리드** 탭을 클릭한 다음 **이동** 단추를 클릭합니다.

   ![](assets/four-3.png)

1. 원하는 리드를 선택하고 **MSC 캠페인에 추가(클래식)** 단추를 클릭합니다.

   ![](assets/five-3.png)

1. &quot;캠페인에 사용자 추가&quot; 팝업이 나타납니다. **다음**&#x200B;을 클릭하고 일반적인 캠페인 흐름을 통해 MSC 캠페인을 트리거합니다.

   ![](assets/six.png)

## Marketo Sales Connect로 푸시 {#push-to-marketo-sales-connect}

1. Salesforce에서 **리드** 탭을 클릭한 다음 **이동** 단추를 클릭합니다.

   ![](assets/seven-1.png)

1. 원하는 리드를 선택하고 **MSC로 푸시(클래식)** 단추를 클릭합니다.

   ![](assets/eight-1.png)

1. &quot;Salesforce Bridge&quot;라는 새 탭이 열립니다. **그룹 →** 진행 단추를 클릭합니다.

   ![](assets/nine-1.png)

1. MSC 계정으로 전송되면 날짜/타임스탬프로 만든 그룹이 표시됩니다. 동기화가 완료되고 그룹에 Salesforce에서 동기화된 잠재 고객이 포함되면 알림을 받게 됩니다.

   ![](assets/ten.png)

>[!NOTE]
>
>동일한 단계에 따라 연락처 목록 보기에서 대량 작업을 사용할 수도 있습니다.

>[!MORELIKETHIS]
>
>* [그룹 전자 메일을 통해 전자 메일 보내기](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/sending-emails-via-group-email.md)
>* [Select 및 Send를 사용하여 일괄 전자 메일 작성](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md#sending-emails)
