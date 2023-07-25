---
unique-page-id: 11378812
description: 계정 살펴보기 - Marketo 문서 - 제품 설명서
title: 계정 검색
exl-id: 90da4ae0-0a12-48bd-8bae-a7431d2cf4f4
feature: Target Account Management
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 1%

---

# 계정 검색 {#discover-accounts}

잠재적 대상 계정을 식별하려면 검색 옵션을 사용합니다.

## CRM 계정 검색 {#discover-crm-accounts}

CRM에서 잠재적인 대상 계정을 식별합니다.

>[!NOTE]
>
>CRM을 Marketo TAM에 연결한 후 **CRM 계정 검색** 은(는) 올바른 명명된 계정을 선택하는 데 도움이 되도록 모든 CRM 계정 및 관련 정보를 표시합니다. Marketo은 CRM으로부터 받은 것 위에 추가 정보를 추가합니다.

**사람** (CRM 계정 검색 및 Marketo 회사 검색에서): 연락처 및 잠재 고객을 모두 포함합니다. Marketo을 사용하여 리드를 검색할 수 있습니다 [리드-계정 일치](/help/marketo/product-docs/target-account-management/target/named-accounts/lead-to-account-matching.md).

**잠재적 사람** (CRM 계정 검색 및 Marketo 회사 검색에서): CRM 계정에 속할 수 있는 Marketo의 잠재 고객 수를 보여줍니다.

**사용자 정의 CRM 필드** (CRM 계정 검색에만 해당): 올바른 대상 계정을 선택하기 위해 영업 및 마케팅 조직을 연계하는 데 도움이 됩니다. 한 번 [사용자 지정 CRM 필드 매핑](/help/marketo/product-docs/target-account-management/setup-tam/create-a-custom-field-for-crm-discovery.md) Marketo TAM을 사용하면 대상 계정을 식별하는 데 도움이 되는 매핑된 데이터를 보여 줍니다.

1. 명명된 계정에서 **신규** 드롭다운 및 선택 **CRM 계정 검색**.

   ![](assets/disc-crm-one.png)

1. 새 창/탭이 열립니다. 명명 계정에 추가할 CRM 계정을 선택하고 **다음**.

   ![](assets/disc-crm-two.png)

1. 미리보기 화면에서 선택 양을 확인합니다. Click **Create**.

   ![](assets/disc-three.png)

   이게 전부입니다!

   ![](assets/disc-four.png)

## Marketo 회사 살펴보기 {#discover-marketo-companies}

타깃팅에 적합한 회사를 식별합니다.

>[!NOTE]
>
>Marketo 회사 검색에서는 CRM에서 가져오지 않은 Marketo 회사를 볼 수 있습니다.

1. 명명된 계정에서 **신규** 드롭다운 및 선택 **Marketo 회사 살펴보기**.

   ![](assets/one-1.png)

1. 새 창/탭이 열립니다. 명명 계정에 추가할 회사를 선택하고 **다음**.

   ![](assets/disc-comp-two.png)

   >[!NOTE]
   >
   >Marketo 회사 검색 및 CRM에서 Marketo은 자동으로 다음 작업을 수행합니다.
   >
   >* Marketo 데이터베이스에서 해당 회사가 레코드에 나열되어 있는 사람을 찾습니다. 일부 속성(예: 산업)에 대한 값이 여러 개 표시되는 경우, Marketo에서 해당 개인에 대해 나열된 다른 값을 발견했기 때문입니다. 히트가 가장 많은 속성이 승리합니다.
   >
   >위치 **CRM 검색** Marketo만 해당:
   >
   >* CRM 연락처를 명명된 계정과 동기화 및 연결
   >
   >위치 **Marketo 회사 살펴보기** Marketo만 해당:
   >
   >* 대부분의 인터넷 서비스 공급자와 공개 도메인(예: yahoo.com, gmail.com)을 회사 이름으로 필터링합니다.
   >
   >* CRM 계정을 중복 제거합니다. 하나의 레코드에서 &quot;Acme&quot;와 &quot;Acme Inc&quot;(또는 다음 접미사 중 하나)가 있는 경우(Co, Corp, Corporation, Gmbh, Inc, Incorporated, LLC, LLP, LP, Ltd, PA, PC, PLC, PLLC), TAM에서 &quot;Acme&quot;와 동일하게 병합합니다.
   >
   >Marketo에서 회사 이름 대신 CRM ID 또는 계정 소유자별로 계정을 중복 제거하려면 다음으로 문의하십시오. [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Named Account 열 아래의 아래쪽 화살표를 클릭하여 드롭다운을 표시합니다.

   ![](assets/disc-comp-three.png)

   >[!CAUTION]
   >
   >앞으로 이러한 선택한 회사의 새 직원은 자동으로 해당 명명 계정에 할당됩니다. 이러한 회사를 다시 한 번 확인하여 올바른 명명 계정에 할당되었는지 확인하십시오.

1. 기존 계정을 선택하려면 **명명된 계정** 드롭다운에서 원하는 계정을 선택하고 **다음**.

   ![](assets/disc-comp-four.png)

   드롭다운 상자에 원하는 이름을 직접 입력하여 새 명명된 계정을 만들 수도 있습니다. 완료하면 상자에서 나가기 클릭...

   ![](assets/disc-comp-five.png)

   ...새 명명된 계정이 표시됩니다. 이 시점에서 **다음** 4단계에서와 같습니다.

   ![](assets/disc-comp-six.png)

1. Click **Create**.

   ![](assets/disc-comp-seven.png)

   수고하셨습니다!

   ![](assets/disc-co-six.png)

>[!NOTE]
>
>선택한 CRM 계정과 검색 CRM 그리드의 항목 간에 불일치가 표시되는 경우, 다음 중 하나 이상의 원인으로 인해 발생할 수 있습니다.
>
>* 중복 제거된 유사한 이름의 다른 CRM 계정 있음
>* 다음 예약된 동기화가 아직 발생하지 않았습니다.

>[!MORELIKETHIS]
>
>[리드-계정 일치](/help/marketo/product-docs/target-account-management/target/named-accounts/lead-to-account-matching.md)
