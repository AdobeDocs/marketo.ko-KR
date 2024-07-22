---
unique-page-id: 14352476
description: 작업(SFDC)의 활동 유형 필드 - Marketo 문서 - 제품 설명서
title: 작업(SFDC)의 활동 유형 필드
exl-id: b291e641-d3af-4667-a01c-cd491cd87add
feature: Marketo Sales Connect
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 0%

---

# 작업(SFDC)의 활동 유형 필드 {#activity-type-field-on-tasks-sfdc}

Sales Connect를 통해 이메일 및 호출을 Salesforce의 활동으로 기록할 수 있습니다. Salesforce에 중요한 데이터를 포함하려면 유형 필드에 올바른 값이 채워져야 합니다.

>[!NOTE]
>
>BCC를 통해 전자 메일을 로깅하면 작업 유형 선택 목록이 표시되지 않고, BCC 주소를 통해 Salesforce로 전달되므로 대신 유형 필드를 &quot;전자 메일&quot;로 자동으로 채웁니다.

## 요구 사항 {#requirements}

* Salesforce와의 연결
* 작업 유형 선택 목록에서 선택한 기본 유형 값 없음
* 호출, 회신 및 이메일은 모두 작업 유형 선택 목록에 있어야 합니다(대소문자 구분 안 함).
* 유형 필드의 값에 대해 작업을 수행하는 워크플로우 또는 트리거 없음

## 설정 {#setup}

먼저 올바른 선택 목록 값이 있는지 확인합니다. 선택 목록을 변경하려면 Salesforce 관리자의 도움이 필요합니다.

1. [Salesforce.com](https://salesforce.com)(으)로 이동한 다음 오른쪽 상단의 [설정]을 클릭합니다.
1. 사용자 정의를 클릭합니다.
1. 활동을 클릭합니다.
1. 작업 필드를 클릭합니다.
1. 유형 을 클릭합니다.
1. 이제 작업 유형 선택 목록에 있습니다. &#39;기본값&#39;이 선택되어 있지 않은지 확인하십시오.
1. 이메일, 호출 및 회신에 대해 유형 값이 나열되어 있는지 확인합니다.

이제 이 기능이 제대로 작동했으므로 유형 필드가 기록된 이메일, 호출 및 답글에 대한 해당 값을 채우는 것을 볼 수 있습니다. 이 값은 Sales Connect 미리 알림 작업에 _not_&#x200B;이(가) 채워집니다.

>[!NOTE]
>
>&#39;회신&#39;이 값으로 표시되지 않으면 **새로 만들기**&#x200B;를 클릭하여 추가하십시오. &#39;Reply&#39;는 Salesforce의 표준 값이 아닙니다.
