---
title: "2019"
description: 2019년 - Marketo 문서 - 제품 설명서
feature: Release Information
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
subfeature_v2:
  - id: a1d50dda-6d94-4e16-8c30-5eb7181c4650
  - id: d5c7388a-594e-4d15-9b39-98d6ce479e8b
  - id: de9e3aa9-f002-4fe1-897b-09ee3c55114b
  - id: df8eb12b-4f82-491f-acbb-d74012ca5654
  - id: ffdd6159-0e10-4a57-8021-94e93bab8183
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: bbbea26f-9621-49eb-9ab8-e06fb3bbce8c
  - id: bce87dde-a4ab-44c9-8a18-ad66e4ddb377
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
source-git-commit: 1e70b9383bf3a1cd30715df4379d440c4efb1abd
workflow-type: tm+mt
source-wordcount: 2528
ht-degree: 0%

---

# 2019

## 2019년 겨울 {#winter}

다음 기능은 19년 겨울 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

가능한 경우 제목 링크를 클릭하여 각 기능에 대한 자세한 문서를 확인하십시오.

>[!NOTE]
>
>이제 [!DNL Facebook]에 사용자 지정 대상 통합을 활용하려면 Business Manager 계정이 필요합니다. [!DNL Facebook] LaunchPoint 서비스 *must*&#x200B;이(가) Business Manager 계정에 연결되어 있거나 **2019년 1월 14일 이후에는 더 이상 통합이 작동하지 않습니다**. Business Manager 계정을 설정하려면 [[!DNL Facebook] 도움말](https://www.facebook.com/business/help/1710077379203657)을 참조하세요.

>[!NOTE]
>
>Microsoft에서 모든 온라인 고객을 최신 버전의 [!DNL Microsoft Dynamics]&#x200B;(으)로 업그레이드하도록 추진하고 있습니다. Marketo 인스턴스를 [!DNL Dynamics Online]과(와) 통합하는 경우 통합이 계속 작동하도록 하려면 **2019년 1월 31일** 전에 [최신 버전의 Marketo 솔루션으로 업그레이드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md)해야 합니다.

>[!NOTE]
>
>Marketo은 GoToWebinar에 대한 OAuth 버전을 1.0에서 2.0으로 업그레이드하는 중입니다. OAuth 1.0에 대한 지원은 2019년 1월에 중단됩니다. GoToWebinar 고객의 경우 통합이 계속 작동하도록 하려면 **2019년 1월 31일**&#x200B;까지 LaunchPoint(관리 영역)를 통해 로그인을 다시 인증해야 합니다. 자세한 내용은 [커뮤니티 페이지](https://nation.marketo.com/docs/DOC-6739-gotowebinar-authentication-change-take-action-before-1312019)를 참조하세요.

## 핵심 플랫폼 개선 사항

**[Marketo 이메일용 이메일 CC](/help/marketo/product-docs/email-marketing/general/email-cc.md)**

Marketo을 통해 전송된 이메일에 수신자당 최대 5개의 CC 주소를 포함합니다.

**API**

* **자산 API에 대한 다중 브랜딩 도메인 지원:** 자산을 승인하고 복제하면 API 및 UI 내에서 동일한 결과가 생성됩니다.
* **자산 API에 대한 이메일 CC 지원**: API를 통해 이메일을 복제, 승인 및 처리하는 사용자는 UI 설정과 동등성을 유지합니다.

