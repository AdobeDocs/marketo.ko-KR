---
description: 릴리스 노트 - 2022년 1월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2022년 1월
source-git-commit: 9136ef46cd3b3293bef605dec997f23b46fa4326
workflow-type: tm+mt
source-wordcount: '964'
ht-degree: 0%

---

# 릴리스 노트: 2022년 1월 {#release-notes-jan-22}

다음 기능은 2022년 1월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Adobe Marketo Engage 버전을 확인하십시오.

>[!AVAILABILITY]
>
>별로 표시된 기능(![별](assets/yellow-star.png))은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은에서 릴리스되기 시작합니다 **2022년 1월 21일**&#x200B;를 설정하는 경우, 다음 주 동안 모든 기능을 단계별로 롤아웃합니다(별도로 지정하지 않는 한).

## 차세대 경험 {#next-generation-experience}

* **차세대 경험에서 업데이트된 화면**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 환경에서 새로 고친 추가 화면을 제공하고 있습니다.

   * Design Studio의 랜딩 페이지 자산 세부 사항
   * 마케팅 활동의 랜딩 페이지 자산 세부 사항

## Microsoft Dynamics 통합 {#microsoft-dynamics-integration}

* **일반적으로 사용할 수 있는 다중 선택 옵션 집합 필드 유형의 동기화**: 보다 세부적인 대상 타깃팅을 위해 Microsoft Dynamics에서 다중 선택 선택 선택 옵션 설정 필드 유형을 동기화하여 스마트 목록 및 스마트 캠페인에서 활용하십시오. 해당 예는 다음과 같습니다. 관심 분야/제품, 선호하는 커뮤니케이션 모드 등 이 새로운 동기화는 Microsoft Dynamics 버전 9.X(Dynamics 365 Online 포함)에서 사용할 수 있습니다.

* **Microsoft Dynamics 365 Online을 위한 서버 간 인증**: 보안 강화를 위해 이제 Microsoft Dynamics 365 Online에 비대화형 액세스를 위해 Azure Active Directory에서 Marketo Engage 동기화 사용자에 대한 추가 인증 모드로 서버 간(S2S)을 지원합니다. 모든 인증 및 사인온은 OAuth(클라이언트 ID 및 클라이언트 암호만)를 기반으로 하므로 다단계 인증을 사용할 수 있습니다.

>[!NOTE]
>
>S2S 모드는 라이센스 사용자가 아닌 애플리케이션 사용자를 기반으로 하여 추가 라이센스 사용을 저장합니다.

## 관리 {#administration}

* **[양식 유효성 검사 규칙](/help/marketo/product-docs/administration/settings/global-form-validation-rules.md)**: 문제 또는 바람직하지 않은 전자 메일 도메인이 Marketo Engage 양식을 제출하지 않도록 차단하는 기능을 사용하여 데이터베이스의 상태를 유지합니다. 관리자는 전역 양식 유효성 검사 규칙 패널을 사용하여을 정의하거나 미리 정의된 사용 가능한 소비자 도메인 목록을 차단 목록에 추가하다 활성화하여 양식에서 차단할 수 있습니다.

* **[랜딩 페이지 헤더 보안](/help/marketo/product-docs/administration/settings/landing-page-headers.md)**: 관리자는 랜딩 페이지 도메인에서 엄격한 전송 보안 및 X-Frame 옵션 헤더를 관리하여 강력한 보안 요구 사항을 적용할 수 있습니다.

**_분기 전체에 출시_**

다음 기능은 비분기별 사이클에 있으며 앞으로 몇 개월 동안 릴리스될 예정입니다.

## AEP Marketo Engage 대상 커넥터 - 신규 리드 만들기 {#aep-marketo-engage-destination-connector}

Adobe Experience Platform(AEP)도 사용하는 Marketo Engage 고객은 AEP 대상 커넥터를 통해 AEP의 Marketo Engage에 신규 개인 레코드를 푸시할 수 있으므로 데이터베이스를 극대화할 수 있습니다. AEP에서 Marketo Engage으로 대상 세그먼트를 보낼 때 세그먼트 내에 아직 존재하지 않는 사람이 Marketo Engage 데이터베이스에 있게 됩니다 [자동으로 추가할 수 있습니다](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/push-an-adobe-experience-platform-segment-to-a-marketo-static-list.md).

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

**Salesforce CRM용 Sales Insight**

* **최상의 선택을 위한 새 유형 열**: 판매자는 Best Pets 페이지에서 리드와 연락처를 구분하기 위해 &quot;Type&quot;이라는 레이블이 지정된 새 열을 사용하여 더 빠른 인사이트를 얻을 수 있습니다.

