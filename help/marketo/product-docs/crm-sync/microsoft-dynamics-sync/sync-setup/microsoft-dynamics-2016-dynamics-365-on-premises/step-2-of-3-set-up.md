---
description: Microsoft Dynamics 2016/Dynamics 365 온-프레미스 2단계 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 2016/Dynamics 365 온-프레미스 3단계용 Marketo 설치
exl-id: c789b977-7ada-4f5d-8488-e1b58963f7e3
source-git-commit: 3fb93520a653109845c3b40aba20304c6163214f
workflow-type: tm+mt
source-wordcount: '492'
ht-degree: 0%

---

# Dynamics용 Marketo 설정 3단계 중 2단계(2016 On-Prem/Dynamics 365 온-프레미스){#step-of-set-up-for-marketo-on-premises-2016}

이전 단계를 완료하는 데 성공했습니다. 계속 이걸 통과합시다

>[!PREREQUISITES]
>
>[Microsoft Dynamics 2016/Dynamics 365 온-프레미스 3단계용 Marketo 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md)

## 새 사용자 만들기 {#create-a-new-user}

1. Dynamics에 로그인합니다. 설정 아이콘을 클릭하고 고급 설정을 선택합니다.

   ![](assets/step-2-of-3-marketo-on-premises-2016-1.png)

1. 클릭 **설정** 을(를) 선택합니다. **보안**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-2.png)

1. 클릭 **사용자**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-3.png)

1. 클릭 **새로 만들기**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-4.png)

1. 클릭 **사용자 추가 및 라이선스**. 새 탭이 열립니다.

   ![](assets/step-2-of-3-marketo-on-premises-2016-5.png)

1. 클릭 **관리** 를 클릭합니다. 다른 새 탭이 열립니다.

   ![](assets/step-2-of-3-marketo-on-premises-2016-6.png)

1. 클릭 **사용자 추가**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-7.png)

1. 모든 정보를 입력합니다. 완료되면 을(를) 클릭합니다. **추가**.

   ![](assets/step-2-of-3-marketo-on-premises-2016-8.png)

   >[!NOTE]
   >
   >이 이름은 기존 CRM 사용자 계정이 아니라 전용 동기화 사용자여야 합니다. 실제 이메일 주소일 필요는 없습니다.

1. 새 사용자 자격 증명을 받을 이메일을 입력하고 이메일 보내기 를 클릭하고 닫기 를 클릭합니다.

   ![](assets/step-2-of-3-marketo-on-premises-2016-9.png)

## 새 클라이언트 응용 프로그램 만들기 {#create-a-new-client-application}

다음 단계를 수행합니다. [이 Microsoft 문서](https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/development/enabling-oauth-confidential-clients-with-ad-fs#create-an-application-group-in-ad-fs-2016-or-later) 새 클라이언트 응용 프로그램을 만들고 권한을 부여하려면 다음을 수행하십시오. Dynamics 클라이언트 응용 프로그램의 클라이언트 ID/암호를 참고하십시오.

## 동기화 사용자 역할 할당 {#assign-sync-user-role}

Marketo 동기화 사용자 역할만 Marketo 동기화 사용자에게 할당합니다. 다른 사용자에게 할당할 필요가 없습니다.

>[!NOTE]
>
>이는 Marketo 버전 4.0.0.14 이상에 적용됩니다. 이전 버전의 경우 모든 사용자는 동기화 사용자 역할이 있어야 합니다. Marketo을 업그레이드하려면 다음을 참조하십시오 [Microsoft Dynamics용 Marketo 솔루션 업그레이드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
>
>동기화 사용자의 언어 설정 [영어로 설정되어야 함](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us).

1. 아래 **설정**&#x200B;를 클릭합니다. **보안**.

   ![](assets/assign1.png)

1. 클릭 **사용자**.

   ![](assets/assign2.png)

1. 여기에 사용자 목록이 표시됩니다. 전용 Marketo 동기화 사용자를 선택하거나 [Active Directory 페더레이션 서비스](https://msdn.microsoft.com/en-us/library/bb897402.aspx)(ADFS) 관리자가 Marketo용 전용 사용자를 만들 수 있습니다.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. 동기화 사용자를 선택합니다. 클릭 **역할 관리**.

   ![](assets/assign4.png)

   Marketo 동기화 사용자를 선택하고 확인을 클릭합니다.

   ![](assets/assign5.png)

   >[!TIP]
   >
   >역할이 표시되지 않으면 로 돌아갑니다 [3단계 중 1단계](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md) 솔루션을 가져옵니다.

   >[!NOTE]
   >
   >동기화 사용자가 CRM에서 수행한 모든 업데이트 **not** Marketo에 다시 동기화됩니다.

## Marketo 솔루션 구성 {#configure-marketo-solution}

거의 다 됐어! 다음 문서로 이동하기 전에 몇 가지 구성 만 있습니다.

1. 아래 **설정**&#x200B;를 클릭합니다. **Marketo 구성**.

   ![](assets/configure1.png)

   >[!NOTE]
   >
   >Marketo 구성이 누락된 경우 페이지를 새로 고쳐 보십시오. 문제가 계속되면 [Marketo 솔루션 게시](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md) 또는 로그아웃한 후 다시 로그인하십시오.

1. 클릭 **기본값**.

   ![](assets/configure2.png)

1. 을(를) 클릭합니다. **Marketo 사용** 필드를 입력하고 동기화 사용자를 선택합니다.

   ![](assets/configure3.png)

1. 오른쪽 아래 모서리에 있는 저장 아이콘을 클릭합니다.

   ![](assets/configure4.png)

1. 클릭 **모든 사용자 지정 게시**.

   ![](assets/publish-all-customizations1.png)

## 3단계로 진행하기 전 {#before-proceeding-to-step}

* 동기화하는 레코드 수를 제한하려면 [사용자 지정 동기화 필터 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) 지금
* 를 실행합니다. [Microsoft Dynamics 동기화 유효성 검사](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) 프로세스. 초기 설정이 올바르게 수행되었는지 확인합니다.
* Microsoft Dynamics CRM에서 Marketo 동기화 사용자에게 로그인합니다.

>[!MORELIKETHIS]
>
>[Microsoft Dynamics 2016/Dynamics 365 온-프레미스 3단계용 Marketo 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-3-of-3-connect.md)