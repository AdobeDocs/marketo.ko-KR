---
unique-page-id: 17727823
description: 릴리스 노트 - 19년 겨울 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2019년 겨울
exl-id: 0cb3b3a1-472e-41d4-84f4-47f06e65017c
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '1050'
ht-degree: 0%

---

# 릴리스 노트: 2019년 겨울 {#release-notes-winter}

다음 기능은 19년 겨울 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

가능한 경우 제목 링크를 클릭하여 각 기능에 대한 자세한 문서를 확인하십시오.

>[!NOTE]
>
>이제 [!DNL Facebook]에 사용자 지정 대상 통합을 활용하려면 Business Manager 계정이 필요합니다. [!DNL Facebook] LaunchPoint 서비스 *must*&#x200B;이(가) Business Manager 계정에 연결되어 있거나 **2019년 1월 14일 이후에는 더 이상 통합이 작동하지 않습니다**. Business Manager 계정을 설정하려면 [[!DNL Facebook] 도움말](https://www.facebook.com/business/help/1710077379203657)을 참조하세요.

>[!NOTE]
>
>Microsoft에서 모든 온라인 고객을 최신 버전의 [!DNL Microsoft Dynamics]&#x200B;(으)로 업그레이드하도록 추진하고 있습니다. Marketo 인스턴스를 [!DNL Dynamics Online]과(와) 통합하는 경우 통합이 계속 작동하도록 하려면 [2019년 1월 31일](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md) 전에 **최신 버전의 Marketo 솔루션으로 업그레이드**&#x200B;해야 합니다.

>[!NOTE]
>
>Marketo은 GoToWebinar에 대한 OAuth 버전을 1.0에서 2.0으로 업그레이드하는 중입니다. OAuth 1.0에 대한 지원은 2019년 1월에 중단됩니다. GoToWebinar 고객의 경우 통합이 계속 작동하도록 하려면 **2019년 1월 31일**&#x200B;까지 LaunchPoint(관리 영역)를 통해 로그인을 다시 인증해야 합니다. 자세한 내용은 [커뮤니티 페이지](https://nation.marketo.com/docs/DOC-6739-gotowebinar-authentication-change-take-action-before-1312019)를 참조하세요.

## 핵심 플랫폼 개선 사항 {#core-platform-enhancements}

**[Marketo 이메일용 이메일 CC](/help/marketo/product-docs/email-marketing/general/email-cc.md)**

Marketo을 통해 전송된 이메일에 수신자당 최대 5개의 CC 주소를 포함합니다.

**API**

* **자산 API에 대한 다중 브랜딩 도메인 지원:** 자산을 승인하고 복제하면 API 및 UI 내에서 동일한 결과가 생성됩니다.
* **자산 API에 대한 이메일 CC 지원**: API를 통해 이메일을 복제, 승인 및 처리하는 사용자는 UI 설정과 동등성을 유지합니다.