**[[!DNL Munchkin] v155(Beta)](https://developers.marketo.com/javascript-api/lead-tracking/configuration/)**

* **API 전용 모드**: 이제 사용자는 Marketo의 자동 추적에 의존하는 대신 웹 페이지 방문을 기록하려는 경우 단일 페이지 웹 앱에서 명시적으로 호출하도록 허용하여 데이터베이스의 구성원을 추적할 시기와 방법을 결정할 수 있습니다.
* **옵트아웃 관리**: 옵트아웃 쿠키 도메인을 [!DNL Munchkin] 추적 쿠키 도메인과 일치시켜 손쉽게 옵트아웃을 관리할 수 있습니다.
* **도메인 수준 의사 결정 매개 변수**: 두 글자로 된 도메인(즉, &quot; [website.io](https://website.io)&quot;)은 추가 설정 요구 사항 없이 Marketo에서 자동으로 추적됩니다.

## Marketo Sales Engage

* **[!DNL Salesforce]사용자 지정 프로필**: 이제 Sales Engage에서 무제한 사용자 지정 프로필을 지원합니다.

* **[!DNL Salesforce]사용자 지정**: 중요하지 않은 사용자 지정 활동 필드를 제거하면 사용자가 CRM 플랫폼에 Sales Engage를 보다 효율적으로 설정할 수 있습니다.
* **이메일 서비스**: [!DNL Microsoft Outlook]에 연결하여(Office365 또는 [이메일 연결] 탭을 통해 온프레미스) 게재 기능 및 개선된 회신 추적, 예약된 이메일 기능, 대량 이메일 기능을 활용하세요.
* **새 관리자 설정**: Sales Engage 인스턴스를 최적화하기 위해 두 개의 관리 페이지가 추가되었습니다.

   * *팀 관리*&#x200B;에서는 관리자가 구독 및 팀을 편집할 수 있도록 하여 원활한 계정 설정 프로세스를 지원합니다.
   * *Salesforce 관리 설정*&#x200B;을 통해 팀은 이전보다 더 빠르고 쉽게 SFDC 동기화를 설정할 수 있습니다.

* [!DNL Windows]&#x200B;**용** OWA 플러그 인: 단일 추가 기능을 사용하면 Outlook에서 Live Feed를 사용할 수 있는 기능을 제공하는 Sales Engage에서 모든 [!DNL Windows Office365] 클라이언트가 지원됩니다. 새 플러그인은 Microsoft 스토어에서 사용할 수 있습니다.
* **활동 푸셔**: 실시간 마케팅 인사이트를 활용하려면 Sales Engage를 핵심 Marketo 플랫폼과 동기화하십시오.

## [!DNL Marketo Sky]

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

## Account-Based Marketing

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

보다 유연하고 새로운 엔지니어링 기능을 포함하는 보다 현대적이고 안정적이며 확장 가능한 프레임워크로 Android용 SDK을 업데이트했습니다. 이제 Android 앱 개발자는 이 새로운 SDK에서 Google의 [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging/)&#x200B;(FCM)을 직접 사용할 수 있습니다.

* [개발자 지침](https://developers.marketo.com/mobile/installation/#android_adding_fcm_to_your_application)
* [개발자 FAQ](https://developers.marketo.com/mobile/installation/#android_fcm_faq)

>[!NOTE]
>
>앱 개발자는 **2019년 3월 31일 이전에 새 버전으로 업데이트해야**&#x200B;합니다. 2019년 3월 31일까지 SDK을 업데이트하지 않으면 이 날짜 이후에 앱을 다운로드하는 모든 새 사용자는 최신 버전의 SDK으로 업데이트할 때까지 푸시 알림을 받을 수 없습니다. SDK 업데이트에서는 현재 모바일 앱 사용자가 새 버전의 앱을 다시 다운로드할 필요가 없습니다.

## 추가 업데이트 {#additional-updates}

**확장 가능한 웨비나 플랫폼**

제품 릴리스 외에도 당사의 파트너 팀은 웨비나 공급자가 Marketo과의 자체 통합을 구축하고 유지할 수 있는 새로운 프레임워크를 개발하고 있으므로, 마케터가 선택한 통합을 최대한 활용하는 동시에 솔루션을 업데이트하고 개선할 수 있습니다.

우리는 사업자들과 함께 새로운 플랫폼을 사안별로 배포할 계획이다. 자세한 내용은 [프로그램 세부 정보](https://www.marketo.com/why-marketo/partners/technology/)를 참조하거나 Marketo 담당자에게 문의하세요.

## 2019년 봄 {#spring}

2019년 봄 릴리스에는 다음과 같은 기능이 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

가능한 경우 제목 링크를 클릭하여 각 기능에 대한 자세한 문서를 확인하십시오.

***분기별 릴리스_**

다음 기능은 2019년 3월 15일에 릴리스되었습니다.

## 핵심 플랫폼 개선 사항

* **대기자 명단 등록됨:** 대기자 명단 등록에 대한 새 프로그램/이벤트 상태: [대기 중](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md)을(를) 원할 경우 공석이 열릴 때까지 대기자 명단 등록 이는 Marketo Classic의 이벤트 프로그램과 연결된 채널 및 [!DNL Marketo Sky]에 웨비나 프로그램이 있는 이벤트 및 이벤트 모두에 적용됩니다. 대기자 명단에 등록됨은 기본적으로 단계 값이 등록됨과 동일합니다.
* **[사용자 지정 통신 제한](/help/marketo/product-docs/administration/email-setup/enable-communication-limits.md)**: 관리자는 이제 사용자 지정 일별 또는 주별 통신 제한을 설정할 수 있습니다.
* **[스마트 캠페인 자산 API](https://developers.marketo.com/rest-api/assets/smart-campaigns/)**: 업데이트된 날짜 및 ID별로 스마트 캠페인 레코드 검색을 통해 Marketo 외부에서 분석을 보강합니다.
* **전자 메일에 대한 HTTPS 추적 링크:** &quot;추적 링크에 대한 보안 도메인&quot;을 구매한 고객의 경우 브랜드 추적 링크를 전자 메일 내에 HTTPS로 표시할 수 있습니다.
* **이메일 전달성 Powerpack 업데이트**: 특정 테스트 결과에 플래그를 지정하고 댓글을 달고, URL을 통해 관련자와 결과를 공유하고, 관련자가 콘텐츠를 편집할 때 이메일의 진행 상황을 확인할 수 있도록 변경 내용을 추적하는 기능입니다.

Account-Based Marketing

이제 **[AccountAI](/help/marketo/product-docs/target-account-management/account-profiling/account-profiling-ranking-and-tuning.md)**&#x200B;을 일반적으로 사용할 수 있습니다. AccountAI는 인공 지능을 사용하여 ABM 전략에 대해 타겟팅해야 하는 계정을 표시합니다.

<br> 

**_비분기 릴리스_**

다음 기능은 첫 번째 달력 분기 전체와 2019년 2분기 초에 릴리스될 예정입니다.

## [!DNL Marketo Sky]

* **전체 전자 메일 프로그램 기능**: 사용자에게 친숙한 환경에서 전자 메일을 보내고, A/B 테스트를 만들고, 결과를 추적합니다.
* **스마트 캠페인 기능**: 스마트 캠페인 기능이 Sky에서 계속 출시되므로 새 사용자 인터페이스에서 향상된 안정성을 즐기십시오.
* **Design Studio Assets 관리**: Design Studio 목록 보기에서 템플릿, 이미지, Forms, 코드 조각, 파일, 이메일 및 랜딩 페이지를 대량으로 관리할 수 있는 기능이 추가되었습니다.
* **받는 사람 표준 시간대 대시보드에서 배달**: Sky의 받는 사람 표준 시간대 배달 기능을 사용하여 보낸 전자 메일에 대한 보고를 통해 고객 행동을 이해합니다.

## Marketo Sales Engage

* **향상된 감사**: 다른 사용자가 만든 [기존 캠페인을 종료](/help/marketo/product-docs/marketo-sales-connect/campaigns/view-campaigns-list-as-another-user.md)할 수 있는 기능이 추가된 인스턴스에서 모든 사람, 전자 메일 및 [콘텐츠](/help/marketo/product-docs/marketo-sales-connect/templates/view-template-list-as-another-user.md)에 대한 새로운 가시성
* **[관리 구독 취소](/help/marketo/product-docs/marketo-sales-connect/email/unsubscribes/marketo-unsubscribe-check.md)**: [전자 메일 도메인 차단](/help/marketo/product-docs/marketo-sales-connect/admin/blocked-domains.md) 기능에 따라 게재 능력을 최대화하고 규정을 준수합니다. Marketo은 이메일을 보내기 전에 가입 해지용 리드 데이터베이스를 상호 참조합니다.

## Marketo의 [!DNL Bizible]

* **[!DNL Bizible]기능 개선 사항 살펴보기**: 새로운 대시보드 세분화 기능을 통해 마케터가 성능을 더 잘 이해할 수 있습니다.
* **다중 통화 지원**: CRM 통화 테이블에 빌드된 [!DNL Bizible]의 새 자동 통화 변환 기능을 사용하여 회사 통화와 모든 로컬 통화 간을 전환합니다.
* **CRM 캠페인 비용**: CRM 캠페인 개체에서 비용 데이터를 자동으로 가져오는 기능을 사용하여 오프라인 마케팅 활동의 지출 및 ROI를 측정합니다.

## 2019년 6월 {#june}

다음 기능은 2019년 6월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

**_분기별 릴리스_**

다음 기능은 2019년 6월 14일에 출시되었습니다.

## Marketo 핵심 서비스 {#marketo-core-services}

* **파일 체크섬 일괄 추출**: 파일 해시를 완료된 추출 작업의 체크섬 문자열과 비교하여 전체 파일이 검색되었는지 확인하십시오.
* **이메일 1.0에서 이메일 2.0으로 자동 마이그레이션**: 이메일 2.0은 이메일 1.0 이메일 및 템플릿과 완전히 호환됩니다. 콘텐츠 요소(이미지, 텍스트 등)를 그룹화하는 기능과 같은 새로운 기능을 즐겨 보십시오. 모듈로 템플릿 내에서 문자열, 색상, 이미지 등과 같은 변수를 정의하고 전체 응답형 스타터 템플릿을 활용합니다. 또한 시각적 이메일 템플릿 선택기도 포함됩니다.

>[!CAUTION]
>
>2019년 6월 18일부터 이메일 1.0을 더 이상 사용할 수 없습니다. Email 2.0 및 Email 1.0 사용 중단에 대해 자세히 알아볼 수 있습니다. [여기](https://nation.marketo.com/docs/DOC-7038).

## Account-Based Marketing

* **[!DNL LinkedIn]계정 일치(BETA)** : 이제 베타에서 새로운 ABM 기능을 사용할 수 있으며, 이를 통해 알려진 계정 및 공백 계정 목록을 Marketo에서 LinkedIn으로 직접 보낼 수 있습니다. 이 기능은 모든 Marketo ABM 고객을 위해 자동으로 포함됩니다.

<br> 

**_분기 내내 출시_**

다음 기능은 2분기 내내, 그리고 2019년 3분기 초까지 릴리스될 예정입니다.

## [!DNL Marketo Sky]

* **이벤트 상한** 및 **이벤트 목표**&#x200B;는 일반적으로 Premium 이벤트 추가 기능의 [!DNL Marketo Sky]에서 사용할 수 있습니다.

   * 이벤트 상한: 등록 상한, 페이지 리디렉션 및 대기자 명단 기능을 사용하여 이벤트 및 웨비나에 대한 고객 경험을 최적화합니다.
   * 이벤트 목표: 이벤트 등록 및 출석 목표를 설정하고 진행 상황을 실시간으로 추적합니다.

* **전체 탐색 링크**: Hootsuite, Calendar 등과 같이 권한이 부여된 모든 응용 프로그램에 대한 탐색을 활성화했습니다.
* **전자 메일, 랜딩 페이지, 코드 조각, 양식, 이미지 및 파일 목록 보기**: Design Studio에서 자산을 보고 검색하고 다수의 작업을 수행합니다.
* **이미지, 파일 및 코드 조각 세부 정보 페이지**: _만든 날짜/만든 사람_&#x200B;과(와) 같은 메타데이터와 _삭제_ 및 _승인_&#x200B;과(와) 같은 작업을 사용하여 자산에 대한 빠른 세부 정보를 가져옵니다.
* **커뮤니티 블로그 게시물 위젯**: 내 Marketo 내 커뮤니티의 최근 게시물에 액세스합니다.
* **곧 만료 위젯**: &quot;곧 만료&quot; 위젯을 My Marketo 대시보드에 추가하여 다음에 만료될 캠페인과 랜딩 페이지를 확인합니다.
* **추가 스마트 목록 카드**: &quot;작업 만들기&quot; 흐름 단계, CRM 스마트 목록 규칙 등을 포함하여 추가 스마트 목록 카드를 적절히 세그먼트화하고 타깃팅합니다.
* **전자 메일 챔피언/챌린저 세부 정보 페이지**: 전자 메일 챔피언/챌린저 테스트에서 채택 기준, 만든 위치 등의 데이터를 확인하십시오.

## Marketo [!DNL Sales Connect] {#marketo-sales-connect}

* [!DNL Salesforce] 사용자 지정의 **일괄 작업**: [!DNL Salesforce] 사용자 지정을 사용하여 이메일을 보내고 연락처를 캠페인에 일괄 추가하여 생산성을 극대화합니다.
* **설정 - 관리자 및 관리자가 아닌 사용자를 위한 [!DNL Salesforce] 페이지**: [!DNL Sales Connect]에 연결된 [!DNL Salesforce] 인스턴스 및 [!DNL Salesforce] 업데이트에 대한 내 전자 메일을 명확하게 확인하여 [!DNL Sales Connect] 인스턴스를 관리합니다. 관리자, 관리자가 아닌 사용자 및 Team Wide Sync에 대한 향상된 동기화 설정이 몇 달 후에 릴리스됩니다.
* **설정 - 통합 페이지**: 개방형 에코시스템을 최대한 활용할 수 있도록 모든 통합을 위한 원스톱 샵입니다.
* **설정 - 프로필 페이지**: 계정 세부 정보를 보고 업데이트하며, 암호를 변경하고, 이 새 프로필 페이지에서 인스턴스의 구현 상태를 확인합니다.

* **시스템 전자 메일 템플릿**: 디자인, 응답성 및 국제화 기능이 업데이트되었습니다.

## Marketo의 [!DNL Bizible]

* [!DNL Dynamics]&#x200B;**에 대한**&#x200B;다중 통화 지원: [!DNL Bizible]은(는) 이제 [!DNL Microsoft Dynamics] 통화 테이블에 적용되므로 회사 통화와 로컬 통화 간에 쉽게 전환할 수 있습니다. (참고: SFDC에 대한 지원은 2019년 1분기에 릴리스되었습니다.)
* **드리프트 통합**: 드리프트 대화가 고객의 여정에 미치는 영향을 이해합니다. [!DNL Bizible]은(는) 대화에서 전자 메일 주소를 가져와서 새 리드를 만들거나 터치포인트를 기존 리드에 연결합니다.
* **로컬라이제이션**: [!DNL Bizible]은(는) 이제 모든 Marketo 지원 언어(영어, 일본어, 독일어, 스페인어, 프랑스어 및 포르투갈어)로 제공됩니다.

_&#x200B;**제품 릴리스 웨비나**&#x200B;_ 2019년 6월 릴리스 혁신 웨비나 녹화를 시청하십시오 [여기](https://engage.marketo.com/Marketo-June-Product-Release-2019-On-Demand.html).

## 2019년 8월 {#august}

다음 기능은 2019년 8월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

**_분기별 릴리스_**

다음 기능은 2019년 8월 16일에 출시되었습니다.

## 코어 Marketo Engage {#core-marketo-engage}

* **확장 가능한 웨비나 프레임워크**: 웨비나 공급자의 데이터를 Marketo에 원활하게 전달하고 그 반대로 전달하는 Marketo의 새로운 기본 웨비나 프레임워크(19년 겨울 릴리스 정보에 도입됨)를 사용하여 시간을 절약할 수 있습니다. 이제 이 새 프레임워크에서 Cvent 및 Zoom을 사용할 수 있습니다.
* **스마트 캠페인 API 업데이트**: CRUD(만들기, 읽기, 업데이트, 삭제) 인터페이스를 마무리하면서 스마트 캠페인 라이프사이클 기능을 관리합니다.
* **전자 메일 헤더 API 업데이트**: 전자 메일 헤더 API 업데이트에는 제목 줄과 같은 헤더 필드를 업데이트하기 위해 전자 메일에 첨부된 템플릿이 더 이상 필요하지 않습니다.

**Account-Based Marketing** ![(별)](assets/yellow-star.png)

* 이전에 beta 버전이었던 **[!DNL LinkedIn]계정 일치**&#x200B;은(는) 이제 일반적으로 사용할 수 있습니다.
* **AccountAI**&#x200B;이(가) 공식적으로 **계정 프로파일링**(으)로 다시 브랜딩됩니다.

<br> 

**_분기 내내 출시_**

다음 기능은 비분기 주기에 있으며 3분기 내내 2019년 4분기 초에 릴리스될 예정입니다.

**[!DNL Marketo Sales Connect]** ![(별)](assets/yellow-star.png)

* **사람 페이지 레이아웃 개선:** 새 사람 페이지 레이아웃에서 목록 가져오기 및 대량 작업을 통해 사람 및 그룹을 관리합니다.

>[!AVAILABILITY]
>
>별(![(별)](assets/yellow-star.png))로 표시되는 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo 담당자에게 문의하십시오.

>[!NOTE]
>
>**TLS 1.0 및 1.1 사용 중단**: Adobe의 세계적 수준의 보안 표준에 맞게 2019년 12월 13일부터 TLS(전송 계층 보안) 1.0 및 1.1에 대한 지원을 중단할 예정입니다. 1.2 프로토콜을 준수하지 않는 Marketo과 통합된 시스템은 잠재적으로 Marketo Engage 서비스에 대한 액세스 권한을 잃을 수 있습니다.
>
>**Marketo Engage 액세스를 유지하려면 2019년 12월 13일 이전에 모든 클라이언트 시스템이 TLS 1.2를 준수하는지 확인**&#x200B;하십시오. 자세한 내용은 [여기](https://nation.marketo.com/docs/DOC-7059-tls-10-11-deprecation-faq)를 참조하세요.

**_제품 릴리스 웨비나_** [참여하기](https://engage.marketo.com/August_19_Release_Webinar.html) 8월 28일 오전 1:00PMPT/4:00PM에 제품 팀이 호스팅하는 라이브 웨비나에 대해 ET로 참여하여 이 릴리스에 포함된 기능에 대해 자세히 알아보십시오.

