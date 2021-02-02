---
unique-page-id: 3571805
description: 3단계 중 1단계 - Marketing To 솔루션 설치(2011 온프레미스) - Marketing Docs - 제품 설명서
title: 3단계 중 1단계 - Marketing To 솔루션 설치(2011 온프레미스)
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '291'
ht-degree: 0%

---


# 3단계 중 1단계:Marketing To 솔루션 설치(2011 온-프레미스) {#step-of-install-the-marketo-solution-on-premises}

Microsoft Dynamics 온-프레미스 및 Marketing To를 동기화하려면 먼저 Dynamics에서 Marketing To 솔루션을 설치해야 합니다.

>[!NOTE]
>
>Marketing을 CRM에 동기화한 후에는 인스턴스를 대체하지 않으면 새 동기화를 수행할 수 없습니다.

>[!PREREQUISITES]
>
>[Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0, 2.1 또는 3.0(ADFS)을 구성한 [인터넷 대면 배포](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701)(IFD)가 있어야 합니다. **참고**:링크를 클릭하면 IFD 문서가 자동으로 다운로드됩니다.
>
>[시작하기 전에 Marketing To 리드 관리 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) 솔루션을 다운로드하십시오.

>[!NOTE]
>
>**Dynamics 관리 권한이 필요합니다.**
>
>이 동기화를 수행하려면 CRM 관리자 권한이 필요합니다.

1. **Dynamics**&#x200B;에 로그인하고 왼쪽 하단 메뉴에서 **설정**&#x200B;을 선택합니다.

   ![](assets/image2015-4-2-11-3a32-3a53.png)

1. 트리에서 **솔루션**&#x200B;을 선택합니다.

   ![](assets/image2015-4-2-11-3a35-3a28.png)

1. **가져오기**&#x200B;를 클릭합니다.

   ![](assets/image2015-4-2-11-3a37-3a33.png)

1. **찾아보기**&#x200B;를 클릭합니다. [다운로드한 ](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md)마케팅 리드 관리 솔루션을 선택합니다. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-11-3a40-3a33.png)

1. 솔루션 정보를 보고 **솔루션 패키지 세부 사항 보기**&#x200B;를 클릭합니다.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. 모든 세부 사항을 확인했으면 **닫기**&#x200B;를 클릭합니다.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. 솔루션 정보 페이지로 돌아가서 **다음**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-11-3a41-3a48.png)

1. SDK 메시지 옵션 확인란이 선택되어 있는지 확인합니다. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-2-11-3a42-3a37.png)

   >[!TIP]
   >
   >설치 과정을 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

1. 이제 가져오기가 완료될 때까지 기다립니다. 일어나서 스트레칭을 좀 해라.

   ![](assets/image2015-4-2-11-3a43-3a51.png)

1. **닫기**&#x200B;를 클릭합니다.

   >[!NOTE]
   >
   >&quot;Marketing To Lead Management completed with warning(마케팅 리드 관리가 경고와 함께 완료)&quot;라는 메시지가 표시될 수 있습니다. 이것은 충분히 예상할 수 있다.

   ![](assets/image2015-4-2-11-3a44-3a44.png)

1. 이제 마케팅 리드 관리가 **모든 솔루션** 페이지에 표시됩니다.

   ![](assets/image2015-4-2-11-3a46-3a55.png)

1. 마케팅 리드 관리를 선택하고 **모든 사용자 지정 게시를 클릭합니다.**

   ![](assets/image2015-4-2-11-3a48-3a21.png)

그렇게 나쁘지 않았나요? 어서, 내가 계속 널 따라갈게.

>[!CAUTION]
>
>Marketing SDK 메시징 프로세스를 비활성화하면 설치가 중단됩니다!

>[!MORELIKETHIS]
>
>[3단계 중 2단계:Dynamics에서 Marketing To Sync 사용자 설정(2011 온-프레미스)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-2-of-3-set-up.md)
