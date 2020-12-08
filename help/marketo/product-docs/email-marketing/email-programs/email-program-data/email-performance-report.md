---
unique-page-id: 2359467
description: 이메일 성능 보고서 - 마케팅 문서 - 제품 설명서
title: 이메일 성능 보고서
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '439'
ht-degree: 0%

---


# 이메일 성능 보고서 {#email-performance-report}

이메일 전달, 열기, 클릭 등의 통계 및 이메일 성과를 확인하려면 이메일 성능 보고서를 만듭니다.

1. [프로그램에서 보고서를 만들고](../../../../product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) 이메일 성과 **보고서** 유형 [을 선택합니다](../../../../product-docs/reporting/basic-reporting/report-types/report-type-overview.md).
1. [보고서 시간대를](../../../../product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md) 변경하고 **보고서** 탭을 클릭합니다.
1. 거기 있어! 이제 보고서를 탐색하여 이메일이 어떻게 수행되었는지 확인합니다.

   >[!NOTE]
   >
   >보낸 날짜 필터는 이메일을 보낸 첫 번째 날짜를 기반으로 합니다.

   ![](assets/email-performance-report.png)

   >[!TIP]
   >
   >이메일 미리 보기에서 이메일 이름을 클릭하여 엽니다.

   >[!NOTE]
   >
   >
   >이메일 성능 보고서에는 이메일을 보낸 후 삭제된 사람을 비롯하여 모든 사람을 위한 활동이 포함되어 있습니다. 경우에 따라, 활동적만을 위한 활동을 보고 싶을 수 있습니다. 이 경우 보고서에서 삭제된 사람을 필터링해야 합니다. 스마트 **목록** 탭을 사용하여 [보고서의 스마트 목록](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 을 만듭니다. 특정 필드에서 필터링하지 않는 경우 이메일 주소 필터를 다음으로 설정합니다. **은 비어 있지 않습니다**.

   [이메일 성과 보고서의 보고서 열](../../../../product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md) 선택:

   | 열 | 설명 |
   |---|---|
   | 거친 바운스됨 | 이메일 주소가 존재하지 않는 등의 영구 조건으로 인해 이메일이 거부되었습니다. |
   | 부드러운 바운스됨 | 서버가 다운되거나 전체 받은 편지함과 같은 임시 조건으로 인해 이메일이 거부되었습니다. |
   | 보류 중 | 이 수는 총 전송 횟수에서 배달된 이메일, 바운스된 이메일 및 부드러운 바운스된 이메일 수를 빼서 계산됩니다. |
   | 클릭한 링크 | 이메일의 링크를 클릭한 이메일 받는 사람 수입니다. |
   | 구독 취소 | 이메일의 구독 취소 **** 링크를 클릭하고 양식을 작성한 이메일 수신자 수입니다. |

   >[!NOTE]
   >
   >이메일에 클릭되는 링크 및 이메일 주소를 가입 해지하면 보고서의 클릭한 링크 아래에 등록되지 않습니다.

이런 통계 수치를 기록하기 위해 상식을 활용하려는 게 보통이다. 예를 들어, 누군가 이메일의 링크를 클릭했을 경우, 먼저 이메일을 열었을 것입니다. 이메일 성능 보고서에 대한 다음과 같은 특정 규칙을 따릅니다.

* **규칙 1**:각 이메일 활동 레코드는 다음 중 하나로 설정됩니다. *전달*, *하드*&#x200B;반송 *,*&#x200B;부드러운 반송 *또는*&#x200B;보류 중.

* **규칙 2**:이메일 레코드가 *열렸음*&#x200B;을 표시하면 배달된 것으로 *계산됩니다*.

* **규칙 3**:이메일 레코드에 *클릭한 이메일**또는*&#x200B;구독이 *표시된 경우* 배달된 *후*&#x200B;열린로계산됩니다.

* **규칙 4**:이메일이 *열려*&#x200B;있으면 바운스 수가 무시됩니다. 전자 메일을 열지 않으면 *강력한 바운스된* 메일 *이 소프트 바운스된* 메일 *및*&#x200B;배달보다 우선합니다.

>[!NOTE]
>
>동일한 캠페인에서 동일한 사람에게 전송되는 여러 개가 한 번만 카운트됩니다.

>[!NOTE]
>
>**관련 문서**
>
>* [캠페인 이메일 보고서의 자산 필터링](../../../../product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [이메일 링크 성능 보고서](email-link-performance-report.md)

>



>[!NOTE]
>
>**딥 다이브**
>
>기본 보고의 자세한 [내용을 살펴보십시오](http://docs.marketo.com/display/docs/basic+reporting).

