---
unique-page-id: 7504739
description: Dynamics 2015 On-Prem 및 2016 365 On-Prem 2단계 - Marketing Docs - 제품 설명서 설치
title: Dynamics 2015 On-Prem 및 2016 365 On-Prem 2단계 설치
translation-type: tm+mt
source-git-commit: dc20aede0894a09e6c0bcd3d1580859b5fecb5f1
workflow-type: tm+mt
source-wordcount: '328'
ht-degree: 0%

---


# 3단계 중 2단계

<!--Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 2 of 3-->

이전 단계를 수료한 데 큰 도움이 되었습니다. 계속 진행합시다.

>[!NOTE]
>
>**사전 요구 사항**
>
>* [Dynamics 2015 On-Prem 및 2016 365 On-Prem 1단계 설치](step-1-of-3-install.md)

>



## 동기화 사용자 역할 할당 {#assign-sync-user-role}

Marketing to Sync 사용자 역할만 Marketing to 동기화 사용자에게 할당합니다. 다른 사용자에게 할당할 필요는 없습니다.

>[!NOTE]
>
>이는 Marketing 버전 4.0.0.14 이상에 적용됩니다. 이전 버전의 경우 모든 사용자는 동기화 사용자 역할이 있어야 합니다. Marketing to를 업그레이드하려면 Microsoft Dynamics [용 Marketing Solution 업그레이드를 참조하십시오](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md).

1. 설정 **에서****보안을 클릭합니다**.

   ![](assets/assign1.png)

1. 사용자를 **클릭합니다**.

   ![](assets/assign2.png)

1. 여기에 사용자 목록이 표시됩니다. 전용 Marketing to Sync 사용자를 선택하거나 ADFS( [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx)) 관리자에게 문의하여 Marketing용 전용 사용자를 만듭니다.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. 동기화 사용자를 선택합니다. 역할 **관리를 클릭합니다**.

   ![](assets/assign4.png)

   Marketing to Sync 사용자를 선택하고 확인을 클릭합니다.

   ![](assets/assign5.png)

   >[!TIP]
   >
   >해당 역할이 표시되지 않으면 3 [단계 중 1단계로 돌아가서 솔루션을](step-1-of-3-install.md) 가져옵니다.

   >[!NOTE]
   >
   >동기화 사용자가 CRM에서 만든 모든 업데이트는 Marketing To로 다시 동기화되지 **않습니다** .

## 마케팅 솔루션 구성 {#configure-marketo-solution}

거의 완료되었습니다. 다음 아티클로 이동하기 전에 몇 가지 구성 요소가 있습니다.

1. 설정 **에서**&#x200B;마케팅 **구성을 클릭합니다**.

   ![](assets/configure1.png)

   >[!NOTE]
   >
   >Marketing To 구성이 없는 경우 페이지를 새로 고쳐 보십시오. 문제가 지속되면 Marketing To [솔루션을](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) 게시하거나 로그아웃했다가 다시 로그인하십시오.

1. 기본값 **을 클릭합니다**.

   ![](assets/configure2.png)

1. Marketing **To 사용자** 필드를 클릭하고 동기화 사용자를 선택합니다.

   ![](assets/configure3.png)

1. 오른쪽 하단에 있는 저장 아이콘을 클릭합니다.

   ![](assets/configure4.png)

1. 모든 사용자 지정 **게시를 클릭합니다**.

   ![](assets/publish-all-customizations1.png)

## 3단계로 이동하기 전 {#before-proceeding-to-step}

* 동기화되는 레코드 수를 제한하려면 [지금 사용자 지정 동기화 필터를](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) 설정합니다.
* Microsoft [Dynamics 동기화 유효성 검사](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) 프로세스를 실행합니다. 초기 설정이 올바르게 수행되었는지 확인합니다.
* Microsoft Dynamics CRM에서 Marketing to Sync 사용자에 로그인합니다.

>[!NOTE]
>
>**관련 문서**
>
>[Dynamics 2015 On-Prem 및 2016 365 On-Prem 3단계 설치](step-3-of-3-connect.md)
