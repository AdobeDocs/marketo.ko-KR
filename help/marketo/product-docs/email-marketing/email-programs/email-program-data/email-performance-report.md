---
unique-page-id: 2359467
description: 이메일 성과 보고서 - Marketo 설명서 - 제품 설명서
title: 이메일 성과 보고서
exl-id: 327d4c0e-951f-4782-989d-4a4c6a513ebc
feature: Email Programs
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: ht
source-wordcount: '489'
ht-degree: 100%

---

# 이메일 성과 보고서 {#email-performance-report}

이메일이 얼마나 제 역할을 잘 수행하고 있는지를 전달됨, 열림, 클릭됨 등과 같은 통계로 확인하려면 이메일 성과 보고서를 만드십시오.

1. [프로그램에서 보고서를 만들고](/help/marketo/product-docs/reporting/basic-reporting/creating-reports/create-a-report-in-a-program.md) **[!UICONTROL Email Performance]** [보고서 유형](/help/marketo/product-docs/reporting/basic-reporting/report-types/report-type-overview.md)을 선택합니다.
1. [보고서 시간대를 변경](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame.md)하고 **[!UICONTROL Report]** 탭을 클릭합니다.
1. 바로 여기입니다! 이제 보고서를 탐색하여 이메일이 어떻게 제 역할을 수행했는지 확인하십시오.

   >[!NOTE]
   >
   >전송 일자 필터는 이메일을 처음 보낸 날짜를 기준으로 합니다.

   ![](assets/email-performance-report.png)

   >[!TIP]
   >
   >이메일 이름을 클릭하여 이메일 미리 보기에서 엽니다.

   >[!NOTE]
   >
   >이메일 성과 보고서에는 이메일이 전송된 후 삭제된 활동을 포함하여 모든 사용자에 대한 활동이 포함됩니다. 적극적인 사람에 대한 활동만 보고 싶을 때가 있을 것입니다. 그런 경우 보고서에서 삭제된 사람을 필터링해야 합니다. **[!UICONTROL Smart List]** 탭을 사용하여 보고서에 대한 [스마트 목록을 만듭니다](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md). 특정 필드를 필터링하지 않는 경우에는 이메일 주소 필터를 **[!UICONTROL is not empty]**&#x200B;로 설정하십시오.

   이메일 성과 보고서에 대한 [보고서 열 선택](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md)에는 다음이 포함됩니다.

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
    <td>서버가 다운되었거나 받은 편지함이 가득 차는 등의 일시적인 상태로 인해 이메일이 거부되었습니다.</td>
  </tr>
  <tr>
    <td>보류 중</td>
    <td>이 숫자는 전송된 총 이메일 수에서 전달된 이메일, 반송된 이메일 및 소프트 바운스 이메일 수를 뺀 결과입니다.</td>
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
    <td>전달할 수 없고 반송 이벤트가 수신되지 않은 이메일 수입니다. 이메일을 보낸 후 3일 이내에 응답을 받지 못하면 이메일은 자동으로 중단됨으로 표시됩니다.</td>
  </tr>
</tbody></table>

>[!NOTE]
>
>이메일에서 클릭한 구독 취소 링크 및 이메일 주소는 보고서의 클릭한 링크에 등록되지 않습니다.

일반적으로 이러한 통계를 기록할 때는 상식을 이용합니다. 예를 들어 누군가 이메일의 링크를 클릭했다면 이메일을 먼저 열었을 것입니다. 이메일 성과 보고서에 대해서는 다음과 같은 특정 규칙을 따릅니다.

* **규칙 1**: 각 이메일 활동 레코드는 _전달됨_, _하드 바운스_, _소프트 바운스_ 또는 _보류 중_ 중 하나로 설정됩니다.

* **규칙 2**: 이메일 레코드에 _[!UICONTROL Opened]_가 표시되면_&#x200B;전달됨&#x200B;_으로 계산됩니다.

* **규칙 3**: 이메일 레코드에 _[!UICONTROL Clicked Email]_또는_[!UICONTROL Unsubscribed]_&#x200B;가 표시되면 _전달됨_ 및 _열림_&#x200B;으로 계산됩니다.

* **규칙 4**: 이메일이 _[!UICONTROL Opened]_이면 바운스는 무시됩니다. 이메일을 열지 않은 경우에는_&#x200B;하드 바운스&#x200B;_가_&#x200B;소프트 바운스&#x200B;_및_&#x200B;전달됨&#x200B;_보다 우선합니다.

* **규칙 5**: 이메일 활동이 전송된 후 3일 후에도 수신되지 않으면 _중단됨_&#x200B;으로 간주됩니다.

>[!NOTE]
>
>* 동일한 캠페인에서 동일한 사용자로의 여러 번에 걸친 전송은 한 번만 카운트됩니다.
>
>* 서로 다른 캠페인에서 동일한 사용자로의 여러 번에 걸친 개별적으로 계산됩니다.

>[!MORELIKETHIS]
>
>* [캠페인 이메일 보고서에서 에셋 필터링](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md){target="_blank"}
>* [이메일 성과 보고서에서 삭제/병합된 레코드 필터링](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-deleted-merged-records-email-performance-report.md){target="_blank"}
>* [이메일 링크 성과 보고서](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report.md){target="_blank"}
