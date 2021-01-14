---
unique-page-id: 5472615
description: 시스템 관리 필드 이해 - 마케팅 문서 - 제품 설명서
title: 시스템 관리 필드 이해
translation-type: tm+mt
source-git-commit: f865630638e7c0fe6ac2a449e196a7de4fbfeea1
workflow-type: tm+mt
source-wordcount: '522'
ht-degree: 0%

---


# 시스템 관리 필드 이해 {#understanding-system-managed-fields}

[개인 세부 정보 페이지](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md)에 Marketing To에서 만든 편집 불가능한 필드가 여러 개 있다는 것을 인지했을 수 있습니다. 이 데이터는 다양한 소스에서 유래되며, 표시할 수 있는 값들이 많이 있습니다.

## 필드 유형 {#field-types}

| **필드 이름** | **정의** |
|---|---|
| 원본 소스 유형 | 개인 또는 웹 사이트 방문자가 처음 발견된 위치(예:목록 가져오기, 웹 페이지 방문) |
| 원본 소스 정보 | 해당 위치에 대한 자세한 내용(예:목록 이름, 웹 페이지의 URL) |
| 원본 검색 엔진 | 해당되는 경우 사용자를 원래 시작 출처로 안내한 검색 엔진 |
| 원래 검색 구문 | 해당되는 경우, 인물을 원래 시작 출처로 안내한 검색어 |
| 원래 레퍼러 | 원래 시작 소스를 호스팅하는 URL |
| 등록 소스 유형 | 활동이 처음 사람이 된 위치(예:목록 가져오기, 웹 페이지 방문) |
| 등록 소스 정보 | 해당 위치에 대한 자세한 내용(예:목록 이름, 웹 페이지의 URL) |
| 익명 IP | 사람의 IP 주소를 나타냅니다. |
| 유추 회사 | 해당 회사의 Marketing&#39;s best guess(IP 기반) |
| 유추 도시 | 해당 도시의 Marketing&#39;s best guess(IP 기반) |
| 유추 상태 영역 | 개인 주 또는 지역의 Marketing&#39;s best guess(IP 기반) |
| 유추 우편 번호 | 개인의 우편 번호에 대한 Marketing&#39;s best guess(IP 기반) |
| 유추 국가 | 해당 국가의 Marketing&#39;s best guess(IP 기반) |
| 유추 대도시 영역 | 해당 지역(IP 기준)의 Marketing&#39;s best guess |
| 유추 전화 영역 코드 | 사람 영역 코드의 Marketing&#39;s best guess(IP 기반) |

## 원본 및 등록 소스 유형에 사용할 수 있는 값 {#possible-values-for-original-and-registration-source-type}

다음은 가능한 값과 그 의미입니다.

| **원본 소스 유형** | **정의** |
|---|---|
| Salesforce.com | Salesforce 동기화에서 사람 발견 |
| 웹 페이지 방문 횟수 | 웹 페이지에서 사람을 찾았습니다. |
| 웹 양식 입력 | 양식을 작성한 후 발견된 사람 |
| 목록 가져오기 | 목록 가져오기에서 사람을 찾았습니다. |
| 새 사람 | 사용자가 데이터베이스에 수동으로 입력됨 |
| 웹 링크 클릭 | 링크를 클릭한 후 사람을 발견했습니다. |
| 영업 이메일 | Sales Insight 이메일 추가 기능을 통해 이메일을 수신한 사람 |
| Person | 사람이 Salesforce에서 다른 사람과 동기화되었습니다. |
| 연락처 | 사용자가 Salesforce에서 연락처로 동기화되었습니다. |
| Munchkin API | Marketing&#39;s Munchkin API에서 사람을 발견했습니다. |
| 소셜 앱 | 소셜 위젯에 의해 발견된 사람 |
| 웹 서비스 API | 웹 서비스 API에서 사람을 발견했습니다. |
| 이벤트 파트너 | 동기화된 웨비나 서비스를 통해 사람을 찾았습니다. |
| 리드 연결 | 연계 리드 API 호출을 통해 병합된 사람 |

| **등록 소스 유형** | **정의** |
|---|---|
| 목록 가져오기 | 목록 가져오기를 통해 사람이 되었습니다. |
| Salesforce.com | Salesforce 동기화를 통해 사람이 됨 |
| 웹 양식 입력 | 양식을 작성한 후 사람이 되었습니다. |
| 영업 이메일 | Sales Insight 이메일 추가 기능을 통해 이메일을 수신한 사람 |
| 웹 서비스 API | SOAP/REST API를 통해 만든 사람 |
| 새 사람 | 사용자가 데이터베이스에 수동으로 입력됨 |
| Munchkin API | Marketing&#39;s Munchkin API를 통해 사람이 된 경우 |
| 소셜 앱 | 소셜 위젯을 통해 사람이 되었습니다. |
| 이벤트 파트너 | 연결된 웨비나 서비스를 통해 사람이 되었습니다. |
