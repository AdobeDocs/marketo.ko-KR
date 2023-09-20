---
unique-page-id: 14352509
description: 동적 필드 용어집 - Marketo 문서 - 제품 설명서
title: 동적 필드 용어집
exl-id: 28351ba9-53da-4408-9526-918200d9bd29
feature: Marketo Sales Connect
source-git-commit: d6a3d95ed42d1c08d69014e1aa013e7436bd06c2
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 1%

---

# 동적 필드 용어집 {#dynamic-fields-glossary}

Sales Connect에서 템플릿을 생성할 때는 항상 를 사용하여 동적 필드를 통합하는 것이 좋습니다. **MSE 동적 필드** 단추를 클릭합니다.

이 도구는 다음 용도로 사용됩니다. `auto-personalize your email` and save you tton of time `pulling information from the People page`.

| 동적 필드 | 이메일에 표시되는 항목 예 |
|---|---|
| `{{company}}` | Adobe |
| `{{company_friendly}}` | Adobe |
| `{{first_name}}` | 키스 |
| `{{friendly_unsubscribe}}` | 다시 소식을 듣고 싶지 않으시면 여기 좀 알려주세요 |
| `{{my_name}}` | 키스 플린 |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | 수석 기술 저자 |
| `{{work_website}}` | https://www.adobe.com |

**유의할 사항**:

* 연락처 정보가 잘못 입력되었거나 사람 페이지에서 누락된 경우 해당 정보가 템플릿으로 올바르게 이동되지 않습니다.
* 차이점 `{{company}}` 및 `{{company_friendly}}` 다음과 같음 `{{company_friendly}}` 은(는) 귀하의 연락처 회사의 이름에서 Inc., LLC 등과 같은 공식적인 제목을 제거합니다.
* 사용 시 `{{company_friendly}}`연락처 세부 정보에서 쉼표로 Inc. 또는 Co.를 구분해야 합니다. Sales Connect는 이러한 방식으로 값을 가져올 때 제거해야 할 사항을 알게 됩니다.

>[!TIP]
>
>자신만의 고유한 을 만들 수 있습니다. [사용자 정의 동적 필드](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/create-custom-dynamic-fields.md) 자동으로 이메일에 넣고 싶은 모든 항목
