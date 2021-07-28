---
description: 현재 릴리스 노트 - Marketo 문서 - 제품 설명서
title: 현재 릴리스 노트
source-git-commit: c4dcf9a69dfb25a689175be6f1ff01d9dc21ad27
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 릴리스 노트: 2021년 8월 {#release-notes-aug-21}

다음 기능은 2021년 8월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo Engage 버전을 확인하십시오.

>[!AVAILABILITY]
>
>별(![](assets/yellow-star.png))로 표시되는 기능은 유료 추가 기능입니다. 자세한 내용은 Adobe Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2021년 8월 20일에 릴리스됩니다**.

## Adobe Experience Platform 통합 {#adobe-experience-platform-integration}

* **Adobe ID를 통한 Marketo Engage 사용자 인증**: 2021년 9월부터 Enterprise 패키지를 사용하는 새 Marketo Engage 사용자는 Adobe ID 사용자 자격 증명을 사용하여 온보딩됩니다. 현재 사용자를 통합 ID 시스템으로 마이그레이션하는 작업은 2022년 중반까지는 발생하지 않으며 추가 통지가 있을 때까지 수행할 필요가 없습니다. IT/보안 관리자는 Adobe ID 사용자 인증을 사용하여 다른 Experience Cloud 솔루션과 함께 여러 Marketo Engage 제품 인스턴스를 관리하고 공통 콘솔을 통해 SSO를 구성할 수 있습니다. 관리자는 사용자 그룹 및 사용자 권한을 한 곳에서 편리하게 관리할 수 있습니다.

## Experience Automation {#experience-automation}

* **실행 가능한 캠페인 중첩**: 이제 실행 가능한 캠페인이 다른 실행 가능한 캠페인을 호출하여 최대 3개 수준 깊이로 중첩할 수도 있습니다. 이를 통해 공통 운영 흐름을 더 통합하고 Smart Campaign 관리를 향상시킬 수 있습니다.

* **개인 세부 정보 페이지의 단일 흐름 작업**: 데이터베이스 그리드 보기로 전환하지 않고 흐름 작업 메뉴를 사용하여 개인 세부 정보 페이지에서 전자 메일 보내기, 개인 소유자 변경 또는 다른 스마트 캠페인 작업과 같은 플로우 작업을 실행합니다.

* **사용자 지정 활동 내보내기**: 메타데이터 내보내기는 이제 구독 데이터 모델을 공유, 분석 및 디자인하는 데 사용할 수 있는 모든 개체 및 각 메타데이터를 지원합니다.

## API 개선 사항 {#api-enhancements}

* **사용자 지정 필드 메타데이터 API**: 파트너 통합을 위한 Marketo Engage에서 사용자 지정 필드 생성 및 관리를 간소화합니다. 리드 개체에 새 필드를 자동으로 만들고, 여러 Marketo Engage 인스턴스에서 즉시 동시에 필드를 업데이트합니다.

* **향상된 필터링**: 이제 이메일 자산 및 프로그램 멤버 필드에 날짜 범위 필터를 추가하는 등의 여러 API에서 더 많은 필터링을 지원합니다. 이제 다음 API에 대한 특정 시간 내에 업데이트된 데이터만 추출할 수 있습니다.
   * 프로그램 구성원 가져오기
   * 이메일 가져오기
   * 벌크 활동 추출

* **양식 API 제출**: 이메일 주소가 둘 이상의 리드 레코드에 중복되면 Adobe에서는 완전히 건너뛰는 대신 &quot;마지막으로 업데이트된&quot; 레코드를 업데이트합니다. Forms 2.0 API와의 패리티를 제공합니다.

* **이메일 API**: 챔피언 또는 도전자 이메일 자산을 검색합니다.

**_분기 전체에 출시_**

다음 기능은 비분기별 사이클에 있으며 앞으로 몇 개월 동안 릴리스될 예정입니다.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **Salesforce CRM 사용자를 위한 Lead, Contact, Account 및 Opportunity 활동에 대한 가시성 개선**: Sales Insight에서 참여 기록이 증가함에 따라 긴 영업 주기 동안 잠재 고객과의 참여를 더 잘 알 수 있습니다. Lead, Contact, Account 및 Opportunity 객체에 걸쳐 최대 400개의 활동이 표시되는 흥미로운 순간, 웹 활동, 이메일 및 점수 탭

## 영업 연결 {#sales-connect}

![(별)](assets/yellow-star.png)

* **이메일 연결 제한(베타)**: Sales Connect의 이메일 연결 조절 기능을 통해 이메일 게재 능력을 향상시키고 개인화된 판매 커뮤니케이션을 확장할 수 있습니다. 이 새로운 기술은 이메일 전송 타이밍을 자동으로 관리하여 Exchange 및 Gmail 사용자를 위한 원활한 경험을 만듭니다. 타사 대량 이메일 전송 애플리케이션을 사용하거나 사용하지 않고 Sales Connect에서 모든 이메일을 신뢰할 수 있게 전송합니다.

>[!NOTE]
>
>이제 Beta에서 전자 메일 제한을 사용할 수 있습니다. [추가 정보](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

* **Enhanced Sales Activity Insights**: 영업 팀의 이전 활동을 기반으로 개인화된 참여를 캡처하고 활성화할 수 있습니다. Sales Call Recording Link, Sales Campaign Name 및 Sales Email Subject 와 같은 새로운 속성은 Marketo Engage 스마트 목록에서 사용할 수 있습니다.  이러한 활동은 Marketo Engage REST API 또는 벌크 내보내기를 통해 내보내거나 보고할 수 있으며, 스마트 목록에 대한 추가 제한으로 필터 및 트리거에서 사용할 수 있습니다.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Bizible LinkedIn Lead Gen Forms 통합**: 이제 마케터는 LinkedIn에서 Lead Gen Forms 광고 단위를 통해 양식이 채워질 때 발생하는 전환에 대한 매출 기여도 분석을 수행할 수 있습니다. 그런 다음 이러한 통찰력을 사용하여 양식 성능과 유료 미디어 투자를 최적화할 수 있습니다. linkedIn Lead Gen Forms 는 LinkedIn에서 가장 빠르게 성장하고 있는 유료 미디어 서비스 중 하나이며, 이 새로운 기능은 Bizible과 통합되는 기존 LinkedIn Ads에 포함되어 있습니다. 
 
* **향상된 속도 대시보드**: 심도 있는 인사이트를 위해 새로운 속도 지표 및 대시보드 필터를 추가했습니다. 이 대시보드는 마케터가 단계별 리드 및 기회 속도와 다양한 형태의 마케팅 및 판매 참여의 효율성을 이해하는 데 사용됩니다.

* **새 집단 폭포 여정 대시보드**: 이를 통해 마케터는 기존의 &quot;수요 흐름&quot; 단계 세트를 통해 선택한 집단에 대한 진행 상황을 볼 수 있으므로 전환율과 단계별 묵시적 스테이지 전환 인과성에 대해 신속하게 이해할 수 있습니다.

## Adobe Experience Cloud과 Bizible 통합 {#bizible-integration-with-adobe-experience-cloud}

이 섹션에는 IMS(Adobe Identity Management System) 마이그레이션을 완료한 Bizible 사용자를 위한 새로운 기능이 포함되어 있습니다. 마이그레이션된 경우 Adobe ID 탭 아래의 Bizible 설정에서 새 Adobe ID이 표시됩니다. 모든 계정은 2021년 말까지 마이그레이션해야 합니다.

* **Bizible과 Adobe Privacy Service**  통합(2021년 9월 출시): Bizible은 Adobe Privacy Service과 통합되므로 Adobe Experience Cloud 애플리케이션에서 중요한 데이터 개인 정보 보호 규정(예: GDPR)을 중앙 집중식으로 준수합니다. 이제 이 서비스를 활용하고 모든 개인 정보 보호 요청을 중앙에서 관리할 수 있으므로 Bizible 및 기타 Adobe 제품에 대한 변경 요청이 애플리케이션 간에 반영됩니다.

* **Adobe 통합 셸의 Bizible**: Bizible의 Adobe Unified Shell 채택을 통해 Bizible 애플리케이션 헤더 표시줄에 나타날 새로운 기능을 제공하고 리소스 및 애플리케이션 전환을 지원하기 위한 액세스 권한을 강화합니다. Adobe 통합 셸은 Bizible과 다른 Adobe Experience Cloud 애플리케이션 간에 일관된 경험을 만드는 데 도움이 됩니다.

* **Bizible 도메인 소유권 및 자체 관리**: Bizible 사용자는 Adobe Admin Console을 활용하여 Bizible에서 추적할 도메인을 관리할 수 있습니다. 이 경우 이전의 수동 프로세스에 셀프 서비스를 제공하고 Adobe Experience Cloud 애플리케이션에서 도메인 소유권 및 추적을 관리하는 방법에 대해 일관된 경험을 제공합니다.

## 공지 {#announcements}

* **구독 범용 ID 설정으로 업데이트**: 기존 사용자에 대해 예정된 Marketo Engage 및 Adobe ID 통합을 지원하기 위해 모든 Marketo Engage 구독이 범용 ID 지원 활성화에서 통합됩니다.
