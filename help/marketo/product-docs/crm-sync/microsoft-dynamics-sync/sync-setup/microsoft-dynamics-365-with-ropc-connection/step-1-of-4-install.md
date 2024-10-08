---
description: 1단계/4단계 - 리소스 소유자 암호 제어 연결이 있는 Marketo 솔루션 설치 - Marketo 문서 - 제품 설명서
title: 1/4단계 - 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치
exl-id: aab3bbb8-4e52-4c40-94d1-631af1d63f9f
feature: Microsoft Dynamics
source-git-commit: 2eb61d43f2f470d42e1b50ab8edc99e4e25c23cf
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 1%

---

# 1단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치 {#step-1-of-4-install-the-marketo-solution-ropc}

Microsoft Dynamics 365와 Marketo Engage을 동기화하려면 먼저 Dynamics에 Marketo 솔루션을 설치해야 합니다. **Dynamics 관리자 권한이 필요합니다**.

>[!CAUTION]
>
>* 초기 동기화가 완료되기 전에 사용자 지정 엔티티 동기화를 활성화하지 마십시오. 초기 동기화가 완료되면 이메일로 알림을 받게 됩니다.
>* Dynamics Sync에 대해 MFA(Multi-Factor Authentication)가 활성화되어 있으면 Dynamics가 Marketo과 올바르게 동기화하려면 비활성화해야 합니다. 자세한 내용은 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}에 문의하십시오.

>[!NOTE]
>
>Marketo을 CRM에 동기화한 후에는 인스턴스를 교체하지 않고 새 동기화를 수행할 수 없습니다.

>[!PREREQUISITES]
>
>[Marketo 리드 관리 솔루션 다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md)

1. **[Microsoft Office 365](https://login.microsoftonline.com/)**&#x200B;에 로그인합니다.

   ![](assets/image2015-3-16-15-3a58-3a55.png)

1. ![](assets/image2015-3-16-16-3a1-3a13.png) 메뉴를 클릭하고 **[!UICONTROL CRM]**&#x200B;을 선택합니다.

   ![](assets/image2015-3-16-16-3a0-3a10.png)

1. ![](assets/image2015-5-13-10-3a5-3a8.png) 메뉴를 클릭합니다. 드롭다운 메뉴에서 **[!UICONTROL 설정]**&#x200B;을 선택한 다음 **[!UICONTROL 솔루션]**&#x200B;을 선택합니다.

   ![](assets/image2015-5-13-10-3a4-3a1.png)

1. **[!UICONTROL 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-3-19-8-3a34-3a8.png)

1. **[!UICONTROL 파일 선택]**&#x200B;을 클릭합니다. [다운로드한](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}Marketo 리드 관리 솔루션을 선택합니다. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2015-10-9-14-3a44-3a14.png)

1. 솔루션 정보를 보고 **[!UICONTROL 솔루션 패키지 세부 정보 보기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-10-9-15-3a4-3a16.png)

1. 모든 세부 정보를 모두 확인했으면 **[!UICONTROL 닫기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. 이제 솔루션 정보 페이지로 돌아가서 **[!UICONTROL 다음]**&#x200B;을 클릭하세요.

   ![](assets/image2015-10-9-14-3a59-3a24.png)

1. SDK 옵션 확인란이 선택되어 있는지 확인합니다. **[!UICONTROL 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-10-9-15-3a7-3a12.png)

   >[!TIP]
   >
   >설치 프로세스를 완료하려면 브라우저에서 팝업을 활성화해야 합니다.

1. 이제 가져오기가 완료될 때까지 기다립니다. 일어나서 스트레칭을 좀 하세요.

   ![](assets/image2015-3-11-11-3a34-3a9.png)

1. Click **[!UICONTROL Close]**.

   >[!NOTE]
   >
   >&quot;Marketo 리드 관리가 경고와 함께 완료되었습니다.&quot;라는 메시지가 표시될 수 있습니다. 이는 완전히 예상되었습니다.

   ![](assets/image2015-3-13-9-3a54-3a39.png)

1. 이제 &quot;Marketo 리드 관리&quot;가 솔루션 목록에 표시됩니다.

   ![](assets/image2015-3-19-8-3a40-3a38.png)

1. **[!UICONTROL Marketo 리드 관리]**&#x200B;를 선택하고 **[!UICONTROL 모든 사용자 지정 Publish]**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-19-8-3a41-3a21.png)

   수고하셨습니다! 설치가 완료되었습니다.

   >[!MORELIKETHIS]
   >
   >[2단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}
