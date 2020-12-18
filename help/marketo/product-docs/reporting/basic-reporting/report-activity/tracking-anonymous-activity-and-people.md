---
unique-page-id: 2360181
description: 익명의 활동 및 사람 추적 - 마케팅 문서 - 제품 설명서
title: 익명 활동 및 사람 추적
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---


# 익명 활동 및 사람 추적 {#tracking-anonymous-activity-and-people}

사용자가 Marketing에 [랜딩 페이지](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md)(또는 [Munchkin 추적 코드](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)가 있는 웹 사이트의 페이지)를 처음 방문하는 경우 Marketing은 *익명* *활동*&#x200B;을 만들고 브라우저 쿠키를 사용하여 이를 추적합니다. 방문자가 식별되면 방문자가 되고 브라우저 쿠키와 연관된 작업 내역이 병합됩니다.

1. 다음과 같은 경우 익명의 활동이 만들어집니다.

   * 처음으로 [랜딩 페이지](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md)에 방문합니다.
   * [Munchkin 추적](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)이(가) 있는 사이트의 페이지를 방문합니다.
   * 마케팅 전자 메일에서 [웹 페이지로 보기](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 링크를 클릭합니다.

   >[!NOTE]
   >
   >마케팅 이메일의 다른 링크와 달리 웹 페이지로 보기는 이메일 클릭으로 추적되지 않습니다.

   익명의 활동은 다음과 같은 경우에 신규 또는 기존 사람에게 병합됩니다.

   * 마케팅 이메일](../../../../product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md)에서 [링크를 클릭합니다.
   * [양식](http://docs.marketo.com/display/docs/forms)을(를) 채웁니다.
   * Marketing의 [REST API](http://developers.marketo.com/rest-api/lead-database/leads/) 또는 [Munchkin](http://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/) API(개발자용)를 사용하여 익명 활동을 알려진 레코드와 연결합니다.

   사람들이 사이트를 방문하기 위해 서로 다른 장치 및 브라우저를 사용하는 경우가 많기 때문에 데이터베이스의 한 이름이 여러 쿠키에 연결되어 있을 수 있습니다.

   >[!NOTE]
   >
   >익명 레코드가 새 개인 레코드나 기존 개인 레코드로 병합되면 사용자 지정 필드 값이 **로 전송되지 않습니다.**

   >[!NOTE]
   >
   >**관련 문서**
   >
   >    
   >    
   >    * [웹 보고서에 사람 또는 익명 방문자 표시](display-people-or-anonymous-visitors-in-web-reports.md)


   >[!NOTE]
   >
   >**자세히 알아보기**
   >
   >
   >[기본 보고](http://docs.marketo.com/display/docs/basic+reporting)에 대해 자세히 알아보십시오.

