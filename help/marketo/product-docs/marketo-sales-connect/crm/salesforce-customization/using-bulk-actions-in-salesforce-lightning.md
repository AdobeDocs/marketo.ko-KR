---
unique-page-id: 42762825
description: Salesforce Lightning에서 일괄 작업 사용 - Marketo 문서 - 제품 설명서
title: Salesforce Lightning에서 일괄 작업 사용
exl-id: 72022507-6568-4cc2-b3b5-c1703a1493ad
feature: Marketo Sales Connect
source-git-commit: 8364c0ebe19bce0d837a96283bea31d593ef4171
workflow-type: tm+mt
source-wordcount: '366'
ht-degree: 0%

---

# [!DNL Salesforce Lightning]에서 일괄 작업 사용 {#using-bulk-actions-in-salesforce-lightning}

[!DNL Salesforce]에서 [!DNL Sales Connect]&#x200B;(으)로 잠재 고객을 푸시하거나 캠페인에 잠재 고객을 추가하거나 대량 이메일을 보내는 등의 대량 작업을 수행하는 방법에 대해 알아봅니다.

>[!PREREQUISITES]
>
>[!DNL Sales Connect] 패키지의 최신 버전으로 업데이트하고 리드/연락처 보기에 일괄 작업 단추를 설치하십시오.
>* [영어로 된 지침] (assets/SF+Guide+for+Lightning-EN)
>* [일본어 지침] (assets/SF+Guide+for+Lightning-JA)

>[!NOTE]
>
>아래 단계를 수행하기 전에 [!DNL Marketo Sales Connect] 계정에 로그인했는지 확인하십시오.

## 벌크 이메일 {#bulk-email}

1. [!DNL Salesforce]에서 **[!UICONTROL Leads]** 탭을 클릭한 다음 원하는 잠재 고객 목록을 선택하십시오.

   ![](assets/one-6.png)

   >[!NOTE]
   >
   >사용 중인 목록에 이미 있는 경우 드롭다운에서 선택하여 다시 실행해야 MSC 일괄 작업 버튼이 표시됩니다. 변경할 수 없는 [!DNL Salesforce] 동작입니다.

1. 화면 오른쪽 끝에 있는 화살표 드롭다운을 클릭하고 **[!UICONTROL Email with MSC]**&#x200B;을(를) 선택합니다.

   ![](assets/two-6.png)

1. MSC 이메일이 표시됩니다. 여기에는 다음 기능이 포함됩니다.

   a. &quot;[!UICONTROL To]&quot; 필드에 &quot;모든 수금&quot;이 표시됩니다. 이 목록은 [가망 고객 목록 보기]에서 선택한 가망 고객 목록에 해당합니다
b. 이 목록은 &quot;일괄 작성&quot;이라는 왼쪽 패널에 표시되며 여기에서 수신자를 추가/제거할 수 있습니다.
c. 템플릿을 선택하거나 직접 이메일을 만들 수 있습니다
d. 이메일을 즉시 보내거나 나중에 보내도록 예약할 수 있습니다

   ![](assets/three-5.png)

## Campaign에 추가 {#add-to-campaign}

1. [!DNL Salesforce]에서 **[!UICONTROL Leads]** 탭을 클릭한 다음 원하는 잠재 고객 목록을 선택하십시오.

   ![](assets/four-4.png)

1. 화면 오른쪽 끝에 있는 화살표 드롭다운을 클릭하고 **[!UICONTROL Add to MSC Campaign]**&#x200B;을(를) 선택합니다.

   ![](assets/five-4.png)

1. &quot;[!UICONTROL Add People to Your Campaign]&quot; 팝업이 나타납니다. **[!UICONTROL Next]**&#x200B;을(를) 클릭하고 일반적인 캠페인 흐름을 통해 MSC 캠페인을 트리거합니다.

   ![](assets/six-1.png)

## [!DNL Marketo Sales Connect]&#x200B;(으)로 푸시 {#push-to-marketo-sales-connect}

1. [!DNL Salesforce]에서 **[!UICONTROL Leads]** 탭을 클릭한 다음 원하는 잠재 고객 목록을 선택하십시오.

   ![](assets/seven-2.png)

1. 화면 오른쪽 끝에 있는 화살표 드롭다운을 클릭하고 **[!UICONTROL Push to MSC]**&#x200B;을(를) 선택합니다.

   ![](assets/eight-2.png)

1. &quot;[!DNL Salesforce] Bridge&quot;라는 새 탭이 열립니다. **[!UICONTROL Proceed to Group]→** 단추를 클릭합니다.

   ![](assets/nine-2.png)

1. MSC 계정으로 전송되면 날짜/타임스탬프로 만든 그룹이 표시됩니다. 동기화가 완료되고 [!DNL Salesforce]에서 동기화된 잠재 고객이 그룹에 포함되면 알림을 받게 됩니다.

   ![](assets/ten-1.png)

>[!NOTE]
>
>동일한 단계에 따라 연락처 목록 보기에서 대량 작업을 사용할 수도 있습니다.

>[!MORELIKETHIS]
>
>* [그룹 전자 메일을 통해 전자 메일 보내기](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/sending-emails-via-group-email.md)
>* [Select 및 Send를 사용하여 일괄 전자 메일 작성](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md#sending-emails)
