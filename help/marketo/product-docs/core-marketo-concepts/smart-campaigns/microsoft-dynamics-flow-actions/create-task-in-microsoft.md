---
unique-page-id: 37356429
description: Microsoft에서 작업 만들기 - Marketo 문서 - 제품 설명서
title: Microsoft에서 작업 만들기
exl-id: b9ae425b-edf1-4aae-92f4-e7c6cf647cdc
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---

# Microsoft에서 작업 만들기 {#create-task-in-microsoft}

마케터는 거래를 마감하는 데 매출을 지원할 수 있는 정보를 제공합니다. 작업을 만들어 그들이 무엇을 해야 하고 언제 해야 하는지를 알려주는 작업을 만들 수 있습니다.

Microsoft에서 작업 만들기 는 Microsoft의 개인(리드 또는 연락처)과 관련된 활동 아래에 작업을 만듭니다.

>[!NOTE]
>
>이 흐름 단계는 **트리거와 함께 사용할 때만 작동합니다**&#x200B;스마트 캠페인에서 필터 대신 필터를 사용합니다.

기본적으로 흐름 단계는 다음과 같습니다.

![](assets/msd1.png)

>[!NOTE]
>
>Marketo 동기화 사용자가 작업을 만드는 경우, **기한** 는 Microsoft에서 작업을 만드는 데 필요한 필드입니다. 값을 입력하지 않으면 Marketo은 기본적으로 5일 값을 입력합니다.

모든 필드를 사용자 지정하여 원하는 방식으로 작업을 만들 수 있습니다.

![](assets/msd2.png)

>[!NOTE]
>
>흐름 작업에서 작업에 대해 지정된 &quot;상태&quot; 필드는 필드를 업데이트합니다. Microsoft의 &quot;상태 이유&quot;입니다.

>[!TIP]
>
>다음을 사용할 수 있습니다 `{{lead.tokens}}`, `{{company.tokens}}`, `{{campaign.tokens}}` 및 `{{system.tokens}}` 에서 **제목** 및 **설명**. 자세한 내용은 [흐름 단계에 대한 토큰](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md) 자세한 내용
