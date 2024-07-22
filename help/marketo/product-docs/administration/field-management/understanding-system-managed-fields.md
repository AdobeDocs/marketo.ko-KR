---
unique-page-id: 5472615
description: 시스템 관리 필드 이해 - Marketo 문서 - 제품 설명서
title: 시스템 관리 필드 이해
exl-id: 4a58d41f-c2f5-4bcc-93ef-10a31e5475fd
feature: Field Management
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '512'
ht-degree: 7%

---

# 시스템 관리 필드 이해 {#understanding-system-managed-fields}

[개인 세부 정보 페이지](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md){target="_blank"}에 Marketo에서 만든 일련의 편집 불가능한 필드가 있습니다. 이 데이터는 다양한 출처에서 나오며, 표시할 수 있는 수많은 가치가 있다.

## 필드 유형 {#field-types}

| **필드 이름** | **정의** |
|---|---|
| 원본 소스 유형 | 사용자 또는 웹 사이트 방문자가 처음 발견된 위치(예: 목록 가져오기, 웹 페이지 방문) |
| 원본 소스 정보 | 해당 위치에 대한 세부 사항(예: 목록 이름, 웹 페이지의 URL) |
| 원본 검색 엔진 | 해당하는 경우 해당 개인을 최초 입력 출처로 참조한 검색 엔진 |
| 원본 검색 구문 | 해당하는 경우, 최초 입력 출처로 해당 사용자를 참조한 검색어가 사용됨 |
| 원래 레퍼러 | 원래 항목 소스를 호스팅하는 URL |
| 등록 Source 유형 | 활동이 처음 개인이 된 위치(예: 목록 가져오기, 웹 페이지 방문) |
| 등록 Source 정보 | 해당 위치에 대한 세부 사항(예: 목록 이름, 웹 페이지의 URL) |
| 익명 IP | 개인의 IP 주소를 나타냅니다. |
| 추론된 회사 | 개인 회사의 Marketo 최고 추측(IP 기반) |
| 추론된 시 | 해당 도시의 Marketo 최고의 추측(IP 기반) |
| 유추된 주 지역 | 개인 상태 또는 지역에 대한 Marketo의 최고 추측(IP 기반) |
| 추론된 우편번호 | 개인 우편 번호에 대한 Marketo의 최적 추측(IP 기반) |
| 추론된 국가 | 해당 국가에 대한 Marketo의 최고 추측(IP 기반) |
| 대도시 지역 유추 | 개인 대도시 지역에 대한 Marketo의 최고 추측(IP 기반) |
| 전화번호 지역코드 유추 | 개인 지역 코드에 대한 Marketo의 최고 추측(IP 기반) |

## 원래 및 등록 Source 유형에 대해 가능한 값 {#possible-values-for-original-and-registration-source-type}

다음은 몇 가지 가능한 값과 그 의미입니다.

| **원래 Source 유형** | **정의** |
|---|---|
| Salesforce.com | [!DNL Webhook] 동기화에서 사용자를 검색했습니다. |
| 웹 페이지 방문 횟수 | 웹 페이지에서 사람을 발견했습니다. |
| 웹 양식 채우기 | 양식을 작성한 후 발견됨 |
| 목록 가져오기 | 목록 가져오기에서 사용자 검색됨 |
| 새 사용자 | 사용자가 데이터베이스에 수동으로 입력되었습니다. |
| 웹 링크 클릭 | 링크를 클릭한 후 사람을 발견했습니다. |
| 영업 이메일 | [!DNL Sales Insight] 전자 메일 추가 기능을 통해 전자 메일을 보냈습니다. |
| 개인 | 사용자가 [!DNL Salesforce]에서 사용자로 동기화되었습니다. |
| 연락처 | [!DNL Webhook]에서 사용자를 연락처로 동기화했습니다. |
| [!DNL Munchkin] API | Marketo Engage [!DNL Munchkin] API에서 사용자를 검색했습니다. |
| 소셜 앱 | 소셜 위젯에 의해 개인이 검색됨 |
| 웹 서비스 API | 웹 서비스 API에 의해 개인을 검색했습니다. |
| 이벤트 파트너 | 동기화된 웨비나 서비스를 통해 사람을 발견했습니다. |
| 리드 연결 | 리드 API 연결 호출을 통해 병합된 개인 |

| **등록 Source 유형** | **정의** |
|---|---|
| 목록 가져오기 | 목록 가져오기를 통해 사람이 됨 |
| Salesforce.com | [!DNL Webhook] 동기화를 통해 사람이 됨 |
| 웹 양식 채우기 | 양식을 작성한 후 사람이 됨 |
| 영업 이메일 | [!DNL Webhook] 전자 메일 추가 기능을 통해 전자 메일을 보냈습니다. |
| 웹 서비스 API | 개인이 SOAP/REST API를 통해 생성됨 |
| 새 사용자 | 사용자가 데이터베이스에 수동으로 입력되었습니다. |
| [!DNL Munchkin] API | Marketo의 [!DNL Munchkin] API를 통해 사람이 됨 |
| 소셜 앱 | 소셜 위젯을 통해 사람이 됨 |
| 이벤트 파트너 | 연결된 웨비나 서비스를 통해 사람이 됨 |
