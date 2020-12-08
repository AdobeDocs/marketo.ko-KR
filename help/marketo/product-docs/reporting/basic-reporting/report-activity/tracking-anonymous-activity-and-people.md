---
unique-page-id: 2360181
description: 익명의 활동 및 사용자 추적 - Marketing Docs - 제품 설명서
title: 익명 활동 및 사람 추적
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---


# 익명 활동 및 사람 추적 {#tracking-anonymous-activity-and-people}

누군가 Marketing to [랜딩 페이지](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) (또는 [Munchkin 추적 코드가](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)있는 웹 사이트의 페이지 *)를 처음 방문하면, Marketing은* 익명 *활동을 만들고* 브라우저 쿠키를 사용하여 추적합니다. 방문자가 식별되면 방문자가 되고 브라우저 쿠키와 연관된 내역이 병합됩니다.

1. 다음과 같은 경우에 익명 활동이 만들어집니다.

   * 마케팅 [랜딩 페이지를](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) 처음 방문합니다.
   * Munchkin 추적이 있는 사이트의 [페이지를 방문합니다](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
   * Marketing [To 이메일에서 웹 페이지로](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 보기 링크를 클릭합니다.

   >[!NOTE]
   >
   >Marketing To 이메일의 다른 링크와 달리, 웹 페이지로 보기는 이메일 클릭으로 추적되지 않습니다.

   익명의 활동은 다음과 같은 경우에 신규 또는 기존 사용자로 병합됩니다.

   * Marketing [to 이메일에 있는 링크를 클릭합니다](../../../../product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
   * 마케팅 [양식](http://docs.marketo.com/display/docs/forms)채우기
   * Marketing의 [REST API](http://developers.marketo.com/rest-api/lead-database/leads/) 또는 [Munchkin](http://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/) API(개발자용)를 사용하여 익명 활동과 알려진 레코드를 연결합니다.

   사람들이 종종 다른 장치 및 브라우저를 사용하여 사이트를 방문하기 때문에 데이터베이스의 한 이름이 여러 쿠키에 연결될 수 있습니다.

   >[!NOTE]
   >
   >익명 레코드가 새 개인 레코드나 기존 개인 레코드로 병합되면 사용자 지정 필드 값이 전송되지 **않습니다** .

   >[!NOTE]
   >
   >**관련 문서**
   >
   >    
   >    
   >    * [웹 보고서에 사람 또는 익명 방문자 표시](display-people-or-anonymous-visitors-in-web-reports.md)


   >[!NOTE]
   >
   >**딥 다이브**
   >
   >
   >기본 보고에 대한 자세한 [내용을 살펴보십시오](http://docs.marketo.com/display/docs/basic+reporting).

