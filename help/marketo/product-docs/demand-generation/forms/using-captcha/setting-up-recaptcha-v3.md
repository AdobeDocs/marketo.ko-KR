---
description: reCAPTCHA v3 설정 - Marketo 문서 - 제품 설명서
title: reCAPTCHA v3 설정
exl-id: 235a2688-59a8-4827-a929-a07f3ae06988
feature: Forms
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '304'
ht-degree: 2%

---

# [!UICONTROL reCAPTCHA v3] 설정 중 {#setting-up-recaptcha-v3}

ReCAPTCHA v3은 텍스트, 이미지 또는 버튼 문제를 사용하지 않고 양식 제출이 얼마나 의심스러운 지에 따라 점수를 매기는 마찰 없는 경험입니다. [자세히 알아보기](https://developers.google.com/search/blog/2018/10/introducing-recaptcha-v3-new-way-to){target="_blank"}

## [!UICONTROL Data Center] 및 [!UICONTROL Munchkin ID] 검색 {#retrieve-your-data-center-and-munchkin-id}

아래의 초기 [!UICONTROL reCAPTCHA v3] 설정 섹션의 6단계는 Marketo Engage 구독의 [!UICONTROL Data Center] 및 [!UICONTROL Munchkin ID]이(가) 필요합니다. 찾는 방법은 다음과 같습니다.

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/setting-up-recaptcha-v3-1.png)

1. **[!UICONTROL My Account]**&#x200B;를 클릭합니다.

   ![](assets/setting-up-recaptcha-v3-2.png)

1. [!UICONTROL Support Information]&#x200B;(으)로 스크롤합니다.

   ![](assets/setting-up-recaptcha-v3-3.png)

## 초기 [!UICONTROL reCAPTCHA v3] 설정 {#initial-recaptcha-v3-setup}

다음 단계는 Marketo 외부에서 수행됩니다.

1. [https://www.google.com/recaptcha/about/](https://www.google.com/recaptcha/about/){target="_blank"}(으)로 이동하여 v3 Admin Console을 클릭합니다.

1. Google 계정으로 로그인/등록

1. 새 키를 만들려면 [!UICONTROL Create] 단추(+ 기호)를 클릭하십시오.

1. Marketo Engage에 사용할 키를 식별하는 레이블을 만듭니다.

1. **[!UICONTROL reCAPTCHA v3]** 유형을 선택하십시오. Marketo Engage은 현재 reCAPTCHA v2를 지원하지 않습니다.

1. Marketo Engage 구독에서 사용하는 각 도메인을 추가합니다. 여기에 설정되지 않은 도메인은 reCAPTCHA가 활성화된 양식에서 오류를 반환합니다. &#39;datacenter&#39; 및 &#39;munchkinID&#39;를 구독의 [데이터](#retrieve-your-data-center-and-munchkin-id)(으)로 바꾸십시오.

   * app-datacenter.marketo.com
   * munchkinID.mktoweb.com
   * 구독에 구성된 모든 랜딩 페이지 도메인 및 별칭

   >[!NOTE]
   >
   >예를 들어 계정의 [!UICONTROL Data Center]이(가) &quot;sjst&quot;인 경우 허용 목록에 추가하다는 `app-sjst.marketo.com`이(가) 됩니다. 허용 목록에 추가하다 [!UICONTROL Munchkin ID]이(가) 123-ABC-789인 경우 도메인을 나타내는 도메인은 `123-ABC-789.mktoweb.com`입니다.

1. 이 서비스에 대한 알림을 수신할 소유자 및 추가 이메일 주소를 설정하십시오.

1. reCAPTCHA 서비스 약관에 동의합니다.

1. **[!UICONTROL Submit]**&#x200B;를 클릭합니다.

   >[!NOTE]
   >
   >Marketo Engage 구성에 대한 사이트 키 및 비밀 키를 가까이에 둡니다.

## Marketo Engage에서 CAPTCHA 설정 {#setting-up-captcha-in-marketo-engage}

>[!IMPORTANT]
>
>이 단계를 따라 [첫 번째 Marketo 양식에서 CAPTCHA를 사용](/help/marketo/product-docs/demand-generation/forms/using-captcha/enable-captcha-in-marketo-forms.md){target="_blank"}한 후 reCAPTCHA 설정에서 잘못 구성하면 양식이 손상될 수 있으므로 양식을 즉시 테스트해야 합니다.

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/setting-up-recaptcha-v3-4.png)

1. 트리에서 **[!UICONTROL CAPTCHA]**&#x200B;을(를) 선택하십시오.

   ![](assets/setting-up-recaptcha-v3-5.png)

1. **[!UICONTROL Edit]** 설정에서 [!UICONTROL CAPTCHA]을(를) 클릭합니다.

   ![](assets/setting-up-recaptcha-v3-6.png)

1. [!UICONTROL CAPTCHA] 드롭다운을 클릭하고 [!UICONTROL reCAPTCHA v3]을(를) 선택합니다.

   ![](assets/setting-up-recaptcha-v3-7.png)

1. **[!UICONTROL Secret Key]** 및 **[!UICONTROL Site Key]**&#x200B;을(를) 삽입합니다. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/setting-up-recaptcha-v3-8.png)

>[!MORELIKETHIS]
>
>[Marketo Forms에서 CAPTCHA 사용](/help/marketo/product-docs/demand-generation/forms/using-captcha/enable-captcha-in-marketo-forms.md)
