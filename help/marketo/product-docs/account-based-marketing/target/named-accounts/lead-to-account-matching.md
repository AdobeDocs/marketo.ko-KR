---
unique-page-id: 11381156
description: 계정 일치 - 마케팅 문서 - 제품 문서로 이동
title: 계정 일치로 이동
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# 계정 일치 {#lead-to-account-matching}으로 이동

리드를 Marketing to Lead-to-Account 일치로 적절한 명명 계정에 일치시킵니다.

>[!NOTE]
>
>**리드-계정 일치** 는 마케팅 계정 기반 마케팅의 기본 기능입니다. 퍼지 로직을 사용하여 거의 실시간으로 적절한 명명 계정에 리드를 자동으로 일치시킵니다. 이러한 명명 계정은 CRM 계정 또는 Marketing To 회사일 수 있습니다.

마케팅 리드-계정 일치는 4단계 프로세스를 따릅니다.

**1단계 -** 대응 프로세스는 다음과 같은 리드 레코드에 대한 키 정보를 사용하여 시작합니다.

* 이메일 도메인(예: acme.com)
* IP 주소에서 유추 회사 이름
* 회사 이름 - CRM 계정 이름 또는 리드 회사 이름 속성(예: 양식 채우기에서 생성됨)일 수 있습니다.

**2단계 - 다양한 리드 속성을 기반으로 찾은 회사 이름을 표준화합니다(예: Acme Inc. 및 Acme Corp는 자동으로 Acme로 정규화됨).** 이 단계를 통해 Marketing To에서 지정된 계정을 한 번 표시하고 단일 명명 계정 내에서 모든 리드를 볼 수 있습니다.

**3단계 -** Adobe는 대응된 리드를 2개의 버킷으로 분할합니다.강력한 일치 및 약한 일치.

* 대응되지 않는 리드는 명명된 계정에 나타나 수동으로 해결할 수 있습니다.

**단계 4-** 강점과 약점이 있는 기업 목록을 제공합니다. 제안된 회사 중 하나를 기반으로 지정된 계정이 생성되면, 일치하는 규칙을 만들어 적절한 명명 계정으로 이동하는 새 리드(예: 양식을 작성한 리드)를 자동으로 연결합니다. 이렇게 하면 리드를 일치시키지 않고 매출을 얻는 데 대해 더 걱정할 수 있습니다.

Marketing to Lead-to-Account 매칭은 Marketing To Account Based Marketing의 내장 기능이므로, 일치하는 리드는 거의 실시간으로 발생합니다(예: 리드가 Marketing To 양식을 작성하는 순간, Adobe는 리드를 올바른 지정된 계정과 연관시킵니다). 이 이벤트를 사용하여 경고를 트리거하고 계정 소유자에게 지정된 계정에서 들어오는 새 리드를 알릴 수 있습니다.

>[!NOTE]
>
>Salesforce에서 LeanData를 사용하여 고객 대 고객 관계를 형성하는 경우 Marketing To는 이러한 일치 항목을 Marketing To 인스턴스와 동기화하는 통합을 제공합니다. 해당 기능을 활성화하려면 [Marketing Support](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하십시오.

>[!MORELIKETHIS]
>
>* [Discover 계정](/help/marketo/product-docs/account-based-marketing/target/named-accounts/discover-accounts.md)

