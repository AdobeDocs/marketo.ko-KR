---
unique-page-id: 14352509
description: 동적 필드 용어집 - Marketo 문서 - 제품 설명서
title: 동적 필드 용어집
exl-id: 28351ba9-53da-4408-9526-918200d9bd29
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%

---

# 동적 필드 용어집 {#dynamic-fields-glossary}

Sales Connect에서 템플릿을 만들 때는 항상 을 사용하여 동적 필드를 통합하는 것이 좋습니다. **MSE 동적 필드** 버튼을 클릭합니다.

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
* 사용 시 `{{company_friendly}}`를 설정하는 경우 연락처 세부 정보에 쉼표를 사용하여 Inc. 또는 Co.를 구분하십시오. 다음은 Sales Connect에서 값을 가져올 때 제거할 항목을 아는 방법입니다.

>[!TIP]
>
>직접 만들 수 있습니다 [사용자 지정 동적 필드](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/create-custom-dynamic-fields.md) 전자 메일에 자동으로 가져오려는 모든 경우
