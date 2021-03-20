---
unique-page-id: 14746470
description: 사용자 지정 배달 채널 설정 - 마케팅 문서 - 제품 설명서
title: 사용자 지정 배달 채널 설정
translation-type: tm+mt
source-git-commit: f3e3efc1cc480e9c6501b7e808f53c3a8bdc93d8
workflow-type: tm+mt
source-wordcount: '397'
ht-degree: 0%

---


# 사용자 지정 배달 채널 {#setting-up-a-custom-delivery-channel} 설정

Marketing To Sales Connect를 사용하면 이메일 배달을 위해 사용자 지정 SMTP 서버와 통합할 수 있습니다. 이 옵션은 Gmail 또는 Exchange 배달 채널에서 대량 이메일을 보내지 않으려는 사용자에게 적합합니다.

사용자가 자신의 개별 사용을 위해 사용자 정의 SMTP 서버를 설정할 수 있고 관리자가 사용자 인스턴스의 모든 Sales Connect 사용자 간에 공유되도록 팀 SMTP를 설정할 수 있습니다.

>[!NOTE]
>
>* SMTP 서버를 설정하는 것 외에도 이메일을 보내기 전에 [이메일 ID를 확인해야 합니다](/help/marketo/product-docs/marketo-sales-connect/getting-started/email-settings/verify-your-email.md).
>* IT 팀 또는 SMTP 서버 공급업체와 협력하여 SMTP 서버에 대한 올바른 서버 자격 증명을 가져오는 것이 좋습니다.
>* SMTP 서버 자격 증명을 사용하여 Gmail 및 Exchange 서버를 연결할 수 없습니다. 이러한 공급자와 통합하려면 Adobe의 이메일 연결 서비스를 사용하십시오.


## 사용자 지정 SMTP {#custom-smtp}

1. [웹 응용 프로그램](https://toutapp.com/login)에 로그인하고 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/setting-up-a-custom-delivery-channel-1.png)

1. 내 계정에서 **이메일 설정**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-2.png)

1. **사용자 지정 배달 채널**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-3.png)

1. SMTP 서버 자격 증명을 입력하고 **Connect**&#x200B;를 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-4.png)

   >[!NOTE]
   >
   >유일한 배달 채널인 경우 모든 이메일 ID에 자동으로 할당되고 여기에 완료됩니다. 이 채널만이 아닌 경우 5단계를 계속 진행하십시오.

1. 이메일 설정에 있는 동안 **주소 및 서명**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-5.png)

1. 배달 채널을 선택할 이메일 ID를 찾고 **배달 채널 선택**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-6.png)

1. 배달 가능 카드에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-7.png)

1. 채널 드롭다운을 클릭하고 방금 추가한 사용자 지정 배달 채널을 선택합니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-8.png)

   >[!NOTE]
   >
   >팀 관리자가 팀 SMTP 서버를 설정하는 경우 기본 이메일 ID에만 자동으로 적용되며 다른 이메일 ID에 대한 옵션으로 사용할 수 있습니다.

## 팀 SMTP 서버 {#team-smtp-server}

>[!NOTE]
>
>**관리자 권한 필요**

1. [웹 응용 프로그램](https://toutapp.com/login)에 로그인하고 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/setting-up-a-custom-delivery-channel-9.png)

1. 관리 설정에서 **일반**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-10.png)

1. **팀 배달 채널**&#x200B;을 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-11.png)

1. SMTP 서버 자격 증명을 입력하고 **Connect**&#x200B;를 클릭합니다.

   ![](assets/setting-up-a-custom-delivery-channel-12.png)

   >[!NOTE]
   >
   >팀 SMTP 서버가 모든 팀 구성원에 대한 기본 이메일 ID의 기본 배달 채널이 됩니다. 또한 다른 모든 이메일 ID에 대한 배달 채널 옵션으로 사용할 수도 있습니다.

   >[!MORELIKETHIS]
   >
   >* [Gmail 사용자를 위한 이메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
      >
      >
   * [Outlook 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)

