---
description: AWS 마이그레이션 - Marketo Engage 문서 - 제품 설명서
title: AWS 마이그레이션
feature: Getting Started
exl-id: a4bb6c23-ec63-43ec-9fbe-b1cb3928f233
source-git-commit: d5768261c9bb659ef96b73c46a9e078f953d8ed6
workflow-type: tm+mt
source-wordcount: '834'
ht-degree: 4%

---

# AWS 마이그레이션 {#aws-migration}

이후 몇 개월 동안 모든 Marketo Engage 구독은 안정성, 확장성 및 속도를 개선하기 위해 개인 데이터 센터에서 AWS 공용 클라우드로 마이그레이션되고 있습니다.

마이그레이션하기 약 30일 전에 이메일과 인앱 알림을 받게 됩니다. 이 안내서를 사용하여 준비하십시오.

## 권장 작업 {#actions}

마이그레이션 기간 동안 모든 Marketo Engage 서비스를 사용할 수 없습니다. 비즈니스에 미치는 영향을 최소화하기 위해 다음 단계를 수행하는 것이 좋습니다.

* **잠재 고객/직원을 만들거나 업데이트하거나** 개인 레코드를 수정하는 프로세스를 실행하지 마십시오.

* 예약된 캠페인이 일시 중지되므로 **후속 프로세스를 트리거하지 마십시오**.

* **Marketo Engage과 데이터를 주고받는 모든 통합을 일시적으로 비활성화**&#x200B;합니다.

* **데이터 가져오기/내보내기 또는 주요 리드/사용자 생성 캠페인을 실행하지 마십시오**.

* 로그인, API 액세스, 전자 메일 전송, 웹 추적 및 통합을 위해 **IP 허용 목록 검토 및 업데이트**.

* **새 IP 주소를 추가**&#x200B;하고 현재 IP를 그대로 유지합니다. 아래 [표](#ip-addresses)을 통해 추가할 IP 주소를 참조하세요.

## 예상되는 서비스 영향 {#impacts}

아래 영향은 귀하에게 어떠한 조치도 필요하지 않습니다.

* **CRM 통합 및 LaunchPoint 서비스**&#x200B;이(가) 비활성화되지만 이후에 자동으로 다시 시작됩니다.
* **랜딩 페이지, 양식 및 데이터 수집**&#x200B;을(를) 사용할 수 없으며 유지 관리 메시지가 대신 표시됩니다.

