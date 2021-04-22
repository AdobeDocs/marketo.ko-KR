---
unique-page-id: 37357276
description: 릴리스 노트 - 2006년 6월 20일 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 -2006년 6월
exl-id: ffc39c9f-8c0c-45af-8ee6-f58971e230b9
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '1073'
ht-degree: 0%

---

# 릴리스 노트:1920년 6월 {#release-notes-june}

다음 기능은 2006년 6월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별( ![(star)](assets/star-yellow.svg))로 표시된 기능은 유료 추가 기능을 사용할 수 있습니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_** 다음 기능은 2020년  **6월 5일에 릴리스됩니다**.

## 코어 Marketo Engage {#core-marketo-engage}

* **[예측 대상](https://experienceleague.adobe.com/docs/marketo/sky/predictive-audiences/getting-started-with-predictive-audiences.html?lang=en#predictive-audiences)** ![(스타)](assets/star-yellow.svg):Adobe Sensei에서 제공하는 새로운 스마트 목록 및 스마트 캠페인 필터를 사용하면 이메일, 이벤트 및 웨비나 마케팅 프로그램을 위한 AI 기반의 고객 세그먼트를 만들 수 있습니다. AI를 사용하여 이벤트를 등록하거나 이벤트에 참여하거나 가입을 해지할 리드 가능성을 기준으로 고객을 분류할 수 있습니다. 이전 프로그램을 기반으로 유사 고객을 구축하여 이전 성과를 효율적으로 복제할 수 있습니다. 예측 목표 추적을 통해 전환 목표를 달성하고 이벤트 프로그램에 대한 고객 세그먼트를 세분화하는 방법에 대한 권장 사항을 얻을 수 있습니다.
* **일괄 이메일 증폭** ![(별)](assets/star-yellow.svg):시간당 최대 300만 개의 일괄 이메일 전송을 지원하는 이메일 마케팅 기능이 향상되었습니다. 이메일 프로그램과 일괄 이메일 캠페인의 성과를 개선하기 위해 일괄 캠페인 및 이메일 보고서 처리 아키텍처를 다시 설계했습니다. 그러면 전송 리드 시간이 단축되고 완료 시간이 개선됩니다. 이메일에 평소처럼 간편하게 전송할 수 있도록 설정할 수 있으므로 복잡성은 더 이상 없습니다. 이 개선 사항은 배달 서비스 시작 팩, 이메일 배달 도구 및 여러 전용 IP 주소도 포함하는 제품 추가 기능으로 사용할 수 있습니다.
* **[Adobe Experience Cloud(AEC)와 대상 통합](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**:새로운 Adobe Experience Cloud(AEC) 통합을 통해 Marketo Engage의 알려진 리드 목록을 여러 AEC 애플리케이션과 동기화할 수 있으므로 기존 프로그램을 개선하고 새로운 사용 사례를 발굴하며 멀티채널 캠페인을 체계적으로 구성할 수 있습니다. 이 통합에는 Adobe Analytics, Adobe Target, Adobe Experience Manager, Adobe Audience Manager 및 Adobe Advertising Cloud이 포함됩니다.
* **[프로그램 회원 사용자 정의 필드](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md)**:프로그램 멤버에 대한 사용자 정의 필드를 캡처하고 활용할 수 있습니다. Marketo Engage 양식에서 이러한 새 필드를 사용하고, 프로그램의 멤버 목록에서 보고, 스마트 목록 필터와 트리거를 활용하고, 새로운 스마트 캠페인 흐름 동작에 포함시켜 자동화 및 보다 세밀하게 개인화합니다. UI 및 API를 통해 가져오고 내보낼 수도 있습니다. 사용자 지정 데이터 개체 및 필드 기능에 대한 개선 사항.
* **프로그램 회원 설명**:REST API를 사용하여 프로그램 멤버 사용자 정의 필드 데이터를 가져오고 내보낼 수 있는 프로그램 멤버 메타데이터를 검색할 수 있습니다. API에 대한 개선 사항.
* **[Microsoft Dynamics에서 작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/create-task-in-microsoft.md)**:Marketo Engage에서 캡처한 고객 행동에 따라 새로운 흐름 동작을 사용하여 Microsoft Dynamics에서 세일즈 작업을 수행할 수 있습니다. 기본 Microsoft Dynamics CRM 통합에 대한 개선 사항입니다.
* **목록 자산 API 끝점에서 사용한 양식 가져오기**:양식에 의존하는 자산 목록을 검색합니다. API에 대한 개선 사항.
* **API를 통해 이메일 미리 헤더 설정**:이메일 프리헤더 필드의 자동 번역 및 현지화를 활성화합니다. API에 대한 개선 사항.
* **이미지 및 파일 캐싱**:60초 캐시의 이미지 및 파일 에셋을 제공하여 Marketo Engage 서버 안정성을 향상시키고 있습니다.

## 계정 기반 마케팅 {#account-based-marketing}

![(별)](assets/star-yellow.svg)

* **일반적으로 사용할 수 있는 새 계정 검색**

   * 새로운 계정 검색은 AI 기반의 이상적인 고객 프로필 모델을 기반으로 ABM 전략에 대한 순 새 타겟 계정을 찾을 수 있도록 해 주는 계정 프로파일링 기능의 개선 사항입니다. AI 기반 맞춤 및 의도 데이터 표시기와 함께 권장 새 계정을 보고 선택 및 가져옵니다.

<br> 

**_분기 전체 릴리즈_**

다음 기능은 분기별로 판매되지 않는 주기에 있으며 향후 몇 개월 동안 출시될 예정입니다.

## biz가능 {#bizible}

![(별)](assets/star-yellow.svg)

* **Marketo Engage 프로그램 통합**:여정에서 프로그램 데이터를 바로 가져와 Bizble의 어트리뷰션 Marketo Engage에 따라 터치포인트를 만들어 이메일 및 참여 프로그램에 적절히 크레딧을 부여할 수 있습니다. Marketo Engage 통합 향상
* **Marketo Engage 활동 통합(베타)**:Marketo Engage 활동 데이터를 Bizzy로 바로 가져와 고객 여정 및 모든 기여도 모델을 통해 고객 접점을 만들 수 있습니다. 리드 점수 변경 사항, 흥미로운 순간, 이메일 클릭 또는 사용자 지정 활동이 이에 해당합니다. Marketo Engage 통합 향상
* **Bizable B2B 고객 속성 통합(베타)**:Adobe Analytics과 통합된 Adobe Experience Cloud을 통해 특정 Bizable 데이터를 Adobe Analytics으로 직접 가져와 보다 심층적인 분석을 수행할 수 있습니다. 이러한 예로는 회사 이름, 계정 속성, CRM 기회, 그리고 Bizable이 매출 및 단계 전환 단계에 정의한 고부가가치 개인별로 계정 기반 사이트 트래픽 및 컨텐츠 분석이 있습니다.
* **bizable Discover 필터 및 개선 사항**:대시보드에서 채널, 하위 채널, 캠페인 및 세그먼트 필터를 사용하여 데이터를 분석할 수 있습니다. 더 많은 드릴다운 특성을 사용하여 데이터 가시성을 강화합니다. 이는 Discover 보드에 대한 개선 사항입니다.
* **Microsoft Dynamics용 활동 동기화**:Microsoft Dynamics CRM 활동을 터치포인트 여정에 가져오고 리드 또는 연락처와 관련된 호출, 약속 또는 작업과 같은 이벤트를 추적하여 영업 상호 작용을 파악할 수 있습니다. Microsoft Dynamics CRM 통합 기능이 향상되었습니다.

## Sales Insight {#sales-insight}

![(별)](assets/star-yellow.svg)

* **[Salesforce CRM용 인사이트 대시보드](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/insights-dashboard-feature-overview.md)**:Adobe는 판매 인사이트 기능을 향후 마케팅 이벤트 및 캠페인에 대한 새로운 가시성으로 재설계함으로써 판매자는 자신의 요구와 관심사를 바탕으로 고객과 잠재 고객에게 보다 연관성 있는 추천을 제공할 수 있게 되었습니다. 판매자는 타임라인에서 연락처 및 계정 활동을 모두 볼 수 있으며 추가 활동 세부 정보에 손쉽게 액세스할 수 있습니다. 패키지 [여기](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/configuration-for-existing-customers.md)에서 업그레이드 방법에 대한 자세한 내용을 살펴보십시오.

<br> 

## 공지 사항 {#announcements}

* **ITP 2.1+ RTP 업데이트**:Safari에 대한 쿠키 정책 변경으로 인해 동일한 도메인의 세션에서 사용자를 추적하는 RTP 쿠키 기능은 방문자가 사용하는 브라우저 및 브라우저 버전을 기준으로 1 또는 7일로 ITP에 의해 제한됩니다. 이를 위해 HTTP 응답을 통해 RTP 쿠키를 Set-Cookie 헤더로 설정할 수 있도록 허용하는 새 웹 서비스를 구현하고 있습니다. 자세한 내용은 [여기](https://nation.marketo.com/t5/Knowledgebase/Browser-Cookie-Updates-How-Marketo-RTP-Is-Affected/ta-p/299603)를 참조하십시오.

* **배치 캠페인 인프라 변경** 사항:올해 남은 기간 동안 일괄 캠페인 서비스를 업그레이드할 예정입니다. 이 업데이트는 진행 중인 모든 배치 캠페인에는 영향을 주지 않고 동작을 변경하지 않는 매끄러운 업데이트입니다. 작업이 필요하지 않습니다. 이 [국가 게시물](https://nation.marketo.com/t5/Product-Documents/Batch-Campaign-Processing-Infrastructure-Update/ta-p/301374)에서 자세한 내용을 참조하십시오.

## 사용 중단 {#deprecations}

* **[Munchkin Associate 리드](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/)**:Munchkin JS 버전 159 릴리스부터 리드 연결 방법이 호출될 때 사용 중단 경고가 브라우저 콘솔에 기록되어 향후 릴리스에서 기능이 제거될 것임을 나타냅니다.  전체 사용 중단 일정은 나중에 발표될 것이다.

**_제품 릴리스_** [웨비나](https://engage.marketo.com/June-Release-2020-On-Demand.html) 2006년 6월 20일 제품 출시 혁신 웨비나의 녹화 자료를 확인하십시오.
