---
unique-page-id: 14352602
description: 내 동적 필드가 채워지지 않음 - 마케팅 문서 - 제품 설명서
title: 내 동적 필드가 채워지지 않음
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '290'
ht-degree: 0%

---


# 내 동적 필드가 {#my-dynamic-fields-arent-filling-out}을(를) 채우지 않습니다.

동적 필드는 템플릿을 사용하는 경우에만 작동합니다. 당신이 쓴 개별 일회성 이메일은 이것을 채우지 않습니다.

## {#what-to-check} 확인

Sales Connect에는 3가지 유형의 동적 필드가 있습니다.기본, 맞춤형 및 Salesforce. 기본 및 사용자 지정 모두 [웹 응용 프로그램](http://toutapp.com/login)에서 정보를 가져옵니다. 웹 응용 프로그램에 정보가 없으면 필드가 비어 있게 됩니다. Salesforce 필드는 [Salesforce.com](http://salesforce.com)에서 정보를 가져옵니다.

`**Troubleshooting Salesforce Fields**`

Salesforce 필드:예:`{{sfdc_account_name}}`

* Sales Connect에 제대로 연결되었는지 확인합니다. [설정](http://toutapp.com/next#settings) 페이지로 이동하여 CRM 옆에 있는 **관리**&#x200B;를 클릭합니다.

**기본 및 사용자 지정 필드 문제 해결**

기본 필드 체크아웃:예:`{{company}}`

사용자 정의 필드 체크아웃:예:`{{custom_field_favorite_movie}}`

* 참조할 동적 필드에 대한 [사람 페이지](http://toutapp.com/next#relationships)의 `he corresponding field needs to be saved for your contact`에 있습니다. 예를 들어 Mary에게 이메일을 보내고 `{{company}}` 필드를 사용하지만 그녀의 연락처 기록에 회사가 나열되지 않는 경우 해당 내용을 채울 수 없습니다.

## 모든 동적 필드를 채우지 않고 전자 메일을 보낸 이유는 무엇입니까?{#why-did-my-email-send-without-populating-all-dynamic-fields}

이메일의 모든 동적 필드를 채울 수 없는 경우 Sales Connect는 이메일 전송을 중단합니다. **그러나** 이 규칙에는 몇 가지 예외가 있습니다. 일부 필드는 공백으로 출력되거나, 찾을 수 있으면 자동으로 값을 채웁니다. 이 필드와 필드가 필드를 채우지 못할 경우 필드가 응답하는 방법이 아래에 나열되어 있습니다.

`{{first_name}}` = 공백

`{{last_name}}` = 공백

`{{title}}` = 공백

`{{company}}` = &quot;회사&quot;

`{{friendly_company}}` = &quot;회사&quot;

>[!NOTE]
>
>`{{first_name}}` 필드는 Sales Connect와 Salesforce에서 정보를 가져오려고 합니다. 이 목록의 다른 모든 필드는 필드를 채우려면 Sales Connect만 찾습니다.

