---
description: 릴리스 노트 - 2022년 1월 - Marketo 설명서 - 제품 설명서
title: 릴리스 노트 - 2022년 1월
exl-id: babc4e7f-3f11-4883-80c6-58e69c3e1ab4
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '889'
ht-degree: 0%

---

# 릴리스 노트: 2022년 1월 {#release-notes-jan-22}

다음 기능은 2022년 1월 릴리스에 포함되어 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별표로 표시되는 기능(![별](assets/yellow-star.png))는 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능에 대한 릴리스가 시작됩니다. **2022년 1월 21일**, (별도로 명시되지 않는 한) 다음 주에 걸친 모든 기능의 단계적 롤아웃 포함.

## 차세대 경험 {#modern-ux}

* **차세대 경험에서 업데이트된 화면**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 환경에서 새롭게 바뀐 추가 화면을 제공합니다.

   * Design Studio의 랜딩 페이지 자산 세부 정보
   * 마케팅 활동의 랜딩 페이지 자산 세부 정보

## Microsoft Dynamics 통합 {#microsoft-dynamics-integration}

* **다중 선택 옵션 집합 필드 유형 동기화(일반적으로 사용 가능)**: 보다 세분화된 대상 타깃팅을 위해 스마트 목록 및 스마트 캠페인에서 활용하도록 Microsoft Dynamics에서 다중 선택 옵션 집합 필드 유형을 동기화합니다. 예로는 관심 주제/제품, 선호하는 커뮤니케이션 모드 등이 있습니다. 이 새 동기화는 Microsoft Dynamics 버전 9.X(Dynamics 365 Online 포함)에서 사용할 수 있습니다.

* **Microsoft Dynamics 365 Online용 서버 간 인증**: 보안 강화를 위해 이제 Microsoft Dynamics 365 Online에 비대화식 액세스를 위해 Azure Active Directory에서 Marketo Engage 동기화 사용자를 위한 추가 인증 모드로 서버 간(S2S)을 지원합니다. 모든 인증 및 로그인이 OAuth(클라이언트 ID 및 클라이언트 암호만)를 기반으로 하므로 다단계 인증을 사용할 수 있습니다.

>[!NOTE]
>
>S2S 모드는 라이센스 사용자가 아닌 애플리케이션 사용자를 기반으로 하므로 추가 라이센스 사용이 절약됩니다.

## 관리 {#administration}

* **[양식 유효성 검사 규칙](/help/marketo/product-docs/administration/settings/global-form-validation-rules.md)**: 문제가 있거나 바람직하지 않은 이메일 도메인이 Marketo Engage 양식을 제출하지 못하도록 차단하는 기능으로 데이터베이스의 상태를 유지 관리합니다. 관리자는 전역 양식 유효성 검사 패널을 사용하여 양식에 대해 사전 정의된 차단 목록 목록을 정의하거나 자유 소비자 도메인이 차단되도록 할 수 있습니다.

* **[랜딩 페이지 헤더 보안](/help/marketo/product-docs/administration/settings/landing-page-headers.md)**: 관리자는 랜딩 페이지 도메인에서 엄격한 전송 보안 및 X-Frame 옵션 헤더를 관리하여 강력한 보안 요구 사항을 적용할 수 있습니다.

**_분기 전체에 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## AEP Marketo Engage 대상 커넥터 - 새로운 리드 만들기 {#aep-marketo-engage-destination-connector}

Adobe Experience Platform(AEP)를 사용하는 Marketo Engage 고객은 AEP 대상 커넥터를 통해 AEP에서 새로운 개인 레코드를 Marketo Engage으로 푸시할 수 있으므로 데이터베이스를 극대화할 수 있습니다. AEP에서 Marketo Engage으로 대상 세그먼트를 보낼 때 세그먼트 내에 아직 Marketo Engage 데이터베이스에 없는 사람이 있습니다 [에 자동으로 추가될 수 있습니다.](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/push-an-adobe-experience-platform-segment-to-a-marketo-static-list.md).

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

**Salesforce CRM에 대한 Sales Insight**

* **최상의 선택을 위한 새 유형 열**: 판매자는 모범 사례 페이지에서 리드와 연락처를 구별하기 위해 &quot;유형&quot;이라는 레이블이 지정된 새 열로 더 빠른 통찰력을 얻습니다.

