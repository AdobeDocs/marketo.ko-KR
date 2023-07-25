---
description: 동적 필드를 채우지 않는 이유는 무엇입니까? - Marketo 문서 - 제품 설명서
title: 동적 필드를 채우지 않는 이유는 무엇입니까?
exl-id: 4e1d133f-8314-4e64-b50b-f3e824c3bef4
feature: Sales Insight Actions
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '294'
ht-degree: 0%

---

# 동적 필드를 채우지 않는 이유는 무엇입니까? {#why-arent-my-dynamic-fields-filling-out}

동적 필드는 템플릿을 사용하는 경우에만 작동합니다. 작성한 개별 일회성 이메일은 작성되지 않습니다.

## 확인할 사항 {#what-to-check}

Sales Insight 작업에는 Basic, Custom 및 Salesforce의 세 가지 동적 필드 유형이 있습니다. 기본 과 사용자 지정 은 모두 [웹 애플리케이션](https://toutapp.com/login){target="_blank"}. If the information does not exist in the web application, the fields will be blank. Salesforce fields pull information from [Salesforce.com](https://salesforce.com){target="_blank"}.

**Salesforce 필드 문제 해결**

Salesforce 필드: 예: `{{sfdc_account_name}}`

* Sales Insight Actions 와 제대로 연결되어 있는지 확인합니다. 로 이동 [설정](https://toutapp.com/login{target="_blank"} 페이지 및 클릭 **관리** crm 옆에 있습니다.

**기본 및 사용자 정의 필드 문제 해결**

Marketo Sales Insight Actions 기본 필드: 예: `{{company}}`

Marketo Sales Insight Actions 사용자 정의 필드: 예: `{{custom_field_favorite_movie}}`

* 연락처에 대해 해당 필드를 저장해야 합니다. [사용자 페이지](https://toutapp.com/next#relationships){target="_blank"} 을 참조하십시오. 예를 들어 Mary에게 이메일을 보내고 `{{company}}` 필드에 있는데 연락처 기록에 회사가 없어서 작성할 수가 없어요.

## 모든 동적 필드를 채우지 않고 이메일이 전송된 이유는 무엇입니까? {#why-did-my-email-send-without-populating-all-dynamic-fields}

Sales Insight Actions 은 이메일의 동적 필드를 모두 채울 수 없는 경우 이메일을 보내지 못하게 합니다. **그러나**, 이 규칙에는 몇 가지 예외가 있습니다. 일부 필드는 비어 있거나, 값을 찾을 수 있는 경우 값이 자동으로 채워집니다. 이러한 필드와 필드를 채울 수 없는 경우 반응할 방식은 아래에 나와 있습니다.

`{{first_name}}` = 비어 있음

`{{last_name}}` =BLANK

`{{title}}` = 비어 있음

`{{company}}` = &quot;내 회사&quot;

`{{friendly_company}}` = &quot;내 회사&quot;

>[!NOTE]
>
>다음 `{{first_name}}` 필드는 정보를 가져오기 위해 Sales Insight Actions 과 Salesforce 를 모두 살펴봅니다. 이 목록의 다른 모든 필드는 필드를 채우기 위한 Sales Insight Actions 에서만 볼 수 있습니다.