**[[!DNL Munchkin] v155(Beta)](https://developers.marketo.com/javascript-api/lead-tracking/configuration/)**

* **API 전용 모드**: 이제 사용자는 Marketo의 자동 추적에 의존하는 대신 웹 페이지 방문을 기록하려는 경우 단일 페이지 웹 앱에서 명시적으로 호출하도록 허용하여 데이터베이스의 구성원을 추적할 시기와 방법을 결정할 수 있습니다.
* **옵트아웃 관리**: 옵트아웃 쿠키 도메인을 [!DNL Munchkin] 추적 쿠키 도메인과 일치시켜 손쉽게 옵트아웃을 관리할 수 있습니다.
* **도메인 수준 의사 결정 매개 변수**: 두 글자로 된 도메인(즉, &quot; [website.io](https://website.io)&quot;)은 추가 설정 요구 사항 없이 Marketo에서 자동으로 추적됩니다.

## Marketo Sales Engage {#marketo-sales-engage}

* **[!DNL Salesforce]사용자 지정 프로필**: 이제 Sales Engage에서 무제한 사용자 지정 프로필을 지원합니다.

* **[!DNL Salesforce]사용자 지정**: 중요하지 않은 사용자 지정 활동 필드를 제거하면 사용자가 CRM 플랫폼에 Sales Engage를 보다 효율적으로 설정할 수 있습니다.
* **이메일 서비스**: [!DNL Microsoft Outlook]에 연결하여(Office365 또는 [이메일 연결] 탭을 통해 온프레미스) 게재 기능 및 개선된 회신 추적, 예약된 이메일 기능, 대량 이메일 기능을 활용하세요.
* **새 관리자 설정**: Sales Engage 인스턴스를 최적화하기 위해 두 개의 관리 페이지가 추가되었습니다.

   * *팀 관리*&#x200B;에서는 관리자가 구독 및 팀을 편집할 수 있도록 하여 원활한 계정 설정 프로세스를 지원합니다.
   * *Salesforce 관리 설정*&#x200B;을 통해 팀은 이전보다 더 빠르고 쉽게 SFDC 동기화를 설정할 수 있습니다.

* **용[!DNL Windows]** OWA 플러그 인: 단일 추가 기능을 사용하면 Outlook에서 Live Feed를 사용할 수 있는 기능을 제공하는 Sales Engage에서 모든 [!DNL Windows Office365] 클라이언트가 지원됩니다. 새 플러그인은 Microsoft 스토어에서 사용할 수 있습니다.
* **활동 푸셔**: 실시간 마케팅 인사이트를 활용하려면 Sales Engage를 핵심 Marketo 플랫폼과 동기화하십시오.

## [!DNL Marketo Sky] {#marketo-sky}

>[!NOTE]
>
>[!DNL Marketo Sky] 릴리스는 더 자주 발생합니다. 다음 기능 및 개선 사항은 4분기 말/1분기 초에 릴리스될 예정입니다. 자세한 내용 및 업데이트는 [Sky 설명서](https://help.marketo.com/)를 참조하세요.

* **선택적 기본 경험**: 관리자가 액세스 권한을 제공한 경우 Marketo 사용자는 [!DNL Marketo Sky]을(를) 기본 경험으로 설정할 수 있습니다.

* **내 Marketo 이미지 다시 만들기**: 중요한 정보, 알림 및 가장 자주 방문하는 영역에 대한 링크를 제공하는 위젯을 추가하여 환경을 사용자 지정합니다.

* **Design Studio 목록 보기 및 세부 정보 페이지**: 전자 메일, 랜딩 페이지 및 양식에 대한 필터링 및 검색 가능한 목록 보기를 통해 조직 및 정확도를 높일 수 있습니다. 에셋 세부 사항 페이지는 에셋이 사용되는 프로그램, 사용 중인 스니펫 수 등을 포함하여 각 에셋에 대한 주요 정보를 제공합니다.

* **전역 검색**: 이제 Marketo은 플랫폼 전체에서 더 빠르고 강력한 전역 검색 기능을 제공합니다. 이제 검색 쿼리는 액세스 가능한 모든 작업 영역에서 실행되며 에셋(활성 및 보관된 에셋), 레이블, 캠페인 및 프로그램을 검색할 수 있습니다. 검색 결과는 오버레이를 통해 제공되며 각 결과에는 에셋이 있는 위치를 지정하는 파일 위치 추적 정보가 포함됩니다.

* **향상된 사용자 인터페이스**: 새 아이콘, 모델, 단추 및 새 색상 팔레트를 추가하여 브랜드 새로 고침을 반영하고 [!DNL Marketo Sky]을(를) 더욱 멋지고 기능적으로 만듭니다.

* **이메일 프로그램 유용성 개선 사항**: 클래식 Marketo 리드 관리 플랫폼과 새로운 [!DNL Marketo Sky] 경험 간의 이메일 프로그램 기능 패리티를 향해 계속 나아가고 있습니다.
* **Event-With-Webinar 프로그램**: Event-With-Webinar 프로그램은 이제 [!DNL Marketo Sky]에서 사용할 수 있습니다(참고: 이 릴리스에서는 시간이 지남에 따라 더 많은 통합이 설정되며 GoToWebinar만 지원됩니다).

## Account-Based Marketing {#account-based-marketing}

**[ABM 사용자 기반 세분화 및 필터링](/help/marketo/product-docs/target-account-management/using-personas.md)**

명명 계정 내에서 특정 개인에 대한 ABM 캠페인을 개인화합니다. ABM 성향 기능은 잠재 고객 세분화를 기반으로 기본 직책을 만들고 추가 성향 세분화를 구성할 수 있습니다.

## Analytics {#analytics}

**[!DNL Bizible]**

* **사용자 지정 계산 필드**: [!DNL Bizible] 특성을 사용하여 대시보드 보고 및 세분화에 사용할 수 있는 사용자 지정 필드를 만드십시오.

* **SOC II Type II Certification**: 새로운 보안 및 개인 정보 보호 인증은 올해 초부터 Type I 인증을 기반으로 구축됩니다.

## [!DNL Web Personalization] {#web-personalization}

**[계정 설정에서 하위 도메인 추가](/help/marketo/product-docs/web-personalization/getting-started/workspaces-in-web-personalization.md)**

이제 도메인과 하위 도메인을 보다 효율적으로 관리하기 위해 사용자는 하위 도메인을 RTP 계정 설정에 추가할 수 있습니다.

## Marketo Mobile Engagement (MME) {#marketo-mobile-engagement-mme}

**Android용 MME 소프트웨어 개발 키트(SDK)를 업데이트했습니다**

보다 유연하고 새로운 엔지니어링 기능이 포함된 보다 현대적이고 안정적이며 확장 가능한 프레임워크로 Android용 SDK을 업데이트했습니다. 이제 Android 앱 개발자는 이 새로운 SDK에서 Google의 [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/)&#x200B;(FCM)을 직접 사용할 수 있습니다.

* [개발자 지침](https://developers.marketo.com/mobile/installation/#android_adding_fcm_to_your_application)
* [개발자 FAQ](https://developers.marketo.com/mobile/installation/#android_fcm_faq)

>[!NOTE]
>
>앱 개발자는 **2019년 3월 31일 이전에 새 버전으로 업데이트해야**&#x200B;합니다. 2019년 3월 31일까지 SDK을 업데이트하지 않으면 이 날짜 이후에 앱을 다운로드하는 모든 새 사용자는 최신 버전의 SDK으로 업데이트할 때까지 푸시 알림을 받을 수 없습니다. SDK 업데이트에서는 현재 모바일 앱 사용자가 새 버전의 앱을 다시 다운로드할 필요가 없습니다.

## 추가 업데이트 {#additional-updates}

**확장 가능한 웨비나 플랫폼**

제품 릴리스 외에도 당사의 파트너 팀은 웨비나 공급자가 Marketo과의 자체 통합을 구축하고 유지할 수 있는 새로운 프레임워크를 개발하고 있으므로, 마케터가 선택한 통합을 최대한 활용하는 동시에 솔루션을 업데이트하고 개선할 수 있습니다.

우리는 사업자들과 함께 새로운 플랫폼을 사안별로 배포할 계획이다. 자세한 내용은 [프로그램 세부 정보](https://www.marketo.com/why-marketo/partners/technology/)를 참조하거나 Marketo 담당자에게 문의하세요.
