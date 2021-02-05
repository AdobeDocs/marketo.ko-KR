---
unique-page-id: 42762825
description: Salesforce Lightning의 일괄 작업 사용 - Marketing To Docs - 제품 설명서
title: Salesforce Lightning에서 일괄 작업 사용
translation-type: tm+mt
source-git-commit: 074701d1a5f75fe592ac7f44cce6fb3571e94710
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 0%

---


# Salesforce Lightning에서 벌크 작업 사용 {#using-bulk-actions-in-salesforce-lightning}

캠페인에 리드 추가, 대량 이메일 전송, Salesforce에서 Sales Connect로 리드 푸시 등 일괄 작업을 수행하는 방법을 알아봅니다.

>[!PREREQUISITES]
>
>최신 버전의 Sales Connect 패키지로 업데이트하고 리드/연락처 보기에 벌크 작업 단추를 설치합니다. [지침을 보려면 여기를 클릭하십시오](http://s3.amazonaws.com/tout-user-store/salesforce/assets/SF+Guide+for+Lightning.pdf).

>[!NOTE]
>
>아래 단계를 수행하기 전에 Marketing To Sales Connect 계정에 로그인되어 있는지 확인하십시오.

## 벌크 이메일 {#bulk-email}

1. Salesforce에서 **리드** 탭을 클릭한 다음 원하는 리드 목록을 선택합니다.

   ![](assets/one-6.png)

   >[!NOTE]
   >
   >사용 중인 목록에 이미 있는 경우 MSC 일괄 작업 단추가 표시되도록 하려면 드롭다운에서 선택하여 다시 실행해야 합니다. 이는 변경할 수 없는 Salesforce 동작입니다.

1. 화살표 드롭다운(화면 오른쪽)을 클릭하고 **MSC가 포함된 이메일**&#x200B;을 선택합니다.

   ![](assets/two-6.png)

1. MSC 이메일이 표시됩니다. 여기에는 다음 기능이 포함됩니다.

   a.&quot;받는 사람&quot; 필드에 &quot;모든 영수증&quot;이 표시됩니다. 이 필드는 리드 목록 보기에서 선택한 리드 목록에 해당합니다\
   b.이 목록은 &quot;대량 작성&quot;이라는 왼쪽 패널에서 볼 수 있습니다. 여기에서 수신자를 추가/제거할 수 있습니다.\
   c. 템플릿을 선택하거나 자신만의 이메일을 만들 수 있습니다.\
   d.이메일을 즉시 보내거나 나중에 보내도록 예약할 수 있습니다

   ![](assets/three-5.png)

## 캠페인 {#add-to-campaign}에 추가

1. Salesforce에서 **리드** 탭을 클릭한 다음 원하는 리드 목록을 선택합니다.

   ![](assets/four-4.png)

1. 화면 맨 오른쪽에 있는 화살표 드롭다운을 클릭하고 **MSC 캠페인에 추가**&#x200B;를 선택합니다.

   ![](assets/five-4.png)

1. &quot;캠페인에 사람 추가&quot; 팝업이 표시됩니다. **다음**&#x200B;을 클릭하고 일반적인 캠페인 흐름을 통해 MSC 캠페인을 트리거합니다.

   ![](assets/six-1.png)

## Marketing To Sales Connect {#push-to-marketo-sales-connect}

1. Salesforce에서 **리드** 탭을 클릭한 다음 원하는 리드 목록을 선택합니다.

   ![](assets/seven-2.png)

1. 화면 맨 오른쪽에 있는 화살표 드롭다운을 클릭하고 **MSC로 푸시**&#x200B;를 선택합니다.

   ![](assets/eight-2.png)

1. &quot;Salesforce Bridge&quot;라는 새 탭이 열립니다. **그룹→ 계속** 단추를 클릭합니다.

   ![](assets/nine-2.png)

1. MSC 계정으로 전송되어 날짜/시간 스탬프로 만든 그룹이 표시됩니다. 동기화가 완료되면 알림이 수신되고 Salesforce에서 동기화된 리드가 그룹에 포함됩니다.

   ![](assets/ten-1.png)

>[!NOTE]
>
>연락처 목록 보기에서도 동일한 단계를 수행하여 일괄 작업을 사용할 수 있습니다.

>[!MORELIKETHIS]
>
>* [그룹 이메일을 통해 이메일 보내기](http://docs.marketo.com/x/KAQ6Ag)
>* [선택 및 전송을 사용하여 일괄 이메일 작성](http://docs.marketo.com/display/public/DOCS/Composing+Bulk+Emails+with+Select+and+Send#ComposingBulkEmailswithSelectandSend-SendingEmails)

>



