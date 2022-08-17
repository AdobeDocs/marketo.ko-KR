---
description: reCAPTCHA v3 설정 - Marketo 문서 - 제품 설명서
title: reCAPTCHA v3 설정
hide: true
hidefromtoc: true
exl-id: 235a2688-59a8-4827-a929-a07f3ae06988
source-git-commit: 1803d6355747f4b6300509a3d361bf235dd56f44
workflow-type: tm+mt
source-wordcount: '205'
ht-degree: 0%

---

# reCAPTCHA 설정 {#setting-up-recaptcha}

소개 텍스트

## reCAPTCHA v3 설정 {#setting-up-recaptcha-v3}

텍스트: 설명 v3 - Marketo Engage 외부에서 다음 단계를 수행합니다.

1. 이동 [https://www.google.com/recaptcha/about/](https://www.google.com/recaptcha/about/){target=&quot;_blank&quot;} 를 클릭하고 v3 Admin Console을 클릭합니다.

1. Google 계정으로 로그인/등록.

1. 만들기(+ 기호) 단추를 클릭하여 새 키를 만듭니다.

1. Marketo Engage에 사용할 키를 식별하는 레이블을 만듭니다.

1. 유형 선택 **reCAPTCHA v3**. Marketo Engage은 현재 reCAPTCHA v2를 지원하지 않습니다.

1. Marketo Engage 구독에서 사용하는 각 도메인을 추가합니다. 여기서 설정되지 않은 도메인은 reCAPTCHA가 활성화된 양식에서 오류를 반환합니다.

   * 123-ABC-456.mktoweb.com
   * app-pod.marketo.com
   * 구독에 구성된 모든 랜딩 페이지 도메인 및 별칭

1. 이 서비스에 대한 알림을 받을 소유자 및 추가 이메일 주소를 설정합니다.

1. reCAPTCHA 서비스 약관에 동의합니다.

1. 클릭 **제출**.

>[!NOTE]
>
>Marketo Engage 구성에 도움이 되도록 사이트 키와 비밀 키를 가까이 보관합니다.

## Marketo Engage에서 CAPTCHA 설정 {#setting-up-captcha-in-marketo-engage}

1. Marketo에서 **관리** 을(를) 선택합니다. **CAPTCHA**.

PICC

1. 클릭 **편집** CAPTCHA 설정

PICC

1. CAPTCHA 드롭다운을 클릭하고 reCAPTCHA v3을 선택합니다.

PICC

1. 비밀 키 및 사이트 키를 삽입합니다. 클릭 **저장** 완료 시.

PICC
