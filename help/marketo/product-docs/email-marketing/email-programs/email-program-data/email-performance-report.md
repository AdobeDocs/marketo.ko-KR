---
unique-page-id: 2359467
description: 이메일 성과 보고서 - Marketo 문서 - 제품 설명서
title: 전자 메일 성능 보고서
exl-id: 327d4c0e-951f-4782-989d-4a4c6a513ebc
feature: Email Programs
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '424'
ht-degree: 0%

---

# 전자 메일 성능 보고서 {#email-performance-report}

이메일이 게재됨, 열림, 클릭됨 등과 같은 통계로 얼마나 성과가 있는지 확인하려면 이메일 성과 보고서를 만듭니다.

1. [프로그램에서 보고서 만들기](/help/marketo/product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) 및 선택 **이메일 성능** [보고서 유형](/help/marketo/product-docs/reporting/basic-reporting/report-types/report-type-overview.md).
1. [보고서 시간대 변경](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md) 을(를) 클릭하고 **보고서** 탭.
1. 거기 있어! 이제 보고서를 탐색하여 이메일이 수행된 방식을 확인합니다.

   >[!NOTE]
   >
   >보낸 날짜 필터는 이메일을 보낸 첫 번째 날짜를 기반으로 합니다.

   ![](assets/email-performance-report.png)

   >[!TIP]
   >
   >이메일 이름을 클릭하여 이메일 미리 보기에서 엽니다.

   >[!NOTE]
   >
   >이메일 성과 보고서에는 이메일을 보낸 이후 삭제된 활동을 포함하여 모든 사용자에 대한 활동이 포함됩니다. 때로는 활동적인 사람에 대해서만 활동을 보고 싶을 때가 있습니다. 이 경우 보고서에서 삭제된 사람을 필터링해야 합니다. 사용 **스마트 목록** 탭 [스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 보고서용입니다. 특정 필드를 필터링하지 않으려면 이메일 주소 필터를 다음으로 설정하십시오. **비어 있지 않음**.

   [보고서 열 선택](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md) 이메일 성능 보고서의 경우 다음을 포함합니다.

   | 열 | 설명 |
   |---|---|
   | 하드 바운스 | 존재하지 않는 이메일 주소와 같은 영구 조건으로 인해 이메일이 거부되었습니다. |
   | 소프트 바운스 | 서버가 다운되었거나 전체 받은 편지함과 같은 임시 조건으로 인해 이메일이 거부되었습니다. |
   | 보류 중 | 이 숫자는 전송된 총 수에서 배달된 이메일, 반송된 이메일 및 반송된 소프트 이메일 수를 뺀 것입니다. |
   | 클릭한 링크 | 이메일의 링크를 클릭한 이메일 수신자 수입니다. |
   | 주소 삭제 | 을(를) 클릭한 이메일 수신자 수 **구독 취소** 이메일에 연결하고 양식을 작성했습니다. |

   >[!NOTE]
   >
   >이메일에 클릭한 구독 취소 링크 및 이메일 주소는 보고서의 클릭한 링크에 등록되지 않습니다.

일반적으로 이러한 통계를 기록하기 위해 상식을 이용하고자 한다. 예를 들어 누군가 이메일의 링크를 클릭한 경우 이메일이 먼저 열린 것이 분명합니다. Email Performance Report에 대해서는 다음과 같은 특정 규칙을 따릅니다.

* **규칙 1**: 각 이메일 활동 레코드는 다음 중 하나로 설정됩니다. _전달됨_, _하드 바운스_, _소프트 바운스_, 또는 _보류 중_.

* **규칙 2**: 이메일 기록에 표시되는 경우 *열림*, 다음과 같이 계산됩니다. *전달됨*.

* **규칙 3**: 이메일 기록에 표시되는 경우 _클릭한 이메일_ 또는 _구독 취소됨_, 다음과 같이 계산됩니다. _전달됨_ 및 _열림_.

* **규칙 4**: 이메일이 다음과 같은 경우 _열림_, 바운스는 무시됩니다. 이메일이 열리지 않았다면, _하드 바운스_ 보다 우선함 _소프트 바운스_ 및 _전달됨_.

>[!NOTE]
>
>동일한 캠페인에서 동일한 사용자로의 여러 전송은 한 번만 카운트됩니다.

>[!MORELIKETHIS]
>
>* [Campaign 이메일 보고서에서 자산 필터링](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [이메일 링크 성과 보고서](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report.md)
