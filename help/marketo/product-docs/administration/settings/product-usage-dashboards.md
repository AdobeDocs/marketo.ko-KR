---
description: 제품 사용 대시보드 - Marketo 문서 - 제품 설명서
title: 제품 사용 대시보드
hide: true
hidefromtoc: true
feature: Administration
exl-id: a0fa5cd0-a61d-4383-88c0-9f2a4b2c717a
source-git-commit: 8a4f0015f99e62127f8b690263fb07de6a0a6e6f
workflow-type: tm+mt
source-wordcount: '610'
ht-degree: 0%

---

# 제품 사용 대시보드 {#product-usage-dashboards}

Marketo Engage 제품 사용 대시보드 는 특정 제한 또는 데이터 처리량 백로그, 일별 할당량 대비 사용, 구독의 주요 지표에 대한 제품 및 플랫폼 사용을 볼 수 있는 기능을 제공합니다. 인프라는 특정 속성에 대해 제품 수준에 정의된 성능 제한을 제공하기 위해 할당됩니다. API 사용과 같은 이러한 제한 중 일부는 패키지 또는 제품 계층의 일부로 구매한 약정된 제한입니다.

## 액세스 방법 {#how-to-access}

1. Marketo Engage에서 **관리자**&#x200B;를 클릭합니다.

   ![](assets/product-usage-dashboards-1.png)

1. 왼쪽의 트리에서 아래로 스크롤하여 **제품 사용 대시보드**&#x200B;를 선택합니다.

   ![](assets/product-usage-dashboards-2.png)

## 활동 사용량 대시보드 {#activity-usage-dashboard}

### 평균 주별 활동 {#average-weekly-activities}

주별 활동 사용량 대시보드는 롤링 52주 기간 동안 활동 유형의 주별 개수를 제공합니다. 주간 활동 산출물은 Marketo Engage에서 얼마나 많은 마케팅을 수행하고 있는지를 나타내는 좋은 지표입니다. 활동은 Marketo 내에서 발생하는 다양한 시스템 프로세스 및 추적 가능한 이벤트에 대한 프록시 역할을 합니다.

활동 유형에는 사람/잠재 고객이 마케팅 이벤트와 상호 작용할 때 캡처된 활동 수와 플로우 작업에 의해 트리거된 시스템 기반 활동이 모두 포함됩니다. 개인이 시작한 활동의 일부 예로는 수신자가 사용자가 보낸 이메일을 열거나 이메일의 링크를 클릭하는 경우가 있습니다. 흐름 작업에 의해 트리거된 시스템 기반 활동의 예로는 트리거가 시작될 때 _SFDC으로 보내기_&#x200B;가 있습니다.

>[!TIP]
>
>특정 주에 대한 활동 유형 수를 보려면 원하는 주를 마우스로 가리키면 수가 표시됩니다.

#### FAQ {#faq}

**어떤 활동 유형을 계산합니까?**

이는 파이프라인에 포함된 활동에 따라 달라집니다.

**알려진 활동과 익명의 사용자/잠재 고객 활동이 모두 포함되어 있습니까?**

알려진 사람/잠재 고객만.

**데이터를 얼마나 자주 새로 고치나요?**

활동 수는 매일 아침 새로 고쳐집니다.

## 활동 분류 {#activity-breakdown}

여기에서는 의미 있는 데이터 조각을 기반으로 지난 7일 동안의 활동 수를 구합니다. 지난 7일 동안 표시된 가장 일반적인 활동 유형별로 활동을 그룹화합니다. 여기에는 _데이터 값 변경_, _목록에 추가_ 또는 _전자 메일 보내기_&#x200B;와 같은 범주가 포함될 수 있습니다. 이를 통해 시스템에서 가장 자주 발생하는 활동 유형을 확인할 수 있습니다. 활동 유형 사용량은 증가를 결정하는 주요 지표이거나 사용량을 줄이기 위해 최적화가 필요한 경우 입니다.

>[!NOTE]
>
>* 아래의 모든 분류는 연속 7일 합계이며 **not**&#x200B;은(는) 현재 요일을 포함합니다. 그래서 그것을 &quot;어제 + 그 전 6일&quot;이라고 생각하십시오.
>
>* 대시보드에는 상위 20개 활동 유형만 표시되고 나머지는 &quot;기타&quot;라는 카테고리로 정렬됩니다.

활동 사용은 얼마나 많은 마케팅이 수행되고 있는지 보여주며, 계약 제품 수준에 대해 식별된 제품과의 성장을 시각화하는 데 도움이 됩니다. 대시보드는 업데이트되는 필드를 줄여 최적화할 수 있는/해야 하는 정도를 결정하는 안내서로 사용할 수도 있습니다.

### 유형별 {#by-type}

지난 7일 동안 표시된 가장 일반적인 활동 유형별로 활동을 그룹화합니다. 여기에는 _데이터 값 변경_, _목록에 추가_ 또는 _전자 메일 보내기_&#x200B;와 같은 범주가 포함될 수 있습니다. 이를 통해 Marketo Engage 계정에서 가장 자주 발생하는 활동 유형을 확인할 수 있습니다.

### 변경 데이터 값 속성별 {#by-change-data-value-attribute}

_데이터 값 변경_&#x200B;이(가) 가장 일반적인 활동 형식입니다. 개인/잠재 고객 레코드에 대한 정보가 업데이트되는 시기를 나타냅니다. 여기에서는 가장 자주 변경되는 필드를 기준으로 그룹화하므로, 마케팅 작업에 어떤 정보가 유용한지, 플랫폼 사용을 최적화할 수 있는 기회가 있는지 등을 판단할 수 있습니다.

### 캠페인별 {#by-campaign}

캠페인이 가장 많은 활동을 생성하는 기준 그룹입니다. 이를 통해 필요한 것보다 더 많은 활동을 만드는 특별히 &quot;시끄러운&quot; 캠페인이 있는지 확인할 수 있습니다. 폐기해야 하는 캠페인 또는 의도한 것보다 더 많은 작업을 수행하는 캠페인에 대해 빠르게 알아봅니다.
