---
unique-page-id: 5472615
description: 시스템 관리 필드 이해 - Marketo 문서 - 제품 설명서
title: 시스템 관리 필드 이해
exl-id: 4a58d41f-c2f5-4bcc-93ef-10a31e5475fd
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '522'
ht-degree: 5%

---

# 시스템 관리 필드 이해 {#understanding-system-managed-fields}

당신은 아마도 [개인 정보 페이지](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) 에는 Marketo에서 만든 일련의 편집할 수 없는 필드가 있습니다. 이 데이터는 다양한 소스에서 오고, 표시할 수 있는 많은 값이 있습니다.

## 필드 유형 {#field-types}

| **필드 이름** | **정의** |
|---|---|
| 원본 소스 유형 | 개인 또는 웹 사이트 방문자가 처음 발견된 위치(예: 목록 가져오기, 웹 페이지 방문) |
| 원본 소스 정보 | 해당 위치에 대한 세부 사항(예: 목록 이름, 웹 페이지의 URL) |
| 원래 검색 엔진 | 해당되는 경우 사용자를 원래 입력 출처로 안내한 검색 엔진입니다 |
| 원래 검색 구 | 해당되는 경우 사용자를 원래 입력 소스로 참조한 검색어 |
| 원래 레퍼러 | 원래 시작 소스를 호스팅하는 URL |
| 등록 소스 유형 | 활동이 처음 사람이 된 위치(예: 목록 가져오기, 웹 페이지 방문) |
| 등록 소스 정보 | 해당 위치에 대한 세부 사항(예: 목록 이름, 웹 페이지의 URL) |
| 익명 IP | 개인의 IP 주소를 나타냅니다. |
| 회사 유추 | Marketo의 가장 좋은 예상(IP 기반) |
| 유추된 시 | Marketo의 IP(Marketing Cloud ID) 예측 |
| 유추된 주 지역 | Marketo의 사용자 주 또는 지역(IP 기반)에 대한 최상의 예측 |
| 우편번호 유추 | Marketo의 개인 우편 번호에 대한 최상의 예상(IP 기준) |
| 추정 국가 | 해당 국가의 Marketo이 가장 잘 추측(IP 기반)합니다. |
| 대도시 지역 유추 | Marketo의 수도권 IP(Best Guess) 기준 |
| 전화번호 지역코드 유추 | Marketo이 개인 지역 코드의 IP를 기반으로 한 최상의 추측입니다 |

## 원본 및 등록 소스 유형에 대해 가능한 값 {#possible-values-for-original-and-registration-source-type}

다음은 가능한 일부 값과 그 의미입니다.

| **원본 소스 유형** | **정의** |
|---|---|
| Salesforce.com | Salesforce 동기화에서 사람이 발견되었습니다. |
| 웹 페이지 방문 횟수 | 사람이 웹 페이지에서 발견되었습니다. |
| 웹 양식 채우기 | 양식에 입력한 후에 사람이 발견되었습니다 |
| 목록 가져오기 | 목록 가져오기에서 사람이 발견되었습니다. |
| 새 사람 | 사용자가 데이터베이스에 수동으로 입력되었습니다. |
| 웹 링크 클릭 | 링크를 클릭한 후 사람이 발견되었습니다 |
| 영업 이메일 | Sales Insight Email 추가 기능을 통해 사람이 이메일을 보냈습니다 |
| 개인 | 사람이 Salesforce에서 사람으로 동기화되었습니다. |
| 연락처 | 사람이 Salesforce에서 연락처로 동기화되었습니다. |
| Munchkin API | Marketo의 Munchkin API에 의해 사람이 발견되었습니다 |
| 소셜 앱 | 사람은 사회 위젯에 의해 발견되었다 |
| 웹 서비스 API | 웹 서비스 API에서 사람을 발견했습니다. |
| 이벤트 파트너 | 개인이 동기화된 웨비나 서비스를 통해 발견되었습니다. |
| 리드 연결 | Associate Lead API 호출을 통해 병합된 사람 |

| **등록 소스 유형** | **정의** |
|---|---|
| 목록 가져오기 | 목록 가져오기를 통해 사람이 되었습니다. |
| Salesforce.com | Salesforce 동기화를 통해 사람이 되었습니다. |
| 웹 양식 채우기 | 양식을 작성한 후 사람이 되었습니다 |
| 영업 이메일 | Sales Insight Email 추가 기능을 통해 사람이 이메일을 보냈습니다 |
| 웹 서비스 API | 개인이 SOAP/REST API를 통해 생성되었습니다. |
| 새 사람 | 사용자가 데이터베이스에 수동으로 입력되었습니다. |
| Munchkin API | Marketo의 Munchkin API를 통해 사람이 되었습니다. |
| 소셜 앱 | 소셜 위젯을 통해 사람이 되었습니다 |
| 이벤트 파트너 | 연결된 웨비나 서비스를 통해 사람이 되었습니다 |
