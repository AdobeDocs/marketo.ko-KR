---
unique-page-id: 3571805
description: 3단계 중 1단계 - Marketo 솔루션 설치(2011 온프레미스) - Marketo 문서 - 제품 설명서
title: 3단계 중 1단계 - Marketo 솔루션 설치(2011 온프레미스)
exl-id: 6e559b10-5273-4dc2-b98d-49c509cbeff7
source-git-commit: eac7e219f1babc22dce30717fea4cecb93e1cce7
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 3단계 중 1단계: Marketo 솔루션 설치(2011 온프레미스) {#step-of-install-the-marketo-solution-on-premises}

Microsoft Dynamics 온-프레미스 및 Marketo을 동기화하려면 먼저 Dynamics에서 Marketo 솔루션을 설치해야 합니다.

>[!NOTE]
>
>Marketo을 CRM에 동기화한 후에는 인스턴스를 바꾸지 않고 새 동기화를 수행할 수 없습니다.

>[!PREREQUISITES]
>
>다음을 수행해야 합니다. [인터넷 연결 배포](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) [Active Directory 페더레이션 서비스](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0, 2.1 또는 3.0(ADFS)이 구성되었습니다. **참고**: 링크를 클릭하면 IFD 문서가 자동으로 다운로드됩니다.
>
>[Marketo 리드 관리 솔루션 다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) 시작하기 전에

>[!NOTE]
>
>**Dynamics 관리 권한이 필요합니다.**
>
>이 동기화를 수행하려면 CRM 관리자 권한이 필요합니다.

1. 에 로그인합니다. **Dynamics**, 선택 **설정** 왼쪽 아래 메뉴에 있습니다.

   ![](assets/image2015-4-2-11-3a32-3a53.png)

1. 선택 **솔루션** 나무에 있습니다.

   ![](assets/image2015-4-2-11-3a35-3a28.png)

1. 클릭 **가져오기**.

   ![](assets/image2015-4-2-11-3a37-3a33.png)

1. 클릭 **찾아보기**. 원하는 Marketo 리드 관리 솔루션을 선택합니다 [다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). 클릭 **다음**.

   ![](assets/image2015-4-2-11-3a40-3a33.png)

1. 솔루션 정보를 보고 **솔루션 패키지 세부 사항 보기**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. 모든 세부 사항을 확인했으면 **닫기**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. 솔루션 정보 페이지로 돌아가서 **다음**.

   ![](assets/image2015-4-2-11-3a41-3a48.png)

1. SDK 메시지 옵션 확인란이 선택되어 있는지 확인합니다. 클릭 **다음**.

   ![](assets/image2015-4-2-11-3a42-3a37.png)

   >[!TIP]
   >
   >설치 프로세스를 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

1. 이제 가져오기가 완료될 때까지 기다립니다. 일어나서 스트레칭을 좀 하세요.

   ![](assets/image2015-4-2-11-3a43-3a51.png)

1. 클릭 **닫기**.

   >[!NOTE]
   >
   >&quot;Marketo 리드 관리가 경고와 함께 완료됨&quot;이라는 메시지가 표시될 수 있습니다. 이것은 충분히 예상되었습니다.

   ![](assets/image2015-4-2-11-3a44-3a44.png)

1. 이제 Marketo 리드 관리가 **모든 솔루션** 페이지.

   ![](assets/image2015-4-2-11-3a46-3a55.png)

1. Marketo Lead Management 를 선택하고 **모든 사용자 지정 사항을 게시합니다.**

   ![](assets/image2015-4-2-11-3a48-3a21.png)

그렇게 나쁘진 않았나요? 자, 내가 계속 널 지나갈께.

>[!CAUTION]
>
>Marketo SDK 메시징 프로세스를 비활성화하면 설치가 중단됩니다!

>[!MORELIKETHIS]
>
>[3단계 중 2단계: Dynamics에서 Marketo 동기화 사용자 설정(2011 온프레미스)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md)