---
unique-page-id: 11381156
description: 계정 일치 리드 - Marketo 문서 - 제품 설명서
title: 계정 일치 리드
exl-id: 676ae500-7691-492d-abec-0cac708216b7
source-git-commit: 98388f1ed941b321449e6e8badac0153dc2245ba
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 계정 일치 리드 {#lead-to-account-matching}

Marketo Lead-to-Account 일치를 사용하여 올바른 리드를 올바른 명명 계정에 일치시킵니다.

>[!NOTE]
>
>**Lead-to-Account** Match 는 Marketo Target 계정 관리의 기본 기능입니다. 퍼지 로직을 사용하여 거의 실시간으로 적절한 명명 계정에 리드를 자동으로 일치시킵니다. 이러한 명명된 계정은 CRM 계정 또는 Marketo 회사일 수 있습니다.

## 개요 {#overview}

Marketo Lead-to-Account Matching 은 4단계 프로세스를 따릅니다.

**1단계 -** Adobe의 일치 프로세스는 다음과 같은 리드 레코드에 대한 주요 정보를 사용하여 시작됩니다.

* 이메일 도메인(예: acme.com)
* IP 주소에서 유추된 회사 이름
* 회사 이름 - CRM 계정 이름 또는 리드 회사 이름 속성(예: 양식 채우기에서 생성됨)일 수 있습니다.

**2단계 -** 다양한 리드 속성을 기반으로 찾은 회사 이름을 정규화합니다(예: Acme Inc. 및 Acme Corp는 자동으로 Acme로 표준화됨). 이 단계에서는 Marketo에 명명된 계정을 한 개 표시하고 단일 명명된 계정 내에서 모든 리드를 볼 수 있습니다.

**3단계 -** 일치하는 리드를 2개의 버킷으로 분할합니다. 강력한 경기 및 약한 경기.

* 이름이 지정된 계정에 매칭되지 않은 리드가 나타나고 이를 수동으로 해결할 수 있습니다.

**4단계 -** 당사가 강하고 약점이 있는 제안된 회사의 목록을 제공합니다. 제안된 회사 중 하나를 기반으로 명명된 계정을 만들 때, Adobe에서는 적합한 명명 계정에 전달되도록 새로운 리드(예: 양식을 작성한 리드)를 자동으로 연결하는 일치 규칙을 만듭니다. 이렇게 하면 리드에 대한 걱정 없이 매출을 얻는 것에 대해 걱정할 수 있습니다.

Marketo Lead-to-Account Match는 Marketo Target 계정 관리의 기본 기능이므로 일치하는 계정이 거의 실시간으로 발생합니다(예: 리드가 Marketo 양식을 작성하는 순간, Adobe에서는 해당 리드를 올바른 명명된 계정에 연결). 이 이벤트를 사용하여 경고를 트리거하고 지정된 계정에서 들어오는 새 리드의 계정 소유자에게 알릴 수 있습니다.

>[!NOTE]
>
>Salesforce에서 LeanData를 사용하여 Lead-to-Account 일치를 수행하는 경우 Marketo에는 해당 일치 항목을 Marketo 인스턴스에 동기화하는 통합이 있습니다. 해당 기능을 활성화하려면 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support) 아래 LeanData를 설정하는 방법을 배웁니다.

## Lean-Data를 사용하여 계정 일치 {#using-leandata-for-lead-to-account-matching}

[Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)이 계정에 대해 LeanData를 활성화한 후 아래 단계에 따라 설정합니다.

1. Salesforce에서 왼쪽 탐색 메뉴에서 **설정 홈**&#x200B;을 클릭합니다.

1. 왼쪽 탐색 메뉴의 관리 아래에서 **사용자**&#x200B;를 클릭한 다음 **프로필**&#x200B;을 클릭합니다.

1. **Marketo Sync** 프로필을 찾아 선택합니다.

1. 필드 수준 보안 섹션으로 스크롤하여 리드 객체를 찾습니다. **보기**&#x200B;를 선택합니다.

1. 필드 이름 &quot;Reporting Matched Account&quot;에 대해 **Read Access** 열의 확인란이 선택되어 있는지 확인합니다.

1. Marketo에서 **관리** 섹션으로 이동합니다.

   ![](assets/lead-to-account-matching-1.png)

1. **필드 관리**&#x200B;를 선택합니다.

   ![](assets/lead-to-account-matching-2.png)

1. &quot;Reporting Matched Account&quot;를 검색하여 필드가 있는지 확인합니다.

   ![](assets/lead-to-account-matching-3.png)

>[!MORELIKETHIS]
[계정 검색](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md)>
>
