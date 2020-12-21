---
unique-page-id: 11378812
description: Discover 계정 - 마케팅 문서 - 제품 설명서
title: Discover 계정
translation-type: tm+mt
source-git-commit: e125f8469239a026aefb703fdb6ba99c32e33565
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---


# Discover 계정 {#discover-accounts}

Discover 옵션을 사용하여 잠재적 타겟 계정을 식별합니다.

## Discover CRM 계정 {#discover-crm-accounts}

CRM에서 잠재적인 타겟 계정을 식별합니다.

>[!NOTE]
>
>CRM을 Marketing ABM에 연결한 후 **Discover CRM 계정**&#x200B;은 올바른 명명 계정을 선택하는 데 도움이 되는 모든 CRM 계정 및 관련 정보를 표시합니다. Marketing은 CRM에서 받은 정보 위에 추가 정보를 추가합니다.

**사람** (Discover CRM 계정 및 Discover 마케팅 회사):연락처 및 리드 모두를 포함합니다. 리드는 Marketing의 [리드-계정 일치](/help/marketo/product-docs/account-based-marketing/target/named-accounts/lead-to-account-matching.md)를 사용하여 검색할 수 있습니다.

**잠재적인 사람** (Discover CRM 계정 및 Discover 마케팅 회사):CRM 계정에 속할 수 있는 리드를 Marketing에서 찾은 횟수를 표시합니다.

**사용자 지정 CRM 필드** (Discover CRM 계정에만 해당):이렇게 하면 올바른 타겟 계정을 선택하기 위해 판매 및 마케팅 조직을 조정하는 데 도움이 됩니다. [사용자 지정 CRM 필드](/help/marketo/product-docs/account-based-marketing/setup-abm/create-a-custom-field-for-crm-discovery.md)를 Marketing to ABM과 매핑하면 대상 계정을 식별하는 데 도움이 되는 매핑된 데이터를 표시합니다.

1. 지정된 계정에서 **새로 만들기** 드롭다운을 클릭하고 **Discover CRM 계정**&#x200B;을 선택합니다.

   ![](assets/disc-crm-one.png)

1. 새 창/탭이 열립니다. 네임드 계정에 추가할 CRM 계정을 선택하고 **다음**&#x200B;을 클릭합니다.

   ![](assets/disc-crm-two.png)

1. 미리 보기 화면에서 선택 영역의 양을 확인합니다. **만들기**&#x200B;를 클릭합니다.

   ![](assets/disc-three.png)

   그게 전부야!

   ![](assets/disc-four.png)

## Discover 마케팅 회사 {#discover-marketo-companies}

타깃팅할 적합한 회사를 식별합니다.

>[!NOTE]
>
>Discover Marketing Company에서는 CRM에서 오지 않은 Marketing Cloud 회사를 볼 수 있습니다.

1. 지정된 계정에서 **새로 만들기** 드롭다운을 클릭하고 **Discover Marketing To Companies**&#x200B;를 선택합니다.

   ![](assets/one-1.png)

1. 새 창/탭이 열립니다. 네임드 계정에 추가할 회사를 선택하고 **다음**&#x200B;을 클릭합니다.

   ![](assets/disc-comp-two.png)

   >[!NOTE]
   >
   >Discover Marketing To Company와 Discover CRM에서 Marketing은 자동으로 다음을 수행합니다.
   >
   >* 해당 회사가 레코드에 나열되는 Marketing 데이터베이스에서 사용자를 찾습니다. 일부 속성(예: 산업)에 대해 여러 값이 표시되는 경우 Marketing에서 해당 개별 사용자에 대해 다른 값을 발견했기 때문입니다. 히트가 가장 많은 속성이 승리함
   >
   >**Discover CRM**&#x200B;에만 해당, Marketing이 자동으로 다음을 수행합니다.
   >
   >* CRM 연락처를 지정된 계정에 동기화 및 연결
   >
   >**Discover Marketing Company**&#x200B;에만 해당, Marketing이 자동으로 다음을 수행합니다.
   >
   >* 대부분의 인터넷 서비스 공급자 및 공개 도메인(예: yahoo.com, gmail.com)을 회사 이름으로 필터링합니다.
      >
      >
   * CRM 계정을 제거합니다. 한 개의 레코드와 &quot;Acme Inc&quot;(또는 다음 접미사 중 하나)에 &quot;Acme&quot;가 있는 경우:Co, Corp, Corporation, Gmbh, Inc, Incorporated, LLP, LP, Ltd, PA, PC, PLC, PLC)는 ABM에서 &quot;Acme&quot;로 병합합니다.
   >
   >Marketing To가 회사 이름 대신 CRM ID 또는 계정 소유자로 계정을 중복 제거하도록 하려면 [Marketing Support](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하십시오.

1. 지정된 계정 열 아래의 아래쪽 화살표를 클릭하여 드롭다운을 표시합니다.

   ![](assets/disc-comp-three.png)

   >[!CAUTION]
   >
   >앞으로, 이 선택된 회사의 새로운 직원은 자동으로 각각의 이름 있는 계정에 할당됩니다. 이 회사들을 다시 확인하고 올바른 명명 계정에 할당되었는지 확인하십시오.

1. 기존 계정을 선택하려면 **명명된 계정** 드롭다운을 클릭하고 원하는 계정을 선택한 다음 **다음**&#x200B;을 클릭합니다.

   ![](assets/disc-comp-four.png)

   드롭다운 상자에 원하는 이름을 직접 입력하여 새 네임드 계정을 만들 수도 있습니다. 완료 시 상자 밖을 클릭합니다...

   ![](assets/disc-comp-five.png)

   ...그러면 새로운 네임드 계정이 표시됩니다. 이때 4단계에서 **다음**&#x200B;을 클릭합니다.

   ![](assets/disc-comp-six.png)

1. **만들기**&#x200B;를 클릭합니다.

   ![](assets/disc-comp-seven.png)

   잘했어!

   ![](assets/disc-co-six.png)

>[!NOTE]
>
>선택한 CRM 계정과 Discover CRM 그리드에 있는 계정이 일치하지 않는 경우, 다음 중 하나 이상이 원인일 수 있습니다.
>
>* 비슷한 이름의 다른 CRM 계정을 가지고 있어서 중복 제거
>* 다음 예약 동기화가 아직 발생하지 않았습니다.


>[!MORELIKETHIS]
>
>[계정 일치로 이동](/help/marketo/product-docs/account-based-marketing/target/named-accounts/lead-to-account-matching.md)
