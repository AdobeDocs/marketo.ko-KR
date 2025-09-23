---
unique-page-id: 10617187
description: 개인 정보 설정 이해 - Marketo 문서 - 제품 설명서
title: 개인 정보 보호 설정 이해
exl-id: 1fde9011-02a9-4ec9-bfa4-c56a52ce1eed
feature: Administration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '500'
ht-degree: 1%

---

# 개인 정보 보호 설정 이해 {#understanding-privacy-settings}

## 개요 {#overview}

Marketo은 마케터에게 웹 방문자의 추적 동의를 얻을 수 있는 방법을 제공합니다. 옵트아웃하는 방법에는 두 가지가 있습니다. 또는 익명으로 처리된 IP로 추적하도록 선택할 수 있습니다.

* 웹 방문자는 브라우저에서 추적 금지(DNT) 기능을 선택합니다(마케터는 추적 금지에 대한 웹 방문자의 요청을 수락함)
* 웹 방문자는 웹 사이트에서 마케터가 제공하는 옵트아웃 쿠키를 사용합니다

또는 마케터는 사용자를 추적할 수 있지만 익명으로 처리된 IP를 사용합니다.

이러한 방법은 특정 영역에서 Marketo의 가치와 기능에 영향을 줄 수 있습니다. 그러나 마케터 _이(가) Marketo의 구성에서 아무것도 변경하지 않는_&#x200B;경우 Marketo 기능은 그대로 유지됩니다.

## Do Not Track 브라우저 설정 {#browser-settings-for-do-not-track}

웹 방문자는 &quot;추적 안 함&quot;(DNT)을 선택하여 모든 웹 사이트에 의한 추적을 방지하도록 브라우저를 설정할 수 있습니다. 이렇게 하면 이 특정 브라우저 및 장치에 대한 추적이 방지됩니다. 자세한 내용은 브라우저의 개인 정보 설정을 참조하십시오.

[!DNL Munchkin]에서 마케터는 [브라우저의 DNT 설정을 지원할지 또는 무시할지 여부를 결정](/help/marketo/product-docs/administration/settings/edit-do-not-track-browser-support-settings.md)할 수 있습니다.

웹 Personalization에서 마케터는 [지원할지 또는 브라우저의 DNT 설정을 무시할지](/help/marketo/product-docs/web-personalization/getting-started/setting-web-personalization-to-do-not-track.md)을 결정할 수 있습니다.

## 특정 웹 사이트에서 옵트아웃 {#opt-out-from-a-specific-website}

**브라우저 추적 안 함** 설정의 구성 여부와 관계없이 사이트 방문자가 웹 사이트에서 웹 사이트 추적을 옵트아웃하도록 허용할 수도 있습니다. 이렇게 하면 사이트 방문자가 웹 사이트에서 직접 추적 환경 설정을 지정할 수 있습니다.

이렇게 하려면 [!DNL Munchkin] 추적이 활성화된 웹 페이지의 옵트아웃 링크에 매개 변수를 추가해야 합니다. 모든 웹 페이지일 수 있지만 웹 페이지 링크에는 다음 매개 변수가 포함되어야 합니다.

?marketo_opt_out=true

다음은 옵트아웃 링크가 있는 웹 페이지와 링크를 클릭한 후의 랜딩 페이지 의 예입니다. 귀하의 정보는 다를 수 있습니다.

다음은 옵트아웃 링크에 &quot;?marketo_opt_out=true&quot; 매개 변수가 있는 버튼이 있는 웹 페이지입니다.

![](assets/understanding-privacy-settings-1.png)

&quot;?marketo_opt_out=true&quot; 매개 변수가 있는 링크를 클릭했을 때의 후속 페이지로 랜딩 페이지를 만들어 게시할 수 있습니다.

![](assets/understanding-privacy-settings-2.png)

링크를 클릭하면 Marketo이 방문자의 브라우저에 **mkto_opt_out**&#x200B;이라는 쿠키를 추가하여 위의 매개 변수로 링크를 클릭하는 사이트 방문자에 대한 [!DNL Munchkin] 추적을 비활성화합니다.

쿠키를 심을 수 있는지 확인하려면 쿠키 리드인지 확인하고 링크를 클릭합니다. 그런 다음 브라우저 쿠키를 확인하여 **mkto_opt_out** 쿠키가 추가되었는지 확인하십시오.

![](assets/understanding-privacy-settings-3.png)

>[!NOTE]
>
>현재 [!DNL Munchkin] 버전 152 이상에서만 작동합니다.

## 옵트인 {#opt-in}

마케터는 사용자가 이메일, 양식, 랜딩 페이지 및 기타 방법에서 Marketo의 기능을 사용하여 옵트인할 수 있도록 합니다.

## 익명화된 IP를 사용한 추적 {#tracking-using-an-anonymized-ip}

마케터는 익명화된 IP 주소를 사용하여 사용자를 추적하여 개인 정보를 보존할 수 있습니다. 이렇게 하려면 이 코드를 웹 사이트에 포함된 RTP 또는 [!DNL Munchkin] Javascript에 추가합니다.

* [!DNL Munchkin]의 경우 init 함수에 {&quot;anonymizeIP&quot;,true}를 추가하십시오.

  >[!NOTE]
  >
  >이 매개 변수를 사용하려면 [!DNL Munchkin] V2를 사용하도록 설정해야 합니다. 구독에 사용하려면 [Marketo 지원](https://nation.marketo.com/community/support_solutions)에 문의하세요.

* 웹 Personalization(RTP)의 경우 이를 javascript에 추가합니다.

`anonymize IP : before calling rtp('send','view'); add rtp('set', 'settings', {'anonymizeIP' : true});`
