---
description: 개인 수준 이메일 추적 재정의를 통해 동의 및 개인 정보 보호 요구 사항을 지원하기 위해 각 사용자에 대한 이메일 열기 및 클릭 추적을 제어하는 방법을 알아봅니다.
title: 개인 수준에서 이메일 추적
feature: Email Setup
TQID: 'https://experienceleague.adobe.com/kF-5V-G6-xr3uV-NQBTmFNfhQnk-r-RYt-v0HvJ-4Go'
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
subfeature_v2:
  - id: a03c57fb-0705-4a0d-b463-bbc931d4cefa
    internal-label: Email setup
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
source-git-commit: a913c84b1c4f8927c951af685884edfc792ff213
workflow-type: tm+mt
source-wordcount: '1593'
ht-degree: 2%
---
# 개인 수준에서 이메일 추적 {#email-tracking-at-person-level}

개인 수준 이메일 추적 재정의를 사용하면 Marketo 환경 수준에서 기본값을 적용한 다음 개별 사용자에 대해 해당 기본값을 변경할 수 있습니다. 열기 추적 및 클릭 추적은 독립적으로 제어됩니다.

이메일 참여를 추적하기 전에 개인 정보 보호 요구 사항 또는 조직 정책에 동의가 필요한 경우 이 기능을 사용합니다.

>[!IMPORTANT]
>
>이 기능은 규정 준수 의무를 지원하는 데 도움이 되는 컨트롤을 제공합니다. 적용되는 법률 또는 동의를 제공해야 하는 사람은 결정하지 않습니다. 법률 및 개인 정보 보호 팀과 협력하여 추적을 구성하는 방법 및 동의를 수집하고 유지하는 방법을 결정합니다.

## 추적 결정 작동 방식 {#how-tracking-decisions-work}

세 가지 설정이 함께 작동합니다.

| 설정 | 레벨 | 기능 설명 |
|---|---|---|
| **개인 수준 전자 메일 추적 재정의** | 환경 | 피쳐를 켜거나 끕니다. 설정을 끄면 Marketo Engage은 환경 기본 및 사용자 무시 필드를 무시하고 일반 추적 동작을 사용합니다. |
| **기본적으로 전자 메일 추적 해제** | 환경 | 열기 및 클릭 추적에 대한 기본값을 설정합니다. 비활성화되면 기본적으로 추적이 켜져 있습니다. 활성화되면 추적이 기본적으로 해제됩니다. |
| **열린 추적 기본값 무시** 및 **클릭 추적 기본값 무시** | 개인 | 부울 사용자 필드. 값 `true`은(는) 해당 추적 유형에 대한 환경 기본값의 반대값을 적용합니다. `false` 값 또는 빈 값이 환경 기본값을 따릅니다. |

재정의 필드는 그 자체로 &quot;옵트인&quot; 또는 &quot;옵트아웃&quot;을 의미하지 않습니다. **`true`은(는) 항상 &quot;환경 기본값의 반대&quot;를 의미합니다.**

### 결정 테이블 추적 {#tracking-decision-table}

Marketo Engage은 이 결정을 이메일 열기 및 이메일 클릭에 별도로 적용합니다.

| 기능 | 환경 기본값 | 사용자 재정의는 `false`이거나 비어 있습니다. | 사용자 재정의는 `true`입니다. |
|---|---|---|---|
| 켜기 | 기본적으로 추적 | 추적됨 | 추적되지 않음 |
| 켜기 | 기본적으로 추적 해제 | 추적되지 않음 | 추적됨 |
| 끄기 | 적용할 수 없음 | 일반 추적, 재정의 및 기본값이 무시됨 | 일반 추적, 재정의 및 기본값이 무시됨 |

### 예 {#example}

기능이 켜져 있고 환경 기본값이 추적 설정이라고 가정해 봅시다. **공개 추적 기본값 무시**&#x200B;가 `true`(으)로 설정되어 있지만 **클릭 추적 기본값 무시**&#x200B;가 비어 있습니다. Marketo Engage은 해당 사용자의 이메일 열기를 추적하지 않지만 이메일 클릭수는 계속 추적합니다.

## 추적 모델 선택 {#choose-a-tracking-model}

기능을 활성화하거나 개인 필드를 채우기 전에 동의 및 개인 정보 요구 사항과 일치하는 모델을 선택하십시오.

| 모델 | 환경 기본값 | 다음과 같은 경우 재정의를 `true`(으)로 설정합니다. | 일반적인 사용 |
|---|---|---|---|
| 옵트아웃 | 기본적으로 추적 | 개인 사용자가 추적에 반대함 | 대부분의 사람을 추적하되 이의가 있는 사람에 대한 추적은 중단합니다. |
| 옵트인(동의) | 기본적으로 추적 해제 | 개인이 추적에 동의함 | 해당 CNIL 또는 Garante 지침이 적용되는 수신자를 포함하여 추적하기 전에 동의해야 합니다. |

