---
description: 릴리스 노트 - 2021년 1월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2021년 1월
exl-id: 24a5f955-ef4b-4adf-9478-2653db6f9d79
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '1268'
ht-degree: 0%

---

# 릴리스 정보: 2021년 1월 {#release-notes-jan-21}

다음 기능은 2021년 1월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별(![(별)](assets/yellow-star.png))로 표시되는 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2021년 1월 15일**&#x200B;에 릴리스됩니다.

## 차세대 사용자 경험 {#next-generation-user-experience}

* 작업 공간 지원: 차세대 Marketo Engage 사용자 경험은 Adobe Experience Cloud의 룩과 느낌을 생산성 혁신과 함께 제공함으로써 마케팅 실무자가 더 빠르고 효율적으로 작업할 수 있도록 지원합니다. 최신 릴리스에서는 작업 영역 간 폴더 공유 기능을 포함하여 작업 영역 및 파티션에 대한 모든 지원을 추가하고 있습니다. 오른쪽 캔버스에는 전환 스위치가 있어 컨텍스트를 손실하지 않고 기능별로 이전 경험과 새 경험 사이를 원활하게 전환할 수 있습니다. 마케팅 국가에 대한 차세대 경험 FAQ에서 [자세히 알아보기](https://nation.marketo.com/t5/The-modern-ux/modern-ux-FAQ/ba-p/307124).

## 다중 채널 Personalization {#multi-channel-personalization}

* **[Adobe Experience Cloud 대상 동기화 단계 3](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**: 기존 Adobe Experience Cloud(AEC) 대상 동기화 기능은 이제 Real-time Customer Data Platform 및 Adobe Experience Platform Activation과 같은 Adobe Experience Platform(AEP) 서비스를 포함하여 Marketo Engage에서 다른 AEC 애플리케이션으로의 지속적인 양방향 B2B 대상 동기화를 지원합니다.  잠재 고객이 대상 세그먼트에 추가되고 제거되면, Marketo Engage은 연결된 AEC 앱에서 업데이트된 대상을 자동으로 동기화합니다. 이를 사용하여 AEC 기술 스택에서 Adobe의 멀티채널 오케스트레이션, 재타겟팅, 대상자 억제, 개인화 및 보고 사용 사례를 이용할 수 있습니다.
* **[Google, Facebook 및 LinkedIn에 대한 지속적인 대상 동기화](/help/marketo/product-docs/demand-generation/ad-network-integrations/send-a-list-to-an-ad-network.md)**: 정적 목록에서 광고 네트워크와의 지속적인 자동 동기화를 사용하도록 설정하여 사용자 개입 없이 목록 멤버십이 변경됨에 따라 광고 네트워크를 업데이트할 수 있습니다.
* **[프로그램 구성원 사용자 지정 필드에 대한 토큰](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/program-member-custom-field-tokens.md)**: 토큰 프레임워크를 지원하도록 프로그램 구성원 사용자 지정 필드 기능을 확장했습니다. 마케터는 프로그램 멤버 사용자 지정 필드 토큰을 이메일, 랜딩 페이지, SMS 메시지, 푸시 알림 및 웹후크에 삽입할 수 있습니다. 캠페인 흐름 액션에서 새 토큰을 사용하여 데이터 값을 변경하거나, 작업을 생성하거나, 즐거운 순간을 만들 수 있습니다.

## 랜딩 페이지 및 Forms {#landing-pages-and-forms}

* **양식 API**: Marketo이 아닌 양식에서 데이터를 가져오는 동안 리드 정보를 가져오거나 캠페인을 트리거합니다. 비 Marketo Forms는 REST API를 통해 Marketo Engage과 통합할 수 있습니다. 새로운 API는 모든 관련 기능을 사용하여 Marketo Engage 양식 제출을 모방하는 기능을 제공합니다.
* **랜딩 페이지 API**: 새로운 랜딩 페이지 미리 보기 API를 사용하여 통합 응용 프로그램의 편집 및 번역 워크플로를 간소화합니다. 이제 서드파티 공급업체는 Marketo Engage에 로그인하지 않고도 랜딩 페이지의 완전히 개인화된 미리보기를 렌더링할 수 있습니다.  랜딩 페이지 미리보기 API를 통해 통합 타사 애플리케이션에서 통합 편집 및 현지화 워크플로를 통합 관리할 수 있습니다.

## 이메일 마케팅 {#email-marketing}

* **[사용자 지정 개체 검색 제한 늘림](/help/marketo/product-docs/administration/email-setup/change-custom-object-retrieval-limits-in-velocity-scripting.md)**: 이메일 속도 스크립팅 개발자는 셀프 서비스 재정의를 통해 사용자 지정 개체 수를 100개로 빠르게 늘릴 수 있습니다. 마케터는 더 많은 첫 번째 및 두 번째 수준 사용자 지정 개체에 액세스하여 스마트 캠페인의 효과를 높일 수 있습니다.

## Salesforce CRM 통합 {#salesforce-crm-integration}

* [Salesforce CRM 인증](/help/marketo/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.md): Marketo Engage과 Salesforce CRM 간의 작업을 동기화하는 데 OAuth 2.0 프로토콜을 사용할 수 있습니다. 새 구독자의 경우 이 옵션은 기본적으로 활성화되어 있습니다. 현재 구독자는 Marketo 지원 센터에 문의하여 이 기능을 요청할 수 있습니다.
* [Salesforce CRM 동기화 대시보드](/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-errors.md): 관리자는 대시보드에서 Salesforce CRM 동기화 상태를 빠르게 검토할 수 있습니다. 성능 보고서 동기화 시간이 2시간에서 5일로 늘어났습니다.
* **메타데이터 내보내기**: 영업 기회 개체 특성, 명명된 계정, 프로그램 구성원의 표준 및 사용자 지정 필드를 지원하도록 개선되었습니다.

## 관리 {#administration}

* **내 계정 페이지를 업데이트했습니다**: 내 계정 페이지에서 필수 구독 정보를 검토하십시오. 모든 수준의 액세스 권한이 있는 사용자는 구독 이름, 데이터 센터 식별자 및 Munchkin ID를 볼 수 있습니다.

**_분기 내내 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **[향상된 테스트 이메일 워크플로(Salesforce CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/actions-in-the-msi-panel/send-marketo-email/send-a-test-email.md)**: 향상된 Sales Insight 테스트 이메일 워크플로를 통해 영업팀의 효율성을 높이십시오. 판매자는 최대 200명의 수신자에게 대량 이메일을 보내기 전에 선택한 이메일 주소로 테스트 이메일을 보낼 수 있습니다.
* **[이메일 상태 인사이트(Salesforce CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/email-tab.md)**: 사용자가 이메일을 보내기 전에 잘못된 이메일 ID 또는 구독 취소한 이메일 주소로 이메일을 보내려고 하면 경고 메시지가 표시됩니다.  이메일 게재 상태는 Sales Insight의 이메일 탭에서 검토할 수 있습니다.
* **[계정](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#account-layout) 및 [영업 기회](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#opportunity-layout) 패널(Salesforce CRM)에서 대량 전자 메일 보내기**: 새로운 대량 작업 기능을 사용하여 판매자의 워크플로우의 효율성을 개선하고 전체 계정 또는 영업 기회 연락처 목록에 참여하십시오. 개별 연락처로 작업하는 대신 Marketo Engage 또는 영업 기회 탭의 새로운 드롭다운 옵션을 사용하여 이메일을 보내거나 연락처를 영업 기회 캠페인에 추가할 수 있습니다. 잠재 고객이 뜨거워지면 알림을 받을 계정 연락처를 관심 목록에 추가합니다.
* **[비기본 Salesforce CRM 통합을 위한 Sales Insight](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)**: 사용자 지정 Salesforce CRM 통합을 통한 GA 구독으로 Sales Insight 패키지를 설치하고 영업 팀이 가장 유망한 리드 및 기회에 우선 순위를 지정하고 상호 작용할 수 있도록 지원합니다.
* **[최고 베트 개선 사항](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/marketo-tab/best-bets.md)**: 최고 베트 탭에서 전자 메일을 보내거나 Marketo Engage 캠페인에 추가하여 핫리드에 빠르게 연락하십시오. Marketo Engage의 잠재 고객을 확인하거나 관심 목록에 추가하십시오. 최상의 선택(Best Bets) 탭의 대량 작업 및 정렬 옵션은 시간을 절약하고 영업팀의 효율성을 향상시킵니다.

## 영업 연결 {#sales-connect}

![(별)](assets/yellow-star.png)

* **전자 메일 연결 제한(BETA)**: Sales Connect의 전자 메일 연결 제한을 사용하여 전자 메일 배달 능력을 개선하고 1:1 판매 커뮤니케이션을 확장하세요. 새로운 조절 기술은 Exchange 및 Gmail 사용자를 위한 원활한 경험을 만들기 위해 이메일 전송 타이밍을 자동으로 관리합니다. 서드파티 벌크 이메일 전송 애플리케이션의 사용을 줄이거나 제거합니다.
* **전자 메일 연결 바운스 추적**: 새로운 전자 메일 바운스 보고서를 사용하여 잠재 고객 품질 및 전자 메일 템플릿 성능에 대한 통찰력을 얻으십시오. Exchange 및 Gmail 사용자는 라이브 피드, 이메일 폴더, 템플릿 분석 및 Campaign Analytics로 롤업되는 바운스 알림을 수신하도록 선택할 수 있습니다.
* **프로필 페이지 구성**: 새 프로필 페이지에서 사용자 환경 설정을 쉽게 관리할 수 있습니다. 한 곳에서 암호 변경, 지리적 위치 및 언어 설정 편집, 통합 상태 검토 등의 작업을 수행할 수 있습니다.
* **템플릿 관리**: 관련 템플릿에 빠르게 액세스하고 검색 시간을 단축할 수 있도록 새로운 드래그 앤 드롭 기능을 사용하여 판매 전자 메일 템플릿을 카테고리로 구성합니다.
* **Sales Connect 사용자 환경 업데이트**: 열 크기 조정 및 순서를 변경하여 Sales Connect 그리드 레이아웃을 사용자 지정합니다. 보기 환경 설정이 자동으로 저장됩니다.

**_공지 및 사용 중단_**

* 모든 사용자는 2021년 1월 15일 이전 **Sales Insight의 최신 버전으로 업그레이드해야 합니다**. 업그레이드를 완료하지 않은 경우 애플리케이션에 로그인하면 업그레이드를 완료하라는 메시지가 표시됩니다. 이 안내서 [&#128279;](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md)의 지침 을(를) 따릅니다. 업데이트된 버전에는 식별된 보안 취약점에 대한 패치가 포함되어 있습니다. 해당 패치는 원래 2016년 4월 6일에 출시되었습니다. 참고: **버전 1.4363 이상**&#x200B;은(는) 업그레이드를 수행할 필요가 없습니다.
* 양식 1.0 서비스 사용 중단이 **2021년 5월** 릴리스에 적용됩니다. Forms 1.0 서비스는 완전히 중단되어 사용 중인 나머지 Forms 1.0 자산의 기능이 손실됩니다. 또한 leadCapture/save 및 leadCapture/save2 종단점에 대한 프로그래밍 방식 양식 POST와 같이 지원되지 않는 메서드를 통해 제출된 양식이 거부됩니다. 자세한 내용 및 수정 사항은 [Marketing Nation의 게시물](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-the-Marketo-Engage-Form-Platform/ta-p/306631)을 참조하세요.
* 2021년에 Marketo Engage은 랜딩 페이지, 양식, 이미지 및 파일 에셋의 URL 구조를 변경할 예정입니다. 기존 Marketo Engage 구독의 경우 2021년 4월 1일부터 점진적 롤아웃을 시작합니다. 롤아웃 타임라인에 대한 자세한 내용은 2021년 3월에 공개될 예정입니다. 영향을 받는 각 에셋 유형의 변경 방법에 대한 자세한 내용은 [Marketing Nation의 게시물](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-Design-Studio-URLs/ta-p/306632)을 참조하세요.

**_제품 릴리스 웨비나_**

이러한 기능 및 개선 사항에 대해 자세히 알아보시겠습니까? 1월 21일 오후 1시(PT)/오후 4시(ET 기준)에 참여하려면 [지금 등록](https://engage.marketo.com/January_21_Release_Webinar_Registration.html)하여 제품 팀과 함께 라이브 웨비나를 통해 이러한 혁신적인 기능을 자세히 알아보십시오.
