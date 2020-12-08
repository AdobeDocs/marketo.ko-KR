---
unique-page-id: 11381156
description: 계정 일치로 이동 - 마케팅 문서 - 제품 설명서
title: 계정 일치로 이동
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# 계정 일치로 이동 {#lead-to-account-matching}

적절한 일치 리드는 Marketing to Lead-to-Account 일치를 사용하여 올바른 명명 계정에 도달합니다.

>[!NOTE]
>
>**리드-계정 일치** 기능은 Marketing To 계정 기반 마케팅의 기본 기능입니다. 퍼지 로직을 사용하여 거의 실시간으로 적절한 이름의 계정에 리드를 자동으로 일치시킵니다. 이러한 지정된 계정은 CRM 계정 또는 Marketing To 회사일 수 있습니다.

Marketing-to-Account Matching은 4단계 프로세스를 따릅니다.

**1단계 -** Adobe의 대응 프로세스는 다음과 같은 리드 레코드에 대한 키 정보를 사용하여 시작됩니다.

* 이메일 도메인(예: acme.com)
* IP 주소의 유추 회사 이름
* 회사 이름 - CRM 계정 이름 또는 리드 회사 이름 속성(예: 양식 채우기에서 생성됨)일 수 있습니다.

**2단계 -** 다양한 리드 속성을 기반으로 찾은 회사 이름을 정규화합니다(예: Acme Inc. 및 Acme Corp는 자동으로 Acme로 정규화됨). 이 단계에서는 Marketing To에서 지정된 계정을 한 번 표시하고 단일 명명 계정 내에서 모든 리드를 볼 수 있습니다.

**3단계 -** 리드를 2개의 버킷으로 분할합니다.강력한 일치 및 약한 일치.

* 대응되지 않는 리드는 명명된 계정에 나타나며, 이를 수동으로 해결할 수 있습니다.

**단계 4-** 현재 경기 실세가 강하고 약점이 있는 기업 목록을 제시해 드립니다. 제안된 회사 중 하나를 기반으로 지정된 계정이 생성되면, 일치하는 규칙을 만들어 적합한 명명 계정으로 이동하는 새 리드(예: 양식을 작성한 리드)를 자동으로 연결합니다. 이렇게 하면 리드를 일치시키지 않고 매출을 얻는 것에 대해 더 걱정할 수 있습니다.

Marketing-to-Account 일치는 Marketing To Account Based Marketing의 내장 기능이므로, 일치하는 계정을 실시간으로 발생시킵니다(예: 리드가 Marketing to 양식을 작성하는 순간, Adobe는 리드를 올바른 명명 계정과 연관시킵니다). 이 이벤트를 사용하여 경고를 트리거하고 계정 소유자에게 지정된 계정에서 들어오는 새 리드를 통지할 수 있습니다.

>[!NOTE]
>
>Salesforce에서 LeanData를 사용하여 고객과 직접 연결할 경우 Marketing To 인스턴스와 일치하는 항목을 동기화할 수 있는 통합이 제공됩니다. 해당 기능을 활성화하려면 Marketing [To 지원 센터에 문의하십시오](https://nation.marketo.com/t5/Support/ct-p/Support).

>[!MORELIKETHIS]
>
>* [Discover 계정](/help/marketo/product-docs/account-based-marketing/target/named-accounts/discover-accounts.md)

