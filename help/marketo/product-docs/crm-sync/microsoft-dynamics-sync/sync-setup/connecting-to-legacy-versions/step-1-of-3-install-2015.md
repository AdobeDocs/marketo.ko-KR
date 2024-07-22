---
unique-page-id: 7504736
description: Microsoft Dynamics 2015용 Marketo 설치 온-프레미스 단계 1/3 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 2015용 Marketo 설치 온-프레미스 단계 1/3
exl-id: c9b6d365-15c1-4eff-938c-8433b1fe7f24
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '296'
ht-degree: 0%

---

# 1단계/3단계: Marketo에 대한 동기화 사용자 구성(2015 On-Prem) {#step-of-configure-sync-user-for-marketo-on-premises-2015}

Microsoft Dynamics 2015 온프레미스를 Marketo Engage과 동기화하려면 먼저 Dynamics에 Marketo 솔루션을 설치해야 합니다.

>[!NOTE]
>
>Marketo을 CRM에 동기화하면 새 CRM을 기존 Marketo 인스턴스에 동기화할 수 없습니다.

>[!PREREQUISITES]
>
>Microsoft Dynamics On-Premise를 사용하는 경우 [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0+(ADFS)가 구성된 [IFD(인터넷 연결 배포](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701){target="_blank"})가 있어야 합니다. 참고: 링크를 클릭하면 IFD 문서가 자동으로 다운로드됩니다.
>
>시작하기 전에 [Marketo 리드 관리 솔루션을 다운로드하십시오](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}.

>[!NOTE]
>
>**Dynamics 관리자 권한이 필요합니다**.
>
>이 동기화를 수행하려면 CRM 관리자 권한이 필요합니다.

1. Dynamics에 로그인합니다. **[!UICONTROL Microsoft Dynamics CRM]** 드롭다운 메뉴를 클릭하고 **[!UICONTROL 설정]**&#x200B;을 선택합니다.

   ![](assets/image2015-3-19-8-33-29.png)

1. **[!UICONTROL 설정]**&#x200B;에서 **[!UICONTROL 솔루션]**&#x200B;을 선택합니다.

   ![](assets/image2015-3-19-8-33-3.png)

1. **[!UICONTROL 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-3-19-8-34-8.png)

1. **[!UICONTROL 찾아보기]**&#x200B;를 클릭하고 [다운로드한](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md)솔루션을 선택합니다. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-19-9-20-56.png)

1. 솔루션 정보를 보고 **[!UICONTROL 솔루션 패키지 세부 정보 보기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-11-18-11-12-8.png)

1. 모든 세부 정보를 모두 확인했으면 **[!UICONTROL 닫기]**&#x200B;를 클릭합니다.

   ![](assets/step6.png)

1. 솔루션 정보 페이지로 돌아가서 **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-19-9-21-50.png)

1. SDK 옵션 확인란이 선택되어 있는지 확인합니다. **[!UICONTROL 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-3-19-9-19-12.png)

1. 가져오기가 완료될 때까지 기다립니다.

   >[!TIP]
   >
   >설치 프로세스를 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

   ![](assets/image2015-3-11-11-34-9.png)

1. 원하는 경우 로그 파일을 다운로드하고 **[!UICONTROL 닫기]**&#x200B;를 클릭합니다.

   >[!NOTE]
   >
   >&quot;Marketo 리드 관리가 경고와 함께 완료되었습니다.&quot;라는 메시지가 표시될 수 있습니다. 이는 완전히 예상되었습니다.

   ![](assets/image2015-3-13-9-54-39.png)

1. 이제 Marketo Lead Management가 **[!UICONTROL 모든 솔루션]** 페이지에 표시됩니다.

   ![](assets/image2015-3-19-8-40-38.png)

1. Marketo 솔루션을 선택하고 **[!UICONTROL 모든 사용자 지정 Publish]**&#x200B;를 클릭합니다.

   ![](assets/image2015-3-19-8-41-21.png)

   수고하셨습니다! 설치가 완료되었습니다.

   >[!CAUTION]
   >
   >Marketo SDK 메시징 프로세스를 비활성화하면 설치가 중단됩니다!

   >[!MORELIKETHIS]
   >
   >[Microsoft Dynamics 2015용 Marketo 설치 온-프레미스 단계 2/3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2015.md){target="_blank"}
