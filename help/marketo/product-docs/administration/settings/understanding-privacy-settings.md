---
unique-page-id: 10617187
description: 개인 정보 설정 이해 - Marketo 문서 - 제품 설명서
title: 개인 정보 설정 이해
exl-id: 1fde9011-02a9-4ec9-bfa4-c56a52ce1eed
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '521'
ht-degree: 0%

---

# 개인 정보 설정 이해 {#understanding-privacy-settings}

## 개요 {#overview}

Marketo은 마케터에게 웹 방문자의 동의를 얻어 추적하는 방법을 제공합니다. 옵트아웃하는 방법에는 두 가지가 있습니다. 또는 익명으로 처리된 IP를 통해 추적하도록 선택할 수 있습니다.

* 웹 방문자는 브라우저에서 DNT(Do Not Track) 기능을 선택합니다(및 마케팅 담당자는 웹 방문자가 추적하지 않음 요청을 준수합니다.)
* 웹 방문자는 웹 사이트에서 마케터가 제공하는 옵트아웃 쿠키를 사용합니다

또는 마케터는 사용자를 추적하지만 익명 처리된 IP를 사용할 수 있습니다.

이러한 메서드는 특정 영역의 Marketo 값 및 기능에 영향을 줄 수 있습니다. 그러나 마케터가 *does not* Marketo의 구성에서 모든 것을 변경하면 Marketo 기능은 동일하게 유지됩니다.

## 추적 안함에 대한 브라우저 설정 {#browser-settings-for-do-not-track}

웹 방문자는 DNT(&quot;추적 안 함&quot;)를 선택하여 모든 웹 사이트의 추적을 방지하도록 브라우저를 설정할 수 있습니다. 이렇게 하면 이 특정 브라우저 및 장치에 대한 추적이 방지됩니다. 자세한 내용은 브라우저의 개인 정보 설정을 참조하십시오.

Munchkin에서 마케터는 [브라우저의 DNT 설정을 지원할지 또는 무시할지를 결정합니다](/help/marketo/product-docs/administration/settings/edit-do-not-track-browser-support-settings.md).

웹 개인화에서 마케터는 다음 방법 여부를 결정할 수 있습니다 [브라우저의 DNT 설정을 지원하거나 무시합니다](/help/marketo/product-docs/web-personalization/getting-started/setting-web-personalization-to-do-not-track.md).

## 특정 웹 사이트에서 옵트아웃 {#opt-out-from-a-specific-website}

사이트 방문자가 웹 사이트 추적을 옵트아웃하도록 허용할 수도 있습니다 **브라우저 추적 안 함** 설정이 구성됩니다. 이렇게 하면 사이트 방문자가 웹 사이트에서 직접 추적 환경 설정을 지정할 수 있습니다.

이렇게 하려면 munchkin 추적이 활성화된 웹 페이지의 옵트아웃 링크에 매개 변수를 추가해야 합니다. 모든 웹 페이지일 수 있지만 웹 페이지 링크에는 다음 매개 변수가 포함되어야 합니다.

?marketo_opt_out=true

아래는 링크를 클릭한 후에에 대한 옵트아웃 링크 및 랜딩 페이지가 있는 웹 페이지의 예입니다. 당신의 것은 달라질 것입니다.

다음은 옵트아웃 링크에 &quot;?marketo_opt_out=true&quot; 매개 변수가 있는 단추가 있는 웹 페이지입니다.

![](assets/opt-out-1.png)

&quot;?marketo_opt_out=true&quot; 매개 변수와의 링크를 클릭할 때 랜딩 페이지를 추가 페이지로 만들고 게시할 수 있습니다.

![](assets/opt-out-2.png)

링크를 클릭하면 Marketo에서 라는 쿠키를 추가합니다. **mkto_opt_out** 위의 매개 변수로 링크를 클릭하는 사이트 방문자에 대한 Munchkin 추적을 비활성화하는 방문자의 브라우저로 연결합니다.

쿠키를 삽입할 수 있는지 확인하려면 쿠키 리드가 있는지 확인하고 링크를 클릭합니다. 그런 다음 브라우저 쿠키를 확인하여 **mkto_opt_out** 쿠키가 추가되었습니다.

![](assets/opt-out-3.png)

>[!NOTE]
>
>현재 Munchkin 버전 152 이상에서만 작동합니다.

## 옵트인 {#opt-in}

마케터는 사용자가 이메일, 양식, 랜딩 페이지 및 기타 방법에 Marketo의 기능을 사용하여 옵트인할 수 있습니다.

## 익명 처리된 IP를 사용한 추적 {#tracking-using-an-anonymized-ip}

마케터는 익명으로 처리된 IP 주소로 사용자를 추적하여 개인 정보를 유지할 수 있습니다. 이렇게 하려면 웹 사이트에 포함된 RTP 또는 Munchkin Javascript에 이 코드를 추가합니다.

* Munchkin의 경우 init 함수에 {&quot;anonymizeIP&quot;,true}를 추가합니다.

   >[!NOTE]
   >
   >이 매개 변수를 사용하려면 Munchkin V2를 활성화해야 합니다. 구독에 대해 사용하도록 설정하려면 다음 주소로 문의하십시오 [Marketo 지원](https://nation.marketo.com/community/support_solutions).

* 웹 개인화(RTP)의 경우 javascript에 추가합니다.

`anonymize IP : before calling rtp('send','view'); add rtp('set', 'settings', {'anonymizeIP' : true});`
