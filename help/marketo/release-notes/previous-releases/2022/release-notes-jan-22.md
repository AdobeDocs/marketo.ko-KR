---
description: 릴리스 노트 - 2022년 1월 - Marketo 설명서 - 제품 설명서
title: 릴리스 정보 - 2022년 1월
exl-id: babc4e7f-3f11-4883-80c6-58e69c3e1ab4
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '884'
ht-degree: 3%

---

# 릴리스 노트: 2022년 1월 {#release-notes-jan-22}

다음 기능은 2022년 1월 릴리스에 포함되어 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2022년 1월 21일**&#x200B;에 릴리스되기 시작하며, 이후 몇 주 동안(달리 지정하지 않는 한) 모든 기능의 단계적 롤아웃이 적용됩니다.

## 차세대 경험 {#modern-ux}

* **차세대 경험에서 업데이트된 Screens**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 경험에서 새로 고친 화면을 추가로 제공합니다.

   * [!UICONTROL Design Studio]의 랜딩 페이지 자산 세부 정보
   * [!UICONTROL Marketing Activities]의 랜딩 페이지 자산 세부 정보

## [!DNL Microsoft Dynamics] 통합 {#microsoft-dynamics-integration}

* **다중 선택 Optionset 필드 형식 동기화(일반적으로 사용 가능)**: 보다 세분화된 대상 타깃팅을 위해 스마트 목록 및 스마트 캠페인에서 활용하려면 [!DNL Microsoft Dynamics]에서 다중 선택 Optionset 필드 형식을 동기화하십시오. 예로는 관심 주제/제품, 선호하는 커뮤니케이션 모드 등이 있습니다. 이 새 동기화는 [!DNL Microsoft Dynamics] 버전 9.X(Dynamics 365 Online 포함)에서 사용할 수 있습니다.

* **에 대한[!DNL Microsoft Dynamics 365 Online]**&#x200B;서버 간 인증: 보안을 강화하기 위해 이제 [!DNL Microsoft Dynamics 365 Online]에 대한 비대화형 액세스를 위해 Azure Active Directory에서 Marketo Engage 동기화 사용자의 추가 인증 모드로 S2S(서버 간)를 지원합니다. 모든 인증 및 로그인이 OAuth(클라이언트 ID 및 클라이언트 암호만)를 기반으로 하므로 다단계 인증을 사용할 수 있습니다.

>[!NOTE]
>
>S2S 모드는 라이센스 사용자가 아닌 애플리케이션 사용자를 기반으로 하므로 추가 라이센스 사용이 절약됩니다.

## 관리 {#administration}

* **[양식 유효성 검사 규칙](/help/marketo/product-docs/administration/settings/global-form-validation-rules.md)**: 문제가 있거나 원치 않는 전자 메일 도메인이 Marketo Engage 양식을 제출하지 않도록 차단하는 기능을 사용하여 데이터베이스의 상태를 유지합니다. 관리자는 전역 양식 유효성 검사 패널을 사용하여 양식에 대해 사전 정의된 차단 목록 목록을 정의하거나 자유 소비자 도메인이 차단되도록 할 수 있습니다.

* **[랜딩 페이지 헤더 보안](/help/marketo/product-docs/administration/settings/landing-page-headers.md)**: 관리자는 강력한 보안 요구 사항을 적용하기 위해 랜딩 페이지 도메인에서 엄격한 전송 보안 및 X-Frame 옵션 헤더를 관리할 수 있습니다.

**_분기 내내 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## AEP Marketo Engage Destination Connector - 새로운 리드 만들기 {#aep-marketo-engage-destination-connector}

Adobe Experience Platform(AEP)도 사용하는 Marketo Engage 고객은 AEP 대상 커넥터를 통해 AEP에서 Marketo Engage으로 net-new person 레코드를 푸시할 수 있으므로 데이터베이스를 극대화할 수 있습니다. AEP에서 Marketo Engage으로 대상 세그먼트를 보낼 때 Marketo Engage 데이터베이스 [에 없는 세그먼트 내의 사람은 자동으로 추가할 수 있습니다](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/push-an-adobe-experience-platform-segment-to-a-marketo-static-list.md).

## [!DNL Sales Insight] {#sales-insight}

![(별)](assets/yellow-star.png)

**[!DNL Sales Insight]CRM용 [!DNL Salesforce]**

* **에 대한[!UICONTROL Best Bets]**&#x200B;새 형식 열: [!UICONTROL Best Bets] 페이지의 리드와 연락처를 구별하기 위해 &quot;Type&quot;이라는 레이블이 지정된 새 열을 사용하여 판매자가 더 빠른 통찰력을 얻습니다.

