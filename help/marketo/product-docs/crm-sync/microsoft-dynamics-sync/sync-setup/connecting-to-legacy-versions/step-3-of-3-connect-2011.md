---
unique-page-id: 3571809
description: 3단계/3단계 - Marketo(2011 온-프레미스)와  [!DNL Microsoft Dynamics] 연결 - Marketo 문서 - 제품 설명서
title: 3단계/3단계 - Marketo(2011 온-프레미스)와  [!DNL Microsoft Dynamics] 연결
exl-id: e6a5d49d-025a-4899-9e92-7a4c32086c67
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '344'
ht-degree: 0%

---

# 3단계/3단계: [!DNL Microsoft Dynamics]을(를) Marketo(2011 온-프레미스)와 연결 {#step-of-connect-microsoft-dynamics-with-marketo-on-premises}

좋아! 솔루션을 설치하고 동기화 사용자를 구성했습니다. 그런 다음 Marketo과 [!DNL Dynamics]을(를) 연결해야 합니다.

>[!PREREQUISITES]
>
>* [3단계 중 1단계: Marketo 솔루션 설치(2011 온-프레미스)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md)
>* [2단계/3: [!DNL Dynamics] (2011 온-프레미스)에서 Marketo 동기화 사용자 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md)

>[!NOTE]
>
>**관리자 권한 필요**

## [!DNL Dynamics] 동기화 사용자 정보 입력 {#enter-dynamics-sync-user-information}

1. Marketo에 로그인하고 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/login-admin.png)

1. **[!UICONTROL CRM]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. **[!UICONTROL Microsoft]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. **[!UICONTROL Edit]**&#x200B;에서 **[!UICONTROL Step 1: Enter credentials]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >제출 후 후속 스키마 변경 사항을 되돌릴 수 없으므로 자격 증명이 올바른지 확인하십시오. 잘못된 자격 증명을 저장하면 새 Marketo 구독을 얻어야 합니다.

1. **[!UICONTROL Username]**, **[!UICONTROL Password]** 및 CRM **[!UICONTROL URL]**&#x200B;을(를) 입력한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-2-14-3a50-3a7.png)

   >[!NOTE]
   >
   >* Marketo의 [!UICONTROL Username]은(는) CRM의 동기화 사용자에 대한 사용자 이름과 일치해야 합니다. 형식은 `user@domain.com` 또는 DOMAIN\user일 수 있습니다.
   >* URL을 모를 경우 [여기에서 찾는 방법을 알아보세요](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md).

## 동기화할 필드 선택 {#select-fields-to-sync}

이제 동기화할 필드를 선택해야 합니다.

1. **[!UICONTROL Edit]**&#x200B;에서 **[!UICONTROL Step 2: Select Fields to Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-51-28a.png)

1. 동기화할 미리 선택된 필드가 있습니다. 원하는 경우 더 추가하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2016-8-25-13-3a26-3a14.png)

   >[!NOTE]
   >
   >Marketo은 동기화할 필드에 대한 참조를 저장합니다. [!DNL Dynamics]에서 필드를 삭제하는 경우 [동기화가 비활성화됨](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md)을(를) 사용하여 삭제하는 것이 좋습니다. 그런 다음 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md)을 편집하고 저장하여 Marketo의 스키마를 새로 고치십시오.

## 사용자 정의 필터의 동기화 필드 {#sync-fields-for-a-custom-filter}

사용자 지정 필터를 만든 경우 로 이동하여 Marketo과 동기화할 새 필드를 선택하십시오.

1. 관리자로 이동하여 **[!UICONTROL Microsoft Dynamics]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. **[!UICONTROL Edit]**&#x200B;에서 [!UICONTROL Field Sync Details]을(를) 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 필드로 스크롤하여 확인합니다. 실제 이름은 new_synctomkto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/image2016-8-25-14-3a14-3a57.png)

## 동기화 활성화 {#enable-sync}

1. **[!UICONTROL Edit]**&#x200B;에서 **[!UICONTROL Step 3: Enable Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-52-2b.png)

   >[!CAUTION]
   >
   >Marketo은 [!DNL Microsoft Dynamics] 동기화에 대해 또는 사람 또는 잠재 고객을 수동으로 입력하는 경우 자동으로 중복 제거되지 않습니다.

1. 팝업의 모든 내용을 읽고 전자 메일을 입력한 다음 **[!UICONTROL Start Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. 레코드 수에 따라 초기 동기화는 몇 시간에서 며칠까지 걸릴 수 있습니다. 완료 시 이메일 알림을 받게 됩니다.

   ![](assets/image2014-12-11-11-3a55-3a15.png)
