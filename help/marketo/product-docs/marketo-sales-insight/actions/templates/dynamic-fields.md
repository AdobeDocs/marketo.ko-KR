---
description: 동적 필드 - Marketo 문서 - 제품 설명서
title: 동적 필드
exl-id: d9e52eae-d5bb-462f-8b7b-c28a560f6ea4
feature: Sales Insight Actions
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '527'
ht-degree: 0%

---

# 동적 필드 {#dynamic-fields}

`{{first_name}}` 또는 `{{company}}`과(와) 같은 미리 정의된 특성을 사용하여 전자 메일 템플릿을 개인화할 수 있습니다. 이러한 필드를 사용하면 각 연락처에 대해 별도로 입력할 필요 없이 여러 연락처를 이메일로 보내고 이러한 필드를 자동으로 완성할 수 있습니다.

>[!TIP]
>
>[!DNL Sales Insight Actions]과(와) [!DNL Salesforce]을(를) 모두 볼 수 있는 필드는 &quot;first_name&quot; 및 &quot;company&quot; 필드뿐입니다. 즉, 연락처가 [웹 응용 프로그램](https://toutapp.com/login)에 없는 경우 [!DNL Salesforce]에서 일치하는 전자 메일 주소가 있는 연락처/잠재 고객 레코드를 찾을 수 있는지 확인합니다. 그런 다음 해당 레코드의 정보를 사용하여 필드를 채웁니다.

## 템플릿에 동적 필드 삽입 {#insert-a-dynamic-field-into-a-template}

1. **[!UICONTROL Templates & Campaigns]**&#x200B;에서 편집할 템플릿을 찾은 다음 **[!UICONTROL Edit Template]**&#x200B;을(를) 클릭합니다.

1. **[!UICONTROL Insert Dynamic Field]**&#x200B;을(를) 클릭합니다.

   >[!NOTE]
   >
   >[!DNL Sales Insight Actions]에 있는 연락처로 전자 메일을 보낼 때 기본 동적 필드를 사용할 수 있습니다. 이것들은 접촉에서 바로 당겨질 것이다.

[!DNL Salesforce]에 있는 대화 상대에게 전자 메일을 보내는 경우 [!DNL Salesforce] 동적 필드를 사용할 수 있습니다. 이러한 모든 항목은 &quot;sfdc&quot;로 시작합니다. [!DNL Salesforce]에 연결되어 있는 동안에는 해당 필드가 [!DNL Salesforce]의 잠재 고객/연락처로 직접 호출되어 템플릿의 정보를 채웁니다.

## 제목 줄에 동적 필드 삽입 {#insert-dynamic-fields-in-a-subject-line}

전자 메일의 제목 필드에 수동으로 복사하여 붙여 넣기만 하면 적절한 서식이 지정되었는지 확인할 수 있습니다.

## 동적 필드 기본값 {#dynamic-field-default-values}

이메일 템플릿에 동적 필드를 추가할 때 사용 가능한 다른 값이 없는 경우 동적 필드에서 해결할 기본값을 추가할 수 있습니다.

이렇게 하려면 동적 필드 레이블 뒤에 &quot;|&quot;을 추가한 다음, &quot;기본값:&quot;(둘 다 따옴표 제외)을 추가하십시오. 다른 값을 찾을 수 없는 경우 필드가 확인할 값(따옴표로 묶음)을 추가합니다.

**예:**

`{{first name | default: "loyal customer"}}`

`{{sfdc_contact_account_name | default: "your company"}}`

## 동적 필드 용어집 {#dynamic-fields-glossary}

[!DNL Sales Insight Actions]에서 템플릿을 만들 때는 항상 **[!UICONTROL Insert Dynamic Field]** 단추를 사용하여 동적 필드를 통합하는 것이 좋습니다.

이 도구를 사용하여 `auto-personalize your email`을(를) `pulling information from the People page`까지 시간을 절약할 수 있습니다.

| 동적 필드 | 이메일에 표시되는 항목 예 |
|---|---|
| `{{company}}` | Adobe |
| `{{company_friendly}}` | Adobe |
| `{{first_name}}` | 키스 |
| `{{team_unsubscribe}}` | 더 이상 이메일을 수신하지 않으려면 여기를 클릭하십시오. |
| `{{friendly_unsubscribe}}` | 모든 이메일에 지쳤나요? 여기 좀 알려주세요 |
| `{{my_name}}` | 키스 플린 |
| `{{my_signature}}` | 선임 기술 작가 Keith Flynn - Adobe |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | 수석 기술 저자 |
| `{{work_website}}` | https://www.adobe.com/kr/ |

**참고할 사항**:

* 연락처 정보가 잘못 입력되었거나 사람 페이지에서 누락된 경우 해당 정보가 템플릿으로 올바르게 이동되지 않습니다.
* `{{company}}`과(와) `{{company_friendly}}`의 차이점은 `{{company_friendly}}`이(가) 연락처의 회사 이름에서 Inc., LLC 등과 같은 형식 제목을 제거한다는 것입니다.
* `{{company_friendly}}`을(를) 사용하는 경우 연락처 세부 정보에서 쉼표로 Inc. 또는 Co.를 구분해야 합니다. 값을 가져올 때 [!DNL Sales Insight Actions]이(가) 제거할 항목을 아는 방법입니다.
* `{{my_name}}` 또는 `{{my_title}}`과(와) 같은 미리 정의된 특성을 사용하여 전자 메일 템플릿을 개인화할 수 있습니다. 이러한 필드를 사용하면 전자 메일 템플릿에서 자신을 빠르게 참조할 수 있습니다.
* 시스템에서는 보낸 각 이메일에 사용자 서명을 자동으로 추가합니다. 사용자가 `{{my_signature}}` 동적 필드가 있는 템플릿을 사용하는 경우 시스템에서 `{{my_signature}}` 동적 필드가 있는 서명을 채웁니다. 중복을 방지하기 위해서만 추가됩니다. 전역 추가 구독 취소 설정이 사용되는 경우 시스템은 `{{team_unsubscribe}}`을(를) 같은 방식으로 처리합니다.

>[!TIP]
>
>동적 필드가 채워지지 않으면 [이 문서](/help/marketo/product-docs/marketo-sales-insight/actions/faq/why-arent-my-dynamic-fields-filling-out.md)를 확인하십시오.
