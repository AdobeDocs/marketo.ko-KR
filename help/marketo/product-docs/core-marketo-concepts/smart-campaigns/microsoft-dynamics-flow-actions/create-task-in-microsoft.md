---
unique-page-id: 37356429
description: Microsoft - Marketo 문서 - 제품 설명서에서 작업 만들기
title: Microsoft에서 작업 만들기
exl-id: b9ae425b-edf1-4aae-92f4-e7c6cf647cdc
feature: Smart Campaigns, Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 4%

---

# Microsoft에서 작업 만들기 {#create-task-in-microsoft}

마케터는 거래 성사에 도움이 되는 정보를 보유하고 있습니다. 작업을 만들어 수행할 작업과 수행할 시기를 알릴 수 있습니다.

Microsoft의 작업 만들기 는 [!DNL Microsoft]의 사용자(잠재 고객 또는 연락처)와 관련된 활동 아래에 작업을 만듭니다.

>[!NOTE]
>
>이 흐름 단계는 스마트 캠페인에서 필터가 아닌 트리거&#x200B;_와(과) 함께 사용할 때만_&#x200B;작동합니다.

기본적으로 흐름 단계는 다음과 같이 표시됩니다.

![](assets/create-task-in-microsoft-1.png)

>[!NOTE]
>
>Marketo 동기화 사용자가 작업을 만들 때 **[!UICONTROL Due In]**&#x200B;은(는) [!DNL Microsoft]에서 작업을 만드는 데 필요한 필드입니다. Marketo은 값을 입력하지 않으면 기본적으로 5일을 입력합니다.

원하는 방식으로 작업을 만들려면 모든 필드를 사용자 지정합니다.

![](assets/create-task-in-microsoft-2.png)

>[!NOTE]
>
>흐름 액션의 작업에 지정된 &quot;상태&quot; 필드가 [!DNL Microsoft]의 &quot;상태 이유&quot; 필드를 업데이트합니다.

>[!TIP]
>
>`{{lead.tokens}}` 및 `{{company.tokens}}`에서 `{{campaign.tokens}}`, `{{system.tokens}}`, **[!UICONTROL Subject]** 및 **[!UICONTROL Description]**&#x200B;을(를) 사용할 수 있습니다. 자세한 내용은 [흐름 단계의 토큰](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md){target="_blank"}을 참조하세요.
