---
description: 문서 1 상속 - Marketo 문서 - 제품 설명서
title: 문서 1 상속
hide: true
hidefromtoc: true
source-git-commit: 0f34b8ac4283e78027c81bf654d090c5ee78b9ee
workflow-type: tm+mt
source-wordcount: '1149'
ht-degree: 3%

---

# 문서 1 상속 {#inherit-doc-1}

상속된 인스턴스를 감사하는 것은...

다른 관리자로부터 기존 Marketo Engage 인스턴스를 상속받았습니까? 그렇다면 이 문서는 귀하를 위한 것입니다 ...

아래 체크리스트는 상속된 인스턴스에서 빠르게 속도를 높이는 데 도움이 되도록 Marketo 챔피언의 입력과 함께 입력되었습니다.

>[!TIP]
>
>새로운 Marketo Engage 사용자이고 많은 용어를 잘 모를 경우 [Marketo 용어](/help/marketo/getting-started/marketo-glossary.md){target="_blank"}.

## 사용자 및 역할 {#users-and-roles}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>사용자</td> 
   <td><li>사용자가 몇 명입니까?</li>
<li>만료되어야 하는 사용자가 있습니까?</li>
<li>회사에 사용자 삭제에 대한 정책이 있습니까?</li> 
<li>관리자 권한이 있는 사용자는 몇 명입니까?</li>
<li>그러한 사용자 중 다른 역할로 변경해야 합니까?</li> 
<li>이 인스턴스의 API 사용자는 누구입니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>역할</td> 
   <td><li>역할이 몇 개 있습니까?</li>  
<li>각 역할에는 어떤 권한/액세스 권한이 있습니까? 조정해야 합니까?</li>
<li>역할당 사용자가 몇 명입니까?</li>
<li>사용자들은 얼마나 자주 로그인합니까?</li>
<li>각 API 사용자에게는 고유한 사용자 역할이 있습니까? 그렇지 않은 경우 이 기능을 구현하여 문제를 더 쉽게 해결할 수 있습니다.</li> 
<li>사용자 역할 및 권한이 회사 데이터 개인정보 처리방침과 일치합니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>내부 설명서</td> 
   <td><li>조직에서 사용자와 역할이 명확하게 정의됩니까?</li>
<li>새 사용자/관리자를 추가하는 프로세스는 무엇입니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>샌드박스(해당되는 경우)</td> 
   <td><li>샌드박스 인스턴스가 있습니까? 그렇다면 샌드박스에 대한 위의 카테고리를 검토하십시오.</li>
