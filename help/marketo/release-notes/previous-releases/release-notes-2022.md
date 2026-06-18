---
title: 2022
description: 2022년 - Marketo 문서 - 제품 설명서
feature: Release Information
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
  - id: efc9a24a-a6a4-449d-a3e6-44f6c74dfd46
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
  - id: bce87dde-a4ab-44c9-8a18-ad66e4ddb377
  - id: c7d04a2c-412a-4c9d-9d7a-4456eaa5adeb
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
source-git-commit: 5247efff11566852d4c7271f1d212cc233593c19
workflow-type: tm+mt
source-wordcount: 4254
ht-degree: 6%

---

# 2022

## 2022년 1월 {#january}

다음 기능은 2022년 1월 릴리스에 포함되어 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2022년 1월 21일**&#x200B;에 릴리스되기 시작하며, 이후 몇 주 동안(달리 지정하지 않는 한) 모든 기능의 단계적 롤아웃이 적용됩니다.

## 차세대 경험

* **차세대 경험에서 업데이트된 Screens**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 경험에서 새로 고친 화면을 추가로 제공합니다.

   * [!UICONTROL Design Studio]의 랜딩 페이지 자산 세부 정보
   * [!UICONTROL Marketing Activities]의 랜딩 페이지 자산 세부 정보

## [!DNL Microsoft Dynamics] 통합 {#microsoft-dynamics-integration}

* **다중 선택 Optionset 필드 형식 동기화(일반적으로 사용 가능)**: 보다 세분화된 대상 타깃팅을 위해 스마트 목록 및 스마트 캠페인에서 활용하려면 [!DNL Microsoft Dynamics]에서 다중 선택 Optionset 필드 형식을 동기화하십시오. 예로는 관심 주제/제품, 선호하는 커뮤니케이션 모드 등이 있습니다. 이 새 동기화는 [!DNL Microsoft Dynamics] 버전 9.X(Dynamics 365 Online 포함)에서 사용할 수 있습니다.

* [!DNL Microsoft Dynamics 365 Online]&#x200B;**에 대한**&#x200B;서버 간 인증: 보안을 강화하기 위해 이제 서버 간(S2S) 인증을 Azure Active Directory의 Marketo Engage 동기화 사용자가 [!DNL Microsoft Dynamics 365 Online]에 비대화형으로 액세스할 수 있도록 추가 인증 모드로 지원합니다. 모든 인증 및 로그인이 OAuth(클라이언트 ID 및 클라이언트 암호만)를 기반으로 하므로 다단계 인증을 사용할 수 있습니다.

>[!NOTE]
>
>S2S 모드는 라이센스 사용자가 아닌 애플리케이션 사용자를 기반으로 하므로 추가 라이센스 사용이 절약됩니다.

## 관리 {#administration}

* **[양식 유효성 검사 규칙](/help/marketo/product-docs/administration/settings/global-form-validation-rules.md)**: 문제가 있거나 원치 않는 전자 메일 도메인이 Marketo Engage 양식을 제출하지 않도록 차단하는 기능을 사용하여 데이터베이스의 상태를 유지합니다. 관리자는 전역 양식 유효성 검사 패널을 사용하여 양식에 대해 사전 정의된 차단 목록 목록을 정의하거나 자유 소비자 도메인이 차단되도록 할 수 있습니다.

* **[랜딩 페이지 헤더 보안](/help/marketo/product-docs/administration/settings/landing-page-headers.md)**: 관리자는 강력한 보안 요구 사항을 적용하기 위해 랜딩 페이지 도메인에서 엄격한 전송 보안 및 X-Frame 옵션 헤더를 관리할 수 있습니다.

**_분기 내내 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## AEP Marketo Engage Destination Connector - 새로운 리드 만들기 {#aep-marketo-engage-destination-connector}

Adobe Experience Platform(AEP)도 사용하는 Marketo Engage 고객은 AEP 대상 커넥터를 통해 AEP에서 Marketo Engage으로 net-new person 레코드를 푸시할 수 있으므로 데이터베이스를 극대화할 수 있습니다. AEP에서 Marketo Engage으로 대상 세그먼트를 보낼 때 Marketo Engage 데이터베이스 [에 없는 세그먼트 내의 사람은 자동으로 추가할 수 있습니다](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/push-an-adobe-experience-platform-segment-to-a-marketo-static-list.md).

## [!DNL Sales Insight]

![(별)](assets/yellow-star.png)

[!DNL Salesforce] CRM용 **[!DNL Sales Insight]**

* [!UICONTROL Best Bets]&#x200B;**에 대한**&#x200B;새 형식 열: 판매자는 [!UICONTROL Best Bets] 페이지의 리드와 연락처를 구별하기 위해 &quot;Type&quot; 레이블이 지정된 새 열로 더 빠른 통찰력을 얻습니다.

* **[!DNL Salesforce]Platform API 업데이트**: [!DNL Salesforce]에서 [!DNL Salesforce] Platform API 버전 21.0에서 30.0을 중단하는 것에 대한 응답으로 [!DNL Sales Insight] 패키지가 최신 API로 업데이트되었습니다.

