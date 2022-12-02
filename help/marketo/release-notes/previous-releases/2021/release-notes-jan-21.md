---
description: 릴리스 노트 - 2021년 1월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2021년 1월
exl-id: 24a5f955-ef4b-4adf-9478-2653db6f9d79
source-git-commit: 85e04fb8a52a417982014bc4bb101b6044e53f84
workflow-type: tm+mt
source-wordcount: '1268'
ht-degree: 0%

---

# 릴리스 노트: 2021년 1월 {#release-notes-jan-21}

다음 기능은 2021년 1월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo 버전을 확인하십시오.

>[!AVAILABILITY]
>
>별로 표시된 기능(![(별)](assets/yellow-star.png))은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2021년 1월 15일**.

## 차세대 사용자 경험 {#next-generation-user-experience}

* 작업 공간 지원: Marketo Engage 차세대 사용자 경험은 Adobe Experience Cloud의 모양과 느낌과 생산성 혁신을 통해 마케팅 전문가가 보다 빠르고 스마트하게 작업할 수 있도록 해줍니다. 최신 릴리스에서는 작업 공간 간에 폴더를 공유하는 기능을 포함하여 작업 공간 및 파티션에 대한 모든 지원을 추가하고 있습니다. 오른쪽 캔버스는 전환 스위치를 제공하여 컨텍스트를 잃지 않고 기능별로 이전 경험과 새 경험 간에 원활하게 전환할 수 있습니다. [추가 정보](https://nation.marketo.com/t5/The-modern-ux/modern-ux-FAQ/ba-p/307124) 를 참조하십시오.

## 다중 채널 개인화 {#multi-channel-personalization}

* **[Adobe Experience Cloud 대상 동기화 3단계](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**: 기존 Adobe Experience Cloud(AEC) Audience Sync 기능은 이제 Real-time Customer Data Platform 및 Adobe Experience Platform 활성화과 같은 Adobe Experience Platform(AEP) 오퍼링을 포함하여 Marketo Engage에서 다른 AEC 애플리케이션으로의 지속적인 양방향 B2B 대상 동기화를 지원합니다.  리드가 대상 세그먼트에 추가되고 제거되면 Marketo Engage은 연결된 AEC 앱에서 업데이트된 대상을 자동으로 동기화합니다. 이 기능을 사용하여 AEC 기술 스택에서 Adobe의 멀티채널 오케스트레이션, 재타깃팅, 대상 억제, 개인화 및 보고 사용 사례를 활용할 수 있습니다.
* **[Google, Facebook 및 LinkedIn에 대한 지속적인 대상 동기화](/help/marketo/product-docs/demand-generation/ad-network-integrations/send-a-list-to-an-ad-network.md)**: 정적 목록에서 광고 네트워크와의 연속 자동 동기화를 사용할 수 있으며, 사용자 개입 없이 광고 네트워크를 목록 멤버십 변경 사항으로 업데이트할 수 있습니다.
* **[프로그램 구성원 사용자 지정 필드에 대한 토큰](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/program-member-custom-field-tokens.md)**: 토큰 프레임워크를 지원하기 위해 프로그램 구성원 사용자 지정 필드 기능을 확장했습니다. 마케터는 프로그램 구성원 사용자 지정 필드 토큰을 이메일, 랜딩 페이지, SMS 메시지, 푸시 알림 및 웹 후크에 삽입할 수 있습니다. 캠페인 흐름 작업의 새 토큰을 사용하여 데이터 값을 변경하거나, 작업을 만들거나, 흥미로운 순간을 만들 수 있습니다.

## 랜딩 페이지 및 Forms {#landing-pages-and-forms}

* **양식 API**: Marketo이 아닌 양식에서 데이터를 가져오면서 리드 정보를 가져오거나 캠페인 육성을 트리거합니다. Marketo이 아닌 양식은 REST API를 통해 Marketo Engage과 통합할 수 있습니다. 새로운 API는 모든 관련 기능으로 Marketo Engage 양식 제출을 모방하는 기능을 제공합니다.
* **랜딩 페이지 API**: 새로운 랜딩 페이지 미리 보기 API를 사용하여 통합 애플리케이션의 편집 및 번역 워크플로우를 간소화합니다. 이제 타사 공급업체는 Marketo Engage에 로그인하지 않고 랜딩 페이지의 완전히 개인화된 미리 보기를 렌더링할 수 있습니다.  랜딩 페이지 미리 보기 API를 사용하면 타사 통합 애플리케이션에서 엔드 투 엔드 편집 및 로컬라이제이션 워크플로우를 사용할 수 있습니다.

## 이메일 마케팅 {#email-marketing}

* **[사용자 정의 객체 검색 제한 증가](/help/marketo/product-docs/administration/email-setup/change-custom-object-retrieval-limits-in-velocity-scripting.md)**: 이메일 속도 스크립팅 개발자는 셀프 서비스 재지정을 통해 사용자 지정 개체 수를 빠르게 100개로 늘릴 수 있습니다. 마케터는 더 많은 수의 첫 번째 및 두 번째 수준 사용자 지정 개체에 액세스하여 스마트 캠페인의 효과를 높일 수 있습니다.

## Salesforce CRM 통합 {#salesforce-crm-integration}

* [Salesforce CRM 인증](/help/marketo/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.md): OAuth 2.0 프로토콜은 Marketo Engage과 Salesforce CRM 간의 작업을 동기화하는 데 사용할 수 있습니다. 새 구독자의 경우 이 옵션이 기본적으로 활성화되어 있습니다. 현재 구독자는 Marketo 지원에 연락하여 이 기능을 요청할 수 있습니다.
* [Salesforce CRM 동기화 대시보드](/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-errors.md): 관리자는 대시보드에서 Salesforce CRM 동기화 상태를 빠르게 검토할 수 있습니다. 성능 보고서 시간 간격을 2시간에서 5일로 늘렸습니다.
* **메타데이터 내보내기**: 기회 객체 속성, 명명된 계정, 프로그램 멤버의 표준 및 사용자 정의 필드를 지원하도록 기능이 향상되었습니다.

## 관리 {#administration}

* **내 계정 페이지를 업데이트했습니다.**: 내 계정 페이지에서 필수 구독 정보를 검토합니다. 모든 액세스 수준의 사용자는 구독 이름, 데이터 센터 식별자 및 Munchkin ID를 볼 수 있습니다.

**_분기 전체에 출시_**

다음 기능은 비분기별 사이클에 있으며 앞으로 몇 개월 동안 릴리스될 예정입니다.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **[향상된 테스트 이메일 워크플로우(Salesforce CRM)](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/actions-in-the-msi-panel/send-marketo-email/send-a-test-email.md)**: 향상된 Sales Insight 테스트 이메일 워크플로우를 통해 영업 팀의 효율성을 높일 수 있습니다. 판매자는 최대 200명의 수신자에게 벌크 이메일을 보내기 전에 선택한 이메일 주소로 테스트 이메일을 보낼 수 있습니다.
* **[이메일 상태(Salesforce CRM)에 대한 통찰력](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/email-tab.md)**: 사용자는 이메일을 보내기 전에 잘못된 이메일 ID 또는 가입 해지된 이메일 주소로 이메일을 보내려고 하면 경고 메시지가 표시됩니다.  이메일 게재 상태는 Sales Insight의 이메일 탭에서 검토할 수 있습니다.
* **보낸 사람 대량 이메일 보내기 [계정](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#account-layout) 및 [기회](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/msi-feature-overview.md#opportunity-layout) 패널(Salesforce CRM)**: 새로운 일괄 작업 기능을 사용하여 판매자 워크플로우의 효율성을 향상시키고 전체 계정 또는 영업 기회 연락처 목록을 통해 영업 기회 활용 개별 연락처를 사용하는 대신 계정 또는 기회 탭에서 새 드롭다운 옵션을 사용하여 Marketo Engage 캠페인에 이메일을 보내거나 연락처를 추가합니다. 리드가 업데이트될 때 알림을 받으려면 감시 목록에 계정 연락처를 추가하십시오.
* **[비기본 Salesforce CRM 통합을 위한 Sales Insight](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)**: 사용자 지정 Salesforce CRM 통합을 사용하는 GA 가입은 Sales Insight 패키지를 설치하고 영업 팀이 가장 유망한 리드 및 기회를 우선 순위화하고 상호 작용할 수 있도록 지원합니다.
* **[최고의 개선 사항](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/marketo-tab/best-bets.md)**: Marketo Engage 캠페인에 이메일로 전송하거나 추가하여 최상의 선택 탭에서 잠재 고객에게 신속하게 문의하십시오. Marketo Engage에서 리드를 보거나 감시 목록에 추가합니다. 최상의 선택 탭에 있는 대량 작업 및 정렬 옵션을 사용하면 시간을 절약하고 영업 팀의 효율성을 향상시킬 수 있습니다.

## 영업 연결 {#sales-connect}

![(별)](assets/yellow-star.png)

* **전자 메일 연결 조절(베타)**: Sales Connect를 위한 Email Connection Throttling을 통해 이메일 게재 능력을 향상시키고 1:1 영업 커뮤니케이션을 확장할 수 있습니다. Adobe의 새로운 조정 기술은 이메일 전송 타이밍을 자동으로 관리하여 Exchange 및 Gmail 사용자를 위한 원활한 경험을 만듭니다. 타사 대량 이메일 전송 애플리케이션을 줄이거나 사용하지 않습니다.
* **전자 메일 연결 바운스 추적**: 새로운 이메일 바운스 보고서를 사용하여 리드 품질 및 이메일 템플릿 성능에 대한 통찰력을 얻을 수 있습니다. Exchange 및 Gmail 사용자는 라이브 피드, 이메일 폴더, 템플릿 분석 및 Campaign Analytics에 롤업되는 바운스 알림을 받도록 선택할 수 있습니다.
* **프로필 페이지 구성**: 새 프로필 페이지에서 사용자 환경 설정을 쉽게 관리할 수 있습니다. 암호를 변경하고, 지리적 위치와 언어 설정을 편집하고, 한 위치에서 통합 상태를 검토합니다.
* **템플릿 관리**: 관련 템플릿에 신속하게 액세스하고 검색 시간을 줄일 수 있도록 새로운 드래그 앤 드롭 기능을 사용하여 영업 이메일 템플릿을 카테고리로 구성할 수 있습니다.
* **Sales Connect 사용자 경험 업데이트**: 열 크기 조정 및 순서 재지정을 통해 Sales Connect 그리드 레이아웃을 사용자 정의합니다. 보기 기본 설정이 자동으로 저장됩니다.

**_공지 및 사용 중단_**

* 모든 사용자는 최신 버전의 Sales Insight로 업그레이드해야 합니다 **2021년 1월 15일 이전**. 업그레이드를 완료하지 않은 경우 애플리케이션에 로그인하면 업그레이드를 완료하라는 메시지가 표시됩니다. 다음 지침을 따르십시오 [이 안내서에서](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md). 업데이트된 버전에는 식별된 보안 취약성에 대한 패치가 포함되어 있습니다. 이 패치는 원래 2016년 4월 6일에 릴리스되었습니다. 참고: **버전 1.4363 이상** 업그레이드를 수행할 필요가 없습니다.
* 양식 1.0 서비스 사용 중단은 **2021년 5월** 릴리스 . Forms 1.0 서비스는 더 이상 사용되지 않으며, 따라서 아직 사용 중인 모든 Forms 1.0 자산의 기능이 손실됩니다. 또한 leadCapture/save 및 leadCapture/save2 종단점에 대한 프로그래밍 양식 POST와 같이 지원되지 않는 방법을 통해 양식 제출이 거부됩니다. 자세한 내용 및 수정은 [마케팅 국가의 adobe 게시물](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-the-Marketo-Engage-Form-Platform/ta-p/306631).
* 2021년에 Marketo Engage은 랜딩 페이지, 양식, 이미지 및 파일 자산에 대한 URL 구조를 변경할 예정입니다. 기존 Marketo Engage 가입의 경우 2021년 4월 1일에 점진적 롤아웃을 시작할 예정입니다. 롤아웃 타임라인에 대한 자세한 내용은 2021년 3월에 릴리스됩니다. 영향을 받는 각 자산 유형이 변경되는 방법에 대한 자세한 내용은 [마케팅 국가의 adobe 게시물](https://nation.marketo.com/t5/Product-Documents/Upcoming-Changes-to-Design-Studio-URLs/ta-p/306632).

**_제품 릴리스 웨비나_**

이러한 기능 및 개선 사항에 대해 자세히 알고 싶으십니까? 반드시 다음을 수행하십시오 [지금 등록](https://engage.marketo.com/January_21_Release_Webinar_Registration.html) 1월 21일 오후 1시 PT / 오후 4시 ET에 참가하여 제품 팀과 함께 이러한 혁신적인 기능을 자세히 살펴보십시오.
