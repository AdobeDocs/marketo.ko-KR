---
description: 대화 상자 - Marketo 문서 - 제품 설명서
title: 대화 상자
hide: true
hidefromtoc: true
source-git-commit: 1a1d4cb7e013253ce7189150486ba03ea02d877d
workflow-type: tm+mt
source-wordcount: '473'
ht-degree: 0%

---

# 대화 상자 {#dialogues}

대화 상자는 사용자가 설정한 특정 채팅 대화입니다. 그들은 누가 그것을 보고 말하는것뿐만 아니라, 외모로 맞춤화될 수 있다.

## 새 대화 상자 만들기 {#create-a-new-dialogue}

1. **대화 상자**&#x200B;를 클릭합니다.

PICC

1. **새로 만들기** 단추를 클릭합니다.

PICC

1. 이름을 입력하고(설명은 선택 사항) 우선 순위 수준을 설정한 다음 **저장**&#x200B;을 클릭합니다.

PICC

>[!NOTE]
>
>우선순위 수준 설명

## 대상 기준 {#audience-criteria}

Marketo 스마트 목록과 유사한 대상 기준 속성을 사용하여 타겟 대상을 정의할 수 있습니다.

선택할 수 있는 속성은 몇 가지가 있습니다. 이 예에서는 50명 이상의 직원이 있는 회사에서 일하는 알려진 모든 리드를 타겟팅합니다.

1. 리드 상태 속성을 선택하고 오른쪽으로 드래그합니다.

PICC

1. __ Isis는 기본적으로 설정되어 있습니다. 값 선택 필드에 CA를 입력합니다. 드롭다운을 클릭하고 목록에서 선택할 수도 있습니다.

PICC

1. 회사 크기 특성을 선택하고 오른쪽으로 드래그합니다.

PICC

1. 연산자 드롭다운을 클릭하고 보다 큼 을 선택합니다.

PICC

1. 50을 입력하고 화면의 아무 곳이나 클릭하여 저장합니다.

PICC

리드 캡처 방법

참고 - 유추된 작동/표시 사용 사례, 리드 이메일이 비어 있는 방법을 언급했을 수 있습니다.

## 그룹 추가 {#add-groups}

다른 속성의 &quot;any&quot;와 함께 모든 특정 속성을 사용하려는 경우 속성을 그룹화하는 옵션이 있습니다.

완료

## Target {#target}

여기에서 특정 대화 상자를 표시할 특정 URL을 입력합니다.

허용 가능한 형식:

* `http://website.com`
* `https://*.website.com`
* `http://website.com/folder/*`
* `https://*.website.com/folder/*`

>[!NOTE]
>
>별표를 사용하는 것은 다목적 엽서 역할을 합니다. 따라서 `https://*.website.com` 은 하위 도메인을 포함하여 사이트의 모든 페이지에 대화 상자를 둡니다(예: `support.website.com`) 및 `https://website.com/folder/*` 은 후속 폴더의 모든 HTML 페이지에 대화 상자를 표시합니다(예: 이 경우 폴더가 &quot;sports&quot;라고 가정해 보겠습니다. website.com/sports/baseball.html, website.com/sports/football.html 등)

## 스트림 디자이너 {#stream-designer}

스트림 디자이너에는 채팅 대화 모양을 만들기 위해 추가할 수 있는 다른 카드가 포함되어 있습니다.

표

메시지: 응답 없이 구문을 만들려면(예: &quot;안녕! 코드 SAVE25를 사용하면 모든 항목이 오늘 25% 할인됩니다.&quot;)

질문: 사용 가능한 응답을 제공하는 다중 선택 질문을 하려면 를 사용합니다(예: 어떤 차종에 관심이 있으십니까? 응답 = SUV, 컴팩트, 트럭 등

정보 캡처: 정보를 수집하려면 를 사용하십시오. 선택할 수 있는 세 개의 필드는 이메일 주소, 전화 번호 및 텍스트(방문자가 고유한 메시지를 작성할 수 있음)입니다.

약속 스케줄러: 방문자에게 후속 작업을 예약하기 위해 사용 가능한 날짜 달력을 제공합니다. 일정 가용성은 [다음 에이전트를 줄](/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md#routing)에 반영합니다.

목표: 방문자가 볼 수 없는 유일한 카드입니다. 특정 채팅(예: 방문자의 이메일을 수집하는 것이 목표인 경우 스트림에서 정보 캡처 뒤에 목표 카드를 배치합니다.)

가능한 자체 섹션

아래에 예를 보여줍니다.