>[!NOTE]
>
>[외부 양식](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md){target="_blank"}을 사용하고 마이그레이션 기간 동안 Marketo Engage을 사용할 수 없는 동안 수집된 양식 제출 데이터가 손실되지 않도록 하려면 미리 [Adobe 지원 센터](https://experienceleague.adobe.com/en/support){target="_blank"} **최소 2일**&#x200B;에 연락하여 양식 ID와 구독의 Munchkin ID를 제공하십시오.

## 데이터 센터/포드 식별 {#identify}

아래 표를 검토하기 전에 [구독 데이터 센터 및 Pod/서버를 식별하는 방법을 알아보세요](/help/marketo/getting-started/things-to-know/system-status-notifications.md#identify).

## 일정 {#schedule}

새 날짜 및 데이터 센터/pod 정보가 주기적으로 추가되거나 변경되므로 이 일정을 모니터링하여 업데이트를 진행하십시오.

+++7월 일정
<table>
 <tbody>
  <tr>
   <th style="width:25%">날짜</th>
   <th style="width:25%">데이터 센터/Pod</th>
   <th style="width:25%">시간</th>
   <th style="width:25%">상태</th>
  </tr>
  <tr>
   <td>2026년 7월 8일</td>
   <td>AB69<br>
   AB64</td>
   <td>오후 5시(태평양 표준시)<br>
   오후 6시(태평양 표준시)</td>
   <td>완료<br>
   완료됨</td>
  </tr>
  <tr>
   <td>2026년 7월 9일</td>
   <td>AB70</td>
   <td>오후 5시(태평양 표준시)</td>
   <td>완료</td>
  </tr>
  <tr>
   <td>2026년 7월 11일</td>
   <td>AB46</td>
   <td>오전 10시(태평양 표준시)</td>
   <td>완료</td>
  </tr>
  <tr>
   <td>2026년 7월 13일</td>
   <td>NLD101</td>
   <td>오전 10시(태평양 표준시)</td>
   <td>완료</td>
  </tr>
  <tr>
   <td>2026년 7월 15일</td>
   <td>NLD102<br>
   NLD104</td>
   <td>오전 10시(태평양 표준시)<br>
   오전 11시(PDT)</td>
   <td>완료<br>
   완료됨</td>
  </tr>
  <tr>
   <td>2026년 7월 17일</td>
   <td>NLD103<br>
   NLD105</td>
   <td>오전 10시(태평양 표준시)<br>
   오전 11시(PDT)</td>
   <td>완료<br>
   완료됨</td>
  </tr>
  <tr>
   <td>2026년 7월 21일</td>
   <td>AB54</td>
   <td>오후 5시(태평양 표준시)</td>
   <td>완료</td>
  </tr>
  <tr>
   <td>2026년 7월 23일</td>
   <td>AB48</td>
   <td>오후 5시(태평양 표준시)</td>
   <td>완료</td>
  </tr>
  <tr>
   <td>2026년 7월 31일</td>
   <td>AB43</td>
   <td>오후 3시(태평양 표준시)</td>
   <td>완료</td>
  </tr>
  </body>
</table>

+++

<table>
 <tbody>
  <tr>
   <th style="width:25%">날짜</th>
   <th style="width:25%">데이터 센터/Pod</th>
   <th style="width:25%">시간</th>
   <th style="width:25%">상태</th>
  </tr>
  <tr>
   <td>2026년 8월 12일</td>
   <td>AB61<br>
   AB17</td>
   <td>오후 3시(태평양 표준시)<br>
   오후 4시(태평양 표준시)</td>
   <td>완료<br>
   완료됨</td>
  </tr>
  <tr>
  <td>2026년 8월 13일</td>
   <td>AB68</td>
   <td>오후 4시(태평양 표준시)</td>
   <td>완료</td>
  </tr>
  <tr>
  <td>2026년 8월 18일</td>
   <td><i>AB39</i></td>
   <td><i>오후 5시(태평양 표준시)</i></td>
   <td><i>연기됨(날짜 TBD)</i></td>
  </tr>
  <tr>
   <td>2026년 8월 20일</td>
   <td>AB42<br>
   AB44</td>
   <td>오후 5시(태평양 표준시)<br>
   오후 6시(태평양 표준시)</td>
   <td>일정대로 진행 중<br>
   일정에 따라</td>
  </tr>
  <tr>
   <td>2026년 8월 26일</td>
   <td>AB40<br>
   AB50</td>
   <td>오후 5시(태평양 표준시)<br>
   오후 6시(태평양 표준시)</td>
   <td>일정대로 진행 중<br>
   일정에 따라</td>
  </tr>
  <tr>
   <td>2026년 8월 28일</td>
   <td>AB53<br>
   AB56</td>
   <td>오후 3시(태평양 표준시)<br>
   오후 4시(태평양 표준시)</td>
   <td>일정대로 진행 중<br>
   일정에 따라</td>
  </tr>
  <tr>
   <td>2026년 9월 8일</td>
   <td>AB01<br>
   AB02</td>
   <td>오후 5시(태평양 표준시)<br>
   오후 6시(태평양 표준시)</td>
   <td>일정대로 진행 중<br>
   일정에 따라</td>
  </tr>
  <tr>
   <td>2026년 9월 10일</td>
   <td>AB03<br>
   <i>AB04</i></td>
   <td>오후 5시(태평양 표준시)<br>
   <i>오후 6시(태평양 표준시)</i></td>
   <td>일정대로 진행 중<br>
   <i>연기됨(날짜 TBD)</i></td>
  </tr>
  <tr>
   <td>2026년 9월 15일</td>
   <td>AB05<br>
   AB06</td>
   <td>오후 5시(태평양 표준시)<br>
   오후 6시(태평양 표준시)</td>
   <td>일정대로 진행 중<br>
   일정에 따라</td>
  </tr>
  <tr>
   <td>2026년 9월 17일</td>
   <td>AB07<br>
   AB08</td>
   <td>오후 5시(태평양 표준시)<br>
   오후 6시(태평양 표준시)</td>
   <td>일정대로 진행 중<br>
   일정에 따라</td>
  </tr>
  </body>
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
</body>
</table>

## 업데이트 및 지원 {#support}

최신 업데이트를 보려면 이 페이지에 책갈피를 지정합니다. 질문이 있는 경우 Admin Console 또는 [Experience League](https://experienceleague.adobe.com/en/support){target="_blank"}의 지원 포털을 통해 Adobe 지원 센터에 문의하십시오.

## FAQ {#faq}

**데이터가 저장된 위치**
모든 Marketo 사용자 데이터는 Amazon Web Services(AWS)에 저장됩니다. Marketo은 소유한 물리적 데이터 센터에서 AWS의 엔터프라이즈급 클라우드 플랫폼으로 인프라를 마이그레이션했습니다.

**개인 데이터는 어디에 저장되어 있습니까?**
개인 데이터는 AWS의 완전히 관리되는 관계형 데이터베이스 서비스인 Amazon Aurora에 저장됩니다. Aurora는 AWS 지역 내의 세 개의 개별 가용 영역에서 6가지 방법으로 데이터를 복제하여 하드웨어 오류, 스토리지 성능 저하 및 현지화된 인프라 이벤트로부터 개인 데이터를 보호합니다.

**저장소 환경을 소유한 사람**
스토리지 인프라는 Amazon Web Services(AWS)가 소유 및 운영합니다. Adobe(Marketo)는 공유 책임 모델 아래 AWS의 고객으로 작동합니다. AWS은 기본 인프라의 보안 및 가용성을 책임지는 반면, Adobe은 그 안에서 실행되는 데이터 및 애플리케이션의 보안을 책임집니다.

**프로덕션, 백업/DR 위치 및 스토리지 기술에 대한 전체 세부 정보는 무엇입니까?**
Marketo은 AWS에서 완전히 관리하는 클라우드 기반 관계형 데이터베이스 엔진인 Amazon Aurora를 기본 데이터베이스 기술로 사용합니다. Aurora는 컴퓨팅 및 스토리지를 분리하여 운영 영역 내 3개의 가용 영역에 걸쳐 6가지 방법으로 데이터를 자동으로 복제하고 쓰기 작업을 확인하기 위해 4개의 복제본 쿼럼을 필요로 합니다.

Aurora는 또한 Amazon S3에 대한 지속적인 자동 백업을 실시간으로 수행하므로 구성된 보존 기간 내의 모든 초 단위로 PITR(시점 복구)을 수행할 수 있습니다.

현재 Marketo의 Aurora 배포는 교차 영역 복제 없이 단일 AWS 영역 내에서 작동합니다. 운영 데이터는 지정된 지역 인프라에 그대로 유지되며 재해 복구는 Aurora의 다중 AZ 스토리지 이중화 및 지속적인 백업을 통해 2차 지역으로 지리적 페일오버가 아니라 제공됩니다. 이는 Marketo의 AWS 인프라가 성숙됨에 따라 더욱 평가될 수 있다.
