---
description: CT-YYYY-MM-Content Marketo 이외 랜딩 페이지 - Marketo 문서 - 제품 설명서
title: CT-YYYY-MM-Marketo 랜딩 페이지가 아닌 콘텐츠
feature: Programs
exl-id: b7cf8e52-4f3f-44d7-ab4c-ad10fa0badc9
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 9%

---

# CT-YYYY-MM-Marketo 랜딩 페이지가 아닌 콘텐츠 {#ct-yyyy-mm-content-non-marketo-landing-page}

다음은 Marketo Engage 기본 프로그램을 사용하여 Marketo Engage이 아닌 랜딩 페이지에서 콘텐츠를 다운로드하기 위한 Marketo Engage 양식이 있는 콘텐츠 프로그램의 예입니다. 이 프로그램은 웹 사이트에 임베드된 Marketo Engage 양식으로 작동하기 위한 것입니다. 오퍼/콘텐츠에 대한 링크는 감사 전자 메일로 보낼 수 있습니다.

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
   <td>웹 컨텐츠</td>
   <td>구성원
<br/>02 참여 성공</td>
   <td>포함</td>
   <td>기본</td>
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
   <td>양식</td>
   <td> </td>
   <td>FM-콘텐츠 등록 양식(Design Studio의 글로벌 자산)</td>
  </tr>
  <tr>
   <td>로컬 보고서</td>
   <td> </td>
   <td>이메일 성능</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>00-Capture Acquisition 프로그램</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>01개 작성된 양식</td>
  </tr>
  <tr>
   <td>스마트 캠페인</td>
   <td> </td>
   <td>02-참여(프로그램 성공)</td>
  </tr>
  <tr>
   <td>폴더</td>
   <td> </td>
   <td>Assets - 모든 크리에이티브 에셋 보유
<br/>(전자 메일 및 랜딩 페이지의 하위 폴더)  </td>
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

![](assets/ct-yyyy-mm-content-non-marketo-landing-page-1.png)

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
   <td><code>{{my.Content-Title}}</code></td>
   <td><code><--My Content Title Here--></code></td>
  </tr>
  <tr>
   <td>텍스트</td>
   <td><code>{{my.Content-Type}}</code></td>
   <td><code><--My Content Type Here--></code></td>
  </tr>
  <tr>
   <td>텍스트</td>
   <td><code>{{my.Content-URL}}</code></td>
   <td>my.ContentURL?without=http://</td>
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

* 콘텐츠 프로그램을 가져온 후 양식을 로컬 에셋에서 Design Studio에 있는 글로벌 에셋으로 이동합니다.
   * Design Studio에서 양식 수를 줄이고 더 많은 글로벌 에셋을 사용하면 프로그램 설계 및 관리 거버넌스에서 더 많은 확장성을 얻을 수 있습니다. 또한 필드, 옵트인 언어 등에 대한 정기적인 규정 준수 업데이트를 위한 유연성도 제공합니다.

* 현재 브랜드 템플릿을 활용하도록 가져온 프로그램의 템플릿을 업데이트하거나, 코드 조각 또는 적절한 로고/바닥글 정보에 추가하여 브랜드를 반영하도록 새로 가져온 템플릿을 업데이트하는 것이 좋습니다.

* 명명 규칙에 맞게 이 프로그램 예제의 명명 규칙을 업데이트하는 것이 좋습니다.

>[!NOTE]
>
>프로그램 템플릿에서 내 토큰 값 을 업데이트하고 필요할 때 프로그램을 사용할 때마다 업데이트합니다.

>[!TIP]
>
>성공 추적을 위해 &quot;02 참여&quot; 캠페인을 활성화하는 것을 잊지 마십시오! 양식이 라이브되고 전자 메일이 전송되기 전에 _먼저_&#x200B;하세요.
