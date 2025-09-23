---
description: 상속된 인스턴스 데이터베이스 검사 목록 - Marketo 문서 - 제품 설명서
title: 상속된 인스턴스 데이터베이스 검사 목록
feature: Getting Started
exl-id: 278a6a2f-7b68-4003-8727-129e0dc96c12
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '420'
ht-degree: 5%

---

# 상속된 인스턴스: 데이터베이스 체크리스트 {#inherited-instance-database-checklist}

구독의 총 인원 수, 마케팅 가능한 사람 및 인기 사용자 확보 소스를 파악합니다. [확인 목록을 다운로드](/help/marketo/getting-started/inheriting-a-marketo-engage-instance/assets/adobe-marketo-engage-inherited-instance-admin-checklist.xlsx)하고 진행 상황을 추적하는 것이 좋습니다.

## 시스템 스마트 목록 {#system-smart-lists}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr>
  <tr>
   <td>모든 사람</td>
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/database-dashboard.md" target="_blank">데이터베이스</a>에 몇 명이 있습니까?</li>
<li>데이터베이스가 거의 꽉 찼을 경우 회사 정책에서 데이터베이스 크기를 확장하거나 기록 데이터를 정리하는 것이 좋습니까?</li>
<li>전체 데이터베이스가 최소 85%의 시장성을 갖추고 있습니까?
<br/>     차단 목록에 추가하다 이 임계값에 해당하면 다른 시스템 스마트 목록(마케팅 중단, 마케팅 중단, 중복, 구독 취소)을 더 자세히 살펴보십시오.</li></td>
  </tr>
  <tr>
   <td>구독 취소된 사람</td>
   <td><li><a href="/help/marketo/product-docs/email-marketing/deliverability/understanding-unsubscribe.md#marketing-suspended" target="_blank">구독 취소자</a>에 대한 기준은 무엇입니까? 구독 취소자가 너무 많습니까?</li>
<li>구독 취소 방법이 데이터 개인 정보 보호 요구 사항과 일치합니까?</li>
<li>구독 취소 기본 설정이 최신 상태입니까? 데이터베이스에 얼마나 오랫동안 마케팅할 수 없는 레코드가 남아 있습니까?</li></td>
  </tr>
  <tr>
   <td>마케팅 중단</td>
   <td><li><a href="/help/marketo/product-docs/email-marketing/deliverability/durable-unsubscribe.md#marketing-suspended" target="_blank">마케팅 중단</a>에 대한 기준은 무엇입니까? 마케팅 중단 대상자가 너무 많습니까?</li>
<li>레코드가 마케팅 일시 중단 상태로 남아 있는 기간은 얼마나 됩니까?</li>
<p>마케팅 중단 사용 사례 예: 마케팅 커뮤니케이션을 억제하려는 지연 단계 기회의 영업과 관련된 사람을 기록합니다.</td>
  </tr>
   <tr>
   <td>차단 목록</td>
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.md" target="_blank">차단 목록에 추가 레코드</a>에 대한 기준은 무엇입니까? 차단 목록에 추가된으로 받는 사람이 너무 많은가요?</li></td>
  </tr>
  <tr>
   <td>반송된 이메일 주소</td>
   <td><li>데이터베이스에 <a href="/help/marketo/product-docs/email-marketing/deliverability/hard-and-soft-bounces-in-email.md" target="_blank">바운스된 </a>명의 사용자가 많습니까?
   <br/>     그렇다면 이유를 조사하는 것이 좋습니다.</li></td></li></td>
  </tr>
  <tr>
   <td>가능한 중복 항목</td>
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md" target="_blank">중복 레코드</a>이(가) 몇 개나 있습니까?
   <br/>     이를 삭제하거나 병합하는 것이 좋습니다.</li></td>
  </tr>
   <tr>
   <td>획득 프로그램 없음</td>
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md#acquisition-program" target="_blank">획득 프로그램</a>이 없는 사람은 몇 명입니까?
   <br/>     만약 많다면, 이유를 조사하는 것을 고려하세요.</li></td>
  </tr>
 </tbody>
</table>

## 스마트 목록 {#smart-lists}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr>
  <tr>
   <td>스마트 목록</td>
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists.md" target="_blank">스마트 목록</a>은 몇 개입니까? 이 인스턴스에서는 어떻게 사용됩니까?</li>
   <p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 데이터베이스 섹션에서 그룹 스마트 목록은 사용자가 생성한 목록이며 시스템 스마트 목록은 Marketo Engage에서 생성한 기본 목록입니다.
<li>목록은 일관된 폴더 구조로 구성되어 있습니까?
<br/>     고아 목록이 있는 경우 에셋을 쉽게 찾을 수 있도록 트리 구성을 고려하십시오.</li>
<p><img src="assets/tip-icon.png" alt="팁 아이콘">팁: <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-folders.md#archive-a-folder" target="_blank">더 이상 필요하지 않은 스마트 목록을 보관</a>하면 조직과 성능에 도움이 됩니다.</td>
  </tr>
 </tbody>
</table>

## 정적 목록 {#static-lists}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr>
  <tr>
   <td>정적 목록</td>
   <td><li>정적 목록<a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/understanding-static-lists.md" target="_blank">개</a>이 몇 개나 있습니까? 이 인스턴스에서는 어떻게 사용됩니까?</li>
   <p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 데이터베이스 섹션에서 그룹 목록은 정적 목록입니다.</td>
  </tr>
 </tbody>
</table>

## 세분화 {#segmentations}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr>
  <tr>
   <td>세분화</td>
   <td><li><a href="/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md" target="_blank">세그먼테이션</a>은(는) 무엇입니까? 어떻게 사용하고 있습니까?</li>
<li><a href="/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/segmentation-order-priority.md" target="_blank">기본 세그먼트</a>에 사람이 너무 많습니까?</li>
<li>마케팅 가능한 대상을 위한 세그먼테이션이 있습니까?
<br/>     그렇지 않으면 새로 만드는 것이 좋습니다.</li></td>
  </tr>
 </tbody>
</table>
