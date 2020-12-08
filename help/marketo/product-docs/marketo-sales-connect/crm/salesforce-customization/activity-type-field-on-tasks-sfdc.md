---
unique-page-id: 14352476
description: 작업의 활동 유형 필드(SFDC) - 마케팅 문서 - 제품 설명서
title: 작업의 활동 유형 필드(SFDC)
translation-type: tm+mt
source-git-commit: c33b7ab59e612f37d3f64bb954579700dc574068
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 0%

---


# 작업의 활동 유형 필드(SFDC) {#activity-type-field-on-tasks-sfdc}

Sales Connect의 도움으로 Salesforce의 활동으로 이메일 및 호출을 기록할 수 있습니다. Salesforce에서 중요한 데이터를 확보하려면 유형 필드가 올바른 값을 채우도록 해야 합니다.

>[!NOTE]
>
>BCC를 통해 이메일을 로깅하면 작업 유형 선택 목록이 보이지 않으며, 대신 BCC 주소를 통해 Salesforce로 배달되므로 문자 필드가 &quot;이메일&quot;으로 자동 채워집니다.

## 요구 사항 {#requirements}

* Salesforce와의 연결
* 작업 유형 선택 목록에서 선택된 기본값 없음
* 작업 유형 선택 목록(대/소문자 구분)에는 모두 전화, 답글 및 이메일이 있어야 합니다.
* 유형 필드 값 `Workflows` 에 대해 조치를 취하지 `Triggers` 않거나 취하지 않습니다.

## 설정 {#setup}

먼저 올바른 선택 목록 값이 있는지 확인하십시오. 선택 목록을 변경하려면 Salesforce 관리자의 도움이 필요합니다.

1. Salesforce.com [으로](http://Salesforce.com) 이동하고 오른쪽 상단에 있는 설정을 클릭합니다.
1. 사용자 지정을 클릭합니다.
1. 활동을 클릭합니다.
1. 작업 필드를 클릭합니다.
1. 유형을 클릭합니다.
1. 이제 작업 유형 선택 목록에 있습니다. &#39;기본값&#39;이 선택되지 않았는지 확인하십시오.
1. [이메일], [전화 걸기] 및 [회신]에 대해 [유형] 값이 나열되어 있는지 확인합니다.

이제 로그인한 이메일, 호출 및 답글에 해당하는 값이 입력되어 있는 유형 필드를 보게 됩니다. 이러한 값은 Sales Connect 미리 알림 작업에 **채워지지** 않습니다.

>[!NOTE]
>
>&#39;응답&#39;이 값으로 표시되지 않으면 [새로 만들기]를 클릭하여 **추가합니다**. &#39;회신&#39;은 Salesforce의 표준 값이 아닙니다.
