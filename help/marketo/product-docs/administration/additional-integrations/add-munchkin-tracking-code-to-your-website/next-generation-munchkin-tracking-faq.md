---
unique-page-id: 10096583
description: 차세대 [!DNL Munchkin] 추적 롤아웃 및 익명 필터 변경에 대한 FAQ입니다.
title: 다음 세대 [!DNL Munchkin] 추적 FAQ
exl-id: 283189ac-c817-479a-b896-91233980608c
feature: Administration, Munchkin Tracking Code
hide: true
hidefromtoc: true
source-git-commit: 40f06a5391f2f7263bea0c5b8cefc1f3a607c68c
workflow-type: tm+mt
source-wordcount: '705'
ht-degree: 0%

---

# 다음 세대 [!DNL Munchkin] 추적 FAQ {#next-generation-munchkin-tracking-faq}

Marketo이 차세대 웹 추적 기술을 단계적으로 출시한다.

다음은 알아야 할 가장 중요한 사항입니다.

* &quot;익명의&quot; 스마트 목록 필터가 제거되었습니다.
* Marketo에서 수집할 수 있는 웹 이벤트(웹 페이지 방문, 웹 페이지에서 링크 클릭)의 수가 증가하고 있습니다
* [!DNL Munchkin] 코드는 변경되지 않으므로 웹 사이트에 업데이트가 필요하지 않습니다.

## 내 Marketo 구독은 언제 [!DNL Munchkin] V2에 표시됩니까? {#when-will-my-marketo-subscription-be-on-munchkin-v}

정확한 날짜는 아직 정해지지 않았습니다. 이 페이지에서 업데이트를 확인하십시오.

## 웹 사이트에서 내 [!DNL Munchkin] 추적을 변경해야 합니까? {#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

아니요. [!DNL Munchkin] 추적 코드는 그대로 유지됩니다. 웹 사이트를 변경할 필요가 없습니다.

>[!NOTE]
>
>이 변경 사항은 웹 Personalization(실시간 Personalization)에 영향을 주지 않습니다. 익명의 웹 방문자와 알려진 웹 방문자를 계속 식별하고 이러한 방문자에게 실시간으로 콘텐츠를 개인화합니다.

## Marketo이 스마트 목록에서 &quot;익명임&quot; 필터를 제거한 이유는 무엇입니까? {#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

Marketo은 익명의 사람들이 스마트 캠페인과 상호 작용하는 방식을 변경했습니다. 이전에, 그들은 알려진 사람들과 마찬가지로 똑똑한 캠페인을 통과했다. &quot;익명성&quot; 필터는 알려진 사람만 또는 익명의 사람만 캠페인을 통과하도록 지정하는 데 사용되었습니다.

[!DNL Munchkin] V2를 사용하면 Marketo에서 모든 익명 활동을 계속 추적하지만 더 이상 익명 사용자에게 필터를 적용할 수 없습니다. 전환 시점(해당 사용자가 Marketo에 알려짐)에 해당 사용자가 익명일 때 발생한 모든 활동이 개인 활동 로그에 추가되며, 이때 해당 활동은 자격이 있는 캠페인을 통해 흐릅니다.

스마트 목록(예: 스마트 캠페인 또는 보고서)에서 이 필터를 이미 사용 중인 경우 스마트 목록에서 자동으로 제거되지 않습니다. 자세한 내용은 아래를 참조하십시오.

>[!NOTE]
>
>**트리거**: 방문 웹 페이지, 웹 페이지가 가격 페이지임&#x200B;>**흐름**: 변경 점수 +10 및 관심 있는 순간&#x200B;>**웹**: 가격 페이지를 조회함
>
>[!DNL Munchkin] V2를 사용하면 익명의 사용자가 가격 책정 페이지를 방문하는 경우 캠페인을 바로 시작하지 않습니다. 익명의 사용자가 알려지면 Marketo에서 해당 사용자에 대해 이 캠페인을 실행합니다. 고객은 다음을 수행합니다.
>
>* 10점 받기
>
>* 웹 페이지 활동을 올바른 날짜(실제로 방문한 날짜)로 설정합니다.
>
>* 관심 있는 순간 기록(해당 사용자가 실제로 페이지를 방문한 날짜 포함, 알게 된 날짜 포함)
>
>* 오늘과 같이 &quot;새 사용자&quot; 활동이 기록됨

## 이미 &quot;익명 여부&quot; 필터가 있는 내 스마트 목록은 어떻게 됩니까? {#what-happens-to-my-smart-lists-that-already-have-the-is-anonymous-filter}

16년 겨울 릴리스 이후, &quot;익명 여부&quot; 필터가 있는 스마트 목록이 있는 이전 스마트 캠페인이 있는 경우 다음 두 가지 중 하나가 발생합니다.

1. 스마트 목록에 &quot;익명 여부 = False&quot; 필터가 있는 경우 아무 일도 발생하지 않습니다. 무시합니다.
1. 스마트 목록에 &quot;익명 여부 = True&quot; 필터가 있는 경우 이 캠페인이 실패하고 알림이 전송됩니다.

## 저는 Marketo을 한동안 사용했습니다. 어느 캠페인이 &quot;익명인지&quot; 필터를 사용하는지 어떻게 알 수 있습니까? {#ive-been-using-marketo-for-a-while-how-do-i-know-which-of-my-campaigns-use-the-is-anonymous-filter}

이 변경 전에 Marketo은 &quot;익명임&quot; 필터를 사용하는 스마트 목록, 스마트 캠페인 및 보고서 목록과 함께 몇 개의 주간 알림을 알림 받은 편지함에 보냈습니다. 현재 이 필터를 사용 중인 위치를 식별하는 데 도움이 될 수 있습니다.

이를 검토하고 &quot;익명성&quot;이 True로 설정된 위치를 식별합니다. 이것이 영향을 받는 캠페인입니다. 대부분의 경우 이 설정은 일종의 채점에 사용됩니다. 이러한 캠페인이 이제 어떻게 작동하는지 이해하려면 위의 예를 참조하십시오.

## 더 자세한 설명서를 원합니다. 어디에서 찾을 수 있나요? {#id-like-more-detailed-documentation-where-can-i-find-it}

다음 링크를 확인하십시오.

[익명 잠재 고객 업그레이드 개요](https://nation.marketo.com/docs/DOC-2937){target="_blank"}

[Anonymous Lead Upgrades - Changes Inside Marketo UI](https://nation.marketo.com/docs/DOC-2938){target="_blank"}

[Anonymous Lead Upgrades - Customer Action Needed](https://nation.marketo.com/docs/DOC-2939){target="_blank"}

[Anonymous Lead Upgrades - Analytics Reports](https://nation.marketo.com/docs/DOC-2940){target="_blank"}

[Anonymous Lead Upgrades - Release Schedule](https://nation.marketo.com/docs/DOC-2961){target="_blank"}

[Anonymous Lead Upgrades - Under The Hood](https://nation.marketo.com/docs/DOC-2962){target="_blank"}

[Anonymous Lead Promotion to Known Lead - [!DNL Munchkin] V2 Behavior](https://nation.marketo.com/docs/DOC-2963){target="_blank"}

## I have more questions! How do I get them answered? {#i-have-more-questions-how-do-i-get-them-answered}

Visit the [Marketo Community](https://experienceleaguecommunities.adobe.com/){target="_blank"}. You can also contact Marketo Support. They are happy to answer your questions.
