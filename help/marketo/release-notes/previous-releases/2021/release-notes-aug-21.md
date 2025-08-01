---
description: 릴리스 노트 - 2021년 8월 - Marketo 문서 - 제품 설명서
title: 릴리스 정보 - 2021년 8월
exl-id: 4aec4e0b-520e-4786-a110-8e68f1bf9950
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '903'
ht-degree: 0%

---

# 릴리스 노트: 2021년 8월 {#release-notes-aug-21}

다음 기능은 2021년 8월 릴리스에 포함되어 있습니다. Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별(![](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Adobe Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2021년 8월 20일**&#x200B;에 릴리스됩니다.

## Experience Automated {#experience-automation}

* **Adobe Identity를 통한 Marketo Engage 사용자 인증**: 곧 Enterprise 패키지가 있는 새 Marketo Engage 사용자가 Adobe ID 사용자 자격 증명을 사용하여 온보딩됩니다. 현재 사용자를 통합 ID 시스템으로 마이그레이션하는 작업은 2022년 중반까지 수행되지 않으며 추가 공지가 있을 때까지 작업이 필요하지 않습니다. Adobe ID 사용자 인증을 사용하면 IT/보안 관리자가 다른 Experience Cloud 솔루션과 함께 여러 Marketo Engage 제품 인스턴스를 관리할 수 있을 뿐만 아니라 공통 콘솔을 통해 SSO를 구성할 수 있습니다. 관리자는 사용자 그룹과 사용자 권한을 한 곳에서 편리하게 관리할 수 있습니다.

* **실행 가능한 캠페인 중첩**: 이제 실행 가능한 캠페인에서 다른 실행 가능한 캠페인을 호출하여 최대 3단계까지 중첩할 수도 있습니다. 이를 통해 공통 운영 흐름을 더욱 통합할 수 있으며 Smart Campaign 관리를 향상시킬 수 있습니다.

* **개인 세부 정보 페이지의 단일 흐름 작업**(9월 9일까지 사용 가능): 데이터베이스 그리드 보기로 전환하지 않고 흐름 작업 메뉴를 사용하여 개인 세부 정보 페이지의 개별 사용자에게 전자 메일 보내기, 개인 소유자 변경 또는 기타 스마트 캠페인 작업과 같은 흐름 작업을 실행합니다.

* **[사용자 지정 활동 내보내기](/help/marketo/product-docs/administration/marketo-custom-activities/custom-activity-metadata-export.md)**: 메타데이터 내보내기는 이제 구독 데이터 모델을 공유, 분석 및 디자인하는 데 사용할 수 있는 모든 개체와 각 메타데이터를 지원합니다.

## API 개선 사항 {#api-enhancements}

* **양식 API 제출**: 이메일 주소가 둘 이상의 잠재 고객 레코드에서 중복되면 모두 건너뛰지 않고 &quot;마지막 업데이트&quot; 레코드를 업데이트합니다. Forms 2.0 API로 패리티를 제공합니다.

* **이메일 API**: 챔피언 또는 챌린저 이메일 자산을 검색합니다. 날짜 범위 필터를 사용하여 이메일 에셋을 검색합니다.

**_분기 내내 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## [!DNL Sales Insight] {#sales-insight}

![(별)](assets/yellow-star.png)

* **Salesforce CRM 사용자를 위한 Lead, Contact, Account 및 Opportunity 활동에 대한 가시성 향상**: [!DNL Sales Insight]에 참여 기록이 증가하여 긴 영업 주기 동안 잠재 고객과의 참여에 대한 정보가 향상됩니다. 관심 있는 순간, 웹 활동, 이메일 및 점수 탭에는 Lead, Contact, Account 및 Opportunity 객체에 걸쳐 최대 400 개의 활동이 표시됩니다.

## [!DNL Sales Connect] {#sales-connect}

![(별)](assets/yellow-star.png)

* **전자 메일 연결 제한(Beta)**: Sales Connect의 전자 메일 연결 제한을 통해 전자 메일 배달 가능성을 개선하고 개인화된 판매 커뮤니케이션을 확장하십시오. 이 새로운 기술은 [!DNL Exchange] 및 Gmail 사용자를 위한 원활한 경험을 만들기 위해 전자 메일 전송 타이밍을 자동으로 관리합니다. 타사 대량 전자 메일 전송 응용 프로그램을 줄이거나 제거하고 [!DNL Sales Connect]에서 모든 전자 메일을 안전하게 전송하세요.

>[!NOTE]
>
>이제 Beta에서 이메일 제한을 사용할 수 있습니다. [자세히 알아보기](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md)

* **향상된 판매 활동 인사이트**: 판매 팀의 이전 활동을 기반으로 개인화된 참여를 캡처하고 활성화합니다. 영업 통화 기록 링크, 영업 캠페인 이름 및 영업 이메일 제목과 같은 새 속성은 Marketo Engage 스마트 목록에서 사용할 수 있습니다.  이러한 활동은 Marketo Engage REST API 또는 일괄 내보내기 를 통해 내보내고 보고할 수 있으며 스마트 목록을 위한 추가 제한으로 필터 및 트리거에서 사용할 수 있습니다.

## [!DNL Bizible] {#bizible}

![](assets/yellow-star.png)

* **[!DNL Bizible][!DNL LinkedIn] 리드 세대 Forms 통합**: 이제 마케터는 [!DNL LinkedIn]이(가) 리드 세대 Forms 광고 단위를 통해 양식 채우기를 캡처할 때 발생하는 전환에 대해 매출 기여도 분석을 수행할 수 있습니다. 그런 다음 이러한 통찰력을 사용하여 양식 성능 및 유료 미디어 투자를 최적화할 수 있습니다. [!DNL LinkedIn] 리드 세대 Forms은 [!DNL LinkedIn]에서 가장 빠르게 성장하고 있는 유료 미디어 서비스 중 하나이며 이 새로운 기능은 [!DNL LinkedIn]과의 기존 [!DNL Bizible] 광고 통합에 포함되어 있습니다. 
 
* **속도 대시보드 개선**: 더 자세한 통찰력을 위해 새로운 속도 지표 및 대시보드 필터를 추가했습니다. 이 대시보드는 마케터가 단계별 잠재 고객 및 영업 기회 속도와 다양한 유형의 마케팅 및 판매 참여의 효율성을 이해하는 데 사용됩니다.

* **새로운 집단 폭포 여정 대시보드**: 이를 통해 마케터는 선택된 집단의 진행률을 클래식 &quot;수요 폭포&quot; 단계 집합을 통해 볼 수 있으므로 전환율과 단계별로 암시된 단계 전환 인과관계를 빠르게 이해할 수 있습니다.

## Adobe Experience Cloud과 [!DNL Bizible] 통합 {#bizible-integration-with-adobe-experience-cloud}

이 섹션에는 Adobe IMS(Identity Management System) 마이그레이션을 완료한 Bizible 사용자를 위한 새로운 기능이 포함되어 있습니다. 마이그레이션한 경우 Adobe ID 탭의 [!DNL Bizible] 설정에서 새 Adobe ID을 볼 수 있습니다. 모든 계정은 2021년 말까지 마이그레이션해야 합니다.

* **[!DNL Bizible]Adobe Privacy Service과의 통합**(2021년 9월 사용 가능): [!DNL Bizible]의 Adobe Privacy Service 통합은 Adobe Experience Cloud 애플리케이션 전반에서 중요한 데이터 개인 정보 보호 규정(예: GDPR) 준수를 중앙 집중화합니다. 이제 이 서비스를 활용하고 모든 개인 정보 요청을 중앙에서 관리하여 [!DNL Bizible] 및 다른 Adobe 제품에 포함된 변경 요청이 여러 애플리케이션에 반영되도록 할 수 있습니다.

* **[!DNL Bizible](Adobe 통합 쉘)**: [!DNL Bizible]의 Adobe 통합 쉘 채택 기능은 [!DNL Bizible] 응용 프로그램 헤더 표시줄에 나타날 새로운 기능을 사용자에게 제공하며 리소스 및 응용 프로그램 전환을 지원하는 더 나은 액세스 권한을 포함합니다. Adobe 통합 셸을 사용하면 [!DNL Bizible]과(와) 다른 Adobe Experience Cloud 응용 프로그램 간에 일관된 환경을 만들 수 있습니다.

* **[!DNL Bizible]도메인 소유권 및 자체 관리**: [!DNL Bizible] 사용자는 Adobe Admin Console을 활용하여 [!DNL Bizible]에서 추적할 도메인을 관리할 수 있습니다. 따라서 이전의 수동 프로세스에 셀프 서비스를 제공하고 Adobe Experience Cloud 애플리케이션 전반에서 도메인 소유권 및 추적을 관리하는 방법에 대한 일관된 경험을 제공합니다.

## 공지 {#announcements}

* **구독 범용 ID 설정 업데이트**: 기존 사용자에 대한 향후 Marketo Engage 및 Adobe Identity 통합을 지원하기 위해 범용 ID 지원 기능에서 모든 Marketo Engage 구독을 통합합니다. [자세한 정보는 여기에서 찾을 수 있습니다](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md).

**_제품 릴리스 웨비나_**

[2021년 8월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/August21_Release_Webinar.html)
