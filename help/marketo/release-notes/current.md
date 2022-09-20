---
description: 현재 릴리스 노트 - Marketo 문서 - 제품 설명서
title: 현재 릴리스 노트
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
source-git-commit: 4794c44db57b41f6d9358f7e6cc24a41dda68550
workflow-type: tm+mt
source-wordcount: '582'
ht-degree: 0%

---

# 릴리스 노트: 2022년 10월 일 {#release-notes-oct-22}

아래에는 10월 22일 릴리스에 포함된 모든 기능이 있습니다. 기능을 사용할 수 있는지 Adobe Marketo Engage 버전을 확인하십시오.

>[!AVAILABILITY]
>
>별로 표시된 기능(![별](assets/yellow-star.png))은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

다음 기능은에서 릴리스되기 시작합니다 **2022년 10월 14일**- 후속 주 동안 나머지 기능에 대한 단계적 롤아웃을 사용합니다(별도로 지정하지 않는 경우). 릴리스 기능과 정확한 날짜는 변경될 수 있습니다.

## 크로스 채널 오케스트레이션 {#cross-channel-orchestration}

* **Dynamic Chat의 대화 상자 스트림 자동 정렬**: 자동 정렬을 통해 단추 키를 눌러 캔버스의 모든 항목을 깨끗하고 읽기 쉬운 형식으로 구성하여 복잡한 대화 상자 캔버스를 개선합니다.

* **다이내믹 채팅에 대한 추가 데이터 유형 지원**: 3가지 새로운 데이터 유형(부울, 정수, 부동)을 사용하면 점수를 기반으로 타깃팅하거나 방문자 예/아니요 질문을 하는 등 다이내믹 채팅에서 더 기존 Marketo Engage 필드를 활용할 수 있습니다.

* **동적 채팅에 대한 모임 링크**: 방문자에게 전송되는 모든 달력 초대에 Google 및 Outlook용 팀 또는 모임 링크를 자동으로 포함하는 옵션입니다.

* **동적 채팅에 대해 예약된 모임 알림**: 영업 사원은 예약된 모임에 대한 자동 이메일 알림과 방문자의 차트 보트 상호 작용에 대한 관련 정보를 받습니다.

* **동적 채팅에 대한 역할 및 권한**: 관리자는 세부 권한을 사용하여 애플리케이션의 가시성과 사용을 제어하고 사용자 지정 사용자 역할을 만들 수 있습니다.

   * 전체 액세스 - 사용자는 기능을 최대한 활용할 수 있습니다(예: 게시 대화 상자, 색상 구성표 변경 등).
   * 읽기 전용 액세스 - 사용자는 정보를 볼 수 있지만 변경할 수는 없습니다(예: 대상 기준 또는 스트림 디자이너 참조, 변경 사항 없음)
   * 액세스 제한 - 사용자는 구성 또는 통합 섹션을 보거나 액세스할 수 없습니다

## 차세대 경험 {#next-generation-experience}

* **차세대 경험에서 업데이트된 화면**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 환경에서 새로 고친 추가 화면을 제공하고 있습니다.

   * 랜딩 페이지 템플릿 세부 정보
   * 전자 메일 템플릿 목록

* **이메일 템플릿 세부 정보의 탭에서 사용하는 향상된 기능**: 새 경험에서는 자산 상태, 마지막 수정 날짜 및 마지막 수정 사람 등 이메일 템플릿을 사용하는 자산과 관련된 추가 정보가 표시됩니다. 자산에서 사용하는 목록을 검색, 정렬 및 필터링할 수도 있습니다.

* **보고서 자산 필터 모델**: 보고서 구성 모듈에 대한 새 디자인이 구성 메뉴에 새 자산 트리를 표시하고 생성 및 수정된 날짜에 대한 필터를 표시합니다.

## 마케팅 데이터 환경 {#marketing-data-environment}

* **Adobe Privacy Service 통합**: Privacy Service과 결합하여 Experience Cloud 제품 전반에서 데이터 개인 정보 보호 규정을 자동으로 준수합니다. 현재 이 서비스는 [Identity Management Adobe](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md){target=&quot;_blank&quot;} 시스템.

* **프로그램 구성원 사용자 지정 필드 동기화**: 프로그램 구성원에 대해 캡처한 확장 가능한 필드(예: 음식, 세션, 트랙 등의 이벤트 등록 중 참석자 환경 설정)를 양방향 동기화할 수 있습니다.

## API 개선 사항 {#api-enhancements}

* **대량 리드 가져오기: 영업 사원 협회**: Lead REST API와 Parity를 사용하여 대량 리드 가져오기 프로세스 동안 Sales와 Lead를 연결할 수 있으므로 복잡성과 API 호출 수가 줄어듭니다.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **[Dynamic Chat와 Sales Insight 통합](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md){target=&quot;_blank&quot;}**: 이제 인사이트 대시보드에 주간 요약 및 세부 사항 카드와 함께 스마트 그리드의 동적 채팅 활동이 포함됩니다.

## 공지 {#announcements}

* **Forms 1.0**: Forms 1.0의 사용 중단은 10월 릴리스와 함께 완료됩니다. Forms 1.0 자산은 더 이상 Marketo Engage에 데이터를 제출할 수 없으며, 시도하는 경우 오류를 반환합니다.

* **No-Script Forms**: 브라우저에서 Javascript가 비활성화되면 Forms이 더 이상 작동하지 않습니다. 양식 제출 시 Javascript를 활성화해야 합니다.
