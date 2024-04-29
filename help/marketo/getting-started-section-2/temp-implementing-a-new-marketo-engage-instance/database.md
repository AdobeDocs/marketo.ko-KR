---
description: 새 Marketo Engage 인스턴스에 대한 데이터베이스 섹션을 설정합니다.
title: 새 영역 데이터베이스
hide: true
hidefromtoc: true
feature: Getting Started
exl-id: 1966bc6f-9384-4c51-b3aa-57d5e52781f1
source-git-commit: 8473c4d59210bb18c3968a56883034febf00c320
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 2%

---

# 새 영역: 데이터베이스 검사 목록 {#new-area-database-checklist}

새 Marketo Engage 인스턴스의 데이터베이스 섹션에 필요한 단계를 구현하는 방법을 알아봅니다. &quot;새 인스턴스 구현&quot; 안내서에 따라 진행 중인 작업을 추적하여 장기적인 효율성을 위해 인스턴스를 설정하는 데 도움을 받으십시오.

## 시스템 스마트 목록 {#system-smart-lists}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>모든 사람</td>
    <td><li>CRM과 1:1 동기화를 구현하거나 필터를 적용하여 시스템에서 시스템으로 이동하는 사람과 언제 이동하는 사용자를 제한할지 결정합니다.</li> 
    <li>의 총 인원과 마케팅 가능한 사람 수를 검토하십시오. <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/database-dashboard.html" target="_blank">Marketo Engage 데이터베이스</a>.</li></td>
  </tr>
  <tr>
    <td>차단 목록</td>
    <td><li>차단 목록 기준을 정의합니다. 경쟁업체의 도메인을 다음에 추가하는 것이 좋습니다. <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.html" target="_blank">차단 목록</a> 이메일을 수신하지 못하도록 할 수 있습니다.</li></td>
  </tr>
  <tr>
    <td>마케팅 중단</td>
    <td><li>정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html#marketing-suspended" target="_blank">마케팅 일시 중단됨</a> 기준.</li></td>
  </tr>
  <tr>
    <td>반송된 이메일 주소 </td>
    <td><li>반송된 이메일 주소에 대한 기준을 정의합니다.</li>
    <li>이메일 부적합 범주의 직원과 이메일이 다음과 같아야 하는지 검토합니다. <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/hard-and-soft-bounces-in-email.html" target="_blank">수동으로 재설정</a>.</li></td>
  </tr>
  <tr>
    <td>가능한 중복 항목</td>
    <td><li>가능한 중복 항목 목록의 사용자를 검토하십시오.</li> 
    <li>중복 관리 전략을 정의하여 다음을 원하는지 결정합니다. <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.html" target="_blank">수동으로 사람 병합</a>.</li>  
    <li>CRM 통합이 있는 경우 다음 프로세스 및 계정을 정의합니다 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.html#effect-in-salesforce" target="_blank">crm에서 잠재 고객 병합의 효과</a>.</li></td>
  </tr>
  <tr>
    <td>획득 프로그램 없음</td>
    <td><li>특히 글로벌 양식을 사용하는 경우 획득 프로그램을 설정하는 캠페인을 프로그램 템플릿에서 설정합니다.</li></td>
  </tr>
  <tr>
    <td>구독 취소된 사람</td>
    <td><li>다음에 대한 기준 검토 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html" target="_blank">구독 취소된 사람</a>.</li></td>
  </tr>
</tbody>
</table>

## 스마트 목록 그룹화 {#group-smart-lists}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>스마트 목록 그룹화</td>
    <td><li>중복되는 목록이 없도록 그룹 스마트 목록을 생성해야 합니다.</li>
    <li>데이터베이스에서 마스터 목록을 추적합니다.</li></td>
  </tr>
</tbody>
</table>

## 세분화 {#segmentation}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>세분화</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.html" target="_blank">세그먼트 만들기</a> 비즈니스 요구 사항에 따라 각 구독은 20개의 세그먼테이션과 각 세그먼테이션 내의 100개의 세그먼트로 제한됩니다.</li></td>
  </tr>
</tbody>
</table>
