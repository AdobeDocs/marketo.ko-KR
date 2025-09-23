---
unique-page-id: 2953415
description: 개인 세부 정보 페이지 사용 - Marketo 문서 - 제품 설명서
title: 개인 정보 페이지 사용
exl-id: 8476ed02-6d94-4aa5-91f6-55c81a87f745
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '525'
ht-degree: 26%

---

# 개인 정보 페이지 사용 {#using-the-person-detail-page}

개인 세부 정보 페이지에는 Marketo이 개인에 대해 알고 있는 모든 정보가 포함되어 있습니다. 이 페이지에서 직접 데이터를 편집할 수 있습니다.

## 개인 세부 정보 페이지로 이동 {#getting-to-person-detail-page}

특정 사람들을 여는 방법에는 여러 가지가 있습니다. 몇 가지 예는 다음과 같습니다.

* **데이터베이스**&#x200B;에서 빠른 찾기에서 검색할 수 있습니다.
* 모든 **스마트 목록** 또는 목록
* 프로그램의 **구성원** 탭
* 스마트 캠페인에서 **캠페인 구성원 보기**
* 일부 **보고서**
  <br> 

1. 사용자를 두 번 클릭하거나 왼쪽의 ID를 한 번 클릭합니다.

   ![](assets/one-1.png)

1. 이렇게 하면 개인 세부 정보 화면이 열립니다.

   ![](assets/two-5.png)

## 페이지 조직 - Salesforce {#page-organization-salesforce}

개인 정보는 다음 탭으로 분류됩니다.

| 탭 | 설명 |
|---|---|
| 정보 | 사용자에 대한 연락처 정보 및 사용자 정의 필드. |
| 회사 정보 | 개인 회사 정보 및 주소. |
| 영업 기회 정보 | Salesforce에서 동기화된 영업 기회 정보. |
| SFDC 리드 필드 | 내장 Salesforce 필드. |
| SFDC 사용자 정의 필드 | 사용자 지정 Salesforce 필드. |
| 활동 로그 | 사용자와 관련된 모든 활동. |

## 페이지 조직 - Microsoft Dynamics {#page-organization-microsoft-dynamics}

| 탭 | 설명 |
|---|---|
| 정보 | 사용자에 대한 연락처 정보 및 사용자 정의 필드. |
| 회사 정보 | 개인 회사 정보 및 주소. |
| 영업 기회 정보 | Microsoft에서 동기화된 영업 기회 정보. |
| Microsoft 사용자 정의 필드 | 사용자 지정 Microsoft 필드. |
| Microsoft 리드 필드 | 내장 Microsoft 필드. |
| 활동 로그 | 사용자와 관련된 모든 활동. |

>[!NOTE]
>
>CRM과 동기화되지 않은 인스턴스에 대한 영업 기회 정보 [API를 통해 삽입됨](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities)도 볼 수 있습니다.

## 필드 편집 {#editing-a-field}

편집 가능한 필드가 많습니다. 개인 정보를 업데이트하려면 새 값을 입력하고 필드 외부를 눌러 저장합니다.

![](assets/image2015-2-27-11-3a14-3a2.png)

## CRM 동기화 전 Marketo 기본 필드 {#marketo-default-fields-prior-to-crm-sync}

|   |  |  |  |  |
|---|---|---|---|---|
| 주소 | 연매출 | 익명 IP | 청구지 주소 | 청구지 시 |
| 청구지 국가 | 청구지 우편번호 | 청구지 주 | 구/군/시 | 회사 이름 |
| 국가 | 생성 위치 | 출생일 | 부서 | 두 낫 콜 |
| 원인 호출 안 함 | 두 낫 콜 이유 | 이메일 주소 | 잘못된 이메일 | 잘못된 이메일 원인 |
| 외부 회사 ID | 외부 영업 사원 ID | 팩스 번호 | 이름 | 전체 이름 |
| 업종 | 추론된 시 | 추론된 회사 | 추론된 국가 | 대도시 지역 유추 |
| 전화번호 지역코드 유추 | 추론된 우편번호 | 유추된 주 지역 | 익명 | 고객 |
| 파트너 | 직위 | 성 | 등급 | 점수 |
| 개인 Source | 상태 | 주요 전화 | Marketo Social [!DNL Facebook] 표시 이름 | Marketo Social [!DNL Facebook] Id |
| Marketo Social [!DNL Facebook] 사진 URL | Marketo Social [!DNL Facebook] 프로필 URL | Marketo Social [!DNL Facebook] 도달 | Marketo Social [!DNL Facebook] 참조 등록 | Marketo Social [!DNL Facebook] 참조 방문 |
| Marketo 소셜 젠더 | Marketo Social 마지막 참조 등록 | Marketo Social 마지막 참조 방문 | Marketo Social [!DNL LinkedIn] 표시 이름 | Marketo Social [!DNL LinkedIn] Id |
| Marketo Social [!DNL LinkedIn] 사진 URL | Marketo Social [!DNL LinkedIn] 프로필 URL | Marketo Social [!DNL LinkedIn] 도달 | Marketo Social [!DNL LinkedIn] 참조 등록 | Marketo Social [!DNL LinkedIn] 참조 방문 |
| Marketo Social 신디케이션 ID | Marketo Social 총 참조된 등록자 수 | Marketo Social 총 참조된 방문 수 | Marketo Social [!DNL Twitter] 표시 이름 | Marketo Social [!DNL Twitter] Id |
| Marketo Social [!DNL Twitter] 사진 URL | Marketo Social [!DNL Twitter] 프로필 URL | Marketo Social [!DNL Twitter] 도달 | Marketo Social [!DNL Twitter] 참조 등록 | Marketo Social [!DNL Twitter] 참조 방문 |
| 중간 이름 | 휴대 전화 번호 | 직원 수 | 전화 번호 | 우편번호 |
| 우선순위 | 상대 스코어 | 역할 | 인사말 | SIC 코드 |
| 사이트 | 주/도 | 구독 취소 | 주소 삭제 이유 | 업데이트 시간 |
| 긴급도 | 웹 사이트 |  |  |  |

>[!NOTE]
>
>일부 필드를 _편집할 수 없음_:
>
>* 활동 로그
>* 회사 정보
>* SFDC 담당자를 위한 기회
>* 만든 날짜 및 원래 Marketo 유형과 같은 특정 Source 관련 필드.
>
>[시스템 관리 필드](/help/marketo/product-docs/administration/field-management/understanding-system-managed-fields.md){target="_blank"}에 대해 자세히 알아보세요.

>[!MORELIKETHIS]
>
>[개인 세부 정보 페이지에 대한 사용자 지정 탭 만들기](/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md){target="_blank"}
