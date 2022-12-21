---
description: 4단계 중 3단계 - MS Dynamics에서 클라이언트 앱 설정 - Marketo 문서 - 제품 설명서
title: 4단계 중 3단계 - MS Dynamics에서 클라이언트 앱 설정
exl-id: e7897174-3303-4c3b-8832-3e10f34fca96
source-git-commit: 0b9a1f50d8828acf019c5c4f82021d327f396fca
workflow-type: tm+mt
source-wordcount: '354'
ht-degree: 0%

---

# 4단계 중 3단계: MS Dynamics에서 클라이언트 앱 설정 {#step-3-of-4-set-up-client-app-ms-dynamics-ropc}

>[!PREREQUISITES]
>
>* [4단계 중 1단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md)
>* [4단계 중 2단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md)


1. https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory#create-an-application-registration으로 이동합니다.

1. 모든 단계를 수행합니다. 3단계의 경우 관련 애플리케이션 이름(예: &quot;Marketo 통합&quot;)을 입력합니다. 지원되는 계정 유형에서 이 조직 디렉터리에서만 계정을 선택합니다.

1. 응용 프로그램 ID(ClientId)를 기록합니다. 나중에 Marketo에 입력해야 합니다.

1. 의 단계에 따라 관리자 동의 부여 [이 문서](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md).

1. 관리 센터에서 클라이언트 암호 생성 **인증서 및 기밀**.

   ![](assets/step-3-of-4-set-up-client-app-ms-dynamics-ropc-1.png)

1. 클릭 **새 클라이언트 암호**.

   ![](assets/step-3-of-4-set-up-client-app-ms-dynamics-ropc-2.png)

1. 클라이언트 암호 설명을 추가하고 **추가**.

   ![](assets/step-3-of-4-set-up-client-app-ms-dynamics-ropc-3.png)

   >[!CAUTION]
   >
   >나중에 필요하므로 클라이언트 암호 값(아래 스크린샷에 표시됨)을 반드시 기록하십시오. 한 번만 표시되므로 다시 검색할 수 없습니다.

   ![](assets/step-3-of-4-set-up-client-app-ms-dynamics-ropc-4.png)

## AD FS On-prem을 사용하여 Azure AD Federated {#azure-ad-federated-with-ad-fs-on-prem}

ADFS Onprem에 대한 Federated Azure AD는 특정 응용 프로그램에 대한 홈 영역 검색 정책을 만들어야 합니다. 이 정책을 사용하면 Azure AD에서 인증 요청을 페더레이션 서비스로 리디렉션합니다. 이를 위해서는 AD Connect에서 암호 해시 동기화를 활성화해야 합니다. 자세한 내용은 [ROPC가 있는 OAuth](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth-ropc) 및 [응용 프로그램에 대한 세 번째 정책 설정](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/configure-authentication-for-federated-users-portal#example-set-an-hrd-policy-for-an-application).

추가 참조 [여기에서 찾을 수 있습니다.](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-all-sign-ins#:~:text=Interactive%20user%20sign%2Dins%20are,as%20the%20Microsoft%20Authenticator%20app.&amp;text=이%20report%20also%20includes%20federated,are%20federated%20to%20Azure%20AD.).

## 4단계로 진행하기 전 {#before-proceeding-to-step-4}

* 동기화하는 레코드 수를 제한하려면 [사용자 지정 동기화 필터 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) 지금
* 를 실행합니다. [Microsoft Dynamics 동기화 유효성 검사](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) 프로세스. 초기 설정이 올바르게 수행되었는지 확인합니다.
* Microsoft Dynamics CRM에서 Marketo 동기화 사용자에게 로그인합니다.

>[!MORELIKETHIS]
>
>* [4단계 중 4단계: 리소스 소유자 암호 제어 연결과 Marketo 솔루션 연결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md)

