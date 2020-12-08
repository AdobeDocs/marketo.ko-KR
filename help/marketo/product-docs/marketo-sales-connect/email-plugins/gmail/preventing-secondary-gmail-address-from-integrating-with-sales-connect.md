---
unique-page-id: 14352546
description: 보조 Gmail 주소가 Sales Connect - Marketing Docs - 제품 문서와 통합되지 않도록 합니다.
title: Sales Connect와 보조 Gmail 주소 통합 방지
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 0%

---


# Sales Connect와 보조 Gmail 주소 통합 방지 {#preventing-secondary-gmail-address-from-integrating-with-sales-connect}

## 깨진 Gmail 통합(개인 Gmail이 이메일을 보내는 이유는 무엇입니까) {#broken-gmail-integration-why-is-my-personal-gmail-sending-emails}

Gmail 연결이 끊어지는 가장 일반적인 이유는 사용자의 개인 계정과 우발적 통합입니다. 사용자가 &quot;Connect&quot;를 클릭하거나 개인 계정에서 이메일을 보내려고 할 때 이러한 문제가 발생할 수 있습니다. 작업 이메일과 동일한 Chrome 인스턴스에서 Gmail 계정에 액세스할 때 옵션이 존재하므로 이 옵션을 사용하기가 매우 주의해야 합니다.

## Sales Connect가 개인 Gmail과 통합하려고 하는 이유는 무엇입니까? {#why-does-sales-connect-even-try-to-integrate-with-my-personal-gmail}

Sales Connect는 Chrome 브라우저에 설치된 익스텐션을 통해 Gmail과 통합됩니다. 익스텐션에서 지메일 인스턴스를 느낄 때마다 이와 통합하는 옵션이 제공됩니다. 개인 Gmail 계정과의 통합을 방지하기 위해 다음 중 하나를 권장합니다..

다른 Chrome 사용자로 로그인(권장)

다른 Chrome 프로필을 만드는 방법을 읽으려면 [이 링크를](http://support.google.com/chrome/answer/2364824?hl=en) 클릭합니다.

**전문가**:다른 사용자로 로그인하면 새로운 Chrome 인스턴스가 열립니다. 이 인스턴스는 Chrome의 새로운 창이며, 이전 확장 기능은 이 창에 존재하지 않습니다. 쿠키가 유지되므로 매번 Gmail에 로그인할 필요가 없습니다.

**반대**:Chrome의 창이 두 개 열려 있어야 합니다.

다른 브라우저 사용

**전문가:** 확장이 설치되지 않은 다른 인터넷 브라우저(IE 또는 Firefox)를 사용하면 이 문제가 발생하지 않습니다.

**반대**:여러 브라우저를 사용하는 경우 불쾌할 수 있습니다.

Uncognito 창 사용

**전문가:** 신분을 가릴 수 없는 창문은 Chrome의 나체 버전을 여는 것과 같다. 즉, 익스텐션이 설치되어 있지 않으며 Sales Connect가 연결되지 않습니다.

**반대**:하루를 시작할 때마다 Gmail에 로그인해야 하고, 실수로 창문을 닫았다면 다시 로그인해야 합니다.
