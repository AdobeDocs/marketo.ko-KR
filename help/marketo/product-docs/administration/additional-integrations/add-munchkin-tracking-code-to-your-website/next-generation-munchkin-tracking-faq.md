---
unique-page-id: 10096583
description: 차세대 [!DNL Munchkin] 추적 FAQ - Marketo 문서 - 제품 설명서
title: 다음 세대 [!DNL Munchkin] 추적 FAQ
exl-id: 283189ac-c817-479a-b896-91233980608c
feature: Administration, Munchkin Tracking Code
hide: true
hidefromtoc: true
source-git-commit: ea07c5c83c51fef4eb454562f041db685cf13775
workflow-type: tm+mt
source-wordcount: '698'
ht-degree: 0%

---

# 다음 세대 [!DNL Munchkin] 추적 FAQ {#next-generation-munchkin-tracking-faq}

곧 차세대 웹 추적 기술의 단계적 롤아웃을 시작할 예정임을 발표하게 되어 매우 기쁘게 생각합니다.

다음은 알아야 할 가장 중요한 사항입니다.

* 1분기 릴리스(이미 완료)에서 &quot;익명&quot; 스마트 목록 필터를 제거하고 있습니다.
* 수집할 수 있는 웹 이벤트(웹 페이지 방문, 웹 페이지에서 링크 클릭)의 수를 늘리고 있습니다
* [!DNL Munchkin] 코드는 변경되지 않으므로 웹 사이트에 업데이트가 필요하지 않습니다.

## 내 Marketo 구독은 언제 [!DNL Munchkin] V2에 표시됩니까? {#when-will-my-marketo-subscription-be-on-munchkin-v}

아직 정확한 날짜가 없지만 업데이트를 보려면 여기에서 다시 확인하십시오.

## 웹 사이트에서 내 [!DNL Munchkin] 추적을 변경해야 합니까? {#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

아니요. [!DNL Munchkin] 추적 코드는 그대로 유지됩니다. 웹 사이트를 변경할 필요가 없습니다.

>[!NOTE]
>
>이 변경 사항은 웹 Personalization(실시간 Personalization)에 영향을 주지 않습니다. 익명의 웹 방문자와 알려진 웹 방문자를 계속 식별하고 이러한 방문자에게 실시간으로 콘텐츠를 개인화합니다.

## Marketo이 스마트 목록에서 &quot;익명임&quot; 필터를 제거한 이유는 무엇입니까? {#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

익명의 사용자가 스마트 캠페인과 상호 작용하는 방식을 변경했습니다. 이전에, 그들은 알려진 사람들과 마찬가지로 똑똑한 캠페인을 통과했다. &quot;익명성&quot; 필터는 알려진 사람만 또는 익명의 사람만 캠페인을 통과하도록 지정하는 데 사용되었습니다.

[!DNL Munchkin] V2에서는 모든 익명 활동을 계속 추적하지만 더 이상 익명 사용자에게 필터를 적용할 수 없습니다. 전환 시점(해당 사용자가 Marketo에 알려짐)에 해당 사용자가 익명일 때 발생한 모든 활동이 개인 활동 로그에 추가되며, 이때 해당 활동은 자격이 있는 캠페인을 통해 흐릅니다.

스마트 목록(예: 스마트 캠페인 또는 보고서)에서 이 필터를 이미 사용 중인 경우 스마트 목록에서 자동으로 제거되지 않습니다. 자세한 내용은 아래를 참조하십시오.

