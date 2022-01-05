---
description: 3단계 중 1단계 - 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치 - Marketo 문서 - 제품 설명서
title: 3단계 중 1단계 - 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치
source-git-commit: 9ee27e22fec4e0ab85c193be2ea99d3c8b40568b
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 3단계 중 1단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치 {#step-1-of-3-install-the-marketo-solution-ropc}

Microsoft Dynamics 365와 Marketo을 동기화하려면 먼저 Dynamics에서 Marketo 솔루션을 설치해야 합니다. **Dynamics 관리 권한이 필요합니다.**

>[!CAUTION]
>
>* 초기 동기화가 완료되기 전에 사용자 지정 엔티티 동기화를 활성화하지 마십시오. 초기 동기화가 완료되면 이메일을 통해 알림을 받게 됩니다.
>* Dynamics Sync에 대해 Multi-Factor Authentication(MFA)을 사용하도록 설정한 경우 Dynamics가 Marketo과 제대로 동기화되려면 MFA를 비활성화해야 합니다. 자세한 내용은 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support).


>[!NOTE]
>
>Marketo을 CRM에 동기화한 후에는 인스턴스를 바꾸지 않고 새 동기화를 수행할 수 없습니다.

>[!PREREQUISITES]
>
>[Marketo 리드 관리 솔루션 다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md)

1. 에 로그인합니다. **[Microsoft Office 365](https://login.microsoftonline.com/)**.

   ![](assets/image2015-3-16-15-3a58-3a55.png)

1. 클릭 ![](assets/image2015-3-16-16-3a1-3a13.png) 메뉴 및 선택 **CRM**.

   ![](assets/image2015-3-16-16-3a0-3a10.png)

1. 클릭 ![](assets/image2015-5-13-10-3a5-3a8.png) 메뉴 아래의 제품에서 사용할 수 있습니다. 드롭다운 메뉴에서 을(를) 선택합니다 **설정** 을(를) 선택합니다. **솔루션**.

   ![](assets/image2015-5-13-10-3a4-3a1.png)

1. 클릭 **가져오기.**

   ![](assets/image2015-3-19-8-3a34-3a8.png)

1. 클릭 **파일을 선택합니다.** 원하는 Marketo 리드 관리 솔루션을 선택합니다 [다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). 클릭 **다음**.

   ![](assets/image2015-10-9-14-3a44-3a14.png)

1. 솔루션 정보를 보고 **솔루션 패키지 세부 사항 보기**.

   ![](assets/image2015-10-9-15-3a4-3a16.png)

1. 모든 세부 사항을 확인했으면 **닫기**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. 이제 솔루션 정보 페이지로 돌아가 **다음**.

   ![](assets/image2015-10-9-14-3a59-3a24.png)

1. SDK 옵션 확인란이 선택되어 있는지 확인합니다. 클릭 **가져오기**.

   ![](assets/image2015-10-9-15-3a7-3a12.png)

   >[!TIP]
   >
   >설치 프로세스를 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

1. 이제 가져오기가 완료될 때까지 기다립니다. 일어나서 스트레칭을 좀 하세요.

   ![](assets/image2015-3-11-11-3a34-3a9.png)

1. 클릭 **닫기.**

   >[!NOTE]
   >
   >&quot;Marketo 리드 관리가 경고와 함께 완료됨&quot;이라는 메시지가 표시될 수 있습니다. 이것은 충분히 예상되었습니다.

   ![](assets/image2015-3-13-9-3a54-3a39.png)

1. 이제 Marketo 리드 관리가 솔루션 목록에 표시됩니다.

   ![](assets/image2015-3-19-8-3a40-3a38.png)

1. 선택 **Marketo 리드 관리** 을(를) 클릭합니다. **모든 사용자 지정 사항을 게시합니다.**

   ![](assets/image2015-3-19-8-3a41-3a21.png)

   하이 파이브! 설치가 완료되었습니다.

   >[!MORELIKETHIS]
   >
   >[3단계 중 2단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-3-set-up.md)
