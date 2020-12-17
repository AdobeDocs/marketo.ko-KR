---
unique-page-id: 14352509
description: 동적 필드 용어집 - 마케팅 문서 - 제품 설명서
title: 동적 필드 용어
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 0%

---


# 동적 필드 용어집 {#dynamic-fields-glossary}

Sales Connect에서 템플릿을 만들 때는 항상 **MSE 동적 필드** 단추를 사용하여 동적 필드를 통합하는 것이 좋습니다.

이 도구는 `auto-personalize your email`에 사용되고 `pulling information from the People page`에 의해 많은 시간을 절약합니다.

| 동적 필드 | 이메일에 표시되는 내용의 예 |
|---|---|
| `{{company}}` | Marketing To |
| `{{company_friendly}}` | Marketing To |
| `{{first_name}}` | Keith |
| `{{friendly_unsubscribe}}` | 다시 연락을 받고 싶지 않으신 경우에는 여기에 알려주세요 |
| `{{my_name}}` | 앨런 브래들리 |
| `{{personal_email}}` | [[전자 메일 보호]](http://docs.marketo.com/cdn-cgi/l/email-protection) |
| `{{title}}` | 선임 기술 작가 |
| `{{work_website}}` | https://www.marketo.com |

**참고** 사항:

* 연락처의 `information is entered incorrectly`이(가) 사람 페이지에 없거나 누락된 경우 해당 연락처가 사용자의 템플릿에 `will not pull over correctly` 포함됩니다.

* `{{company}}`과 `{{company_friendly}}`의 차이점은 `{{company_friendly}}`가 `remove any formal title`(예: Inc., LLC 등)을 연락처의 회사 이름과 구별한다는 점입니다.
* `{{company_friendly}}`을 사용할 때는 연락처 세부 정보에 쉼표를 사용하여 Inc. 또는 Co.를 구분해야 합니다. 값을 가져올 때 Sales Connect에서 제거할 항목을 아는 방법입니다.

>[!TIP]
>
>이메일에 자동으로 가져오려는 모든 항목에 대해 자신의 [사용자 지정 동적 필드](http://docs.marketo.com/x/fADb)를 만들 수 있습니다.

