---
description: 대상 기준 - Marketo 문서 - 제품 설명서
title: 대상 기준
feature: Dynamic Chat
exl-id: 95c4558e-0c0c-4623-bb7d-b6ac2f455c01
source-git-commit: d255c1c4c15d5aca5d89687f50ee0e6f0dedfb7d
workflow-type: tm+mt
source-wordcount: '605'
ht-degree: 1%

---

# 대상 기준 {#audience-criteria}

대상 기준 속성을 사용하면 Marketo Engage 스마트 목록과 유사하게 대상 대상을 정의할 수 있습니다. 유추, 개인 또는 회사 속성(또는 이들의 조합)을 사용하여 알려지거나 알려지지 않은 사람을 타깃팅할 수 있습니다.

## 우선순위 {#priority}

우선 순위는 잠재 고객이 두 개 이상의 자격이 있는 경우 받을 대화 상자를 결정합니다. 처음 [대화 상자를 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}할 때 설정됩니다. 기존 대화 상자를 열고 대상 기준 탭에서 **[!UICONTROL 대화 상자 세부 정보]**(으)로 이동하여 대화 상자의 우선 순위를 변경할 수 있습니다.

![](assets/audience-criteria-1.png)

## 이벤트 {#events}

이벤트를 사용하면 스크롤하는 시간이나 페이지/사이트에 있는 시간에 따라 방문자를 타깃팅할 수 있습니다. 아래 예에서는 20초 이상 특정 페이지에 있었던 방문자를 대상으로 합니다.

1. **[!UICONTROL Time on Page]** 이벤트를 가져와서 오른쪽으로 끕니다.

   ![](assets/audience-criteria-3.png)

1. &quot;보다 큼&quot; 시간을 20초로 설정합니다.

   ![](assets/audience-criteria-4.png)

1. [Target](#target) 섹션에 원하는 페이지의 URL을 추가하십시오.

   ![](assets/audience-criteria-5.png)

## 속성 {#attributes}

**알려진 사용자**

선택할 _많은_ 특성 조합이 있습니다. 아래 예에서는 캘리포니아에 있는 직원 수 50명 이상의 회사에 근무하는 알려진 모든 사람을 대상으로 합니다.

1. **[!UICONTROL Person State]** 특성을 가져와서 오른쪽으로 끕니다.

   ![](assets/audience-criteria-7.png)

1. _Is_&#x200B;이(가) 기본적으로 설정되어 있습니다. 값 선택 필드에 CA를 입력합니다(드롭다운을 클릭하고 목록에서 선택할 수도 있음).

   ![](assets/audience-criteria-8.png)

1. **[!UICONTROL Company Size]** 특성을 가져와서 _여기에 특성을 끌어다 놓기_&#x200B;하는 위치로 끌어 놓습니다.

   ![](assets/audience-criteria-9.png)

   >[!NOTE]
   >
   >해당 **+** 아이콘을 클릭하여 특성을 선택할 수도 있습니다.

1. 연산자 드롭다운을 클릭하고 **[!UICONTROL 다음보다 큼]**&#x200B;을 선택합니다.

   ![](assets/audience-criteria-10.png)

1. 50을 입력하고 화면의 아무 곳이나 클릭하여 저장합니다.

   ![](assets/audience-criteria-11.png)

다 됐습니다!

**익명 사용자**

데이터베이스에 아직 없는 사용자를 구체적으로 타겟팅하는 쉬운 방법이 있습니다. 이 예제에서는 뉴욕 지역에 있는 모든 익명의 사용자를 타겟으로 합니다.

1. **[!UICONTROL 개인 전자 메일]** 특성을 가져와서 오른쪽으로 끕니다.

   ![](assets/audience-criteria-12.png)

1. 연산자 드롭다운을 클릭하고 **[!UICONTROL 비어 있음]**&#x200B;을 선택합니다.

   ![](assets/audience-criteria-13.png)

1. **[!UICONTROL Referred State]** 특성을 가져와서 _특성을 여기에 끌어다 놓기_&#x200B;로 끕니다.

   ![](assets/audience-criteria-14.png)

   >[!NOTE]
   >
   >누군가가 웹 사이트를 방문하면 [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}에서 쿠키를 만들어 시스템에 넣습니다. 우리는 특별한 데이터베이스에서 그들의 IP를 찾고 모든 종류의 좋은 정보를 추론한다.

1. _Is_&#x200B;이(가) 기본적으로 설정되어 있습니다. 값 선택 필드에 NY를 입력합니다(드롭다운을 클릭하고 목록에서 선택할 수도 있음).

   ![](assets/audience-criteria-15.png)

## 멤버십 {#membership}

대화 상자의 타겟 대상에 Marketo Engage 스마트 목록 을 사용합니다.

>[!AVAILABILITY]
>
>스마트 목록 구성원 또는 목록 구성원 기준을 사용하려면 Dynamic Chat Prime이 필요합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

1. [멤버십]에서 **[!UICONTROL Smart List의 멤버]**&#x200B;을(를) 가져와서 캔버스에 놓습니다.

   ![](assets/audience-criteria-15a.png)

1. 원하는 스마트 목록을 선택합니다.

   ![](assets/audience-criteria-15b.png)

## 그룹 추가 {#add-groups}

특정 속성을 모두 &quot;모두 또는 모두&quot;와 함께 사용하려는 경우에도 속성을 그룹화할 수 있습니다. 여러 그룹을 추가할 수 있습니다.

![](assets/audience-criteria-16.png)

![](assets/audience-criteria-17.png)

## Target {#target}

여기에서 특정 대화 상자를 표시할 URL을 입력합니다. 제외를 추가할 수도 있습니다.

허용되는 형식:

* `http://website.com`
* `https://*.website.com`
* `http://website.com/folder/*`
* `https://*.website.com/folder/*`

>[!NOTE]
>
>* 별표를 사용하는 것은 만능의 와일드카드 역할을 합니다. 따라서 `https://*.website.com`은(는) 하위 도메인을 포함하여 사이트의 모든 페이지에 대화 상자를 표시합니다(예: `support.website.com`). `https://website.com/folder/*`은(는) 후속 폴더의 모든 HTML 페이지에 대화 상자를 추가합니다(예: 이 경우 폴더가 &quot;sports&quot;라고 가정해 보겠습니다. website.com/sports/baseball.html, website.com/sports/football.html 등).
>
>* 현재 URL 매개 변수는 지원되지 않습니다.

**제외**

제외를 사용하여 사이트의 특정 페이지/영역에 대화 상자가 _표시되지 않음_&#x200B;되게 합니다. 제외는 포함과 동일한 형식을 따릅니다.

![](assets/audience-criteria-18.png)

>[!MORELIKETHIS]
>
>* [대화 상자 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}
>* [Designer 스트리밍](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/stream-designer.md){target="_blank"}
