---
description: NUR-YYYY-MM-Advanced Grooth - Marketo 문서 - 제품 설명서
title: NUR-YYYY-MM-Advanced Gurture
hide: true
hidefromtoc: true
feature: Programs
source-git-commit: 5aa0c2e3be16219613f0c72235428a962f8d58b3
workflow-type: tm+mt
source-wordcount: '482'
ht-degree: 3%

---

# NUR-YYYY-MM-Advanced Gurture {#nur-yyyy-mm-advanced-nurture}

Marketo Engage 참여 프로그램을 활용하는 고급 Grooth 프로그램의 예입니다. 중첩된 이메일 프로그램은 사용자가 이미 사용한 콘텐츠를 수신하지 못하도록 하거나 각 스트림에서 소비해야 하는 콘텐츠 유형을 제어합니다. 각각의 중첩된 이메일 프로그램에 대해 속성 보고를 실행할 수 있습니다. 채널: &quot;Grooth&quot; 및 중첩된 이메일 프로그램에 대한 전용 &quot;Grooth Email&quot; 채널은 Marketo Engage 이메일 프로그램을 활용하여 하나의 뉴스레터 이메일을 전송합니다. 이메일에는 A/B 테스트가 포함되거나 포함되지 않을 수 있습니다.

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
   <td>육성</td> 
   <td>01 - 구성원 
<br/>02 - 참여 - 성공</td>
   <td>포함</td>
   <td>참여</td>
  </tr>
  <tr> 
   <td>전자 메일 육성</td> 
   <td>01 - 건너뛰기 
<br/>02 - 전송됨
<br/>03 - 참여 - 성공</td>
   <td>포함</td>
   <td>기본값</td>
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
   <td>중첩 프로그램</td> 
   <td> </td>
   <td>01 - 항목 X</td>
  </tr>
  <tr> 
   <td>중첩 프로그램</td> 
   <td> </td>
   <td>02 - 항목 Y</td>
  </tr>
  <tr> 
   <td>중첩 프로그램</td> 
   <td> </td>
   <td>03 - 항목 Z</td>
  </tr>
  <tr> 
   <td>이메일</td> 
   <td>빠른 시작 이메일 템플릿</td>
   <td>01 - 이메일(중첩된 프로그램에 라이브)</td>
  </tr>
   <tr> 
   <td>이메일</td> 
   <td>빠른 시작 이메일 템플릿</td>
   <td>02 - 이메일(중첩된 프로그램에서 라이브)</td>
  </tr>
   <tr> 
   <td>이메일</td> 
   <td>빠른 시작 이메일 템플릿</td>
   <td>03 - 이메일(중첩된 프로그램에 라이브)</td>
  </tr>
  <tr> 
   <td>로컬 보고서</td> 
   <td> </td>
   <td>이메일 성능</td>
  </tr>
  <tr> 
   <td>로컬 보고서</td> 
   <td> </td>
   <td>이메일 링크 성능</td>
  </tr>
  <tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>01 - Grooth에 추가</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>02 - 육성 일시 중지</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>03 - 육성 다시 시작</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>04 - 참여(프로그램 성공)</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>00 - 이메일 건너뛰기(중첩된 각 프로그램에 있음)</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>01 - 이메일 보내기(중첩된 각 프로그램에 있음)</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>02 - 참여 성공(중첩된 각 프로그램에 위치)</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>에셋(중첩된 프로그램 포함) 및 에셋 폴더는 중첩된 프로그램에 상주하여 이메일을 포함합니다.</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>중첩된 프로그램(Assets 폴더 아래에 있음)</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>캠페인 - 상위 육성 프로그램에 모든 스마트 캠페인이 있고 캠페인 폴더도 각 중첩 프로그램에 있습니다</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>보고서</td>
  </tr>
 </tbody> 
</table>

## 내 토큰이 포함됨 {#my-tokens-included}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>토큰 유형</th> 
   <th>토큰 이름</th>
   <th>값</th>
  </tr>
  <tr> 
   <td>텍스트</td> 
   <td><code>{{my.Email-FromAddress}}</code></td>
   <td>PlaceholderFrom.email@mydomain.com</td>
  </tr>
  <tr> 
   <td>텍스트</td> 
   <td><code>{{my.Email-FromName}}</code></td>
   <td><code><--My From Name Here--></code></td>
  </tr>
  <tr> 
   <td>텍스트</td> 
   <td><code>{{my.Email-ReplyToAddress}}</code></td>
   <td>reply-to.email@mydomain.com</td>
  </tr>
 </tbody> 
</table>

프로그램의 스크린샷

## 충돌 규칙 {#conflict-rules}

* **프로그램 태그**
   * 이 구독에서 태그 만들기 - _추천_
   * 무시

* **동일한 이름의 랜딩 페이지 템플릿**
   * 원본 템플릿 복사
   * 대상 템플릿 사용 - _추천_

* **이름이 같은 이미지**
   * 두 파일 모두 보관
   * 이 구독의 항목 바꾸기 - _추천_

* **이름이 같은 이메일 템플릿**
   * 두 템플릿 모두 유지
   * 기존 템플릿 바꾸기 - _추천_

충돌 규칙 스크린샷

## 우수 사례 {#best-practices}

* 현재 브랜드 템플릿을 활용하도록 가져온 프로그램의 템플릿을 업데이트하거나, 코드 조각 또는 적절한 로고/바닥글 정보에 추가하여 브랜드를 반영하도록 새로 가져온 템플릿을 업데이트하는 것이 좋습니다.

* 명명 규칙에 맞게 이 프로그램 예제의 명명 규칙을 업데이트하는 것이 좋습니다.

* 육성 케이던스를 일시 중지하고 다시 시작할 수 있는 규칙이 있는지 확인합니다. 참여 프로그램이 활성화되기 전에 이러한 스마트 캠페인을 활성화하거나 예약해야 합니다.

>[!NOTE]
>
>프로그램 템플릿에서 내 토큰 값 을 업데이트하고 필요할 때 프로그램을 사용할 때마다 업데이트합니다.

>[!TIP]
>
>성공 추적을 위해 &quot;04 - 참여(프로그램 성공)&quot; 캠페인을 활성화하는 것을 잊지 마십시오! 수행 _다음 이전_ 이메일이 전송되었습니다.
