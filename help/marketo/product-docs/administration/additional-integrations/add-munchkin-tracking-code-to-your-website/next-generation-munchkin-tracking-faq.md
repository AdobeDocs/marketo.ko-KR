---
unique-page-id: 10096583
description: 차세대 Munchkin 추적 FAQ - Marketo 문서 - 제품 설명서
title: 차세대 Munchkin 추적 FAQ
exl-id: 283189ac-c817-479a-b896-91233980608c
source-git-commit: 813bab6169a121e90919f9a02505ccde5167cda4
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 차세대 Munchkin 추적 FAQ {#next-generation-munchkin-tracking-faq}

우리는 곧 차세대 웹 추적 기술에 대한 단계적 출시를 시작할 것이라고 발표하게 되어 기쁘게 생각합니다.

다음은 알아야 할 가장 중요한 사항입니다.

* 1분기 릴리스(이미 수행됨)를 통해 &quot;익명&quot; 스마트 목록 필터를 제거합니다
* 수집할 수 있는 웹 이벤트(웹 페이지 방문, 웹 페이지에서 클릭한 링크)의 수를 늘리고 있습니다
* Munchkin 코드가 변경되지 않으므로 웹 사이트에 대한 업데이트가 필요하지 않습니다

## Marketo 구독은 언제 Munchkin V2에 게시됩니까? {#when-will-my-marketo-subscription-be-on-munchkin-v}

아직 정확한 날짜가 없습니다. 여기에서 업데이트를 확인하십시오.

## 웹 사이트에서 Munchkin 추적을 변경해야 합니까? {#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

아니요. Munchkin 추적 코드는 동일하게 유지됩니다. 웹 사이트를 변경할 필요가 없습니다.

>[!NOTE]
>
>이 변경 사항은 웹 개인화(실시간 개인화)에 영향을 주지 않습니다. 익명 및 알려진 웹 방문자를 계속 식별하고 이러한 방문자에게 실시간으로 컨텐츠를 개인화합니다.

## Marketo이 스마트 목록에서 &quot;익명&quot; 필터를 제거한 이유는 무엇입니까? {#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

익명 사람들이 스마트 캠페인과 상호 작용하는 방식을 변경했습니다. 이전엔, 그들은 알려진 사람들과 마찬가지로 똑똑한 캠페인을 통해 흘러갔습니다. 익명 처리됨 필터는 알려진 사용자 또는 익명 사용자만 캠페인을 통해 이동하도록 지정하는 데 사용됩니다.

Munchkin V2를 통해 우리는 모든 익명의 활동을 계속 추적할 것입니다. 하지만 더 이상 익명 사용자에게 필터를 적용할 수 없습니다. 전환 시점(Marketo에 사람이 알려질 때)에 익명의 사용자가 되었을 때 발생한 모든 활동이 개인 활동 로그에 추가되며, 이때 해당 활동은 자격이 있는 캠페인을 통해 전달됩니다.

스마트 목록에서 이미 이 필터를 사용 중인 경우(예: 스마트 캠페인이나 보고서에서) 스마트 목록에서 자동으로 제거되지 않습니다. 자세한 내용은 아래를 참조하십시오.

>[!NOTE]
>
>**트리거**: 방문 횟수 웹 페이지, 웹 페이지는 가격 책정 페이지임\
>**흐름**: 점수 +10 및 관심 모멘트 변경
>**웹**: 조회 가격 페이지
>
>Munchkin V2를 사용하면, 익명의 사람이 가격 페이지를 방문한다면, 그녀는 즉시 그 캠페인에 들어가지 않습니다. 익명의 사람이 알려지면 이 캠페인을 진행할 겁니다 그녀는 다음과 같이 할 것입니다.
>
>* 10점 받기
>
>* 웹 페이지 활동을 올바른 날짜(실제로 방문한 날짜)로 설정하도록 합니다
>
>* 그녀에게 흥미로운 순간을 기록하세요(그녀가 알게 된 시점이 아니라 실제로 페이지를 방문한 날짜 포함)
>
>* 현재 상태로 &quot;새 사람&quot; 활동이 기록되어 있습니다


## 이미 &quot;익명&quot;인 필터가 있는 내 스마트 목록은 어떻게 됩니까? {#what-happens-to-my-smart-lists-that-already-have-the-is-anonymous-filter}

16년 겨울 릴리스 이후 &quot;익명&quot;이라는 필터가 있는 스마트 목록이 있는 이전 스마트 캠페인이 있는 경우 두 가지 중 하나가 발생합니다.

1. 스마트 목록에 &quot;Is Anonymous = False&quot; 필터가 있으면 아무 일도 발생하지 않습니다. 그냥 무시하면 돼
1. 스마트 목록에 &quot;Is Anonymous = True&quot; 필터가 있는 경우, 이 캠페인이 실패하고 알림이 전송됩니다.

## Marketo을 잠시 이용했어요 내 캠페인 중 &quot;익명&quot;인 필터를 사용하는 캠페인을 어떻게 알 수 있습니까? {#ive-been-using-marketo-for-a-while-how-do-i-know-which-of-my-campaigns-use-the-is-anonymous-filter}

이 변경 사항을 수행하기 전에 &quot;익명&quot;인 필터를 사용하는 스마트 목록, 스마트 캠페인 및 보고서 목록과 함께 몇 개의 주별 알림을 알림 받은 편지함으로 전송했습니다. 이 URL은 현재 이 필터를 사용하고 있는 위치를 식별하는 데 도움이 될 수 있습니다.

영향을 받는 캠페인이므로 이러한 캠페인을 검토하고 &quot;익명&quot;이 True로 설정된 위치를 확인하십시오. 대부분의 경우 고객은 이 설정을 사용하여 점수를 매깁니다. 이제 이러한 캠페인이 어떻게 작동하는지 알려면 위의 예를 참조하십시오.

## 더 자세한 설명서가 필요합니다. 어디에서 찾을 수 있나요? {#id-like-more-detailed-documentation-where-can-i-find-it}

다음 링크를 확인하십시오.

[익명 리드 업그레이드 개요](https://nation.marketo.com/docs/DOC-2937){target=&quot;_blank&quot;}

[익명 리드 업그레이드 - Marketo UI 내의 변경 사항](https://nation.marketo.com/docs/DOC-2938){target=&quot;_blank&quot;}

[익명 리드 업그레이드 - 고객 조치 필요](https://nation.marketo.com/docs/DOC-2939){target=&quot;_blank&quot;}

[익명 리드 업그레이드 - Analytics 보고서](https://nation.marketo.com/docs/DOC-2940){target=&quot;_blank&quot;}

[익명 리드 업그레이드 - 릴리스 일정](https://nation.marketo.com/docs/DOC-2961){target=&quot;_blank&quot;}

[익명 리드 업그레이드 - 후드](https://nation.marketo.com/docs/DOC-2962){target=&quot;_blank&quot;}

[알려진 리드에 대한 익명의 리드 홍보 - Munchkin V2 동작](https://nation.marketo.com/docs/DOC-2963){target=&quot;_blank&quot;}

## 질문이 더 있어! 어떻게 답변을 받게 되죠? {#i-have-more-questions-how-do-i-get-them-answered}

다음 주소로 문의하십시오. [커뮤니티](https://nation.marketo.com/){target=&quot;_blank&quot;}. 연락처가 가능합니다 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support){target=&quot;_blank&quot;}. 그들은 당신의 질문에 기꺼이 대답할 것입니다.
