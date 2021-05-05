---
description: 캠페인 실행 - Marketo 문서 - 제품 설명서
title: 캠페인 실행
translation-type: tm+mt
source-git-commit: 20a3bee9973340d7b772532d1be31fe745e5ffd7
workflow-type: tm+mt
source-wordcount: '711'
ht-degree: 0%

---

# 캠페인 실행 {#execute-campaign}

다른 캠페인과 마찬가지로 실행 캠페인에도 스마트 목록, 흐름 및 일정이 포함됩니다. 다른 캠페인과 달리 실제로 예약하거나 활성화하지는 않습니다. 캠페인 실행 흐름 단계를 통해 다른 캠페인에서만 호출할 수 있습니다. 실행 캠페인의 흐름 단계는 상위 캠페인과 함께 연속으로 실행됩니다(별도의 트리거 캠페인에서 동시에 실행되는 요청 캠페인과 달리).

>[!NOTE]
>
>실행 가능 캠페인은 항상 해당 캠페인을 호출하는 (상위) 캠페인의 하위 보고서입니다.

## 캠페인 실행 {#when-to-use-execute-campaign}을 사용해야 하는 경우

실행 캠페인으로 수행할 수 있는 작업은 많습니다. 리드 라우팅, 라이프사이클 관리, 점수 지정 등 일반적인 작업 작업을 용이하게 하도록 설계되었으며, 일괄 처리 또는 트리거 캠페인 내에서 동일한 워크플로우를 실행하는 데 사용할 수 있습니다.

별도의 흐름을 실행해야 할 때도 사용할 수 있지만, 후속 흐름 단계 선택(즉, 이렇게 하는 경우)에서 해당 흐름의 결과에 의존해야 합니다.

캠페인 실행은 [캠페인 요청](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/request-campaign.md)에 대한 개선으로, 인시리즈 또는 동시에 실행할 수 있지만 후자는 병렬로만 실행됩니다.

>[!NOTE]
>
>대기 단계 및 Webhook은 실행 가능한 캠페인과 호환되지 않습니다. 이러한 경우 캠페인 요청을 대신 사용해야 합니다.

## 실행 가능한 캠페인 {#how-to-create-an-executable-campaign}을 만드는 방법

1. 원하는 프로그램을 마우스 오른쪽 단추로 클릭하고 **새 스마트 캠페인**&#x200B;을 선택합니다.

   ![](assets/execute-campaign-1.png)

1. 이름을 지정하고 **실행 파일** 확인란을 선택하고 **만들기**&#x200B;를 클릭합니다.

   ![](assets/execute-campaign-2.png)

1. 다른 스마트 캠페인과 마찬가지로 스마트 목록 및 흐름을 정의합니다.

기존 스마트 캠페인을 복제할 수도 있습니다. 기존 실행 캠페인을 복제하는 경우 이름을 지정한 후에도 **실행 파일** 확인란을 선택해야 합니다.

>[!NOTE]
>
>트리거가 포함된 캠페인을 복제할 수 없습니다.

## 상위 캠페인 토큰 컨텍스트 사용 {#use-parent-campaign-token-context}

true로 설정하면 다음 토큰 컨텍스트가 하위 캠페인(실행 중인 컨텍스트)으로 전송됩니다.

* 내 토큰
* 캠페인 토큰
* 프로그램 토큰
* 구성원 토큰
* [트리거 토큰](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/interesting-moments/trigger-tokens-for-interesting-moments.md) (트리거된 캠페인에서 호출되는 경우)

**API 상호 작용**

API](https://developers.marketo.com/rest-api/assets/smart-campaigns/#batch)에서 예약 또는 요청 캠페인 [을 사용할 때 두 프로그램 모두 호출하려는 캠페인의 해당 토큰에 대해 설정된 값을 무시하는 내 토큰에 대한 값을 전달할 수 있습니다. 그러면 해당 캠페인이 다른 캠페인을 실행하고 &quot;상위 컨텍스트 사용&quot;을 True로 설정하면 애플리케이션에 설정된 값이 아닌 API를 통해 전달된 값을 사용합니다.

## 참고 사항 {#things-to-note}

* 스마트 목록은 자격이 없는 사람을 필터링합니다. 자격이 있는 사람이 되면, 만들어진 실행 캠페인 활동 레코드에 &quot;자격:TRUE&quot;(그리고 그렇지 않은 경우 FALSE)
* 예약 캠페인 자격 규칙 적용(예약 탭 아래의 스마트 캠페인 설정)
* 작업 영역에서 실행 캠페인을 호출할 수 없습니다.
* 실행 캠페인을 대상으로 하는 [흐름](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/remove-from-flow.md)에서 제거 흐름 작업을 사용하는 경우 하위 및 상위 캠페인을 모두 타게팅합니다
* 토큰 상속 활용 - 예를 들어 서로 다른 여러 자산에 의해 트리거되는 하나의 공통 점수 흐름 중 하나가 있는 경우 상위 캠페인에 대한 하위 점수 캠페인 값을 무시할 수 있도록 하위 캠페인과 상위 캠페인에서 기본 내 토큰 점수를 정의할 수 있습니다(시각적 예는 아래 참조).
* 현재 실행 캠페인 중첩은 사용할 수 없지만 향후 릴리스에 포함될 예정입니다.

>[!CAUTION]
>
>실행 가능한 캠페인에 대한 스마트 목록이 유효하지 않게 남겨두지 마십시오. 그렇지 않으면 **아무도**&#x200B;의 자격을 가지지 못합니다. 우수 사례는 별도의 스마트 목록 에셋을 만들고 이를 완전히 정의하고 유효한지 확인하는 것입니다. 그런 다음 실행 캠페인에서 &quot;스마트 목록 멤버&quot; 필터를 사용하여 스마트 목록 정의를 교체할 수 있습니다.

## 토큰 상속 예 {#token-inheritance-example}

다음은 하나의 실행 캠페인과 두 개의 상위 캠페인에서 토큰 상속의 시각적 예입니다.토큰 컨텍스트가 **True**&#x200B;로 설정된 경우이고, 다른 하나는 **False**&#x200B;입니다.

토큰화된 변경 점수가 있는 하위 캠페인입니다.

![](assets/execute-campaign-3.png)

하위 캠페인의 내 토큰입니다.

![](assets/execute-campaign-4.png)

**예 1 - True**

첫 번째 상위 캠페인의 캠페인 실행 흐름 단계에서 &quot;상위 캠페인 토큰 컨텍스트 사용&quot;은 **True**&#x200B;로 설정됩니다.

![](assets/execute-campaign-5.png)

상위 캠페인의 내 토큰.

![](assets/execute-campaign-6.png)

결과:점수가 +10으로 변경되었습니다.

![](assets/execute-campaign-7.png)

**예 2:False**

두 번째 상위 캠페인의 캠페인 실행 필터에서 &quot;상위 캠페인 토큰 컨텍스트 사용&quot;은 **False**&#x200B;로 설정됩니다.

![](assets/execute-campaign-8.png)

상위 캠페인의 내 토큰.

![](assets/execute-campaign-9.png)

결과:하위 캠페인의 점수 값 +0이 사용되었기 때문에 점수는 변경되지 않습니다.

![](assets/execute-campaign-10.png)
