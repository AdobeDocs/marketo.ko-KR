---
description: 이메일 템플릿의 필드 프롬프트에 대해 알아봅니다. 보낼 때 발신자에게 사용자 지정 콘텐츠를 입력하라는 메시지를 표시하는 자리 표시자를 추가합니다.
title: 필드 프롬프트
exl-id: c138b627-f853-4d35-b022-cc517d6b86d4
source-git-commit: 03f984d4049c119267c7b2c2baa4e68c7db34ad0
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 2%

---

# 필드 프롬프트 {#field-prompts}

필드 프롬프트를 사용하면 이메일을 보내기 전에 제거하거나 대체해야 하는 이메일에 텍스트 문자열을 추가할 수 있습니다. 이는 사용자에게 추가적인 개인화를 추가하도록 상기시키는 좋은 방법입니다.

필드 프롬프트를 추가하려면 원하는 텍스트를 입력하십시오. 느낌표를 붙인 다음 중괄호로 둘러쌉니다(아래 참조).

**예:**

`{{! Introduce yourself}}`

`{{! Insert name of Account Executive}}`

`{{! Add sentence that references their industry and role}}`

<p>사용자는 이메일을 보내기 전에 이 텍스트를 자신의 개인화로 바꾸어야 합니다.

![](assets/field-prompts-1.png)

>[!NOTE]
>
>영업 캠페인에 프롬프트를 사용할 때는 수동 이메일 단계와 함께 사용하는 것이 좋습니다. 이 단계에서는 사용자에게 이메일을 보낼 미리 알림 작업을 할당하여 프롬프트를 사용자 정의 텍스트로 바꿀 수 있는 기회를 제공합니다. 판매 캠페인의 자동 이메일 단계는 사용자가 프롬프트를 바꿀 수 없도록 자동 전송을 시도합니다. 바꾸지 않는 프롬프트로 인해 이메일을 보낼 수 없습니다.
