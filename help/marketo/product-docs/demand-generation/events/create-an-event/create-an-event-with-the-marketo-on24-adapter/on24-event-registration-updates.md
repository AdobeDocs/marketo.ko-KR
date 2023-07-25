---
unique-page-id: 10096683
description: ON24 이벤트 등록 업데이트 - Marketo 문서 - 제품 설명서
title: ON24 이벤트 등록 업데이트
exl-id: 1d194ef2-b6ca-4e2d-b476-beb5bccd3c5f
feature: Events
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '282'
ht-degree: 0%

---

# ON24 이벤트 등록 업데이트 {#on-event-registration-updates}

## 등록자 수동 승인 {#manually-approving-registrants}

등록자에게 확인 이메일을 보내기 전에 수동으로 승인할 수 있습니다. 이렇게 하려면 이 추가 단계를 처리하도록 캠페인을 구성해야 합니다.

1. 등록 트리거 캠페인의 경우:

   * Smart List에서 트리거를 로 설정합니다. **양식 작성**.
   * 플로우에서 진행 상태를 다음으로 설정합니다. **승인 보류 중**.

1. Event 로 이동하고 **구성원** 탭. 이 탭에는 양식을 작성한 모든 사용자가 표시됩니다. 이 사용자의 상태는 다음으로 설정되어야 합니다. **승인 보류 중**.
1. 표 상단의 필터를 사용하여 다음 상태의 사용자만 볼 수 있습니다. **승인 보류 중**.
1. 등록할 사람을 선택합니다(Shift 키, Ctrl 키 또는 모두 선택).
1. 메뉴에서 **상태 변경**. 선택 **등록됨**, **거부됨**&#x200B;또는 기타 적용 가능한 상태.

## 등록 오류가 있는 사람 처리 {#handling-people-with-a-registration-error}

등록되지 않고 Registration Error 상태로 설정되는 경우 복구해도 늦지 않습니다.

1. 구성원 탭에서 상태의 사람 목록을 필터링합니다. **등록 오류**.
1. 계속하기 전에 통합 문제를 확인하고 해결했는지 확인하십시오( 아래에 오류가 없는지 확인). **이벤트 파트너** 관리자)에서 참조할 수 있었습니다.
1. 문제가 해결되면 등록 오류 상태의 모든 직원을 선택하고 상태를 (으)로 변경합니다. **등록됨**. 이렇게 하면 ON24에 다시 등록됩니다.

## ON24에서 구성원 상태 업데이트 {#updating-member-status-from-on}

Marketo은 매일 밤 태평양 표준시 오후 약 11시에 출석 정보를 자동으로 가져옵니다. 참석 정보를 수동으로 갱신하려면 **웨비나 공급자에서 새로 고침** 아래에 **이벤트 작업**.

>[!MORELIKETHIS]
>
>[Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}
