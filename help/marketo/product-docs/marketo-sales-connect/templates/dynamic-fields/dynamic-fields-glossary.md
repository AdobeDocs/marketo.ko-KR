---
unique-page-id: 14352509
description: 동적 필드 용어집 - Marketo 문서 - 제품 설명서
title: 동적 필드 용어집
exl-id: 28351ba9-53da-4408-9526-918200d9bd29
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '240'
ht-degree: 3%

---

# 동적 필드 용어집 {#dynamic-fields-glossary}

[!DNL Sales Connect]에서 템플릿을 만들 때는 항상 **[!UICONTROL MSE Dynamic Fields]** 단추를 사용하여 동적 필드를 통합하는 것이 좋습니다.

이 도구를 사용하여 `auto-personalize your email`을(를) `pulling information from the [!UICONTROL People] page`까지 시간을 절약할 수 있습니다.

| 동적 필드 | 이메일에 표시되는 항목 예 |
|---|---|
| `{{company}}` | Adobe |
| `{{company_friendly}}` | Adobe |
| `{{first_name}}` | 키스 |
| `{{team_unsubscribe}}` | 더 이상 이메일을 수신하지 않으려면 여기를 클릭하십시오. |
| `{{friendly_unsubscribe}}` | 모든 이메일에 지쳤나요? 여기 좀 알려주세요 |
| `{{my_name}}` | 키스 플린 |
| `{{my_signature}}` | 선임 기술 작가 Keith Flynn - Adobe |
| `{{personal_email}}` | <keith@pickyouremail.com> |
| `{{title}}` | 수석 기술 저자 |
| `{{work_website}}` | <https://www.adobe.com> |

**참고할 사항**:

* 연락처 정보가 잘못 입력되었거나 사람 페이지에서 누락된 경우 해당 정보가 템플릿으로 올바르게 이동되지 않습니다.
* `{{company}}`과(와) `{{company_friendly}}`의 차이점은 `{{company_friendly}}`이(가) 연락처의 회사 이름에서 Inc., LLC 등과 같은 형식 제목을 제거한다는 것입니다.
* `{{company_friendly}}`을(를) 사용하는 경우 연락처 세부 정보에서 쉼표로 Inc. 또는 Co.를 구분해야 합니다. Sales Connect는 이러한 방식으로 값을 가져올 때 제거해야 할 사항을 알게 됩니다.
* 시스템에서는 보낸 각 이메일에 사용자 서명을 자동으로 추가합니다. 사용자가 `{{my_signature}}` 동적 필드가 있는 템플릿을 사용하는 경우 시스템에서 `{{my_signature}}` 동적 필드가 있는 서명을 채웁니다. 중복을 방지하기 위해서만 추가됩니다. 전역 추가 구독 취소 설정이 사용되는 경우 시스템은 `{{team_unsubscribe}}`을(를) 같은 방식으로 처리합니다.

>[!TIP]
>
>자동으로 전자 메일로 가져오려는 모든 항목에 대해 자신만의 [사용자 지정 동적 필드](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/create-custom-dynamic-fields.md)를 만들 수 있습니다.
