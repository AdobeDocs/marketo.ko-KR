---
unique-page-id: 2359467
description: 이메일 성과 보고서 - Marketo 문서 - 제품 설명서
title: 이메일 성과 보고서
exl-id: 327d4c0e-951f-4782-989d-4a4c6a513ebc
feature: Email Programs
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '489'
ht-degree: 2%

---

# 이메일 성과 보고서 {#email-performance-report}

이메일이 게재됨, 열림, 클릭됨 등과 같은 통계로 얼마나 성과가 있는지 확인하려면 이메일 성과 보고서를 만듭니다.

1. [프로그램에서 보고서를 만들고](/help/marketo/product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) **[!UICONTROL Email Performance]** [보고서 형식](/help/marketo/product-docs/reporting/basic-reporting/report-types/report-type-overview.md)을(를) 선택합니다.
1. [보고서 시간대를 변경](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md)하고 **[!UICONTROL Report]** 탭을 클릭합니다.
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
   >이메일 성과 보고서에는 이메일을 보낸 이후 삭제된 활동을 포함하여 모든 사용자에 대한 활동이 포함됩니다. 때로는 활동적인 사람에 대해서만 활동을 보고 싶을 때가 있습니다. 이 경우 보고서에서 삭제된 사람을 필터링해야 합니다. **[!UICONTROL Smart List]** 탭을 사용하여 보고서에 대한 [스마트 목록을 만듭니다](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md). 특정 필드를 필터링하지 않는 경우 전자 메일 주소 필터를 **[!UICONTROL is not empty]**(으)로 설정하십시오.

   전자 메일 성능 보고서에 대한 [보고서 열 선택](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md)에는 다음이 포함됩니다.

   <table><thead>

<tr>
    <th>열</th>
    <th>설명</th>
  </tr></thead>
<tbody>
  <tr>
    <td>하드 바운스</td>
    <td>존재하지 않는 이메일 주소와 같은 영구 조건으로 인해 이메일이 거부되었습니다.</td>
  </tr>
  <tr>
    <td>소프트 바운스</td>
    <td>서버가 다운되었거나 전체 받은 편지함과 같은 임시 조건으로 인해 이메일이 거부되었습니다.</td>
  </tr>
  <tr>
    <td>보류 중</td>
    <td>이 숫자는 전송된 총 수에서 배달된 이메일, 반송된 이메일 및 반송된 소프트 이메일 수를 뺀 것입니다.</td>
  </tr>
  <tr>
    <td>클릭한 링크</td>
    <td>이메일의 링크를 클릭한 이메일 수신자 수입니다.</td>
  </tr>
  <tr>
    <td>구독 취소</td>
    <td>이메일의 구독 취소 링크를 클릭하고 양식을 작성한 이메일 수신자 수입니다.</td>
  </tr>
  <tr>
    <td>중단됨</td>
    <td>게재할 수 없고 바운스 이벤트가 수신되지 않은 이메일 수입니다. 이메일을 보낸 후 3일 이내에 응답을 받지 못하면 이메일은 자동으로 중단됨으로 표시됩니다.</td>
  </tr>
</tbody></table>

>[!NOTE]
>
>이메일에 클릭한 구독 취소 링크 및 이메일 주소는 보고서의 클릭한 링크에 등록되지 않습니다.

일반적으로 이러한 통계를 기록하기 위해 상식을 이용하고자 한다. 예를 들어 누군가 이메일의 링크를 클릭한 경우 이메일이 먼저 열린 것이 분명합니다. Email Performance Report에 대해서는 다음과 같은 특정 규칙을 따릅니다.

* **규칙 1**: 각 전자 메일 활동 레코드는 _배달됨_, _하드 바운스됨_, _소프트 바운스됨_ 또는 _보류 중_ 중 하나로 설정됩니다.

* **규칙 2**: 전자 메일 레코드에 _[!UICONTROL Opened]_이(가) 표시되면_&#x200B;배달됨&#x200B;_으로 계산됩니다.

* **규칙 3**: 전자 메일 레코드에 _[!UICONTROL Clicked Email]_또는_[!UICONTROL Unsubscribed]_&#x200B;이(가) 표시되면 _배달됨_ 및 _열림_&#x200B;으로 계산됩니다.

* **규칙 4**: 전자 메일이 _[!UICONTROL Opened]_이면 바운스가 무시됩니다. 이메일을 열지 않은 경우_&#x200B;하드 바운스&#x200B;_가_&#x200B;소프트 바운스&#x200B;_및_&#x200B;배달됨&#x200B;_보다 우선합니다.

* **규칙 5**: 전자 메일 활동이 전송된 후 3일 후에 수신되지 않으면 _중단됨_&#x200B;으로 간주됩니다.

>[!NOTE]
>
>* 동일한 캠페인에서 동일한 사용자로의 여러 전송은 한 번만 카운트됩니다.
>
>* 서로 다른 캠페인에서 동일한 사람에게 전송된 다중 전송은 별도로 계산됩니다.

>[!MORELIKETHIS]
>
>* [Campaign 이메일 보고서에서 Assets 필터링](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md){target="_blank"}
>* [전자 메일 성능 보고서에서 삭제/병합된 레코드 필터링](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-deleted-merged-records-email-performance-report.md){target="_blank"}
>* [전자 메일 링크 성과 보고서](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report.md){target="_blank"}
