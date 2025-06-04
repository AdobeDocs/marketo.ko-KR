---
description: 4단계/4단계 - 리소스 소유자 암호 제어 연결과 Marketo 솔루션 연결 - Marketo 문서 - 제품 설명서
title: 4단계/4단계 - 리소스 소유자 암호 제어 연결과 Marketo 솔루션 연결
exl-id: 71a52a3e-f31e-45ee-8196-d536528e42ca
feature: Microsoft Dynamics
source-git-commit: 2d3264ab75d2327f9226373aad383e7a51508589
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---

# 4단계/4단계: 리소스 소유자 암호 제어 연결과 Marketo 솔루션 연결 {#step-4-of-4-connect-the-marketo-solution-ropc}

동기화의 마지막 단계입니다. 거의 다 왔어!

>[!PREREQUISITES]
>
>* [4단계 중 1단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md){target="_blank"}
>* [2단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}
>* [3단계/4단계: MS Dynamics에서 클라이언트 앱 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md){target="_blank"}

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>기본 인증에서 OAuth로 업그레이드하는 경우 [이 문서](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md){target="_blank"}을(를) 사용하여 인증을 다시 구성할 수 있습니다.

## Dynamics 동기화 사용자 정보 입력 {#enter-dynamics-sync-user-information}

1. Marketo에 로그인하고 **A관리자**&#x200B;를 클릭합니다.

   ![](assets/login-admin.png)

1. **[!UICONTROL CRM]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-3a47-3a34.png)

1. **[!UICONTROL Microsoft]**&#x200B;를 선택합니다.

   ![](assets/image2015-3-16-9-3a50-3a6.png)

1. **[!UICONTROL Enter Credentials]**&#x200B;에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-3a48-3a43.png)

   >[!CAUTION]
   >
   >제출 후 후속 스키마 변경 사항을 되돌릴 수 없으므로 조직 URL이 올바른지 확인하십시오. 잘못된 조직 URL이 사용되는 경우 새 Marketo 구독을 얻어야 합니다. URL을 모를 경우 [여기에서 찾는 방법을 알아보세요](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"}.

   >[!NOTE]
   >
   >새 자격 증명을 입력하기 전에 [여기에서 유효성을 확인](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"}할 수 있습니다.

1. **[!UICONTROL Username]**, **[!UICONTROL Password]**, Microsoft Dynamics **URL**, **[!UICONTROL Client ID]** 및 **[!UICONTROL Client Secret]**&#x200B;을(를) 입력하십시오. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-4-of-4-connect-ropc-5.png)

   >[!NOTE]
   >
   >Marketo의 사용자 이름은 CRM의 동기화 사용자에 대한 사용자 이름과 일치해야 합니다. 형식은 `user@domain.com` 또는 DOMAIN\user일 수 있습니다.

## 동기화할 필드 선택 {#select-fields-to-sync}

1. **[!UICONTROL Select Fields to Sync]**&#x200B;에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Marketo에 동기화할 필드를 선택하면 미리 선택됩니다. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2016-8-25-15-3a6-3a11.png)

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

   ![](assets/image2016-8-25-15-3a7-3a35.png)

## 동기화 활성화 {#enable-sync}

1. **[!UICONTROL Enable Sync]**&#x200B;에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo은 Microsoft Dynamics 동기화나 사람 또는 잠재 고객을 수동으로 입력하는 경우 자동으로 중복 제거되지 않습니다.

1. 팝업의 모든 내용을 읽고 전자 메일 주소를 입력한 다음 **[!UICONTROL Start Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-16-9-3a55-3a10.png)

1. 레코드 수에 따라 초기 동기화는 몇 시간에서 며칠까지 걸릴 수 있습니다. 완료 시 이메일 알림을 받게 됩니다.

   ![](assets/image2015-3-16-9-3a59-3a51.png)

>[!MORELIKETHIS]
>
>[Dynamics 인증 방법 다시 구성](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md){target="_blank"}
