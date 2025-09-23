---
unique-page-id: 1147322
description: 익명 활동 및 사용자 이해 - Marketo 문서 - 제품 설명서
title: 익명 활동 및 사용자 이해
exl-id: 1676e8f3-9138-42ed-8bb4-40e195391fc4
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 3%

---

# 익명 활동 및 사용자 이해 {#understanding-anonymous-activity-and-people}

누군가가 Marketo 랜딩 페이지(또는 [Munchkin 추적 코드](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}가 있는 웹 사이트의 페이지)를 처음 방문하면 Marketo은 *익명 활동*&#x200B;을 만들고 브라우저 쿠키를 사용하여 추적합니다. 식별되면 개인이 되고 브라우저 쿠키와 연관된 기록이 병합됩니다.

>[!IMPORTANT]
>
>Known **[!DNL Munchkin]에서 Beta 기능** V2 익명 재생 활동을 활성화하면 익명 잠재 고객이 알려진 레코드에 성공적으로 병합된 후 익명 잠재 고객 프로모션에 의해 트리거된 캠페인이 항상 재생됩니다. 따라서 재생된 캠페인에서 데이터 값 변경 단계에 의해 변경된 사용자 지정 필드는 알려진 레코드에서 유지됩니다.

**익명** 활동은 다음 경우에 만들어집니다.

* Marketo 랜딩 페이지를 처음 방문합니다.
* [Munchkin 추적](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}이 있는 사이트의 페이지를 방문합니다.
* Marketo 이메일에서 [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} 링크를 클릭합니다.

>[!NOTE]
>
>Marketo 전자 메일의 다른 링크와 달리 [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"}는 전자 메일 클릭으로 추적되지 않습니다.

누군가 다음과 같은 경우 익명 활동은 새 사용자 또는 기존 사용자에 병합됩니다.

* Marketo 전자 메일의 [링크를 클릭합니다](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md){target="_blank"}.
* Marketo [양식](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md){target="_blank"}을 작성합니다.
* Marketo의 [SOAP](/help/marketo/product-docs/administration/additional-integrations/configuring-your-soap-api-settings.md){target="_blank"} 또는 [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"} API(개발자용)를 사용하여 익명의 사용자를 알려진 레코드와 연결합니다.

사람들이 사이트를 방문하기 위해 서로 다른 디바이스와 브라우저를 사용하는 경우가 많기 때문에 데이터베이스의 한 이름이 많은 쿠키에 연결되어 있을 수 있습니다.

>[!NOTE]
>
>익명 레코드가 새 개인 레코드 또는 기존 개인 레코드에 병합되면 사용자 지정 필드 값이 *전송되지*&#x200B;합니다.
