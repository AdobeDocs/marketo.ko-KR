---
unique-page-id: 1147322
description: 익명의 활동 및 사용자 이해 - Marketing Docs - 제품 설명서
title: 익명 활동 및 사람 이해
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '270'
ht-degree: 0%

---


# 익명 활동 및 사람 이해 {#understanding-anonymous-activity-and-people}

누군가 Marketing to [l `anding page`](http://docs.marketo.com/display/DOCS/Personalizing+Landing+Pages) (또는 [Munchkin 추적 코드가](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)있는 웹 사이트의 페이지)을 처음 방문하는 경우, Marketing은 익명 **활동* 을 만들고 브라우저 쿠키를 사용하여 추적합니다. 식별되면 사람이 되며 브라우저 쿠키와 연관된 내역이 병합됩니다.

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

**익명의** 활동은 다음과 같은 경우에 만들어집니다.

* 마케팅 랜딩 페이지를 처음 방문합니다.

* Munchkin 추적이 있는 사이트의 [페이지를 방문합니다](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).

* Marketing [To 이메일에서 웹 페이지로](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 보기 링크를 클릭합니다.

>[!NOTE]
>
>Marketing To 이메일의 다른 링크와 달리, [웹 페이지로](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 보기는 이메일 클릭으로 추적되지 않습니다.

익명의 활동은 다음과 같은 경우에 신규 또는 기존 사용자로 병합됩니다.

* Marketing [to 이메일에 있는 링크를 클릭합니다](../../../../product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md).
* 마케팅 [양식](../../../../product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md)채우기
* Marketing의 [SOAP](http://docs.marketo.com/pages/viewpage.action?pageid=7509846) 또는 [Munchkin](../../../../product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) API(개발자용)를 사용하여 익명 사용자를 알려진 기록과 연결합니다.

사람들이 종종 다른 장치 및 브라우저를 사용하여 사이트를 방문하기 때문에 데이터베이스의 한 이름이 여러 쿠키에 연결될 수 있습니다.

>[!NOTE]
>
>익명 레코드가 새 개인 레코드나 기존 개인 레코드로 병합되면 사용자 지정 필드 값이 전송되지 **않습니다** .

