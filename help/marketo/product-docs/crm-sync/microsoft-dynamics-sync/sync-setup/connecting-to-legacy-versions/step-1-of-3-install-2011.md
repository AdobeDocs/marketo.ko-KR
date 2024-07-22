---
unique-page-id: 3571805
description: 1단계/3단계 - Marketo 솔루션 설치(2011 온프레미스) - Marketo 문서 - 제품 설명서
title: 1/3단계 - Marketo 솔루션 설치(2011 온프레미스)
exl-id: 6e559b10-5273-4dc2-b98d-49c509cbeff7
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '285'
ht-degree: 0%

---

# 1단계/3단계: Marketo 솔루션 설치(2011 온프레미스) {#step-of-install-the-marketo-solution-on-premises}

Microsoft Dynamics 온-프레미스 및 Marketo Engage을 동기화하려면 먼저 Dynamics에 Marketo 솔루션을 설치해야 합니다.

>[!NOTE]
>
>Marketo을 CRM에 동기화한 후에는 인스턴스를 교체하지 않고 새 동기화를 수행할 수 없습니다.

>[!PREREQUISITES]
>
>ADFS(Active Directory Federation Services)가 구성된 [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0, 2.1 또는 3.0 IFD(인터넷 연결 배포)가 [있어야 합니다](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701){target="_blank"}. **참고**: 링크를 클릭하면 IFD 문서가 자동으로 다운로드됩니다.
>
>시작하기 전에 [Marketo 리드 관리 솔루션을 다운로드하십시오](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}.

>[!NOTE]
>
>**Dynamics 관리자 권한이 필요합니다**.
>
>이 동기화를 수행하려면 CRM 관리자 권한이 필요합니다.

1. Dynamics에 로그인하고 왼쪽 하단 메뉴에서 **[!UICONTROL 설정]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-4-2-11-3a32-3a53.png)

1. 트리에서 **[!UICONTROL 솔루션]**&#x200B;을 선택하십시오.

   ![](assets/image2015-4-2-11-3a35-3a28.png)

1. **[!UICONTROL 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-4-2-11-3a37-3a33.png)

1. **[!UICONTROL 찾아보기]**&#x200B;를 클릭합니다. [다운로드한](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}Marketo 리드 관리 솔루션을 선택합니다. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-11-3a40-3a33.png)

1. 솔루션 정보를 보고 **[!UICONTROL 솔루션 패키지 세부 정보 보기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. 모든 세부 정보를 모두 확인했으면 **[!UICONTROL 닫기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. 솔루션 정보 페이지로 돌아가서 **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-11-3a41-3a48.png)

1. SDK 메시지 옵션 확인란이 선택되어 있는지 확인합니다. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-11-3a42-3a37.png)

   >[!TIP]
   >
   >설치 프로세스를 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

1. 이제 가져오기가 완료될 때까지 기다립니다. 일어나서 스트레칭을 좀 하세요.

   ![](assets/image2015-4-2-11-3a43-3a51.png)

1. Click **[!UICONTROL Close]**.

   >[!NOTE]
   >
   >&quot;Marketo 리드 관리가 경고와 함께 완료되었습니다.&quot;라는 메시지가 표시될 수 있습니다. 이는 완전히 예상되었습니다.

   ![](assets/image2015-4-2-11-3a44-3a44.png)

1. 이제 Marketo Lead Management가 **모든 솔루션** 페이지에 표시됩니다.

   ![](assets/image2015-4-2-11-3a46-3a55.png)

1. Marketo 리드 관리를 선택하고 **[!UICONTROL 모든 사용자 지정 Publish]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-2-11-3a48-3a21.png)

>[!CAUTION]
>
>Marketo SDK 메시징 프로세스를 비활성화하면 설치가 중단됩니다!

>[!MORELIKETHIS]
>
>[2단계/3단계: Dynamics에서 Marketo 동기화 사용자 설정(2011 온-프레미스)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md){target="_blank"}