* **브랜딩 업데이트됨**: 모든 [!DNL Sales Insight] 페이지가 Adobe 브랜딩에 맞게 업데이트되고 있습니다.

[!DNL Microsoft Dynamics]&#x200B;**에 대한**&#x200B;[!DNL Sales Insight]

* **업데이트된 계정 레이아웃**: 판매자는 전자 메일 활동, 웹 활동, 관심 있는 순간, 계정 내 모든 연락처에 대한 점수 변경과 같은 상위 활동에 대한 집단 보기를 얻을 수 있습니다.

## [!DNL Sales Connect]

![(별)](assets/yellow-star.png)

* **통화 결과 및 이유**: 완전히 사용자 지정 가능한 새로운 통화 결과 및 통화 이유 옵션을 사용하여 영업 팀의 아웃바운드 노력을 더 자세히 이해하고 추적합니다. 이러한 새로운 필드 외에도 판매자가 호출하는 동안 통화 이유 및 결과 선택을 적용하는 새로운 거버넌스, 통화 이유 및 결과를 활성화 또는 비활성화하는 새로운 거버넌스, [!DNL Salesforce]에 데이터를 로깅하는 새로운 통화 이유 및 통화 결과 [!DNL Salesforce] 활동 사용자 지정 필드를 도입합니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/product-blogs/sales-connect-enhancements-to-call-outcomes-q1-22-release/ba-p/319812).

* **[!DNL Salesforce]활동 세부 정보 사용자 지정**: 판매 활동이 [!DNL Sales Connect]에서 [!DNL Salesforce]&#x200B;(으)로 기록될 때 [!DNL Salesforce] 작업 제목 필드에 추가되는 정보를 사용자 지정하여 [!DNL Salesforce]에서 더 많은 판매 활동 및 작업 데이터를 캡처합니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/product-blogs/sales-connect-enahncements-to-activity-logging-to-salesforce-q1/ba-p/319819).

## 공지

* **Marketo Sky 사용 중단**: 차세대 사용자 환경을 제공하기 위해 리소스를 집중하기 때문에 3월에는 Marketo Sky을 더 이상 사용할 수 없습니다. 현재 Marketo Sky에만 적용되는 기능에 대한 액세스를 유지하기 위한 노력으로 3월에 자산 만료 및 스마트 캠페인 우선 순위 재정의를 주요 경험으로 가져올 예정입니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33).

* **양식 끝점 사용 중단**: leadCapture/save2 끝점에 대해 지원되지 않는 프로그래밍 방식의 양식 POST가 Marketo Engage 양식에 의해 거부됩니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/product-documents/updated-october-2021-upcoming-changes-to-the-marketo-engage-form/ta-p/306631).

* **사용자 초대 대화 상자에 로그인**: 3월부터 선택적 기능인 기존 &quot;사용자 초대 대화 상자에 로그인&quot;이 더 이상 사용되지 않습니다. 기능 &quot;[!UICONTROL Login in Invite User Dialog]&quot; 기능은 향후 Adobe Identity Management 시스템 통합에 필요한 유니버설 ID 기능으로 대체되었으며 모든 구독에서 2021년 8월에 활성화되었습니다. 사용 중단으로 인해 Marketo Engage에서는 구독 내 이메일 주소당 하나의 사용자만 연결하도록 강제합니다.

**Marketo Engage 도메인 - [!DNL Sales Insight] 구성**: SSL 인증서가 프로비저닝되고 https://이 없는 Marketo Engage 도메인의 경우 SSL 핸드셰이크 오류로 인해 호출이 실패합니다. 따라서 이러한 도메인은 사용되지 않습니다. 따라서 이러한 도메인을 가리키는 이전 구성을 가진 [!DNL Sales Insight]명의 사용자에게 리드, 연락처, 계정, 영업 기회 패널 또는 Marketo 글로벌 페이지에서 시스템 호출 오류가 발생할 수 있습니다. 이 오류가 발생하면 [!DNL Salesforce]에서 [Marketo Engage 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)을 업데이트하는 것이 좋습니다. 문서의 &quot;[!DNL Marketo Sales Insight] 구성&quot; 섹션에서 강조 표시된 Marketo Engage 자격 증명만 업데이트하면 됩니다.

**_제품 릴리스 웨비나_**

[2022년 1월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_January_Release_Webinar_DemandPage.html)

## 2022년 3월 {#march}

다음 기능은 2022년 3월 릴리스에 포함되어 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2022년 3월 11일**&#x200B;에 릴리스되기 시작하며, 이후 몇 주 동안 모든 기능의 단계적 롤아웃이 적용됩니다(달리 지정되지 않은 경우).

## 크로스 채널 오케스트레이션

