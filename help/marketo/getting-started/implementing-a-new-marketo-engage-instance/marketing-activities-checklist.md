---
description: 새 Marketo Engage 인스턴스에 대한 마케팅 활동 섹션을 설정합니다.
title: 새 인스턴스 모범 사례 - 마케팅 활동 검사 목록
feature: Getting Started
exl-id: df536423-7ac8-437a-86c1-3692e68cd9fa
source-git-commit: 7805983cdaff0b99a38aefc2c2467b53f3386da3
workflow-type: tm+mt
source-wordcount: '794'
ht-degree: 1%

---

# 새 인스턴스 모범 사례: 마케팅 활동 검사 목록 {#new-instance-best-practices-marketing-activities-checklist}

마케팅 활동에는 자동화된 마케팅 프로그램을 구성하는 모든 에셋 및 콘텐츠가 보관됩니다. 새 Marketo Engage 인스턴스를 설정할 때 깔끔하고 명확한 조직을 통해 모든 사용자가 다양한 프로그램을 쉽게 찾고 관리할 수 있습니다.

[확인 목록을 다운로드](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx)하고 진행 상황을 추적하는 것이 좋습니다.

## 조직 {#organization}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>이름 지정 규칙</td>
    <td><li>폴더 구조를 빌드하기 전에 구독에 대해 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs#naming-schemes" target="_blank">일관된 명명 규칙</a>을(를) 정의합니다.</li></td>
  </tr>
  <tr>
    <td>폴더 구조</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs#folders" target="_blank">이 예제</a>를 참조하여 일관성 있고 쉽게 탐색할 수 있는 폴더 구조를 빌드합니다.</td>
  </tr>
  <tr>
    <td>프로그램</td>
    <td><li>관리자 섹션에서 만든 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/tags/create-a-program-channel" target="_blank">각 채널</a>에 대한 프로그램 템플릿을 만드십시오. 프로그램 라이브러리에서 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program" target="_blank">프로그램을 가져오기</a>하여 시작할 수 있습니다. 아래의 "Assets" 표에서 세부 사항을 참조하십시오.</li>
    <li>글로벌 프로그램과 로컬 프로그램에서 스마트 캠페인의 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign" target="_blank">흐름 단계</a>를 결정합니다.</li> <li>획득, 멤버십 및 성공 추적을 프로그램 템플릿의 일부로 포함하여 프로세스를 표준화합니다.</li></td>
  </tr>
  <tr>
    <td>보관</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-folders#archive-a-folder" target="_blank">프로그램 및 자산을 보관</a>할 시기에 대한 정책을 결정하십시오. 
    <p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 항목이 보관되면 선택 목록과 보고에서 제거됩니다.</li></td>
  </tr>
  <tr>
    <td>알림</td>
    <td><li>알림 구독</li></td>
  </tr>
</tbody>
</table>

## 자산 {#assets}

