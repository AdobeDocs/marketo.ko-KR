---
unique-page-id: 3571807
description: 3단계 중 2단계 - Dynamics에서 Marketing To Sync 사용자 설정(2011 온-프레미스) - Marketing Docs - 제품 설명서
title: 3단계 중 2단계 - Dynamics에서 Marketing To Sync 사용자 설정(2011 온-프레미스)
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '350'
ht-degree: 0%

---


# 3단계 중 2단계:Dynamics에서 Marketing To Sync 사용자 설정(2011 온-프레미스) {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises}

이전 단계를 성공적으로 마쳤으니 계속 진행해 봅시다.

>[!PREREQUISITES]
>
>[3단계 중 1단계:Marketing To 솔루션 설치(2011 온프레미스)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md)

## 동기화 사용자 역할 할당 {#assign-sync-user-role}

Marketing to Sync 사용자 역할을 Marketing Cloud에 할당하여 사용자를 동기화합니다. 다른 사용자에게 할당할 필요는 없습니다.

>[!NOTE]
>
>이것은 Marketing to 플러그인 버전 4.0.0.14 이상에 적용됩니다. 이전 버전의 경우 모든 사용자는 동기화된 사용자 역할이 있어야 합니다. 마케팅을 업그레이드하려면 [Microsoft Dynamics용 Marketing Solution 업그레이드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/upgrade-the-marketo-solution-for-microsoft-dynamics.md)를 참조하십시오.

1. 왼쪽 하단 메뉴에서 **설정**&#x200B;을 선택합니다.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. 트리에서 **관리**&#x200B;를 선택합니다.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. **사용자**&#x200B;를 선택합니다.

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. 여기에 사용자 목록이 표시됩니다. 전용 Marketing을 선택하여 사용자를 동기화하거나 [AFDS(Active Directory Federation Services)](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 관리자에게 문의하여 Marketing To에만 사용되는 새 사용자를 만듭니다. **역할 관리**&#x200B;를 클릭합니다.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. **Marketing To Sync 사용자**&#x200B;를 선택하고 **확인**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   >
   >역할이 표시되지 않으면 [단계 1/3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md)으로 돌아가서 솔루션을 가져옵니다.

   >[!NOTE]
   >
   >동기화 사용자가 CRM에서 수행한 모든 업데이트는 Marketing To에 다시 동기화되지 **않습니다.**

## 마케팅 솔루션 {#configure-marketo-solution} 구성

거의 완료되었습니다! 다음 아티클로 이동하기 전에 몇 개의 마지막 구성 요소가 있습니다.

1. **설정**&#x200B;을 선택합니다. 그런 다음 트리에서 **Marketing Config**&#x200B;를 선택합니다.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   >
   >Marketing To 구성이 없는 경우 페이지를 새로 고쳐 보십시오. 문제가 지속되면 [Marketing 솔루션을 다시 게시하거나](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md) 로그아웃했다가 다시 로그인합니다.

1. **기본값**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-14-3a27-3a30.png)

1. ![](assets/image2015-4-2-14-3a29-3a1.png)을 클릭합니다.

   ![](assets/image2015-4-2-14-3a28-3a40.png)

1. 팝업에서 동기화 사용자를 선택합니다. 그런 다음 **확인**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-14-3a32-3a43.png)

1. **저장**&#x200B;을 클릭하여 변경 내용을 저장합니다.

   ![](assets/image2015-4-2-14-3a34-3a15.png)

1. **모든 사용자 지정 게시**&#x200B;를 클릭합니다.

   ![](assets/publish-all-customizations1.png)

## 3단계로 진행하기 전 {#before-proceeding-to-step}

    * 동기화하려는 레코드 수를 제한하려면 지금 [사용자 정의 동기화 필터 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md).
    * [Microsoft Dynamics 동기화 유효성 검사](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) 프로세스를 실행합니다. 초기 설정이 올바르게 수행되었는지 확인합니다.
    * Microsoft Dynamics CRM에서 Marketing to Sync 사용자에 로그인합니다.

잘했어요!

>[!MORELIKETHIS]
>
>[3단계 중 3단계:Microsoft Dynamics와 Marketing(2011 온-프레미스) 연결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-3-of-3-connect.md)
