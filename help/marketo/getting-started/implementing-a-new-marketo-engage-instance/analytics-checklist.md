---
description: 새 Marketo Engage 인스턴스에 대한 Analytics 섹션을 설정합니다.
title: 새로운 인스턴스 모범 사례 - Analytics 검사 목록
hide: true
hidefromtoc: true
feature: Getting Started
source-git-commit: df8087dbaf2b621d0d877eba1c16f160ee9bf460
workflow-type: tm+mt
source-wordcount: '1393'
ht-degree: 0%

---

# 새로운 인스턴스 모범 사례: Analytics 검사 목록 {#new-instance-best-practices-analytics-checklist}

분석 섹션은 마케팅 노력의 성과를 분석하는 글로벌 보고서를 제공합니다. 탐색하는 데 필요한 단계에 대해 알아봅니다.

다음을 잊지 마십시오. [확인 목록 다운로드](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) 진행 상황을 추적할 수 있습니다.

## 트리 {#tree}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>조직: 이름 지정, 폴더 및 보관</td>
    <td><li>보고서 이름 지정 규칙을 사용하여 전역 보고서 탭의 보고서를 구분합니다.</li>
    <ul><li>좋은 명명 규칙 사례의 예로는 [이메일 성능]-[전역]-[180일 이메일 참여]와 같은 [보고서 유형] [전역 및 BU별 태그] [보고서 설명]이 있습니다.</li></ul><br>
    <li>조직 내의 다른 사용자 그룹(예: 영업 팀, 마케팅 리더십)과 공유해야 하는 보고서를 식별하고, 글로벌 보고서용 Analytics의 그룹 보고서 폴더 내에 있는 폴더별로 보고서를 구성합니다.</li> 
    <li>보관은 항상 켜져 있는 보고서이므로 글로벌 보고서 폴더로 제한되어야 합니다.   <ul>
    <li>사업부 구조에 따라 보고하는 경우 관련 사업부를 축소하거나 추가하는 등의 조직 변경 사항으로 보관을 제한합니다.</li>
    </ul></td>
  </tr>
  <tr>
    <td>작업 공간(해당하는 경우)</td>
    <td><li>작업 영역 간에 글로벌 보고서 및 폴더 구조를 복제하여 팀에 대한 일관된 보고를 유지합니다. 이러한 보고서는 그룹 보고서 폴더에 있습니다.</li></td>
  </tr>
  <tr>
    <td>내 보고서</td>
    <td><li>에서 사용하는 데 필요한 보고서 식별 및 만들기 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/creating-reports/understanding-my-reports-and-group-reports">내 보고서</a> 섹션. 이 개인 보고서 섹션을 글로벌 보고서의 샌드박스로 사용합니다. 보고서를 작성하는 사용자만 사용할 수 있습니다.</li>
    <li>내 보고서의 보고서를 그룹 보고서의 보고서와 조정할 수 있도록 조직의 명명 규칙을 사용하여 보고서와 사용량을 식별합니다.</li></td>
  </tr>
  <tr>
    <td>그룹 보고서</td>
    <td><li>그룹 보고서는 조직의 글로벌 보고서이며 조직의 전체 활동에 대해 보고해야 합니다.</li>
    <li>생성 고려 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/clone-a-report-to-group-reports" target="_blank">복제 가능한 핵심 보고서</a> 각 사업부에서 보고서를 가져오는 데 필요한 시간을 줄이고 데이터를 정확하기 위해 가장 자주 사용할 것으로 예상됩니다. 다음에서 세부 사항 보기: <a href="#global-reports">아래 글로벌 보고서 표</a>.
    <ul><li>소스별, 월별 인력 성과 보고서(전체 시간 및 시간 기반)</li>
    <li>프로그램 성과 보고서(비용 월별, 시간 기반)</li>
    <li>이메일 성과 보고서(시간 기반)</li></ul>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/report-email-campaign-performance-across-workspaces" target="_blank">"전역 보고" 켜기</a> 모든 작업 영역의 데이터를 보고서의 설정 탭에 포함하여 이메일 성능 및 이메일 링크 성능 보고서에 포함시킵니다. 작업공간이 두 개 이상인 경우 기본 작업공간에서만 활성화하면 됩니다.</li>
    <p><img src="assets/tip-icon.png" alt="메모 아이콘"> 팁: <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists" target="_blank">스마트 목록</a> 대부분의 보고서에 포함할 필터를 데이터베이스 섹션에 포함합니다. 스마트 목록 기준을 업데이트해야 하는 경우 모든 글로벌 보고서에서 업데이트하지 않고 한 곳에서 업데이트할 수 있습니다.</td>
  </tr>
</tbody>
</table>

