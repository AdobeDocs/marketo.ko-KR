---
unique-page-id: 8159286
description: 기회 필터 및 트리거 - 마케팅 문서 - 제품 설명서
title: 기회 필터 및 트리거
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '471'
ht-degree: 0%

---


# 기회 필터 및 트리거 {#opportunity-filters-and-triggers}

기회 필터 및 트리거를 사용하여 Salesforce에서 기회 이벤트를 추적할 수 있습니다. 다른 필터 및 트리거와 약간 다릅니다.

## 기회 필터 {#opportunity-filters}

기회 필터를 사용하면 기회가 있는 Salesforce 리드를 드릴다운할 수 있습니다. 스마트 목록을 편집할 때 팔레트의 기회 폴더에서 찾을 수 있습니다. 몇 가지 맛이 있습니다

* 옵션 수
* 총 수량
* 총 예상 매출
* 기회 있음
* 기회가 추가되었습니다.
* 기회가 제거되었습니다.
* 기회가 업데이트되었습니다.

Opportunity 필드(사용자 지정 또는 표준)를 찾는 경우 Has Opportunity 필터 또는 **Opportunity가 필터 또는** 트리거였음 **`[Added/Removed/Updated]`** 을 사용하십시오.

**오퍼 수, 총 오차 금액, 총 예상 수익**

이러한 필터를 사용하면 모든 기회의 총 매출액, 금액 또는 예상 매출액을 기준으로 리드를 찾을 수 있습니다.

![](assets/image2015-6-11-12-3a29-3a34.png)

**Opportunity 가 Opportunity에 추가되고 Opportunity에서 제거됨**

조건 조합을 기반으로 한 기회가 있는 리드를 찾으려면 **기회**&#x200B;있음 **, 기회에****추가됨** 또는 기회에서 제거됨필터를사용하십시오. 다음과 같은 정보를 제공합니다.

* **기회**&#x200B;있음:현재 이 리드에 일치하는 기회가 있는 경우
* **Opportunity에 추가됨**:이 리드가 일치하는 기회에 추가된 경우
* **Opportunity에서 제거됨**:이 리드가 일치하는 기회에서 제거된 경우

필터에 검색 기준 **을 제한** 요소로 추가합니다. 제한 사항에는 기회 표준 및 사용자 정의 필드가 포함됩니다.

![](assets/image2015-6-11-12-3a31-3a0.png)

![](assets/image2015-6-11-12-3a31-3a46.png)

예를 들어 최소 5,000달러의 영업 기회가 있는 리드를 찾고 싶다고 가정해 봅시다. 기회 **가 있음** 필터에서 드래그하고 폐쇄됨 **및** 양 **제약 조건** 을 사용합니다.

![](assets/image2015-6-11-12-3a32-3a0.png)

>[!NOTE]
>
>여러 개의 기회 필터를 사용하는 경우 잘못된 대답이 나타날 수 있습니다. 위의 예를 두 개의 Opportunity 필터로 작성한 경우 5,000달러 이상의 기회와 기회가 없는 Adobe Experience Manager를 통해 Adobe Extension Manager가 별도로 제공되더라도 Adobe Extension Manager가 Adobe Extension Manager ManagerX에 대해

**기회가 업데이트되었습니다.**

Opportunity **Was Updated** 필터는 특정 기회 필드가 업데이트되면 어떤 기회든 찾습니다. 트리거 속성 풀다운에서 확인할 필드를 선택한 다음 제한 조건을 사용하여 변경 내용 집합을 좁힙니다.

예를 들어 이 필터는 최근 30일 이내에 종료 날짜가 변경된 모든 리드를 표시합니다.

![](assets/image2015-6-11-12-3a33-3a7.png)

## 기회 트리거 {#opportunity-triggers}

다음 기회 트리거를 사용할 수 있습니다. 이벤트가 발생할 때 캠페인을 바로 트리거할 수 있다는 점을 제외하면, 해당 필터(앞에서 설명됨)와 마찬가지로 작동합니다.

* Opportunity 가 업데이트됨
* Opportunity에 추가됨
* Opportunity에서 제거됨

예를 들어 이 스마트 목록을 사용하여 어떤 기회에도 리드가 추가되면 트리거할 수 있습니다. 플로우에서 마케팅 일시 중단 목록에 추가하거나 타깃팅된 이메일을 보낼 수 있습니다.

![](assets/image2015-6-11-12-3a33-3a48.png)

기회 사용자 정의 필드를 트리거하려면 **기회가 업데이트됨** 트리거를 사용하고 풀다운에서 필드를 선택합니다.

![](assets/image2015-6-11-12-3a33-3a34.png)

