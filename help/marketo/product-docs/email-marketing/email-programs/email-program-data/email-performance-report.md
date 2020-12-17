---
unique-page-id: 2359467
description: 이메일 성과 보고서 - 마케팅 문서 - 제품 설명서
title: 이메일 성능 보고서
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '437'
ht-degree: 0%

---


# 이메일 성능 보고서 {#email-performance-report}

이메일 성능이 배달, 열림, 클릭됨 등 통계와 어떻게 다른지 확인하려면 이메일 성능 보고서를 만듭니다.

1. [프로그램에서 보고서를 만들고 ](../../../../product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) 이메일  **성능 보고서** [유형을 선택합니다](../../../../product-docs/reporting/basic-reporting/report-types/report-type-overview.md).
1. [보고서 시간 프레임을 변경하고 ](../../../../product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md) Reporttab을  **** 클릭합니다.
1. 거기 있었구나! 이제 보고서를 탐색하여 이메일의 성과를 확인할 수 있습니다.

   >[!NOTE]
   >
   >보낸 날짜 필터는 이메일을 보낸 첫 번째 날짜를 기준으로 합니다.

   ![](assets/email-performance-report.png)

   >[!TIP]
   >
   >이메일 미리 보기에서 이메일 이름을 클릭하여 엽니다.

   >[!NOTE]
   >
   >
   >이메일 성과 보고서에는 이메일을 보낸 후 삭제된 사람을 비롯하여 모든 사람을 위한 활동이 포함되어 있습니다. 경우에 따라, 활동적인 사람들을 위한 활동만 보고 싶어합니다. 이 경우 보고서에서 삭제된 사람을 필터링해야 합니다. **스마트 목록** 탭을 사용하여 [보고서에 대한 스마트 목록](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)을 만듭니다. 특정 필드에서 필터링하지 않는 경우 이메일 주소 필터를 다음으로 설정합니다.**이(가) 비어 있지 않습니다**.

   [이메일 성과 ](../../../../product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md) 보고서에 대해 보고서 열을 선택합니다.

   | 열 | 설명 |
   |---|---|
   | 하드 바운스됨 | 존재하지 않는 이메일 주소와 같은 영구 조건으로 인해 이메일이 거부되었습니다. |
   | 부드러운 바운스됨 | 서버가 다운되거나 전체 받은 편지함과 같은 임시 조건으로 인해 이메일이 거부되었습니다. |
   | 보류 중 | 이 수는 총 보낸 횟수에서 배달된 이메일, 바운스된 이메일, 바운스된 소프트 바운스된 이메일 수를 빼서 계산됩니다. |
   | 클릭한 링크 | 이메일의 링크를 클릭한 이메일 받는 사람 수입니다. |
   | 구독 취소 | 이메일의 **가입 해지** 링크를 클릭하고 양식을 작성한 이메일 수신자 수입니다. |

   >[!NOTE]
   >
   >이메일에서 클릭한 링크 및 이메일 주소를 가입 해지하면 보고서의 클릭한 링크 아래에 등록되지 않습니다.

일반적으로, 우리는 이러한 통계를 기록하기 위해 상식을 이용하려고 노력한다. 예를 들어 이메일에 있는 링크를 클릭한 사람이 먼저 이메일을 연 것이 분명합니다. 이메일 성능 보고서에 대한 다음과 같은 특정 규칙을 따릅니다.

* **규칙 1**:각 이메일 활동 레코드는 다음 중 한 개로 설정됩니다. *배달됨*,  *강하게*&#x200B;반송됨 *,*&#x200B;부드러운 반송 *또는*&#x200B;보류 중.

* **규칙 2**:이메일 레코드에  *열림*&#x200B;이 표시되면 배달된 것으로  *계산됩니다*.

* **규칙 3**:이메일 레코드에 클릭한  *이메일 또* 는 구독되지 않은 *이메일*&#x200B;이 **  표시되면  *배달 및*&#x200B;열음으로계산됩니다.

* **규칙 4**:이메일이  *열려* 있으면 바운스 수가 무시됩니다. 전자 메일을 열지 않은 경우 *Hard Bo수*&#x200B;가 *Soft Bounded* 및 *Delivered*&#x200B;보다 우선합니다.

>[!NOTE]
>
>동일한 캠페인에서 동일한 사람에게 전송되는 여러 개 방문은 한 번만 카운트됩니다.

>[!MORELIKETHIS]
>
>* [캠페인 이메일 보고서의 자산 필터링](../../../../product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [이메일 링크 성능 보고서](email-link-performance-report.md)

>



>[!NOTE]
>
>**자세히 알아보기**
>
>[기본 보고](http://docs.marketo.com/display/docs/basic+reporting)에서 자세히 알아보십시오.

