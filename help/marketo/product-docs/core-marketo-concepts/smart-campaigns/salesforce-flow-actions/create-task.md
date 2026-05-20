---
unique-page-id: 1147017
description: 흐름 단계에서 Salesforce 작업을 만드는 방법을 알아봅니다. 누군가가 플로우를 입력하면 리드 소유자를 위한 작업을 만듭니다.
title: 작업 만들기
exl-id: c484d913-1fd8-4716-8caa-0bf318218ca1
feature: Smart Campaigns, Salesforce Integration
TQID: https://experienceleague.adobe.com/RJ5nZrVvURtgXEWWZwL2xXzlYOhWjKGSbX-MFTWCwzg
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 126
ht-degree: 3%

---

# 작업 만들기 {#create-task}

마케터는 거래 성사에 도움이 되는 정보를 보유하고 있습니다. 작업을 만들어 수행할 작업과 수행할 시기를 알릴 수 있습니다.

![](assets/create-task-1.png)

>[!NOTE]
>
>Marketo 동기화 사용자가 작업을 만들 때 **[!UICONTROL Due In]**&#x200B;은(는) Salesforce에서 작업을 만드는 데 필요한 필드입니다. Marketo은 값이 없는 경우 기본적으로 5일을 입력합니다.

기본적으로 흐름 단계는 다음과 같이 표시됩니다.

![](assets/create-task-2.png)

원하는 방식으로 작업을 만들려면 모든 필드를 사용자 지정합니다.

![](assets/create-task-3.png)

>[!TIP]
>
>**[!UICONTROL Subject]** 및 **[!UICONTROL Description]**&#x200B;에서 `{{lead.tokens}}`, `{{company.tokens}}`, `{{campaign.tokens}}` 및 `{{system.tokens}}`을(를) 사용할 수 있습니다. 자세한 내용은 [흐름 단계의 토큰](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md){target="_blank"}을 참조하세요.
