---
unique-page-id: 3571739
description: Microsoft Dynamics 365에서 Marketo Sales Insight 설치 및 구성 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 365에서 Marketo Sales Insight 설치 및 구성
exl-id: c1f06b8c-48fd-4015-9502-7c9693632589
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '458'
ht-degree: 0%

---

# Microsoft Dynamics 365에서 Marketo Sales Insight 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight는 영업 팀에 마케팅 팀이 보유한 풍부한 데이터를 &quot;창&quot;으로 볼 수 있는 환상적인 도구입니다. 다음은 설치 및 구성 방법입니다.

>[!PREREQUISITES]
>
>Marketo-Microsoft 통합을 완료합니다.
>
>[올바른 솔루션 다운로드](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) Microsoft Dynamics CRM 버전용입니다.

## 솔루션 가져오기 {#import-solution}

1. 에 로그인 [Microsoft Office 365](https://login.microsoftonline.com/).

   ![](assets/image2015-3-16-15-58-55.png)

1. 다음을 클릭합니다. ![—](assets/image2015-3-16-16-1-13.png) 메뉴 및 선택 **CRM**.

   ![](assets/image2015-3-16-16-0-10.png)

1. 다음을 클릭합니다. ![—](assets/image2015-5-13-10-5-8.png) 메뉴 아래의 제품에서 사용할 수 있습니다. 드롭다운에서 을 선택합니다. **설정**&#x200B;을 선택한 다음 을 선택합니다. **솔루션**.

   ![](assets/image2015-5-13-10-4-1.png)

   >[!NOTE]
   >
   >이미 다음을 했어야 합니다. [Marketo 솔루션 설치 및 구성](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md) 앞으로 나아가기 전에.

1. 클릭 **가져오기**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. 새 창에서 다음을 클릭합니다. **찾아보기**. 다음을 선택합니다. [1단계에서 다운로드한 Marketo Sales Insight 솔루션](#msi). 클릭 **다음**.

   ![](assets/image2015-5-13-15-3a38-3a49.png)

1. 솔루션이 업로드됩니다. 원한다면 패키지 콘텐츠를 볼 수 있습니다. 클릭 **다음**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. 상자를 그대로 둡니다. **선택됨** 및 클릭 **가져오기**.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. 언제든지 로그 파일을 다운로드할 수 있습니다. Click **Close**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. 멋지다! 이제 해결 방법을 확인해야 합니다. 없는 경우 화면을 새로 고칩니다.

   ![](assets/image2015-5-13-15-3a42-3a29.png)

1. 클릭 **모든 사용자 지정 게시**.

   ![](assets/image2015-11-10-11-3a15-3a40.png)

## Marketo 및 Sales Insight 연결 {#connect-marketo-and-sales-insight}

Marketo 인스턴스를 Dynamics의 Sales Insight에 연결하겠습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. Marketo에 로그인하고 **관리자** 섹션.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. 아래 **Sales Insight** 섹션, 클릭 **API 구성 편집**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. 다음을 복사합니다. **Marketo 호스트**, **API URL** 및 **API 사용자 ID** 를 참조하십시오. 다음을 입력하십시오. **API 비밀 키** 을(를) 선택하고 **저장**.

   >[!CAUTION]
   >
   >API 비밀 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >다음 필드는 을(를) 위해 Marketo과 동기화해야 합니다. _리드 및 연락처 모두_ for Sales Insight to work:
   >
   > * 우선 순위
   > * 긴급도
   > * 상대 스코어
   >
   >이러한 필드 중 하나가 누락된 경우 누락된 필드 이름과 함께 Marketo에 오류 메시지가 표시됩니다. 이 문제를 해결하려면 다음을 수행합니다 [이 절차](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Microsoft Dynamics로 돌아가 ![](assets/image2015-5-13-15-3a49-3a19.png) 아이콘을 클릭한 다음, 선택 **Marketo API 구성** 드롭다운에서 을 클릭합니다.

   ![](assets/image2015-5-13-16-3a4-3a1.png)

1. 클릭 **기본 구성**.

   ![](assets/image2015-5-13-16-3a5-3a2.png)

1. 이전에 Marketo에서 복사한 정보를 입력합니다.

   ![](assets/image2015-5-13-16-3a7-3a6.png)

1. 다음을 클릭합니다. ![](assets/image2015-5-13-16-3a8-3a51.png) 아이콘을 클릭하여 변경 내용을 저장합니다.

## 사용자 액세스 설정 {#set-user-access}

Sales Insight를 사용하려면 사용자에게 권한을 부여해야 합니다.

1. 다음을 클릭합니다. ![](assets/image2015-5-13-10-3a5-3a8.png) 메뉴 아래의 제품에서 사용할 수 있습니다. 드롭다운 메뉴에서 을(를) 선택합니다 **설정**&#x200B;을 선택한 다음 을 선택합니다. **보안**.

   ![](assets/image2015-5-13-16-3a12-3a12.png)

1. 클릭 **사용자**.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. Sales Insight에 대한 액세스 권한을 부여할 사용자를 선택하고 **역할 관리**.

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. 다음 항목 선택 **Marketo Sales Insight** 역할 및 클릭 **확인**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   그리고 넌 다 끝내야 해! 마지막으로 테스트하려면 Marketo Sales Insight에 액세스할 수 있는 사용자로 Dynamics에 로그인하여 잠재 고객 또는 연락처를 확인합니다.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

이제 영업 팀을 위한 Marketo Sales Insight의 기능을 잠금 해제했습니다.

>[!MORELIKETHIS]
>
>[Lead/Contact Records에 Stars 및 Flames 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
