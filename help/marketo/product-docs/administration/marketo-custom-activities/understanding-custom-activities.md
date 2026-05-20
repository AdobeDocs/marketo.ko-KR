---
unique-page-id: 10100266
description: 비즈니스별 개인 작업을 추적하기 위한 사용자 지정 활동 개요, 사용자 지정 개체와 차이점 및 활동 및 API 구현을 만드는 두 단계 설정입니다.
title: 사용자 정의 활동 이해
exl-id: 0bb74d9d-3a9d-4ef7-8c8c-2de36cd6190b
feature: Custom Activities
TQID: https://experienceleague.adobe.com/QwH82DomS1BDHbK3wfoP14N8xDBKZ28gOLyZ-L8fAeY
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 286
ht-degree: 3%

---

# 사용자 정의 활동 이해 {#understanding-custom-activities}

사용자 지정 활동으로 사용자가 비즈니스에 대해 수행한 작업을 추적합니다.

## 활동이란 무엇입니까? {#what-are-activities}

사용자가 조직과 상호 작용할 수 있는 방법에는 여러 가지가 있습니다. 회사 웹 사이트를 방문하거나, 무역 박람회에 참석하거나, 회사 웹 사이트로 전송된 이메일의 링크를 클릭할 수 있습니다. 이러한 작업은 활동이며, 수행하는 작업이 무엇이든 Marketo이 이를 캡처하므로 마케팅 팀이 적시에 적절한 메시지를 보내는 방법을 더 잘 이해할 수 있습니다.

## 사용자 지정 활동 {#custom-activities}

사용자 지정 활동은 Marketo 양식, 이메일 또는 랜딩 페이지와 관련이 없는 활동을 추적하는 데 도움이 됩니다. 누군가가 수표를 입금하는 시점을 추적하려면 사용자 지정 활동을 사용하십시오. 웨비나에 참석하는 사용자를 추적하려면 사용자 지정 활동을 사용하십시오.

>[!NOTE]
>
>사용자 지정 활동은 사용자 지정 개체와 다릅니다. 값이 변경될 수 있는 경우(즉, &quot;자동차 색상&quot;이 파란색에서 빨간색으로 변경됨) 사용자 지정 개체를 사용합니다. 발생한 순간을 추적하고 해당 세부 사항을 변경할 수 없는 경우(예: &quot;구매한 자동차&quot;) 사용자 지정 활동을 사용합니다.

## 필드 {#fields}

활동과 연결할 [추가 필드](/help/marketo/product-docs/administration/marketo-custom-activities/add-edit-delete-marketo-custom-activity-fields.md)를 추가할 수 있습니다. 기본 필드와 마찬가지로 스마트 목록에서 필터링 기준으로 사용할 수 있습니다.

## 시작하기 {#getting-started}

사용자 지정 활동은 표준 활동과 동일하게 작동합니다. 단, 두 단계로 설정하는 것이 좋습니다.

1단계: Marketo 계정에서 [사용자 지정 활동 만들기](/help/marketo/product-docs/administration/marketo-custom-activities/create-a-custom-activity.md)

2단계: Marketo API를 사용하는 조직의 직원은 구현을 시작할 수 있습니다. 자세한 내용은 [사용자 지정 활동 API](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Activities/operation/addCustomActivityUsingPOST)를 참조하세요.