<li>프로그램 가져오기가 샌드박스와 연결되어 있습니까?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 감사 추적 {#audit-trail}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>감사 추적</td> 
   <td><li>인스턴스에서 작업 중인 사람은 누구입니까?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 작업 공간 및 파티션 {#workspaces-and-partitions}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>작업 공간 및 파티션</td> 
   <td><li>보유한 작업 공간 및/또는 파티션은 몇 개입니까?</li>
<li>각 작업 공간 및 파티션의 주요 목적은 무엇입니까?</li>
<li>감사를 받거나 변경해야 합니까?</li>
<li>작업 영역과 파티션 간의 관계는 무엇입니까?</li>
<li>각 작업 영역에 액세스할 수 있는 사용자는 몇 명입니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>내부 설명서</td> 
   <td><li>작업 공간 및 분할 영역은 어떻게 정의됩니까?</li>
<li>인스턴스에 작업 영역을 추가하거나 작업 영역에 사용자를 추가하는 프로세스는 무엇입니까?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 스마트 캠페인 {#smart-campaigns}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>스마트 캠페인 설정</td> 
   <td><li>스마트 캠페인 크기에 대한 제한이 있습니까?</li>
<li>그렇지 않으면 한 개를 추가하는 것이 좋습니다. 스마트 캠페인 제한을 데이터베이스의 25%로 제한하여 과도한 커뮤니케이션이나 워크플로우에서 전체 데이터베이스를 처리하지 않도록 함으로써 브랜드를 보호할 뿐만 아니라 인스턴스의 성능을 보호하는 것이 좋습니다.</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 커뮤니케이션 제한 {#communication-limits}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>커뮤니케이션 제한</td> 
   <td><li>제한이 있나요? 귀사의 비즈니스에 통신 제한이 필요할 수 있는 정책이 있습니까?</li>
<li>Adobe은 비운영 이메일을 차단하여 하루에 1회, 7일에 3회로 커뮤니케이션을 제한하는 것을 권장합니다.</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 태그 {#tags}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>태그</td> 
   <td><li>태그가 몇 개 있습니까? 몇 개의 태그가 사용 중입니까? 추가해야 합니까?</li>
<li>프로그램 내에 태그가 필요합니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>채널</td> 
   <td><li>채널이 몇 개나 됩니까? 몇 대가 사용 중입니까?</li>
<li>모든 채널 프로그램 상태가 적절합니까? 프로그램 내에서 진행 상황을 표시합니까?</li>
<li>특정 프로그램 유형과 관련된 채널?</li>
<li>각 채널에 대해 성공으로 간주되는 상태는 무엇입니까? 이것이 마케팅 목표와 일치합니까?</li>
<li>운영 채널이 적절하게 사용되고 있습니까?</li>
<li>고급 Report Builder(Revenue Cycle Explorer\RCE)의 경우 채널 분석 비헤이비어가 기간 비용을 통합하는 프로그램 관행에 맞게 설정되었습니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>마케팅 달력(해당되는 경우)</td> 
   <td><li>달력 항목 유형은 몇 가지입니까? 그들 모두 여전히 관련이 있습니까?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 데이터베이스 관리 {#database-management}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>필드 관리</td> 
   <td><li>몇 개의 필드가 있습니까? 필드, 사용자 정의 필드 및 API 이름 목록을 검토하려면 "필드 이름 내보내기"를 클릭합니다.</li>
<li>사용자 정의 필드는 몇 개입니까?</li>
<li>얼마나 많은 필드가 사용되고 있습니까? 필드의 관련 에셋을 검토하려면 필드 작업 드롭다운에서 "Export Used By"를 선택합니다.</li>
<li>Marketo Engage과 CRM 간에 몇 개가 동기화됩니까?</li>
<li>CRM 필드가 적절한 오브젝트에 동기화됩니까?</li>
<li>개인 세부 사항에 대한 사용자 정의 보기가 설정되어 있습니까? 있어야 하나?</li>
<li>소스를 기반으로 필드에 대한 이름 지정 규칙이 있습니까? 그렇지 않으면 이를 구현하는 것이 좋습니다.</li>
<li>차단된 필드가 있습니까? 그 이유가 무엇인지 반드시 알아두십시오.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>사용자 지정 활동</td> 
   <td><li>사용자 지정 활동이 있습니까?</li>
<li>그렇다면 이러한 활동을 클릭하여 Marketo 양식, 이메일 또는 랜딩 페이지와 관련이 없는 활동을 이해합니다.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>사용자 지정 개체</td> 
   <td><li>사용자 지정 개체가 몇 개 있습니까? CRM에 동기화되는 방법은 무엇입니까?</li>
<li>프로그램 및 목록 쿼리에서 이러한 사용자 지정 개체를 어떻게 활용합니까?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 통합 {#integrations}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>CRM</td> 
   <td><li>어떤 CRM과 동기화하시겠습니까? Salesforce? MS Dynamics? 베바?</li>
<li>사용자 지정 동기화 또는 양방향 동기화? (KG: 문법 수정 및 중요도 확인)</li>
<li>[Salesforce만 해당] 인스턴스에 사용자 지정 동기화 필터가 구현되었습니까? 사용자 지정 동기화 필터를 식별하거나 사용자 지정 동기화 규칙을 구현하도록 요청하려면 Marketo 지원 센터에 문의하십시오.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>랜딩 페이지</td> 
   <td><li>으로 설정된 도메인은 무엇입니까?</li>
<li>대체 (fallback) 은 무엇으로 설정됩니까?</li>
<li>홈페이지가 무엇으로 설정되어 있습니까?</li>
<li>양식 미리 채우기가 활성화되었습니까?</li>
<li>개인화된 URL이 활성화됩니까?</li>
<li>리디렉션에 대한 규칙이 설정되어 있습니까?</li>
<li>도메인 별칭을 사용할 수 있습니까? 도메인 별칭을 활용하는 방법을 설명서를 통해 추적하고 있습니까?</li>
<li>랜딩 페이지의 보안 도메인이 활성화되어 있습니까? 랜딩 페이지 에셋에 "http" URL이 포함되어 있는지 확인합니다.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>먼치킨</td> 
   <td><li>Munchkin 추적 코드가 웹 사이트(Marketo이 아님)에 있습니까?</li>
<li>"Do Not Track" 브라우저 요청이 활성화되어 있습니까?</li>
<li>Munchkin API가 구성되어 있습니까? 웹 사이트에서 munchkin 코드가 있는 위치에 대한 설명서가 없는 경우 기본 'Analytics'의 '웹 분석 보고서'를 사용하여 빠른 보기를 시작하여 웹 사이트 전체에서 Munchkin 코드가 있는 위치를 파악합니다.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>웹 서비스</td> 
   <td><li>IP 제한이 활성화되어 있습니까? 그래야 하나?</li>
<li>인스턴스에서 API를 호출하는 사용자/앱은 무엇입니까?</li>
<li>API 제한에 도달하고 있습니까, 거의 도달하고 있습니까? 그런 경우에는 API를 늘리거나 인스턴스를 감사하여 해당 API 호출을 줄여 보십시오.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Marketo Sales Insight(해당되는 경우)</td> 
   <td><li>이(가) <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md" target="_blank">MSI 패키지 설치됨</a>?</li>
<li>있음 <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md" target="_blank">최신 버전의 Sales Insight로 업그레이드</a>?</li>
<li>Sales Insight 구성을 완료했습니까? Enterprise/Unlimited 사용자 <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md" target="_blank">여기를 클릭하십시오</a>, 전문 사용자 <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md" target="_blank">여기를 클릭하십시오</a>.</li>
<li>있음 <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-permission-set.md" target="_blank">사용자에게 부여된 액세스 권한</a> 구입한 시트 수에 따라?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 보물상자 {#treasure-chest}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>보물상자</td> 
   <td><li>보물상자에는 무엇이 작동되고 있나요?</li>
<li>켜거나 꺼야 하는 기능이 있습니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>캠페인 검사자</td> 
   <td><li>Campaign Inspector가 켜져 있습니까?</li>
<li>활성화되지 않은 경우 켜서 활성화된 캠페인을 쉽게 식별하고 CRM과 동기화하거나 레코드를 삭제하는 것이 좋습니다.</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## 기타 {#miscellaneous}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>영역</th> 
   <th>리뷰 포커스</th>
   <th>열 3</th>
  </tr> 
  <tr> 
   <td>Marketo Engage 상태 업데이트</td> 
   <td><li>인스턴스가 Marketo Engage 상태 업데이트에 등록되었습니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>승인된 연락처</td> 
   <td><li>지원 포털에서 적절한 공인 연락처를 설정했습니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>경고</td> 
   <td><li>Marketo Engage에서 내부 팀으로 전송되는 활성 경고가 있습니까?</li>
<li>그렇다면 해당 경고가 적절하게 작동하고 있습니까?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>알림</td> 
   <td><li>적절한 관리자 알림을 구독하십니까?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>
