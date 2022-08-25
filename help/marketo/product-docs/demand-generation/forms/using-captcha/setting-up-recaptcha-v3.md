---
description: reCAPTCHA v3 설정 - Marketo 문서 - 제품 설명서
title: reCAPTCHA v3 설정
hide: true
hidefromtoc: true
exl-id: 235a2688-59a8-4827-a929-a07f3ae06988
source-git-commit: fed5fc3a511022fbac40b8ad369a1cdda5112167
workflow-type: tm+mt
source-wordcount: '354'
ht-degree: 0%

---

# reCAPTCHA v3 설정 {#setting-up-recaptcha-v3}

ReCAPTCHA v3는 텍스트, 이미지 또는 단추 관련 문제를 사용하지 않고 의심스러운 위치를 기반으로 양식 제출 점수를 매기는 마찰이 없는 경험입니다. [추가 정보](https://developers.google.com/search/blog/2018/10/introducing-recaptcha-v3-new-way-to){target=&quot;_blank&quot;}.

## 데이터 센터 및 Munchkin ID 검색 {#retrieve-your-data-center-and-munchkin-id}

아래의 초기 reCAPTCHA v3 설정 섹션의 6단계는 Marketo Engage 구독의 데이터 센터 및 Munchkin ID가 필요합니다. 여기 어떻게 찾을 수 있죠?

1. Marketo에서 **관리**.

   ![](assets/setting-up-recaptcha-v3-1.png)

1. 클릭 **내 계정**.

   ![](assets/setting-up-recaptcha-v3-2.png)

1. 지원 정보로 스크롤합니다.

   ![](assets/setting-up-recaptcha-v3-3.png)

## 초기 reCAPTCHA v3 설정 {#initial-recaptcha-v3-setup}

다음 단계는 Marketo 외부에서 수행됩니다.

1. 이동 [https://www.google.com/recaptcha/about/](https://www.google.com/recaptcha/about/){target=&quot;_blank&quot;} 를 클릭하고 v3 Admin Console을 클릭합니다.

1. Google 계정으로 로그인/등록.

1. 만들기 단추(+ 기호)를 클릭하여 새 키를 만듭니다.

1. Marketo Engage에 사용할 키를 식별하는 레이블을 만듭니다.

1. 유형 선택 **reCAPTCHA v3**. Marketo Engage은 현재 reCAPTCHA v2를 지원하지 않습니다.

1. Marketo Engage 구독에서 사용하는 각 도메인을 추가합니다. 여기서 설정되지 않은 도메인은 reCAPTCHA가 활성화된 양식에서 오류를 반환합니다. &#39;datacenter&#39; 및 &#39;munchkinID&#39;를 [구독의 데이터](#retrieve-your-data-center-and-munchkin-id).

   * app-datacenter.marketo.com
   * munchkinID.mktoweb.com
   * 구독에 구성된 모든 랜딩 페이지 도메인 및 별칭

   >[!NOTE]
   >
   >예를 들어 계정의 데이터 센터가 &quot;sjst&quot;일 경우 허용 목록에 추가하다 사용자가 지정하는 도메인은 다음과 같습니다 `app-sjst.marketo.com`. Munchkin ID가 123-ABC-789인 경우, 도메인허용 목록에 추가하다는 다음과 같습니다 `123-ABC-789.mktoweb.com`.

1. 이 서비스에 대한 알림을 받을 소유자 및 추가 이메일 주소를 설정합니다.

1. reCAPTCHA 서비스 약관에 동의합니다.

1. 클릭 **제출**.

   >[!NOTE]
   >
   >Marketo Engage 구성에 대해 사이트 키와 비밀 키를 가까이 보관합니다.

## Marketo Engage에서 CAPTCHA 설정 {#setting-up-captcha-in-marketo-engage}

>[!IMPORTANT]
>
>다음 단계를 수행한 후 [첫 번째 Marketo 양식에서 CAPTCHA 활성화](/help/marketo/product-docs/demand-generation/forms/using-captcha/enable-captcha-in-marketo-forms.md){target=&quot;_blank&quot;}, reCAPTCHA 설정에서 잘못된 구성을 정렬하면 양식이 손상될 수 있으므로 바로 양식을 테스트하십시오.

1. Marketo에서 **관리**.

   ![](assets/setting-up-recaptcha-v3-4.png)

1. 선택 **CAPTCHA** 나무에 있습니다.

   ![](assets/setting-up-recaptcha-v3-5.png)

1. 클릭 **편집** CAPTCHA 설정

   ![](assets/setting-up-recaptcha-v3-6.png)

1. CAPTCHA 드롭다운을 클릭하고 reCAPTCHA v3을 선택합니다.

   ![](assets/setting-up-recaptcha-v3-7.png)

1. 비밀 키 및 사이트 키를 삽입합니다. 클릭 **저장** 완료 시.

   ![](assets/setting-up-recaptcha-v3-8.png)
