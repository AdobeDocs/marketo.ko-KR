---
description: 내 동적 필드가 작성되지 않는 이유 - Marketo 문서 - 제품 설명서
title: 내 동적 필드가 작성되지 않는 이유는 무엇입니까?
hide: true
hidefromtoc: true
exl-id: 4e1d133f-8314-4e64-b50b-f3e824c3bef4
source-git-commit: f77a076c243c25f3bff98a82751f51c464712795
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---

# 내 동적 필드가 작성되지 않는 이유는 무엇입니까? {#why-arent-my-dynamic-fields-filling-out}

동적 필드는 템플릿을 사용하는 경우에만 작동합니다. 사용자가 작성하는 개별 일회용 이메일은 이러한 내용을 채우지 않습니다.

## 확인할 사항 {#what-to-check}

Sales Insight Actions 에는 다음과 같은 세 가지 유형의 동적 필드가 있습니다. 기본, 사용자 정의 및 Salesforce. 기본 및 사용자 지정 모두 [웹 애플리케이션](https://toutapp.com/login). 웹 응용 프로그램에 정보가 없으면 필드가 비어 있습니다. Salesforce 필드에서 정보를 가져옵니다. [Salesforce.com](https://salesforce.com).

**Salesforce 필드 문제 해결**

Salesforce 필드: 예 `{{sfdc_account_name}}`

* Sales Insight Actions에 제대로 연결되었는지 확인합니다. 로 이동합니다. [설정](https://toutapp.com/login) 페이지를 클릭하고 **관리** CRM에 바로 옆에 있습니다.

**기본 및 사용자 지정 필드 문제 해결**

기본 필드 설명: 예 `{{company}}`

사용자 지정 필드 테스트: 예 `{{custom_field_favorite_movie}}`

* 에서 연락처에 대해 해당 필드를 저장해야 합니다 [사용자 페이지](https://toutapp.com/next#relationships) 을 참조하십시오. 예를 들어 Mary에게 이메일을 보내고 `{{company}}` 하지만 그녀의 연락처 기록이 회사를 나열하지 않아서, 우리는 그것을 작성할 수 없을 것입니다.

## 모든 동적 필드를 채우지 않고 이메일을 보낸 이유는 무엇입니까? {#why-did-my-email-send-without-populating-all-dynamic-fields}

이메일에 모든 동적 필드를 채울 수 없는 경우 Sales Insight Actions를 통해 이메일 전송이 중지됩니다. **하지만**&#x200B;에는 이 규칙에 몇 가지 예외가 있습니다. 일부 필드는 빈 필드로 전송되거나, 값을 찾을 수 있는 경우 자동으로 채웁니다. 이러한 필드와 필드를 채울 수 없는 경우 반응하는 방식이 아래에 나와 있습니다.

`{{first_name}}` = 비어 있음

`{{last_name}}` = 공백

`{{title}}` = 비어 있음

`{{company}}` = &quot;회사&quot;

`{{friendly_company}}` = &quot;회사&quot;

>[!NOTE]
>
>다음 `{{first_name}}` 이 필드는 Sales Insight Actions 과 Salesforce 모두에서 정보를 가져오려고 합니다. 이 목록의 다른 모든 필드는 필드를 채울 Sales Insight Actions만 보고 있습니다.
