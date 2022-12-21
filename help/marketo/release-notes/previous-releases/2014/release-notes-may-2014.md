---
unique-page-id: 2951044
description: 릴리스 노트 - 2014년 5월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2014년 5월
exl-id: c7b5b2c1-ea3d-483b-8a65-c4d6313bfe31
source-git-commit: 74effe9f8078f8d71e6de01d6e737ddc86978abb
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 0%

---

# 릴리스 노트: 2014년 5월 {#release-notes-may}

다음 기능은 2014년 5월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo Edition을 확인하십시오. 릴리스 후 다시 돌아와 각 기능에 대한 세부 기술 자료 문서에 대한 링크를 확인하십시오!

## 작업 공간 삭제 {#delete-workspace}

이제 다음을 수행할 수 있습니다 [사용하지 않은 작업 공간 삭제](/help/marketo/product-docs/administration/workspaces-and-person-partitions/delete-a-workspace.md). 작업 공간을 삭제하기 전에 모든 자산을 다른 작업 공간으로 이동해야 합니다.

## 첫 번째 캐스트 예약 {#schedule-first-cast}

참여 프로그램에서 [첫 번째 캐스트 실행](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence.md). 예를 들어 2주마다 캐덴스를 지정하고 첫 번째 캐스트의 날짜를 선택합니다.

![](assets/image2014-9-22-11-3a57-3a36.png)

![](assets/image2014-9-22-11-3a57-3a54.png)

## 향상된 참여 프로그램 {#enhanced-engagement-programs}

이제 모든 사람이 여러 프로그램, 스트림 및 통신 제한을 받습니다.

## 텍스트 이메일의 링크 추적 {#link-tracking-in-text-emails}

[대괄호 추가](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-tracked-links-to-a-text-email.md) 링크가 리디렉션된 Marketo 추적 링크로 변환되어야 하는 시기를 나타내기 위해 이메일의 텍스트 버전에 있는 URL에 대해 알아봅니다.

>[!NOTE]
>
>**예**
>
>`[[https://www.marketo.com]]`

기본적으로 이메일의 텍스트 버전에서는 링크가 추적되지 않습니다. 링크를 추적 링크로 변환해야 하는 시기를 나타내기 위해 이 새 구문을 추가합니다. HTML 링크의 동작은 변경되지 않습니다.  추적된 링크를 전자 메일에 추가하려면:

* **HTML 버전:** 링크를 삽입하세요. 기본적으로 추적됩니다.
* **텍스트 버전:** 대괄호로 둘러싸인 URL을 입력합니다.

추적되지 않은 링크를 전자 메일에 추가하려면:

* **HTML 버전:** 링크를 삽입하고 &quot;mktNoTrack&quot; 클래스를 링크에 추가합니다.
* **텍스트 버전:** URL만 입력합니다. 기본적으로 추적되지 않습니다.

![](assets/image2014-9-22-12-3a1-3a34.png)

## 샘플 이메일의 링크 마크업 {#link-markup-in-sample-emails}

미리 이메일에서 링크가 어떻게 동작하는지 확인하십시오. 이제 샘플 이메일에 리드에 표시되는 방법에 대한 링크가 정확하게 표시됩니다. 링크가 추적 링크로 변환된 링크를 미리 보기하면 메시지가 실제로 수신자에게 표시되는 방식을 더 잘 알 수 있습니다.

## 캠페인 중단 {#abort-campaign}

당황하지 마! 실수를 발견했다면 새 [campaign 중단](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/abort-a-smart-campaign.md) 버튼을 클릭하여 캠페인을 즉시 중지할 수 있습니다. 캠페인이 중지되었을 때 각 흐름 단계에서 보류 중인 리드 수에 대한 개요를 제공하는 알림을 받게 됩니다.

## 일본어, 포르투갈어 및 스페인어로 된 영업 인사이트 {#sales-insight-in-japanese-portuguese-and-spanish}

일본어, 포르투갈어 및 스페인어를 사용하는 판매 에이전트가 Sales Insight 컨텐츠를 기본 언어로 볼 수 있도록 AppExchange에서 최신 버전의 Sales Insight를 다운로드합니다.

![](assets/image2014-9-22-12-3a2-3a12.png)

## 프로그램 멤버십 분석의 프로그램 상태 및 성공 일정 {#program-status-and-success-timeframe-in-program-membership-analysis}

몇 개 보기 [구성원은 각 프로그램 상태에 있습니다.](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/build-a-program-membership-analysis-report-that-lists-leads.md) 그리고 프로그램 성공 날짜를 포함하여 각 상태로 변경된 경우

## A/B 이메일 분석에서 이메일 테스트 {#a-b-test-emails-in-email-analysis}

보고서 세트에 대해 [A/B 테스트 이메일 변형](/help/marketo/product-docs/reporting/revenue-cycle-analytics/email-analysis/build-an-email-analysis-report-that-shows-program-information.md) 이메일 분석에서 을 참조하십시오.

## Analytics 패키지 변경 사항 {#analytics-packaging-changes}

Revenue Cycle Modeler 및 Success Path Analyzer 가 이제 MA Standard Edition에 포함되어 있습니다.

## 모바일 플랫폼 정보 {#mobile-platform-info}

[세그먼트 및 트리거](/help/marketo/product-docs/reporting/basic-reporting/report-activity/build-a-people-performance-report-with-mobile-platform-columns.md) 잠재 고객이 모바일 장치에서 이메일을 열고 클릭하는 중입니다.
