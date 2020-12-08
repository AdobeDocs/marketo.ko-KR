---
unique-page-id: 14352602
description: 내 동적 필드가 채워지지 않음 - Marketing Docs - 제품 설명서
title: 내 동적 필드가 채워지지 않음
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '290'
ht-degree: 0%

---


# 내 동적 필드가 채워지지 않음 {#my-dynamic-fields-arent-filling-out}

동적 필드는 템플릿을 사용하는 경우에만 작동합니다. 개별 일회성 이메일로는 내용을 입력하지 않습니다.

## 확인 사항 {#what-to-check}

Sales Connect에는 세 가지 유형의 동적 필드가 있습니다.기본, 맞춤형 및 Salesforce. 기본 및 사용자 지정 모두 [웹 애플리케이션에서 정보를 가져옵니다](http://toutapp.com/login). 웹 응용 프로그램에 정보가 없으면 필드가 비어 있게 됩니다. Salesforce 필드는 [Salesforce.com에서 정보를 가져옵니다](http://salesforce.com).

`**Troubleshooting Salesforce Fields**`

Salesforce 필드:예: `{{sfdc_account_name}}`

* Sales Connect와 제대로 연결되었는지 확인하십시오. [ [설정](http://toutapp.com/next#settings) ] 페이지로 이동하여 CRM **옆의 [관리** ]를 클릭합니다.

**기본 및 사용자 지정 필드 문제 해결**

기본 필드 체크아웃:예: `{{company}}`

사용자 정의 필드 체크아웃:예: `{{custom_field_favorite_movie}}`

* 사용자 페이지 `he corresponding field needs to be saved for your contact` 에서 [동적 필드를 참조하기](http://toutapp.com/next#relationships) 위해 선택합니다. 예를 들어, Mary에게 이메일을 보내고 이 `{{company}}` 필드를 사용하는 경우, Mary의 연락처 기록에 회사가 나열되지 않는다면, 우리는 그 내용을 채울 수 없을 것입니다.

## 모든 동적 필드를 채우지 않고 이메일을 보낸 이유는 무엇입니까? {#why-did-my-email-send-without-populating-all-dynamic-fields}

이메일의 모든 동적 필드를 채울 수 없는 경우 Sales Connect는 이메일 전송을 중지합니다. **하지만**&#x200B;이 규칙에는 몇 가지 예외가 있습니다. 일부 필드는 공백으로 출력되거나, 찾을 수 있는 경우 값을 자동으로 채웁니다. 이 필드와 필드가 아래 나열된 것처럼 필드를 채울 수 없을 경우 어떻게 반응할지 지정합니다.

`{{first_name}}` = BLANK

`{{last_name}}` BLANK

`{{title}}` = BLANK

`{{company}}` = &quot;회사&quot;

`{{friendly_company}}` = &quot;회사&quot;

>[!NOTE]
>
>이 `{{first_name}}` 필드는 Sales Connect와 Salesforce에서 정보를 가져오려고 합니다. 이 목록의 다른 모든 필드는 Sales Connect에서만 필드를 채웁니다.

