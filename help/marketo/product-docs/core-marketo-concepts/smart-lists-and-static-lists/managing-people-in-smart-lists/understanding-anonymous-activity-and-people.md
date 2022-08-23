---
unique-page-id: 1147322
description: 익명 활동 및 사람 이해 - Marketo 문서 - 제품 설명서
title: 익명 활동 및 사람 이해
exl-id: 1676e8f3-9138-42ed-8bb4-40e195391fc4
source-git-commit: cc66f4ff2e3e0e6ddfabab91215e3ad31f3b9226
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 0%

---

# 익명 활동 및 사람 이해 {#understanding-anonymous-activity-and-people}

사용자가 처음으로 Marketo 랜딩 페이지를 방문하거나 [Munchkin 추적 코드](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)로 지정하는 경우 Marketo이 생성합니다 _익명 활동_ 및 은 브라우저 쿠키를 사용하여 추적합니다. 식별되면 개인이 되고 브라우저 쿠키와 연결된 기록이 병합됩니다.

>[!IMPORTANT]
>
>베타 기능 활성화 **알려진 Munchkin V2 익명 재생 활동** 익명 리드 프로모션에 의해 트리거된 캠페인이 알려진 레코드에 성공적으로 병합된 후 항상 다시 재생되도록 합니다. 따라서 재생된 캠페인에서 데이터 값 변경 단계에서 변경된 사용자 지정 필드는 알려진 레코드에 유지됩니다.

**익명** 활동은 다음과 같은 경우에 생성됩니다.

* 처음으로 Marketo 랜딩 페이지를 방문합니다.
* 가 있는 사이트의 페이지를 방문합니다. [Munchkin 추적](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
* 클릭 [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 링크를 클릭합니다.

>[!NOTE]
>
>Marketo 이메일의 다른 링크와 달리, [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 은 이메일 클릭으로 추적되지 않습니다.

익명 활동은 다음과 같은 경우에 새로 만들거나 기존 사람에게 병합됩니다.

* 클릭 [Marketo 이메일에 링크](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md).
* Marketo 채우기 [양식](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md).
* Marketo 사용 [SOAP](/help/marketo/product-docs/administration/additional-integrations/configuring-your-soap-api-settings.md) 또는 [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) 익명 사용자를 알려진 레코드와 연결할 API(개발자용)

사람들이 종종 다른 장치와 브라우저를 사용하여 사이트를 방문하기 때문에 데이터베이스의 한 이름이 많은 쿠키에 연결되어 있을 수 있습니다.

>[!NOTE]
>
>익명 레코드가 신규 또는 기존 개인 레코드에 병합되면 사용자 지정 필드 값이 **not** 갈아타세요