>[!NOTE]
>
>**트리거**: 방문 웹 페이지, 웹 페이지가 가격 페이지임\
>**흐름**: 변경 점수 +10 및 즐거운 순간
>>**웹**: 가격 페이지를 조회함
>
>[!DNL Munchkin] V2를 사용하면 익명의 사용자가 가격 책정 페이지를 방문하는 경우 캠페인을 바로 시작하지 않습니다. 익명의 인물이 알려질 때, 우리는 그녀에 대해 이 캠페인을 실행할 것입니다. She will:
>
>* 10점 받기
>
>* 웹 페이지 활동을 올바른 날짜(실제로 방문했을 때)로 설정합니다.
>
>* (그녀가 실제로 페이지를 방문한 날짜와 함께, 그녀가 알려졌을 때가 아님) 그녀를 위해 기록 된 흥미로운 순간
>
>* 오늘과 같이 &quot;새 사용자&quot; 활동이 기록됨

## 이미 &quot;익명 여부&quot; 필터가 있는 내 스마트 목록은 어떻게 됩니까? {#what-happens-to-my-smart-lists-that-already-have-the-is-anonymous-filter}

16년 겨울 릴리스 이후, &quot;익명 여부&quot; 필터가 있는 스마트 목록이 있는 이전 스마트 캠페인이 있는 경우 다음 두 가지 중 하나가 발생합니다.

1. 스마트 목록에 &quot;익명 여부 = False&quot; 필터가 있는 경우 아무 일도 발생하지 않습니다. 그냥 무시하죠.
1. 스마트 목록에 &quot;익명성 = True&quot; 필터가 있는 경우 이 캠페인은 실패하고 알림이 전송됩니다.

## Marketo을 사용한지 꽤 되었어요. 어느 캠페인이 &quot;익명인지&quot; 필터를 사용하는지 어떻게 알 수 있습니까? {#ive-been-using-marketo-for-a-while-how-do-i-know-which-of-my-campaigns-use-the-is-anonymous-filter}

이 변경 작업을 수행하기 전에 &quot;익명임&quot; 필터를 사용하는 스마트 목록, 스마트 캠페인 및 보고서 목록이 포함된 몇 개의 주간 알림을 알림 받은 편지함으로 보냈습니다. 현재 이 필터를 사용 중인 위치를 식별하는 데 도움이 될 수 있습니다.

이러한 항목을 검토하고 &quot;익명 여부&quot;가 True로 설정된 위치를 식별하십시오. 이러한 항목이 영향을 받는 캠페인입니다. 대부분의 경우 고객은 일종의 채점에 대해 이 설정을 사용합니다. 이러한 캠페인이 이제 어떻게 작동하는지 이해하려면 위의 예를 참조하십시오.

## 좀 더 상세한 설명서가 있었으면 합니다. 어디에서 찾을 수 있나요? {#id-like-more-detailed-documentation-where-can-i-find-it}

다음 링크를 확인하십시오.

[익명 잠재 고객 업그레이드 개요](https://nation.marketo.com/docs/DOC-2937){target="_blank"}

[익명 잠재 고객 업그레이드 - Marketo UI 내 변경 사항](https://nation.marketo.com/docs/DOC-2938){target="_blank"}

[익명 잠재 고객 업그레이드 - 고객 조치 필요](https://nation.marketo.com/docs/DOC-2939){target="_blank"}

[익명 잠재 고객 업그레이드 - Analytics 보고서](https://nation.marketo.com/docs/DOC-2940){target="_blank"}

[익명 잠재 고객 업그레이드 - 릴리스 일정](https://nation.marketo.com/docs/DOC-2961){target="_blank"}

[익명 잠재 고객 업그레이드 - 내부](https://nation.marketo.com/docs/DOC-2962){target="_blank"}

[알려진 잠재 고객으로 익명 잠재 고객 승격 - [!DNL Munchkin] V2 동작](https://nation.marketo.com/docs/DOC-2963){target="_blank"}

## 질문이 더 있습니다! 어떻게 해야 답을 얻을 수 있습니까? {#i-have-more-questions-how-do-i-get-them-answered}

[커뮤니티](https://nation.marketo.com/){target="_blank"}에 문의하세요. [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}에 문의할 수도 있습니다. 그들은 기꺼이 당신의 질문에 대답할 것입니다.
