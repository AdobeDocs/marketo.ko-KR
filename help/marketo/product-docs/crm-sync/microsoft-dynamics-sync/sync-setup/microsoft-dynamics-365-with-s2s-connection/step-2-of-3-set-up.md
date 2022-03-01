---
unique-page-id: 3571827
description: 3단계 중 2단계 - 서버 연결 시 Marketo 솔루션 설정 - Marketo 문서 - 제품 설명서
title: 3단계 중 2단계 - 서버 간 연결을 사용하여 Marketo 솔루션 설정
exl-id: 324e2142-2aa2-4548-9a04-683832e3ba69
source-git-commit: 48b8289994e000eafd72982ac1b4a0a809b10bab
workflow-type: tm+mt
source-wordcount: '643'
ht-degree: 0%

---

# 3단계 중 2단계: 서버 간 연결을 사용하여 Marketo 솔루션 설정 {#step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s}

>[!PREREQUISITES]
>
>[3단계 중 1단계: 서버 간 연결과 함께 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md)

## Azure AD에서 클라이언트 응용 프로그램 만들기 {#create-client-application-in-azure-ad}

1. 다음으로 이동 [이 Microsoft 문서](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory#create-an-application-registration).

1. 모든 단계를 수행합니다. 3단계의 경우 관련 애플리케이션 이름(예: &quot;Marketo 통합&quot;)을 입력합니다. 지원되는 계정 유형에서 **이 조직 디렉터리의 계정만**.

1. 애플리케이션 ID(ClientId) 및 테넌트 ID를 기록합니다. 나중에 Marketo에 입력해야 합니다.

1. 단계에 따라 관리자 동의 부여 [이 문서](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md).

1. 관리 센터에서 클라이언트 암호 생성 **인증서 및 기밀**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-1.png)

1. 을(를) 클릭합니다. **새 클라이언트 암호** 버튼을 클릭합니다.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-2.png)

1. 클라이언트 암호 설명을 입력하고 **추가**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-3.png)

>[!CAUTION]
>
>나중에 필요하므로 클라이언트 암호 값(아래 스크린샷에 표시됨)을 반드시 기록하십시오. 한 번만 표시되므로 다시 검색할 수 없습니다.

![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-4.png)

## Microsoft에서 애플리케이션 사용자 만들기 {#create-application-user-in-microsoft}

1. 다음 링크에서 다음 절차를 따르십시오. [Microsoft에서 애플리케이션 사용자 설정](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/use-single-tenant-server-server-authentication#application-user-creation).

   >[!IMPORTANT]
   >
   >* 애플리케이션 사용자에게 권한을 부여하는 동안 이 권한을 &quot;Marketo 동기화 사용자 역할&quot;에 할당하십시오.
   >* Application User의 이메일 주소를 [세부 정보 보기 옵션](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user) 전원 플랫폼에 있습니다. 이 이메일 주소는 Marketo 내에서 MS Dynamics 연결을 설정할 때 사용자 이름으로 사용됩니다.


## AD FS On-prem을 사용하여 Azure AD Federated {#azure-ad-federated-with-ad-fs-on-prem}

ADFS Onprem에 대한 Federated Azure AD는 특정 응용 프로그램에 대한 홈 영역 검색 정책을 만들어야 합니다. 이 정책을 사용하면 Azure AD에서 인증 요청을 페더레이션 서비스로 리디렉션합니다. 이를 위해서는 AD Connect에서 암호 해시 동기화를 활성화해야 합니다. 자세한 내용은 [ROPC가 있는 OAuth](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth-ropc) 및 [응용 프로그램에 대한 세 번째 정책 설정](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/configure-authentication-for-federated-users-portal#example-set-an-hrd-policy-for-an-application).

추가 참조 [여기에서 찾을 수 있습니다.](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-all-sign-ins#:~:text=Interactive%20user%20sign%2Dins%20are,as%20the%20Microsoft%20Authenticator%20app.&amp;text=이%20report%20also%20includes%20federated,are%20federated%20to%20Azure%20AD.).

## Marketo 솔루션 구성 {#configure-marketo-solution}

거의 다 왔어! 새로 만든 사용자에 대해 Marketo Solution에 알려기만 하면 됩니다.

>[!IMPORTANT]
>
>기본 인증에서 OAuth로 업그레이드하는 경우 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support) 추가 매개 변수 업데이트에 대한 도움말을 참조하십시오. 기본 동기화 사용자에 대한 구성 변경을 수행하면 새 자격 증명을 입력하고 동기화를 다시 사용할 수 있을 때까지 동기화가 일시적으로 중지됩니다. 요청이 있을 때, Marketo 지원에서 이전 인증 방법으로 되돌리려면 기능을 비활성화(2022년 4월까지)할 수 있습니다.

1. 고급 설정 섹션으로 돌아가서 ![](assets/image2015-5-13-15-3a49-3a19.png) 설정 옆에 있는 아이콘을 선택하고 **Marketo 구성**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >표시되지 않으면 **Marketo 구성** 설정 메뉴에서 페이지를 새로 고칩니다. 효과가 없으면, [Marketo 솔루션 게시](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md) 다시 시도하거나 로그아웃했다가 다시 로그인하십시오.

1. 클릭 **기본값**.

   ![](assets/fifteen.png)

1. 에서 검색 단추를 클릭합니다. **Marketo 사용** 필드를 입력하고 만든 동기화 사용자를 선택합니다.

   ![](assets/sixteen.png)

1. 을(를) 클릭합니다. ![](assets/image2015-3-13-15-3a10-3a11.png) 오른쪽 아래 모서리에 있는 아이콘을 사용하여 변경 사항을 저장합니다.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. 을(를) 클릭합니다. **X** 오른쪽 상단에서 화면을 닫습니다.

   ![](assets/seventeen.png)

1. 을(를) 클릭합니다. ![](assets/image2015-5-13-15-3a49-3a19-1.png) 설정 옆에 있는 아이콘을 선택하고 **솔루션**.

   ![](assets/eighteen.png)

1. 을(를) 클릭합니다. **모든 사용자 지정 게시** 버튼을 클릭합니다.

   ![](assets/nineteen.png)

## 3단계로 진행하기 전 {#before-proceeding-to-step}

* 동기화하는 레코드 수를 제한하려면 [사용자 지정 동기화 필터 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) 지금
* 를 실행합니다. [Microsoft Dynamics 동기화 유효성 검사](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) 프로세스. 초기 설정이 올바르게 수행되었는지 확인합니다.
* Microsoft Dynamics CRM에서 Marketo 동기화 사용자에게 로그인합니다.

>[!MORELIKETHIS]
>
>* [3단계 중 3단계: Marketo 솔루션을 서버와 서버 연결 연결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-3-of-3-connect.md)
>* [Dynamics 인증 메서드 다시 구성](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md)

