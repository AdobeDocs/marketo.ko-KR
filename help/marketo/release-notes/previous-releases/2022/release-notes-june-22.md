---
description: 릴리스 노트 - 2022년 6월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2022년 6월
exl-id: f4438ea8-1657-4955-9f9f-640b3ecf5caa
feature: Release Information
source-git-commit: cf4dcb6a316eba631ccb73a991c09e83c80b82ca
workflow-type: tm+mt
source-wordcount: '640'
ht-degree: 0%

---

# 릴리스 노트: 2022년 6월 {#release-notes-june-22}

아래에는 2022년 6월 릴리스에 포함된 모든 기능이 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별표로 표시되는 기능(![별](assets/yellow-star.png))는 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

다음 기능에 대한 릴리스가 시작됩니다. **2022년 6월 24일**: 이후 주에 걸쳐 남은 기능의 단계적 롤아웃 포함(별도로 지정하지 않는 한).

## 마케팅 데이터 환경 {#marketing-data-environment}

* **사용자 지정 개체에 대해 CreatedAt/UpdatedAt 필드 표시**: 개인 세부 정보 화면에서 이러한 필드를 검사하여 추가 통찰력을 얻을 수 있는 기능을 제공합니다.

## 크로스 채널 오케스트레이션 {#cross-channel-orchestration}

* **Dynamic Chat을 위한 스트림 디자이너 유용성 개선**: 드래그하여 놓을 필요 없이 스트림 디자이너 캔버스에서 직접 카드를 추가합니다. Dynamic Chat 인터페이스도 개선되어 개별 카드의 콘텐츠를 더 잘 볼 수 있습니다.

* **Dynamic Chat에 대한 고급 약속 공정순서 규칙**: Dynamic Chat은 타깃팅된 약속 라우팅에 대한 추가 옵션을 제공합니다. Marketo Engage 속성에 따라 라우팅할 에이전트 약속을 지정하여 리드가 적절한 에이전트로 라우팅되도록 합니다.

* **Dynamic Chat을 위한 고급 대화 상자 보고**: 참여 및 전환 지표에 대한 완전히 새로운 데이터 시각화를 사용하여 Dynamic Chat 캠페인의 성능을 자세히 확인합니다.

* **Dynamic Chat에 대해 사용하지 않은 Marketo Engage 속성 동기화 해제**: 사용되지 않는 Dynamic Chat 구독의 Marketo Engage 속성을 동기화하지 않으므로 데이터를 깔끔하게 정리하고 필요한 경우 대체 속성을 동기화할 수 있습니다.

## 차세대 경험

**새로운 전환 스위치 보기**: 이제 차세대 경험에서 아래 보기를 사용할 수 있습니다.

* [이메일 세부 정보 보기](/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md#email-details-view){target="_blank"}
* [전자 메일 목록 보기](/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md#email-list-view){target="_blank"}

## Experience Automated {#experience-automation}

* **글로벌 양식 필드 유효성 검사 규칙 제외**: 구독 센터 및 기타 비즈니스 크리티컬 워크플로우가 모든 값을 수락할 수 있도록 글로벌 양식 유효성 검사 규칙에서 특정 양식을 제외합니다.

* **셀프서비스 플로우 단계**: 스마트 캠페인에 사용할 사용자 지정 흐름 단계를 작성하는 기능을 통해 Marketo Engage과 스택의 나머지 부분 간의 연결을 확장합니다. Marketo Engage 사용자와 파트너 모두 이 기능을 활용하여 트리거 캠페인에서만 사용할 수 있는 웹후크와 달리 트리거, 일괄 처리 및 실행 가능한 캠페인에서 외부 웹 서비스를 사용할 수 있습니다.

* **Munchkin 프로토콜 Agnostic 링크 추적**: 추적 지원 확장 `tel` 및 `mailto` Munchkin과 연결하여 확장된 웹 비헤이비어 세트를 추적합니다.

* **웹후크에 대한 추가 HTTP 메서드**: 웹 서비스와 상호 작용할 요청 유형으로 PUT, PATCH 및 DELETE을 지정합니다.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **Salesforce의 Sales Insight 권한 집합**: 관리자는 Sales Insight Salesforce 패키지의 일부인 Marketo 앱 권한 집합을 통해 프로필 수준이 아닌 사용자 수준의 제한된 직원 집합에 Sales Insight 액세스 권한을 제공할 수 있습니다.

* **내 Marketo 타일 업데이트 - Sales Insight 작업**: Marketo 관리자(및 사용자가 지정한 사용자)는 이제 내 Marketo 페이지에 있는 새 Sales Insight 작업 타일을 통해 Sales Insight 작업 인스턴스로 빠르게 이동할 수 있습니다.

## 영업 연결 {#sales-connect}

![(별)](assets/yellow-star.png)

* **Salesforce API 업데이트**: Salesforce 22년 여름 릴리스를 통해 API 레거시 버전 21 -30은 더 이상 Salesforce에서 지원되지 않습니다. 이 Marketo Engage 릴리스에서는 기존 API 버전을 사용하는 모든 Sales Connect 요청이 지원되는 버전 내에서 유지되도록 업데이트되었습니다. Salesforce API 사용 중지 계획에 대한 자세한 내용을 보려면 [여기](https://help.salesforce.com/s/articleView?language=en_US&amp;type=1&amp;id=000354473){target="_blank"}.

## API 개선 사항 {#api-enhancements}

* **벌크 프로그램 멤버 추출 API에 대한 새로운 필터링 기능**: 프로그램 멤버십 상태, updatedAt, 케이던스 또는 소진된 콘텐츠별로 필터링하여 추출된 데이터 세트를 구체화합니다.

* **벌크 프로그램 멤버 추출 API 개선 사항**: 처리량을 향상시키기 위해 작업 생성 중 최대 10개의 프로그램을 지정합니다.

## 공지 {#announcements}

* **Forms 사용 중단 - Forms 1.0, 리드 캡처/저장 엔드포인트 및 no-script 버전의 forms**: Forms 1.0 자산에 대한 지원은 2022년 10월까지 Marketo Engage에서 완전히 제거됩니다. 기존의 모든 Forms 1.0 자산이 작동하지 않습니다. Marketo Engage 양식을 사용하려면 랜딩 페이지 및 웹 사이트에 JavaScript를 로드해야 합니다.

**_제품 릴리스 웨비나_**

[2022년 6월 및 8월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_June_August_Release_Webinar_OnDemandPage.html){target="_blank"}
