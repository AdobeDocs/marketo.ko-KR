---
unique-page-id: 1147082
description: 개인 삭제 - Marketo 문서 - 제품 설명서
title: 사용자 삭제
exl-id: 40039444-9b2a-4b80-93bc-7da3d6e9475c
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '113'
ht-degree: 3%

---

# 사용자 삭제 {#delete-person}

오류가 있는 사람들이 때로 데이터베이스에 들어갑니다. 개인 삭제 플로우 단계에서는 해당 항목을 제거할 수 있습니다.

![](assets/delete-person-1.png)

>[!CAUTION]
>
>사용자를 삭제하면 개인의 이전 RCE 데이터도 모두 삭제됩니다. 실행을 취소할 수 없습니다.

1. 흐름 단계에서 드래그하면 CRM에서도 삭제되도록 자동으로 설정됩니다.

   ![](assets/delete-person-2.png)

1. 다음과 같이 CRM이 아닌 Marketo Engage에서 삭제할 수 있습니다.

   ![](assets/delete-person-3.png)

>[!NOTE]
>
>CRM에서 사용자 제거 _은(는)[!DNL Salesforce]_&#x200B;에서만 작동합니다. Marketo에서 사용자를 삭제하고 [!DNL Salesforce]에 유지하도록 선택하면 해당 [!DNL Salesforce] 레코드가 업데이트되면 Marketo에 다시 만들어집니다.
