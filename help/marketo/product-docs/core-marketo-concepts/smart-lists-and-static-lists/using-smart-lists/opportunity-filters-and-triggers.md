---
unique-page-id: 8159286
description: 영업 기회 필터 및 트리거 - Marketo 문서 - 제품 설명서
title: 영업 기회 필터 및 트리거
exl-id: 5b372c00-1553-4ac3-a495-53e208371d8d
feature: Smart Lists
source-git-commit: ac7d6b222ca561c88e0bf10aba7736c1b2eee3f7
workflow-type: tm+mt
source-wordcount: '474'
ht-degree: 0%

---

# 영업 기회 필터 및 트리거 {#opportunity-filters-and-triggers}

Opportunity 필터 및 트리거를 사용하여 Salesforce에서 Opportunity 이벤트를 추적할 수 있습니다. 다른 필터 및 트리거와 비교하면 약간 다릅니다.

## 영업 기회 필터 {#opportunity-filters}

영업 기회 필터를 사용하여 영업 기회가 있는 Salesforce 리드를 자세히 살펴볼 수 있습니다. 스마트 목록을 편집할 때 팔레트의 Opportunities 폴더에서 찾을 수 있습니다. 몇 가지 맛이 있습니다.

* 옵션 수
* 총 Opty 금액
* 총 Opty 예상 수익
* 영업 기회 있음
* 영업 기회가 추가되었습니다.
* 영업 기회 제거됨
* 영업 기회가 업데이트되었습니다.

영업 기회 필드(사용자 지정 또는 표준)를 찾는 경우 **영업 기회 있음** 필터를 사용하거나 **영업 기회가`[Added/Removed/Updated]`**&#x200B;개 필터 또는 트리거인 경우

**Opty 수, 총 Opty 금액, 총 Opty 예상 매출**

이러한 필터를 사용하면 모든 기회의 총 수, 금액 또는 예상 수익을 기반으로 잠재 고객을 찾을 수 있습니다.

![](assets/opportunity-filters-and-triggers-1.png)

**영업 기회가 있으며, 영업 기회에 추가되었으며, 영업 기회에서 제거되었습니다.**

기준의 조합에 따라 기회가 있는 잠재 고객을 찾으려면 **기회 있음**, **기회에 추가됨** 또는 **기회에서 제거됨** 필터를 사용하십시오. 그들은 당신에게 말합니다:

* **기회가 있음**: 현재 이 리드에 일치하는 기회가 있는 경우
* **영업 기회에 추가됨**: 이 잠재 고객이 일치하는 영업 기회에 추가된 경우
* **영업 기회에서 제거됨**: 일치하는 영업 기회에서 이 잠재 고객이 제거된 경우

검색 조건을 필터에 **제약 조건**(으)로 추가하십시오. 제한에는 영업 기회 표준 및 사용자 정의 필드가 포함됩니다.

![](assets/opportunity-filters-and-triggers-2.png)

![](assets/opportunity-filters-and-triggers-3.png)

예를 들어 $5,000 이상의 오픈 기회를 갖는 리드를 찾고 싶다고 가정해 보겠습니다. **기회 있음** 필터를 드래그하고 **닫힘** 및 **금액** 제한을 사용합니다.

![](assets/opportunity-filters-and-triggers-4.png)

>[!NOTE]
>
>여러 Opportunity 필터를 사용하는 경우 잘못된 응답이 나올 수 있습니다. 두 개의 Opportunity 필터를 사용하여 위의 예를 구축한 경우, 최소 5,000 달러 이상의 Opportunity 가 있는 Lead 목록과 Opportunity 가 Separate Opportunity 인 경우에도 Closed 되는 Opportunity 를 표시합니다.

**기회가 업데이트되었습니다**

특정 영업 기회 필드가 업데이트되면 **영업 기회가 업데이트됨** 필터가 모든 영업 기회를 찾습니다. 트리거 속성 풀다운 메뉴로 확인할 필드를 선택한 다음 제약조건을 사용하여 변경 세트 범위를 좁힙니다.

예를 들어 이 필터는 지난 30일 이내에 종료 날짜가 변경된 모든 리드를 표시합니다.

![](assets/opportunity-filters-and-triggers-5.png)

## 영업 기회 트리거 {#opportunity-triggers}

다음 영업 기회 트리거를 사용할 수 있습니다. 이벤트 발생 시 캠페인을 바로 트리거할 수 있다는 점을 제외하면 이 필터는 해당 필터(앞에서 설명됨)와 동일하게 작동합니다.

* 영업 기회가 업데이트되었습니다.
* 영업 기회에 추가됨
* 영업 기회에서 제거됨

예를 들어 이 Smart List를 사용하여 영업 기회에 리드가 추가될 때 트리거할 수 있습니다. 플로우에서 마케팅 일시 중단 목록에 추가하거나 타겟팅된 이메일을 보낼 수 있습니다.

![](assets/opportunity-filters-and-triggers-6.png)

영업 기회 사용자 지정 필드를 트리거하려면 **영업 기회가 업데이트됨** 트리거를 사용하고 풀다운 메뉴에서 필드를 선택하십시오.

![](assets/opportunity-filters-and-triggers-7.png)
