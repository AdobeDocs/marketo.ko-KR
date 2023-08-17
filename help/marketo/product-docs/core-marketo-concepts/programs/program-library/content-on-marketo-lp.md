---
description: Marketo LP의 콘텐츠 - Marketo 설명서 - 제품 설명서
title: Marketo LP의 콘텐츠
hide: true
hidefromtoc: true
feature: Programs
source-git-commit: 661a41eb0c5c43541a63a36c31837b35f516d827
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 2%

---

# Marketo LP의 콘텐츠 {#content-on-marketo-lp}

프로그램 이름: Marketo LP의 CT-YYYY-MM-Content

이 샘플 참조는 Marketo 기본 프로그램을 활용하여 Marketo 양식과 함께 Marketo 랜딩 페이지를 활용하는 컨텐츠 프로그램으로 설계되었습니다. 양식은 콘텐츠/오퍼에 액세스하는 것입니다. 오퍼에 대한 링크는 감사 인사 페이지에 표시하거나, 감사 인사 전자 메일로 전송하거나, 둘 다에 표시할 수 있습니다. 추가적인 전략 지원 또는 프로그램 맞춤화에 대한 도움말을 보려면 Adobe 계정 팀에 문의하거나 [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html) 페이지를 가리키도록 업데이트하는 중입니다.

**채널 요약**

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
<br/>2-참여 성공</td>
   <td>포함</td>
   <td>기본값</td>
  </tr>
 </tbody> 
</table>

**프로그램에는 다음 자산이 포함되어 있습니다.**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>유형</th> 
   <th>템플릿 이름</th>
   <th>에셋 이름</th>
  </tr> 
  <tr> 
   <td>이메일</td> 
   <td>빠른 시작 이메일 템플릿</td>
   <td>01-이메일-감사</td>
  </tr>
  <tr> 
   <td>랜딩 페이지</td> 
   <td>빠른 시작 LP 템플릿</td>
   <td>01 - LP - 등록</td>
  </tr>
  <tr> 
   <td>랜딩 페이지</td> 
   <td>빠른 시작 LP 템플릿</td>
   <td>02 - LP - 감사합니다.</td>
  </tr>
  <tr> 
   <td>양식</td> 
   <td> </td>
   <td>컨텐츠 등록 양식</td>
  </tr>
  <tr> 
   <td>로컬 보고서</td> 
   <td> </td>
   <td>이메일 성능</td>
  </tr>
  <tr> 
   <td>로컬 보고서</td> 
   <td> </td>
   <td>랜딩 페이지 성능</td>
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
   <td>Assets - 모든 크리에이티브 에셋을 저장합니다. 
<br/>(이메일 및 랜딩 페이지의 하위 폴더)  </td>
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

스크린샷 - 프로그램 사진

**내 토큰이 포함됨:**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>토큰 유형</th> 
   <th>토큰 이름</th>
   <th>값</th>
  </tr> 
  <tr> 
   <td>리치 텍스트</td> 
   <td><code>{{my.Content-Description}}</code></td>
   <td>세부 사항을 보려면 두 번 클릭  
<br/><code><--My Content Description Here--></code> 
<br/>내 토큰 탭 아래의 프로그램 수준에서 이 컨텐츠 설명을 편집합니다. 
<br/>배울 내용: 
<li>글머리 기호</li>
<li>글머리 기호 2</li>
<li>글머리 기호 3</li></td>
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
   <td><code>{{my. Email-ReplyToAddress}}</code></td>
   <td>reply-to.email@mydomain.com</td>
  </tr>
  <tr> 
   <td>텍스트</td> 
   <td><code>{{my.PageURL-ThankYou}}</code></td>
   <td>My.ThankYouPageURL?http://</td>
  </tr>
 </tbody> 
</table>

>[!CAUTION]
>
>기본 충돌 규칙에 대해서는 프로그램 가져오기 지침 을 참조하십시오.

**가져오기에 대한 권장 기본 충돌 규칙:**

* 프로그램 태그
   * 이 구독에서 태그 만들기(기본값) - 권장
   * 무시

* 동일한 이름의 랜딩 페이지 템플릿
   * 원본 템플릿 복사(기본값)
   * 대상 템플릿 사용 - 권장

* 이름이 같은 이미지
   * 두 파일 모두 유지(기본값)
   * 이 구독의 항목 바꾸기 - 권장

* 이름이 같은 이메일 템플릿
   * 두 템플릿 모두 유지(기본값)
   * 기존 템플릿 바꾸기 - 권장

스크린샷 - 기본 충돌 규칙 그림

**권장 모범 사례:**

* Marketo Consulting 우수 사례에 따라 컨텐츠 프로그램을 가져온 후 양식을 로컬 자산에서 Marketo Engage Design Studio에 있는 글로벌 자산으로 이동하는 것이 좋습니다.
   * Design Studio에서 양식 수를 줄이고 더 많은 글로벌 에셋을 사용하면 프로그램 설계 및 관리 거버넌스에서 더 많은 확장성을 얻을 수 있습니다. 또한 필드, 옵트인 언어 등에 대한 정기적인 규정 준수 업데이트의 유연성을 제공합니다.

* 가져온 프로그램의 템플릿을 업데이트하여 현재 브랜드 템플릿을 활용하거나, 코드 조각 또는 적절한 로고 및 바닥글 정보를 추가하여 새로 가져온 템플릿을 업데이트하여 브랜드를 반영하는 것이 좋습니다.

* 필요한 경우 명명 규칙에 맞게 이 프로그램 템플릿의 명명 규칙을 업데이트하는 것이 좋습니다.

* 프로그램 템플릿에서 내 토큰 값 을 업데이트하고 필요할 때 프로그램을 사용할 때마다 업데이트하는 것을 잊지 마십시오.

* 추가적인 전략 지원 또는 프로그램 맞춤화에 대한 도움말을 보려면 Adobe 계정 팀에 문의하거나 [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html) 페이지를 가리키도록 업데이트하는 중입니다.

>[!TIP]
>
>성공 추적을 위해 &quot;02 참여&quot; 캠페인을 활성화하는 것을 잊지 마십시오! 양식을 라이브로 전환하고 이메일을 보내기 전에 이 작업을 수행하십시오.

>[!NOTE]
>
>URL을 참조하는 내 토큰은 http:// 또는 https://을 포함할 수 없습니다. 그렇지 않으면 링크가 자산 내에서 적절하게 작동하지 않습니다.
