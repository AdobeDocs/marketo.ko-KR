---
description: 대상 기준 - Marketo 문서 - 제품 설명서
title: 대상 기준
exl-id: 9b70b03e-229e-469e-bd65-07aaf2dcbec6
feature: Dynamic Chat
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '540'
ht-degree: 2%

---

# 대상 기준 {#audience-criteria}

Marketo 스마트 목록과 유사한 대상 기준 속성을 사용하여 타겟 대상을 정의할 수 있습니다. 유추, 개인 또는 회사 속성(또는 이들의 조합)을 사용하여 알려지거나 알려지지 않은 사람을 타깃팅할 수 있습니다.

## 우선 순위 {#priority}

우선 순위는 잠재 고객이 두 개 이상의 자격이 있는 경우 받을 대화 상자를 결정합니다. 처음 시작했을 때 설정됩니다. [대화 상자 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target="_blank"}. 기존 대화 상자를 열고 로 이동하여 대화 상자의 우선 순위를 변경할 수 있습니다. **대화 상자 세부 정보** 대상 기준 탭에서.

![](assets/audience-criteria-1.png)

## 이벤트 {#events}

![](assets/audience-criteria-2.png)

이벤트를 사용하면 스크롤하는 시간이나 페이지/사이트에 있는 시간에 따라 방문자를 타깃팅할 수 있습니다. 아래 예에서는 20초 이상 특정 페이지에 있었던 방문자를 대상으로 합니다.

1. 다음 항목을 가져옵니다. **페이지에서 시간** 이벤트를 표시하고 오른쪽으로 드래그합니다.

   ![](assets/audience-criteria-3.png)

1. &quot;보다 큼&quot; 시간을 20초로 설정합니다.

   ![](assets/audience-criteria-4.png)

1. 에서 원하는 페이지의 URL을 추가합니다. [Target](#target) 섹션.

   ![](assets/audience-criteria-5.png)

## 속성 {#attributes}

![](assets/audience-criteria-6.png)

**알려진 사람**

다음 항목이 있습니다. _많음_ 선택할 속성 조합입니다. 아래 예에서는 모든 을(를) 타깃팅합니다. **알려진 사람** 캘리포니아에서 50명 이상의 직원이 있는 회사에서 일합니다.

1. 다음 항목을 가져옵니다. **사용자 상태** 속성을 지정하고 오른쪽으로 드래그합니다.

   ![](assets/audience-criteria-7.png)

1. _다음과 같음_ 는 기본적으로 설정되어 있습니다. 값 선택 필드에 CA를 입력합니다(드롭다운을 클릭하고 목록에서 선택할 수도 있음).

   ![](assets/audience-criteria-8.png)

1. 다음 항목을 가져옵니다. **회사 규모** 속성을 지정하고 표시된 위치로 드래그합니다. _여기에 속성 끌어다 놓기_.

   ![](assets/audience-criteria-9.png)

   >[!NOTE]
   >
   >속성을 클릭하여 선택할 수도 있습니다 **+** 아이콘.

1. 연산자 드롭다운을 클릭하고 를 선택합니다. **보다 큼**.

   ![](assets/audience-criteria-10.png)

1. 50을 입력하고 화면의 아무 곳이나 클릭하여 저장합니다.

   ![](assets/audience-criteria-11.png)

다 됐습니다!

**익명 사용자**

데이터베이스에 아직 없는 사용자를 구체적으로 타겟팅하는 쉬운 방법이 있습니다. 이 예제에서는 모든 대상을 타겟팅합니다 **익명의 사람** 뉴욕 지역에 위치하고 있습니다.

1. 다음 항목을 가져옵니다. **개인 이메일** 속성을 지정하고 오른쪽으로 드래그합니다.

   ![](assets/audience-criteria-12.png)

1. 연산자 드롭다운을 클릭하고 를 선택합니다. **비어 있음**.

   ![](assets/audience-criteria-13.png)

1. 다음 항목을 가져옵니다. **상태 유추** 속성을 지정하고 표시된 위치로 드래그합니다. _여기에 속성 끌어다 놓기_.

   ![](assets/audience-criteria-14.png)

   >[!NOTE]
   >
   >누군가가 귀하의 웹 사이트를 방문할 때, [먼치킨](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) 쿠키를 만들어 시스템에 넣습니다. 우리는 특별한 데이터베이스에서 그들의 IP를 찾고 모든 종류의 좋은 정보를 추론한다.

1. _다음과 같음_ 는 기본적으로 설정되어 있습니다. 값 선택 필드에 NY를 입력합니다(드롭다운을 클릭하고 목록에서 선택할 수도 있음).

   ![](assets/audience-criteria-15.png)

## 그룹 추가 {#add-groups}

특정 속성을 모두 &quot;모두 또는 모두&quot;와 함께 사용하려는 경우에도 속성을 그룹화할 수 있습니다. 여러 그룹을 추가할 수 있습니다.

![](assets/audience-criteria-16.png)

![](assets/audience-criteria-17.png)

## 대상 {#target}

여기에서 특정 대화 상자를 표시할 URL을 입력합니다. 제외를 추가할 수도 있습니다.

허용되는 형식:

* `http://website.com`
* `https://*.website.com`
* `http://website.com/folder/*`
* `https://*.website.com/folder/*`

>[!NOTE]
>
>별표를 사용하는 것은 만능의 와일드카드 역할을 합니다. So `https://*.website.com` 은 하위 도메인을 포함하여 사이트의 모든 페이지에 대화 상자를 추가합니다(예: `support.website.com`). 및 `https://website.com/folder/*` 후속 폴더의 모든 HTML 페이지에 대화 상자가 표시됩니다(예: 이 경우 폴더가 &quot;sports&quot;라고 가정해 보겠습니다. website.com/sports/baseball.html, website.com/sports/football.html 등).

**제외**

제외를 사용하여 대화 상자가 다음을 수행하는지 확인합니다 **아님** 사이트의 특정 페이지/영역에 표시됩니다. 제외는 포함과 동일한 형식을 따릅니다.

![](assets/audience-criteria-18.png)

>[!MORELIKETHIS]
>
>* [대화 상자 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target="_blank"}
>* [스트림 디자이너](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/stream-designer.md){target="_blank"}
>* [보고서](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/reports.md){target="_blank"}