* **Salesforce Platform API 업데이트**: Salesforce가 Salesforce Platform API 버전 21.0부터 30.0까지를 중단함에 따라 Sales Insight 패키지가 최신 API로 업데이트되었습니다.

* **업데이트된 브랜딩**: 모든 Sales Insight 페이지가 Adobe 브랜딩에 맞게 업데이트됩니다.

**Microsoft Dynamics용 Sales Insight**

* **업데이트된 계정 레이아웃**: 판매자는 이메일 활동, 웹 활동, 관심 있는 순간, 계정 내의 모든 연락처에 대한 점수 변경과 같은 상위 활동에 대한 집합적 보기를 얻을 수 있습니다.

## 영업 연결 {#sales-connect}

![(별)](assets/yellow-star.png)

* **호출 결과 및 이유**: 완전히 맞춤화가 가능한 새로운 통화 결과 및 통화 이유 옵션을 통해 판매 팀의 아웃바운드 노력을 더 자세히 이해하고 추적합니다. 이러한 새로운 필드 외에도 판매자가 호출하는 동안 통화 이유 및 결과 선택을 적용하는 새로운 거버넌스, 통화 이유 및 결과를 활성화 또는 비활성화하는 새로운 거버넌스 및 Salesforce에 데이터를 로깅하기 위한 새로운 통화 이유 및 통화 결과 Salesforce 활동 사용자 지정 필드를 도입합니다. [여기를 클릭하십시오.](https://nation.marketo.com/t5/product-blogs/sales-connect-enhancements-to-call-outcomes-q1-22-release/ba-p/319812) 자세히 알아보십시오.

* **Salesforce 활동 세부 정보 사용자 지정**: 판매 활동이 Sales Connect에서 Salesforce로 기록될 때 Salesforce 작업 주제 필드에 추가되는 정보를 사용자 정의하여 Salesforce에서 더 많은 판매 활동 및 작업 데이터를 캡처합니다. [여기를 클릭하십시오.](https://nation.marketo.com/t5/product-blogs/sales-connect-enahncements-to-activity-logging-to-salesforce-q1/ba-p/319819) 자세히 알아보십시오.

## 공지 {#announcements}

* **Marketo Sky 사용 중단**: 3월에는 차세대 사용자 경험을 제공하는 데 리소스를 집중하기 때문에 더 이상 Marketo Sky을 사용할 수 없습니다. 현재 Marketo Sky 전용인 기능에 대한 액세스를 유지하기 위한 노력으로, 3월에 자산 만료 및 스마트 캠페인 우선 순위 재정의를 주요 경험으로 가져올 예정입니다. [여기를 클릭하십시오.](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33) 자세히 알아보십시오.

* **양식 끝점 사용 중단**: leadCapture/save2 끝점에 대한 지원되지 않는 프로그래밍 방식 양식 POST가 Marketo Engage 양식에 의해 거부됩니다. [여기를 클릭하십시오.](https://nation.marketo.com/t5/product-documents/updated-october-2021-upcoming-changes-to-the-marketo-engage-form/ta-p/306631) 자세히 알아보십시오.

**Marketo Engage 도메인 - Sales Insight 구성**: SSL 인증서가 프로비저닝되고 https://이 없는 Marketo Engage 도메인의 경우 SSL 핸드셰이크 오류로 호출이 실패합니다. 따라서 이러한 도메인은 사용되지 않습니다. 따라서 이러한 도메인을 가리키는 이전 구성이 있는 Sales Insight 사용자는 Lead, Contact, Account, Opportunity Panel 또는 Marketo Global 페이지에서 시스템 호출 오류가 발생할 수 있습니다. 다음을 업데이트하는 것이 좋습니다. [Marketo Engage 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md) 이 오류가 발생하는 경우 Salesforce에서 을 참조하십시오. 문서의 &quot;Marketo Sales Insight Config&quot; 섹션에 강조 표시된 Marketo Engage 자격 증명만 업데이트하면 됩니다.

**_제품 릴리스 웨비나_**

[2022년 1월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_January_Release_Webinar_DemandPage.html)
