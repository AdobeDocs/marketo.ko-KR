---
solution: Marketo Engage
product: marketo
title: Personalization 토큰
description: 새로운 Marketo Engage 이메일 Designer에서 개인화 토큰을 사용하는 방법을 알아봅니다
level: Beginner, Intermediate
hide: true
hidefromtoc: true
source-git-commit: 0abb2a7499541b8efbf3000bcd9fc9c1a79e43e1
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 0%

---

# Personalization 토큰 {#personalization-tokens}

이메일 Designer의 이메일 개인화 토큰은 클래식 이메일 편집기와 다른 형식입니다. 이 변경 사항은 Handlebar 스크립팅과의 호환성을 개선하고 이메일 작성 프로세스를 간소화하기 위해 구현되었습니다.

>[!AVAILABILITY]
>
>2025년 5월 23일부터 이 기능은 Marketo Engage 사용자에게 일괄로 제공되며, 한 지역은 매주 업데이트됩니다. 롤아웃 중에 새 이메일 디자이너를 사용하여 만든 모든 이메일은 기존 토큰을 새 형식으로 자동으로 마이그레이션합니다. 이 업데이트를 통해 모든 토큰을 영어로만 사용할 수 있습니다.

## 기본 사용 사례 {#primary-use-case}

이 개선 사항은 주로 [Velocity 스크립팅](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/email-scripting){target="_blank"}에서 Handlebar 스크립팅으로 전환하는 데 도움이 됩니다. 새 이메일 Designer은 새 토큰 형식만 지원합니다. 업데이트된 형식은 공백을 제거하고 수정된 기본 텍스트 구조를 도입하여 더 유연하고 효율적인 스크립팅 환경을 보장합니다.

## 토큰 경험 {#token-experience}

토큰 경험을 살펴보십시오. 기존 경험과 신규 경험 모두.

### 이전 형식 {#old-format}

클래식 전자 메일 편집기에서 `lead.Anonymous IP` 또는 `member.registration code`과(와) 같이 공백이 있는 토큰을 추가할 수 있습니다. 기본 텍스트 형식은 `{{lead.City:default=fallback}}`입니다.

![](assets/personalization-tokens-1.png){width="500" zoomable="yes"}

### 새 형식 {#new-format}

전자 메일 디자이너에서 [카멜 대/소문자](https://developer.mozilla.org/en-US/docs/Glossary/Camel_case) 또는 토큰에 대한 밑줄(예: `lead.anonymousIP` 또는 `member.registration_code`)을 적용해야 합니다. 기본 텍스트 형식도 `{%=lead.city ?: "fallback" %}`(으)로 변경됩니다.

![](assets/personalization-tokens-2.png){width="600" zoomable="yes"}

## 참고할 사항 {#things-to-note}

* 개인화 편집기에는 작성의 편의를 위해 다음 기능도 포함되어 있습니다.

   * 실행 취소/다시 실행
   * 찾기/찾기 및 바꾸기
   * 자동 완성

* 이전에 Marketo Engage에서 지원된 **모든** 토큰은 새 개인화 편집기에서 지원됩니다.
