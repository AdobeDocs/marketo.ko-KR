---
description: reCAPTCHA v3 설정 - Marketo 문서 - 제품 설명서
title: reCAPTCHA v3 설정
exl-id: 235a2688-59a8-4827-a929-a07f3ae06988
feature: Forms
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 0%

---

# reCAPTCHA v3 설정 {#setting-up-recaptcha-v3}

ReCAPTCHA v3은 텍스트, 이미지 또는 버튼 문제를 사용하지 않고 양식 제출이 얼마나 의심스러운 지에 따라 점수를 매기는 마찰 없는 경험입니다. [자세히 알아보기](https://developers.google.com/search/blog/2018/10/introducing-recaptcha-v3-new-way-to){target="_blank"}.

## 데이터 센터 및 Munchkin ID 검색 {#retrieve-your-data-center-and-munchkin-id}

아래의 초기 reCAPTCHA v3 설정 섹션의 6단계는 Marketo Engage 구독의 데이터 센터와 Munchkin ID가 필요합니다. 찾는 방법은 다음과 같습니다.

1. Marketo에서 **관리자**.

   ![](assets/setting-up-recaptcha-v3-1.png)

1. 클릭 **내 계정**.

   ![](assets/setting-up-recaptcha-v3-2.png)

1. 아래로 스크롤하여 지원 정보를 확인합니다.

   ![](assets/setting-up-recaptcha-v3-3.png)

## 초기 reCAPTCHA v3 설정 {#initial-recaptcha-v3-setup}

다음 단계는 Marketo 외부에서 수행됩니다.

1. 다음으로 이동 [https://www.google.com/recaptcha/about/](https://www.google.com/recaptcha/about/){target="_blank"} v3 Admin Console을 클릭합니다.

1. Google 계정으로 로그인/등록

1. 만들기 단추(+ 기호)를 클릭하여 새 키를 만듭니다.

1. Marketo Engage에 사용할 키를 식별하는 레이블을 만듭니다.

1. 유형 선택 **reCAPTCHA v3**. Marketo Engage은 현재 reCAPTCHA v2를 지원하지 않습니다.

1. Marketo Engage 구독에서 사용하는 각 도메인을 추가합니다. 여기에 설정되지 않은 도메인은 reCAPTCHA가 활성화된 양식에서 오류를 반환합니다. &quot;datacenter&quot; 및 &quot;munchkinID&quot;를 [구독의 데이터](#retrieve-your-data-center-and-munchkin-id).

   * app-datacenter.marketo.com
   * munchkinID.mktoweb.com
   * 구독에 구성된 모든 랜딩 페이지 도메인 및 별칭

   >[!NOTE]
   >
   >예를 들어, 계정의 데이터 센터가 &quot;sjst&quot;인 경우 허용 목록에 추가하다 도메인은 다음과 같습니다. `app-sjst.marketo.com`. Munchkin ID가 123-ABC-789이면 허용 목록에 추가하다 도메인이 됩니다. `123-ABC-789.mktoweb.com`.

1. 이 서비스에 대한 알림을 수신할 소유자 및 추가 이메일 주소를 설정하십시오.

1. reCAPTCHA 서비스 약관에 동의합니다.

1. 클릭 **제출**.

   >[!NOTE]
   >
   >Marketo Engage 구성을 위해 사이트 키와 비밀 키를 근처에 보관합니다.

## Marketo Engage에서 CAPTCHA 설정 {#setting-up-captcha-in-marketo-engage}

>[!IMPORTANT]
>
>다음 단계를 수행하고 [첫 번째 Marketo 양식에서 CAPTCHA 활성화](/help/marketo/product-docs/demand-generation/forms/using-captcha/enable-captcha-in-marketo-forms.md){target="_blank"}, reCAPTCHA 설정의 잘못된 구성으로 인해 양식이 손상될 수 있으므로 양식을 즉시 테스트해야 합니다.

1. Marketo에서 **관리자**.

   ![](assets/setting-up-recaptcha-v3-4.png)

1. 선택 **CAPTCHA** 나무에.

   ![](assets/setting-up-recaptcha-v3-5.png)

1. 클릭 **편집** CAPTCHA 설정에서 다음을 수행합니다.

   ![](assets/setting-up-recaptcha-v3-6.png)

1. CAPTCHA 드롭다운을 클릭하고 reCAPTCHA v3을 선택합니다.

   ![](assets/setting-up-recaptcha-v3-7.png)

1. 암호 키 및 사이트 키를 삽입합니다. 클릭 **저장** 완료 시.

   ![](assets/setting-up-recaptcha-v3-8.png)

>[!MORELIKETHIS]
>
>[Marketo Forms에서 CAPTCHA 활성화](/help/marketo/product-docs/demand-generation/forms/using-captcha/enable-captcha-in-marketo-forms.md)
