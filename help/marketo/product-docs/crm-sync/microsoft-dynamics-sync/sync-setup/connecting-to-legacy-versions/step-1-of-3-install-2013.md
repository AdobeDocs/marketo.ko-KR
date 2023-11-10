---
unique-page-id: 3571813
description: 1단계/3단계 - Dynamics(2013 온-프레미스)에 Marketo 솔루션 설치 - Marketo 문서 - 제품 설명서
title: 1단계/3단계 - Dynamics에서 Marketo 솔루션 설치(2013 온-프레미스)
exl-id: 89f90bca-b459-447f-bbdd-363f232a1059
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---

# 1단계/3단계: Dynamics에서 Marketo 솔루션 설치(2013 온-프레미스) {#step-of-install-the-marketo-solution-in-dynamics-on-premises}

Microsoft Dynamics 온-프레미스 및 Marketo Engage을 동기화하려면 먼저 Dynamics에 Marketo 솔루션을 설치해야 합니다.

>[!NOTE]
>
>Marketo을 CRM에 동기화한 후에는 인스턴스를 교체하지 않고 새 동기화를 수행할 수 없습니다.

>[!PREREQUISITES]
>
>다음을 수행해야 합니다. [인터넷 연결 배포](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701){target="_blank"} (IFD) with [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0, 2.1 또는 3.0(ADFS)이 구성되었습니다. 참고: 링크를 클릭하면 IFD 문서가 자동으로 다운로드됩니다.
>
>[Marketo 솔루션 다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} 시작하기 전에.

>[!NOTE]
>
>**Dynamics 관리자 권한 필요**.
>
>이 동기화를 수행하려면 CRM 관리자 권한이 필요합니다.

1. Dynamics에 로그인합니다. 다음을 클릭합니다. **[!UICONTROL Microsoft Dynamics CRM]** 드롭다운 메뉴 및 선택 **[!UICONTROL 설정]**.

   ![](assets/image2014-12-11-10-3a39-3a41.png)

1. 아래 **[!UICONTROL 설정]**, 선택 **[!UICONTROL 솔루션]**.

   ![](assets/image2014-12-11-10-3a39-3a51.png)

1. 클릭 **[!UICONTROL 가져오기]**.

   ![](assets/image2015-3-26-9-3a52-3a10.png)

1. 클릭 **[!UICONTROL 찾아보기]** 및 선택 [다운로드한 솔루션](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-26-9-3a54-3a1.png)

1. 솔루션 정보를 보고 **[!UICONTROL 솔루션 패키지 세부 정보 보기]**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. 모든 세부 사항을 확인했으면 **[!UICONTROL 닫기]**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. 솔루션 정보 페이지로 돌아가서 **[!UICONTROL 다음]**.

   ![](assets/image2015-3-26-9-3a55-3a17.png)

1. SDK 옵션이 선택되어 있는지 확인합니다. 클릭 **[!UICONTROL 가져오기]**.

   ![](assets/image2015-3-26-10-3a3-3a11.png)

1. 가져오기가 완료될 때까지 기다립니다.

   >[!TIP]
   >
   >설치 프로세스를 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

   ![](assets/image2014-12-11-10-3a41-3a5.png)

1. 로그 파일을 다운로드하고(원하는 경우) **[!UICONTROL 닫기]**.

   >[!NOTE]
   >
   >&quot;Marketo 리드 관리가 경고와 함께 완료되었습니다.&quot;라는 메시지가 표시될 수 있습니다. 이는 완전히 예상되었습니다.

   ![](assets/image2014-12-11-10-3a41-3a14.png)

1. 이제 Marketo Lead Management 가 **[!UICONTROL 모든 솔루션]** 페이지를 가리키도록 업데이트하는 중입니다.

   ![](assets/image2015-3-26-10-3a1-3a21.png)

1. Marketo 솔루션을 선택하고 **[!UICONTROL 모든 사용자 지정 게시]**.

   ![](assets/image2014-12-11-10-3a41-3a32.png)

>[!CAUTION]
>
>Marketo SDK 메시징 프로세스를 비활성화하면 설치가 중단됩니다!

>[!MORELIKETHIS]
>
>[2단계/3단계: Marketo에 대한 동기화 사용자 구성(2013 온-프레미스)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-configure-2013.md){target="_blank"}
