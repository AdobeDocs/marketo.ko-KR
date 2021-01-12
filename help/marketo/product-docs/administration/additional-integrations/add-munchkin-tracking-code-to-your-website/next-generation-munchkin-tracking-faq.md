---
unique-page-id: 10096583
description: 차세대 Munchkin 추적 FAQ - 마케팅 문서 - 제품 설명서
title: 차세대 Munchkin 추적 FAQ
translation-type: tm+mt
source-git-commit: 78961a3e163ce903facf955a9dda6909b5e85bad
workflow-type: tm+mt
source-wordcount: '733'
ht-degree: 0%

---


# 차세대 Munchkin 추적 FAQ {#next-generation-munchkin-tracking-faq}

우리는 곧 차세대 웹 추적 기술에 대한 단계적인 출시를 시작할 것이라고 발표하게 되어 기쁘게 생각합니다.

다음은 가장 중요한 사항입니다.

* Q1 릴리스와 함께 &quot;익명&quot; 스마트 목록 필터가 제거되었습니다(이미 완료).
* 인제스트할 수 있는 웹 이벤트(웹 페이지 방문, 웹 페이지의 클릭한 링크) 수 증가
* Munchkin 코드는 변경되지 않으므로 웹 사이트에 대한 업데이트는 필요하지 않습니다

## 마케팅 구독은 언제 Munchkin V2에서 시작됩니까?{#when-will-my-marketo-subscription-be-on-munchkin-v}

아직 정확한 날짜가 없습니다. 업데이트된 내용을 보려면 여기에서 확인하십시오.

## 웹 사이트에서 Munchkin 추적을 변경해야 합니까?{#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

아니. Munchkin 추적 코드는 동일하게 유지됩니다. 웹 사이트를 변경할 필요가 없습니다.

>[!NOTE]
>
>이 변경 사항은 웹 개인화(실시간 개인화)에 영향을 주지 않습니다. 익명의 웹 방문자를 식별하고 방문자에게 실시간으로 컨텐츠를 개인화합니다.

## Marketing에서 스마트 목록에서 &quot;익명&quot; 필터를 제거한 이유는 무엇입니까?{#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

익명의 사람들이 스마트 캠페인과 상호 작용하는 방식을 변경했습니다. 이전에는, 그들은 알려진 사람들처럼 똑똑한 캠페인을 통해 흘러갔습니다. &quot;익명&quot; 필터는 알려진 사람 또는 익명 사람만 캠페인을 통과하도록 지정하는 데 사용되었습니다.

Munchkin V2를 통해 우리는 모든 익명의 활동을 계속 추적할 것입니다.하지만 익명 사용자에게 필터를 더 이상 적용할 수 없습니다. 전환 시점(인물이 Marketing To에 알려지게 될 때)에, 인물을 익명으로 했을 때 발생한 모든 활동이 개인 활동 로그에 추가되며 이 경우 방문자가 자격이 부여된 캠페인을 통해 전달됩니다.

스마트 목록(예: 스마트 캠페인 또는 보고서)에서 이 필터를 이미 사용하고 있는 경우 스마트 목록에서 자동으로 제거되지 않습니다. 자세한 내용은 아래를 참조하십시오.

>[!NOTE]
>
>**트리거**:웹 페이지 방문 횟수, 웹 페이지가 가격 페이지임\
>**흐름**:점수 +10 및 관심 모멘트 변경
>**웹**:본 가격 페이지
>
>Munchkin V2를 사용하면 익명의 사용자가 가격 페이지를 방문하면 캠페인에 즉시 진입하지 않습니다. 익명의 사람이 알려지면 이 캠페인을 전개할 겁니다 She will:
>
>* 10점 받기
   >
   >
* 웹 페이지 활동이 올바른 날짜(실제로 방문한 시기)로 설정되도록 합니다.
   >
   >
* 그녀에게 흥미로운 순간을 기록하도록 하세요(그녀가 알게 된 시점이 아니라 실제로 페이지를 방문한 날짜와 함께)
   >
   >
* 현재 &quot;새 사람&quot; 활동이 기록되어 있음


## &quot;익명&quot; 필터가 이미 있는 내 스마트 목록은 어떻게 됩니까?{#what-happens-to-my-smart-lists-that-already-have-the-is-anonymous-filter}

16년 겨울 릴리스 이후 &quot;익명&quot; 필터가 있는 스마트 목록이 있는 이전 스마트 캠페인이 있는 경우 다음 두 가지 중 하나가 발생합니다.

1. 스마트 목록에 &quot;Is Anonymous = False&quot; 필터가 있으면 아무 작업도 수행되지 않습니다. 그냥 무시하면 돼
1. 스마트 목록에 &quot;Is Anonymous = True&quot; 필터가 있으면 이 캠페인이 실패하고 알림이 전송됩니다.

## Marketing To를 오랫동안 사용하고 있습니다. &quot;익명&quot; 필터를 사용하는 내 캠페인 중 어떤 캠페인을 사용하는지 어떻게 알 수 있습니까?{#ive-been-using-marketo-for-a-while-how-do-i-know-which-of-my-campaigns-use-the-is-anonymous-filter}

이 변경 전에 &quot;익명&quot; 필터를 사용하는 스마트 목록, 스마트 캠페인 및 보고서 목록이 포함된 여러 주별 알림을 알림 받은 편지함에 전송했습니다. 이 필터를 사용하면 현재 이 필터를 사용하고 있는 위치를 식별할 수 있습니다.

영향을 받는 캠페인이므로 이러한 캠페인을 검토하고 &quot;익명 여부&quot;가 True로 설정된 위치를 확인하십시오. 대부분의 경우 고객은 이 설정을 일종의 점수를 매깁니다. 위의 예를 참조하여 이러한 캠페인의 작동 방식을 확인하십시오.

## 더 자세한 설명서가 필요합니다. 어디서 찾을 수 있나요?{#id-like-more-detailed-documentation-where-can-i-find-it}

다음 링크를 확인합니다.

[익명 리드 업그레이드 개요](https://nation.marketo.com/docs/DOC-2937)

[익명의 리드 업그레이드 - Marketing UI 내의 변경 사항](https://nation.marketo.com/docs/DOC-2938)

[익명 리드 업그레이드 - 고객 조치 필요](https://nation.marketo.com/docs/DOC-2939)

[익명 리드 업그레이드 - 분석 보고서](https://nation.marketo.com/docs/DOC-2940)

[익명 리드 업그레이드 - 릴리스 일정](https://nation.marketo.com/docs/DOC-2961)

[익명의 리드 업그레이드 - 최신 정보](https://nation.marketo.com/docs/DOC-2962)

[알려진 리드로 익명의 리드 홍보 - Munchkin V2 동작](https://nation.marketo.com/docs/DOC-2963)

## 궁금한 게 더 있어! 답변을 얻으려면 어떻게 해야 합니까?{#i-have-more-questions-how-do-i-get-them-answered}

[커뮤니티](https://nation.marketo.com/welcome)에서 연락하십시오. [마케팅 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의할 수도 있습니다. 그들은 당신의 질문에 기꺼이 답변할 것입니다.
