---
description: 릴리스 노트 - 2022년 6월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2022년 6월
exl-id: f4438ea8-1657-4955-9f9f-640b3ecf5caa
feature: Release Information
source-git-commit: ecd225af3ecfd7cb9159faf5a9d384d47ee6312c
workflow-type: tm+mt
source-wordcount: '600'
ht-degree: 0%

---

# 릴리스 노트: 2022년 6월 {#release-notes-june-22}

아래에는 2022년 6월 릴리스에 포함된 모든 기능이 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별(![별](assets/yellow-star.png))로 표시되는 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

다음 기능은 **2022년 6월 24일**&#x200B;에 릴리스되기 시작하며, 이후 몇 주 동안 남은 기능의 단계적 롤아웃이 적용됩니다(달리 지정되지 않은 경우).

## 마케팅 데이터 환경 {#marketing-data-environment}

* **사용자 지정 개체에 대해 CreatedAt/UpdatedAt 필드 표시**: 사용자 세부 정보 화면에서 이러한 필드를 검사하여 추가 insight을 가져올 수 있습니다.

## 크로스 채널 오케스트레이션 {#cross-channel-orchestration}

* **개선된[!DNL Dynamic Chat]**&#x200B;의 스트림 Designer 사용 편의성: 드래그 앤 드롭할 필요 없이 스트림 Designer 캔버스에서 직접 카드를 추가하십시오. [!DNL Dynamic Chat] 인터페이스도 개선되어 개별 카드의 콘텐츠를 더 잘 볼 수 있습니다.

* **[!DNL Dynamic Chat]**&#x200B;에 대한 고급 약속 라우팅 규칙: [!DNL Dynamic Chat]에서는 대상 약속 라우팅에 대한 추가 옵션을 제공합니다. Marketo Engage 속성에 따라 라우팅할 에이전트 약속을 지정하여 리드가 적절한 에이전트로 라우팅되도록 합니다.

* [!DNL Dynamic Chat]**에 대한**&#x200B;고급 대화 상자 보고: 참여 및 전환 지표에 대한 새로운 데이터 시각화를 사용하여 [!DNL Dynamic Chat] 캠페인의 성과를 자세히 봅니다.

* **[!DNL Dynamic Chat]**&#x200B;에 대해 사용하지 않은 Marketo Engage 특성 동기화 해제: 사용되지 않는 [!DNL Dynamic Chat] 구독의 Marketo Engage 특성을 동기화하지 않으므로 데이터를 깔끔하게 정리하고 필요에 따라 다른 특성을 동기화할 수 있습니다.

## 차세대 경험

**새로운 전환 보기**: 이제 다음 보기를 차세대 환경에서 사용할 수 있습니다.

* [전자 메일 세부 정보 보기](/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md#email-details-view){target="_blank"}
* [전자 메일 목록 보기](/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md#email-list-view){target="_blank"}

## Experience Automated {#experience-automation}

* **전역 양식 필드 유효성 검사 규칙 제외**: 구독 센터 및 기타 비즈니스 크리티컬 워크플로우가 모든 값을 수락할 수 있도록 전역 양식 유효성 검사 규칙에서 특정 양식을 제외합니다.

* **셀프 서비스 흐름 단계**: 스마트 캠페인에 사용할 사용자 지정 흐름 단계를 작성하는 기능을 사용하여 Marketo Engage과 스택의 나머지 부분 간의 연결을 확장합니다. Marketo Engage 사용자와 파트너 모두 이 기능을 활용하여 트리거 캠페인에서만 사용할 수 있는 웹후크와 달리 트리거, 일괄 처리 및 실행 가능한 캠페인에서 외부 웹 서비스를 사용할 수 있습니다.

* **Munchkin 프로토콜 불가지론적 링크 추적**: 확장된 웹 동작 집합을 추적하기 위해 Munchkin에서 `tel` 및 `mailto` 링크 추적에 대한 지원을 확장합니다.

* **웹후크에 대한 추가 HTTP 메서드**: 웹 서비스와 상호 작용할 요청 유형으로 PUT, PATCH 및 DELETE을 지정합니다.

## [!DNL Sales Insight] {#sales-insight}

![(별)](assets/yellow-star.png)

* [!DNL Salesforce]**의**[!DNL Sales Insight] 사용 권한 집합: 관리자는 [!DNL Sales Insight] [!DNL Salesforce] 패키지의 일부인 Marketo 앱 사용 권한 집합을 통해 프로필 수준이 아닌 사용자 수준의 제한된 사용자 집합에 대한 [!DNL Sales Insight] 액세스 권한을 제공할 수 있습니다.

* **내 Marketo 타일 업데이트 - [!DNL Sales Insight] 작업**: Marketo 관리자(및 사용자가 지정한 사용자)는 이제 내 Marketo 페이지에 있는 새 [!DNL Sales Insight] 작업 타일을 통해 [!DNL Sales Insight] 작업 인스턴스로 빠르게 이동할 수 있습니다.

## [!DNL Sales Connect] {#sales-connect}

![(별)](assets/yellow-star.png)

* **[!DNL Salesforce]API 업데이트**: [!DNL Salesforce] 22년 여름 릴리스에서 API 레거시 버전 21 -30은 [!DNL Salesforce]에서 더 이상 지원되지 않습니다. 이 Marketo Engage 릴리스에서는 기존 API 버전을 사용하는 모든 [!DNL Sales Connect] 요청이 지원되는 버전 내에서 유지되도록 업데이트되었습니다. [!DNL Salesforce] API 사용 중지 계획에 대한 자세한 내용을 보려면 [여기](https://help.salesforce.com/s/articleView?language=en_US&type=1&id=000354473){target="_blank"}를 클릭하십시오.

## API 개선 사항 {#api-enhancements}

* **일괄 프로그램 구성원 추출 API에 대한 새로운 필터링 기능**: 프로그램 구성원 상태, updatedAt, cadence 또는 소진된 콘텐츠별로 필터링하여 추출된 데이터 집합을 구체화합니다.

* **일괄 프로그램 구성원 추출 API 개선 사항**: 처리량을 개선하기 위해 작업을 만드는 동안 최대 10개의 프로그램을 지정합니다.

## 공지 {#announcements}

* **Forms 사용 중단 - Forms 1.0, 리드 캡처/저장 끝점 및 forms의 no-script 버전**: Forms 1.0 자산에 대한 지원이 2022년 10월까지 Marketo Engage에서 완전히 제거됩니다. 기존의 모든 Forms 1.0 자산이 작동하지 않습니다. Marketo Engage forms를 사용하려면 JavaScript이 랜딩 페이지 및 웹 사이트에 로드되어야 합니다.

**_제품 릴리스 웨비나_**

[2022년 6월 및 8월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_June_August_Release_Webinar_OnDemandPage.html){target="_blank"}