## 구독수 {#subscriptions}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>구독수</td>
    <td><li>구현 중에 보고서 결과 및 케이던스를 검토해야 하는 사람에 대해 마케팅 리더와 협력합니다.</li> <li>구독을 사용하여 명명된 사용자 라이선스를 사용하지 않고 조직의 꼭 필요한 사람에게 데이터를 배포합니다.</li>
    <p><img src="assets/tip-icon.png" alt="메모 아이콘"> 팁: 직원들이 실시간 보고서 데이터에 액세스할 수 있도록 하려면 직원들이 보고서를 볼 수 있도록 사용자로 추가해야 합니다.
    <p>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/subscribe-to-a-basic-report">구독 설정</a> 각 팀의 지속적인 모니터링에 대해 원하는 케이던스(일별/주별/월별)로. 다음을 수행할 수도 있습니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/manage-report-subscriptions">모든 구독 보기</a> analytics의 구독 탭 아래에서 한 곳에 있습니다.</li></td>
  </tr>
</tbody>
</table>

## 글로벌 보고서 {#global-reports}

조직 내의 다른 사용자 그룹(예: 영업 팀, 마케팅 리더십)과 공유해야 하는 보고서를 식별합니다. 각 팀/사용자 그룹/비즈니스 단위에 대해 적절한 폴더 구조를 생성하여 그룹 보고서 내에 복제된 보고서를 구성합니다. 다음과 같은 글로벌 보고서 설정을 고려하십시오.

<table>
<thead>
  <tr>
    <th style="width:20%">보고서 유형</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>전자 메일 성능 보고서</td>
    <td><li>올바른 이메일을 선택하여 글로벌, 작업 공간/비즈니스 단위 전체 보고서를 만듭니다.</li>
    <li>복제 가능한 모든 프로그램 템플릿에서 로컬 이메일 성과 보고서를 만듭니다.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame">관련 일정 사용</a> (예: YTD, 최근 90일 등) 표준 이메일 참여 및 전달성 지표에 대한 정확한 보기를 제공할 수 있습니다.</li>
    <p><img src="assets/tip-icon.png" alt="메모 아이콘"> 팁: <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/email-setup/filtering-email-bot-activity">에서 '보트 활동' 필터링 켜기 <strong>관리자 &gt; 이메일</strong></a> 로깅을 방지하거나 보트 활동에 대해 로깅이 활성화되어 있는지 식별합니다. 허용만 할 필터 포함 <a href="https://nation.marketo.com/t5/product-documents/filtering-email-bot-activity-feature-latest-release/ta-p/324860">"봇 활동임"이 "False"로 제한된 상태에서 열림/클릭한 활동</a> (복제 가능한 글로벌 보고서의 스마트 목록).</td>
  </tr>
  <tr>
    <td>사용자 성과 보고서</td>
    <td><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 적절한 것이 좋습니다 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags">채널 및 태그 전략</a> 모든 Marketo Engage 구현에 대해, 획득한 사람 및 마케팅 투자의 ROI를 채널별로 추적할 수 있습니다.
    <p>
    <li>잠재 고객 확보 프로그램의 성과를 측정하는 데 사용할 기준을 결정하고 다음 지표를 기반으로 시간 기반(올해, 마지막 롤링 12개월 보기 또는 180일) 표준 보고서를 만듭니다.</li> <ul><li>고객 확보 프로그램: 개인 확보 Marketo Engage 프로그램.</li>
    <li>개인 소스: 레코드가 데이터베이스에 알려지는 방법에 대한 소스 범주(CRM의 소스 값 목록 기반)
    </li></ul>
    <li>주 또는 월별로 생성된 사람을 측정합니다. 이 보고서는 데이터베이스 증가율과 데이터베이스 크기 제한에 도달하는지 여부를 측정합니다.</li>
    <li>사람 성과 보고서의 지표 필터링 기준 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/editing-reports/add-custom-columns-to-a-person-report">스마트 목록을 사용자 정의 열로 사용.</a></li>
    <p><img src="assets/tip-icon.png" alt="메모 아이콘"> 팁: 마케팅 활동 대신 데이터베이스의 사람 성과 보고서에 추가할 사용자 정의 열에 대한 스마트 목록을 만들면 보고서에서 스마트 목록 이름이 선택되었는지 정확하고 올바르게 확인할 수 있습니다.</td>
  </tr>
  <tr>
    <td>프로그램 성과 보고서</td>
    <td><p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 이 보고서에는에 채널, 진행 상태 및 성공 단계가 정의되어 있어야 합니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/tags/create-a-program-channel"><strong>관리자</strong> &gt; <strong>태그</strong></a>.
    <p>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report">마케팅 전술의 효율성 측정</a> 선택적 프로그램 내.</li>
    <li>마케팅 활동 내의 모범 사례에 따라 프로그램 멤버십을 관리합니다(스마트 캠페인을 사용하여 획득 프로그램, 상태, 성공 상태 업데이트).</li>
    <li>현재 연도 및 연속 12개월 비용을 기반으로 측정합니다.
    <ul><li>유지 관리 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program">기간 비용</a> 는 프로그램 성과 보고서를 활용하는 데 매우 중요합니다.</li></ul>
    <p><img src="assets/tip-icon.png" alt="메모 아이콘"> 팁: 모든 항목을 집계하고 조회하려면 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/quick-wins/import-a-list-of-people">가져온 목록</a> 프로그램 성과 보고서에서 팀이 태그 지정에 적합한 획득 프로그램을 선택했는지 확인합니다. 고려 <a href="https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/programs-and-campaigns/default-programs/create-and-measure-default-programs">기본 프로그램 만들기</a> 가져온 목록이 채널에 적용되지 않을 때 획득 프로그램으로 선택됩니다. 이렇게 하면 가져온 모든 사람이 빈 값 대신 소스, 비즈니스 단위, 채널 등과 관련된 유효한 획득 프로그램을 보유할 수 있습니다.</td>
  </tr>
  <tr>
    <td>랜딩 페이지 성능 보고서</td>
    <td><li>만들기 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-performance-report">랜딩 페이지 성능 보고서</a> 글로벌 보고서로 사용하여 다음을 수행할 수 있습니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/filter-a-landing-page-performance-report">숫자 필터링 및 검토</a> 모든 Design Studio/마케팅 활동 랜딩 페이지를 한 곳에 배치합니다.</li>
    <li>랜딩 페이지가 있는 프로그램의 경우 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-performance-report">프로그램 템플릿 내에서 전용 로컬 보고서 만들기</a> 프로그램 수준에서 성과를 검토할 수 있습니다.</li></td>
  </tr>
  <tr>
    <td>웹 페이지 활동 보고서</td>
    <td><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 다음과 같은 웹 페이지(외부 및 Marketo 랜딩 페이지)만 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website">munchkin JavaScript</a> 활성화됨은 이 보고서에서 추적됩니다. 다음과 같은 Tag Management Platform에 JavaScript 코드를 배치하는 것이 좋습니다. <a href="https://developers.marketo.com/blog/integrating-munchkin-with-google-tag-manager/">Google 태그 관리자</a>모든 웹 페이지에서 코드를 하드코딩하지 않도록 하려면 를 사용하십시오.
    <p>
    <li>만들기 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/web-page-activity-report">웹 페이지 활동 보고서</a> 모든 웹 페이지의 수를 한 곳에서 검토할 수 있는 글로벌 보고서입니다. 외부 웹 페이지 활동은 웹 페이지 활동 보고서에만 반영됩니다.</li></td>
  </tr>
