---
unique-page-id: 1147322
description: 익명 활동 및 사람 이해 - Marketo 문서 - 제품 설명서
title: 익명 활동 및 사람 이해
exl-id: 1676e8f3-9138-42ed-8bb4-40e195391fc4
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '208'
ht-degree: 0%

---

# 익명 활동 및 사람 이해 {#understanding-anonymous-activity-and-people}

Marketo 랜딩 페이지(또는 [Munchkin 추적 코드](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)가 있는 웹 사이트의 페이지를 처음 방문하는 Marketo은 _익명 활동_&#x200B;을 만들고 브라우저 쿠키를 사용하여 추적합니다. 식별되면 개인이 되고 브라우저 쿠키와 연관된 기록이 병합됩니다.

**다음과** 같은 경우 익명성이 만들어집니다.

* Marketo 랜딩 페이지를 처음 방문합니다.
* [Munchkin 추적](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)이(가) 있는 사이트의 페이지를 방문합니다.
* Marketo 이메일에서 [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 링크를 클릭합니다.

>[!NOTE]
>
>Marketo 이메일의 다른 링크와 달리 [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md)는 이메일 클릭으로 추적되지 않습니다.

익명의 활동은 다음과 같은 경우에 신규 또는 기존 사람에게 병합됩니다.

* Marketo 이메일](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md)에서 [링크를 클릭합니다.
* Marketo [양식](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md)을 채웁니다.
* Marketo의 [SOAP](/help/marketo/product-docs/administration/additional-integrations/configuring-your-soap-api-settings.md) 또는 [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) API(개발자용)를 사용하여 익명 사용자를 알려진 레코드에 연결합니다.

사람들이 사이트를 방문하기 위해 서로 다른 장치 및 브라우저를 사용하는 경우가 많기 때문에 데이터베이스의 한 이름이 여러 쿠키에 연결되어 있을 수 있습니다.

>[!NOTE]
>
>익명 레코드가 새 개인 레코드나 기존 개인 레코드로 병합되면 사용자 지정 필드 값이 **로 전송되지 않습니다.**
