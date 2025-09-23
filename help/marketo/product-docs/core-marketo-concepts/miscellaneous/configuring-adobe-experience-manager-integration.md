---
unique-page-id: 30081815
description: Adobe Experience Manager 통합 구성 - Marketo 문서 - 제품 설명서
title: Adobe Experience Manager 통합 구성
hide: true
hidefromtoc: true
exl-id: 06b2c214-1afb-443f-ae01-0c00fed77dce
feature: Integrations
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 7%

---

# Adobe Experience Manager 통합 구성 {#configuring-adobe-experience-manager-integration}

Adobe Experience Manager(AEM)를 구성하여 AEM 에셋에 액세스하고, 선택하고, Marketo Engage Design Studio로 가져올 수 있습니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!IMPORTANT]
>
>* 이 통합은 AEM의 온-프레미스 구현에서만 작동하며 AEM Cloud Service 구현에는 지원되지 않습니다.
>
>* 현재 이 기능은 Firefox에서만 완전히 지원됩니다. 이 기능은 Safari에서 지원되지 않으며, SameSite 쿠키 설정에 따라 최신 버전의 Chrome에서 작동하지 않을 수 있습니다.

1. Adobe Experience Manager(회사별 URL)로 이동합니다.

   ![](assets/one.png)

1. Adobe으로 로그인하거나 로컬로 로그인할 수 있습니다. 이 예에서는 로컬로 로그인합니다.

   ![](assets/two.png)

1. **[!UICONTROL Tools]**&#x200B;에서 **[!UICONTROL Operations]**&#x200B;을(를) 클릭하고 **[!UICONTROL Web Console]**&#x200B;을(를) 선택합니다.

   ![](assets/2a.png)

1. 브라우저에서 &quot;[!UICONTROL Adobe Granite Cross-Origin Resource Sharing Policy]&quot;을(를) 검색합니다(Windows에서는 ctrl+f, Mac에서는 cmd+f).

   ![](assets/three.png)

1. 오른쪽의 **+** 기호를 클릭합니다.

   ![](assets/four.png)

1. **[!UICONTROL Allowed Origins (Regexp)]** 텍스트 상자에 `https://.*\.marketo\.com`을(를) 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/five-psd.png)

1. 페이지 상단의 헤더에서 **[!UICONTROL Web Console]**&#x200B;을(를) 클릭하고 **[!UICONTROL System Information]**&#x200B;을(를) 선택합니다.

   ![](assets/six.png)

1. 서버 정보에서 **[!UICONTROL Restart]** 단추를 클릭합니다.

   ![](assets/seven.png)

1. **[!UICONTROL OK]**&#x200B;을(를) 클릭하여 확인합니다.

   ![](assets/eight.png)

1. Marketo Engage에서 **[!UICONTROL Admin]**&#x200B;을 클릭합니다.

   ![](assets/nine.png)

1. 통합에서 **[!UICONTROL Adobe Experience Manager]**&#x200B;을(를) 선택합니다.

   ![](assets/ten.png)

1. **[!UICONTROL Edit]**&#x200B;를 클릭합니다.

   ![](assets/eleven.png)

1. AEM URL을 입력하고 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/twelve.png)
