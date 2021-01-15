---
unique-page-id: 10617187
description: 개인 정보 설정 이해 - 마케팅 문서 - 제품 설명서
title: 개인 정보 설정 이해
translation-type: tm+mt
source-git-commit: f79909ce8f2e37bf0748596774fe47ac03618696
workflow-type: tm+mt
source-wordcount: '521'
ht-degree: 0%

---


# 개인 정보 설정 이해 {#understanding-privacy-settings}

## 개요 {#overview}

마케터는 웹 방문자의 동의를 얻어 추적하는 방법을 제공합니다. 수신 거부하는 방법에는 두 가지가 있으며, 익명 처리된 IP로 추적하도록 선택할 수도 있습니다.

* 웹 방문자는 브라우저에서 DNT(추적 안 함) 기능을 선택합니다(그리고 마케터는 웹 방문자의 추적 안 함 요청을 처리합니다.)
* 웹 방문자는 웹 사이트의 마케터가 제공하는 옵트아웃 쿠키를 사용합니다

또는 마케터는 사용자를 추적할 수 있지만 익명 처리된 IP를 사용할 수 있습니다.

이러한 메서드는 특정 영역의 Marketing To 값과 기능에 영향을 줄 수 있습니다. 그러나 마케터 *이 Marketing의 구성에서*&#x200B;의 변경 사항이 없는 경우 Marketing To 기능은 동일하게 유지됩니다.

## {#browser-settings-for-do-not-track}을(를) 추적하지 않기 위한 브라우저 설정

웹 방문자는 &quot;DNT(Do Not Track)&quot;를 선택하여 모든 웹 사이트의 추적을 방지하도록 브라우저를 설정할 수 있습니다. 이렇게 하면 이 특정 브라우저 및 장치에 대한 추적을 방지할 수 있습니다. 자세한 내용은 브라우저의 개인 정보 설정을 참조하십시오.

Munchkin에서 마케터는 [브라우저의 DNT 설정](/help/marketo/product-docs/administration/settings/edit-do-not-track-browser-support-settings.md)을 지원할지 여부를 결정할 수 있습니다.

웹 개인화에서 마케터는 [을(를) 지원할지 또는 브라우저의 DNT 설정](/help/marketo/product-docs/web-personalization/getting-started/setting-web-personalization-to-do-not-track.md)을 무시할지 결정할 수 있습니다.

## 특정 웹 사이트 {#opt-out-from-a-specific-website}에서 옵트아웃

**브라우저 추적 안 함** 설정 구성 여부와 관계없이 사이트 방문자가 웹 사이트에서 웹 사이트 추적을 옵트아웃하도록 허용할 수도 있습니다. 이렇게 하면 사이트 방문자가 웹 사이트에서 직접 추적 기본 설정을 지정할 수 있습니다.

이렇게 하려면 문통 추적이 활성화된 웹 페이지의 옵트아웃 링크에 매개 변수를 추가해야 합니다. 모든 웹 페이지가 될 수 있지만 웹 페이지 링크에는 다음 매개 변수가 포함되어야 합니다.

?marketing_opt_out=true

아래는 링크를 클릭한 후 옵트아웃 링크 및 랜딩 페이지가 있는 웹 페이지의 예입니다. 여러분의 제품은 다양합니다.

옵트아웃 링크에 &quot;?marketing_opt_out=true&quot; 매개 변수가 있는 단추가 있는 웹 페이지가 있습니다.

![](assets/opt-out-1.png)

&quot;?marketing_opt_out=true&quot; 매개 변수를 사용한 링크를 클릭할 때 랜딩 페이지를 후속 페이지로 만들고 게시할 수 있습니다.

![](assets/opt-out-2.png)

링크를 클릭하면 Marketing은 위의 매개 변수로 링크를 클릭하는 사이트 방문자에 대한 Munchkin 추적을 비활성화하는 방문자의 브라우저에 **mkto_opt_out**&#x200B;이라는 쿠키를 추가합니다.

쿠키를 생성할 수 있는지 확인하려면 쿠키 리드가 있는지 확인하고 링크를 클릭합니다. 그런 다음 브라우저 쿠키를 확인하여 **mkto_opt_out** 쿠키가 추가되었는지 확인합니다.

![](assets/opt-out-3.png)

>[!NOTE]
>
>현재 이 기능은 Munchkin 버전 152 이상에서만 작동합니다.

## {#opt-in} 옵트인

마케터는 이메일, 양식, 랜딩 페이지 및 기타 방법으로 Marketing To의 기능을 사용하여 사용자가 옵트인할 수 있도록 할 수 있습니다.

## 익명 처리된 IP {#tracking-using-an-anonymized-ip} 사용 추적

마케터는 익명으로 처리된 IP 주소로 사용자를 추적하여 개인 정보를 보호할 수 있습니다. 이렇게 하려면 웹 사이트에 포함된 RTP 또는 Munchkin Javascript에 이 코드를 추가합니다.

* Munchkin의 경우 init 함수에 {&quot;animizeIP&quot;,true} 만 추가합니다.

   >[!NOTE]
   >
   >이 매개 변수를 사용하려면 Munchkin V2가 활성화되어 있어야 합니다. 구독을 사용하도록 설정하려면 [Marketing Support](http://nation.marketo.com/community/support_solutions)에 문의하십시오.

* 웹 개인화(RTP)의 경우 javascript에 추가합니다.

`anonymize IP : before calling rtp('send','view'); add rtp('set', 'settings', {'anonymizeIP' : true});`
