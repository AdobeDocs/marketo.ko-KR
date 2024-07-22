---
unique-page-id: 7504739
description: Microsoft Dynamics 2015용 Marketo 설치 온-프레미스 3단계 중 2단계 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 2015용 Marketo 설치 온-프레미스 단계 2/3
exl-id: 39f00749-4ba3-47f1-b2e3-72cbaa7caf2e
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '371'
ht-degree: 0%

---

# 2단계/3단계 Dynamics용 Marketo 설정(2015 온프레미스){#step-of-set-up-for-marketo-on-premises-2015}

이전 단계를 완료해 주셔서 감사합니다. 계속 이 문제를 헤쳐나갑시다.

>[!PREREQUISITES]
>
>[Microsoft Dynamics 2015용 Marketo 설치 온-프레미스 단계 1/3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"}

## 동기화 사용자 역할 할당 {#assign-sync-user-role}

Marketo 동기화 사용자 역할만 Marketo 동기화 사용자에게 할당합니다. 다른 사용자에게 할당할 필요가 없습니다.

>[!NOTE]
>
>이 기능은 Marketo 버전 4.0.0.14 이상에 적용됩니다. 이전 버전의 경우 모든 사용자에게 동기화 사용자 역할이 있어야 합니다. Marketo을 업그레이드하려면 [Microsoft Dynamics용 Marketo 솔루션 업그레이드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md){target="_blank"}를 참조하십시오.

>[!IMPORTANT]
>
>동기화 사용자 [의 언어 설정은 영어로 설정해야 합니다](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us){target="_blank"}.

1. **[!UICONTROL 설정]**&#x200B;에서 **[!UICONTROL 보안]**&#x200B;을 클릭합니다.

   ![](assets/assign1.png)

1. **[!UICONTROL 사용자]**&#x200B;를 클릭합니다.

   ![](assets/assign2.png)

1. 여기에 사용자 목록이 표시됩니다. 전용 Marketo 동기화 사용자를 선택하거나 [Active Directory 페더레이션 서비스](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"}(ADFS) 관리자에게 문의하여 Marketo에 대한 전용 사용자를 만드십시오.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. 동기화 사용자를 선택합니다. **[!UICONTROL 역할 관리]**&#x200B;를 클릭합니다.

   ![](assets/assign4.png)

1. Marketo 동기화 사용자를 확인하고 **[!UICONTROL 확인]**&#x200B;을 클릭합니다.

   ![](assets/assign5.png)

   >[!IMPORTANT]
   >
   >동기화 사용자는 Marketo 구성에 대한 읽기 권한이 있어야 합니다.

   >[!TIP]
   >
   >역할이 표시되지 않으면 [3단계 중 1단계](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"}(으)로 돌아가서 솔루션을 가져오세요.

   >[!NOTE]
   >
   >동기화 사용자가 CRM에서 업데이트한 내용은 _다시 Marketo에 동기화되지 않습니다_.

## Marketo 솔루션 구성 {#configure-marketo-solution}

거의 완료되었습니다! 다음 문서로 이동하기 전에 마지막으로 구성한 부분이 몇 개 있습니다.

1. **[!UICONTROL 설정]**&#x200B;에서 **[!UICONTROL Marketo 구성]**&#x200B;을 클릭합니다.

   ![](assets/configure1.png)

   >[!NOTE]
   >
   >Marketo 구성이 누락된 경우 페이지를 새로 고침해 보십시오. 문제가 지속되면 [Marketo 솔루션을 게시](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md){target="_blank"}하거나 로그아웃했다가 다시 로그인하십시오.

1. **[!UICONTROL 기본값]**&#x200B;을 클릭합니다.

   ![](assets/configure2.png)

1. **[!UICONTROL Marketo 사용자]** 필드를 클릭하고 동기화 사용자를 선택합니다.

   ![](assets/configure3.png)

1. 오른쪽 아래 모서리에 있는 저장 아이콘을 클릭합니다.

   ![](assets/configure4.png)

1. **[!UICONTROL 모든 사용자 지정 Publish]**&#x200B;을 클릭합니다.

   ![](assets/publish-all-customizations1.png)

   >[!NOTE]
   >
   >동기화 사용자는 Marketo 구성에 대한 읽기 권한이 있어야 합니다.

## 3단계로 진행하기 전에 {#before-proceeding-to-step}

* 동기화하는 레코드 수를 제한하려면 [사용자 지정 동기화 필터를 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"}하세요.
* [Microsoft Dynamics 동기화 확인](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} 프로세스를 실행합니다. 초기 설정이 올바르게 수행되었는지 확인합니다.
* Microsoft Dynamics CRM에서 Marketo 동기화 사용자에 로그인합니다.

>[!MORELIKETHIS]
>
>[Microsoft Dynamics 2015 온-프레미스 3단계 중 3단계에 Marketo 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-3-of-3-connect-2015.md){target="_blank"}