* **[!DNL Salesforce]Platform API 업데이트**: [!DNL Salesforce]에서 [!DNL Salesforce] Platform API 버전 21.0에서 30.0을 중단하는 것에 대한 응답으로 [!DNL Sales Insight] 패키지가 최신 API로 업데이트되었습니다.

* **브랜딩 업데이트됨**: 모든 [!DNL Sales Insight] 페이지가 Adobe 브랜딩에 맞게 업데이트되고 있습니다.

**[!DNL Sales Insight]에 대한[!DNL Microsoft Dynamics]**

* **업데이트된 계정 레이아웃**: 판매자는 전자 메일 활동, 웹 활동, 관심 있는 순간, 계정 내 모든 연락처에 대한 점수 변경과 같은 상위 활동에 대한 집단 보기를 얻을 수 있습니다.

## [!DNL Sales Connect] {#sales-connect}

![(별)](assets/yellow-star.png)

* **통화 결과 및 이유**: 완전히 사용자 지정 가능한 새로운 통화 결과 및 통화 이유 옵션을 통해 영업 팀의 아웃바운드 노력을 더 자세히 이해하고 추적합니다. 이러한 새로운 필드 외에도 판매자가 호출하는 동안 통화 이유 및 결과 선택을 적용하는 새로운 거버넌스, 통화 이유 및 결과를 활성화 또는 비활성화하는 새로운 거버넌스, [!DNL Salesforce]에 데이터를 로깅하는 새로운 통화 이유 및 통화 결과 [!DNL Salesforce] 활동 사용자 지정 필드를 도입합니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/product-blogs/sales-connect-enhancements-to-call-outcomes-q1-22-release/ba-p/319812).

* **[!DNL Salesforce]활동 세부 정보 사용자 지정**: 판매 활동이 [!DNL Salesforce]에서 [!DNL Salesforce]&#x200B;(으)로 기록될 때 [!DNL Salesforce] 작업 제목 필드에 추가되는 정보를 사용자 지정하여 [!DNL Sales Connect]에서 더 많은 판매 활동 및 작업 데이터를 캡처합니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/product-blogs/sales-connect-enahncements-to-activity-logging-to-salesforce-q1/ba-p/319819).

## 공지 {#announcements}

* **Marketo Sky 사용 중단**: 차세대 사용자 환경을 제공하기 위해 리소스를 집중하기 때문에 3월에는 Marketo Sky을 더 이상 사용할 수 없습니다. 현재 Marketo Sky에만 적용되는 기능에 대한 액세스를 유지하기 위한 노력으로 3월에 자산 만료 및 스마트 캠페인 우선 순위 재정의를 주요 경험으로 가져올 예정입니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33).

* **양식 끝점 사용 중단**: leadCapture/save2 끝점에 대해 지원되지 않는 프로그래밍 방식의 양식 POST가 Marketo Engage 양식에 의해 거부됩니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/product-documents/updated-october-2021-upcoming-changes-to-the-marketo-engage-form/ta-p/306631).

* **사용자 초대 대화 상자에 로그인**: 3월부터 선택적 기능인 기존 &quot;사용자 초대 대화 상자에 로그인&quot;이 더 이상 사용되지 않습니다. 기능 &quot;[!UICONTROL Login in Invite User Dialog]&quot; 기능은 향후 Adobe Identity Management 시스템 통합에 필요한 유니버설 ID 기능으로 대체되었으며 모든 구독에서 2021년 8월에 활성화되었습니다. 사용 중단으로 인해 Marketo Engage에서는 구독 내 이메일 주소당 하나의 사용자만 연결하도록 강제합니다.

**Marketo Engage 도메인 - [!DNL Sales Insight] 구성**: SSL 인증서가 프로비저닝되고 https://이 없는 Marketo Engage 도메인의 경우 SSL 핸드셰이크 오류로 인해 호출이 실패합니다. 따라서 이러한 도메인은 사용되지 않습니다. 따라서 이러한 도메인을 가리키는 이전 구성을 가진 [!DNL Sales Insight]명의 사용자에게 리드, 연락처, 계정, 영업 기회 패널 또는 Marketo 글로벌 페이지에서 시스템 호출 오류가 발생할 수 있습니다. 이 오류가 발생하면 [에서 ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)Marketo Engage 구성[!DNL Salesforce]을 업데이트하는 것이 좋습니다. 문서의 &quot;[!DNL Marketo Sales Insight] 구성&quot; 섹션에서 강조 표시된 Marketo Engage 자격 증명만 업데이트하면 됩니다.

**_제품 릴리스 웨비나_**

[2022년 1월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_January_Release_Webinar_DemandPage.html)
