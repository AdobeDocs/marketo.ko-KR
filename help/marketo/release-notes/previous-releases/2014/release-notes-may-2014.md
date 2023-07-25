---
unique-page-id: 2951044
description: 릴리스 노트 - 2014년 5월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2014년 5월
exl-id: c7b5b2c1-ea3d-483b-8a65-c4d6313bfe31
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 0%

---

# 릴리스 노트: 2014년 5월 {#release-notes-may}

다음 기능은 2014년 5월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오. 릴리스 후에 다시 돌아와 각 기능에 대한 자세한 기술 자료 문서에 대한 링크를 찾으십시오.

## 작업 영역 삭제 {#delete-workspace}

이제 다음을 수행할 수 있습니다 [사용하지 않는 작업 영역 삭제](/help/marketo/product-docs/administration/workspaces-and-person-partitions/delete-a-workspace.md). 작업 영역을 삭제하기 전에 모든 자산을 다른 작업 영역으로 이동해야 합니다.

## 첫 번째 캐스트 예약 {#schedule-first-cast}

참여 프로그램에서는 다음에 대한 날짜를 예약할 수 있습니다. [첫 번째 캐스트 실행](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence.md). 예를 들어 케이던스를 2주마다 지정하고 첫 번째 캐스트 날짜를 선택합니다.

![](assets/image2014-9-22-11-3a57-3a36.png)

![](assets/image2014-9-22-11-3a57-3a54.png)

## 향상된 참여 프로그램 {#enhanced-engagement-programs}

이제 모든 사람이 여러 프로그램, 스트림 및 통신 제한을 받습니다.

## 텍스트 이메일의 링크 추적 {#link-tracking-in-text-emails}

[이중 대괄호 추가](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-tracked-links-to-a-text-email.md) 링크가 리디렉션된 Marketo 추적 링크로 변환되어야 하는 시기를 나타내기 위해 이메일의 텍스트 버전에 있는 URL 주위에

>[!NOTE]
>
>**예**
>
>`[[https://www.marketo.com]]`

기본적으로 이메일의 텍스트 버전에서는 링크가 추적되지 않습니다. 링크가 추적 링크로 변환되어야 하는 시기를 나타내려면 이 새 구문을 추가합니다. HTML 링크의 동작은 변경되지 않습니다.  이메일에 추적된 링크를 추가하려면:

* **HTML 버전:** 링크를 삽입합니다. 기본적으로 추적됩니다.
* **텍스트 버전:** 이중 대괄호로 둘러싸인 URL을 입력합니다.

이메일에 추적되지 않은 링크를 추가하려면:

* **HTML 버전:** 링크를 삽입하고 &quot;mktNoTrack&quot; 클래스를 링크에 추가합니다.
* **텍스트 버전:** URL을 입력하기만 하면 됩니다. 기본적으로 추적 해제됩니다.

![](assets/image2014-9-22-12-3a1-3a34.png)

## 샘플 이메일의 링크 마크업 {#link-markup-in-sample-emails}

미리 이메일에서 링크가 어떻게 작동하는지 확인하십시오. 이제 샘플 이메일에 잠재 고객에게 표시되는 것과 동일한 링크가 표시됩니다. 추적 링크로 변환된 링크를 미리 보기하여 메시지가 실제로 수신자에게 표시되는 방식을 보다 잘 이해할 수 있습니다.

## 캠페인 중단 {#abort-campaign}

당황하지 마세요! 실수를 발견하면 새 를 사용하십시오. [캠페인 중단](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/abort-a-smart-campaign.md) 트랙에서 캠페인을 즉시 중단하기 위한 버튼. 캠페인이 중단되었을 때 각 흐름 단계에서 몇 개의 리드가 보류 중이었는지에 대한 개요를 설명하는 알림을 받게 됩니다.

## 일본어, 포르투갈어 및 스페인어로 된 Sales Insight {#sales-insight-in-japanese-portuguese-and-spanish}

AppExchange에서 최신 버전의 Sales Insight를 다운로드하여 일본어, 포르투갈어 및 스페인어를 구사하는 영업 상담원은 기본 언어로 Sales Insight 콘텐츠를 볼 수 있습니다.

![](assets/image2014-9-22-12-3a2-3a12.png)

## 프로그램 멤버십 분석의 프로그램 상태 및 성공 일정 {#program-status-and-success-timeframe-in-program-membership-analysis}

몇 개 보기 [구성원은 각 프로그램 상태에 있습니다.](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/build-a-program-membership-analysis-report-that-lists-leads.md) 프로그램 성공을 달성한 날짜를 포함하여 각 상태로 변경한 경우.

## 이메일 분석의 A/B 테스트 이메일 {#a-b-test-emails-in-email-analysis}

각 보고서 세트 [A/B 테스트 이메일 변형](/help/marketo/product-docs/reporting/revenue-cycle-analytics/email-analysis/build-an-email-analysis-report-that-shows-program-information.md) 이메일 분석에서.

## Analytics 패키징 변경 사항 {#analytics-packaging-changes}

Revenue Cycle Modeler 및 Success Path Analyzer 는 이제 MA Standard Edition에 포함되어 있습니다.

## 모바일 플랫폼 정보 {#mobile-platform-info}

[세그먼트 및 트리거](/help/marketo/product-docs/reporting/basic-reporting/report-activity/build-a-people-performance-report-with-mobile-platform-columns.md) / 모바일 장치에서 이메일을 열고 클릭하는 잠재 고객.
