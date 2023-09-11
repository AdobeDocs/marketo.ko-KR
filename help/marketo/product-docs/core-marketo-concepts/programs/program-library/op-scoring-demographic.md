---
description: OP-Scoring-Demographic - Marketo 문서 - 제품 설명서
title: OP-점수-인구 통계
feature: Programs
source-git-commit: 720215ea958206931413f2d273a4a058bc051579
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 16%

---

# OP-점수-인구 통계 {#op-scoring-demographic}

이는 인구 통계학적 점수에 Marketo Engage 기본 프로그램을 활용하는 고급(토큰화된) 운영 프로그램의 예입니다. 프로그램의 &quot;내 토큰&quot; 탭에서 점수 값을 보고 편집합니다. &quot;인구 통계학적 점수&quot;라는 사용자 정의 점수 필드가 필요합니다.

추가적인 전략 지원 또는 프로그램 맞춤화에 대한 도움말을 보려면 Adobe 계정 팀에 문의하거나 [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"} 페이지를 가리키도록 업데이트하는 중입니다.

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
   <td>01 - 구성원</td>
   <td>운영</td>
   <td>기본값</td>
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
   <td>스코어</td> 
   <td>인구 통계 점수</td>
   <td>인구 통계학적 점수</td>
  </tr>
 </tbody> 
</table>

## 프로그램에 다음 자산이 포함되어 있습니다. {#program-contains-the-following-assets}

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
   <td>범용 이메일 도메인</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>잘못된 이름</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>잘못된 이름이 업데이트됨</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>잘못된 성</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>잘못된 성이 업데이트됨</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>연간 수익</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>산업</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>직위</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>직원 수</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>소스</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>범용 이메일 도메인</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>잘못된 이름</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>잘못된 성</td>
  </tr>
 </tbody> 
</table>

![](assets/op-scoring-demographic-1.png)

## 내 토큰이 포함됨 {#my-tokens-included}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>토큰 유형</th> 
   <th>토큰 이름</th>
   <th>값</th>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Annual Revenue - High}}</code></td>
   <td>+15</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Annual Revenue - Low}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Annual Revenue - Mid}}</code></td>
   <td>+10</td>
  </tr>
   <tr> 
   <td>스코어</td> 
   <td><code>{{my.Generic Email Domain}}</code></td>
   <td>-2</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Industry - High}}</code></td>
   <td>+10</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Industry - Low}}</code></td>
   <td>+6</td>
  </tr>
   <tr> 
   <td>스코어</td> 
   <td><code>{{my.Industry - Mid}}</code></td>
   <td>+8</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Invalid First Name}}</code></td>
   <td>-5</td>
  </tr>
   <tr> 
   <td>스코어</td> 
   <td><code>{{my.Invalid First Name Updated}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Invalid Last Name}}</code></td>
   <td>-5</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Invalid Last Name Updated}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Job Title - High}}</code></td>
   <td>+15</td>
  </tr>
   <tr> 
   <td>스코어</td> 
   <td><code>{{my.Job Title - Low}}</code></td>
   <td>+5</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Job Title - Mid}}</code></td>
   <td>+10</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Lead Source - High}}</code></td>
   <td>+20</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Lead Source - Low}}</code></td>
   <td>+8</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Lead Source - Mid}}</code></td>
   <td>+10</td>
  </tr>
  <tr> 
   <td>스코어</td> 
   <td><code>{{my.Number of Employees}}</code></td>
   <td>+5</td>
  </tr>
 </tbody> 
</table>

## 충돌 규칙 {#conflict-rules}

* **프로그램 태그**
   * 이 구독에서 태그 만들기 - _추천_
   * 무시

* **동일한 이름의 랜딩 페이지 템플릿**
   * 원본 템플릿 복사 - _추천_
   * 대상 템플릿 사용

* **이름이 같은 이미지**
   * 두 파일 모두 보관 - _추천_
   * 이 구독의 항목 바꾸기

* **이름이 같은 이메일 템플릿**
   * 두 템플릿 모두 유지 - _추천_
   * 기존 템플릿 바꾸기

## 우수 사례 {#best-practices}

* 빌드된 각 캠페인은 사용 사례에만 국한되지 않고 모범 사례 빌드의 예시여야 합니다. 구체적인 해결 과제 및 데이터 문제를 해결하기 위해 스마트 캠페인을 업데이트해야 합니다.

* 명명 규칙에 맞게 이 프로그램 예제의 명명 규칙을 업데이트하는 것이 좋습니다.