* **[!DNL Dynamic Chat]**: 사전 예방적이고 흥미로운 1:1 맞춤형 대화를 통해 잠재 고객과 계정을 모두 타겟팅하여 웹 사이트의 모든 기회를 극대화할 수 있습니다. [Dynamic Chat](/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md){target="_blank"}을(를) 통해 Marketo Engage 사용자는 채팅을 B2B 마케팅 및 판매 사용 사례에 대한 통합 크로스 채널 경험의 핵심 부분으로 활용할 수 있습니다. 기능에는 채팅 내에서 직접 회의를 예약하는 기능, 리드 라우팅, 스타터 템플릿, 끌어다 놓기 대화 만들기 등이 포함됩니다. Dynamic Chat은 모든 Marketo Engage 패키지에 포함되어 있으며 올해 모든 Marketo Engage 사용자에게 배포됩니다.

* **이메일 보트 활동 필터링 개선 사항**: 이전에 릴리스된 [이메일 보트 활동 필터링](/help/marketo/product-docs/administration/email-setup/filtering-email-bot-activity.md){target="_blank"} 기능의 개선 사항으로 이제 봇으로 식별된 로깅 활동을 옵트인할 수 있습니다. 그런 다음 봇이 수행하는 것으로 식별된 활동을 기반으로 작업을 필터링하고 트리거할 수 있습니다.

## 차세대 경험

* **차세대 경험에서 업데이트된 Screens**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 경험에서 새로 고친 화면을 추가로 제공합니다.

   * [!UICONTROL Design Studio]의 양식 목록 보기(새 대량 작업 포함)

* **프로그램 가져오기 워크플로 업데이트**: 가져오기 프로그램 워크플로는 업데이트된 디자인 및 유용성 개선 사항으로 차세대 환경에서 제공됩니다. 토글 스위치가 없는 자동 변경입니다.

* **차세대 경험 전환 스위치에 대한 관리자 컨트롤**: 관리자가 전환 스위치에 액세스할 수 있는 사용자 유형을 선택할 수 있는 기능을 통해 사용자에게 작동하는 방식으로 차세대 경험의 롤아웃을 관리합니다.

## Experience Automated

* **셀프 서비스 흐름 단계(Beta)**: 스마트 캠페인에서 사용할 사용자 지정 흐름 단계를 작성하는 기능을 사용하여 Marketo Engage과 스택의 나머지 부분 간의 연결을 확장합니다. Marketo 사용자와 파트너 모두 이 기능을 활용하여 트리거 캠페인에만 사용할 수 있는 웹후크와 달리 배치 및 실행 가능한 캠페인에서 외부 웹 서비스를 사용할 수 있습니다.

* **자산 만료**: 클래식 사용자 경험에서 지정된 날짜 및 시간에 자동 비활성화를 예약할 수 있는 기능을 사용하여 시간에 민감한 자산 및 캠페인에 대한 제어를 유지합니다.

* **스마트 캠페인 우선 순위 재정의**: 우선 순위가 높은 트리거 스마트 캠페인이 표준 캠페인 우선 순위 순위를 재정의할 수 있는 기능을 사용하여 가능한 한 빨리 실행되도록 합니다. 우선 순위가 낮은 트리거 스마트 캠페인의 우선 순위를 낮춰 우선 순위가 높은 다른 작업에 대한 처리 리소스를 확보할 수도 있습니다.

## API 개선 사항

* **전자 메일의 열기 추적 상태 사용 안 함 반환**: API를 통해 전자 메일의 열기 추적 상태를 읽을 수 있습니다.
* **전자 메일에서 동적 콘텐츠 제목 줄 검색**: 마케터가 BI 도구에서 동적 제목 줄 분석을 수행할 수 있도록 허용합니다.
* **프로그램 멤버 사용자 지정 필드 CRUD**: 마케터가 프로그램 멤버 사용자 지정 필드를 프로그래밍 방식으로 만들 수 있습니다.
* **대량 사용자 지정 개체 내보내기 업데이트됨At 필터**: 마케터가 사용자 지정 개체를 프로그래밍 방식으로 동기화할 수 있도록 허용합니다
* **이메일 프로그램에 대한 헤드 시작 설정 노출**: 마케터는 API를 통해 헤드 시작을 사용하여 이메일 프로그램을 구성할 수 있습니다.
* **선택적 프로그램 태그 업데이트**: 마케터가 모든 태그를 동시에 푸시하지 않고 선택적 태그 업데이트를 푸시할 수 있습니다.
* **일괄 활동 추출 actionResult 필드**: 마케터는 생략되거나 실패한 활동을 식별할 수 있습니다.

**_분기 내내 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## [!DNL Bizible] {#bizible}

![(별)](assets/yellow-star.png)

* **BI 템플릿**: [!DNL Bizible]은(는) 이제 다운로드 가능한 기본 보고 아티팩트와 Tableau 및 Power BI에 대한 샘플 보고서를 제공하여 특정 비즈니스 요구 사항에 맞는 맞춤형 보고서를 신속하게 개발할 수 있도록 합니다.

## [!DNL Sales Connect]