</tbody>
</table>

## 로컬 보고서 {#local-reports}

일부 Marketo Engage 보고서는 일반적으로 보다 제한된 프로그램 및 에셋 세트에 사용되므로 마케팅 활동의 특정 프로그램 내에서 로컬 에셋으로 배포하는 것이 가장 좋습니다. 다음과 같은 기본 보고서 설정을 고려하십시오.

<table>
<thead>
  <tr>
    <th style="width:20%">보고서 유형</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>이메일 링크 성과 보고서</td>
    <td><li>만들기 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report" target="_blank">이메일 링크 성과 보고서</a> 이메일 및 드립 캠페인을 전송하는 프로그램 내에서 사람들이 이메일을 통해 클릭하는 링크에 대한 통찰력을 제공합니다.</li></td>
  </tr>
  <tr>
    <td>캠페인 활동 보고서</td>
    <td><li>만들기 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/campaign-activity-report" target="_blank">캠페인 활동 보고서</a> 마케팅 활동의 운영 폴더 내에서 기간을 선택합니다.</li>
    <li>보고서를 설정하여 각 사용 사례 및 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/campaign-activity-report" target="_blank">캠페인 필터 적용</a> (예: 동작 채점 트리거, 라이프사이클 자격 트리거, 관심 있는 순간 트리거).</li></td>
  </tr>
  <tr>
    <td>참여 스트림 성과 보고서(해당되는 경우)</td>
    <td><li>만들기 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/drip-nurturing/reports-and-notifications/engagement-stream-performance-report" target="_blank">참여 스트림 성과 보고서</a> 참여 프로그램 내에 배포된 콘텐츠 및 스트림의 효과를 측정합니다.</li>
    <li>다음 사용을 고려하십시오. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/group-email-reports-by-segmentations" target="_blank">보고서의 설정 탭에 있는 "세그먼테이션" 필터</a> 보고 데이터를 그룹화할 기준: <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation" target="_blank">세그먼트</a> (예: 개인 소스, 업계) 귀하의 참여 프로그램에 사용됩니다. 이렇게 하면 각 세그먼트의 참여 패턴에 대한 심층적인 통찰력을 얻을 수 있으므로 참여 프로그램(콘텐츠, 스트림, 스트림 케이던스 등)을 개선하기 위해 전략적인 변경을 수행하는 것을 안내합니다.</li></td>
  </tr>
</tbody>
</table>
