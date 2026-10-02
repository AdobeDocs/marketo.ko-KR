---
unique-page-id: 2360188
description: 스마트 캠페인별로 이메일 통계를 그룹화하는 캠페인 이메일 성능 보고서에 대해 알아봅니다. 열기, 클릭, 바운스 및 구독 취소를 추적하여 캠페인 효과를 측정합니다.
title: 캠페인 이메일 성과 보고서
exl-id: 524222c6-7cf6-4e6d-a1a5-20a771cd9da5
feature: Reporting
TQID: https://experienceleague.adobe.com/pMoHSEmaDbjOVpoVaUi1lvUHBYkyzOwkuF1n7mxpmY0
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
source-git-commit: fd61a23992a0698425987c9c1c307c148c51041e
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 26%
---
# 캠페인 이메일 성과 보고서 {#campaign-email-performance-report}

[스마트 캠페인](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/understanding-batch-and-trigger-smart-campaigns.md)별로 그룹화된 이메일 성과 통계를 보려면 캠페인 이메일 성과 보고서를 실행하십시오.

>[!NOTE]
>
>캠페인 이메일 성과 보고서는 마케팅 활동 프로그램에서만 로컬 자산으로 만들 수 있습니다. Analytics 섹션에서는 사용할 수 없습니다.

1. 프로그램에서 **새로 만들기**&#x200B;를 클릭하고 **새 로컬 자산**&#x200B;을 선택합니다.

   ![](assets/campaign-email-performance-report-1.png)

1. **보고서**&#x200B;를 선택하십시오.

   ![](assets/campaign-email-performance-report-2.png)

1. _유형_ 드롭다운에서 **캠페인 이메일 성과**&#x200B;를 선택합니다. 보고서에 이름을 지정하고 **만들기**&#x200B;를 클릭합니다.

   ![](assets/campaign-email-performance-report-3.png)

1. 보고서의 매개 변수를 정의합니다.

   ![](assets/campaign-email-performance-report-4.png)

1. 완료되면 **보고서** 탭을 클릭하여 보고서를 확인합니다.

Campaign 이메일 성과 보고서에 대해 선택할 수 있는 [열](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md)은(는) 다음과 같습니다.

| 열 | 설명 |
|---|---|
| [!UICONTROL Hard Bounced] | 존재하지 않는 이메일 주소와 같은 영구 조건으로 인해 이메일이 거부되었습니다. |
| [!UICONTROL Soft Bounced] | 서버가 다운되었거나 받은 편지함이 가득 차는 등의 일시적인 상태로 인해 이메일이 거부되었습니다. |
| [!UICONTROL Pending] | 이메일이 아직 전달 중입니다. |
| [!UICONTROL Clicked Link] | 이메일의 링크를 클릭한 이메일 수신자 수입니다. |
| [!UICONTROL Unsubscribed] | 이메일의 **[!UICONTROL Unsubscribe]** 링크를 클릭하고 양식을 작성한 이메일 수신자 수입니다. |

>[!NOTE]
>
>일반적으로 이러한 통계를 기록할 때는 상식을 이용합니다. 예를 들어, 누군가 이메일의 링크를 클릭한 경우 먼저 링크를 클릭한 것이 분명합니다. 따라야 할 특정 규칙을 보려면 [전자 메일 성능 보고서](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md)를 참조하십시오.

>[!MORELIKETHIS]
>
>* [캠페인 전자 메일 보고서에서 Assets 필터링](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [전자 메일 성능 보고서](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md)
