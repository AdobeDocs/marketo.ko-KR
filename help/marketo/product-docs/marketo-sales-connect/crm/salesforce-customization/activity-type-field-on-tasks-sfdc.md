---
unique-page-id: 14352476
description: 작업(SFDC)의 활동 유형 필드 - Marketo 문서 - 제품 설명서
title: 작업(SFDC)의 활동 유형 필드
exl-id: b291e641-d3af-4667-a01c-cd491cd87add
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---

# 작업(SFDC)의 활동 유형 필드 {#activity-type-field-on-tasks-sfdc}

Sales Connect의 도움으로 Salesforce에서 활동으로 로그인한 이메일 및 호출을 사용할 수 있습니다. Salesforce에서 중요한 데이터를 보유하기 위한 주요 부분은 유형 필드가 올바른 값을 채워야 한다는 것입니다.

>[!NOTE]
>
>BCC를 통해 전자 메일을 로깅하면 작업 유형 선택 목록이 표시되지 않으며, 대신 BCC 주소를 통해 Salesforce에 전달되므로 유형 필드를 &quot;전자 메일&quot;로 자동으로 채웁니다.

## 요구 사항 {#requirements}

* Salesforce와의 연결
* 작업 유형 선택 목록에서 선택된 기본 유형 값이 없습니다.
* Task Type Picklist(대문자 사항) 아래에 Call, Reply 및 Email이 모두 있어야 합니다.
* 유형 필드의 값에 대해 작업을 수행하는 워크플로우 또는 트리거가 없습니다

## 설정 {#setup}

먼저 올바른 선택 목록 값이 있는지 확인합니다. 선택 목록을 변경하려면 Salesforce 관리자의 도움이 필요합니다.

1. 다음으로 이동 [Salesforce.com](https://salesforce.com) 오른쪽 상단 모서리에서 설정 을 클릭합니다.
1. 사용자 지정을 클릭합니다.
1. 활동을 클릭합니다.
1. 작업 필드를 클릭합니다.
1. 유형을 클릭합니다.
1. 이제 작업 유형 선택 목록에 있습니다. &#39;기본값&#39;을 선택하지 않았는지 확인합니다.
1. 이메일, 호출 및 응답에 대한 유형 값이 나열되는지 확인합니다.

이제 로그인된 이메일, 호출 및 답글에 해당하는 값을 채우는 유형 필드를 확인할 수 있습니다. 이러한 값은 **not** Sales Connect 미리 알림 작업에 대한 정보를 제공합니다.

>[!NOTE]
>
>&#39;회신&#39;이 값으로 표시되지 않으면 을(를) 클릭하여 추가합니다 **새로 만들기**. &#39;Reply&#39;는 Salesforce에서 표준 값이 아닙니다.
