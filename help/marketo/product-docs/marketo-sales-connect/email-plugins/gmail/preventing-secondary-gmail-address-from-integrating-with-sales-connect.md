---
unique-page-id: 14352546
description: 보조 Gmail 주소가 Sales Connect - Marketo 문서 - 제품 설명서와 통합되지 않음
title: 보조 Gmail 주소가 Sales Connect와 통합되지 않도록 방지
exl-id: a84fe53b-0ec8-400c-8747-be496c68a8e3
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '325'
ht-degree: 0%

---

# 보조 Gmail 주소가 Sales Connect와 통합되지 않도록 방지 {#preventing-secondary-gmail-address-from-integrating-with-sales-connect}

## 끊어진 Gmail 통합(내 개인 Gmail에서 이메일을 보내는 이유) {#broken-gmail-integration-why-is-my-personal-gmail-sending-emails}

Gmail 연결이 끊어진 가장 일반적인 이유는 사용자의 개인 계정과 우연한 통합입니다. 이 문제는 사용자가 &quot;연결&quot;을 클릭하거나 개인 계정에서 이메일을 보내려고 할 때 발생할 수 있습니다. 작업 이메일과 동일한 Chrome 인스턴스에 있는 Gmail 계정에 액세스할 때 옵션이 존재하므로 이 작업을 수행하는 것이 매우 빠를 수 있습니다.

## Sales Connect에서 개인 Gmail과 통합하려고 하는 이유는 무엇입니까? {#why-does-sales-connect-even-try-to-integrate-with-my-personal-gmail}

Sales Connect는 Chrome 브라우저에 설치된 확장을 통해 Gmail과 통합됩니다. 확장에서 Gmail 인스턴스가 열리는 것을 감지할 때마다 과 통합하는 옵션을 제공합니다. 개인 Gmail 계정과의 통합을 방지하기 위해 다음 세 가지 중 하나를 권장합니다.

다른 Chrome 사용자로 로그인(권장)

다른 Chrome 프로필을 만드는 방법을 보려면 [이 링크](https://support.google.com/chrome/answer/2364824?hl=en)를 클릭하십시오.

**장점**: 다른 사용자로 로그인하면 Chrome의 새 인스턴스가 열립니다. 이 인스턴스는 Chrome의 완전히 새로운 창이며 이전 확장은 이 인스턴스에 존재하지 않습니다. 또한 쿠키를 보관하므로 매번 Gmail에 로그인할 필요가 없습니다.

**단점**: 두 개의 Chrome 창이 열려 있어야 합니다.

다른 브라우저 사용

**장점:** 확장이 설치되어 있지 않은 다른 인터넷 브라우저(IE 또는 Firefox)를 사용하면 이러한 문제가 발생하지 않습니다.

**단점**: 여러 브라우저를 사용하는 것은 귀찮을 수 있습니다.

시크릿 창 사용

**장점:** 시크릿 창은 네이키드 버전의 Chrome을 여는 것과 같습니다. 즉, 설치된 확장이 없으며 Sales Connect에서 연결할 수 없습니다.

**단점**: 하루를 시작할 때마다 Gmail에 로그인하고 실수로 창을 닫으면 다시 로그인해야 합니다.
