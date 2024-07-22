---
unique-page-id: 14746470
description: 사용자 지정 게재 채널 설정 - Marketo 문서 - 제품 설명서
title: 사용자 지정 게재 채널 설정
exl-id: a31f7bfd-a4ee-4948-9bdc-b49d47054d40
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '394'
ht-degree: 0%

---

# 사용자 지정 게재 채널 설정 {#setting-up-a-custom-delivery-channel}

Marketo Sales Connect를 통해 사용자 정의 SMTP 서버와 통합하여 이메일을 전송할 수 있습니다. 이는 Gmail 또는 Exchange 게재 채널에서 대량 이메일을 보내고 싶지 않은 사용자에게 유용한 옵션입니다.

사용자는 자신의 개인 사용에 대한 사용자 정의 SMTP 서버를 설정하거나 관리자는 인스턴스의 모든 Sales Connect 사용자 간에 공유되도록 팀 SMTP를 설정할 수 있습니다.

>[!NOTE]
>
>* SMTP 서버 설정 외에 전자 메일을 보내려면 먼저 [전자 메일 ID를 확인](/help/marketo/product-docs/marketo-sales-connect/getting-started/email-settings/verify-your-email.md)해야 합니다.
>* SMTP 서버에 대한 올바른 서버 자격 증명을 얻기 위해 IT 팀 또는 SMTP 서버 공급업체와 협력하는 것이 좋습니다.
>* SMTP 서버 자격 증명을 사용하여 Gmail 및 Exchange 서버를 연결할 수 없습니다. 이러한 공급자와 통합하려면 이메일 연결 서비스를 사용하십시오.

## 사용자 정의 SMTP {#custom-smtp}

1. [웹 응용 프로그램](https://toutapp.com/login)에 로그인하고 오른쪽 상단의 톱니바퀴 아이콘을 클릭한 다음 **설정**&#x200B;을 선택합니다.

   ![](assets/setting-up-a-custom-delivery-channel-1.png)

1. 내 계정에서 **전자 메일 설정**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-2.png)

1. **사용자 지정 배달 채널**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-3.png)

1. SMTP 서버 자격 증명을 입력하고 **연결**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-4.png)

   >[!NOTE]
   >
   >이 채널이 유일한 게재 채널인 경우 모든 이메일 ID에 자동으로 할당되고 여기에서 완료됩니다. 유일한 게재 채널이 아닌 경우 5단계로 진행하십시오.

1. 전자 메일 설정에서 **주소 및 서명**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-5.png)

1. 배달 채널을 선택할 전자 메일 ID를 찾아 **배달 채널 선택**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-6.png)

1. 게재 기능 카드에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-7.png)

1. 채널 드롭다운을 클릭하고 방금 추가한 사용자 지정 게재 채널을 선택합니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-8.png)

   >[!NOTE]
   >
   >팀 관리자가 팀 SMTP 서버를 설정하면 기본 전자 메일 ID에만 자동으로 적용되고 다른 전자 메일 ID에 대한 옵션으로 사용할 수 있습니다.

## 팀 SMTP 서버 {#team-smtp-server}

>[!NOTE]
>
>**관리자 권한 필요**

1. [웹 응용 프로그램](https://toutapp.com/login)에 로그인하고 오른쪽 상단의 톱니바퀴 아이콘을 클릭한 다음 **설정**&#x200B;을 선택합니다.

   ![](assets/setting-up-a-custom-delivery-channel-9.png)

1. 관리자 설정에서 **일반**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-10.png)

1. **팀 배달 채널**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-11.png)

1. SMTP 서버 자격 증명을 입력하고 **연결**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-12.png)

   >[!NOTE]
   >
   >팀 SMTP 서버는 모든 팀 구성원에 대한 기본 전자 메일 ID의 기본 배달 채널이 됩니다. 또한 다른 모든 이메일 ID에 대한 게재 채널 옵션으로 사용할 수 있습니다.

   >[!MORELIKETHIS]
   >
   >* [Gmail 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
   >
   >* [Outlook 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
