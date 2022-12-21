---
unique-page-id: 37357276
description: 릴리스 노트 - 2006년 6월 20일 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2020년 6월
exl-id: ffc39c9f-8c0c-45af-8ee6-f58971e230b9
source-git-commit: 74effe9f8078f8d71e6de01d6e737ddc86978abb
workflow-type: tm+mt
source-wordcount: '1071'
ht-degree: 0%

---

# 릴리스 노트: 2020년 6월 {#release-notes-june}

다음 기능은 2020년 6월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo 버전을 확인하십시오.

>[!AVAILABILITY]
>
>별로 표시된 기능(![](assets/yellow-star.png))은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_** 다음 기능은 **2020년 6월 5일**.

## 코어 Marketo Engage {#core-marketo-engage}

* **[Predictive Audiences](https://experienceleague.adobe.com/docs/marketo/sky/predictive-audiences/getting-started-with-predictive-audiences.html?lang=en#predictive-audiences)** ![(별)](assets/yellow-star.png): Adobe Sensei에서 제공하는 새로운 스마트 목록 및 스마트 캠페인 필터를 사용하면 이메일, 이벤트 및 웨비나 마케팅 프로그램에 AI 기반의 대상 세그먼트를 만들 수 있습니다. AI를 사용하여 리드 가능성을 기반으로 대상을 세그먼트화하여 이벤트에 등록하거나, 이벤트에 참여하거나, 가입을 해지할 수 있습니다. 이전 프로그램을 기반으로 유사 대상을 구축하여 이전 성공을 효율적으로 복제 예측 목표 추적을 사용하여 전환 목표를 달성하고 이벤트 프로그램에 대한 대상 세그먼트를 세분화하는 방법에 대한 권장 사항을 얻습니다.
* **일괄 이메일 증폭** ![(별)](assets/yellow-star.png): 시간당 최대 300만 개의 일괄 이메일을 보낼 수 있는 이메일 마케팅 기능이 향상되었습니다. 이메일 프로그램 및 배치 이메일 캠페인의 성능을 향상시키기 위해 배치 캠페인 및 이메일 보고서 처리를 다시 설계했습니다. 따라서 전송 리드 타임이 단축되고 완료 시간이 향상됩니다. 평상시처럼 이메일을 보내기를 설정해도 복잡성을 추가하지 않습니다. 이 개선 사항은 게재 서비스 실행 팩, 이메일 게재 도구 및 여러 전용 IP 주소도 포함하는 제품 추가 기능으로 사용할 수 있습니다.
* **[AEC(Adobe Experience Cloud)과 대상 통합](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**: 새로운 AEC(Adobe Experience Cloud) 통합을 통해 Marketo Engage에서 알려진 리드의 정적 목록을 여러 AEC 애플리케이션과 동기화하여 기존 프로그램을 개선하고, 새로운 사용 사례를 잠금 해제하며, 멀티채널 캠페인을 오케스트레이션할 수 있습니다. 이 통합에는 Adobe Analytics, Adobe Target, Adobe Experience Manager, Adobe Audience Manager 및 Adobe Advertising Cloud이 포함됩니다.
* **[프로그램 구성원 사용자 정의 필드](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md)**: 프로그램 멤버에 대한 사용자 정의 필드를 캡처하고 활용합니다. Marketo Engage 양식에서 이러한 새로운 필드를 사용하고, 프로그램의 구성원 목록에서 보고, 스마트 목록 필터 및 트리거에서 활용하고, 향상된 자동화 및 보다 세분화된 개인화를 위해 새로운 스마트 캠페인 흐름 작업에 포함하십시오. UI 및 API를 통해 가져오고 내보낼 수도 있습니다. 사용자 지정 데이터 개체 및 필드 기능의 개선 사항입니다.
* **프로그램 멤버 설명**: 프로그램 멤버 메타데이터를 검색하여 REST API를 사용하여 프로그램 멤버 사용자 지정 필드 데이터를 가져오고 내보낼 수 있습니다. API에 대한 개선 사항.
* **[Microsoft Dynamics에서 작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/create-task-in-microsoft.md)**: Marketo Engage에 캡처된 고객 행동에 따라 새로운 흐름 작업을 사용하여 Microsoft Dynamics 내에서 Sales를 위한 작업을 만듭니다. 기본 Microsoft Dynamics CRM 통합 개선 사항.
* **목록 자산 API 끝점에서 사용하는 양식 가져오기**: 양식에 의존하는 자산 목록을 검색합니다. API에 대한 개선 사항.
* **API를 통해 이메일 미리 헤더 설정**: 전자 메일 사전 헤더 필드의 자동 번역 및 지역화를 활성화합니다. API에 대한 개선 사항.
* **이미지 및 파일 캐싱**: 60초 캐시에서 이미지 및 파일 자산을 제공하여 Marketo Engage 서버 안정성을 향상시키고 있습니다.

## Account-Based Marketing {#account-based-marketing}

![(별)](assets/yellow-star.png)

* **일반적으로 사용할 수 있는 새로운 계정 검색**

   * 새로운 계정 검색은 AI 기반의 이상적인 고객 프로필 모델을 기반으로 ABM 전략에 대한 순-새로운 타겟 계정을 검색할 수 있도록 해주는 Adobe의 계정 프로파일링 기능의 개선 사항입니다. AI 기반 Fit 및 Intent 데이터 표시기와 함께 권장 새 계정을 보고 선택하고 가져옵니다.

<br> 

**_분기 전체에 출시_**

다음 기능은 비분기별 사이클에 있으며 앞으로 몇 개월 동안 릴리스될 예정입니다.

## Bizible {#bizible}

![(별)](assets/yellow-star.png)

* **Marketo Engage 프로그램 통합**: 프로그램 데이터를 Marketo Engage에서 직접 가져와 Bizible의 속성 여정에 따라 터치포인트를 만들어 이메일 및 참여 프로그램을 적절하게 크레딧합니다. Marketo Engage 통합 개선 사항.
* **Marketo Engage 활동 통합(베타)**: Marketo Engage 활동 데이터를 Bizible로 직접 가져와 고객 여정 및 모든 속성 모델에서 터치 포인트를 만듭니다. 예를 들면 리드 점수 변경, 흥미로운 순간, 이메일 클릭 또는 사용자 지정 활동이 있습니다. Marketo Engage 통합 개선 사항.
* **Bizible B2B 고객 특성 통합(베타)**: Adobe Analytics과 통합된 Adobe Experience Cloud에서 선택한 Bizible 데이터를 Adobe Analytics으로 직접 가져와 보다 심층적인 분석을 수행할 수 있습니다. 예를 들면 Bizible에서 수익 및 단계 단계로 정의한 회사 이름, 계정 속성, CRM 기회 및 고부가가치 개인별 계정 기반 사이트 트래픽 및 컨텐츠 분석이 있습니다.
* **Bizible Discover 필터 및 개선 사항**: 대시보드 간에 채널, 하위 채널, 캠페인 및 세그먼트 필터를 사용하여 데이터를 분석합니다. 더 많은 드릴다운 특성을 사용하여 데이터 가시성을 강화합니다. 이는 Adobe Discover Board의 개선 사항입니다.
* **Microsoft Dynamics용 활동 동기화**: Microsoft Dynamics CRM 활동을 터치포인트 여정에 가져와서 영업 상호 작용을 만들고, 리드 또는 연락처와 연관된 호출, 약속 또는 작업과 같은 이벤트를 추적합니다. Microsoft Dynamics CRM 통합 개선 사항.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **[Salesforce CRM용 통찰력 대시보드](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/insights-dashboard-feature-overview.md)**: Adobe는 판매 인사이트 기능을 향후 마케팅 이벤트 및 캠페인에 대한 새로운 가시성을 통해 재설계하여 판매자가 자신의 요구 사항과 관심사에 따라 고객과 잠재 고객에게 보다 연관성 있는 추천을 할 수 있도록 합니다. 판매자는 타임라인에서 연락처 및 계정 활동을 모두 보고 추가 활동 세부 사항에 쉽게 액세스할 수도 있습니다. 패키지 업그레이드 방법에 대한 자세한 내용 찾기 [여기](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configuration-for-existing-customers.md).

<br> 

## 공지 {#announcements}

* **ITP 2.1+ RTP 업데이트**: Safari용 쿠키 정책 변경 사항으로 인해, 동일한 도메인의 세션에서 사용자를 추적하는 RTP 쿠키의 기능은 방문자가 사용하는 브라우저 및 브라우저 버전을 기준으로 1 또는 7일로 제한됩니다. 이를 설명하기 위해 HTTP 응답을 통해 RTP 쿠키를 Set-Cookie 헤더로 설정할 수 있도록 새 웹 서비스를 구현하고 있습니다. 자세한 내용 [여기](https://nation.marketo.com/t5/Knowledgebase/Browser-Cookie-Updates-How-Marketo-RTP-Is-Affected/ta-p/299603).

* **배치 캠페인 인프라 변경 사항**: 우리는 올해 남은 기간 동안 일괄 캠페인 서비스를 업그레이드할 것이다. 이 업데이트는 진행 중이며 동작을 변경하지 않는 배치 캠페인에 영향을 주지 않는 매끄러운 업데이트입니다. 필요한 작업은 없습니다. 자세한 내용은 여기에서 확인하십시오 [국가 게시물](https://nation.marketo.com/t5/Product-Documents/Batch-Campaign-Processing-Infrastructure-Update/ta-p/301374).

## 사용 중단 {#deprecations}

* **[Munchkin Associate Lead](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/)**: Munchkin JS 버전 159 릴리스부터 리드 연결 방법이 호출되면 사용 중단 경고가 브라우저 콘솔에 기록되며, 이는 향후 릴리스에서 기능이 제거됨을 나타냅니다.  전체 사용 중단 일정은 나중에 발표될 예정입니다.

**_제품 릴리스 웨비나_** [기록 보기](https://engage.marketo.com/June-Release-2020-On-Demand.html) 2020년 6월 제품 릴리스 혁신 내용 웨비나를 통해 제공됩니다.
