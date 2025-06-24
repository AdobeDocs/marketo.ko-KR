---
unique-page-id: 37357276
description: 릴리스 노트 - 2020년 6월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2020년 6월
exl-id: ffc39c9f-8c0c-45af-8ee6-f58971e230b9
feature: Release Information
source-git-commit: ecd225af3ecfd7cb9159faf5a9d384d47ee6312c
workflow-type: tm+mt
source-wordcount: '1031'
ht-degree: 0%

---

# 릴리스 노트: 2020년 6월 {#release-notes-june}

다음 기능은 2020년 6월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별(![](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_** 다음 기능은 **2020년 6월 5일**&#x200B;에 릴리스됩니다.

## 코어 Marketo Engage {#core-marketo-engage}

* **[예측 대상](https://experienceleague.adobe.com/docs/marketo/sky/predictive-audiences/getting-started-with-predictive-audiences.html?lang=ko#predictive-audiences)** ![(별)](assets/yellow-star.png): Adobe Sensei에서 제공하는 새로운 스마트 목록 및 스마트 캠페인 필터를 사용하면 이메일, 이벤트 및 웨비나 마케팅 프로그램에 대한 AI 기반 대상 세그먼트를 만들 수 있습니다. 이벤트에 등록하거나, 이벤트에 참석하거나, 구독을 취소할 잠재 가능성을 기반으로 대상을 세그먼트화하는 데 AI를 사용할 수 있습니다. 이전 성공을 효율적으로 복제하기 위해 이전 프로그램을 기반으로 유사 대상을 작성합니다. 예측 목표 추적을 통해 전환 목표를 달성하고 이벤트 프로그램에 대한 대상 세그먼트를 세분화하는 방법에 대한 권장 사항을 얻을 수 있습니다.
* **일괄 이메일 증폭** ![(별)](assets/yellow-star.png): 시간당 최대 300만 개의 일괄 이메일을 보낼 수 있는 이메일 마케팅 기능이 향상되었습니다. 당사는 이메일 프로그램 및 일괄 이메일 캠페인의 성능을 향상하기 위해 일괄 캠페인 및 이메일 보고서 처리를 다시 설계했습니다. 이렇게 하면 전송 리드 타임이 짧아지고 완료 시간도 향상됩니다. 평소대로 이메일 전송을 설정하므로 복잡성이 가중되지 않습니다. 이 개선 사항은 게재 서비스 시작 팩, 이메일 게재 도구 및 여러 전용 IP 주소를 포함하는 제품 추가 기능으로 사용할 수 있습니다.
* **[Adobe Experience Cloud(AEC)와 대상 통합](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md)**: Marketo Engage의 알려진 잠재 고객의 정적 목록을 여러 AEC 애플리케이션과 동기화하여 기존 프로그램을 개선하고 새로운 사용 사례를 잠금 해제하고 멀티채널 캠페인을 오케스트레이션할 수 있는 새로운 Adobe Experience Cloud(AEC) 통합입니다. 이 통합에는 Adobe Analytics, Adobe Target, Adobe Experience Manager, Adobe Audience Manager 및 Adobe Advertising Cloud가 포함됩니다.
* **[프로그램 구성원 사용자 지정 필드](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md)**: 프로그램 구성원에 대한 사용자 지정 필드를 캡처하고 활용합니다. Marketo Engage Forms에서 이러한 새 필드를 사용하고, 프로그램의 멤버 목록에서 보고, 스마트 목록 필터 및 트리거에서 활용하고, 향상된 자동화 및 보다 세분화된 개인화를 위해 새 스마트 캠페인 플로우 작업에 포함하십시오. UI 및 API를 통해 가져오고 내보낼 수도 있습니다. 사용자 지정 데이터 개체 및 필드 기능의 개선 사항.
* **프로그램 구성원 설명**: 프로그램 구성원 메타데이터를 검색하여 REST API를 사용하여 프로그램 구성원 사용자 지정 필드 데이터를 가져오고 내보낼 수 있습니다. API 개선 사항.
* **[다음 위치에 작업 만들기 [!DNL Microsoft Dynamics]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/create-task-in-microsoft.md)**: Marketo Engage에서 캡처한 고객 동작을 기반으로 하는 새 흐름 작업을 사용하여 [!DNL Microsoft Dynamics] 내부에 판매용 작업을 만듭니다. 기본 [!DNL Microsoft Dynamics] CRM 통합 기능이 향상되었습니다.
* **목록 자산 API 끝점에서 사용하는 양식 가져오기**: 양식에 종속된 자산 목록을 검색합니다. API 개선 사항.
* **API를 통해 전자 메일 사전 머리글 설정**: 전자 메일 사전 머리글 필드의 자동 번역 및 지역화를 활성화합니다. API 개선 사항.
* **이미지 및 파일 캐싱**: 60초 캐시에서 이미지 및 파일 자산을 제공하여 Marketo Engage 서버의 안정성을 높이고 있습니다.

## Account-Based Marketing {#account-based-marketing}

![(별)](assets/yellow-star.png)

* **새 계정 검색을 일반적으로 사용할 수 있음**

   * 새 계정 검색은 계정 프로파일링 기능의 향상된 기능으로, AI 기반의 이상적인 고객 프로필 모델을 기반으로 ABM 전략에 대한 신규 대상 계정을 검색할 수 있습니다. AI 기반 적합 및 의도 데이터 지표와 함께 권장 새 계정을 보고, 선택하고, 가져옵니다.

<br> 

**_분기 내내 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## [!DNL Bizible] {#bizible}

![(별)](assets/yellow-star.png)

* **Marketo Engage 프로그램 통합**: 전자 메일 및 참여 프로그램을 적절히 크레딧하기 위해 Marketo Engage에서 직접 프로그램 데이터를 가져와서 [!DNL Bizible]의 속성 여정에 따라 터치포인트를 만듭니다. Marketo Engage 통합 개선 사항.
* **Marketo Engage 활동 통합(BETA)**: Marketo Engage 활동 데이터를 [!DNL Bizible]에 직접 가져와 고객 여정 및 모든 속성 모델에서 터치포인트를 만듭니다. 예를 들면 리드 점수 변경, 흥미로운 순간, 이메일 클릭 또는 사용자 지정 활동이 있습니다. Marketo Engage 통합 개선 사항.
* **[!DNL Bizible]B2B 고객 특성 통합(BETA)**: 선택한 Bizible 데이터를 Adobe Analytics으로 직접 가져와 보다 심층적으로 분석할 수 있는 Adobe Analytics과의 Adobe Experience Cloud 통합입니다. 회사 이름, 계정 특성, CRM 기회 및 [!DNL Bizible] 속성 매출 및 단계 단계로 정의된 고가치 개인별 계정 기반 사이트 트래픽 및 콘텐츠 분석을 예로 들 수 있습니다.
* **[!DNL Bizible]필터 및 개선 사항 검색**: 대시보드에서 채널, 하위 채널, 캠페인 및 세그먼트 필터를 사용하여 데이터를 분석합니다. 더 많은 드릴다운 속성을 통해 데이터 가시성을 강화합니다. 이것은 검색 보드의 개선 사항입니다.
* [!DNL Microsoft Dynamics]&#x200B;**에 대한**&#x200B;활동 동기화: [!DNL Microsoft Dynamics] CRM 활동을 터치포인트 여정에 가져와 판매 상호 작용을 특성화하고 잠재 고객 또는 연락처와 연결된 통화, 약속 또는 작업과 같은 이벤트를 추적합니다. [!DNL Microsoft Dynamics] CRM 통합 개선 사항.

## [!DNL Sales Insight] {#sales-insight}

![(별)](assets/yellow-star.png)

* **[Salesforce CRM용 인사이트 대시보드](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/insights-dashboard-feature-overview.md)**: 판매자가 필요 사항과 관심사를 기반으로 고객 및 잠재 고객에게 더 적합한 추천을 제공할 수 있도록 향후 마케팅 이벤트 및 캠페인에 대한 새로운 가시성으로 [!DNL Sales Insight] 기능을 다시 구상하고 있습니다. 판매자는 타임라인 내에서 연락처 및 계정 활동을 모두 볼 수 있으며 추가 활동 세부 정보에 쉽게 액세스할 수도 있습니다. 패키지를 업그레이드하는 방법에 대한 자세한 내용을 보려면 [여기](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configuration-for-existing-customers.md)를 참조하세요.

<br> 

## 공지 {#announcements}

* **ITP 2.1+ RTP 업데이트**: [!DNL Safari]의 쿠키 정책 변경으로 인해 동일한 도메인의 세션 간에 사용자를 추적하는 RTP 쿠키의 기능은 방문자가 사용하는 브라우저 및 브라우저 버전에 따라 ITP에 의해 1일 또는 7일로 제한됩니다. 이를 위해 RTP 쿠키가 HTTP 응답을 통해 Set-Cookie 헤더로 설정될 수 있도록 새 웹 서비스를 구현하고 있습니다. 자세한 내용은 [여기](https://nation.marketo.com/t5/Knowledgebase/Browser-Cookie-Updates-How-Marketo-RTP-Is-Affected/ta-p/299603)를 참조하세요.

* **일괄 캠페인 인프라 변경**: 올해 남은 기간 동안 일괄 캠페인 서비스를 업그레이드할 예정입니다. 진행 중인 일괄 캠페인에는 영향을 주지 않고 동작을 변경하지 않는 매끄러운 업데이트입니다. 별도의 작업이 필요하지 않습니다. 이 [국가 게시물](https://nation.marketo.com/t5/Product-Documents/Batch-Campaign-Processing-Infrastructure-Update/ta-p/301374)에서 자세한 내용을 확인하세요.

## 사용 중단 {#deprecations}

* **[Munchkin 리드 연결](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/)**: [!DNL Munchkin] JS의 버전 159 릴리스부터 리드 연결 메서드를 호출하면 브라우저 콘솔에 사용 중단 경고가 기록되어 향후 릴리스에서 기능이 제거됨을 나타냅니다.  전체 사용 중단 일정은 추후 공지될 예정입니다.

**_제품 릴리스 웨비나_** [20년 6월 제품 릴리스 혁신 웨비나 녹화 시청](https://engage.marketo.com/June-Release-2020-On-Demand.html)
