---
unique-page-id: 10096683
description: ON24 이벤트 등록 업데이트 - Marketo 문서 - 제품 설명서
title: ON24 이벤트 등록 업데이트
exl-id: 1d194ef2-b6ca-4e2d-b476-beb5bccd3c5f
source-git-commit: 40cfdddac66b7cd90e33bedf11888a7c5e3b38c9
workflow-type: tm+mt
source-wordcount: '302'
ht-degree: 0%

---

# ON24 이벤트 등록 업데이트 {#on-event-registration-updates}

>[!IMPORTANT]
>
>2022년 8월부터 ON24는 더 이상 새로운 Marketo 통합을 지원하지 않습니다. 이 문서의 정보는 기존 사용자에게만 적용됩니다.

## 수동으로 등록 승인 {#manually-approving-registrants}

등록자가 확인 이메일을 보내기 전에 수동으로 승인할 수 있습니다. 이렇게 하려면 이 추가 단계를 처리하도록 캠페인을 구성해야 합니다.

1. 등록 트리거 캠페인의 경우:

   * Smart List에서 트리거를 **양식 채우기**.
   * 플로우에서 진행 상태 를 로 설정합니다. **승인 보류 중**.

1. 이벤트로 이동하고 **멤버** 탭. 이 탭에는 양식을 작성한 모든 사람이 표시됩니다. 상태는 로 설정되어야 합니다. **승인 보류 중**.
1. 그리드 맨 위에 있는 필터를 사용하여 상태가 **승인 보류 중**.
1. 등록할 사람을 선택합니다(Shift 키, Ctrl 키 또는 모두 선택).
1. 메뉴에서 **상태 변경**. 선택 **등록**, **거부됨**&#x200B;또는 기타 적용 가능한 상태

## 등록 오류가 있는 사람 처리 {#handling-people-with-a-registration-error}

사용자가 등록을 하지 않고 등록 오류 상태로 설정하면 복구하기에 너무 늦지 않습니다.

1. 멤버 탭에서 상태가 있는 사람 목록을 필터링합니다 **등록 오류**.
1. 계속하기 전에 통합 문제를 확인하고 해결했는지 확인하십시오(아래에 오류가 없는지 확인) **이벤트 파트너** 관리자).
1. 문제가 해결되면 등록 오류 상태를 가진 모든 사람을 선택하고 상태를 로 변경합니다. **등록**. 이렇게 하면 ON24에 다시 등록하려고 시도합니다.

## ON24에서 멤버 상태 업데이트 {#updating-member-status-from-on}

Marketo은 매일 밤 약 오후 11시에 참석 정보를 자동으로 가져옵니다. 참석 정보를 수동으로 업데이트하려면 **웨비나 공급자에서 새로 고침** 아래에 **이벤트 작업**.

>[!MORELIKETHIS]
>
>[Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md)
