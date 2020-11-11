---
title: 내 토큰 이해
description: 내 토큰 이해
translation-type: tm+mt
source-git-commit: 642fd57105afff1031f18883c5809206f136b7c6
workflow-type: tm+mt
source-wordcount: '329'
ht-degree: 0%

---


# 내 토큰 이해

<br> 

내 토큰은 프로그램 또는 캠페인 폴더에서 만들고 사용할 수 있는 사용자 지정 변수입니다. 다음과 같습니다. `{{_my.Name of Token_}}`

## 예제

* `{{my.Event Date}}`
* `{{my.Webinar Speaker}}`

내 토큰에 액세스하여 만들려면 프로그램 또는 캠페인 폴더를 선택하고 [!UICONTROL My Tokens] 탭으로 이동합니다. 토큰을 캔버스에 드래그하여 [!UICONTROL Local Tokens] 놓습니다.

![이미지 원](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-1.png)

>[!CAUTION]
>
>내 토큰의 이름은 저장한 후에는 변경할 수 없으므로 신중하게 선택하십시오.

>[!NOTE]
>
>Microsoft Dynamics 또는 Salesforce의 Sales Insight에서 이메일을 보낼 때 내 토큰은 확인되지 않습니다.표준 토큰만 채워집니다(리드, 회사 등). 그러나 토큰의 기본값은 작동합니다.

>[!NOTE]
>
>링크 토큰은 텍스트 전용 이메일에서 작동하지 않습니다.

## 토큰 중첩

새 토큰을 만들면 트리의 다른 개체에서 참조할 수 있습니다. 트리의 하위 수준에서 글로벌 변수를 재정의할 수 있습니다. 편리한 관리를 위해 토큰을 만든 곳에 이름 지정 구조가 있습니다.

* **로컬 토큰:** 토큰은 해당 프로그램 또는 폴더에 직접 만들어졌습니다.
* **[재정의된 토큰:](/help/sky/override-an-inherited-my-token.md)** 토큰이 상속되었지만 이 프로그램 또는 폴더에서 예외가 발생했습니다.
* **상속된 토큰:** 토큰이 트리 위로 더 높은 수준의 프로그램 또는 폴더 어딘가에 만들어졌습니다.

프로그램 또는 캠페인 폴더의 [!UICONTROL **내 토큰**] 탭 아래에서 이 세 가지 유형을 찾을 수 있습니다.

![이미지 2](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-2.png)

프로그램 및 폴더 이동은 토큰에도 영향을 줍니다. 이동 중에 참조가 손상되지 않았는지 항상 확인합니다.

>[!NOTE]
>
>참여 프로그램에서 보낸 이메일이 기본 프로그램의 하위 이메일(예: 참여 프로그램의 로컬 이메일 아님)인 경우, 이메일에 사용된 내 토큰은 하위 이메일이 상주하는 기본 프로그램에서 해결됩니다.

## 토큰 사용

토큰을 선택한 다음 오른쪽 상단 모서리의 사용 아이콘을 클릭하여 해당 토큰을 포함하는 자산 목록을 확인합니다.

![이미지 3](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-3.png)

![이미지 4](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-4.png)

**딥 다이브**

내 토큰에 대한 자세한 내용:

* [CRM 캠페인](/help/sky/my-token-crm-campaign.md)
* [날짜](/help/sky/my-token-date.md)
* [달력 파일](/help/sky/my-token-calendar-file.md)
* [이미지](/help/sky/my-token-image.md)
* [링크](/help/sky/my-token-link.md)
* [숫자](/help/sky/my-token-number.md)
* [리치 텍스트](/help/sky/my-token-rich-text.md)
* [점수](/help/sky/my-token-score.md)
* [이메일 스크립트](/help/sky/my-token-email-script.md)
* [텍스트](/help/sky/my-token-text.md)
