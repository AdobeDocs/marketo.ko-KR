---
unique-page-id: 2953415
description: 개인 세부 사항 페이지 사용 - Marketo 문서 - 제품 설명서
title: 개인 세부 정보 페이지 사용
exl-id: 8476ed02-6d94-4aa5-91f6-55c81a87f745
source-git-commit: a24b0de6493d4849723099d6164fafb73ef7c926
workflow-type: tm+mt
source-wordcount: '550'
ht-degree: 19%

---

# 개인 세부 정보 페이지 사용 {#using-the-person-detail-page}

개인 세부 사항 페이지에는 Marketo에서 한 사람에 대해 알고 있는 모든 정보가 포함되어 있습니다. 이 페이지에서 직접 데이터를 편집할 수 있습니다.

## 개인 세부 정보 페이지 가져오기 {#getting-to-person-detail-page}

특정한 사람들을 여는 방법에는 많은 것들이 있습니다. 예를 들면 다음과 같습니다.

* 에서 **데이터베이스**&#x200B;를 검색하는 경우
* 모든 스마트 **list** 또는 list
* **멤버** 프로그램의 탭
* **캠페인 구성원 보기** 스마트 캠페인
* 일부 **보고서**

   <br> 

1. 사람을 두 번 클릭하거나 왼쪽의 ID를 한 번 클릭합니다.

   ![](assets/one-1.png)

1. 그러면 개인 세부 사항 화면이 열립니다.

   ![](assets/two-5.png)

## 페이지 조직 - Salesforce {#page-organization-salesforce}

개인 정보는 다음 탭으로 분류됩니다.

| 탭 | 설명 |
|---|---|
| 정보 | 사람에 대한 연락처 정보 및 사용자 지정 필드. |
| 회사 정보 | 개인의 회사 정보 및 주소입니다. |
| 영업 기회 정보 | Salesforce에서 동기화된 영업 기회 정보. |
| SFDC 리드 필드 | 기본 제공 Salesforce 필드. |
| SFDC 사용자 지정 필드 | 사용자 지정 Salesforce 필드. |
| 활동 로그 | 사람과 관련된 모든 활동. |

## 페이지 조직 - Microsoft Dynamics {#page-organization-microsoft-dynamics}

| 탭 | 설명 |
|---|---|
| 정보 | 사람에 대한 연락처 정보 및 사용자 지정 필드. |
| 회사 정보 | 개인의 회사 정보 및 주소입니다. |
| 영업 기회 정보 | Microsoft에서 동기화된 기회 정보. |
| Microsoft 사용자 지정 필드 | 사용자 지정 Microsoft 필드. |
| Microsoft 리드 필드 | 기본 제공 Microsoft 필드. |
| 활동 로그 | 사람과 관련된 모든 활동. |

>[!NOTE]
>
>Opportunity 정보를 볼 수도 있습니다 [API를 통해 삽입됨](https://developers.marketo.com/rest-api/lead-database/opportunities/) CRM과 동기화되지 않는 인스턴스용.

## 필드 편집 {#editing-a-field}

많은 필드를 편집할 수 있습니다. 개인 정보를 업데이트하려면 새 값을 입력하고 필드 바깥쪽을 클릭하여 저장합니다.

![](assets/image2015-2-27-11-3a14-3a2.png)

## CRM 동기화 전 Marketo 기본 필드 {#marketo-default-fields-prior-to-crm-sync}

|  |  |  |  |  |
|---|---|---|---|---|
| 주소 | 연매출 | 익명 IP | 청구지 주소 | 청구지 시 |
| 청구지 국가 | 청구지 우편번호 | 청구지 주 | 시 | 회사명 |
| 국가 | 생성 위치 | 출생일 | 부서 | 두 낫 콜 |
| 원인 호출 안 함 | 두 낫 콜 이유 | 이메일 주소 | 이메일이 잘못되었습니다. | 잘못된 이메일 원인 |
| 외부 회사 Id | 외부 영업 사원 ID | 팩스 번호 | 이름 | 전체 이름 |
| 산업 | 유추된 시 | 추론된 회사 | 추론된 국가 | 대도시 지역 유추 |
| 전화번호 지역코드 유추 | 우편번호 유추 | 유추된 주 지역 | 익명 | 고객 |
| 파트너 | 직위 | 성 | 등급 | 스코어 |
| 개인 소스 | 상태 | 메인 전화 | Marketo Social Facebook 표시 이름 | Marketo Social Facebook Id |
| Marketo Social Facebook 사진 URL | Marketo Social Facebook 프로필 URL | Marketo Social Facebook 도달 범위 | Marketo Social Facebook에서 참조하는 등록 | Marketo Social Facebook 참조 방문 |
| Marketo 소셜 성별 | Marketo Social 마지막 참조 등록 | Marketo Social 마지막 참조 방문 | Marketo Social LinkedIn 표시 이름 | Marketo Social LinkedIn Id |
| Marketo Social LinkedIn 사진 URL | Marketo Social LinkedIn 프로필 URL | Marketo Social LinkedIn 도달 범위 | Marketo Social LinkedIn에서 참조하는 등록 | Marketo Social LinkedIn 참조 방문 |
| Marketo Social 신디케이션 ID | Marketo Social 총 참조 등록 | Marketo 소셜 총 참조된 방문 수 | Marketo 소셜 Twitter 표시 이름 | Marketo Social Twitter Id |
| Marketo 소셜 Twitter 사진 URL | Marketo 소셜 Twitter 프로필 URL | Marketo 소셜 Twitter 도달 범위 | Marketo Social Twitter 참조 등록 | Marketo Social Twitter 참조 방문 |
| 중간 이름 | 휴대 전화 번호 | 직원 수 | 전화 번호 | 우편 번호 |
| 우선 순위 | 상대 점수 | 역할 | 인사말 | SIC 코드 |
| 사이트 | 주 | 주소 삭제 | 주소 삭제 이유 | 업데이트 날짜: |
| 긴급성 | 웹 사이트 |  |  |  |

>[!NOTE]
>
>일부 필드는 다음과 같습니다 _not_ 편집 가능:
>
>* 활동 로그
>* 회사 정보
>* SFDC 연락처 기회
>* 만든 날짜 및 원래 소스 유형과 같은 특정 Marketo 관련 필드입니다.
>
>추가 정보 [시스템 관리 필드](/help/marketo/product-docs/administration/field-management/understanding-system-managed-fields.md).

>[!MORELIKETHIS]
>
>[개인 세부 정보 페이지에 대한 사용자 지정 탭 생성](/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md)
