---
description: On-Prem용 Microsoft Dynamics CRM 앱 설정 - Marketo 문서 - 제품 설명서
title: On-Prem용 Microsoft Dynamics CRM 앱 설정
exl-id: 50d41d0a-0c3b-43b8-8117-d91903e74699
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 0%

---

# On-prem {#set-up-microsoft-dynamics-crm-app-for-on-prem}용 Microsoft Dynamics CRM 앱 설정

Marketo의 클라이언트 ID/클라이언트 암호 기반 설정은 AD FS가 있는 On-Prem(버전)에 대해 수행할 수 있습니다. 2016 이상). 이전 버전의 On-Prem의 경우 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에 연락하여 인증 방법이 사용자 ID 및 암호에만 기반하도록 변경되도록 하십시오.

## Microsoft Dynamics CRM 앱 {#set-up-microsoft-dynamics-crm-app} 설정

[이 Microsoft 문서](https://docs.microsoft.com/en-us/windows-server/identity/ad-fs/development/enabling-oauth-confidential-clients-with-ad-fs#create-an-application-group-in-ad-fs-2016-or-later)의 단계를 따릅니다.

완료되면 다음 단계는 **Dynamics CRM에서 생성된 클라이언트 ID 및 암호를 Marketo**&#x200B;에 입력하는 것입니다.

## Dynamics CRM에서 생성된 클라이언트 Id와 암호를 Marketo {#enter-the-dynamics-crm-generated-client-id-and-secret-into-marketo}에 입력합니다.

다음 단계는 온라인 및 On-Prem 버전에 적용됩니다.

1. Marketo에서 **관리**&#x200B;를 클릭합니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-1.png)

1. **Microsoft Dynamics**&#x200B;을 클릭합니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-2.png)

1. **동기화 비활성화**&#x200B;를 클릭합니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-3.png)

1. 자격 증명 옆에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-4.png)

1. 이전에 검색한 **클라이언트 ID** 및 **클라이언트 암호**&#x200B;를 입력하고 **저장**&#x200B;을 누릅니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-5.png)

1. **동기화 설정 유효성 검사**&#x200B;를 클릭합니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-6.png)

1. **다음**&#x200B;을 클릭합니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-7.png)

1. 녹색 체크 표시가 모두 표시되어야 합니다. **닫기**&#x200B;를 클릭합니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-8.png)

   >[!NOTE]
   >
   >녹색 확인 표시 중 빨간색 X가 표시되면 수정 옵션을 보려면 [이 문서](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md)을 참조하십시오.

1. **동기화 활성화**&#x200B;를 클릭합니다.

   ![](assets/set-up-microsoft-dynamics-crm-app-for-on-prem-9.png)

바로 그거야!
