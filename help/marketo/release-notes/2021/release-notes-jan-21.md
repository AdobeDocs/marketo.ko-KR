---
description: 릴리스 노트 - 2021년 1월 - 마케팅 문서 - 제품 설명서
title: 릴리스 노트 - 2021년 1월
translation-type: tm+mt
source-git-commit: 073b73255d49f859c32c8b4793e6798f02f7a5c4
workflow-type: tm+mt
source-wordcount: '1268'
ht-degree: 0%

---


# 릴리스 노트:2021년 1월 {#release-notes-jan-21}

다음 기능은 2011년 1월 릴리스에 포함되어 있습니다. 기능 가용성을 확인하려면 Marketing Edition을 확인하십시오.

>[!AVAILABILITY]
>
>별( ![(star)](assets/star-yellow.svg))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2021년 1월 15일에 릴리스됩니다**.

## 차세대 사용자 경험 {#next-generation-user-experience}

* 작업 영역 지원:Marketo Engage 차세대 사용자 경험은 Adobe Experience Cloud의 모양과 느낌을 통합하며 생산성을 높여주는 혁신적인 기능을 통해 마케팅 전문가가 보다 빠르고 스마트하게 작업할 수 있도록 지원합니다. 최신 릴리스에서는 작업 영역 간에 폴더를 공유할 수 있는 기능을 비롯하여 작업 영역 및 파티션에 대한 모든 지원이 추가되었습니다. 오른쪽 캔바스는 전환 전환을 제공하므로 상황에 맞는 기존 경험과 새로운 경험 간을 매끄럽게 전환할 수 있습니다. [마케팅 ](https://nation.marketo.com/t5/The-Next-Generation-Experience/Next-Generation-Experience-FAQ/ba-p/307124) 국가에 대한 차세대 경험 FAQ에서 자세히 알아보십시오.

## 다중 채널 개인화 {#multi-channel-personalization}

* **[Adobe Experience Cloud 고객 동기화 단계 3](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**:기존 Adobe Experience Cloud(AEC) 대상 동기화 기능은 이제 Marketo Engage에서 다른 AEC 애플리케이션과 Adobe Experience Platform(AEP) 솔루션을 비롯하여 실시간 고객 데이터 플랫폼 및 Adobe Experience Platform 활성화과 같은 지속적인 양방향 B2B 고객 동기화를 지원합니다.  리드가 고객 세그먼트에 추가 및 제거되면 Marketo Engage은 연결된 AEC 앱에서 업데이트된 고객을 자동으로 동기화합니다. AEC 기술 스택에서 Adobe의 멀티채널 통합, 재타깃팅, 고객 억제, 개인화 및 보고 사용 사례를 활용할 수 있습니다.
* **[Google, Facebook 및 LinkedIn에 대한 지속적인 대상 동기화](/help/marketo/product-docs/demand-generation/ad-network-integrations/send-a-list-to-an-ad-network.md)**:광고 네트워크와의 지속적인 자동 동기화를 정적 목록에서 활성화할 수 있으므로 사용자의 개입 없이 광고 네트워크를 목록 구성원 자격 변경 사항으로 업데이트할 수 있습니다.
* **[프로그램 멤버 사용자 정의 필드에 대한 토큰](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/program-member-custom-field-tokens.md)**:토큰 프레임워크를 지원하기 위해 확장된 프로그램 멤버 사용자 정의 필드 기능이 있습니다. 마케터는 프로그램 회원 사용자 정의 필드 토큰을 이메일, 랜딩 페이지, SMS 메시지, 푸시 알림 및 웹후크에 삽입할 수 있습니다. 캠페인 흐름 동작의 새 토큰을 사용하여 데이터 값을 변경하거나 작업을 만들거나 흥미로운 순간을 만들 수 있습니다.

## 랜딩 페이지 및 Forms {#landing-pages-and-forms}

* **양식 API**:리드 정보를 가져오거나 비마케팅 양식에서 데이터를 가져오는 동시에 캠페인을 실행할 수 있습니다. 비마케팅 양식은 REST API를 통해 Marketo Engage과 통합할 수 있습니다. 새로운 API는 모든 관련 기능과 함께 Marketo Engage 양식 제출을 모방하는 기능을 제공합니다.
* **랜딩 페이지 API**:새로운 랜딩 페이지 미리 보기 API를 사용하여 통합 애플리케이션의 편집 및 번역 워크플로우를 간소화할 수 있습니다. 이제 제3자 공급업체는 Marketo Engage에 로그인하지 않고도 랜딩 페이지의 미리 보기를 개인화하여 렌더링할 수 있습니다.  랜딩 페이지 미리 보기 API를 사용하면 제3자 통합 애플리케이션에서 엔드 투 엔드 편집 및 로컬라이제이션 워크플로우를 수행할 수 있습니다.

## 이메일 마케팅 {#email-marketing}

* **[사용자 정의 객체 검색 제한 증가](/help/marketo/product-docs/administration/email-setup/change-custom-object-retrieval-limits-in-velocity-scripting.md)**:이메일 속도 스크립팅 개발자는 셀프 서비스 재정의를 통해 사용자 정의 개체 수를 100개로 빠르게 늘릴 수 있습니다. 마케터는 많은 수의 1차 및 2차 수준 사용자 지정 개체에 액세스하여 스마트 캠페인의 효과를 증가시킬 수 있습니다.

## Salesforce CRM 통합 {#salesforce-crm-integration}

* [Salesforce CRM 인증](/help/marketo/product-docs/crm-sync/salesforce-sync/setting-up-oauth-2-0.md):OAuth 2.0 프로토콜은 Marketo Engage 및 Salesforce CRM 간 작업을 동기화하는 데 사용할 수 있습니다. 새 가입자의 경우 이 옵션은 기본적으로 활성화되어 있습니다. 현재 구독자는 Marketing To 지원에 문의하여 이 기능을 요청할 수 있습니다.
* [Salesforce CRM 동기화 대시보드](/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-errors.md):관리자는 대시보드에서 Salesforce CRM 동기화 상태를 신속하게 검토할 수 있습니다. 성능 보고서 시간 간격을 2시간에서 5일로 늘렸습니다.
* **메타데이터 내보내기**:기회 객체 속성, 지정된 계정, 프로그램 회원의 표준 및 사용자 정의 필드를 지원하도록 향상되었습니다.

## 관리 {#administration}

* **내 계정 페이지** 업데이트:내 계정 페이지에서 필수 구독 정보를 검토하십시오. 모든 수준의 액세스 권한이 있는 사용자는 구독 이름, 데이터 센터 식별자 및 Munchin ID를 볼 수 있습니다.

**_분기 전체 릴리즈_**

다음 기능은 분기별로 판매되지 않는 주기에 있으며 향후 몇 개월 동안 출시될 예정입니다.

## Sales Insight {#sales-insight}

![(별)](assets/star-yellow.svg)

* **[향상된 테스트 이메일 워크플로우(Salesforce CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/actions-in-the-msi-panel/send-marketo-email/send-a-test-email.md)**:향상된 Sales Insight 테스트 이메일 워크플로우를 통해 세일즈 팀의 효율성을 높일 수 있습니다. 판매자는 최대 200명의 수신자에게 일괄 이메일을 보내기 전에 선택한 이메일 주소로 테스트 이메일을 보낼 수 있습니다.
* **[이메일 상태(Salesforce CRM)에 대한 인사이트](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/email-tab.md)**:이메일을 보내기 전에 유효하지 않은 이메일 ID 또는 구독되지 않은 이메일 주소로 이메일을 보내려는 경우 경고 메시지가 표시됩니다.  이메일 배달 상태를 Sales Insight의 이메일 탭에서 검토할 수 있습니다.
* **Account and OpportunityPanels(Salesforce CRM) [](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#account-layout) 에서  [](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#opportunity-layout) 대량 이메일 보내기**:새로운 일괄 작업 기능을 사용하여 판매자 워크플로우의 효율성을 향상시키고 전체 계정 또는 기회 연락처 목록에 참여할 수 있습니다. 개별 연락처를 사용하는 대신 계정 또는 기회 탭의 새로운 드롭다운 옵션을 사용하여 이메일을 보내거나 Marketo Engage 캠페인에 연락처를 추가합니다. 리드가 뜨거워질 때 알림을 받을 수 있도록 계정 연락처를 감시 목록에 추가합니다.
* **[네이티브 Salesforce CRM 통합을 위한 Sales Insight](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)**:맞춤형 Salesforce CRM 통합을 통한 GA 가입은 Sales Insight 패키지를 설치할 수 있고 세일즈 팀이 가장 유망한 리드 및 기회를 우선적으로 고려하고 상호 작용할 수 있도록 지원합니다.
* **[최상의 개선 사항](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/marketo-tab/best-bets.md)**:Marketo Engage 캠페인에 이메일을 보내거나 추가하여 베스트 테스트 탭에서 핫 리드에 빠르게 연락합니다. Marketo Engage에서 리드를 보거나 감시 목록에 추가합니다. 최상의 선택 탭에 있는 일괄 작업 및 정렬 옵션을 사용하면 시간을 절약하고 영업 팀의 효율성을 향상시킬 수 있습니다.

## 판매 연결 {#sales-connect}

![(별)](assets/star-yellow.svg)

* **이메일 연결 제한(베타)**:Sales Connect에 대한 이메일 연결 조절을 사용하여 이메일 전달 능력을 향상시키고 1:1 판매 커뮤니케이션을 확장할 수 있습니다. Adobe의 새로운 조정 기술을 통해 이메일 전송 시간을 자동으로 관리하여 Exchange 및 Gmail 사용자를 위한 완벽한 경험을 제작할 수 있습니다. 제3자 벌크 이메일 보내기 애플리케이션의 사용을 줄이거나 없앨 수 있습니다.
* **이메일 연결 바운스 추적**:새로운 이메일 바운스 보고서를 사용하여 리드 품질 및 이메일 템플릿 성능에 대한 통찰력을 얻을 수 있습니다. Exchange 및 Gmail 사용자는 라이브 피드, 이메일 폴더, 템플릿 분석 및 캠페인 분석에 롤업되는 바운스 알림을 받도록 선택할 수 있습니다.
* **프로필 페이지 구성**:새로운 프로필 페이지에서 사용자 환경 설정을 손쉽게 관리할 수 있습니다. 암호를 변경하고 지리적 위치 및 언어 설정을 편집하며 통합 상태를 한 곳에서 검토할 수 있습니다.
* **템플릿 관리**:새로운 드래그 앤 드롭 기능을 사용하여 세일즈 이메일 템플릿을 카테고리로 구성하여 관련 템플릿에 신속하게 액세스하고 검색 시간을 줄일 수 있습니다.
* **Sales Connect 사용자 경험 업데이트**:열의 크기를 조정하고 순서를 변경하여 Sales Connect 그리드 레이아웃을 사용자 정의할 수 있습니다. 보기 환경 설정이 자동으로 저장됩니다.

**_공지 및 사용 중단_**

* 모든 사용자는 2021년 1월 15일 전에 최신 버전의 Sales Insight **로 업그레이드해야 합니다.** 업그레이드를 완료하지 않은 경우 애플리케이션에 로그인하면 업그레이드를 완료하라는 메시지가 표시됩니다. 이 안내서](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md)의 지침 [을 따릅니다. 업데이트된 버전에는 식별된 보안 취약점에 대한 패치가 포함되어 있습니다. 이 패치는 원래 2016년 4월 6일에 릴리스되었습니다. 참고:**버전 1.4363 이상** 업그레이드를 수행할 필요가 없습니다.
* 양식 1.0 서비스 사용 중단은 **2021년 5월** 릴리스에서 적용됩니다. Forms 1.0 서비스는 완전히 삭제되며 이로 인해 남아 있는 Forms 1.0 에셋의 기능이 계속 손실됩니다. 또한 leadCapture/save 및 leadCapture/save2 엔드포인트에 대한 프로그래머틱 양식 POST와 같이 지원되지 않는 방법을 통해 양식 제출이 거부됩니다. 자세한 정보 및 교정에 대해서는 마케팅 국가](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-the-Marketo-Engage-Form-Platform/ta-p/306631)의 [당사의 게시물을 참조하십시오.
* 2021년에는 Marketo Engage이 랜딩 페이지, 양식, 이미지 및 파일 자산에 대한 URL 구조를 변경할 것입니다. 기존 Marketo Engage 구독의 경우 2021년 4월 1일부터 점진적 롤아웃을 시작할 것입니다. 롤아웃 타임라인에 대한 자세한 내용은 2021년 3월에 발표될 예정입니다. 영향을 받는 각 자산 유형이 변경되는 방법에 대한 자세한 내용은 마케팅 국가에서 [당사의 게시물](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-Design-Studio-URLs/ta-p/306632)을 참조하십시오.

**_제품 릴리스 웨비나_**

이러한 기능과 향상된 기능에 대해 자세히 알고 싶으십니까? 이러한 혁신적인 기능에 대해 자세히 알아보려면 지금 [등록하십시오. 1월 21일 오후 1시 PT / 오후 4시 ET에서 라이브 웨비나를 위해 참가하십시오.](https://engage.marketo.com/January_21_Release_Webinar_Registration.html)
