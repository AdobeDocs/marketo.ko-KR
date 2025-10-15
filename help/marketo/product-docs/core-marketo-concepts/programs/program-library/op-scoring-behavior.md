---
description: OP-Scoring-Behavior - Marketo 문서 - 제품 설명서
title: OP-채점-행동
feature: Programs
exl-id: c564a301-0054-431a-8f0f-0299cd91b59c
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 22%

---

# OP-채점-행동 {#op-scoring-behavior}

이 예는 Marketo Engage 기본 프로그램을 사용한 동작 점수에 대한 고급(토큰화된) 운영 프로그램입니다. 프로그램의 &quot;내 토큰&quot; 탭에서 점수 값을 보고 편집합니다. &quot;동작 점수&quot;라는 사용자 정의 점수 필드가 필요합니다.

추가 전략 지원 또는 프로그램 사용자 지정에 도움이 필요하면 Adobe 계정 팀에 문의하거나 [Adobe Professional Services](https://business.adobe.com/kr/customers/consulting-services/main.html){target="_blank"} 페이지를 방문하십시오.

## 채널 요약 {#channel-summary}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>채널</th>
   <th>멤버십 상태</th>
   <th>Analytics 동작</th>
   <th>프로그램 유형</th>
  </tr>
  <tr>
   <td>운영</td>
   <td>구성원</td>
   <td>운영</td>
   <td>기본</td>
  </tr>
 </tbody>
</table>

## 전제 조건 필드 {#prerequisite-fields}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>유형</th>
   <th>알기 쉬운 이름</th>
   <th>API 이름</th>
  </tr>
  <tr>
   <td>점수</td>
   <td>비헤이비어 점수</td>
   <td>BehaviorScore</td>
  </tr>
 </tbody>
</table>

## 프로그램에는 다음 Assets이 포함되어 있습니다 {#program-contains-the-following-assets}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>유형</th>
   <th>템플릿 이름</th>
   <th>에셋 이름</th>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>이메일 - 이메일의 클릭 수 링크</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>양식 - 연락처 양식 작성</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>양식 - 컨텐츠 양식 작성</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>양식 - 기본 양식 작성</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>양식 - 이벤트 양식 작성</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>웹 - 모든 PDF 다운로드</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>웹 - PPC 점수</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>웹 - 방문 주요 웹 페이지</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>웹 - 하루 만에 여러 웹 페이지 방문</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>라이브 이벤트 - 참석됨</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>Tradeshow - 영향을 받음</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>박람회 - 방문 부스</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>웨비나 - 출석</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>점수 감소 - 활동 없음</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>점수 감소 - 방문자 웹 페이지를 원하지 않음</td>
  </tr>
  <tr>
   <td>폴더</td>
   <td> </td>
   <td>상호 작용</td>
  </tr>
  <tr>
   <td>폴더</td>
   <td> </td>
   <td>프로그램 상태 변경</td>
  </tr>
  <tr>
   <td>폴더</td>
   <td> </td>
   <td>점수 감소</td>
  </tr>
 </tbody>
</table>

![](assets/op-scoring-behavior-1.png)

## 내 토큰이 포함됨 {#my-tokens-included}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>토큰 유형</th>
   <th>토큰 이름</th>
   <th>값</th>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Decrease Score - No Activity}}</code></td>
   <td>-10</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Decrease Score - Visits Undesirable Web Pages}}</code></td>
   <td>-5</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Email - Clicks Link}}</code></td>
   <td>+2</td>
  </tr>
   <tr>
   <td>점수</td>
   <td><code>{{my.Form - Fills Out Contact Form}}</code></td>
   <td>+30</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Form - Fills Out Content Form}}</code></td>
   <td>+15</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Form - Fills Out Default Form}}</code></td>
   <td>+10</td>
  </tr>
   <tr>
   <td>점수</td>
   <td><code>{{my.Form - Fills-out Event Form}}</code></td>
   <td>+15</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Live Event - Attended}}</code></td>
   <td>+30</td>
  </tr>
   <tr>
   <td>점수</td>
   <td><code>{{my.Tradeshow - Influenced}}</code></td>
   <td>+20</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Tradeshow - Visited Booth}}</code></td>
   <td>+5</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Web - Downloaded Any PDF}}</code></td>
   <td>+5</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Web - PPC Scoring}}</code></td>
   <td>+15</td>
  </tr>
   <tr>
   <td>점수</td>
   <td><code>{{my.Web - Visits Key Web Pages}}</code></td>
   <td>+5</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Web - Visits Multiple Web Pages in 1 Day}}</code></td>
   <td>+5</td>
  </tr>
  <tr>
   <td>점수</td>
   <td><code>{{my.Webinar - Attended}}</code></td>
   <td>+20</td>
  </tr>
 </tbody>
</table>

## 충돌 규칙 {#conflict-rules}

* **프로그램 태그**
   * 이 구독에서 태그 만들기 - _권장_
   * 무시

* **같은 이름의 랜딩 페이지 템플릿**
   * 원본 템플릿 복사 - _권장_
   * 대상 템플릿 사용

* **이름이 같은 이미지**
   * 두 파일 모두 보관 - _권장_
   * 이 구독의 항목 바꾸기

* **같은 이름의 전자 메일 서식 파일**
   * 두 템플릿 모두 보관 - _권장_
   * 기존 템플릿 바꾸기

## 우수 사례 {#best-practices}

* 빌드된 각 캠페인은 사용 사례에만 국한되지 않고 모범 사례 빌드의 예시여야 합니다. 구체적인 해결 과제 및 데이터 문제를 해결하기 위해 스마트 캠페인을 업데이트해야 합니다.

* 명명 규칙에 맞게 이 프로그램 예제의 명명 규칙을 업데이트하는 것이 좋습니다.
