---
description: 사용자 지정 게재 채널 설정 - Marketo 문서 - 제품 설명서
title: 사용자 지정 게재 채널 설정
hide: true
hidefromtoc: true
source-git-commit: 55afdc537d0a5d0b6114f478c4dd2ded09c84e34
workflow-type: tm+mt
source-wordcount: '409'
ht-degree: 0%

---

# 사용자 지정 게재 채널 설정 {#setting-up-a-custom-delivery-channel}

Marketo Sales Connect를 사용하면 전자 메일 배달을 위해 사용자 지정 SMTP 서버와 통합할 수 있습니다. Gmail 또는 Exchange 게재 채널에서 벌크 이메일을 보내지 않으려는 사용자에게 이 옵션이 적합합니다.

사용자는 자신의 개별 사용을 위해 사용자 지정 SMTP 서버를 설정하거나 관리자는 인스턴스의 모든 Sales Connect 사용자 간에 공유하도록 팀 SMTP를 설정할 수 있습니다.

>[!NOTE]
>
>* SMTP 서버를 설정할 뿐만 아니라 [이메일 ID를 확인해야 함](/help/marketo/product-docs/marketo-sales-connect/getting-started/email-settings/verify-your-email.md) 전자 메일을 보내기 전에
>* IT 팀이나 SMTP 서버 공급업체와 협력하여 SMTP 서버에 대한 올바른 서버 자격 증명을 받는 것이 좋습니다.
>* SMTP 서버 자격 증명을 사용하여 Gmail 및 Exchange 서버를 연결할 수 없습니다. 전자 메일 연결 서비스를 사용하여 이러한 공급자와 통합하십시오.


## 사용자 지정 SMTP {#custom-smtp}

1. 에 로그인합니다. [웹 애플리케이션](https://toutapp.com/login)오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

PICC

1. 내 계정에서 **전자 메일 설정**.

PICC

1. 클릭 **사용자 지정 게재 채널**.

PICC

1. SMTP 서버 자격 증명을 입력하고 **Connect**.

PICC

>[!NOTE]
>
>유일한 게재 채널인 경우 모든 이메일 ID에 자동으로 할당되며 여기에서 수행합니다. 유일한 게재 채널이 아닌 경우 5단계로 이동하십시오.

1. 전자 메일 설정에 있는 동안 **주소 및 서명**.

PICC

1. 게재 채널을 선택할 이메일 ID를 찾아 **배달 채널 선택**.

PICC

1. 게재 가능성 카드에서 **편집**.

PICC

1. 채널 드롭다운을 클릭하고 방금 추가한 사용자 지정 게재 채널을 선택합니다. 클릭 **저장**.

PICC

>[!NOTE]
>
>팀 관리자가 팀 SMTP 서버를 설정하면 기본 전자 메일 ID에만 자동으로 적용되며 다른 전자 메일 ID에 대한 옵션으로 사용할 수 있습니다.

## 팀 SMTP 서버 {#team-smtp-server}

>[!NOTE]
>
>**관리 권한 필요**

1. 에 로그인합니다. [웹 애플리케이션](https://toutapp.com/login)오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

PICC

1. 관리자 설정에서 을 클릭합니다. **일반**.

PICC

1. 클릭 **팀 전달 채널**.

PICC

1. SMTP 서버 자격 증명을 입력하고 **Connect**.

PICC

>[!NOTE]
>
>팀 SMTP 서버는 모든 팀 구성원에 대한 기본 전자 메일 ID의 기본 배달 채널입니다. 또한 다른 모든 이메일 ID에 대한 게재 채널 옵션으로 사용할 수 있습니다.

>[!MORELIKETHIS]
>
>* [Gmail 사용자를 위한 이메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [Outlook 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)

