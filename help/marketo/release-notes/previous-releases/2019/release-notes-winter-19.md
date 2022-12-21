---
unique-page-id: 17727823
description: 릴리스 노트 - 겨울 '19 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2019년 겨울
exl-id: 0cb3b3a1-472e-41d4-84f4-47f06e65017c
source-git-commit: 74effe9f8078f8d71e6de01d6e737ddc86978abb
workflow-type: tm+mt
source-wordcount: '1109'
ht-degree: 0%

---

# 릴리스 노트: 19년 겨울 {#release-notes-winter}

다음 기능은 2019년 겨울 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo 버전을 확인하십시오.

사용 가능한 경우 제목 링크를 클릭하여 각 기능에 대한 세부 문서를 확인하십시오.

>[!NOTE]
>
>이제 사용자 지정 대상 통합을 활용하려면 facebook에 Business Manager 계정이 필요합니다. facebook LaunchPoint 서비스 *반드시* Business Manager 계정 또는 **2019년 1월 14일 이후에는 통합이 더 이상 작동하지 않습니다**. Business Manager 계정을 설정하려면 다음을 참조하십시오. [Facebook 도움말](https://www.facebook.com/business/help/1710077379203657).

>[!NOTE]
>
>Microsoft은 모든 온라인 고객에게 최신 버전의 Microsoft Dynamics로 업그레이드하도록 촉구하고 있습니다. Marketo 인스턴스를 Dynamics Online과 통합하는 경우 다음을 수행해야 합니다 [최신 버전의 Marketo 솔루션으로 업그레이드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md) 이전 **2019년 1월 31일** 통합이 계속 작동하도록 하려면 다음을 수행하십시오.

>[!NOTE]
>
>Marketo은 GoToWebinar용 OAuth 버전을 1.0에서 2.0으로 업그레이드하고 있습니다. OAuth 1.0에 대한 지원은 2019년 1월에 더 이상 사용되지 않습니다. GoToWebinar 고객인 경우, 다음을 통해 LaunchPoint(관리 영역)를 통해 로그인을 다시 인증해야 합니다. **2019년 1월 31일** 통합이 계속 작동하도록 하려면 다음을 수행하십시오. 자세한 내용은 [커뮤니티 페이지](https://nation.marketo.com/docs/DOC-6739-gotowebinar-authentication-change-take-action-before-1312019).

## 핵심 플랫폼 개선 사항 {#core-platform-enhancements}

**[Marketo 이메일용 이메일 CC](/help/marketo/product-docs/email-marketing/general/email-cc.md)**

Marketo을 통해 전송된 이메일에 수신자당 최대 5개의 CC 주소를 포함합니다.

**API**

* **자산 API에 대한 다중 브랜딩 도메인 지원:** 자산을 승인하고 복제하면 API 및 UI 내에서 동일한 결과가 생성됩니다.
* **자산 API에 대한 이메일 CC 지원**: API를 통해 이메일을 복제, 승인 및 처리하는 사용자는 UI 설정과 패리티를 유지합니다.

**[Munchkin v155(베타)](https://developers.marketo.com/javascript-api/lead-tracking/configuration/)**

* **API 전용 모드**: 이제 사용자는 Marketo의 자동 추적에 의존하지 않고 단일 페이지 웹 앱이 웹 페이지 방문을 기록하려는 경우 명시적으로 호출하도록 함으로써 데이터베이스의 구성원을 추적할 시점과 방법을 결정할 수 있습니다.
* **옵트아웃 관리**: 옵트아웃 쿠키 도메인을 Munchkin 추적 쿠키 도메인과 일치시켜 옵트아웃을 쉽게 관리합니다.
* **도메인 수준 디사이더 매개 변수**: 두 문자로 이루어진 도메인(예: &quot; [website.io](https://website.io)추가 설정 요구 사항 없이 Marketo에서 이 자동으로 추적됩니다.

## Marketo 영업 참여 {#marketo-sales-engage}

* **Salesforce 사용자 지정 프로필**: Sales Engage 는 이제 무제한 사용자 지정 프로필을 지원합니다.

* **Salesforce 사용자 지정**: 중요하지 않은 사용자 지정 활동 필드를 제거하여 CRM 플랫폼에서 보다 효율적으로 Sales Engage 를 설정할 수 있습니다.
* **이메일 서비스**: Microsoft Outlook(Office365 또는 전자 메일 연결 탭을 통해 온프레미스)에 연결하여 보다 나은 게재 기능과 향상된 회신 추적, 예약된 전자 메일 기능 및 대량 전자 메일 기능을 사용할 수 있습니다.
* **새 관리 설정**: Sales Engage 인스턴스를 최적화하기 위해 두 개의 관리 페이지가 추가되었습니다

   * _팀 관리_ 관리자가 구독 및 팀을 편집할 수 있도록 하여 원활한 계정 설정 프로세스를 지원합니다.
   * _Salesforce 관리 설정_ 는 팀이 이전보다 빠르고 쉽게 SFDC 동기화를 설정할 수 있도록 지원합니다.

* **Windows용 OWA 플러그인**: 단일 추가 기능을 통해 모든 Windows Office365 클라이언트는 Sales Engage에서 지원되며 Outlook에서 라이브 피드를 사용할 수 있습니다. 새 플러그인은 Microsoft 스토어에서 사용할 수 있습니다.
* **활동 푸시**: Sales Engage 를 핵심 Marketo 플랫폼에 동기화하여 실시간 마케팅 통찰력을 활용할 수 있습니다.

## Marketo Sky {#marketo-sky}

>[!NOTE]
>
>Marketo Sky 릴리스는 더 빈번한 케이던스에 발생합니다. 2010년 4분기/1분기 후반에 다음 기능과 향상된 기능이 출시될 예정입니다. 자세한 내용 및 업데이트를 보려면 [Sky 설명서](https://help.marketo.com/).

* **선택 사항인 기본 경험**: Marketo 사용자는 관리자가 Marketo Sky에게 액세스 권한을 제공한 경우를 기본 경험으로 설정할 수 있습니다.

* **My Marketo을 다시 상상함**: 중요한 정보, 알림 및 가장 자주 방문하는 영역에 대한 링크를 제공하는 위젯을 추가하여 경험을 사용자 지정합니다.

* **Design Studio 목록 보기 및 세부 정보 페이지**: 이메일, 랜딩 페이지 및 양식의 필터링 및 검색 가능한 목록 보기를 사용하여 조직 및 정확도를 높일 수 있습니다. 자산 세부 사항 페이지에서는 자산이 사용되는 프로그램, 사용 중인 코드 조각 수 등을 포함하여 각 자산에 대한 주요 정보를 제공합니다.

* **전역 검색**: 이제 Marketo은 플랫폼 전체에서 더 빠르고 강력한 전역 검색 기능을 제공합니다. 이제 검색 쿼리는 액세스 가능한 모든 작업 공간에서 실행되며 자산(활성 및 보관된 항목), 레이블, 캠페인 및 프로그램을 검색할 수 있습니다. 검색 결과는 오버레이를 통해 제공되며, 각 결과에는 자산이 있는 위치를 지정하는 해당 파일 위치 추적이 포함됩니다.

* **향상된 사용자 인터페이스**: 브랜드 새로 고침을 반영하며 Marketo Sky을 더욱 놀랍고 기능적으로 만들기 위한 새로운 색상 팔레트와 함께 새로운 아이콘, 모델 및 단추.

* **이메일 프로그램 유용성 개선 사항**: Adobe는 기존의 Marketo 리드 관리 플랫폼과 새로운 Marketo Sky 환경 간에 이메일 프로그램 기능의 패리티를 계속 향해 나아가고 있습니다.
* **Event-With-Webinar 프로그램**: 이제 Marketo Sky에서 이벤트-웨비나 프로그램을 사용할 수 있습니다(참고: 이 릴리스에서는 GoToWebinar만 지원되며, 시간이 지남에 따라 추가적인 통합이 제공됩니다.)

## Account-Based Marketing {#account-based-marketing}

**[ABM 성향 기반 세분화 및 필터링](/help/marketo/product-docs/target-account-management/using-personas.md)**

명명된 계정 내에서 특정 성향에 대한 ABM 캠페인을 개인화합니다. ABM 성향 기능은 리드 세그멘테이션을 기반으로 기본 작업 제목을 만들고 추가 성향 세그멘테이션을 구성할 수 있도록 해줍니다.

## 분석 {#analytics}

**Bizible**

* **사용자 지정 계산된 필드**: 대시보드 보고 및 세그멘테이션에 사용할 수 있는 사용자 지정 필드를 만들려면 Bizible 속성을 사용하십시오.

* **SOC II 타입 II 인증**: 올해 초부터 Type I 인증을 바탕으로 새로운 보안 및 개인 정보 보호 인증을 구축했습니다.

## 웹 개인화 {#web-personalization}

**[계정 설정에서 하위 도메인 추가](/help/marketo/product-docs/web-personalization/getting-started/workspaces-in-web-personalization.md)**

이제 도메인과 하위 도메인을 보다 효율적으로 관리하기 위해 사용자가 RTP 계정 설정에 하위 도메인을 추가할 수 있습니다.

## Marketo 모바일 참여(MME) {#marketo-mobile-engagement-mme}

**Android용 MME SDK(소프트웨어 개발 키트) 업데이트**

Android용 SDK를 더 많은 유연성과 새로운 엔지니어링 기능을 포함하는 보다 현대적이고 안정적이며 확장 가능한 프레임워크로 업데이트했습니다. 이제 Android 앱 개발자는 Google을 직접 사용할 수 있습니다 [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/) (FCM) 및 이 새로운 SDK가 포함되어 있습니다.

* [개발자 지침](https://developers.marketo.com/mobile/installation/#android_adding_fcm_to_your_application)
* [개발자 FAQ](https://developers.marketo.com/mobile/installation/#android_fcm_faq)

>[!NOTE]
>
>앱 개발자 **반드시** 2019년 3월 31일 이전에 새 버전으로 업데이트하십시오. 2019년 3월 31일까지 SDK를 업데이트하지 않으면 이 날짜 이후에 앱을 다운로드하는 새로운 사용자는 최신 버전의 SDK로 업데이트할 때까지 푸시 알림을 받을 수 없습니다. SDK 업데이트에서는 현재 기존 모바일 앱 사용자가 앱의 새 버전을 다시 다운로드할 필요가 없습니다.

## 추가 업데이트 {#additional-updates}

**확장 가능한 웨비나 플랫폼**

Adobe의 제품 릴리스 외에도 Adobe의 파트너 팀은 웨비나 공급업체가 Marketo와의 자체 통합을 구축하고 유지할 수 있도록 하는 새로운 프레임워크를 개발하고 있으므로, 마케터가 선택한 통합을 최대한 활용할 수 있도록 하면서 솔루션을 업데이트하고 향상시키는 데 더 많은 유연성을 제공합니다.

Dell은 케이스 별로 공급자와 함께 새로운 플랫폼을 제공할 계획입니다. 자세한 내용은 [프로그램 세부 사항](https://www.marketo.com/why-marketo/partners/technology/) 또는 Marketo 담당자에게 문의하십시오.
