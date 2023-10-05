---
description: 동적 필드 - Marketo 문서 - 제품 설명서
title: 동적 필드
exl-id: d9e52eae-d5bb-462f-8b7b-c28a560f6ea4
feature: Sales Insight Actions
source-git-commit: cffe7a8734f79f887f3aad017a16fad4f04cda74
workflow-type: tm+mt
source-wordcount: '559'
ht-degree: 0%

---

# 동적 필드 {#dynamic-fields}

다음과 같이 사전 정의된 속성을 사용하여 이메일 템플릿을 개인화할 수 있습니다. `{{first_name}}` 또는 `{{company}}`. 이러한 필드를 사용하면 각 연락처에 대해 별도로 입력할 필요 없이 여러 연락처를 이메일로 보내고 이러한 필드를 자동으로 완성할 수 있습니다.

>[!TIP]
>
>first_name 및 company 필드는 Sales Insight Actions 및 Salesforce를 모두 표시하는 유일한 필드입니다. 즉, 연락처가 다음에 존재하지 않는 경우 [웹 애플리케이션](https://toutapp.com/login), Salesforce를 살펴보고 이메일 주소가 일치하는 연락처/잠재 고객 레코드를 찾을 수 있는지 확인합니다. 그런 다음 해당 레코드의 정보를 사용하여 필드를 채웁니다.

## 템플릿에 동적 필드 삽입 {#insert-a-dynamic-field-into-a-template}

1. 위치 **템플릿 및 캠페인**&#x200B;편집할 템플릿을 찾은 다음 를 클릭합니다 **템플릿 편집**.

1. 클릭 **동적 필드 삽입**.

   >[!NOTE]
   >
   >Sales Insight Actions에 있는 담당자에게 이메일을 보낼 때 기본 동적 필드를 사용할 수 있습니다. 이것들은 접촉에서 바로 당겨질 것이다.

Salesforce에 있는 연락처에 이메일을 보내는 경우 Salesforce 동적 필드를 활용할 수 있습니다. 이러한 모든 항목은 &quot;sfdc&quot;로 시작합니다. Salesforce에 연결되어 있는 한 이러한 필드는 템플릿에 정보를 채우려면 Salesforce의 리드/연락처에 직접 호출됩니다.

## 제목 줄에 동적 필드 삽입 {#insert-dynamic-fields-in-a-subject-line}

전자 메일의 제목 필드에 수동으로 복사하여 붙여 넣기만 하면 적절한 서식이 지정되었는지 확인할 수 있습니다.

## 동적 필드 기본값 {#dynamic-field-default-values}

이메일 템플릿에 동적 필드를 추가할 때 사용 가능한 다른 값이 없는 경우 동적 필드에서 해결할 기본값을 추가할 수 있습니다.

이렇게 하려면 동적 필드 레이블 뒤에 &quot;|&quot;을 추가한 다음, &quot;기본값:&quot;(둘 다 따옴표 제외)을 추가하십시오. 다른 값을 찾을 수 없는 경우 필드가 확인할 값(따옴표로 묶음)을 추가합니다.

**예:**

`{{first name | default: "loyal customer"}}`

`{{sfdc_contact_account_name | default: "your company"}}`

## 동적 필드 용어집 {#dynamic-fields-glossary}

Sales Insight Actions에서 템플릿을 생성할 때는 항상 다음을 사용하여 동적 필드를 통합하는 것이 좋습니다. **동적 필드 삽입** 단추를 클릭합니다.

이 도구는 다음 용도로 사용됩니다. `auto-personalize your email` and save you tton of time `pulling information from the People page`.

| 동적 필드 | 이메일에 표시되는 항목 예 |
|---|---|
| `{{company}}` | Adobe |
| `{{company_friendly}}` | Adobe |
| `{{first_name}}` | 키스 |
| `{{team_unsubscribe}}` | 더 이상 이메일을 수신하지 않으려면 여기를 클릭하십시오. |
| `{{friendly_unsubscribe}}` | 모든 이메일에 지쳤나요? 여기 좀 알려주세요 |
| `{{my_name}}` | 키스 플린 |
| `{{my_signature}}` | 수석 기술 작가 Keith Flynn - Adobe |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | 수석 기술 저자 |
| `{{work_website}}` | https://www.adobe.com |

**유의할 사항**:

* 연락처 정보가 잘못 입력되었거나 사람 페이지에서 누락된 경우 해당 정보가 템플릿으로 올바르게 이동되지 않습니다.
* 차이점 `{{company}}` 및 `{{company_friendly}}` 다음과 같음 `{{company_friendly}}` 은(는) 귀하의 연락처 회사의 이름에서 Inc., LLC 등과 같은 공식적인 제목을 제거합니다.
* 사용 시 `{{company_friendly}}`연락처 세부 정보에서 쉼표로 Inc. 또는 Co.를 구분해야 합니다. 이는 Sales Insight Actions 이 값을 가져올 때 제거할 항목을 아는 방법입니다.
* 다음과 같이 사전 정의된 속성을 사용하여 이메일 템플릿을 개인화할 수 있습니다. `{{my_name}}` 또는 `{{my_title}}`. 이러한 필드를 사용하면 전자 메일 템플릿에서 자신을 빠르게 참조할 수 있습니다.
* 시스템에서는 보낸 각 이메일에 사용자 서명을 자동으로 추가합니다. 사용자가 템플릿으로 `{{my_signature}}` 동적 필드에서는 시스템이 `{{my_signature}}` 동적 필드가 배치되었습니다. 중복을 방지하기 위해서만 추가됩니다. 시스템이 처리합니다. `{{team_unsubscribe}}` 전역 추가 구독 취소 설정이 활성화된 경우와 동일한 방식입니다.

>[!TIP]
>
>동적 필드가 채워지지 않으면 체크 아웃합니다 [이 문서](/help/marketo/product-docs/marketo-sales-insight/actions/faq/why-arent-my-dynamic-fields-filling-out.md).
