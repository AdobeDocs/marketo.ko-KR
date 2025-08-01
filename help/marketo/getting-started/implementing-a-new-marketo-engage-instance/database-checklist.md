---
description: 새 Marketo Engage 인스턴스에 대한 데이터베이스 섹션을 설정합니다.
title: 새 인스턴스 모범 사례 - 데이터베이스 검사 목록
feature: Getting Started
exl-id: 996ea2db-a00c-48e5-97a8-00f869c261b1
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 2%

---

# 새 인스턴스 모범 사례: 데이터베이스 검사 목록 {#new-instance-best-practices-database-checklist}

데이터베이스 섹션에서 인스턴스에 있는 사람들의 주요 속성을 찾을 수 있습니다. 데이터베이스에서 다양한 목록 및 세그먼트를 탐색하고 사용자 레코드를 관리하는 데 필요한 단계에 대해 자세히 알아봅니다.

[확인 목록을 다운로드](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx)하고 진행 상황을 추적하는 것이 좋습니다.

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
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/database-dashboard.html?lang=ko" target="_blank">Marketo Engage 데이터베이스</a>의 총 인원과 마케팅 가능한 인원을 검토하십시오.</li></td>
  </tr>
  <tr>
    <td>차단 목록</td>
    <td><li>차단 목록 기준을 정의합니다. 경쟁사의 도메인이 이메일을 수신하지 못하도록 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.html?lang=ko" target="_blank">차단 목록</a>에 추가하는 것이 좋습니다.</li></td>
  </tr>
  <tr>
    <td>마케팅 중단</td>
    <td><li><a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe#marketing-suspended" target="_blank">마케팅 중단</a> 조건을 정의합니다.</li></td>
  </tr>
  <tr>
    <td>반송된 이메일 주소 </td>
    <td><li>반송된 이메일 주소에 대한 기준을 정의합니다.</li>
    <li>'전자 메일 잘못됨' 범주의 사용자를 검토하여 전자 메일이 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/hard-and-soft-bounces-in-email.html?lang=ko" target="_blank">수동으로 재설정</a>해야 하는지 확인하십시오.</li></td>
  </tr>
  <tr>
    <td>가능한 중복 항목</td>
    <td><li>가능한 중복 항목 목록의 사용자를 검토하십시오.</li>
    <li>중복 관리 전략을 정의하여 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.html?lang=ko" target="_blank">사람들을 수동으로 병합</a>할지 여부를 결정합니다.</li>
    <li>CRM 통합이 있는 경우 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people#effect-in-salesforce" target="_blank">CRM에서 잠재 고객 병합의 효과</a>에 대한 프로세스와 계정을 정의하십시오.</li></td>
  </tr>
  <tr>
    <td>획득 프로그램 없음</td>
    <td><li>특히 글로벌 양식을 사용하는 경우 획득 프로그램을 설정하는 캠페인을 프로그램 템플릿에서 설정합니다.</li></td>
  </tr>
  <tr>
    <td>구독 취소된 사람</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html?lang=ko" target="_blank">미구독 사용자</a>에 대한 기준을 검토하십시오.</li></td>
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
    <th style="width:21%">영역</th>
    <th style="width:79%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>세분화</td>
    <td><li>비즈니스 요구 사항에 따라 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.html?lang=ko" target="_blank">세그먼트를 만듭니다</a>. 각 구독은 20개의 세그먼테이션과 각 세그먼테이션 내의 100개의 세그먼트로 제한됩니다.</li></td>
  </tr>
</tbody>
</table>
