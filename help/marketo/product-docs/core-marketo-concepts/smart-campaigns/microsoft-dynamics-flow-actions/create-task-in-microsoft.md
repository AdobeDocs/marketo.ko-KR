---
unique-page-id: 37356429
description: Microsoft - Marketo 문서 - 제품 설명서에서 작업 만들기
title: Microsoft에서 작업 만들기
exl-id: b9ae425b-edf1-4aae-92f4-e7c6cf647cdc
feature: Smart Campaigns, Microsoft Dynamics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---

# Microsoft에서 작업 만들기 {#create-task-in-microsoft}

마케터는 거래 성사에 도움이 되는 정보를 보유하고 있습니다. 작업을 만들어 수행할 작업과 수행할 시기를 알릴 수 있습니다.

Microsoft에서 작업 만들기 는 Microsoft의 사용자(잠재 고객 또는 연락처)와 관련된 활동에 작업을 만듭니다.

>[!NOTE]
>
>이 흐름 단계는 **트리거와 함께 사용할 때만 작동합니다.**, 스마트 캠페인에서 필터 아님.

기본적으로 흐름 단계는 다음과 같이 표시됩니다.

![](assets/msd1.png)

>[!NOTE]
>
>Marketo 동기화 사용자가 작업을 만들 때, **기한:** 은(는) Microsoft에서 작업을 생성하는 데 필요한 필드입니다. Marketo은 값을 입력하지 않으면 기본적으로 5일을 입력합니다.

원하는 방식으로 작업을 만들려면 모든 필드를 사용자 지정합니다.

![](assets/msd2.png)

>[!NOTE]
>
>흐름 액션의 작업에 지정된 &quot;상태&quot; 필드는 Microsoft의 &quot;상태 사유&quot; 필드를 업데이트합니다.

>[!TIP]
>
>다음을 사용할 수 있습니다. `{{lead.tokens}}`, `{{company.tokens}}`, `{{campaign.tokens}}` 및 `{{system.tokens}}` 다음에서 **제목** 및 **설명**. 다음을 참조하십시오 [흐름 단계용 토큰](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md) 을 참조하십시오.