>[!CAUTION]
>
>무시 필드를 채우기 전에 모델을 선택하고 그 후에는 환경 기본값을 변경하지 마십시오. `true`은(는) &quot;기본값의 반대&quot;를 의미하므로 기본값을 변경하면 기존의 모든 재정의 값의 효과를 반전시킵니다. 예를 들어, 기본적으로 추적에서 기본적으로 추적으로 전환하면 이전에 추적을 거부했던 사람들이 추적될 수 있습니다. 기본값을 변경해야 하는 경우 변경 사항이 적용되기 전에 영향을 받는 모든 사람의 대체 값을 갱신합니다.

## 기능 활성화 {#enable-the-feature}

개인 수준 전자 메일 추적 무시는 기본적으로 꺼져 있습니다. 활성화하려면 Adobe 고객 지원 센터에 문의하십시오. Marketo 환경에 대해 기능의 기본 상태를 **활성화됨** 또는 **비활성화됨**&#x200B;으로 지정할지 여부를 지정할 수도 있습니다.

>[!NOTE]
>
>이 요청을 제출하려면 Marketo 관리자여야 합니다.

>[!TIP]
>
>Adobe에 이 기능을 활성화하도록 요청하기 전에 기존 사용자에 대한 무시 필드를 채웁니다. 이렇게 하면 활성화 후에 준비된 첫 번째 이메일에서 의도한 추적 동작이 적용되는지 확인할 수 있습니다.

## 사람에 대한 재정의 값 설정 {#set-override-values-for-people}

재정의 필드는 부울 사용자 필드입니다. 워크플로우에 맞는 메서드를 사용하여 설정합니다.

| 메서드 | 참고 |
|---|---|
| [데이터 값 흐름 변경 단계](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value){target="_blank"} | 양식에 대한 동의 확인란을 제출하는 것과 같이 사용자가 기준을 만족할 때 필드를 설정하려면 스마트 캠페인을 사용하십시오. |
| 양식 | Marketo Engage 양식의 확인란 또는 숨겨진 필드를 개인 필드에 매핑합니다. |
| 목록 가져오기 | 필드를 가져오기 파일의 열로 포함합니다. |
| REST API | API 필드 이름 `overrideOpenTrackingDefault` 및 `overrideClickTrackingDefault`을(를) 사용합니다. |

개인의 동의에 따라 각 필드를 설정합니다. 동의 언어가 열림과 클릭을 별도로 처리하는 경우 각 필드를 독립적으로 구성하십시오.

## 이메일의 변경 사항 {#what-changes-in-the-email}

Marketo Engage이 개인을 추적하지 않으면 해당 개인에게 보내는 이메일 콘텐츠가 변경됩니다.

| 에 대한 추적 해제됨 | 변경 사항 | 아직 작동 중인 항목 |
|---|---|---|
| 열람 수 | 이메일에는 오픈 추적 픽셀이 포함되어 있지 않습니다. **메일 열기** 활동이 기록되지 않았습니다. | 다른 이메일 기능(클릭 추적 포함)은 계속 활성화되어 있을 경우 |
| 클릭수 | 링크는 Marketo Engage 추적 도메인을 통하지 않고 해당 대상으로 직접 이동합니다. 숨겨진 추적 링크는 추가되지 않습니다. **전자 메일 클릭** 활동이 기록되지 않았습니다. | 구독 취소 링크, 전자 메일 바닥글 옵트아웃 링크, `list-unsubscribe` 및 **웹 페이지로 보기** 링크가 계속 작동합니다. 이 링크를 사용하면 **메일 클릭** 활동이 기록되지 않습니다. |

## 영향을 받는 이메일 {#which-emails-are-affected}

| 이메일 유형 | 재정의가 적용됩니까? |
|---|---|
| 일괄 처리 Smart Campaign 또는 이메일 프로그램에서 보낸 이메일과 같은 일괄 처리 이메일 | 예 |
| Smart Campaign 트리거에서 전송된 이메일과 같은 이메일 트리거 | 예 |
| A/B 테스트 또는 챔피언/챌린저 변형이 있는 이메일 | 예. 추적은 수신하는 변형에 관계없이 각 사용자에 대해 별도로 결정됩니다. |
| 웹 페이지로 보기 | 예. 웹 버전은 개인의 현재 설정을 따릅니다. 변경 사항이 표시되는 데 최대 1시간이 걸릴 수 있습니다. |
| [운영 전자 메일](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational){target="_blank"} | 아니요. 일반적인 추적 동작을 따릅니다. |
| 샘플(테스트) 이메일 | 아니요. 일반적인 추적 동작을 따릅니다. |
| 이메일 미리 보기 | 거스름돈 없어 미리보기는 추적되지 않습니다. |
| 경고 이메일 | 거스름돈 없어 경고는 추적되지 않습니다. |
| SMS 메시지 | 아니요. 이 기능은 이메일에만 적용됩니다. |

## Marketo Engage에서 추적 결정을 내릴 때 {#when-marketo-engage-makes-the-tracking-decision}

Marketo Engage은 전송할 이메일을 준비할 때 개인의 재정의 값을 읽습니다.

