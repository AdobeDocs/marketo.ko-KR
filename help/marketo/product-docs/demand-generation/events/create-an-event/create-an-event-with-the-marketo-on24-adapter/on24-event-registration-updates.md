---
unique-page-id: 10096683
description: ON24 이벤트 등록 업데이트 - Marketing Docs - 제품 설명서
title: ON24 이벤트 등록 업데이트
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '282'
ht-degree: 0%

---


# ON24 이벤트 등록 업데이트 {#on-event-registration-updates}

## 수동으로 등록자 승인 {#manually-approving-registrants}

등록자에게 확인 이메일을 보내기 전에 등록자를 수동으로 승인할 수 있습니다. 이렇게 하려면 이 추가 단계를 처리하도록 캠페인을 구성해야 합니다.

1. 등록 트리거 캠페인의 경우:

   * 스마트 목록에서 트리거를 양식 채우기 **로 설정합니다**.
   * 플로우에서 진행 상태를 승인 **대기중으로 설정합니다**.

1. [이벤트]로 이동하고 [ **구성원** ] 탭을 클릭합니다. 이 탭에는 양식을 작성한 모든 사람이 표시됩니다. 상태는 승인 **대기중으로 설정되어야 합니다**.
1. 격자 상단에 있는 필터를 사용하여 승인 대기 중 상태의 사람만 **표시합니다**.
1. 등록할 사람을 선택합니다(Shift 키를 누른 상태에서 클릭, Control 키를 누른 상태에서 클릭 또는 모두 선택).
1. 메뉴에서 상태 **변경을 클릭합니다**. 등록됨 ****, **거부됨**&#x200B;또는 기타 해당 상태를 선택합니다.

## 등록 오류가 있는 사람 처리 {#handling-people-with-a-registration-error}

등록되지 않고 등록 오류로 설정되는 경우에도 너무 늦지 않습니다.

1. [멤버] 탭에서 [등록 오류] 상태의 사람 목록을 **필터링합니다**.
1. 계속하기 전에 통합 문제를 확인하고 수정했는지 확인하십시오(관리의 **이벤트 파트너** 아래에 오류가 없는지 확인).
1. 문제가 해결되면 등록 오류 상태의 모든 사람을 선택하고 상태를 **등록으로 변경합니다**. 이 경우 ON24에 다시 등록하려고 시도합니다.

## ON24에서 멤버 상태 업데이트 {#updating-member-status-from-on}

Marketing Cloud는 매일 밤 약 오후 11시에 참석 정보를 자동으로 가져옵니다. 참석 정보를 수동으로 업데이트하려면 [이벤트 작업] 아래에서 **웨비나** 제공자로부터 **새로 고침을 클릭합니다**.

>[!MORELIKETHIS]
>
>* [Marketing ON24 어댑터 이벤트 이해](understanding-marketo-on24-adapter-events.md)

>



