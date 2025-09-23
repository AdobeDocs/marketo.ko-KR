---
unique-page-id: 11381156
description: 계정 일치 - Marketo 문서 - 제품 설명서로 연결하십시오.
title: 계정 일치로 이어짐
exl-id: 676ae500-7691-492d-abec-0cac708216b7
feature: Target Account Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '451'
ht-degree: 2%

---

# 계정 일치로 이어짐 {#lead-to-account-matching}

Marketo 리드-계정 일치를 사용하여 오른쪽 리드를 올바른 명명된 계정에 대응합니다.

>[!NOTE]
>
>**리드-계정 일치**&#x200B;는 Marketo [!UICONTROL Target Account Management]의 기본 기능입니다. 퍼지 논리를 사용하여 거의 실시간으로 올바른 명명된 계정에 대한 리드를 자동으로 일치시킵니다. 이러한 명명된 계정은 CRM 계정 또는 Marketo 회사일 수 있습니다.

## 개요 {#overview}

Marketo 리드-계정 일치는 4단계 프로세스를 따릅니다.

**1단계 -** 일치 프로세스는 다음과 같은 잠재 고객 레코드의 주요 정보를 사용하여 시작합니다.

* 이메일 도메인(예: acme.com)
* IP 주소에서 회사 이름 유추
* 회사 이름 - CRM 계정 이름 또는 리드 회사 이름 속성일 수 있음(예: 양식 작성에서 가져옴)

**2단계 -** 다양한 리드 특성을 기반으로 찾은 회사 이름을 정규화합니다(예: Acme Inc. 및 Acme Corp는 자동으로 Acme로 정규화됨). 이 단계에서는 Marketo에 명명된 계정이 단일 표시로 표시되고 단일 명명된 계정 내에서 모든 잠재 고객을 볼 수 있습니다.

**3단계 -** 일치하는 리드를 두 개의 버킷(강한 일치 및 약한 일치)으로 분할했습니다.

* 취약한 대응 리드가 명명된 계정에 표시되면 수동으로 해결할 수 있습니다.

**4단계 -** 일치하는 회사와 일치하는 제안 회사 목록을 제공합니다. 제안된 회사 중 하나를 기반으로 명명 계정을 만들면 일치하는 규칙을 만들어 올바른 명명 계정으로 진행되는 새 리드(예: 양식으로 작성된 리드)를 자동으로 연결합니다. 이렇게 하면 일치하는 리드에 대해 더 적게 걱정하고 매출을 얻는 데 더 많이 걱정할 수 있습니다.

Marketo 리드-계정 일치는 Marketo [!UICONTROL Target Account Management]의 기본 제공 기능이므로 일치하는 리드는 거의 실시간으로 발생합니다(예: 리드가 Marketo 양식을 작성하는 순간 해당 리드를 올바른 명명된 계정과 연결). 이 이벤트는 경고를 트리거하고 계정 소유자에게 명명된 계정에서 들어오는 새 리드를 알리는 데 사용할 수 있습니다.

>[!NOTE]
>
>Salesforce의 LeanData를 사용하여 리드-계정 일치를 수행하는 경우 Marketo에는 이러한 일치를 Marketo 인스턴스에 동기화하는 통합이 있습니다. 해당 기능을 활성화하려면 [Marketo 지원 센터](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하십시오. 아래에서 LeanData를 설정하는 방법에 대해 알아보십시오.

## 리드 대 계정 일치에 LeanData 사용 {#using-leandata-for-lead-to-account-matching}

[Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에서 계정에 대해 LeanData를 활성화한 후 아래 단계에 따라 설정하십시오.

1. Salesforce에서 왼쪽 탐색 메뉴에서 **[!UICONTROL Setup Home]**&#x200B;을(를) 클릭합니다.

1. 왼쪽 탐색 메뉴에서 관리에서 **[!UICONTROL Users]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Profiles]**&#x200B;을(를) 클릭합니다.

1. **Marketo 동기화** 프로필을 찾아 선택합니다.

1. 필드 수준 보안 섹션까지 아래로 스크롤하여 리드 객체를 찾습니다. **[!UICONTROL View]**&#x200B;를 선택합니다.

1. 필드 이름 &quot;일치하는 계정 보고&quot;에 대해 **[!UICONTROL Read Access]** 열의 확인란을 선택해야 합니다.

1. Marketo에서 **[!UICONTROL Admin]** 섹션으로 이동합니다.

   ![](assets/lead-to-account-matching-1.png)

1. **[!UICONTROL Field Management]**&#x200B;를 선택합니다.

   ![](assets/lead-to-account-matching-2.png)

1. &quot;[!UICONTROL Reporting Matched Account]&quot;을(를) 검색하여 필드가 있는지 확인하십시오.

   ![](assets/lead-to-account-matching-3.png)

>[!MORELIKETHIS]
>
>[계정 검색](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md)
