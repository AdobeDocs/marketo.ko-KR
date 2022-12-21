---
unique-page-id: 2359467
description: 이메일 성과 보고서 - Marketo 문서 - 제품 설명서
title: 전자 메일 성과 보고서
exl-id: 327d4c0e-951f-4782-989d-4a4c6a513ebc
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '424'
ht-degree: 0%

---

# 전자 메일 성과 보고서 {#email-performance-report}

배달됨, 열림, 클릭됨 등의 상태로 이메일이 얼마나 잘 작동하는지 확인하려면 이메일 성과 보고서를 만듭니다.

1. [프로그램에서 보고서 만들기](/help/marketo/product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) 을(를) 선택하고 을(를) 선택합니다. **이메일 성능** [보고서 유형](/help/marketo/product-docs/reporting/basic-reporting/report-types/report-type-overview.md).
1. [보고서 기간 변경](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md) 을 클릭하고 **보고서** 탭.
1. 거기 있어! 이제 보고서를 살펴보고 이메일이 어떻게 수행되었는지 확인합니다.

   >[!NOTE]
   >
   >보낸 날짜 필터는 이메일이 전송된 첫 번째 날짜를 기반으로 합니다.

   ![](assets/email-performance-report.png)

   >[!TIP]
   >
   >이메일 이름을 클릭하여 이메일 미리 보기에서 엽니다.

   >[!NOTE]
   >
   >이메일 성과 보고서에는 이메일을 보낸 후 삭제된 사람을 비롯하여 모든 사람을 위한 활동이 포함되어 있습니다. 경우에 따라 활동가에 대한 활동만 보고 싶을 수 있습니다. 이 경우 삭제된 사람을 보고서에서 필터링해야 합니다. 를 사용하십시오 **Smart List** 탭 대상 [스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 참조하십시오. 특정 필드에서 필터링하지 않는 경우 이메일 주소 필터를 다음과 같이 설정합니다. **비어 있지 않음**.

   [보고서 열 선택](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md) 이메일 성과 보고서의 경우 다음을 포함합니다.

   | 열 | 설명 |
   |---|---|
   | 하드 바운스 | 존재하지 않는 이메일 주소와 같은 영구 조건 때문에 이메일이 거부되었습니다. |
   | 소프트 바운스 | 서버가 다운되거나 전체 받은 편지함과 같은 임시 조건으로 인해 이메일이 거부되었습니다. |
   | 보류 중 | 이 수는 총 전송 수에서 게재된 이메일, 바운스 및 소프트 바운스 수를 뺀 것입니다. |
   | 클릭한 링크 | 이메일에서 링크를 클릭한 이메일 수신자 수입니다. |
   | 주소 삭제 | 클릭한 이메일 수신자 수 **구독 취소** 이메일에 연결하고 양식을 채웁니다. |

   >[!NOTE]
   >
   >이메일에서 클릭한 링크 및 이메일 주소를 가입 해지하면 보고서의 클릭한 링크 아래에 등록되지 않습니다.

일반적으로, 우리는 이러한 통계를 기록하기 위해 상식을 이용하려고 노력한다. 예를 들어 누군가가 이메일의 링크를 클릭한 경우 이메일을 먼저 여는 것이 분명합니다. 전자 메일 성과 보고서에 대해 다음과 같은 특정 규칙을 따릅니다.

* **규칙 1**: 각 이메일 활동 레코드는 다음 중 1개로 설정되어 있으며 1개만 설정됩니다. _배달됨_, _하드 바운스_, _소프트 바운스_, 또는 _보류 중_.

* **규칙 2**: 이메일 레코드가 표시되는 경우 *열림*&#x200B;로 카운트되면 *배달됨*.

* **규칙 3**: 이메일 레코드가 표시되는 경우 _클릭한 이메일_ 또는 _가입 해지됨_&#x200B;로 카운트되면 _배달됨_ 및 _열림_.

* **규칙 4**: 이메일이 _열림_, 바운스 수는 무시됩니다. 이메일이 열리지 않은 경우, _하드 바운스_ 우선 순위 _소프트 바운스_ 및 _배달됨_.

>[!NOTE]
>
>동일한 캠페인에서 동일한 사람에게 전송되는 여러 전송은 한 번만 카운트됩니다.

>[!MORELIKETHIS]
>
>* [캠페인 이메일 보고서에서 자산 필터링](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [이메일 링크 성과 보고서](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report.md)

