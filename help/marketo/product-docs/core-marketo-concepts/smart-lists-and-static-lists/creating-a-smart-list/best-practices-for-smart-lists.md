---
unique-page-id: 7512524
description: 스마트 목록 우수 사례 - Marketo 문서 - 제품 설명서
title: 스마트 목록 우수 사례
exl-id: 466de198-1012-4ac3-906c-d41943fe5bc0
feature: Smart Lists
source-git-commit: 198d7d7fd4c1c312aeb30fa922fd89863ac87f81
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# 스마트 목록 우수 사례 {#best-practices-for-smart-lists}

스마트 목록은 마케팅 영역에서 가장 강력한 쿼리 도구입니다. 그들은 마법의 속도와 쉽게 찾고 있는 사람들을 찾습니다.

쉽게 작업하고 성능을 최적화하기 위해 모범 사례 목록을 만들었습니다. 맛있게 드십시오!

>[!NOTE]
>
>**모든 Marketo Engage 사용자가 다릅니다.** 데이터베이스가 클수록 더 많은 처리가 발생합니다. 더 많은 활동을 저장할수록 활동을 검색하는 데 더 오래 걸립니다.
>
>속도가 느려지는 경우 아래 팁을 시도해 보십시오. 문제가 지속되면 [Marketo 지원 센터](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}에 문의하십시오.

1. **내역 제한 -** 내역 필터(활동 필터라고도 함)는 리소스 집약적이고 시간이 많이 소요되는 작업에 속합니다. 이를 사용해야 하는 경우 날짜 범위를 가능한 짧게 제한하십시오. 이렇게 하면 검색 가능한 데이터 세트가 줄어듭니다. 또한 날짜 범위는 보존 기간을 대체하지 않습니다. 예: 쿼리하는 활동에 90일 보존 기간이 있고 &quot;지난 100일&quot;을 선택한 경우 지난 90일의 결과만 반환됩니다. 활동 유지 기간 [은(는) 여기에서 찾을 수 있습니다](https://nation.marketo.com/t5/knowledgebase/marketo-activities-data-retention-policy/ta-p/251480){target="_blank"}.
1. **중첩된 스마트 목록 제한 -** 새 스마트 목록을 만들 때 사용되는 &quot;스마트 목록 구성원&quot; 필터의 양을 제한합니다. 이를 중첩 스마트 목록이라고 하며, 참조된 각 스마트 목록은 처리 시간을 늘립니다. 대신 정적 목록을 참조하거나 [세그멘테이션](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md){target="_blank"}을 활용하세요.
1. **음수 연산자보다 양수 연산자 사용 -** 필터를 사용할 수 있지만 &quot;사용할 수 없음&quot;일 경우 인스턴스에 있는 전체 데이터 집합을 검색해야 하므로 시간이 많이 걸릴 수 있습니다. 긍정적인 &quot;is&quot; 필터는 더 효과적인 검색 알고리즘을 활용할 수 있습니다.
1. **포함 안 함 -** 부분 데이터만 있는 경우 &quot;다음으로 시작&quot; 한정자는 &quot;포함&quot;보다 훨씬 빠른 결과를 생성합니다. &quot;Is&quot;는 훨씬 더 빠르게 실행됩니다. 다중 값에 &quot;포함&quot;을 사용하지 마십시오. 두 값을 함께 사용하면 캠페인 속도가 훨씬 더 느려질 수 있습니다.
1. **무작위 샘플을 직접 사용 -** 무작위 샘플은 특수 필터입니다. 직접 사용해 사람들을 미리 만들어진 목록에 넣으세요. 그런 다음 &quot;목록의 구성원&quot;을 사용하여 스마트 목록을 매우 빠르게 만듭니다. 임의 샘플은 중첩된 스마트 목록에서 **NOT** 작동합니다. &quot;스마트 목록의 구성원&quot; 필터에 대해 참조되는 스마트 목록인 경우 무작위 샘플 필터가 작동하지 않습니다.
1. **비활성 필터를 사용하여 검소하게 작업하십시오. -** &quot;양식을 채우지 않음&quot;과 같은 필터는 매우 유용할 수 있지만 처리 능력이 훨씬 더 필요합니다.
1. **여러 값을 붙여 넣는 것이 좋습니다.** 다중 선택은 수십 개 또는 수백 개의 값을 붙여 넣도록 설계되었습니다. 그러나 너무 많이 넣으면 속도가 느려질 것이다.
1. **제약 조건을 추가할 때 절약하십시오. -** 규칙과 관련 값의 작은 세부 정보입니다. 제한을 많이 추가할수록 처리 시간이 느려집니다.
1. **캠페인 간소화 -** 100개 이상의 독립 규칙(확인함!) 진행하는데 분명히 약간의 시간이 걸릴 것입니다. 단순하게 유지하면 속도가 빨라지는 것을 알 수 있을 뿐만 아니라 쉽게 이해할 수 있습니다.
1. **전자 메일 주소 필터를 사용할 때 도메인 이름 앞에 @ 기호를 포함합니다** **-** 이렇게 하면 더 빠른 쿼리를 사용할 수 있습니다. 예: _이메일에 &#39;somedomain.com&#39;_&#x200B;이 들어 있는 경우 대신 _이메일에 &#39;somedomain.com@somedomain3&rbrace;이 들어 있는 경우&#39;를 사용하십시오._ &quot;포함&quot;이 있는 여러 전자 메일 주소를 사용하는 경우 모든 전자 메일 주소는 &quot;@&quot;으로 시작해야 합니다.

>[!TIP]
>
>Marketo Engage은 다양한 방식으로 사용할 수 있으며 특정 기술은 사용자와 비즈니스에 더 적합합니다. 투자를 최대한 활용하는 데 도움이 필요하면 Adobe Professional Services 영업 담당자에게 문의하십시오.
