---
unique-page-id: 1147322
description: 익명 활동 및 사용자 이해 - Marketo 문서 - 제품 설명서
title: 익명 활동 및 사용자 이해
exl-id: 1676e8f3-9138-42ed-8bb4-40e195391fc4
feature: Smart Lists
source-git-commit: 208ba59e3a5cb8e613e887b4c89e51cec4b3f897
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 0%

---

# 익명 활동 및 사용자 이해 {#understanding-anonymous-activity-and-people}

누군가가 Marketo 랜딩 페이지(또는 웹 사이트의 페이지에 [Munchkin 추적 코드](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}), Marketo은 *익명 활동* 브라우저 쿠키를 사용하여 추적합니다. 식별되면 개인이 되고 브라우저 쿠키와 연관된 기록이 병합됩니다.

>[!IMPORTANT]
>
>Beta 기능 활성화 **알려진 의 Munchkin V2 익명 재생 활동** 익명 잠재 고객 홍보에 의해 트리거된 캠페인은 익명 잠재 고객이 알려진 레코드에 성공적으로 병합된 후에 항상 재생되도록 합니다. 따라서 재생된 캠페인에서 데이터 값 변경 단계에 의해 변경된 사용자 지정 필드는 알려진 레코드에서 유지됩니다.

**익명** 활동은 다음과 같은 경우에 만들어집니다.

* Marketo 랜딩 페이지를 처음 방문합니다.
* 가 있는 사이트의 페이지를 방문합니다. [Munchkin 추적](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}.
* 클릭 수: [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} Marketo 이메일에 있는 링크입니다.

>[!NOTE]
>
>Marketo 이메일의 다른 링크와 달리 [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} 이메일 클릭으로 추적되지 않습니다.

누군가 다음과 같은 경우 익명 활동은 새 사용자 또는 기존 사용자에 병합됩니다.

* 클릭 수: [Marketo 이메일의 링크](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md){target="_blank"}.
* Marketo 작성 [양식](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md){target="_blank"}.
* Marketo 사용 [SOAP](/help/marketo/product-docs/administration/additional-integrations/configuring-your-soap-api-settings.md){target="_blank"} or [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"} 익명의 사용자를 알려진 레코드와 연결하기 위한 API(개발자용).

사람들이 사이트를 방문하기 위해 서로 다른 디바이스와 브라우저를 사용하는 경우가 많기 때문에 데이터베이스의 한 이름이 많은 쿠키에 연결되어 있을 수 있습니다.

>[!NOTE]
>
>익명 레코드가 새 개인 레코드 또는 기존 개인 레코드에 병합되면 사용자 정의 필드 값이 *아님* 갈아타세요
