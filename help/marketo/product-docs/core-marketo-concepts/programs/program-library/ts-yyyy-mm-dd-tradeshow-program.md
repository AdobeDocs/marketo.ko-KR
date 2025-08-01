---
description: TS-YYYY-MM-DD-Tradeshow 프로그램 - Marketo 문서 - 제품 설명서
title: TS-YYYY-MM-DD-Tradeshow 프로그램
feature: Programs
exl-id: 39ef8d6e-392b-456e-a925-b1f6c2cb81d8
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '410'
ht-degree: 7%

---

# TS-YYYY-MM-DD-Tradeshow 프로그램 {#ts-yyyy-mm-dd-tradeshow-program}

Marketo Engage 이벤트 프로그램을 활용하는 초대 및 후속 이메일이 포함된 박람회 프로그램의 예입니다.

추가 전략 지원 또는 프로그램 사용자 지정에 도움이 필요하면 Adobe 계정 팀에 문의하거나 [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"} 페이지를 방문하십시오.

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
   <td>이벤트</td>
   <td>01-초대됨
   대기자 명단에 등록된 <br/>02
   <br/>03-등록됨
   <br/>04 방문 부스
   <br/>05 참여 쇼 - 성공
   <br/>06 참여 게시물 쇼 - 성공</td>
   <td>포함</td>
   <td>이벤트</td>
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
   <td>이메일</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">빠른 시작 이메일 템플릿</a></td>
   <td>01-이메일-감사</td>
  </tr>
   <tr>
   <td>이메일</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">빠른 시작 이메일 템플릿</a></td>
   <td>02a- 이메일 - 초대</td>
  </tr>
  <tr>
  <tr>
   <td>로컬 보고서</td>
   <td> </td>
   <td>이메일 성능</td>
  </tr>
  <tr>
   <td>로컬 보고서</td>
   <td> </td>
   <td>프로그램 성능</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>00 - 획득 프로그램 캡처</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>01 - 초대 보내기</td>
  </tr>
   <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>02 - 후속 이메일 보내기</td>
  </tr>
   <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>03 - 후속 이메일 참여(성공)</td>
  </tr>
  <tr>
   <td>폴더</td>
   <td> </td>
   <td>Assets - 모든 크리에이티브 에셋 보유
<br/>(전자 메일 및 랜딩 페이지의 하위 폴더)</td>
  </tr>
  <tr>
   <td>폴더</td>
   <td> </td>
   <td>캠페인 - 모든 스마트 캠페인 저장</td>
  </tr>
  <tr>
   <td>폴더</td>
   <td> </td>
   <td>보고서</td>
  </tr>
 </tbody>
</table>

![](assets/ts-yyyy-mm-dd-tradeshow-program-1.png)

## 내 토큰이 포함됨 {#my-tokens-included}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>토큰 유형</th>
   <th>토큰 이름</th>
   <th>값</th>
  </tr>
  <tr>
   <td>캘린더 파일</td>
   <td><code>{{my.AddToCalendar}}</code></td>
   <td>세부 사항을 보려면 두 번 클릭</td>
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
  <tr>
   <td>텍스트</td>
   <td><code>{{my.Event-Date}}</code></td>
   <td><code><--My Event Date--></code></td>
  </tr>
   <tr>
   <td>리치 텍스트</td>
   <td><code>{{my.Event-Booth#}}</code></td>
   <td><code><--My Booth Number--></code></td>
  </tr>
   <tr>
   <td>텍스트</td>
   <td><code>{{my.Event-City}}</code></td>
   <td><code><--My Event City Here--></code></td>
  </tr>
  <tr>
   <td>텍스트</td>
   <td><code>{{my.Event-Date}}</code></td>
   <td><code><--My Event Date--></code></td>
  </tr>
  <tr>
   <td>텍스트</td>
   <td><code>{{my.Event-Time}}</code></td>
   <td><code><--My Event Time + TimeZone--></code></td>
  </tr>
  <tr>
   <td>텍스트</td>
   <td><code>{{my.Event-Title}}</code></td>
   <td><code><--My Event Title Here--></code></td>
  </tr>
  <tr>
   <td>텍스트</td>
   <td><code>{{my.Event-Type}}</code></td>
   <td>박람회</td>
  </tr>
 </tbody>
</table>

## 충돌 규칙 {#conflict-rules}

* **프로그램 태그**
   * 이 구독에서 태그 만들기 - _권장_
   * 무시

* **같은 이름의 랜딩 페이지 템플릿**
   * 원본 템플릿 복사
   * 대상 템플릿 사용 - _권장_

* **이름이 같은 이미지**
   * 두 파일 모두 보관
   * 이 구독의 항목 바꾸기 - _권장_

* **같은 이름의 전자 메일 서식 파일**
   * 두 템플릿 모두 유지
   * 기존 템플릿 바꾸기 - _권장_

## 우수 사례 {#best-practices}

* 웨비나 프로그램을 가져온 후 양식을 로컬 에셋에서 Design Studio에 있는 글로벌 에셋으로 이동합니다.
   * Design Studio에서 양식 수를 줄이고 더 많은 글로벌 에셋을 사용하면 프로그램 설계 및 관리 거버넌스에서 더 많은 확장성을 얻을 수 있습니다. 또한 필드, 옵트인 언어 등에 대한 정기적인 규정 준수 업데이트의 유연성을 제공합니다.

* 현재 브랜드 템플릿을 활용하도록 가져온 프로그램의 템플릿을 업데이트하거나, 코드 조각 또는 적절한 로고/바닥글 정보에 추가하여 브랜드를 반영하도록 새로 가져온 템플릿을 업데이트하는 것이 좋습니다.

* 명명 규칙에 맞게 이 프로그램 예제의 명명 규칙을 업데이트하는 것이 좋습니다.

>[!NOTE]
>
>프로그램 템플릿에서 내 토큰 값 을 업데이트하고 필요할 때 프로그램을 사용할 때마다 업데이트합니다.

>[!TIP]
>
>성공 추적을 위해 &quot;03 - 후속 이메일에 참여(프로그램 성공)&quot; 캠페인을 활성화하는 것을 잊지 마십시오! 이메일을 보내기 전에 _다음 작업을 수행합니다_.

>[!IMPORTANT]
>
>URL을 참조하는 내 토큰은 http:// 또는 https://을 포함할 수 없습니다. 그렇지 않으면 링크가 자산 내에서 적절하게 작동하지 않습니다.
