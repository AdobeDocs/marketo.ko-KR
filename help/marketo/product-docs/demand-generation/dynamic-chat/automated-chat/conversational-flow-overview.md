---
description: 대화형 흐름 개요 - Marketo 문서 - 제품 설명서
title: 대화 흐름 개요
feature: Dynamic Chat
exl-id: c741886d-d672-471f-8902-208d25898afa
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 0%

---

# 대화 흐름 개요 {#conversational-flow-overview}

대화형 흐름을 디자인하고 특정 작업(예: call-to-action 버튼 클릭, 페이지 로드 시, 페이지에서 보낸 시간 등)을 기반으로 방문자에게 이를 트리거합니다.

![](assets/conversational-flow-overview-1.png)

## 대화 상자 대 대화 흐름 {#dialogues-vs-conversational-flows}

대화 상자 및 대화 흐름에는 몇 가지 유사성이 있지만 두 가지 별개의 기능입니다.

<table>
 <tbody>
  <tr>
   <th style="width:50%">대화 상자</th>
   <th style="width:50%">대화 플로우</th>
  </tr>
  <tr>
   <td>대화 상자가 타깃팅됨 - 구현한 매개 변수를 기반으로 특정 페이지 및 대상자에 대한 대화를 디자인합니다.</td>
   <td>대화 흐름이 트리거됨 - 양식 작성, 링크 클릭 등과 같은 방문자의 작업에 따라 트리거될 수 있는 대화를 디자인합니다.</td>
  </tr>
   <tr>
   <td>챗봇 인터페이스에서만 지원됩니다.</td>
   <td>현재 추가 인터페이스를 계획하고 팝업 인터페이스에서 지원됩니다.</td>
  </tr>
  </tr>
   <tr>
   <td>동일한 잠재 고객 세그먼트에 대해 여러 개의 대화 상자를 우선순위 순서로 만들 수 있으므로 각 방문자는 계속 참여할 때 우선순위에 따라 대화 상자를 순서대로 볼 수 있습니다.</td>
   <td>전환 흐름에는 우선 순위가 없으며 결정된 call-to-action에 따라 동일한 리드에 의해 여러 번 트리거될 수 있습니다.</td>
  </tr>
  <tr>
   <td>챗봇 대화는 대화 상자를 통해 제공됩니다.</td>
   <td>Marketo Engage의 <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">대화형 Forms</a>은(는) 대화형 흐름을 기반으로 합니다.</td>
  </tr>
 </tbody>
</table>

## 스트림 Designer 탭 {#stream-designer-tab}

대화형 흐름에 대한 스트림 Designer은 대화 상자에 대한 스트림과 거의 동일합니다. [여기에서 자세히 알아보세요](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/stream-designer.md){target="_blank"}.

![](assets/conversational-flow-overview-2.png)

## 보고서 탭 {#reports-tab}

보고서 탭에서는 대화형 흐름의 성능 수준에 대한 지표를 볼 수 있습니다.

![](assets/conversational-flow-overview-3.png)

참여 비율, 전환율 보기, 알려진 방문자 및/또는 알 수 없는 방문자로 필터링 등.

![](assets/conversational-flow-overview-4.png)

## 설정 탭 {#settings-tab}

![](assets/conversational-flow-overview-5.png)

설정 탭의 상단에서 대화형 흐름의 이름을 업데이트하고, 선택적 설명을 추가하고, 언어를 변경할 수 있습니다.

![](assets/conversational-flow-overview-6.png)

>[!NOTE]
>
>다른 언어를 선택하면 시스템 텍스트의 언어만 변경됩니다. 콘텐츠 번역은 사용자가 담당합니다.

### 대화 SDK {#conversations-sdk}

설정 탭의 하단에서 대화 트리거(대화 SDK)를 사용자 지정합니다. 방문자가 링크를 클릭할 때 또는 페이지 로드 시 웹 사이트에서 대화가 트리거되는지 여부를 결정할 수 있습니다.

![](assets/conversational-flow-overview-7.png)

>[!TIP]
>
>작동 중인 [대화 SDK](https://experienceleague.adobe.com/tools/marketo-dynamic-chatbot/conversations-sdk/){target="_blank"}을 확인하세요!

>[!MORELIKETHIS]
>
>[대화 흐름 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-conversational-flow.md){target="_blank"}
