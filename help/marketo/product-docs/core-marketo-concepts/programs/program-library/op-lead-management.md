---
description: 잠재 고객 관리 - Marketo 문서 - 제품 설명서
title: OP-리드 관리
feature: Programs
exl-id: 28db1a91-a559-4dcb-b2e3-9cb2c0c23f9f
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '266'
ht-degree: 2%

---

# OP-리드 관리 {#op-lead-management}

다음은 CRM에 대한 Marketo Engage 데이터베이스 내의 레코드를 관리하는 데 도움이 되도록 Marketo Engage 기본 프로그램을 활용하는 리드 관리 모범 사례 워크플로의 예입니다.

>[!NOTE]
>
>Marketo Engage에서 데이터베이스의 레코드는 사람/사용자라고 합니다. 이 예에서 리드 관리는 CRM의 레코드를 참조합니다.

추가적인 전략 지원 또는 프로그램 맞춤화에 대한 도움말을 보려면 Adobe 계정 팀에 문의하거나 [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html) 페이지를 가리키도록 업데이트하는 중입니다.

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
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>01 - 새 사용자를 CRM에 동기화</td>
  </tr>
  <tr> 
   <td>스마트 캠페인</td> 
   <td> </td>
   <td>02 - 적격 마케팅</td>
  </tr>
  <tr> 
   <td>이메일</td> 
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">빠른 시작 이메일 템플릿</a></td>
   <td>01 - 이메일 - 경고 - MQL</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>캠페인</td>
  </tr>
  <tr> 
   <td>폴더</td> 
   <td> </td>
   <td>이메일 경고</td>
  </tr>
 </tbody> 
</table>

![](assets/op-lead-management-1.png)

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

* 조직에서 추적할 수 있는 각 라이프사이클 상태 요구 사항을 해결하기 위해 추가 스마트 캠페인을 추가하는 것이 좋습니다. 이 프로그램에 내장된 각 캠페인은 모든 사용 사례에만 적용되는 것이 아니라 모범 사례 빌드의 예시여야 합니다. Smart Campaign을 업데이트하여 특정 LEAD LIFECYCLE MANAGEMENT 프로세스를 처리해야 합니다.

* 내 프로그램에 맞게 이 프로그램 예제의 명명 규칙을 업데이트하는 것이 좋습니다.
