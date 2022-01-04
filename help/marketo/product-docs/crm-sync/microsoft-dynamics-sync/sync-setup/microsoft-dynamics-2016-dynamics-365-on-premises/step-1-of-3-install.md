---
description: Microsoft Dynamics 2016/Dynamics 365 온-프레미스 1/3 - Marketo 문서 - 제품 설명서용 Marketo 설치
title: Microsoft Dynamics 2016/Dynamics 365 온-프레미스 3단계용 Marketo 설치
exl-id: 0a494ae7-87da-4ff9-bb47-990b957533e1
source-git-commit: 3fb93520a653109845c3b40aba20304c6163214f
workflow-type: tm+mt
source-wordcount: '296'
ht-degree: 0%

---

# 3단계 중 1단계: Marketo에 대한 동기화 사용자 구성(2016 On-Prem/Dynamics 365 On-Premises) {#step-of-configure-sync-user-for-marketo-on-premises-2016}

Microsoft Dynamics 2016 On-Prem/Dynamics 365를 Marketo과 동기화하려면 먼저 Marketo 솔루션을 Dynamics에 설치해야 합니다.

>[!NOTE]
>
>Marketo을 CRM에 동기화한 후에는 기존 Marketo 인스턴스에 새 CRM을 동기화할 수 없습니다.

>[!PREREQUISITES]
>
>Microsoft Dynamics On-Premise를 사용하는 경우 다음을 수행해야 합니다 [인터넷 연결 배포](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) [Active Directory 페더레이션 서비스](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0+(ADFS)가 구성되었습니다. 참고: 링크를 클릭하면 IFD 문서가 자동으로 다운로드됩니다.
>
>[Marketo 리드 관리 솔루션 다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) 시작하기 전에

>[!NOTE]
>
>**Dynamics 관리 권한이 필요합니다.**
>
>이 동기화를 수행하려면 CRM 관리자 권한이 필요합니다.

1. 에 로그인합니다. **Dynamics.** 을(를) 클릭합니다. **Microsoft Dynamics CRM** 드롭다운 메뉴를 선택하고 **설정**.

   ![](assets/image2015-3-19-8-33-29.png)

1. 아래 **설정**, 선택 **솔루션**.

   ![](assets/image2015-3-19-8-33-3.png)

1. 클릭 **가져오기**.

   ![](assets/image2015-3-19-8-34-8.png)

1. 클릭 **찾아보기** 솔루션 선택 [다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). 클릭 **다음**.

   ![](assets/image2015-3-19-9-20-56.png)

1. 솔루션 정보를 보고 **솔루션 패키지 세부 사항 보기**.

   ![](assets/image2015-11-18-11-12-8.png)

1. 모든 세부 사항을 확인했으면 **닫기**.

   ![](assets/step6.png)

1. 솔루션 정보 페이지로 돌아가서 **다음**.

   ![](assets/image2015-3-19-9-21-50.png)

1. SDK 옵션 확인란이 선택되어 있는지 확인합니다. 클릭 **가져오기**.

   ![](assets/image2015-3-19-9-19-12.png)

1. 가져오기가 완료될 때까지 기다립니다.

   >[!TIP]
   >
   >설치 프로세스를 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

   ![](assets/image2015-3-11-11-34-9.png)

1. 로그 파일(원하는 경우)을 다운로드하고 **닫기**.

   >[!NOTE]
   >
   >&quot;Marketo 리드 관리가 경고와 함께 완료됨&quot;이라는 메시지가 표시될 수 있습니다. 이것은 충분히 예상되었습니다.

   ![](assets/image2015-3-13-9-54-39.png)

1. 이제 Marketo 리드 관리가 **모든 솔루션** 페이지.

   ![](assets/image2015-3-19-8-40-38.png)

1. Marketo 솔루션을 선택하고 을(를) 클릭합니다 **모든 사용자 지정 게시**.

   ![](assets/image2015-3-19-8-41-21.png)

   하이 파이브! 설치가 완료되었습니다.

   >[!CAUTION]
   >
   >Marketo SDK 메시징 프로세스를 비활성화하면 설치가 중단됩니다!

   >[!MORELIKETHIS]
   >
   >[Dynamics 2015 On-Prem 및 2016 365 On-Prem 3단계 2용 Marketo 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-2-of-3-set-up.md)