- **예약된 배달 또는 지연된 배달:** 전자 메일이 지금 준비되고 나중에 배달되는 경우(예: [Head Start](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs){target="_blank"} 또는 [Recipient Time Zone](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone){target="_blank"}) 준비 시 값이 적용됩니다. 준비 후 변경한 사항은 해당 이메일을 변경하지 않습니다.
- **이미 배달된 전자 메일:** 개인의 재정의를 변경해도 이미 받은 전자 메일은 변경되지 않습니다. 이전에 보낸 이메일의 링크 클릭은 해당 링크가 추적을 활성화한 상태로 준비된 경우에도 계속 추적할 수 있습니다.
- **향후 이메일:** 변경 사항은 변경 후 Marketo Engage이 준비하는 이메일에 적용됩니다.

동의를 철회하는 경우 가능한 한 빨리 재정의 값을 업데이트하여 변경 사항이 동의자를 위해 준비된 다음 이메일에 적용됩니다.

## 보고, 스마트 목록 및 점수에 미치는 영향 {#impact-on-reporting-smart-lists-and-scoring}

Marketo Engage에서 사용자를 추적하지 않는 경우 **이메일 열기** 또는 **이메일 클릭** 활동을 기록하지 않습니다. 그 결과는 다음과 같습니다.

- **스마트 목록/캠페인:** **열린 전자 메일** 및 **전자 메일의 링크 클릭**&#x200B;과 같은 필터 및 트리거가 해당 활동이 추적되지 않을 때 해당 사용자에 대해 일치하지 않거나 실행되지 않습니다.
- **보고서 및 대시보드:** 전자 메일 열람률, 클릭률 및 링크 성능은 추적된 사람만 반영합니다. 더 많은 사람들이 추적되지 않으므로 참여 지표가 감소할 수 있습니다.
- **채점 및 프로그램 성공:** 열기 또는 클릭에 따른 규칙 및 프로그램 성공 단계는 활동이 추적되지 않는 사용자에게는 적용되지 않습니다. 이러한 규칙을 검토하여 사람들이 부당하게 점수를 받거나 승진하지 않도록 하십시오.
- **웹 활동 연결:** 클릭 추적이 해제되어 있으면 전자 메일 링크에 Marketo Engage 추적 토큰이 전달되지 않습니다. 해당 사용자가 Munchkin에 아직 알려지지 않은 경우 해당 이메일의 웹 사이트 방문이 링크를 통해 해당 사용자와 연결되어 있지 않습니다.

>[!NOTE]
>
>전송, 게재, 반송 및 구독 취소 활동은 영향을 받지 않습니다.

## 다른 추적 설정과 함께 작동하는 방법 {#how-this-works-with-other-tracking-settings}

개인 수준 전자 메일 추적 무시는 사용자에 대한 추적을 끌 수 있습니다. 다른 설정이 이미 추적을 비활성화한 경우에는 추적을 켜지 않습니다. 예를 들어, `mktNoTrack` 클래스로 표시된 링크는 개인의 설정이 클릭 추적을 허용하더라도 추적되지 않습니다.

## 기능 비활성화 {#disable-the-feature}

개인 수준 이메일 추적 재정의를 비활성화하려면 Adobe 고객 지원 센터에 문의하십시오.

>[!NOTE]
>
>이 요청을 제출하려면 Marketo 관리자여야 합니다.

비활성화하면 변경 후 준비된 이메일이 정상 추적 동작으로 돌아갑니다. 재정의 값은 개인 레코드에 남아 있지만 무시됩니다. 나중에 이 기능이 다시 활성화되면 저장된 값이 다시 적용됩니다.

## 자주 묻는 질문 {#frequently-asked-questions}

### 사용자에 대한 열림은 추적하지만 클릭은 추적할 수 있습니까? 아니면 그 반대로 추적할 수 있습니까? {#can-i-track-opens-but-not-clicks-for-a-person-or-the-reverse}

예. 열기 및 클릭 추적은 독립적으로 결정됩니다. 변경할 추적 유형에 대해 무시 필드만 설정합니다.

### 이 기능을 사용하면 사람에게 이메일을 보낼 수 없습니까? {#does-this-feature-stop-me-from-sending-emails-to-a-person}

아니요. 추적만 제어합니다. 개인에게 마케팅 이메일 전송을 중단하려면 기존 구독 취소 및 동의 기능을 사용하십시오.

### 추적되지 않는 사람도 여전히 작동 중인 구독 취소 링크를 볼 수 있습니까? {#do-people-who-are-not-tracked-still-see-working-unsubscribe-links}

예. 구독 취소 링크 및 **웹 페이지로 보기** 링크가 모든 사용자에 대해 계속 작동합니다.

### 을 옵트아웃한 사람에게 왜 여전히 이메일 클릭 활동이 있습니까? {#why-does-a-person-who-opted-out-still-have-a-click-email-activity}

재정의 값이 변경되기 전에 준비된 이메일의 링크를 클릭했을 수 있습니다. 변경 사항은 변경 후에 준비된 이메일에 적용됩니다.

### 이메일 템플릿을 변경해야 합니까? {#do-i-need-to-change-my-email-templates}

아니요. Marketo Engage은 각 이메일을 작성할 때 추적 결정을 적용합니다. 템플릿 또는 이메일을 변경할 필요가 없습니다.
