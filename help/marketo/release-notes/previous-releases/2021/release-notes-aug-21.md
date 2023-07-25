---
description: 릴리스 노트 - 2021년 8월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2021년 8월
exl-id: 4aec4e0b-520e-4786-a110-8e68f1bf9950
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '925'
ht-degree: 0%

---

# 릴리스 노트: 2021년 8월 {#release-notes-aug-21}

다음 기능은 2021년 8월 릴리스에 포함되어 있습니다. 사용 가능한 기능이 있는지 Marketo Engage 버전을 확인하십시오.

>[!AVAILABILITY]
>
>별표로 표시되는 기능(![](assets/yellow-star.png))는 유료 추가 기능입니다. 자세한 내용은 Adobe Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능이에 릴리스됩니다. **2021년 8월 20일**.

## Experience Automated {#experience-automation}

* **Marketo Engage ID를 통한 Adobe 인증**: 곧 Enterprise 패키지가 있는 새 Marketo Engage 사용자가 Adobe ID 사용자 자격 증명을 사용하여 온보딩됩니다. 현재 사용자를 통합 ID 시스템으로 마이그레이션하는 작업은 2022년 중반까지 수행되지 않으며 추가 공지가 있을 때까지 작업이 필요하지 않습니다. Adobe ID 사용자 인증을 사용하면 IT/보안 관리자가 다른 Experience Cloud 솔루션과 함께 여러 Marketo Engage 제품 인스턴스를 관리할 수 있을 뿐만 아니라 공통 콘솔을 통해 SSO를 구성할 수 있습니다. 관리자는 사용자 그룹과 사용자 권한을 한 곳에서 편리하게 관리할 수 있습니다.

* **실행 가능한 캠페인 중첩**: 이제 실행 가능한 캠페인에서 다른 실행 가능한 캠페인을 호출하여 최대 3단계 깊이로 중첩할 수도 있습니다. 이를 통해 공통 운영 흐름을 더욱 통합할 수 있으며 Smart Campaign 관리를 향상시킬 수 있습니다.

* **개인 세부 정보 페이지의 단일 흐름 작업** (9월 9일까지 사용 가능): 데이터베이스 그리드 뷰로 전환하지 않고 플로우 작업 메뉴를 사용하여 개인 세부 정보 페이지에서 개별 사용자에 대해 이메일 보내기, 개인 소유자 변경 또는 기타 스마트 캠페인 작업과 같은 플로우 작업을 실행합니다.

* **[사용자 정의 활동 내보내기](/help/marketo/product-docs/administration/marketo-custom-activities/custom-activity-metadata-export.md)**: 메타데이터 내보내기는 이제 구독 데이터 모델을 공유, 분석 및 디자인하는 데 사용할 수 있는 모든 개체와 각 메타데이터를 지원합니다.

## API 개선 사항 {#api-enhancements}

* **양식 API 제출**: 이메일 주소가 둘 이상의 잠재 고객 레코드에서 중복되면 모두 건너뛸 것이 아니라 &quot;마지막 업데이트&quot; 레코드를 업데이트합니다. Forms 2.0 API로 패리티를 제공합니다.

* **이메일 API**: 챔피언 또는 챌린저 이메일 자산을 검색합니다. 날짜 범위 필터를 사용하여 이메일 에셋을 검색합니다.

**_분기 전체에 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **Salesforce CRM 사용자를 위한 Lead, Contact, Account 및 Opportunity 활동에 대한 가시성 향상**: Sales Insight의 참여 기록 수가 증가하여 긴 영업 주기 동안 잠재 고객과의 참여에 대한 정보가 더욱 풍부해졌습니다. 관심 있는 순간, 웹 활동, 이메일 및 점수 탭에는 Lead, Contact, Account 및 Opportunity 객체에 걸쳐 최대 400 개의 활동이 표시됩니다.

## 영업 연결 {#sales-connect}

![(별)](assets/yellow-star.png)

* **이메일 연결 제한(Beta)**: Sales Connect의 이메일 연결 제한을 통해 이메일 전달성을 개선하고 개인화된 판매 커뮤니케이션을 확장하십시오. 이 새로운 기술은 Exchange 및 Gmail 사용자를 위한 원활한 경험을 만들기 위해 이메일 전송 타이밍을 자동으로 관리합니다. 서드파티 벌크 이메일 전송 애플리케이션의 사용을 줄이거나 제거하고 Sales Connect에서 모든 이메일을 안심하고 보낼 수 있습니다.

