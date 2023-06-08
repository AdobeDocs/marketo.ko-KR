---
unique-page-id: 10617187
description: 개인 정보 설정 이해 - Marketo 문서 - 제품 설명서
title: 개인 정보 설정 이해
exl-id: 1fde9011-02a9-4ec9-bfa4-c56a52ce1eed
source-git-commit: b71729a678ff4a676bb60803d845d0a44118f7e5
workflow-type: tm+mt
source-wordcount: '514'
ht-degree: 0%

---

# 개인 정보 설정 이해 {#understanding-privacy-settings}

## 개요 {#overview}

Marketo은 마케터에게 웹 방문자의 추적 동의를 얻을 수 있는 방법을 제공합니다. 옵트아웃하는 방법에는 두 가지가 있습니다. 또는 익명으로 처리된 IP로 추적하도록 선택할 수 있습니다.

* 웹 방문자는 브라우저에서 추적 금지(DNT) 기능을 선택합니다(마케터는 추적 금지에 대한 웹 방문자의 요청을 수락함)
* 웹 방문자는 웹 사이트에서 마케터가 제공하는 옵트아웃 쿠키를 사용합니다

또는 마케터는 사용자를 추적할 수 있지만 익명으로 처리된 IP를 사용합니다.

이러한 방법은 특정 영역에서 Marketo의 가치와 기능에 영향을 줄 수 있습니다. 그러나 마케터가 _다음과 같지 않음_ Marketo의 구성에서 원하는 대로 변경할 수 있으므로 Marketo 기능은 그대로 유지됩니다.

## Do Not Track 브라우저 설정 {#browser-settings-for-do-not-track}

웹 방문자는 &quot;추적 안 함&quot;(DNT)을 선택하여 모든 웹 사이트에 의한 추적을 방지하도록 브라우저를 설정할 수 있습니다. 이렇게 하면 이 특정 브라우저 및 장치에 대한 추적이 방지됩니다. 자세한 내용은 브라우저의 개인 정보 설정을 참조하십시오.

위치 [!DNL Munchkin], 마케터 [브라우저의 DNT 설정을 지원할지 또는 무시할지 여부를 결정합니다.](/help/marketo/product-docs/administration/settings/edit-do-not-track-browser-support-settings.md).

웹 개인화에서 마케터는 다음을 수행할지 여부를 결정할 수 있습니다. [브라우저의 DNT 설정 지원 또는 무시](/help/marketo/product-docs/web-personalization/getting-started/setting-web-personalization-to-do-not-track.md).

## 특정 웹 사이트에서 옵트아웃 {#opt-out-from-a-specific-website}

또한 사이트 방문자가 웹 사이트에서 웹 사이트 추적을 옵트아웃하도록 허용할 수도 있습니다 **브라우저가 추적하지 않음** 설정이 구성되었습니다. 이렇게 하면 사이트 방문자가 웹 사이트에서 직접 추적 환경 설정을 지정할 수 있습니다.

이렇게 하려면 이(가) 있는 웹 페이지의 옵트아웃 링크에 매개 변수를 추가해야 합니다 [!DNL Munchkin] 추적이 활성화되었습니다. 모든 웹 페이지일 수 있지만 웹 페이지 링크에는 다음 매개 변수가 포함되어야 합니다.

?marketo_opt_out=true

다음은 옵트아웃 링크가 있는 웹 페이지와 링크를 클릭한 후의 랜딩 페이지 의 예입니다. 귀하의 정보는 다를 수 있습니다.

다음은 옵트아웃 링크에 &quot;?marketo_opt_out=true&quot; 매개 변수가 있는 버튼이 있는 웹 페이지입니다.

![](assets/understanding-privacy-settings-1.png)

&quot;?marketo_opt_out=true&quot; 매개 변수가 있는 링크를 클릭했을 때의 후속 페이지로 랜딩 페이지를 만들어 게시할 수 있습니다.

![](assets/understanding-privacy-settings-2.png)

링크를 클릭하면 Marketo이 라는 쿠키를 추가합니다. **mkto_opt_out** 을 비활성화하는 방문자의 브라우저로 [!DNL Munchkin] 위의 매개 변수로 링크를 클릭하는 사이트 방문자에 대한 추적.

쿠키를 심을 수 있는지 확인하려면 쿠키 리드인지 확인하고 링크를 클릭합니다. 그런 다음 브라우저 쿠키를 확인하여 **mkto_opt_out** 쿠키가 추가되었습니다.

![](assets/understanding-privacy-settings-3.png)

>[!NOTE]
>
>현재 다음 항목에서만 작동합니다. [!DNL Munchkin] 버전 152 이상

## 옵트인 {#opt-in}

마케터는 사용자가 이메일, 양식, 랜딩 페이지 및 기타 방법에서 Marketo의 기능을 사용하여 옵트인할 수 있도록 합니다.

## 익명화된 IP를 사용한 추적 {#tracking-using-an-anonymized-ip}

마케터는 익명화된 IP 주소를 사용하여 사용자를 추적하여 개인 정보를 보존할 수 있습니다. 이렇게 하려면 이 코드를 RTP에 추가하거나 [!DNL Munchkin] 웹 사이트에 포함된 JavaScript.

* 대상 [!DNL Munchkin]을(를) 사용하려면 init 함수에 {&quot;anonymizeIP&quot;,true}를 추가하십시오.

  >[!NOTE]
  >
  >이 매개 변수를 사용하려면 다음을 수행해야 합니다. [!DNL Munchkin] V2를 사용할 수 있습니다. 구독에 대해 활성화하려면 다음으로 문의하십시오. [Marketo 지원](https://nation.marketo.com/community/support_solutions).

* 웹 개인화(RTP)의 경우 다음 항목을 javascript에 추가합니다.

`anonymize IP : before calling rtp('send','view'); add rtp('set', 'settings', {'anonymizeIP' : true});`