![(별)](assets/yellow-star.png)

* **GA(전자 메일 연결 제한)**: 전자 메일 연결 제한을 사용하면 [!DNL Sales Connect] 관리자가 Gmail 또는 [!DNL Exchange]을(를) 배달 채널로 사용할 때 전자 메일의 전송 속도를 구성할 수 있으므로 전자 메일이 배달 채널 공급자에게 전달되는 속도가 적용된 제한을 초과하지 않습니다.

## 공지

* **Marketo Sky 사용 중단**: 차세대 사용자 환경을 제공하기 위해 리소스를 집중하기 때문에 3월에는 Marketo Sky을 더 이상 사용할 수 없습니다. 현재 Marketo Sky에만 적용되는 기능에 대한 액세스를 유지하기 위한 노력으로 에셋 만료 및 스마트 캠페인 우선 순위 재정의를 클래식 경험으로 가져오고 있습니다. 자세한 내용을 보려면 [여기를 클릭하세요](https://nation.marketo.com/t5/the-modern-ux/marketo-sky-deprecation-notice/ba-p/320115#M33).

**_제품 릴리스 웨비나_**

[2022년 3월 및 5월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_March_May_Release_Webinar_DemandPage.html){target="_blank"}

## 2022년 5월 {#may}

아래에는 2022년 5월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2022년 5월 6일**&#x200B;에 릴리스되기 시작하며, 이후 몇 주 동안 남은 기능의 단계적 롤아웃이 적용됩니다(달리 지정되지 않은 경우).

## 기본 CRM 통합 {#native-crm-integration}

**[기본 Veeva CRM 통합](/help/marketo/product-docs/crm-sync/veeva-crm-sync/understanding-the-veeva-crm-sync.md){target="_blank"}(제한된 가용성)**: 기본 통합을 통해 Veeva CRM과 Marketo Engage 간의 활동을 동기화하여 의료 전문가와의 참여를 향상시키십시오. 이러한 통합을 통해 마케터는 의료 전문가를 위한 보다 개인화되고 원활한 크로스 채널 경험을 만들 수 있습니다. 참여에 관심이 있는 경우 Customer Success Manager에게 문의하십시오.

## 크로스 채널 오케스트레이션

[!DNL Dynamic Chat]&#x200B;**에 대한**&#x200B;챗봇 이벤트: 웹 방문자에 대한 자세한 동작 데이터(예: 페이지 체류 시간, 사이트 체류 시간 및 페이지 스크롤 백분율)를 활용하여 채팅 대화 상자가 표시되는 시기를 정의합니다.

[!DNL Dynamic Chat]&#x200B;**용** PDF 포함: PDF를 채팅 대화 상자에 포함하여 참여를 늘리고 의미 있는 콘텐츠를 공유하며 참여 활동 추적을 통해 콘텐츠 성능을 측정합니다.

[!DNL Dynamic Chat]&#x200B;**에 대한**&#x200B;확장 언어 지원: 이제 프랑스어, 독일어, 일본어, 포르투갈어 및 스페인어로도 [!DNL Dynamic Chat] 사용자 인터페이스를 사용할 수 있습니다. 이러한 언어로 채팅 대화 상자를 구성할 수도 있습니다.

**[!DNL Dynamic Chat]**&#x200B;에 대한 URL 제외: 타깃팅 기준에서 특정 URL을 제외하는 기능으로 웹 페이지 [!DNL Dynamic Chat]의 표시 항목을 제어합니다.

**[전자 메일 보트 활동 필터링 개선 사항](/help/marketo/product-docs/administration/email-setup/filtering-email-bot-activity.md){target="_blank"}**: 기존 IAB 목록 일치 식별뿐 아니라 숨겨진 링크 사용자 에이전트 또는 IP 및 근접 패턴을 기반으로 보트 동작을 식별하는 기능을 사용하여 데이터베이스의 상태를 계속 보호합니다. 각 유형에 대해 식별된 보트 활동의 수를 이해할 수 있는 보트 활동 통계를 봅니다.

**[전자 메일 추적 링크에 대한 STS 헤더](/help/marketo/product-docs/administration/settings/email-tracking-link-headers.md){target="_blank"}**: 추적된 링크에 대한 트래픽이 항상 안전하도록 보안 전송 보안 헤더를 적용하는 기능으로 보안 모범 사례를 충족합니다.

## 차세대 경험

**전환 스위치를 차세대 환경으로 기본 설정**: 전환 스위치는 사용 가능한 모든 화면에서 새로운 환경으로 기본 설정되므로 사용자가 업데이트된 디자인과 유용성 개선 사항을 쉽게 확인할 수 있습니다.

**차세대 환경에서 업데이트된 화면**:

[!UICONTROL Design Studio] 내의 전자 메일 템플릿 세부 정보 보기를 차세대 환경에 제공하고 있습니다. 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공합니다.

## Experience Automated

**셀프 서비스 흐름 단계(연속 베타)**: 스마트 캠페인에 사용할 사용자 지정 흐름 단계를 작성하는 기능을 사용하여 Marketo Engage과 스택의 나머지 부분 간의 연결을 확장합니다. Marketo Engage 사용자와 파트너 모두 이 기능을 활용하여 트리거, 일괄 처리 및 실행 가능한 캠페인에서 외부 웹 서비스를 사용할 수 있습니다(트리거 캠페인에만 사용할 수 있는 웹 후크와 대조적으로).

## API 개선 사항

* **CRM 사용 구독에 대한 확장된 API 액세스**: 사용자가 Marketo Engage에서 회사, 기회 및 영업 직원을 검색할 수 있도록 CRM 동기화를 사용하도록 설정한 구독에 대한 API 액세스를 확장하고 있습니다.
* **Forms에서 &quot;숨겨진&quot; 데이터 형식 지원**: API를 통해 숨겨진 양식 필드를 관리할 수 있는 기능을 제공합니다.
* **규칙을 통해 isNot Form에 대한 여러 비교 값 지원**: 다른 필드의 값이 지정된 목록에 있는 값 중 하나가 아닌지 여부를 기준으로 양식 필드의 가시성을 관리합니다.
* **별도로 선택 목록에서 표시 값과 제출된 값을 설정할 수 있도록 허용**: 필드에 표시 값과 제출된 값을 별도로 설정합니다. 예를 들어 호텔 이름을 표시하지만 내부 ID를 백엔드에 제출합니다.
* **전자 메일 만들기 또는 업데이트 시 열기 추적을 사용하지 않도록 설정할 수 있도록 허용**: 열기 추적을 사용하지 않는 전자 메일을 만듭니다.

## 공지

**전자 메일 확인 및 고유성**: 4월부터 전자 메일 확인 롤아웃이 시작됩니다. 이때 Marketo Engage 사용자 이메일 주소에는 확인 및 고유성이 필요합니다(API 전용 사용자에게는 적용되지 않음). 이메일 확인을 통해 구독이 활성화되면 디렉터리 서비스 인증된 사용자의 이메일이 자동으로 확인됩니다.

&quot;[!UICONTROL Login in Invite User Dialog]&quot; 기능을 사용하거나 여러 사용자와 연결된 하나의 전자 메일이 있는 구독에 대한 전자 메일 확인은 5월 릴리스와 일치합니다. 여러 사용자와 연결된 하나의 이메일이 있는 구독은 이메일 확인을 통해 활성화되며 이러한 사용자가 충돌을 해결하고 사용자당 고유한 이메일을 사용해야 합니다. &#39;사용자 초대 대화 상자에서 로그인&#39; 기능을 활성화하면 이 기능을 통해 초대된 사용자의 이메일 주소가 고유해야 합니다. 이 기능을 통해 초대된 API 전용 사용자의 경우 이메일 주소가 고유할 필요가 없습니다.

**보관 폴더 동작 변경**: 이 릴리스에서는 보관 폴더에 새 자산을 만드는 기능을 트리 컨텍스트 메뉴에서 더 이상 사용할 수 없습니다. 새 에셋을 만들기 위한 메뉴 옵션은 모든 에셋에 대해 숨겨집니다. [여기에서 자세히 알아보십시오](https://nation.marketo.com/t5/product-discussions/archive-folder-change-in-may-2022-release/m-p/324369#M183235){target="_blank"}.

**_제품 릴리스 웨비나_**

[2022년 3월 및 5월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_March_May_Release_Webinar_DemandPage.html){target="_blank"}

## 2022년 6월 {#june}

아래에는 2022년 6월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

다음 기능은 **2022년 6월 24일**&#x200B;에 릴리스되기 시작하며, 이후 몇 주 동안 남은 기능의 단계적 롤아웃이 적용됩니다(달리 지정되지 않은 경우).

## 마케팅 데이터 환경

* **사용자 지정 개체에 대해 CreatedAt/UpdatedAt 필드 표시**: 사용자 세부 정보 화면에서 이러한 필드를 검사하여 추가 insight을 가져올 수 있습니다.

## 크로스 채널 오케스트레이션

* **개선된[!DNL Dynamic Chat]**&#x200B;의 스트림 Designer 사용 편의성: 드래그 앤 드롭할 필요 없이 스트림 Designer 캔버스에서 직접 카드를 추가하십시오. [!DNL Dynamic Chat] 인터페이스도 개선되어 개별 카드의 콘텐츠를 더 잘 볼 수 있습니다.

* **[!DNL Dynamic Chat]**&#x200B;에 대한 고급 약속 라우팅 규칙: [!DNL Dynamic Chat]에서는 대상 약속 라우팅에 대한 추가 옵션을 제공합니다. Marketo Engage 속성에 따라 라우팅할 에이전트 약속을 지정하여 리드가 적절한 에이전트로 라우팅되도록 합니다.

* [!DNL Dynamic Chat]&#x200B;**에 대한**&#x200B;고급 대화 상자 보고: 참여 및 전환 지표에 대한 새로운 데이터 시각화를 사용하여 [!DNL Dynamic Chat] 캠페인의 성과를 자세히 봅니다.

* **[!DNL Dynamic Chat]**&#x200B;에 대해 사용하지 않은 Marketo Engage 특성 동기화 해제: 사용되지 않는 [!DNL Dynamic Chat] 구독의 Marketo Engage 특성을 동기화하지 않으므로 데이터를 깔끔하게 정리하고 필요에 따라 다른 특성을 동기화할 수 있습니다.

## 차세대 경험

**새로운 전환 보기**: 이제 다음 보기를 차세대 환경에서 사용할 수 있습니다.

* [이메일 세부 정보 보기](/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md#email-details-view){target="_blank"}
* [이메일 목록 보기](/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md#email-list-view){target="_blank"}

## Experience Automated

* **전역 양식 필드 유효성 검사 규칙 제외**: 구독 센터 및 기타 비즈니스 크리티컬 워크플로우가 모든 값을 수락할 수 있도록 전역 양식 유효성 검사 규칙에서 특정 양식을 제외합니다.

* **셀프 서비스 흐름 단계**: 스마트 캠페인에 사용할 사용자 지정 흐름 단계를 작성하는 기능을 사용하여 Marketo Engage과 스택의 나머지 부분 간의 연결을 확장합니다. Marketo Engage 사용자와 파트너 모두 이 기능을 활용하여 트리거 캠페인에서만 사용할 수 있는 웹후크와 달리 트리거, 일괄 처리 및 실행 가능한 캠페인에서 외부 웹 서비스를 사용할 수 있습니다.

* **Munchkin 프로토콜 불가지론적 링크 추적**: 확장된 웹 동작 집합을 추적하기 위해 Munchkin에서 `tel` 및 `mailto` 링크 추적에 대한 지원을 확장합니다.

* **웹후크에 대한 추가 HTTP 메서드**: 웹 서비스와 상호 작용할 요청 유형으로 PUT, PATCH 및 DELETE을 지정합니다.

## [!DNL Sales Insight]

![(별)](assets/yellow-star.png)

* [!DNL Salesforce]&#x200B;**의**&#x200B;[!DNL Sales Insight] 사용 권한 집합: 관리자는 [!DNL Sales Insight] [!DNL Salesforce] 패키지의 일부인 Marketo 앱 사용 권한 집합을 통해 프로필 수준이 아닌 사용자 수준의 제한된 사용자 집합에 대한 [!DNL Sales Insight] 액세스 권한을 제공할 수 있습니다.

* **내 Marketo 타일 업데이트 - [!DNL Sales Insight] 작업**: Marketo 관리자(및 사용자가 지정한 사용자)는 이제 내 Marketo 페이지에 있는 새 [!DNL Sales Insight] 작업 타일을 통해 [!DNL Sales Insight] 작업 인스턴스로 빠르게 이동할 수 있습니다.

## [!DNL Sales Connect]

![(별)](assets/yellow-star.png)

* **[!DNL Salesforce]API 업데이트**: [!DNL Salesforce] 22년 여름 릴리스에서 API 레거시 버전 21 -30은 [!DNL Salesforce]에서 더 이상 지원되지 않습니다. 이 Marketo Engage 릴리스에서는 기존 API 버전을 사용하는 모든 [!DNL Sales Connect] 요청이 지원되는 버전 내에서 유지되도록 업데이트되었습니다. [!DNL Salesforce] API 사용 중지 계획에 대한 자세한 내용을 보려면 [여기](https://help.salesforce.com/s/articleView?language=en_US&type=1&id=000354473){target="_blank"}를 클릭하십시오.

## API 개선 사항

* **일괄 프로그램 구성원 추출 API에 대한 새로운 필터링 기능**: 프로그램 구성원 상태, updatedAt, cadence 또는 소진된 콘텐츠별로 필터링하여 추출된 데이터 집합을 구체화합니다.

* **일괄 프로그램 구성원 추출 API 개선 사항**: 처리량을 개선하기 위해 작업을 만드는 동안 최대 10개의 프로그램을 지정합니다.

## 공지

* **Forms 사용 중단 - Forms 1.0, 리드 캡처/저장 끝점 및 forms의 no-script 버전**: Forms 1.0 자산에 대한 지원이 2022년 10월까지 Marketo Engage에서 완전히 제거됩니다. 기존의 모든 Forms 1.0 자산이 작동하지 않습니다. Marketo Engage forms를 사용하려면 JavaScript이 랜딩 페이지 및 웹 사이트에 로드되어야 합니다.

**_제품 릴리스 웨비나_**

[2022년 6월 및 8월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_June_August_Release_Webinar_OnDemandPage.html){target="_blank"}

## 2022년 8월 {#august}

아래에는 2022년 8월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

다음 기능은 **2022년 8월 26일**&#x200B;에 단계적으로 롤아웃을 시작했습니다.

## 크로스 채널 오케스트레이션

* [!DNL Dynamic Chat]에 대해 게시된 모든 대화 상자를 한 번에 활성화/비활성화**: 단추를 눌러 [구성] 페이지에서 게시된 모든 대화 상자를 한 번에 전체적으로 활성화/비활성화합니다.

* [!DNL Dynamic Chat]&#x200B;**에 대한**&#x200B;사용자 지정 아바타: 사용자 지정 챗봇 아바타를 업로드하여 내 브랜드에 맞게 개인화할 수 있습니다.

* [!DNL Dynamic Chat]&#x200B;**에 대한**&#x200B;채팅 트랜스크립트: 모든 대화에 대한 채팅 트랜스크립트를 보고 각 웹 방문자가 관심을 갖는 내용에 대해 더 자세한 insight을 얻습니다.

## 차세대 경험

* **Adobe 브랜딩**: 새로운 Adobe Experience Cloud 브랜딩으로 편집자 및 개인 세부 정보 페이지의 모양과 느낌을 업데이트했습니다.

* **이동 대화 상자에 대상 폴더의 폴더 계층 구조 표시**: 각 폴더에 대한 폴더 계층 구조를 보면 자산을 더 쉽게 이동할 수 있으며 잘못된 폴더에 넣을 수 있는 가능성이 줄어듭니다.

* **[차세대 경험에서 업데이트된 Screens](/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md){target="_blank"}**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 경험에서 새로 고친 화면을 추가로 제공합니다.

   * 코드 조각 세부 사항
   * &quot;이미지 및 파일&quot; 세부 정보

>[!NOTE]
>
>예외적으로 마케팅 활동의 프로그램 내에서 자산을 폴더로 이동합니다. 프로그램 내의 폴더에는 중복 이름을 사용할 수 없으므로 이 이동 작업으로 폴더 계층 구조가 표시되지 않습니다.

## Experience Automated

* **[셀프 서비스 흐름 단계 - 프로그램 가져오기 개선 사항](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/flow-step-service.md){target="_blank"}**: 이제 동일한 서비스 공급자의 여러 인스턴스를 사용하고 해당 서비스 공급자와 호환되는 흐름 단계가 있는 프로그램을 가져올 수 있는 사용자 지정 흐름 단계로 프로그램 가져오기에 대한 지원이 개선되었습니다.

* **[!DNL Munchkin]- 확장된 링크 추적**: 확장된 웹 동작 집합을 추적하기 위해 Munchkin에서 `tel` 및 `mailto` 링크 추적에 대한 지원을 확장합니다.

* **Webhook 사용자 지정 헤더 표시**: 이제 Webhook 사용자 지정 헤더가 [!UICONTROL Admin] > [!UICONTROL Webhooks] 탭에 표시되므로 더 잘 표시할 수 있습니다.

* **CAPTCHA**: 들어오는 양식 트래픽을 평가할 때 [reCAPTCHA v3](/help/marketo/product-docs/demand-generation/forms/using-captcha/enable-captcha-in-marketo-forms.md){target="_blank"}을(를) 사용하여 양식 제출의 유효성을 평가합니다. 의심스러운 봇 트래픽을 자동으로 제외, 격리 또는 삭제하는 마케팅 워크플로우를 빌드합니다.

* **양식 승인 권한**: 다른 [!UICONTROL Design Studio] 자산과 함께 양식의 변경 내용을 승인할 수 있는 디자이너를 제어하는 새 권한입니다. 이렇게 하면 다른 디자이너가 승인 권한이 있는 다른 사람이 양식을 검토하지 않고 변경 사항을 양식에 푸시할 수 없습니다.

* **익명 병합 후 캠페인 재생을 항상 수행**: 익명 캠페인 재생이 완료되면 사용자 지정 필드 필터가 안정적으로 작동하도록 캠페인 재생 전에 익명 리드 병합이 발생합니다.

## 마케팅 데이터 환경

* **사용자 지정 개체 &quot;[!UICONTROL Used By]&quot; 필드의 UI 잘림 수정**: 이제 &quot;사용 중&quot;인 사용자 지정 개체 필드를 더 쉽게 식별하여 필요한 경우 사용자 지정 개체에서 필드를 삭제할 수 있습니다.

## API 개선 사항

* **일괄 프로그램 구성원 추출 API를 위한 새로운 필터링 기능**: 프로그램 구성원 상태, updatedAt, cadence 또는 소진된 콘텐츠별로 필터링하여 추출된 데이터 집합을 구체화합니다.

## [!DNL Sales Insight]

![(별)](assets/yellow-star.png)

* **[[!DNL Sales Insight] 와 통합 [!DNL Dynamic Chat]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md){target="_blank"}**: [!DNL Sales Insight] 패널에서 [!DNL Dynamic Chat]의 활동을 보고 예측에 이 새로운 데이터 포인트를 활용하십시오.

## 공지

**_제품 릴리스 웨비나_**

[2022년 6월 및 8월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_June_August_Release_Webinar_OnDemandPage.html){target="_blank"}

## 2022년 10월 {#october}

아래에는 2022년 10월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2022년 10월 14일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능의 상태를 아래에서 확인하십시오.

### 마케팅 데이터 환경

</br>

* **프로그램 구성원 사용자 지정 필드 동기화**: 프로그램 구성원에 대해 캡처된 확장 가능한 필드를 양방향으로 동기화하는 기능(예: 음식, 세션, 트랙 등과 같은 이벤트 등록 중 참석자 환경 설정) Salesforce의 Campaign 멤버 필드를 사용하는 경우입니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-field-sync.md">프로그램 멤버 사용자 정의 필드 동기화</a></td>
  </tr>
  </tbody>
</table>

* **Adobe Privacy Service 통합**: Privacy Service과 함께 사용하여 Experience Cloud 제품 전반에 걸친 데이터 개인정보 보호 규정 준수를 자동화합니다. 현재 이 서비스는 Adobe Identity Management 시스템에 온보딩한 Marketo Engage 고객만 사용할 수 있습니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md">Adobe Identity Management</a></td>
  </tr>
  </tbody>
</table>

### 차세대 경험

</br>

* **차세대 경험에서 업데이트된 Screens**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 경험에서 새로 고친 화면을 추가로 제공합니다.

   * 랜딩 페이지 템플릿 세부 정보
   * 이메일 템플릿 목록

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md">토글 스위치</a></td>
  </tr>
  </tbody>
</table>

* **전자 메일 템플릿 세부 정보의 향상된 사용 기능**: 새 경험에서 자산 상태, 마지막 수정자 및 마지막 수정자를 포함하여 전자 메일 템플릿을 사용하는 자산과 관련된 추가 정보를 볼 수 있습니다. 에셋에서 사용하는 목록을 검색, 정렬 및 필터링할 수도 있습니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td>해당 사항 없음</td>
  </tr>
  </tbody>
</table>

* **보고서 에셋 필터 모달**: 구성 메뉴에 새 에셋 트리와 생성 및 수정 날짜 필터를 표시하는 보고서 구성 모달의 새로운 디자인입니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td>해당 사항 없음</td>
  </tr>
  </tbody>
</table>

### API 개선 사항

</br>

* **일괄 리드 가져오기: 영업 사원 연결**: 일괄 리드 가져오기 프로세스 동안 영업 사원과 리드를 연결할 수 있도록 리드 REST API와 동등하므로 복잡성과 필요한 API 호출 수가 줄어듭니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="https://developer.adobe.com/marketo-apis/api/mapi/#tag/Bulk-Import-Leads">벌크 리드 가져오기</a></td>
  </tr>
  </tbody>
</table>

### Sales Insight

</br>

![(별)](assets/yellow-star.png)

* **Dynamic Chat과 Insight 통합**: 이제 Insights Dashboard에 주별 요약 및 세부 사항 카드와 함께 스마트 그리드의 Dynamic Chat 활동이 포함됩니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md">Dynamic Chat 통합</a></td>
  </tr>
  </tbody>
</table>

## 애자일 릴리스 기능

다음 기능은 애자일 형식을 따르며, 표준 릴리스 날짜 이전 또는 이후의 다양한 날짜에 릴리스됩니다. 각 기능의 상태를 아래에서 확인하십시오.

* **Dynamic Chat용 자동 정렬 대화 상자 스트림**: [자동 정렬]을 통해 단추를 눌러 캔버스의 모든 내용을 깔끔하고 읽기 쉬운 형식으로 구성하여 복잡한 대화 상자 캔버스를 개선합니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/stream-designer.md#stream-designer-icons">스트림 Designer 아이콘</a></td>
  </tr>
  </tbody>
</table>

* **Dynamic Chat의 모임 링크**: 방문자에게 보내는 모든 일정 초대에 Google 및 Outlook의 팀 또는 모임 링크를 자동으로 포함하는 옵션입니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/agent-settings.md">캘린더</a></td>
  </tr>
  </tbody>
</table>

* **Dynamic Chat에 대한 추가 데이터 형식 지원**: 3개의 새로운 데이터 형식(부울, 정수, 부동 소수점)을 사용하면 점수를 기반으로 타깃팅하거나 방문자에게 예/아니요 질문을 하는 것과 같은 작업에 대해 Dynamic Chat의 더 많은 기존 Marketo Engage 필드를 활용할 수 있습니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td>해당 사항 없음</td>
  </tr>
  </tbody>
</table>

## 공지

* **Forms 1.0**: 10월 릴리스를 통해 Forms 1.0의 사용이 중단됩니다. Forms 1.0 Assets는 더 이상 Marketo Engage에 데이터를 제출할 수 없으며 시도하면 오류를 반환합니다.

* **스크립트가 없는 Forms**: 브라우저에서 Javascript가 비활성화되어 있으면 Forms이 더 이상 작동하지 않습니다. 양식 제출을 사용하려면 Javascript를 활성화해야 합니다.
