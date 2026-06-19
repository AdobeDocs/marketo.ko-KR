---
description: AWS 마이그레이션 - Marketo Engage 문서 - 제품 설명서
title: AWS 마이그레이션
feature: Getting Started
hide: true
exl-id: a4bb6c23-ec63-43ec-9fbe-b1cb3928f233
source-git-commit: 1f54476f0f7d66f6250299464b3c1145b11e86b1
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 3%

---

# AWS 마이그레이션 {#aws-migration}

이후 몇 개월 동안 모든 Marketo Engage 구독은 안정성, 확장성 및 속도를 개선하기 위해 개인 데이터 센터에서 AWS 공용 클라우드로 마이그레이션되고 있습니다.

마이그레이션하기 약 30일 전에 이메일과 인앱 알림을 받게 됩니다. 이 안내서를 사용하여 준비하십시오.

## 권장 작업

마이그레이션 기간 동안 모든 Marketo Engage 서비스를 사용할 수 없습니다. 비즈니스에 미치는 영향을 최소화하기 위해 다음 단계를 수행하는 것이 좋습니다.

* **잠재 고객/직원을 만들거나 업데이트하거나** 개인 레코드를 수정하는 프로세스를 실행하지 마십시오.

* 예약된 캠페인이 일시 중지되므로 **후속 프로세스를 트리거하지 마십시오**.

* **Marketo Engage과 데이터를 주고받는 모든 통합을 일시적으로 비활성화**&#x200B;합니다.

* **데이터 가져오기/내보내기 또는 주요 리드/사용자 생성 캠페인을 실행하지 마십시오**.

* 로그인, API 액세스, 전자 메일 전송, 웹 추적 및 통합을 위해 **IP 허용 목록 검토 및 업데이트**.

* **새 IP 주소를 추가**&#x200B;하고 현재 IP를 그대로 유지합니다. 아래 [표](#ip-addresses)을 통해 추가할 IP 주소를 참조하세요.

## 예상되는 서비스 영향

아래 영향은 귀하에게 어떠한 조치도 필요하지 않습니다.

* **CRM 통합 및 LaunchPoint 서비스**&#x200B;이(가) 비활성화되지만 이후에 자동으로 다시 시작됩니다.
* **랜딩 페이지, 양식 및 데이터 수집**&#x200B;을(를) 사용할 수 없으며 유지 관리 메시지가 대신 표시됩니다.

## 데이터 센터/포드 식별 {#identify}

아래 표를 검토하기 전에 [구독 데이터 센터 및 Pod/서버를 식별하는 방법을 알아보세요](/help/marketo/getting-started/things-to-know/system-status-notifications.md#identify).

## 일정 {#schedule}

새 날짜 및 데이터 센터/pod 정보가 주기적으로 추가되므로 자세한 내용은 여기에서 다시 확인하십시오.

<table>
 <tbody>
  <tr>
   <th style="width:50%">날짜</th>
   <th style="width:20%">데이터 센터/Pod</th>
   <th style="width:30%">시간</th>
  </tr>
  <tr>
   <td>2026년 6월 19일</td>
   <td>AB46</td>
   <td>오후 5시(PST)</td>
  </tr>
  <tr>
   <td>2026년 7월 8일</td>
   <td>AB69<br>
   AB64</td>
   <td>오후 5시(PST)<br>
   오후 6시(PST)</td>
  </tr>
  <tr>
   <td>2026년 7월 9일</td>
   <td>AB70<br>
   AB43</td>
   <td>오후 5시(PST)<br>
   오후 6시(PST)</td>
  </tr>
  &lt;/body>
  </table>

## 추가할 IP 주소 {#ip-addresses}

데이터 센터를 기반으로 IT 부서와 협력하여 각 IP 주소를 추가합니다.

<table>
 <tbody>
  <tr>
   <th style="width:25%">데이터 센터</th>
   <th style="width:75%">IP 주소</th>
  </tr>
  <tr>
   <td>AB</td>
   <td>54.160.246.246<br>
   54.237.141.197<br>
   52.20.211.99</td>
  </tr>
  <tr>
   <td>NLD</td>
   <td>34.247.24.245<br>
18.200.201.81<br>
54.220.138.65</td>
  </tr>
  &lt;/body>
  </table>

## 업데이트 및 지원

최신 업데이트를 보려면 이 페이지에 책갈피를 지정합니다. 질문이 있는 경우 Admin Console 또는 [Experience League](https://experienceleague.adobe.com/ko/support){target="_blank"}의 지원 포털을 통해 Adobe 지원 센터에 문의하십시오.
