---
unique-page-id: 10617187
description: 개인 정보 설정 이해 - Marketing Docs - 제품 설명서
title: 개인 정보 설정 이해
translation-type: tm+mt
source-git-commit: efadb7eb3845012c273e1a60f9cd98ac884eb543
workflow-type: tm+mt
source-wordcount: '534'
ht-degree: 0%

---


# 개인 정보 설정 이해 {#understanding-privacy-settings}

## 개요 {#overview}

마케터는 웹 방문자의 동의를 얻어 이를 추적하는 방법을 제공합니다. 수신 거부할 방법에는 두 가지가 있으며, 익명 처리 IP로 추적하도록 선택할 수도 있습니다.

* 웹 방문자는 브라우저에서 DNT(추적 안 함) 기능을 선택하고 마케터는 웹 방문자의 추적 안 함 요청을 처리합니다.
* 웹 방문자는 웹 사이트의 마케터가 제공하는 옵트아웃 쿠키를 사용합니다

또는 마케터는 사용자를 추적하지만 익명 처리된 IP를 사용할 수 있습니다.

이러한 방법은 특정 영역의 Marketing To 값과 기능에 영향을 줄 수 있습니다. 그러나 마케터가 Marketing To의 구성에서 *변경하지* 않으면 Marketing To 기능이 동일하게 유지됩니다.

## 추적하지 않기 위한 브라우저 설정 {#browser-settings-for-do-not-track}

웹 방문자는 &quot;DNT(추적 안 함)&quot;를 선택하여 모든 웹 사이트에서 추적하는 것을 방지하기 위해 브라우저를 설정할 수 있습니다. 이렇게 하면 이 특정 브라우저 및 장치에 대한 추적이 방지됩니다. 자세한 내용은 브라우저의 개인 정보 설정을 참조하십시오.

Munchkin에서 마케터는 브라우저의 DNT 설정을 지원할지 또는 무시할지 [결정할 수 있습니다](edit-do-not-track-browser-support-settings.md).

웹 개인화에서 마케터는 브라우저의 DNT 설정을 [지원할지 또는 무시할지를 결정할 수 있습니다](/help/marketo/product-docs/web-personalization/getting-started/setting-web-personalization-to-do-not-track.md).

## 특정 웹 사이트에서 옵트아웃 {#opt-out-from-a-specific-website}

또한 [브라우저 추적 안 함] 설정이 구성되어 있는지 여부에 관계없이 사이트 방문자가 웹 사이트에서 **웹 사이트 추적을 옵트아웃하도록 허용할** 수 있습니다. 이렇게 하면 사이트 방문자가 웹 사이트에서 직접 추적 환경 설정을 지정할 수 있습니다.

이렇게 하려면, 문킨 추적이 활성화된 웹 페이지의 옵트아웃 링크에 매개 변수를 추가해야 합니다. 모든 웹 페이지가 될 수 있지만 웹 페이지 링크에는 다음 매개 변수가 포함되어야 합니다.

?marketing_opt_out=true

아래는 옵트아웃 링크 및 링크를 클릭한 후 랜딩 페이지가 있는 웹 페이지의 예입니다. 당신의 것은 다를 것입니다.

옵트아웃 링크에 &quot;?markto_opt_out=true&quot; 매개 변수가 있는 단추가 있는 웹 페이지가 있습니다.

![](assets/opt-out-1.png)

&quot;?markto_opt_out=true&quot; 매개 변수를 사용하는 링크를 클릭할 때 랜딩 페이지를 후속 페이지로 만들고 게시할 수 있습니다.

![](assets/opt-out-2.png)

링크를 클릭하면 Marketing에서는 위의 매개 변수로 링크를 클릭하는 사이트 방문자에 대한 **문킨 추적을 비활성화하는 mkto_opt_out** 이라는 쿠키를 방문자의 브라우저에 추가합니다.

쿠키가 만들어질 수 있는지 확인하려면, 쿠키가 있는지 확인하고 링크를 클릭합니다. 그런 다음 브라우저 쿠키를 확인하여 **mkto_opt_out** 쿠키가 추가되었는지 확인합니다.

![](assets/opt-out-3.png)

>[!NOTE]
>
>현재 이 기능은 Munchkin 버전 152 이상에서만 작동합니다.

## 옵트인 {#opt-in}

마케터는 이메일, 양식, 랜딩 페이지 및 기타 방법으로 Marketing To의 기능을 사용하여 사용자가 옵트인할 수 있도록 할 수 있습니다.

## 익명 처리된 IP를 사용한 추적 {#tracking-using-an-anonymized-ip}

마케터는 익명 처리된 IP 주소로 사용자를 추적함으로써 개인 정보를 보호할 수 있습니다. 이렇게 하려면 웹 사이트에 포함된 RTP 또는 Munchkin Javascript에 이 코드를 추가합니다.

* Munchkin의 경우 init 함수에 {&quot;animizeIP&quot;,true}를 추가하면 됩니다.

   >[!NOTE]
   >
   >이 매개 변수를 사용하려면 Munchkin V2가 활성화되어 있어야 합니다. 구독을 사용하도록 설정하려면 Marketing [Support에 문의하십시오](http://nation.marketo.com/community/support_solutions).

* 웹 개인화(RTP)의 경우 javascript에 추가합니다.

IP 익명 처리:rtp(&#39;send&#39;,&#39;view&#39;)를 호출하기 전에add rtp(&#39;set&#39;, &#39;settings&#39;, {&#39;익명화IP&#39; :true});

