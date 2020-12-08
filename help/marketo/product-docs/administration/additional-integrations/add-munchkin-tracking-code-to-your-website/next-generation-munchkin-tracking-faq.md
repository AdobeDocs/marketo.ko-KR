---
unique-page-id: 10096583
description: 차세대 Munchkin 추적 FAQ - Marketing Docs - 제품 설명서
title: 차세대 Munchkin 추적 FAQ
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '794'
ht-degree: 0%

---


# 차세대 Munchkin 추적 FAQ {#next-generation-munchkin-tracking-faq}

차세대 웹 추적 기술에 대한 단계별 출시를 곧 시작할 예정입니다.

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

다음은 가장 중요한 사항입니다.

* Q1 릴리스에서 &quot;익명&quot; 스마트 목록 필터를 제거할 예정입니다(이미 수행됨).
* 인제스트할 수 있는 웹 이벤트(웹 페이지 방문, 웹 페이지에서 클릭한 링크) 수 증가
* Munchkin 코드는 변경되지 않으므로 웹 사이트에 대한 업데이트는 필요하지 않습니다

## Marketing의 구독은 언제 Munchkin V2에서 시작됩니까? {#when-will-my-marketo-subscription-be-on-munchkin-v}

아직 정확한 날짜가 정해지지 않았지만 업데이트된 내용을 다시 확인하시기 바랍니다.

## 웹 사이트에서 Munchkin 추적을 변경해야 합니까? {#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

아뇨 Munchkin 추적 코드는 동일하게 유지됩니다. 웹 사이트를 변경할 필요가 없습니다.

>[!NOTE]
>
>이 변경 사항은 웹 개인화(실시간 개인화)에 영향을 주지 않습니다. 익명의 웹 방문자를 식별하고 이러한 방문자에게 실시간으로 컨텐츠를 개인화합니다.

## Marketing에서 스마트 목록에서 &quot;익명&quot; 필터를 제거한 이유는 무엇입니까? {#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

익명 사용자가 스마트 캠페인과 상호 작용하는 방식을 변경했습니다. 이전엔, 그들은 알려진 사람들과 마찬가지로 똑똑한 캠페인을 통해 흘러갔습니다. &quot;익명 여부&quot; 필터는 알려진 사람 또는 익명 사람만 캠페인을 통과하도록 지정하는 데 사용되었습니다.

Munchkin V2를 통해 우리는 모든 익명의 활동을 계속해서 추적할 것입니다.하지만 더 이상 익명 사용자에게 필터를 적용할 수 없습니다. 전환 시점(사용자가 Marketing To에 알려지면), 개인이 익명으로 되었을 때 발생한 모든 활동이 개인 활동 로그에 추가되며 이 시점에 방문자가 자격이 되는 캠페인을 통해 전송됩니다.

스마트 목록(예: 스마트 캠페인 또는 보고서)에서 이 필터를 이미 사용하고 있는 경우 스마트 목록에서 자동으로 제거되지 않습니다. 자세한 내용은 아래를 참조하십시오.

>[!NOTE]
>
>**예**
>
>**트리거**:웹 페이지 방문 횟수, 웹 페이지는 가격 페이지\
>**흐름**:점수 +10 및 관심 모멘트, **웹**:본 가격 페이지
>
>Munchkin V2를 사용하면 익명의 사용자가 가격 페이지를 방문하는 경우 캠페인에 즉시 진입하지 않습니다. 그 익명의 사람이 알려지면, 우리는 이 캠페인을 그녀에게 전개할 것이다. She will:
>
>* 10점 받기
   >
   >
* 웹 페이지 활동이 올바른 날짜(실제 방문 시)로 설정되어 있는지 여부
   >
   >
* Have an Interest Moment logged for her (with the date that she really visited the page, not when she knit.
   >
   >
* 현재 &quot;새 사람&quot; 활동이 기록되어 있음

>



## &quot;익명&quot; 필터가 이미 있는 내 스마트 목록은 어떻게 됩니까? {#what-happens-to-my-smart-lists-that-already-have-the-is-anonymous-filter}

2016년 겨울 릴리스 이후 &quot;익명 여부&quot; 필터가 있는 스마트 목록이 있는 이전 스마트 캠페인을 보유하고 있는 경우 다음 두 가지 중 하나가 발생합니다.

1. 스마트 목록에 &quot;Is Anonymous = False&quot; 필터가 있으면 아무 일도 발생하지 않습니다. 그냥 무시하겠습니다.
1. 스마트 목록에 &quot;Is Anonymous = True&quot; 필터가 있으면 이 캠페인이 실패하고 알림이 전송됩니다.

## Marketing To를 오랫동안 사용하고 있습니다. 내 캠페인 중 &quot;익명 여부&quot; 필터를 사용하는 캠페인을 어떻게 알 수 있습니까? {#ive-been-using-marketo-for-a-while-how-do-i-know-which-of-my-campaigns-use-the-is-anonymous-filter}

이 변경 전에, &quot;익명&quot; 필터를 사용하는 스마트 목록, 스마트 캠페인 및 보고서 목록이 포함된 여러 주간 알림을 알림 받은 편지함에 보냈습니다. 이 필터를 사용하면 현재 이 필터를 사용하고 있는 위치를 식별하는 데 도움이 됩니다.

영향을 받는 캠페인이므로 이러한 캠페인을 검토하고 &quot;익명 여부&quot;가 True로 설정된 위치를 확인하십시오. 대부분의 경우 고객은 이 설정을 일종의 점수 매기에 사용합니다. 이러한 캠페인의 작동 방식을 이해하려면 위의 예를 참조하십시오.

## 더 상세한 설명서가 필요합니다 어디서 찾을 수 있나요? {#id-like-more-detailed-documentation-where-can-i-find-it}

다음 링크를 확인하십시오.

[익명 리드 업그레이드 개요](https://nation.marketo.com/docs/DOC-2937)

[익명 리드 업그레이드 - Marketing To UI 내부의 변경](https://nation.marketo.com/docs/DOC-2938)

[익명 리드 업그레이드 - 고객 조치 필요](https://nation.marketo.com/docs/DOC-2939)

[익명 리드 업그레이드 - 분석 보고서](https://nation.marketo.com/docs/DOC-2940)

[익명 리드 업그레이드 - 릴리스 일정](https://nation.marketo.com/docs/DOC-2961)

[익명의 리드 업그레이드 - 인기](https://nation.marketo.com/docs/DOC-2962)

[알려진 리드로 익명의 리드 홍보 - Munchkin V2 동작](https://nation.marketo.com/docs/DOC-2963)

## 궁금한 게 더 있어요 어떻게 답변을 얻을 수 있습니까? {#i-have-more-questions-how-do-i-get-them-answered}

커뮤니티에 [연락하세요](https://nation.marketo.com/welcome). 또한 이메일을 보내 질문에 답변해 [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#4c3f393c3c233e380c212d3e27293823622f232162) 드릴 수 있습니다.
