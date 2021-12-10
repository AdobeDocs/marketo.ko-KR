---
description: 고급 검색 개요 - Marketo 문서 - 제품 설명서
title: 고급 검색 개요
hide: true
hidefromtoc: true
exl-id: a7cf5078-1d24-4fc0-a82d-02f46f93893d
source-git-commit: fda1bf51d4016a61c41be9acba4771db1797a552
workflow-type: tm+mt
source-wordcount: '418'
ht-degree: 0%

---

# 고급 검색 개요 {#advanced-search-overview}

고급 검색을 활용하여 이메일을 보거나 클릭하거나 회신한 잠재 고객을 타겟팅하면 가장 참여한 잠재 고객의 대상 목록을 만들 수 있습니다.

## 고급 검색에 액세스하는 방법 {#how-to-access-advanced-search}

1. 웹 응용 프로그램에서 **명령 센터**.

   ![](assets/advanced-search-overview-1.png)

1. 클릭 **이메일**.

   ![](assets/advanced-search-overview-2.png)

1. 적용 가능한 탭을 선택합니다.

   ![](assets/advanced-search-overview-3.png)

1. 고급 검색을 클릭합니다.

   ![](assets/advanced-search-overview-4.png)

## 필터 {#filters}

**날짜**

검색할 날짜 범위를 선택합니다. 사전 설정 날짜는 선택한 이메일 상태(전송됨, 배달되지 않음, 보류 중)에 따라 업데이트됩니다.

![](assets/advanced-search-overview-5.png)

**Who**

Who 섹션에서 이메일 수신자/발신자별로 필터링합니다.

![](assets/advanced-search-overview-6.png)

<table>
 <tr>
  <td><strong>드롭다운</strong></td>
  <td><strong>설명</strong></td>
 </tr>
 <tr>
  <td><strong>다음으로 보기</strong></td>
  <td>Sales Connect 인스턴스에서 특정 발신자에 의해 필터링합니다(이 옵션은 관리자만 사용 가능).</td>
 </tr>
 <tr>
  <td><strong>그룹별</strong></td>
  <td>특정 수신자 그룹별로 이메일을 필터링합니다.</td>
 </tr>
 <tr>
  <td><strong>개인별</strong></td>
  <td>특정 수신자별로 필터링합니다.</td>
 </tr>
</table>

**When**

생성된 날짜, 배달된 날짜, 실패한 날짜 또는 예약된 날짜별로 선택합니다. 사용 가능한 옵션은 선택한 이메일 상태(전송됨, 배달되지 않음, 보류 중)에 따라 변경됩니다.

![](assets/advanced-search-overview-7.png)

**캠페인**

캠페인 기여도별로 이메일을 필터링합니다.

![](assets/advanced-search-overview-8.png)

**상태**

선택할 수 있는 세 가지 이메일 상태가 있습니다. 유형/활동 옵션은 선택한 상태에 따라 변경됩니다.

![](assets/advanced-search-overview-9.png)

_**상태: 전송**_

![](assets/advanced-search-overview-10.png)

보낸 이메일 활동별로 필터링합니다. 보기/보기 안 함, 클릭/클릭 안 함 및/또는 답글/응답 안 함을 선택할 수 있습니다.

_**상태: 보류 중**_

![](assets/advanced-search-overview-11.png)

보류 중인 모든 전자 메일의 필터입니다.

<table>
 <tr>
  <td><strong>상태</strong></td>
  <td><strong>설명</strong></td>
 </tr>
 <tr>
  <td><strong>예약됨</strong></td>
  <td>작성 창(Salesforce 또는 웹 앱), 이메일 플러그인 또는 캠페인에서 예약된 이메일.</td>
 </tr>
 <tr>
  <td><strong>초안</strong></td>
  <td>현재 초안 상태인 이메일. 초안으로 저장하려면 이메일에 제목 줄과 수신자가 필요합니다.</td>
 </tr>
 <tr>
  <td><strong>진행 중</strong></td>
  <td>전송 중인 이메일. 이메일은 몇 초 이상 이 상태로 유지되지 않아야 합니다.</td>
 </tr>
</table>

_**상태: 배달되지 않음**_

![](assets/advanced-search-overview-12.png)

배달되지 않은 이메일의 필터입니다.

<table>
 <tr>
  <td><strong>상태</strong></td>
  <td><strong>설명</strong></td>
 </tr>
 <tr>
  <td><strong>실패</strong></td>
  <td>Sales Connect에서 이메일을 보내지 못하는 경우(일반적인 이유는 다음과 같습니다. 가입 해지됨/차단된 연락처에 이메일을 보내거나 동적 필드를 채우는 데 문제가 있는 경우).</td>
 </tr>
 <tr>
  <td><strong>바운스됨</strong></td>
  <td>전자 메일은 수신자 서버가 거부하면 바운스된 것으로 표시됩니다. Sales Connect 서버를 통해 전송된 이메일만 여기에 표시됩니다.</td>
 </tr>
 <tr>
  <td><strong>스팸</strong></td>
  <td>수신자가 이메일을 스팸(요청하지 않은 이메일의 공통 용어)으로 표시했을 때. Sales Connect 서버를 통해 전송된 이메일만 여기에 표시됩니다.</td>
 </tr>
</table>

## 저장된 검색 {#saved-searches}

저장된 검색을 만드는 방법은 다음과 같습니다.

1. 모든 필터가 제자리에 있으면 를 클릭합니다. **필터를 다른 이름으로 저장**.

   ![](assets/advanced-search-overview-13.png)

1. 검색 이름을 지정하고 을(를) 클릭합니다. **저장**.

   ![](assets/advanced-search-overview-14.png)

저장된 검색은 왼쪽의 사이드바에 있습니다.

![](assets/advanced-search-overview-15.png)
