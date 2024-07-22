---
unique-page-id: 3571819
description: 3단계 중 3단계 - Marketo 및 Dynamics 연결(2013 온프레미스) - Marketo 문서 - 제품 설명서
title: 3단계 중 3단계 - Marketo 및 Dynamics 연결(2013 온프레미스)
exl-id: e28f1cc3-ee15-4981-a537-6c4a1682c4c1
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '413'
ht-degree: 0%

---

# 3단계/3단계: Marketo 및 Dynamics 연결(2013 온프레미스) {#step-of-connect-marketo-and-dynamics-on-premises}

좋아! 솔루션을 설치하고 동기화 사용자를 구성했습니다. 다음으로, Marketo Engage과 Dynamics를 연결해야 합니다.

>[!PREREQUISITES]
>
>* [3단계 중 1단계: Dynamics(2013 온-프레미스)에 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md){target="_blank"}
>* [3단계 중 2단계: Marketo(2013 온-프레미스)에 대한 동기화 사용자 구성](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-configure-2013.md){target="_blank"}

>[!NOTE]
>
>**관리자 권한 필요**

## Dynamics 동기화 사용자 정보 입력 {#enter-dynamics-sync-user-information}

1. Marketo에 로그인하고 **[!UICONTROL 관리자]**&#x200B;를 클릭합니다.

   ![](assets/login-admin.png)

1. **[!UICONTROL CRM]**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. **[!DNL Microsoft]**&#x200B;을(를) 선택합니다.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. **[!UICONTROL 자격 증명 입력]**&#x200B;에서 **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >제출 후 후속 스키마 변경 사항을 되돌릴 수 없으므로 자격 증명이 올바른지 확인하십시오. 잘못된 자격 증명을 저장하면 새 Marketo 구독을 얻어야 합니다.

1. **[!UICONTROL 사용자 이름]**, **[!UICONTROL 암호]** 및 Microsoft Dynamics **[!UICONTROL URL]**&#x200B;을(를) 입력한 다음 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-26-11-3a47-3a59.png)

   >[!NOTE]
   >
   >* Marketo의 사용자 이름은 CRM의 동기화 사용자에 대한 사용자 이름과 일치해야 합니다. 형식은 `user@domain.com` 또는 DOMAIN\user일 수 있습니다.
   >* URL을 모를 경우 [여기에서 찾는 방법을 알아보세요](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"}.

## 동기화할 필드 선택 {#select-fields-to-sync}

이제 동기화할 필드를 선택해야 합니다.

1. **[!UICONTROL 동기화할 필드 선택]**&#x200B;에서 **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Marketo에 동기화할 필드를 선택하면 미리 선택됩니다. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2016-8-25-15-3a10-3a17.png)

   >[!NOTE]
   >
   >Marketo은 동기화할 필드에 대한 참조를 저장합니다. Dynamics에서 필드를 삭제하는 경우 [동기화가 비활성화됨](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md){target="_blank"}을(를) 사용하여 삭제하는 것이 좋습니다. 그런 다음 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md){target="_blank"}을 편집하고 저장하여 Marketo의 스키마를 새로 고치십시오.

## 사용자 정의 필터의 동기화 필드 {#sync-fields-for-a-custom-filter}

사용자 지정 필터를 만든 경우 로 이동하여 Marketo과 동기화할 새 필드를 선택하십시오.

1. 관리자로 이동하여 **[!UICONTROL Microsoft Dynamics]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 필드 동기화 세부 정보에서 **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 필드로 스크롤하여 확인합니다. 실제 이름은 new_synctomkto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2016-8-25-15-3a11-3a4.png)

## 동기화 활성화 {#enable-sync}

1. **[!UICONTROL 동기화 활성화]**&#x200B;에서 **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo은 Microsoft Dynamics 동기화와 비교하여 또는 사람 또는 잠재 고객을 수동으로 입력하는 경우 자동으로 중복 제거되지 않습니다.

1. 팝업의 모든 내용을 읽고 전자 메일을 입력한 다음 **[!UICONTROL 동기화 시작]**&#x200B;을 클릭하세요.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. 첫 번째 동기화는 몇 시간이 걸릴 수 있습니다. 완료되면 이메일 알림을 받게 됩니다.

   ![](assets/image2014-12-11-11-3a55-3a15.png)

훌륭합니다! Marketo과 Microsoft Dynamics 간의 양방향 동기화 기능을 방금 활성화했습니다. Marketo Sales Insight를 구입한 경우 다음과 같은 이점이 있습니다.

>[!MORELIKETHIS]
>
>[Microsoft Dynamics 2013에서 Marketo Sales Insight 설치 및 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2013.md){target="_blank"}
