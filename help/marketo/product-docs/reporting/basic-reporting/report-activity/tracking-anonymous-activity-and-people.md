---
unique-page-id: 2360181
description: 익명 활동 및 사람 추적 - Marketo 문서 - 제품 설명서
title: 익명 활동 및 사람 추적
exl-id: 95a39e57-4636-4bae-8ca8-00cb43cb566c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '229'
ht-degree: 0%

---

# 익명 활동 및 사람 추적 {#tracking-anonymous-activity-and-people}

Marketo을 처음 방문한 사람 [랜딩 페이지](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) (또는 [Munchkin 추적 코드](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)). Marketo이 _익명 활동_ 및 은 브라우저 쿠키를 사용하여 추적합니다. 방문자가 식별되면 개인이 되고 브라우저 쿠키와 연관된 기록이 병합됩니다.

1. 누군가 다음 경우에 익명 활동이 만들어집니다.

   * Marketo 방문 [랜딩 페이지](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) 처음으로
   * 가 있는 사이트의 페이지를 방문합니다. [Munchkin 추적](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
   * 클릭 [웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 링크를 클릭합니다.

   >[!NOTE]
   >
   >Marketo 이메일의 다른 링크와 달리 웹 페이지로 보기는 이메일 클릭으로 추적되지 않습니다.

   익명 활동은 다음과 같은 경우에 새로 만들거나 기존 사람에게 병합됩니다.

   * 클릭 [Marketo 이메일에 링크](/help/marketo/product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
   * Marketo 채우기 [양식](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md).
   * Marketo 사용 [REST API](https://developers.marketo.com/rest-api/lead-database/leads/) 또는 [Munchkin](https://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/) 익명 활동을 알려진 레코드와 연결하기 위한 API(개발자용)

   사람들이 종종 다른 장치와 브라우저를 사용하여 사이트를 방문하기 때문에 데이터베이스의 한 이름이 많은 쿠키에 연결되어 있을 수 있습니다.

   >[!NOTE]
   >
   >익명 레코드가 신규 또는 기존 개인 레코드에 병합되면 사용자 지정 필드 값이 **not** 갈아타세요

   >[!MORELIKETHIS]
   >
   >[웹 보고서에 사람 또는 익명 방문자 표시](/help/marketo/product-docs/reporting/basic-reporting/report-activity/display-people-or-anonymous-visitors-in-web-reports.md)
