---
unique-page-id: 17727823
description: 릴리스 노트 - 2019년 겨울 - Marketing Docs - 제품 설명서
title: 릴리스 노트 - 2019년 겨울
translation-type: tm+mt
source-git-commit: dc20aede0894a09e6c0bcd3d1580859b5fecb5f1
workflow-type: tm+mt
source-wordcount: '1112'
ht-degree: 0%

---


# 릴리스 노트:19년 겨울 {#release-notes-winter}

다음 기능은 2019년 겨울 릴리스에 포함되어 있습니다. Marketing Edition에서 기능을 사용할 수 있는지 확인하십시오.

사용 가능한 경우 제목 링크를 클릭하여 각 기능에 대한 세부 집필을 확인하십시오.

>[!NOTE]
>
>이제 Facebook에서 사용자 지정 대상 통합을 활용하려면 Business Manager 계정이 필요합니다. Facebook LaunchPoint 서비스는 Business Manager 계정과 *연결되어 있어야* 합니다. 그렇지 않으면 **통합이 2019년** 1월 14일 이후 더 이상 작동하지 않습니다. Business Manager 계정을 설정하려면 [Facebook 도움말을 참조하십시오](https://www.facebook.com/business/help/1710077379203657).

>[!NOTE]
>
>Microsoft는 모든 온라인 고객에게 최신 버전의 Microsoft Dynamics로 업그레이드를 권장하고 있습니다. Marketing To 인스턴스를 Dynamics Online과 통합하는 경우 통합이 계속 작동하도록 하려면 2019년 [1](../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md) 월 31일 **** 전에 최신 버전의 Marketing To 솔루션으로 업그레이드해야 합니다.

>[!NOTE]
>
>Marketing에서 GoToWebinar의 OAuth 버전을 1.0에서 2.0으로 업그레이드하고 있습니다. OAuth 1.0에 대한 지원은 2019년 1월에 더 이상 필요하지 않습니다. GoToWebinar 고객의 경우 통합이 계속 작동하도록 하려면 LaunchPoint(관리 영역의)를 통해 로그인 **** 을 다시 인증해야 합니다. 자세한 내용은 [커뮤니티 페이지를 참조하십시오](https://nation.marketo.com/docs/DOC-6739-gotowebinar-authentication-change-take-action-before-1312019).

## 향상된 핵심 플랫폼 {#core-platform-enhancements}

** [마케팅 이메일을 위한 이메일 CC](../../product-docs/email-marketing/general/email-cc.md)**

Marketing To를 통해 보낸 이메일에 수신자당 최대 5개의 CC 주소를 포함할 수 있습니다.

**API**

* **자산 API에 대한 다중 브랜딩 도메인 지원:** 에셋을 승인하고 복제하면 API와 UI 내에서 동일한 결과가 생성됩니다.
* **에셋 API에 대한 이메일 CC 지원**:API를 통해 이메일을 복제, 승인 및 처리하는 사용자는 UI 설정과 동등한 상태를 유지합니다.

** [Munchkin v155(베타)](http://developers.marketo.com/javascript-api/lead-tracking/configuration/)**

* **API 전용 모드**:이제 사용자는 단일 페이지 웹 앱이 웹 페이지 방문을 기록할 때 Marketing의 자동 추적에 의존하지 않고 명시적으로 호출하도록 함으로써 데이터베이스의 구성원을 추적하는 시기와 방법을 결정할 수 있습니다.
* **옵트아웃 관리**:옵트아웃 쿠키 도메인을 Munchkin 추적 쿠키 도메인과 일치시켜 옵트아웃을 손쉽게 관리할 수 있습니다.
* **도메인 수준 데시더 매개 변수**:두 문자 도메인(예:&quot; [website.io](http://website.io)&quot;)는 추가 설정 요구 사항 없이 Marketing To에서 자동으로 추적됩니다.

## Marketing To Sales Engage {#marketo-sales-engage}

* **Salesforce 사용자 지정 프로필**:이제 Sales Engage는 제한 없는 맞춤형 프로필을 지원합니다.

* **Salesforce 맞춤화**:사용자는 중요한 사용자 지정 활동 필드를 제거하여 CRM 플랫폼에서 세일즈 참여를 보다 효율적으로 설정할 수 있습니다.
* **이메일 서비스**:Microsoft Outlook(Office365 또는 이메일 연결 탭을 통해 온프레미스)에 연결하여 향상된 응답 추적, 예약된 이메일 기능 및 벌크 이메일 기능을 통해 더 나은 전달을 경험할 수 있습니다.
* **새 관리 설정**:Sales Engage 인스턴스를 최적화하기 위해 두 개의 관리 페이지가 추가되었습니다.

   * *팀 관리는* 관리자가 구독 및 팀을 편집할 수 있도록 함으로써 원활한 계정 설정 프로세스를 지원합니다.
   * *Salesforce 관리 설정을* 사용하면 팀은 SFDC 동기화를 이전보다 빠르고 손쉽게 설정할 수 있습니다.

* **OWA Plugin for Windows**:단일 추가 기능을 사용하면 모든 Windows Office 365 클라이언트가 Sales Engage에서 지원되므로 Outlook에서 라이브 피드를 사용할 수 있습니다. 새 플러그인은 Microsoft Store에서 사용할 수 있습니다.
* **활동**:세일즈 동기화 핵심 마케팅 플랫폼에 연결하여 실시간 마케팅 통찰력을 활용할 수 있습니다.

## Marketo Sky {#marketo-sky}

>[!NOTE]
>
>Marketo Sky 릴리스는 빈번한 케이더에서 발생합니다. 다음 기능 및 개선 사항이 4분기 말/1분기 초에 릴리스될 예정입니다. 자세한 내용 및 업데이트를 살펴보려면 [Sky 설명서를 참조하십시오](https://help.marketo.com/hc/en-us/articles/360012858573).

* **선택적 기본 경험**:Marketing 사용자가 관리자가 액세스 권한을 제공한 경우 Marketo Sky을 기본 경험으로 설정할 수 있습니다.

* **마케팅 혁신**:중요한 정보, 알림 및 가장 자주 방문하는 영역에 대한 링크를 제공하는 위젯을 추가하여 경험을 맞춤화할 수 있습니다.

* **디자인 스튜디오 목록 보기 및 세부 사항 페이지**:이메일, 랜딩 페이지 및 양식의 필터링 및 검색 가능한 목록 보기를 통해 조직과 정확도를 높일 수 있습니다. 자산 세부 사항 페이지는 자산을 사용하는 프로그램, 사용 중인 코드 조각 등을 비롯하여 각 자산에 대한 주요 정보를 제공합니다.

* **전역 검색**:이제 Marketing To는 플랫폼 전반에서 더욱 빠르고 강력한 글로벌 검색 기능을 제공합니다. 이제 액세스 가능한 모든 작업 영역에서 검색 쿼리가 실행되고 자산(활성 및 보관 모두), 레이블, 캠페인 및 프로그램을 검색할 수 있습니다. 검색 결과는 오버레이를 통해 제공되며 각 결과에는 자산의 수명을 지정하는 파일 위치 추적이 포함됩니다.

* **향상된 사용자 인터페이스**:새로운 아이콘, 모듈 및 버튼과 새로운 색상 팔레트를 추가하여 브랜드를 새로 고치고 Marketo Sky을 더욱 멋지고 실용적으로 만들 수 있습니다.

* **이메일 프로그램 유용성 개선**:기존의 Marketing to Lead Management 플랫폼과 새로운 Marketo Sky 경험 간에 이메일 프로그램 기능의 동등한 위치에 머물러 있습니다.
* **웨비나 이벤트 관련 프로그램**:이제 Marketo Sky에서 이벤트-웨비나 프로그램을 사용할 수 있습니다(참고:이 릴리스에서는 GoToWebinar만 지원되며, 시간이 지남에 따라 추가로 통합됩니다.)

## 계정 기반 마케팅 {#account-based-marketing}

** [ABM 페르소나 기반의 세그멘테이션 및 필터링](../../product-docs/account-based-marketing/using-personas.md)**

지정된 계정 내에서 특정 개인에 맞는 ABM 캠페인을 개인화할 수 있습니다. ABM 페르소나 기능은 리드 세그멘테이션을 기반으로 기본 작업 제목을 만들고 추가 페르소나 세그먼트를 구성할 수 있도록 합니다.

## 분석 {#analytics}

**비즈블**

* **사용자 지정 계산된 필드**:대시보드 보고 및 세그멘테이션에 사용할 수 있는 사용자 지정 필드를 작성하려면 Bizible 속성을 사용하십시오.

* **SOC II 유형 인증**:새로운 보안 및 개인 정보 보호 인증은 올해 초부터 제1종 인증을 기반으로 구축되었습니다.

## 웹 개인화 {#web-personalization}

**[계정 설정에서 하위 도메인 추가](/help/marketo/product-docs/web-personalization/getting-started/workspaces-in-web-personalization.md)**

이제 도메인과 하위 도메인을 보다 효율적으로 관리하기 위해 사용자는 RTP 계정 설정에 하위 도메인을 추가할 수 있습니다.

## MME(Marketing To Mobile Engagement) {#marketo-mobile-engagement-mme}

**Android용 MME SDK(Software Development Kit) 업데이트**

Android용 SDK가 유연성과 새로운 엔지니어링 기능이 포함된 보다 현대적이고 안정적이며 확장 가능한 프레임워크로 업데이트되었습니다. 이제 Android 앱 개발자는 이 새로운 SDK와 함께 Google의 [Firebase Cloud Messaging](http://firebase.google.com/docs/cloud-messaging/) (FCM)을 직접 사용할 수 있습니다.

* [개발자 지침](http://developers.marketo.com/mobile/installation/#android_adding_fcm_to_your_application)
* [개발자 FAQ](http://developers.marketo.com/mobile/installation/#android_fcm_faq)

>[!NOTE]
>
>앱 개발자는 2019년 3월 31일 이전에 새로운 버전으로 업데이트해야 **합니다** . 2019년 3월 31일까지 SDK를 업데이트하지 않는 경우, 이 날짜 이후에 앱을 다운로드하는 새로운 사용자는 최신 버전의 SDK로 업데이트하기 전까지 푸시 알림을 받을 수 없습니다. SDK 업데이트는 현 기존 모바일 앱 사용자가 새로운 버전의 앱을 다시 다운로드하지 않아도 됩니다.

## 추가 업데이트 {#additional-updates}

**확장 가능한 웨비나 플랫폼**

Adobe의 제품 출시 외에도 Adobe 파트너 팀은 웨비나 제공업체가 Marketing To와의 고유한 통합을 구축하여 유지 관리할 수 있는 새로운 프레임워크를 개발하고 있으므로 마케터가 선택한 통합 기능을 최대한 활용할 수 있도록 솔루션을 업데이트 및 향상시킬 수 있습니다.

Adobe는 사례별로 제공업체와 새로운 플랫폼을 선보일 계획입니다. 자세한 내용은 [프로그램 세부](https://www.marketo.com/why-marketo/partners/technology/) 사항을 참조하거나 Marketing Cloud 담당자에게 문의하십시오.
