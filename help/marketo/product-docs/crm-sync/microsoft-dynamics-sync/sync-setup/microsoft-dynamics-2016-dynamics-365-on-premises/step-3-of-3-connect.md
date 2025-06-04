---
description: Microsoft Dynamics 2016/Dynamics 365용 Marketo 설치 온-프레미스 3단계 중 3단계 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 2016/Dynamics 365 온-프레미스에 대한 Marketo 설치 3단계 중 3단계
exl-id: ae801a59-8e29-479c-84c5-a18c7511f21f
feature: Microsoft Dynamics
source-git-commit: 2d3264ab75d2327f9226373aad383e7a51508589
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 1%

---

# 3단계/3단계: Marketo Dynamics 연결(2016년 Prem/Dynamics 365 온프레미스) {#step-of-connect-marketo-dynamics-on-premises-2016}

>[!PREREQUISITES]
>
>* [Microsoft Dynamics 2016/Dynamics 365 온-프레미스 단계 1/3을 위한 Marketo 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-1-of-3-install.md){target="_blank"}
>* [Marketo for Microsoft Dynamics 2016/Dynamics 365 온-프레미스 단계 2/3단계](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-2-of-3-set-up.md){target="_blank"} 설치

>[!NOTE]
>
>**관리자 권한 필요**

## Dynamics 동기화 사용자 정보 입력 {#enter-dynamics-sync-user-information}

1. Marketo에 로그인하고 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/login-admin.png)

1. **[!UICONTROL CRM]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-47-34.png)

1. **[!DNL Microsoft]**&#x200B;를 선택합니다.

   ![](assets/image2015-3-16-9-50-6.png)

1. **[!UICONTROL Enter Credentials]**&#x200B;에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-48-43.png)

   >[!CAUTION]
   >
   >제출 후 후속 스키마 변경 사항을 되돌릴 수 없으므로 자격 증명이 올바른지 확인하십시오. 잘못된 자격 증명을 저장하면 새 Marketo 구독을 얻어야 합니다.

1. **[!UICONTROL Username]**, **[!UICONTROL Password]**, Microsoft Dynamics **[!UICONTROL URL]** 및 **클라이언트 Id/암호**&#x200B;를 입력하십시오. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-5.png)

   >[!NOTE]
   >
   >* 2020년 10월 이전에 Marketo이 프로비저닝된 경우 클라이언트 ID 및 암호는 선택 필드입니다. 그렇지 않으면 필수입니다. 이 정보를 얻는 것은 사용 중인 MSD 버전에 따라 다릅니다.
   >* Marketo의 사용자 이름은 CRM의 동기화 사용자에 대한 사용자 이름과 일치해야 합니다. 형식은 `user@domain.com` 또는 DOMAIN\user일 수 있습니다.
   >* URL을 모를 경우 [여기에서 찾는 방법을 알아보세요](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"}.

   >[!TIP]
   >
   >URL을 모르십니까? 여기에서 [Dynamics 조직 서비스 URL](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md)을(를) 찾는 방법을 보여 드리겠습니다.

## 동기화할 필드 선택 {#select-fields-to-sync}

1. **[!UICONTROL Select Fields to Sync]**&#x200B;에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-51-28.png)

1. Marketo에 동기화할 필드를 선택하면 미리 선택됩니다. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2016-8-25-15-3a14-3a28.png)

>[!NOTE]
>
>Marketo은 동기화할 필드에 대한 참조를 저장합니다. Dynamics에서 필드를 삭제하는 경우 [동기화가 비활성화됨](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md){target="_blank"}을(를) 사용하여 삭제하는 것이 좋습니다. 그런 다음 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md){target="_blank"}을 편집하고 저장하여 Marketo의 스키마를 새로 고치십시오.

## 사용자 정의 필터의 동기화 필드 {#sync-fields-for-a-custom-filter}

사용자 지정 필터를 만든 경우 로 이동하여 Marketo과 동기화할 새 필드를 선택하십시오.

1. 관리자로 이동하여 **[!DNL Microsoft Dynamics]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 필드 동기화 세부 정보에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 필드로 스크롤하여 확인합니다. 실제 이름은 new_synctomkto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2016-8-25-15-3a15-3a35.png)

## 동기화 활성화 {#enable-sync}

1. **[!UICONTROL Enable Sync]**&#x200B;에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-52-2.png)

   >[!CAUTION]
   >
   >Marketo은 Microsoft Dynamics 동기화나 수동으로 사람을 입력할 때 자동으로 중복 제거되지 않습니다.

1. 팝업의 모든 내용을 읽고 전자 메일을 입력한 다음 **[!UICONTROL Start Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. 레코드 수에 따라 초기 동기화는 몇 시간에서 며칠까지 걸릴 수 있습니다. 완료 시 이메일 알림을 받게 됩니다.

   ![](assets/image2015-3-16-9-59-51.png)
