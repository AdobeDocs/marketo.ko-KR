---
description: 동적 필드 - Marketo 문서 - 제품 설명서
title: 동적 필드
exl-id: d9e52eae-d5bb-462f-8b7b-c28a560f6ea4
source-git-commit: d9b8b92ac5f051178b8eb9b450c4949b56d50b99
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 동적 필드 {#dynamic-fields}

Adobe에서는 다음과 같은 사전 정의된 특성을 사용하여 이메일 템플릿을 개인화할 수 있습니다 `{{first_name}}` 또는 `{{company}}`. 이러한 필드를 사용하면 각 연락처에 대해 별도로 입력하지 않고도 여러 연락처를 이메일로 보내고 이러한 필드를 자동으로 완료할 수 있습니다.

>[!TIP]
>
>first_name 및 &quot;company&quot; 필드는 Sales Insight Actions와 Salesforce 모두에서 볼 수 있는 유일한 필드입니다. 즉, 연락처가 [웹 애플리케이션](https://toutapp.com/login), Salesforce에서 이메일 주소가 일치하는 연락처/리드 레코드를 찾을 수 있는지 확인합니다. 그런 다음 해당 레코드의 정보를 사용하여 필드를 채웁니다.

## 템플릿에 동적 필드 삽입 {#insert-a-dynamic-field-into-a-template}

1. in **템플릿 및 캠페인**&#x200B;편집할 템플릿을 찾은 다음 **템플릿 편집**.

1. 클릭 **동적 필드 삽입**.

   >[!NOTE]
   >
   >Sales Insight Actions에 있는 연락처로 이메일을 보낼 때 기본 동적 필드를 사용할 수 있습니다. 이러한 정보는 연락처에서 바로 가져옵니다.

Salesforce에 있는 연락처로 이메일을 보내는 경우 Salesforce 동적 필드를 활용할 수 있습니다. 이 모든 것은 &quot;sfdc&quot;로 시작합니다. Salesforce에 연결된 한 이러한 필드는 Salesforce에서 리드/연락처에 직접 호출하여 템플릿에 정보를 채웁니다.

## 제목 줄에 동적 필드 삽입 {#insert-dynamic-fields-in-a-subject-line}

이메일의 제목 필드에 수동으로 복사하여 붙여넣으면 서식이 제대로 지정되는지 확인합니다.

## 동적 필드 용어집 {#dynamic-fields-glossary}

Sales Insight Actions에서 템플릿을 만들 때는 항상 을 사용하여 동적 필드를 통합하는 것이 좋습니다. **동적 필드 삽입** 버튼을 클릭합니다.

이 도구는 `auto-personalize your email` 시간을 절약하고 `pulling information from the People page`.

| 동적 필드 | 전자 메일에 표시되는 내용의 예 |
|---|---|
| `{{company}}` | Marketo |
| `{{company_friendly}}` | Marketo |
| `{{first_name}}` | 키스 |
| `{{friendly_unsubscribe}}` | 다시 연락을 받고 싶지 않으시면 여기 알려주세요 |
| `{{my_name}}` | 앨런 브래들리 |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | 수석 기술 작가 |
| `{{work_website}}` | https://www.marketo.com |

**주목할 사항**:

* 연락처 정보를 잘못 입력하거나 사용자 페이지에서 누락된 경우 해당 연락처 정보를 템플릿에 올바르게 가져오지 않습니다.
* 차이점 `{{company}}` 및 `{{company_friendly}}` 저것은 `{{company_friendly}}` 은 연락처 회사의 이름에서 Inc., LLC 등과 같은 공식 제목을 제거합니다.
* 사용 시 `{{company_friendly}}`를 설정하는 경우 연락처 세부 정보에 쉼표를 사용하여 Inc. 또는 Co.를 구분하십시오. 다음은 Sales Insight Actions에서 값을 가져올 때 제거할 항목을 아는 방법입니다.
* Adobe에서는 다음과 같은 사전 정의된 특성을 사용하여 이메일 템플릿을 개인화할 수 있습니다 `{{my_name}}` 또는 `{{my_title}}`. 이러한 필드를 사용하면 이메일 템플릿에서 자신을 빠르게 참조할 수 있습니다.

>[!TIP]
>
>동적 필드를 채우지 않는 경우 체크 아웃하십시오 [이 문서](/help/marketo/product-docs/marketo-sales-insight/actions/faq/why-arent-my-dynamic-fields-filling-out.md).
