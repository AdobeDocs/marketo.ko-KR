---
unique-page-id: 557339
description: 중복 사용자 찾기 및 병합 - Marketo 문서 - 제품 설명서
title: 중복 사용자 찾기 및 병합
exl-id: a6d46096-587a-4e3a-b37a-917c0d2098b1
feature: Smart Lists
source-git-commit: 208ba59e3a5cb8e613e887b4c89e51cec4b3f897
workflow-type: tm+mt
source-wordcount: '423'
ht-degree: 0%

---

# 중복 사용자 찾기 및 병합 {#find-and-merge-duplicate-people}

Marketo Engage은 새로운 사용자가 시스템에 들어올 때 자동으로 중복 제거를 수행합니다. 그러나 처음에 CRM에서 중복을 보냈을 수 있습니다. 결합 방법은 다음과 같습니다.

>[!CAUTION]
>
>사람을 병합하는 것은 영구적이므로 &quot;실행 취소&quot; 옵션이 없습니다.

>[!PREREQUISITES]
>
>중복 항목을 찾아서 병합하려면 다음을 사용합니다. [기본 제공/시스템 스마트 목록](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-built-in-system-smart-lists.md){target="_blank"}.

>[!NOTE]
>
>Marketo은 Salesforce 또는 Microsoft Dynamics 동기화와 관련해서 또는 수동으로 인원을 입력할 때 자동으로 중복 제거되지 않습니다.

## 중복 항목 찾기 {#find-duplicates}

1. 로 이동 **[!UICONTROL 데이터베이스]** 영역입니다.

   ![](assets/find-and-merge-duplicate-people-1.png)

   >[!CAUTION]
   >
   >Salesforce 사용자 계정을 사용하는 경우 Marketo의 직원 병합이 작동하지 않을 수 있습니다. 가능하면 Salesforce에서 레코드를 병합하십시오.

1. 다음 항목 선택 **[!UICONTROL 가능한 중복 항목]** System Smart List 를 클릭하고 **[!UICONTROL 사람]** 탭.

   ![](assets/find-and-merge-duplicate-people-2.png)

   >[!NOTE]
   >
   >다음을 수행할 수도 있습니다. [사용자 지정 논리로 중복 사용자 찾기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-duplicate-people-with-custom-logic.md){target="_blank"}.

## 수동으로 사람 병합 {#merge-people-manually}

>[!CAUTION]
>
>사람들을 병합할 때 손실되는 사람에게 Marketo 사용자 지정 개체가 있는 경우 병합은 _아님_ 우승자에게 다시 연결하십시오. 병합을 수행하기 전에 사용자 지정 개체의 상위 항목을 다시 지정하십시오.

1. Ctrl/Cmd를 누른 채 클릭하여 중복 항목을 선택하고 **[!UICONTROL 사람 병합]**.

   ![](assets/find-and-merge-duplicate-people-3.png)

   >[!TIP]
   >
   >동일한 사용자에 대해 두 개 이상의 중복 항목을 가질 수 있습니다. 모두 한 번에 선택하십시오.

1. 다음 레코드 사이에 있는 값이 표시됩니다. _안 함_ 일치. 각 필드에 유지할 값을 선택합니다. 클릭 **[!UICONTROL 병합]** 완료 시. 둘 중 하나의 값을 원하지 않는 경우 다음을 확인할 수 있습니다 **[!UICONTROL 사용자 정의]** 선택한 값을 입력합니다.

   ![](assets/find-and-merge-duplicate-people-4.png)

   >[!NOTE]
   >
   >수동으로 사람을 병합하는 경우 처음 선택한 사람이 &quot;우승자&quot;가 됩니다. 따라서 사람 탭에서 레코드 ID 198과 199를 병합하고 먼저 199를 클릭하면 199가 병합된 사람의 레코드 ID가 됩니다. 두 개 이상의 레코드가 병합되는 경우에도 적용됩니다.

   >[!TIP]
   >
   >병합하는 것이 삭제하는 것보다 낫습니다. 모든 기록(페이지 방문, 링크 클릭, 이메일 열기, 양식 채우기 등)을 보존합니다.

## Salesforce의 효과 {#effect-in-salesforce}

Salesforce 통합이 있는 경우 Salesforce의 가망 고객 병합 효과에 대한 몇 가지 참고 사항이 있습니다.

* Lead 만 병합하거나 Contact 만 병합하는 경우 일반적인 Salesforce 규칙에 따라 병합됩니다.
* Lead 와 Contact 를 병합할 경우 모든 Lead 는 일반적인 Salesforce 규칙에 따라 병합하기 전에 Contact 로 변환됩니다.

Leads 또는 Contact 를 병합할 때의 Salesforce 동작에 대한 자세한 내용은 다음 Salesforce 문서를 확인하십시오.

* [중복 잠재 고객 병합](https://help.salesforce.com/HTViewHelpDoc?id=leads_merge.htm&amp;language=en_US){target="_blank"}
* [중복 연락처 병합](https://help.salesforce.com/HTViewHelpDoc?id=contacts_merge.htm&amp;language=en_US){target="_blank"}

## 벌크 병합 {#bulk-merging}

중복 항목이 너무 많아 수동으로 병합할 수 없는 경우에는 Adobe 계정 팀(계정 관리자)에 문의하여 옵션에 대해 논의하십시오.
