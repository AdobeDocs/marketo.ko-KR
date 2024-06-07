---
unique-page-id: 2360181
description: 익명 활동 및 사용자 추적 - Marketo 문서 - 제품 설명서
title: 익명 활동 및 사용자 추적
exl-id: 95a39e57-4636-4bae-8ca8-00cb43cb566c
feature: Reporting
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---

# 익명 활동 및 사용자 추적 {#tracking-anonymous-activity-and-people}

누군가가 Marketo을 처음 방문하는 경우 [랜딩 페이지](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) (또는 웹 사이트의 페이지에 [Munchkin 추적 코드](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)), Marketo은 _익명 활동_ 브라우저 쿠키를 사용하여 추적합니다. 방문자가 식별되면 개인이 되고 브라우저 쿠키와 연관된 내역이 병합됩니다.

1. 익명 활동은 다음과 같은 경우에 만들어집니다.

   * Marketo 방문 횟수 [랜딩 페이지](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) 처음.
   * 가 있는 사이트의 페이지를 방문합니다. [Munchkin 추적](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
   * 클릭 수: [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) Marketo 이메일에 있는 링크입니다.

   >[!NOTE]
   >
   >Marketo 이메일의 다른 링크와 달리 웹 페이지로 보기 는 이메일 클릭으로 추적되지 않습니다.

   누군가 다음과 같은 경우 익명 활동은 새 사용자 또는 기존 사용자에 병합됩니다.

   * 클릭 수: [Marketo 이메일의 링크](/help/marketo/product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
   * Marketo 작성 [양식](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md).
   * Marketo 사용 [나머지 API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/leads) 또는 [먼치킨](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/lead-tracking) 익명 활동을 알려진 레코드와 연결하는 API(개발자용).

   사람들이 사이트를 방문하기 위해 서로 다른 디바이스와 브라우저를 사용하는 경우가 많기 때문에 데이터베이스의 한 이름이 많은 쿠키에 연결되어 있을 수 있습니다.

   >[!NOTE]
   >
   >익명 레코드가 새 개인 레코드 또는 기존 개인 레코드에 병합되면 사용자 정의 필드 값이 **아님** 갈아타세요

   >[!MORELIKETHIS]
   >
   >[웹 보고서에 사람 또는 익명 방문자 표시](/help/marketo/product-docs/reporting/basic-reporting/report-activity/display-people-or-anonymous-visitors-in-web-reports.md)