>[!NOTE]
>
>이제 Beta에서 이메일 제한을 사용할 수 있습니다. [자세히 알아보기](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

* **Enhanced Sales Activity Insights**: 영업팀의 이전 활동을 기반으로 개인화된 참여를 캡처하고 활성화합니다. 영업 통화 기록 링크, 영업 캠페인 이름 및 영업 이메일 제목과 같은 새 속성을 Marketo Engage 스마트 목록에서 사용할 수 있습니다.  이러한 활동은 Marketo Engage REST API 또는 일괄 내보내기 를 통해 내보내고 보고할 수 있으며 스마트 목록을 위한 추가 제한으로 필터 및 트리거에서 사용할 수 있습니다.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Bizible LinkedIn Lead Gen Forms 통합**: 이제 마케터는 LinkedIn이 리드 세대 Forms 광고 단위를 통해 양식 채우기를 캡처할 때 발생하는 전환에 대해 매출 기여도 분석을 수행할 수 있습니다. 그런 다음 이러한 통찰력을 사용하여 양식 성능 및 유료 미디어 투자를 최적화할 수 있습니다. LinkedIn 리드 젠인 Forms은 LinkedIn에서 가장 빠르게 성장하고 있는 유료 미디어 제품 중 하나이며 이 새로운 기능은 Bizible과의 기존 LinkedIn Ads 통합에 포함되어 있습니다.

* **향상된 속도 대시보드**: 보다 심층적인 통찰력을 위해 새로운 속도 지표 및 대시보드 필터를 추가했습니다. 이 대시보드는 마케터가 단계별 잠재 고객 및 영업 기회 속도와 다양한 유형의 마케팅 및 판매 참여의 효율성을 이해하는 데 사용됩니다.

* **새 집단 폭포 여정 대시보드**: 이를 통해 마케터는 클래식 &quot;수요 폭포&quot; 스테이지 세트를 통해 선택한 집단의 진행률을 볼 수 있으므로 전환율과 단계별로 암시적인 스테이지 전환 인과관계를 빠르게 이해할 수 있습니다.

## Adobe Experience Cloud과 Bizible 통합 {#bizible-integration-with-adobe-experience-cloud}

이 섹션에는 Adobe IMS(Identity Management System) 마이그레이션을 완료한 Bizible 사용자를 위한 새로운 기능이 포함되어 있습니다. 마이그레이션한 경우 Adobe ID 탭 아래의 Bizible 설정에 새 Adobe ID이 표시됩니다. 모든 계정은 2021년 말까지 마이그레이션해야 합니다.

* **Bizible Adobe Privacy Service 통합** (2021년 9월 제공): Bizible은 Adobe Privacy Service과 통합되어 Adobe Experience Cloud 애플리케이션 전반에서 중요한 데이터 개인 정보 보호 규정(예: GDPR) 준수를 중앙 집중화합니다. 이제 이 서비스를 활용하고 모든 개인 정보 보호 요청을 중앙에서 관리하여 Bizible 및 기타 Adobe 제품으로 들어오는 변경 요청이 여러 애플리케이션에 반영되도록 할 수 있습니다.

* **Adobe Experience Cloud 인터페이스의 Bizible**: Bizible이 Adobe Experience Cloud 인터페이스를 채택하면 Bizible 애플리케이션 헤더 표시줄에 표시되는 새로운 기능에 지원 리소스 및 애플리케이션 전환에 대한 액세스 기능이 향상됩니다. Experience Cloud 인터페이스는 Bizible과 다른 Adobe Experience Cloud 애플리케이션 간에 일관된 환경을 만드는 데 도움이 됩니다.

* **Bizible 도메인 소유권 및 자체 관리**: Bizible 사용자는 Adobe Admin Console을 활용하여 Bizible이 추적할 도메인을 관리할 수 있습니다. 따라서 이전의 수동 프로세스에 셀프 서비스를 제공하고 Adobe Experience Cloud 애플리케이션 전반에서 도메인 소유권 및 추적을 관리하는 방법에 대한 일관된 경험을 제공합니다.

## 공지 {#announcements}

* **구독 범용 ID 설정 업데이트**: 기존 사용자에 대해 예정된 Marketo Engage 및 Adobe ID 통합을 지원하기 위해 범용 ID 지원 기능에서 모든 Marketo Engage 구독을 통합합니다. 추가 정보 [은(는) 여기에서 찾을 수 있음](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md).

**_제품 릴리스 웨비나_**

[2021년 8월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/August21_Release_Webinar.html)
