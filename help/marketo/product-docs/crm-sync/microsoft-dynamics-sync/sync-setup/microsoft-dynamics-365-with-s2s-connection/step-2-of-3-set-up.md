---
unique-page-id: 3571827
description: 2단계/3단계 - 서버 간 연결을 통해 Marketo 솔루션 설정 - Marketo 문서 - 제품 설명서
title: 2/3단계 - 서버 간 연결을 통해 Marketo 솔루션 설정
exl-id: 324e2142-2aa2-4548-9a04-683832e3ba69
feature: Microsoft Dynamics
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '598'
ht-degree: 0%

---

# 2단계/3단계: 서버 간 연결을 통해 Marketo 솔루션 설정 {#step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s}

>[!PREREQUISITES]
>
>[1/3단계: 서버 간 연결을 통해 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md){target="_blank"}

## Azure AD에서 클라이언트 응용 프로그램 만들기 {#create-client-application-in-azure-ad}

1. 다음으로 이동 [이 Microsoft 문서](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory#create-an-application-registration){target="_blank"}.

1. 모든 단계를 따르십시오. 3단계의 경우 관련 애플리케이션 이름(예: &quot;Marketo 통합&quot;)을 입력합니다. 지원되는 계정 유형에서 다음을 선택합니다. **이 조직 디렉터리의 계정만 해당**.

1. 애플리케이션 ID(ClientId) 및 테넌트 ID를 기록합니다. 나중에 Marketo에서 입력해야 합니다.

1. 단계에 따라 관리자 동의 부여 [이 문서에서](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md){target="_blank"}.

1. 다음을 클릭하여 관리 센터에서 클라이언트 암호 생성 **[!UICONTROL 인증서 및 암호]**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-1.png)

1. 다음을 클릭합니다. **[!UICONTROL 새 클라이언트 암호]** 단추를 클릭합니다.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-2.png)

1. 클라이언트 암호 설명을 입력하고 **[!UICONTROL 추가]**.

   ![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-3.png)

>[!CAUTION]
>
>클라이언트 암호 값(아래 스크린샷에 표시됨)은 나중에 필요하므로 기록해 두십시오. 한 번만 표시되며 다시 검색할 수 없습니다.

![](assets/step-2-of-3-set-up-marketo-sync-user-in-dynamics-s2s-4.png)

## Microsoft에서 애플리케이션 사용자 만들기 {#create-application-user-in-microsoft}

1. 다음 링크에서 다음 단계를 수행합니다. [Microsoft에서 애플리케이션 사용자 설정](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/use-single-tenant-server-server-authentication#application-user-creation){target="_blank"}.

   >[!IMPORTANT]
   >
   >* 애플리케이션 사용자에게 권한을 부여하는 동안 &quot;Marketo 동기화 사용자 역할&quot;에 할당해야 합니다.
   >* 에서 애플리케이션 사용자의 이메일 주소를 기록합니다. [세부 정보 보기 옵션](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user){target="_blank"} 전원 플랫폼에서. 이 이메일 주소는 Marketo 내에서 MS Dynamics에 대한 연결을 설정할 때 사용자 이름으로 사용됩니다.
   >* 동기화 사용자가 CRM을 업데이트하면 **아님** Marketo에 다시 동기화됩니다.

## Azure AD Federated with AD FS On-prem {#azure-ad-federated-with-ad-fs-on-prem}

Federated Azure AD에서 ADFS Onprem으로 전환하려면 특정 응용 프로그램에 대한 홈 영역 검색 정책을 만들어야 합니다. 이 정책을 사용하면 Azure AD는 인증 요청을 페더레이션 서비스로 리디렉션합니다. 이를 위해 AD Connect에서 암호 해시 동기화를 활성화해야 합니다. 자세한 내용은 다음을 참조하십시오. [ROPC가 있는 OAuth](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth-ropc){target="_blank"} and [Set an hrd policy for an application](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/configure-authentication-for-federated-users-portal#example-set-an-hrd-policy-for-an-application){target="_blank"}.

추가 참조 [은(는) 여기에서 찾을 수 있음](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-all-sign-ins#:~:text=Interactive%20user%20sign%2Dins%20are,as%20the%20Microsoft%20Authenticator%20app.&amp;text=이%20report%20also%20includes%20federated, are%20federated%20to%20Azure%20AD.){target="_blank"}.

## Marketo 솔루션 구성 {#configure-marketo-solution}

거의 다 됐어! 이제 새로 만든 사용자에 대해 Marketo 솔루션에 알리는 일만 남았습니다.

1. 고급 설정 섹션으로 돌아가서 ![](assets/image2015-5-13-15-3a49-3a19.png) 아이콘을 클릭하고 **[!UICONTROL Marketo 구성]**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >설정 메뉴에 &quot;Marketo 구성&quot;이 표시되지 않으면 페이지를 새로 고치십시오. 그래도 안 되면 [Marketo 솔루션 게시](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md){target="_blank"} 다시 로그인하거나 로그아웃했다가 다시 로그인합니다.

1. 클릭 **[!UICONTROL 기본값]**.

   ![](assets/fifteen.png)

1. 에서 검색 단추를 클릭합니다. **[!UICONTROL Marketo 사용자]** 을(를) 필드에 추가하고 생성한 동기화 사용자를 선택합니다.

   ![](assets/sixteen.png)

1. 다음을 클릭합니다. ![](assets/image2015-3-13-15-3a10-3a11.png) 아이콘을 클릭하여 변경 내용을 저장합니다.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. 다음을 클릭합니다. **X** 오른쪽 상단에서 화면을 닫습니다.

   ![](assets/seventeen.png)

1. 다음을 클릭합니다. ![](assets/image2015-5-13-15-3a49-3a19-1.png) 아이콘을 클릭하고 **[!UICONTROL 솔루션]**.

   ![](assets/eighteen.png)

1. 다음을 클릭합니다. **[!UICONTROL 모든 사용자 지정 게시]** 단추를 클릭합니다.

   ![](assets/nineteen.png)

   >[!NOTE]
   >
   >기본 인증에서 OAuth로 업그레이드하는 경우 다음을 사용할 수 있습니다 [이 문서](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md){target="_blank"} 인증을 다시 구성합니다.

## 3단계로 진행하기 전에 {#before-proceeding-to-step}

* 동기화하는 레코드 수를 제한하려면 [사용자 지정 동기화 필터 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"} 지금.
* 실행 [Microsoft Dynamics 동기화 확인](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} 프로세스. 초기 설정이 올바르게 수행되었는지 확인합니다.
* Microsoft Dynamics CRM에서 Marketo 동기화 사용자에 로그인합니다.

>[!MORELIKETHIS]
>
>* [3단계/3: Marketo 솔루션을 서버 간 연결에 연결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-3-of-3-connect.md){target="_blank"}
>* [Dynamics 인증 방법 다시 구성](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md){target="_blank"}
