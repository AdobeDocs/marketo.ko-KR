---
unique-page-id: 14352546
description: 보조 Gmail 주소가 Sales Connect와 통합되지 않도록 합니다. - Marketo 문서 - 제품 설명서
title: 보조 Gmail 주소가 Sales Connect와 통합되지 않도록 합니다.
exl-id: a84fe53b-0ec8-400c-8747-be496c68a8e3
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 0%

---

# 보조 Gmail 주소가 Sales Connect와 통합되지 않도록 합니다. {#preventing-secondary-gmail-address-from-integrating-with-sales-connect}

## 손상된 Gmail 통합(개인 Gmail에서 전자 메일을 보내는 이유) {#broken-gmail-integration-why-is-my-personal-gmail-sending-emails}

끊어진 Gmail 연결의 가장 일반적인 이유는 사용자의 개인 계정과의 우발적 통합입니다. 이 문제는 사용자가 &quot;연결&quot;을 클릭하거나 개인 계정에서 이메일을 전송하려고 할 때 발생할 수 있습니다. 작업 이메일과 동일한 Chrome 인스턴스에서 Gmail 계정에 액세스할 때 옵션이 존재하므로 이 작업을 수행하기가 매우 어려울 수 있습니다.

## Sales Connect가 Gmail과 통합하려고 하는 이유는 무엇입니까? {#why-does-sales-connect-even-try-to-integrate-with-my-personal-gmail}

Sales Connect는 Chrome 브라우저에 설치된 확장을 통해 Gmail과 통합됩니다. 확장에서 Gmail 인스턴스를 열 때마다 확장과 통합하는 옵션을 제공합니다. 개인 Gmail 계정과의 통합을 방지하기 위해 다음 세 가지 중 하나를 권장합니다.

다른 Chrome 사용자로 로그인(권장)

클릭 [이 링크](https://support.google.com/chrome/answer/2364824?hl=en) 다른 Chrome 프로필을 만드는 방법을 살펴보십시오.

**장점**: 다른 사용자로 로그인하면 새 Chrome 인스턴스가 열립니다. 이 인스턴스는 Chrome의 완전히 새로운 창이며 이전 확장 프로그램은 이 인스턴스에 존재하지 않습니다. 또한 쿠키가 유지되므로 매번 Gmail에 로그인할 필요가 없습니다.

**단점**: Chrome의 창이 두 개 열려 있어야 합니다.

다른 브라우저 사용

**장점:** 확장이 설치되어 있지 않은 다른 인터넷 브라우저(IE 또는 Firefox)를 사용하면 이러한 문제가 발생하지 않습니다.

**단점**: 여러 브라우저를 사용하는 것은 짜증날 수 있습니다.

Incognito 창 사용

**장점:** 시크릿 윈도우는 벌거벗은 Chrome을 여는 것과 같다. 즉, 확장이 설치되어 있지 않으며 Sales Connect가 연결할 수 없습니다.

**단점**: 하루를 시작할 때마다 Gmail에 로그인해야 하며 실수로 창을 닫으면 다시 Gmail에 로그인해야 합니다.
