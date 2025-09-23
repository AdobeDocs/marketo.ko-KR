---
description: 사용자 정의 도메인 추적을 설정하는 방법 - Marketo 문서 - 제품 설명서
title: 사용자 정의 도메인 추적을 설정하는 방법
exl-id: 6dea7f3d-d44d-4f67-af44-a8963c95c378
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '187'
ht-degree: 7%

---

# 사용자 정의 도메인 추적을 설정하는 방법 {#how-to-set-up-custom-domain-tracking}

사용자 정의 도메인 추적을 사용하면 팀이 판매 이메일에 추가된 모든 추적 가능한 링크에서 고유한 회사 이름을 사용할 수 있습니다. 이 설정을 완료하면 go.yourcompany.com으로 표시되는 이메일에 포함된 모든 링크가 허용 목록에 추가하다되므로 누군가 링크를 마우스로 가리키면 go.toutapp.com 대신 go.yourcompany.com으로 읽혀집니다.

go.toutapp.com 을 가리키는 도메인에 대해 CNAME 레코드를 설정하려면 IT 팀의 도움이 필요합니다. 이 CNAME은 모든 추적 링크(예: go.yourcompany.com)에 표시됩니다.

CNAME이 올바르게 구성되었는지 IT 팀에 확인하면 작업에서 [!UICONTROL Custom Domain Tracking] 페이지에 추가할 수 있습니다.

>[!NOTE]
>
>CNAME이 제대로 설정되지 않았으며 작업에서 사용자 지정 도메인으로 활성화하면 추적 링크와 픽셀이 손상될 수 있습니다.

## 사용자 정의 도메인 추적 활성화 {#enable-custom-domain-tracking}

>[!NOTE]
>
>**관리자 권한이 필요합니다.**

1. 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/how-to-set-up-custom-domain-tracking-1.png)

1. [!UICONTROL Admin Settings]에서 **[!UICONTROL Tracking]**&#x200B;을(를) 선택합니다.

   ![](assets/how-to-set-up-custom-domain-tracking-2.png)

1. [!UICONTROL Custom Domain Tracking] 탭에서 CNAME을 입력하고 **[!UICONTROL Connect]**&#x200B;을(를) 클릭합니다.

   ![](assets/how-to-set-up-custom-domain-tracking-3.png)
