---
description: Salesforce - Marketo 문서 - 제품 설명서에 활동을 기록할 때 활동 유형 필드 업데이트
title: Salesforce에 활동을 기록할 때 활동 유형 필드 업데이트
exl-id: 800323cb-2b99-42f1-ae30-0f87a9a1b4be
source-git-commit: c16081143588ebc0793f5b6e2630b58348e27124
workflow-type: tm+mt
source-wordcount: '420'
ht-degree: 1%

---

# Salesforce에 활동을 기록할 때 활동 유형 필드 업데이트 {#update-activity-type-field-when-logging-activities-to-salesforce}

작업은 보고에 사용하도록 이메일 및 호출 활동을 Salesforce에 자동으로 동기화하여 활동 내역에 대한 가시성을 높일 수 있습니다. 활동을 기록할 때 활동 유형 필드가 기록되는 활동 유형에 따라 이메일, 호출 또는 회신으로 제대로 업데이트되었는지 확인하십시오.

>[!NOTE]
>
>BCC를 통해 이메일을 로깅하면 작업 유형 선택 목록이 표시되지 않고, BCC 주소를 통해 Salesforce로 전달되므로 대신 유형 필드를 &quot;이메일&quot;로 자동으로 채웁니다.

## 알아야 할 사항 {#things-to-know}

* 작업 유형을 업데이트하려면 Salesforce와의 연결이 필요합니다.
* 작업 유형 선택 목록에 기본 유형 값이 선택되어 있지 않아야 합니다.
* 호출, 회신 및 이메일은 모두 작업 유형 선택 목록에 있어야 합니다(대소문자 구분 안 함).
* 작업 유형 필드를 업데이트하는 Salesforce의 워크플로우 또는 트리거가 이 프로세스를 방해할 수 있습니다.

## 설정 {#setup}

먼저 올바른 선택 목록 값이 있는지 확인합니다. 선택 목록을 변경하려면 Salesforce 관리자의 도움이 필요합니다.

먼저 작업 유형 선택 목록(이메일, 호출 및 회신 제외)에서 누락된 값을 확인합니다. 이를 검토하고 활동 유형 선택 목록을 변경하려면 Salesforce 관리자의 도움이 필요할 수 있습니다. 이러한 변경 작업을 수행하기 위해 Salesforce 관리자는 아래 단계를 따를 수 있습니다.

### Salesforce 번개에서 {#salesforce-lightning}

1. [Salesforce.com](https://salesforce.com){target="_blank"}(으)로 이동합니다.
1. 오른쪽 상단 모서리의 톱니바퀴 아이콘을 클릭하고 **설정** > **개체 관리자**&#x200B;를 선택합니다.
1. &#39;빠른 찾기&#39; 상자에 &quot;task&quot;를 입력합니다.
1. 왼쪽 패널에서 **필드 및 관계**&#x200B;를 클릭합니다.
1. 필드 레이블 **Type**&#x200B;을(를) 클릭합니다.
1. 작업 유형 선택 목록 값에서 **새로 만들기**&#x200B;를 클릭합니다.
1. 누락된 작업 유형 선택 목록 값의 이름을 입력합니다(&quot;Email, &quot;Call&quot;, &quot;Reply&quot;).
1. **저장**&#x200B;을 클릭합니다.

### Salesforce Classic에서 {#salesforce-classic}

1. [Salesforce.com](https://salesforce.com){target="_blank"}(으)로 이동합니다.
1. **설정** > **빌드** > **사용자 지정** > **활동** > **작업 필드**&#x200B;를 클릭합니다.
1. **유형**&#x200B;을 클릭합니다.
1. 작업 유형 선택 목록 값에서 **새로 만들기**&#x200B;를 클릭합니다.
1. 누락된 작업 유형 선택 목록 값의 이름을 입력합니다(&quot;Email, &quot;Call&quot;, &quot;Reply&quot;).
1. **저장**&#x200B;을 클릭합니다.

이제 이 기능이 제대로 작동했으므로 유형 필드가 기록된 이메일, 호출 및 답글에 대한 해당 값을 채우는 것을 볼 수 있습니다. 이 값은 Sales Insight Actions 미리 알림 작업에 _not_&#x200B;됩니다.

>[!NOTE]
>
>&#39;회신&#39;이 값으로 표시되지 않으면 **새로 만들기**&#x200B;를 클릭하여 추가하십시오. &#39;Reply&#39;는 Salesforce의 표준 값이 아닙니다.

>[!MORELIKETHIS]
>
>* [Salesforce에 판매 활동 특성 로깅](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"}
>* [Salesforce 활동 세부 정보 사용자 지정 구성](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md){target="_blank"}
>* [영업 활동을 Salesforce에 동기화](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md){target="_blank"}
