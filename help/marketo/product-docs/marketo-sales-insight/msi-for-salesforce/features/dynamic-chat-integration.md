---
description: 다이내믹 채팅 통합 - Marketo 문서 - 제품 설명서
title: Dynamic Chat 통합
hide: true
hidefromtoc: true
exl-id: b2e3b4da-9ca7-4299-9c50-f52e0de91e36
source-git-commit: b8f2308d3b1a252a8fe10ba0a26d4c5aa07c4756
workflow-type: tm+mt
source-wordcount: '316'
ht-degree: 3%

---

# Dynamic Chat 통합 {#dynamic-chat-integration}

Sales Insight와 Dynamic Chat 통합에 대해 자세히 알아보십시오.

>[!PREREQUISITES]
>
>* Sales Insight SFDC 패키지는 버전이어야 합니다 [1.9 이상](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md){target=&quot;_blank&quot;}
>
>* 다음 항목이 있어야 합니다. [다이내믹 채팅 통합](/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md){target=&quot;_blank&quot;} 설정


## Marketo Sales Insight 구성 탭 {#marketo-sales-insight-configuration-tab}

아래 절차에 따라 다이내믹 채팅 통합을 활성화합니다.

1. Salesforce 계정에 로그인하고 탭 모음의 끝에 있는 + 를 클릭하고 를 클릭합니다. **Marketo Sales Insight Config**.

1. 를 클릭하여 &quot;시각화 패널&quot;을 엽니다.

   ![](assets/dynamic-chat-integration-1.png)

1. 을(를) 선택합니다 **동적 채팅 데이터 활성화** 확인란을 선택합니다.

   ![](assets/dynamic-chat-integration-2.png)

## 기능 개요 {#feature-overview}

Sales Insight 사용자는 다음 Dynamic Chat 활동을 활용할 수 있습니다.

참여 대화 상자: 방문자가 Chatbot를 클릭하고 대화 상자를 사용할 때 Marketo에 로그인되어 Sales Insight에 채워집니다.

* 대화 상자 이름
* 페이지 URL
* 상태(시작됨/삭제됨/완료됨)

예약된 약속: 방문자가 Chatbot를 통해 약속을 성공적으로 예약하면 Marketo에 로그인하고 Sales Insight에 채워집니다.

* 대화 상자 이름
* 에이전트
* 페이지 URL
* 예약됨(날짜 및 타임스탬프 삽입)
* 상태(예약됨, 예약됨, 취소됨)

목표에 도달함: 방문자가 모든 대화 상자 흐름에서 목표에 도달하면 Marketo에 로그인하고 Sales Insight에 채워집니다.

* 대화 상자 이름
* 목표 이름
* 페이지 URL

채팅 탭은 리드 및 연락처 패널에서 사용할 수 있습니다. 여기에는 활동 유형, 대화 상자 이름 및 날짜 열이 포함되어 있습니다.

![](assets/dynamic-chat-integration-3.png)

활동 유형을 클릭하여 자세히 알아볼 수 있습니다.

![](assets/dynamic-chat-integration-4.png)

마찬가지로 계정 및 기회 패널에는 이름, 활동 유형, 대화 상자 이름 및 날짜 열이 포함됩니다.

![](assets/dynamic-chat-integration-5.png)

채팅 탭은 글로벌 Marketo 탭에도 포함되어 있습니다. 여기에는 세 가지 활동 유형(참여 대화 상자, 예약된 약속, 도달 목표)이 포함되어 있으며, 다음과 같은 열이 포함되어 있습니다.

* 개인
* 계정
* 활동 유형(참여 대화 상자, 예약된 약속, 목표에 도달함)
* 대화 상자 이름
* 날짜 및 타임스탬프

활동 유형을 클릭하여 자세히 알아볼 수 있습니다.

![](assets/dynamic-chat-integration-6.png)

>[!NOTE]
>
>&quot;Interact with Document&quot; 활동은 향후 릴리스에서 MSI에서 사용할 수 있습니다.
