---
unique-page-id: 557339
description: 중복 사용자 찾기 및 병합 - Marketing To Docs - 제품 문서
title: 중복 인물 찾기 및 병합
translation-type: tm+mt
source-git-commit: 07f713ece9832b7696451001f61c6a3b45b4a94a
workflow-type: tm+mt
source-wordcount: '429'
ht-degree: 0%

---


# 중복 인물 찾기 및 병합 {#find-and-merge-duplicate-people}

새 사용자가 시스템에 입력되면 Marketing에서 자동으로 중복 제거 기능을 사용할 수 있습니다. 그러나 CRM에서 처음에 Marketing To로 중복 항목을 보냈을 수 있습니다. 병합하는 방법을 소개합니다.

>[!NOTE]
>
>Salesforce 또는 Microsoft Dynamics 동기화에 대해 또는 수동으로 사람을 입력할 때 Marketing To는 자동으로 중복 제거 기능을 제공하지 않습니다.

>[!PREREQUISITES]
>
>중복 항목을 찾아 병합하면 [내장/시스템 스마트 목록](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-built-in-system-smart-lists.md)이(가) 사용됩니다.

## 중복 항목 찾기 {#find-duplicates}

1. **데이터베이스** 영역으로 이동합니다.

   ![](assets/db.png)

   >[!CAUTION]
   >
   >Salesforce 사람 계정을 사용하는 경우 Marketing에서 사람을 병합하면 작동하지 않을 수 있습니다. 가능하면 Salesforce의 레코드를 병합하십시오.

1. **가능한 중복 항목** 시스템 스마트 목록을 선택하고 **사람** 탭을 클릭합니다.

   ![](assets/two.png)

   >[!NOTE]
   >
   >[사용자 지정 로직을 사용하여 중복 인물 찾기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-duplicate-people-with-custom-logic.md)도 할 수 있습니다.

## 수동으로 사람 병합 {#merge-people-manually}

>[!CAUTION]
>
>사람을 병합할 때, 유실된 사람에게 Marketing 사용자 지정 개체가 있는 경우, 이 개체는 우승한 사람과 다시 연결되지는 **않습니다.** 병합을 수행하기 전에 사용자 지정 개체를 다시 부모하십시오.

1. Ctrl/Cmd를 누른 채 을 클릭하고 **사람 병합**&#x200B;을 클릭하여 중복 항목을 선택합니다.

   ![](assets/three.png)

   >[!TIP]
   >
   >동일한 사용자에 대해 두 개 이상의 중복 항목이 있을 수 있습니다. 한 번에 모두 선택하십시오.

1. _일치하지 않는 레코드 사이의 값이 표시됩니다_. 각 필드에 유지할 값을 선택합니다. 완료되면 **병합**&#x200B;을 클릭합니다. 두 값 중 하나를 원하지 않는 경우 **사용자 지정**&#x200B;을 선택하고 원하는 값을 입력할 수 있습니다.

   ![](assets/four.png)

   >[!NOTE]
   >
   >수동으로 사람을 병합할 때, 첫 번째로 선택된 사람은 &quot;우승자&quot;가 됩니다. 인물 탭에서 레코드 ID를 198과 199로 병합하는 경우 199를 먼저 클릭하면 199가 병합된 사람의 레코드 ID가 됩니다. 두 개 이상의 레코드가 병합된 경우에도 적용됩니다.

   >[!TIP]
   >
   >병합은 삭제하는 것보다 낫습니다. 모든 내역(페이지 방문, 링크 클릭 수, 이메일 열기, 양식 채우기 등)을 보존합니다.

## Salesforce {#effect-in-salesforce}의 효과

Salesforce와의 통합이 있는 경우 Salesforce에서 리드 병합이 미치는 영향에 대한 몇 가지 메모가 있습니다.

* 리드만 병합하거나 연락처만 병합하면 일반 Salesforce 규칙별로 병합됩니다.
* 리드 및 연락처를 병합할 때 모든 리드는 일반적인 Salesforce 규칙별로 병합되기 전에 연락처로 변환됩니다.

리드 또는 연락처를 병합할 때의 Salesforce 동작에 대한 자세한 내용은 다음 Salesforce 문서를 확인하십시오.

* [중복 리드 병합](https://help.salesforce.com/HTViewHelpDoc?id=leads_merge.htm&amp;language=en_US)
* [중복 연락처 병합](https://help.salesforce.com/HTViewHelpDoc?id=contacts_merge.htm&amp;language=en_US)

## 벌크 병합 {#bulk-merging}

수동으로 병합할 중복 항목이 너무 많으면 고객 성공 관리자에게 문의하여 옵션에 대해 상담하십시오.

수퍼! CRM에 연결되어 있으면 레코드는 아래 규칙에 따라 병합됩니다.
