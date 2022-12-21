---
unique-page-id: 557339
description: 중복 사용자 찾기 및 병합 - Marketo 문서 - 제품 설명서
title: 중복 사람 찾기 및 병합
exl-id: a6d46096-587a-4e3a-b37a-917c0d2098b1
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '429'
ht-degree: 0%

---

# 중복 사람 찾기 및 병합 {#find-and-merge-duplicate-people}

Marketo은 새 사용자가 시스템에 들어올 때 자동으로 중복을 제거합니다. 그러나 CRM에서 처음에 Marketo에 중복을 전송했을 수 있습니다. 여기에 그것들을 병합하는 방법이 있습니다.

>[!NOTE]
>
>Marketo은 Salesforce 또는 Microsoft Dynamics 동기화에 대해 자동으로 중복 제거를 수행하지 않거나 수동으로 사람을 입력할 때 자동으로 중복 제거를 수행하지 않습니다.

>[!PREREQUISITES]
>
>중복을 찾아 병합하는 경우 [내장/시스템 스마트 목록](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-built-in-system-smart-lists.md).

## 중복 찾기 {#find-duplicates}

1. 로 이동합니다. **데이터베이스** 영역.

   ![](assets/db.png)

   >[!CAUTION]
   >
   >Salesforce 개인 계정을 사용하는 경우 Marketo에서 사람 병합이 작동하지 않을 수 있습니다. 가능하면 Salesforce에서 레코드를 병합하십시오.

1. 을(를) 선택합니다 **가능한 중복** system smart list 를 클릭하고 **사람** 탭.

   ![](assets/two.png)

   >[!NOTE]
   >
   >다음을 수행할 수도 있습니다 [사용자 지정 논리를 사용하여 중복 사람 찾기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-duplicate-people-with-custom-logic.md).

## 수동으로 사람 병합 {#merge-people-manually}

>[!CAUTION]
>
>사람을 병합할 때 유실자에게 Marketo 사용자 지정 개체가 있으면 이 개체가 만들어집니다 **not** 우승자와 다시 연결하세요. 병합을 수행하기 전에 사용자 지정 개체를 다시 부모하십시오.

1. Ctrl/Cmd를 누른 채 을 클릭하여 중복을 선택합니다 **사람 병합**.

   ![](assets/three.png)

   >[!TIP]
   >
   >동일한 사람에 대해 두 개 이상의 중복을 보유할 수 있습니다. 한 번에 모두 선택합니다.

1. 다음 레코드 사이에 _하지 않음_ 일치. 각 필드에 유지할 값을 선택합니다. 클릭 **병합** 완료 시. 두 값 중 하나를 원하지 않는 경우 다음을 확인할 수 있습니다 **사용자 지정** 원하는 값을 입력합니다.

   ![](assets/four.png)

   >[!NOTE]
   >
   >수동으로 사람을 병합하면 가장 먼저 선택한 사람이 &quot;우승자&quot;가 됩니다. 사람 탭에서 레코드 ID를 198과 199로 병합하고 199를 처음 클릭하면 199가 병합된 사람의 레코드 ID가 됩니다. 두 개 이상의 레코드가 병합되는 경우에도 적용됩니다.

   >[!TIP]
   >
   >병합은 삭제하는 것보다 낫습니다. 모든 기록(페이지 방문 횟수, 링크 클릭 수, 이메일 열기, 양식 채우기 등)을 보존합니다.

## Salesforce의 효과 {#effect-in-salesforce}

Salesforce 통합이 있는 경우 Salesforce에서 리드 병합의 효과에 대한 몇 가지 메모가 있습니다.

* Leads만 병합하거나 Contacts만 병합하면 일반 Salesforce 규칙별로 병합됩니다.
* Lead 와 Contacts 를 함께 병합하면 모든 Lead 가 Contacts 로 변환되고 Salesforce 규칙별로 병합됩니다.

Lead 또는 Contacts를 병합할 때 Salesforce 동작에 대한 자세한 내용은 다음 Salesforce 문서를 참조하십시오.

* [중복 리드 병합](https://help.salesforce.com/HTViewHelpDoc?id=leads_merge.htm&amp;language=en_US)
* [중복 연락처 병합](https://help.salesforce.com/HTViewHelpDoc?id=contacts_merge.htm&amp;language=en_US)

## 벌크 병합 {#bulk-merging}

수동으로 병합하기 위해 중복 항목이 너무 많은 경우 고객 성공 관리자에게 문의하여 선택 사항에 대해 논의하십시오.

아주! CRM에 연결되어 있으면 아래 규칙에 따라 레코드가 여기에 병합됩니다.