>[!NOTE]
>
>프로그램, 랜딩 페이지 및 전자 메일과 같은 마케팅 자산을 별도의 영역에 저장하려면 [관리 섹션 체크리스트](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/admin-section-checklist.md#workspaces-partitions)를 참조하여 작업 영역을 설정하는 방법을 알아보십시오.

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>프로그램 유형</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs" target="_blank">네 가지 프로그램 유형</a>을 이해합니다.</li>
    <li>시작하려면 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-library/program-import-library-overview" target="_blank">프로그램 라이브러리</a>에서 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program" target="_blank">프로그램 템플릿 가져오기</a>.</li>
    <li>이벤트 프로그램을 사용하여 기본 제공 웨비나 플랫폼인 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/create-an-interactive-webinar" target="_blank">대화형 웨비나</a>를 만들고 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/designing-interactive-webinars">룸을 대화형 웨비나 프로그램에 연결</a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-score.html" target="_blank">채점 프로그램</a>을 설정하여 웹 사이트 및 콘텐츠에서 구매 신호를 확인하십시오.</li></td>
  </tr>
  <tr>
    <td>토큰</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.html" target="_blank">토큰</a>을 설정합니다.</li>
    <li>정기적으로 사용되는 프로그램 유형에서 토큰을 사용하여 효율성을 높입니다. 조직에서 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program#nesting-tokens" target="_blank">전역 폴더</a>에 정기적으로 필요한 토큰을 구현하는 것이 좋습니다.</li></td>
  </tr>
  <tr>
    <td>캠페인 일괄 처리</td>
    <td><li>스마트 목록 섹션에서 필터를 사용하여 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/understanding-batch-and-trigger-smart-campaigns.html#batch-campaign" target="_blank">일괄 스마트 캠페인</a>을(를) 설정합니다.</li>
    <li>일별, 주별 및 월별 등의 반복에 대해 스마트 캠페인을 예약합니다.</li></td>
  </tr>
  <tr>
    <td>캠페인 트리거</td>
    <td><li>스마트 목록 섹션 내에서 하나 이상의 트리거를 사용하여 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/understanding-batch-and-trigger-smart-campaigns#trigger-campaign" target="_blank">스마트 캠페인 트리거</a>를 설정합니다.</li>
    <li>'예약' 탭에서 스마트 캠페인을 활성화하여 캠페인 작업을 실행합니다.</li></td>
  </tr>
  <tr>
    <td>랜딩 페이지</td>
    <td><li>프로그램 사용을 위해 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-templates/create-a-free-form-landing-page-template" target="_blank">자유 형식의 랜딩 페이지 템플릿</a> 또는 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/guided-landing-pages/create-a-guided-landing-page" target="_blank">안내 랜딩 페이지 템플릿</a>을 만듭니다.</li></td>
  </tr>
  <tr>
    <td>로컬 Forms</td>
    <td><li>글로벌 양식과 로컬 양식을 비교하여 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/forms/creating-a-form/create-a-form.html" target="_blank">양식 전략</a>을(를) 정의합니다.</li>
    <li>글로벌 양식을 사용하려면 스마트 캠페인을 사용하여 보고를 위한 획득 프로그램을 설정하고 레퍼러 세부 사항을 사용하여 프로그램/캠페인에 사용자를 적절하게 할당합니다.</li></td>
  </tr>
  <tr>
    <td>스마트 목록 구독</td>
    <td><li>매일, 매주 또는 매월(예: 이메일 실적, 개인 실적 등) 받을 보고서에 대해 마케팅 활동 또는 데이터베이스에서 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/edit-a-smart-list-subscription.html" target="_blank">스마트 목록 구독</a>을 설정합니다.</li></td>
  </tr>
  <tr>
    <td>보고서 구독 관리</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/manage-report-subscriptions.html" target="_blank">마케팅 활동 또는 분석에서 보고서 구독을 설정</a>하여 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/subscribe-to-a-basic-report.html" target="_blank">기본 보고서</a> 또는 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/reporting/revenue-cycle-analytics/revenue-explorer/subscribe-to-a-revenue-explorer-report.html" target="_blank">수익 주기 탐색기 보고서</a>를 만듭니다.</li></td>
  </tr>
</tbody>
</table>

## 운영 프로그램 {#operational-programs}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>개인 채점</td>
    <td><li>토큰화된 잠재 고객/개인 점수 책정 프로그램을 구현합니다. 일반 사용자 점수에서 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-library/op-scoring-behavior.html" target="_blank">비헤이비어</a> 및 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-library/op-scoring-demographic.html" target="_blank">인구 통계학적</a> 점수가 모두 분석됩니다.</li>
    <li>시작하려면 Marketo 프로그램 라이브러리에서 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.html" target="_blank">채점 프로그램을 가져오기</a>하십시오.</li></td>
  </tr>
  <tr>
    <td>개인 Source</td>
    <td><li>시스템 관리 필드의 잠재 고객/개인 소스에 값을 할당하는 중앙 집중식 프로그램을 만듭니다.</li>  
    <li>시작하려면 Marketo 프로그램 라이브러리에서 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-library/op-data-management" target="_blank">운영 데이터 관리 프로그램을 가져오기</a>하십시오.</li></td>
  </tr>
  <tr>
    <td>데이터 표준화</td>
    <td><li>중앙 집중식 프로그램을 만들어 수신 데이터를 표준화합니다.</li>
    <li>시작하려면 Marketo 프로그램 라이브러리에서 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-library/op-data-management.html">운영 데이터 관리 프로그램을 가져오기</a>하십시오.</li></td>
  </tr>
  <tr>
    <td>바운스 관리</td>
    <td><li>바운스 관리를 위한 운영 프로그램을 만들어 모든 바운스 세부 정보를 캡처합니다.</li>
    <li>시작하려면 Marketo 프로그램 라이브러리에서 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-library/op-deliverability-management" target="_blank">게재 가능성 관리 프로그램 가져오기</a>.</li></td>
  </tr>
  <tr>
    <td>개인 정보 및 규정 준수</td>
    <td><li><a href="https://business.adobe.com/resources/ebooks/the-gdpr-and-the-marketer.html" target="_blank">GDPR, CASL, CAN-SPAM, CCPA 등과 같은 데이터 개인 정보 보호 및 스팸 법률을 준수하도록 프로그램을 만듭니다.</a></li>
    <p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 이러한 문제에 대해서는 항상 법무팀에 문의하십시오. 변경하기 전에 규정 준수를 유지하기 위한 이전 이니셔티브에 대해 팀에 문의하십시오.</td>
  </tr>
  <tr>
    <td>라이프사이클</td>
    <td><li>개인 상태에 대한 값을 업데이트하여 가망 고객 라이프사이클을 통해 가망 고객을 이동하는 프로그램을 만듭니다.</li>
    <li>시작하려면 Marketo 프로그램 라이브러리에서 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-library/op-lead-management.html" target="_blank">리드 관리 프로그램을 가져오기</a>하십시오.</li></td>
  </tr>
  <tr>
    <td>즐거운 순간(해당되는 경우)</td>
    <td><li>Marketo Sales Insights 앱을 통해 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/interesting-moments/using-interesting-moments.html#how-do-i-create-an-interesting-moment" target="_blank">관련 정보를 영업 팀에 전달</a>하는 중앙 집중식 Smart Campaign을 만드십시오.</li></td>
  </tr>
  <tr>
    <td>구독 센터</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/lead-and-data-management/subscription-center-learn.html" target="_blank">구독/환경 설정 센터</a>를 설정할 때의 이점을 알아보세요.</li>
    <p><img src="assets/tip-icon.png" alt="팁 아이콘">팁: 설정하는 방법이 없으므로 <a href="https://nation.marketo.com/" target="_blank">Marketing Nation 커뮤니티</a>를 방문하여 "구독 센터"를 검색하여 동료들이 사용 중인 다른 방법을 확인하고 사용자의 요구 사항에 가장 적합한 방법을 선택하는 것이 좋습니다.</td></td>
  </tr>
  <tr>
    <td>이메일 전달성</td>
    <td><li>전자 메일 전송 및 게재 가능성 트렌드를 모니터링하기 위해 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/email-programs/email-program-data/email-performance-report" target="_blank">전자 메일 성능 보고서를 만듭니다</a>.</li></td>
  </tr>
</tbody>
</table>
