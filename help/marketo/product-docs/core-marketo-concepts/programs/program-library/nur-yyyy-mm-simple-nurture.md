---
description: NUR-YYYY-MM-Simple Grooth - Marketo 문서 - 제품 설명서
title: NUR-YYYY-MM-Simple Grooth
feature: Programs
exl-id: aed11d75-3190-46ea-8b0b-c1494645901d
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 7%

---

# NUR-YYYY-MM-Simple Grooth {#nur-yyyy-mm-simple-nurture}

다음은 간단한 육성 프로그램의 예입니다. Marketo Engage 참여 프로그램 을 사용하면 케이던스된 콘텐츠가 데이터베이스에 지속적으로 저장되고 스트림을 활용하여 동작을 기반으로 여정을 통해 레코드를 안내할 수 있습니다.

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
   <td>육성</td>
   <td>01 - 구성원
<br/>02 - 참여 - 성공</td>
   <td>포함</td>
   <td>참여</td>
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
   <td>01 - 이메일</td>
  </tr>
   <tr>
   <td>이메일</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">빠른 시작 이메일 템플릿</a></td>
   <td>02 - 이메일</td>
  </tr>
   <tr>
   <td>이메일</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">빠른 시작 이메일 템플릿</a></td>
   <td>03 - 이메일</td>
  </tr>
  <tr>
   <td>로컬 보고서</td>
   <td> </td>
   <td>이메일 성능</td>
  </tr>
  <tr>
   <td>로컬 보고서</td>
   <td> </td>
   <td>참여 스트림 성능</td>
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
   <td>폴더</td>
   <td> </td>
   <td>Assets - 모든 크리에이티브 에셋 보유
   <br/>(전자 메일의 하위 폴더)</td>
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

![](assets/nur-yyyy-mm-simple-nurture-1.png)

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

* 현재 브랜드 템플릿을 활용하도록 가져온 프로그램의 템플릿을 업데이트하거나, 코드 조각 또는 적절한 로고/바닥글 정보에 추가하여 브랜드를 반영하도록 새로 가져온 템플릿을 업데이트하는 것이 좋습니다.

* 명명 규칙에 맞게 이 프로그램 예제의 명명 규칙을 업데이트하는 것이 좋습니다.

* 육성 케이던스를 일시 중지하고 다시 시작할 수 있는 규칙이 있는지 확인합니다. 참여 프로그램이 활성화되기 전에 이러한 스마트 캠페인을 활성화하거나 예약해야 합니다.

>[!NOTE]
>
>프로그램 템플릿에서 내 토큰 값 을 업데이트하고 필요할 때 프로그램을 사용할 때마다 업데이트합니다.

>[!TIP]
>
>성공 추적을 위해 &quot;04 - 참여(프로그램 성공)&quot; 캠페인을 활성화하는 것을 잊지 마십시오! 이메일을 보내기 전에 _다음 작업을 수행합니다_.
