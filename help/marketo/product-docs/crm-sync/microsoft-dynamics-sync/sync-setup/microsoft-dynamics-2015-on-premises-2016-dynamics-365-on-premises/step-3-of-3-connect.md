---
unique-page-id: 7504744
description: Dynamics 2015 On-Prem 및 2016 365 On-Prem 3단계 - Marketing Docs - 제품 설명서 설치
title: Dynamics 2015 On-Prem 및 2016 365 On-Prem 3을 위한 Market 설치
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '323'
ht-degree: 0%

---


# Dynamics 2015 On-Prem 및 2016 365 On-Prem 3단계 중 3단계 {#install-marketo-for-dynamics-on-prem-and-on-prem-step-of} 설치

>[!PREREQUISITES]
>
>* [Dynamics 2015 On-Prem 및 2016 365 On-Prem용 Marketing To 설치 1/3](step-1-of-3-install.md)
>* [Dynamics 2015 On-Prem 및 2016 365 On-Prem 2단계/3을 위한 Marketing 설치](step-2-of-3-set-up.md)

>



>[!NOTE]
>
>**관리자 권한 필요**

## Dynamics 동기화 사용자 정보 {#enter-dynamics-sync-user-information} 입력

1. Marketing에 로그인하고 **관리**&#x200B;를 클릭합니다.

   ![](assets/login-admin.png)

1. **CRM**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-16-9-47-34.png)

1. **Microsoft**&#x200B;를 선택합니다.

   ![](assets/image2015-3-16-9-50-6.png)

1. **1단계에서**&#x200B;편집&#x200B;**을 클릭합니다.자격 증명**&#x200B;을 입력합니다.

   ![](assets/image2015-3-16-9-48-43.png)

   >[!CAUTION]
   >
   >제출 후 스키마 변경 내용을 되돌릴 수 없으므로 자격 증명이 올바른지 확인하십시오. 잘못된 자격 증명이 저장되면 새 Marketing To 구독을 구해야 합니다.

1. **사용자 이름**, **암호** Microsoft Dynamics **URL**&#x200B;을 입력하고 선택적 **클라이언트 ID**&#x200B;를 입력합니다. 완료되면 **저장**&#x200B;을 클릭합니다.

   ![](assets/client-id.png)

   >[!NOTE]
   >
   >Marketing의 사용자 이름은 CRM의 동기화 사용자의 사용자 이름과 일치해야 합니다. 형식은 [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#8cf9ffe9fecce8e3e1ede5e2a2efe3e1) 또는 DOMAIN\user일 수 있습니다.

   >[!TIP]
   >
   >URL을 모르십니까? 여기에서 [Dynamics 조직 서비스 URL](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md)을 찾는 방법을 보여 드리겠습니다.

## 동기화할 필드 선택 {#select-fields-to-sync}

1. **2단계에서**&#x200B;편집&#x200B;**을 클릭합니다.동기화할 필드**&#x200B;를 선택합니다.

   ![](assets/image2015-3-16-9-51-28.png)

1. Marketing To에 동기화하려는 필드를 선택하여 미리 선택합니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2016-8-25-15-3a14-3a28.png)

## 사용자 지정 필터 {#sync-fields-for-a-custom-filter}에 대한 필드 동기화

사용자 정의 필터를 만든 경우 해당 위치로 이동하여 Marketing To와 동기화할 새 필드를 선택하십시오.

1. 관리로 이동하고 **Microsoft Dynamics**&#x200B;을 선택합니다.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 필드 동기화 세부 정보에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 아래로 스크롤하여 확인합니다. 실제 이름은 new_synctomto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2016-8-25-15-3a15-3a35.png)

## {#enable-sync} 동기화 사용

1. **단계 3:동기화**&#x200B;을(를) 활성화합니다.****

   ![](assets/image2015-3-16-9-52-2.png)

   >[!CAUTION]
   >
   >Microsoft Dynamics 동기화 또는 수동으로 사람을 입력할 때 Marketing To는 자동으로 중복 제거 기능을 제공하지 않습니다.

1. 팝업에서 모든 내용을 읽고 전자 메일을 입력한 다음 **동기화 시작**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. 첫 번째 동기화에는 몇 시간이 걸릴 수 있습니다. 완료되면 이메일 알림을 수신하게 됩니다.

   ![](assets/image2015-3-16-9-59-51.png)

탁월한 작업!
