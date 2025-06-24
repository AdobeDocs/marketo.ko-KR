---
unique-page-id: 2360181
description: 익명 활동 및 사용자 추적 - Marketo 문서 - 제품 설명서
title: 익명 활동 및 사용자 추적
exl-id: 95a39e57-4636-4bae-8ca8-00cb43cb566c
feature: Reporting
source-git-commit: e3f61755dccd9bea1378a429fc428b440fc3ecb4
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---

# 익명 활동 및 사용자 추적 {#tracking-anonymous-activity-and-people}

누군가가 Marketo [랜딩 페이지](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md)(또는 [Munchkin 추적 코드](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)가 있는 웹 사이트의 페이지)를 처음 방문하면, Marketo은 _익명 활동_&#x200B;을 만들고 브라우저 쿠키를 사용하여 추적합니다. 방문자가 식별되면 개인이 되고 브라우저 쿠키와 연관된 내역이 병합됩니다.

1. 익명 활동은 다음과 같은 경우에 만들어집니다.

   * Marketo [랜딩 페이지](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md)를 처음 방문합니다.
   * [Munchkin 추적](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)이 있는 사이트의 페이지를 방문합니다.
   * Marketo 이메일에서 [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 링크를 클릭합니다.

   >[!NOTE]
   >
   >Marketo 이메일의 다른 링크와 달리 웹 페이지로 보기 는 이메일 클릭으로 추적되지 않습니다.

   누군가 다음과 같은 경우 익명 활동은 새 사용자 또는 기존 사용자에 병합됩니다.

   * Marketo 전자 메일의 [링크를 클릭합니다](/help/marketo/product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
   * Marketo [form](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md)을(를) 채웁니다.
   * Marketo의 [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/leads) 또는 [Munchkin](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/leadtracking/lead-tracking) API(개발자용)를 사용하여 익명 활동을 알려진 레코드와 연결합니다.

   사람들이 사이트를 방문하기 위해 서로 다른 디바이스와 브라우저를 사용하는 경우가 많기 때문에 데이터베이스의 한 이름이 많은 쿠키에 연결되어 있을 수 있습니다.

   >[!NOTE]
   >
   >익명 레코드가 새 개인 레코드 또는 기존 개인 레코드에 병합되면 사용자 지정 필드 값이 **전송되지**&#x200B;합니다.

   >[!MORELIKETHIS]
   >
   >[웹 보고서에 사람 또는 익명 방문자 표시](/help/marketo/product-docs/reporting/basic-reporting/report-activity/display-people-or-anonymous-visitors-in-web-reports.md)
