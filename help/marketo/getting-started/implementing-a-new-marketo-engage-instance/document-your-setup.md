---
description: 새 Marketo Engage 인스턴스의 설정을 문서화합니다.
title: 새 인스턴스 모범 사례 - 설정 문서화
feature: Getting Started
exl-id: c64d25e8-564b-487d-824e-7fcbfbf5d8bb
source-git-commit: 14583b7fa148aa2b03c8cf6316b9a106c11717b7
workflow-type: tm+mt
source-wordcount: '454'
ht-degree: 1%

---

# 새로운 인스턴스 모범 사례: 설정 문서화 {#new-instance-best-practices-document-your-setup}

이제 새 Marketo Engage 인스턴스를 설정하는 주요 제품 영역에 대해 알아보았으므로, 다음 단계는 인스턴스 구성 및 기술 스택에 대한 설명서를 만드는 것입니다. 스프레드시트나 프로젝트 관리 애플리케이션을 통해 작성하든, 설명서는 진행 상황을 추적하고 세부 정보를 기록할 수 있을 뿐만 아니라 조직 내에서 미래의 마케터를 위해 인스턴스를 구조화하고 지속 가능하게 유지하는 데 훌륭한 리소스가 됩니다.

## 데이터 {#data}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>목록 가져오기</td>
    <td><li>레코드를 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/getting-started/quick-wins/import-a-list-of-people" target="_blank">Marketo Engage으로 가져오기</a>(으)로 가져올 데이터 원본 목록을 수집합니다.</li>
    <li>여러 데이터 소스에서 가져오는 경우 기본 목록을 사용하거나 개인 레코드에 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo" target="_blank">사용자 지정 필드 만들기</a>를 사용하여 데이터 소스를 나타내는 것이 좋습니다.</li></td>
  </tr>
  <tr>
    <td>데이터베이스 통합</td>
    <td><li>Marketo Engage과 CRM 간의 기본 동기화를 활용하는 경우 시스템 간에 동기화할 필드를 신중하게 고려하십시오. 모든 필드를 동기화할 필요는 없으므로 데이터 흐름에 대해 전략적으로 대처하십시오.</li></td>
  </tr>
</tbody>
</table>

## 사용자 가이드 {#documentation}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>사용자</td>
    <td><li>안전을 위해 인스턴스의 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user#add-a-user" target="_blank">현재 사용자</a>를 문서화합니다. 다음 세부 정보는 최소한으로 포함해야 합니다(그리고 관리 &gt; 사용자 및 역할로 이동하여 모두 볼 수 있음).</li>
    <ul>
    <li>이름</li>
    <li>이메일</li>
    <li>로그인</li>
    <li>역할</li>
    <li>액세스 만료일</li>
    <li>사용자 생성 날짜</li>
    <li>가장 최근 로그인 날짜</li></ul>
    <p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 이에 대해 를 확장하여 역할/권한에 대한 설명서를 포함할 수도 있습니다.
    <p>
    <li>Marketo Engage 제품 관리자로서 Marketo Engage 사용자 목록을 정기적으로 감사하고 업데이트하는 내부 프로세스를 개발하십시오. Adobe Admin Console의 사용자 목록을 변경하려면 .CSV 업로드, 사용자 관리 REST API 사용 등과 같은 <a href="https://helpx.adobe.com/kr/enterprise/using/users.html" target="_blank">일괄 작업</a>을 고려해 보십시오.</li></td>
  </tr>
  <tr>
    <td>조직</td>
    <td><li>합의된 폴더 구조, 프로그램, 에셋 등에 대한 표준 이름 지정 규칙 및 이러한 결정에 영향을 미치는 이유를 문서화합니다. <a href="https://experienceleague.adobe.com/ko/docs/marketo-learn/tutorials/fundamentals/best-practices-to-organize-a-new-instance" target="_blank">모범 사례에 대해 자세히 알아보세요.</a></li></td>
  </tr>
  <tr>
    <td>변경 로그</td>
    <td><li>인스턴스의 변경 내용과 수정 이유를 문서화할 수 있는 변경 로그를 만듭니다. <a href="https://experienceleague.adobe.com/ko/docs/marketo-learn/auditing-an-inherited-instance/develop-an-instance-governance-guide" target="_blank">모범 사례에 대해 자세히 알아보세요.</a></li></td>
  </tr>
  <tr>
    <td>플레이북</td>
    <td><li>내부 사용자가 인스턴스에 온보딩할 수 있도록 사용자 플레이북 또는 관리자 플레이북을 만듭니다.</li></td>
  </tr>
  <tr>
    <td>내부 팀과의 대화</td>
    <td><li>Marketo Engage에 대한 내부 마케팅 팀의 기대치를 Marketo Engage의 역량과 일치시킵니다.</li>
    <li>Marketo Engage 인스턴스에서 이해 당사자가 될 팀을 식별하고 Marketo Engage을 기술로 사용하여 달성하기 위한 목표를 문서화합니다.</li></td>
  </tr>
  <tr>
    <td>작업 공간 및 파티션(해당되는 경우)</td>
    <td><li>작업 공간 정의 방법과 데이터베이스 파티션(예: 모든 사용자 및 비즈니스 섹터를 보여 주는 전역 작업 공간)과 관련된 방법을 문서화합니다.</li>
    <li>새 레코드를 적절한 파티션으로 가져옵니다.</li>
    <li>CRM에서 사용자를 적절한 파티션에 배치하는 값을 정의합니다.</li></td>
  </tr>
</tbody>
</table>
