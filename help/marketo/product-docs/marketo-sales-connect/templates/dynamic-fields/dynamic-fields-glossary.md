---
unique-page-id: 14352509
description: 동적 필드 용어집 - 마케팅 문서 - 제품 설명서
title: 동적 필드 용어집
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 0%

---


# 동적 필드 용어집 {#dynamic-fields-glossary}

Sales Connect에서 템플릿을 만들 때는 항상 MSE 동적 필드 **단추를 사용하여 동적 필드를 통합하는 것이** 좋습니다.

이 도구는 시간 `auto-personalize your email` 을 크게 절약하는 데 사용됩니다 `pulling information from the People page`.

| 동적 필드 | 이메일에 표시되는 내용 예 |
|---|---|
| `{{company}}` | Marketing |
| `{{company_friendly}}` | Marketing |
| `{{first_name}}` | Keith |
| `{{friendly_unsubscribe}}` | 다시 연락을 받고 싶지 않으시면 여기 알려주세요 |
| `{{my_name}}` | 앨런 브래들리 |
| `{{personal_email}}` | [[이메일 보호됨]](http://docs.marketo.com/cdn-cgi/l/email-protection) |
| `{{title}}` | 선임 기술 작가 |
| `{{work_website}}` | https://www.marketo.com |

**참고**&#x200B;사항:

* 사람 페이지에서 연락처가 `information is entered incorrectly` 없거나 누락된 경우 해당 연락처 `will not pull over correctly` 가 템플릿에 추가됩니다.

* 와 `{{company}}` 의 `{{company_friendly}}` 차이는 연락처의 회사명 `{{company_friendly}}` `remove any formal title`에서 Inc., LLC 등과 같은 의사 결정 때문입니다.
* 사용 `{{company_friendly}}`시 연락처 세부 정보에 쉼표를 사용하여 Inc. 또는 Co.를 구분해야 합니다. 값을 가져올 때 Sales Connect에서 제거할 항목을 아는 방법입니다.

>[!TIP]
>
>이메일에 자동으로 [가져오려는 모든 항목에 대해 고유한 사용자 지정 동적 필드](http://docs.marketo.com/x/fADb) 만들기