* **Salesforce 플랫폼 API 업데이트**: Salesforce의 종료에 따른 Salesforce Platform API 버전 21.0부터 30.0까지, Sales Insight 패키지가 최신 API로 업데이트되었습니다.

* **업데이트된 브랜딩**: 모든 Sales Insight 페이지가 Adobe 브랜딩에 맞게 업데이트됩니다.

**Microsoft Dynamics용 Sales Insight**

* **업데이트된 계정 레이아웃**: 판매자는 다음과 같은 최상위 활동을 집단적으로 볼 수 있습니다. 계정 내 모든 연락처에 대한 이메일 활동, 웹 활동, 흥미로운 순간 및 점수 변경 사항입니다.

## 영업 연결 {#sales-connect}

![(별)](assets/yellow-star.png)

* **통화 결과 및 이유**: 새롭고 완벽하게 사용자 지정 가능한 호출 결과 및 호출 이유 옵션을 사용하여 영업 팀의 아웃바운드 노력을 보다 자세히 파악하고 추적합니다. 이러한 새로운 필드 외에도 Adobe에서는 판매자가 호출을 하는 동안 통화 이유와 결과 선택을 강제 적용하는 새로운 거버넌스, 호출 이유 및 결과를 활성화 또는 비활성화하는 새로운 거버넌스, Salesforce에 데이터를 로깅하는 새 호출 이유 및 호출 결과 Salesforce 활동 사용자 지정 필드를 도입했습니다. [여기를 클릭하십시오.](https://nation.marketo.com/t5/product-blogs/sales-connect-enhancements-to-call-outcomes-q1-22-release/ba-p/319812) 추가 정보

* **Salesforce 활동 세부 사항 사용자 지정**: Sales Connect에서 Salesforce에 영업 활동이 기록될 때 Salesforce 작업 제목 필드에 추가되는 정보를 사용자 지정하여 Salesforce에서 더 많은 영업 활동 및 작업 데이터를 캡처합니다. [여기를 클릭하십시오.](https://nation.marketo.com/t5/product-blogs/sales-connect-enahncements-to-activity-logging-to-salesforce-q1/ba-p/319819) 추가 정보

## 공지 {#announcements}

* **Marketo Sky 사용 중단**: 3월에는 차세대 사용자 경험을 제공하기 위해 리소스를 집중하므로 Marketo Sky을 더 이상 사용할 수 없습니다. 현재 Marketo Sky 전용 기능에 대한 액세스를 유지하기 위해 Adobe에서는 자산 만료 및 스마트 캠페인 우선 순위 무시 를 3월에 주요 경험으로 도입할 예정입니다. [여기를 클릭하십시오.](https://nation.marketo.com/t5/the-next-generation-experience/marketo-sky-deprecation-notice/ba-p/320115#M33) 추가 정보

* **양식 끝점 사용 중단**: leadCapture/save2 종단점에 대해 지원되지 않는 프로그래밍 방식 양식 POST가 Marketo Engage 양식에 의해 거부됩니다. [여기를 클릭하십시오.](https://nation.marketo.com/t5/product-documents/updated-october-2021-upcoming-changes-to-the-marketo-engage-form/ta-p/306631) 추가 정보

* **사용자 초대 대화 상자에서 로그인**: 3월에는 옵션 기능인 &quot;사용자 초대 대화 상자에서 로그인&quot;이 더 이상 사용되지 않습니다. 기능 &quot;사용자 초대 대화 상자에 로그인&quot; 기능은 예정된 Adobe Identity Management 시스템 통합에 필요하고 모든 구독에서 2021년 8월에 활성화되었던 범용 ID 기능에 의해 재정의됩니다. 사용 중단 결과 Marketo Engage은 구독 내에 이메일 주소당 연결할 사용자를 한 명만 적용합니다.

**Marketo Engage 도메인 - Sales Insight 구성**: SSL 인증서가 프로비저닝되지 않은 Marketo Engage 도메인 및 https://의 경우 SSL 핸드셰이크 오류로 인해 호출이 실패합니다. 따라서 이러한 도메인은 사라질 것입니다. 따라서 이러한 도메인을 가리키는 이전 구성이 있는 Sales Insight 사용자는 Lead, Contact, Account, Opportunity Panels 또는 Marketo Global 페이지에서 시스템 콜아웃 오류가 발생할 수 있습니다. 을(를) 업데이트하는 것이 좋습니다 [Marketo Engage 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md) Salesforce에서 이 오류가 발생한 경우 문서의 &quot;Marketo Sales Insight Config&quot; 섹션에 강조 표시된 Marketo Engage 자격 증명만 업데이트해야 합니다.

**_제품 릴리스 웨비나_**

[2022년 1월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_January_Release_Webinar_DemandPage.html)
