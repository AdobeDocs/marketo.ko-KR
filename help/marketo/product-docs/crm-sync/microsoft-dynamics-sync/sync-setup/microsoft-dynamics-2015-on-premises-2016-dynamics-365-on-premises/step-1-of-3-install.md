---
unique-page-id: 7504736
description: Dynamics 2015 On-Prem 및 2016 365 On-Prem 1단계 - Marketing Docs - 제품 설명서 설치
title: Dynamics 2015 On-Prem 및 2016 365 On-Prem 1단계 설치
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '292'
ht-degree: 0%

---


# 3단계 중 1단계

<!--Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 1 of 3-->

Microsoft Dynamics 2015 온-프레미스 또는 2016(Dynamics 365)을 Marketing To와 동기화하려면 먼저 Dynamics에서 Marketing To 솔루션을 설치해야 합니다.

>[!NOTE]
>
>Marketing을 CRM에 동기화한 후에는 새 CRM을 기존 Marketing To 인스턴스에 동기화할 수 없습니다.

>[!PREREQUISITES]
>
>Microsoft Dynamics 온-프레미스를 사용하는 경우 ADFS( [Active Directory Federation Services](http://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) 2.0+)가 구성된 IFD(Internet Facing Deployment [](https://msdn.microsoft.com/en-us/library/bb897402.aspx) )가 있어야 합니다. 참고:링크를 클릭하면 IFD 문서가 자동으로 다운로드됩니다.
>
>[시작하기 전에 Marketing To 리드 관리 솔루션을](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) 다운로드하십시오.

>[!NOTE]
>
>**Dynamics 관리 권한이 필요합니다.**
>
>이 동기화를 수행하려면 CRM 관리자 권한이 필요합니다.

1. Dynamics에 **로그인합니다.** Microsoft **Dynamics CRM** 드롭다운 메뉴를 클릭하고 **설정을 선택합니다**.

   ![](assets/image2015-3-19-8-33-29.png)

1. 설정 **아래에서****솔루션을 선택합니다**.

   ![](assets/image2015-3-19-8-33-3.png)

1. 가져오기를 **클릭합니다**.

   ![](assets/image2015-3-19-8-34-8.png)

1. [ **찾아보기** ]를 클릭하고 [다운로드한 솔루션을 선택합니다](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). 다음을 **클릭합니다**.

   ![](assets/image2015-3-19-9-20-56.png)

1. 솔루션 정보를 보고 솔루션 패키지 세부 사항 **보기를 클릭합니다**.

   ![](assets/image2015-11-18-11-12-8.png)

1. 모든 세부 사항을 확인했으면 **닫기를 클릭합니다**.

   ![](assets/step6.png)

1. [솔루션 정보] 페이지로 돌아가서 **다음을 클릭합니다**.

   ![](assets/image2015-3-19-9-21-50.png)

1. SDK 옵션 확인란이 선택되어 있는지 확인합니다. 가져오기를 **클릭합니다**.

   ![](assets/image2015-3-19-9-19-12.png)

1. 가져오기가 완료될 때까지 기다립니다.

   >[!TIP]
   >
   >설치 과정을 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

   ![](assets/image2015-3-11-11-34-9.png)

1. 로그 파일(필요한 경우)을 다운로드하고 **닫기를 클릭합니다**.

   >[!NOTE]
   >
   >&quot;Marketing to Lead Management 완료(경고 포함)&quot;라는 메시지가 표시될 수 있습니다. 이것은 충분히 예상된 일이다.

   ![](assets/image2015-3-13-9-54-39.png)

1. 이제 마케팅 리드 관리가 **모든 솔루션** 페이지에 표시됩니다.

   ![](assets/image2015-3-19-8-40-38.png)

1. Marketing 솔루션을 선택하고 모든 사용자 지정 **게시를 클릭합니다**.

   ![](assets/image2015-3-19-8-41-21.png)

   하이 파이브! 설치가 완료되었습니다.

   >[!CAUTION]
   >
   >Marketing SDK 메시징 프로세스를 비활성화하면 설치가 중단됩니다!

   >[!NOTE]
   >
   >**관련 문서**
   >
   >
   >[Dynamics 2015 On-Prem 및 2016 365 On-Prem 2단계 설치](step-2-of-3-set-up.md)
