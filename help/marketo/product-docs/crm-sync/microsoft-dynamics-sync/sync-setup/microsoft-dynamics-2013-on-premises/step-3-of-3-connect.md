---
unique-page-id: 3571819
description: 3단계 중 3단계 - Connect Marketing 및 Dynamics(2013년 온프레미스) - Marketing Docs - 제품 설명서
title: 3단계 중 3단계 - Connect Marketing 및 Dynamics(2013년 온프레미스)
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '430'
ht-degree: 0%

---


# 3단계 중 3단계:Connect Marketing 및 Dynamics(2013 온-프레미스) {#step-of-connect-marketo-and-dynamics-on-premises}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

좋아! 솔루션을 설치하고 동기화 사용자를 구성했습니다. Adobe는 Marketing To와 Dynamics를 연계해야 합니다.

>[!PREREQUISITES]
>
>* [3단계 중 1단계:Dynamics에서 Marketing Solution 설치(2013 온프레미스)](step-1-of-3-install.md)
>* [3단계 중 2단계:Marketing(2013 온-프레미스)용 사용자 동기화 구성](step-2-of-3-configure.md)

>



>[!NOTE]
>
>**관리자 권한 필요**

## Dynamics 사용자 정보 입력 {#enter-dynamics-sync-user-information}

1. Marketing에 로그인하고 관리를 **클릭합니다**.

   ![](assets/login-admin.png)

1. CRM을 **클릭합니다**.

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. Microsoft **를 선택합니다**.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. 1단계에서 **편집** 을 **클릭합니다.자격 증명을 입력합니다**.

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >제출 후 스키마 변경 사항을 되돌릴 수 없으므로 자격 증명이 올바른지 확인하십시오. 잘못된 자격 증명이 저장된 경우 새 Marketing To 구독을 구해야 합니다.

1. 사용자 이름, 암호 **및 Microsoft Dynamics** URL을 **입력한 다음** 저장 **을******&#x200B;클릭합니다.

   ![](assets/image2015-3-26-11-3a47-3a59.png)

   >[!NOTE]
   >
   >Marketing의 사용자 이름은 CRM의 동기화 사용자의 사용자 이름과 일치해야 합니다. 형식은 DOMAIN\user [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#631610061123070c0e020a0d4d000c0e) 일 수 있습니다.

   >[!TIP]
   >
   >URL을 모르십니까? 여기에서 Dynamics [조직 서비스 URL을 찾는 방법을](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md) 알려드리겠습니다.

## 동기화할 필드 선택 {#select-fields-to-sync}

이제 동기화할 필드를 선택해야 합니다.

1. 2단계에서 **EDIT **를 **클릭합니다.동기화할 필드를 선택합니다**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Marketing To에 동기화할 필드를 선택하여 미리 선택합니다. 저장을 **클릭합니다**.

   ![](assets/image2016-8-25-15-3a10-3a17.png)

## 사용자 정의 필터의 필드 동기화 {#sync-fields-for-a-custom-filter}

사용자 지정 필터를 만든 경우 Marketing To와 동기화할 새 필드를 선택해야 합니다.

1. 관리자로 이동하고 **Microsoft Dynamics를 선택합니다**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 필드 **동기화** 세부 정보에서 편집을 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 아래로 스크롤하여 확인합니다. 실제 이름은 new_synctomto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. 저장을 **클릭합니다**.

   ![](assets/image2016-8-25-15-3a11-3a4.png)

## 동기화 사용 {#enable-sync}

1. 3단계에서 **EDIT **를 **클릭합니다.동기화를 활성화합니다**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Microsoft Dynamics 동기화에 대해 또는 수동으로 사람 또는 리드를 입력할 때 Marketing To에서 자동으로 데이터 중복 제거가 되지 않습니다.

1. 팝업에서 모든 내용을 읽고 이메일을 입력한 다음 [동기화 **시작]을 클릭합니다**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. 첫 번째 동기화에는 몇 시간이 걸릴 수 있습니다. 완료되면 알림 이메일을 수신하게 됩니다.

   ![](assets/image2014-12-11-11-3a55-3a15.png)

탁월한 작품! Marketing To와 Microsoft Dynamics 간의 양방향 동기화 기능을 활용할 수 있습니다. Marketing To Sales Insight를 구입한 경우 더 재미있는 방법이 있습니다.

>[!NOTE]
>
>**관련 문서**
>
>* [Microsoft Dynamics 2013에서 Marketing To Sales Insight 설치 및 구성](../../../../../product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2013.md)

>



