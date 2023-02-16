---
unique-page-id: 2360217
description: Analytics에 대한 속성 설정 변경 - Marketo 문서 - 제품 설명서
title: Analytics에 대한 속성 설정 변경
exl-id: 4740b0fa-ddaf-46ed-87d6-8b3f8d35afe3
source-git-commit: 07899e541b3624e99e0ead59d898ced2ab4e57af
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---

# Analytics에 대한 속성 설정 변경 {#change-attribution-settings-for-analytics}

Marketo이 연락처와 첫 번째 및 다중 터치 속성, 리드 전환 지표 및 마케팅 영향을 받는 기회 플래그를 위한 기회에 연결하는 방법을 변경할 수 있습니다.

이러한 설정은 [프로그램 기회 분석](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/understanding-the-program-opportunity-analysis-area.md), [기회 분석](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-explorer/understanding-opportunity-analysis-in-revenue-explorer.md), 및 Lead Analysis 영역 을 참조하십시오. 프로그램 분석기 보고서도 영향을 받습니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/change-attribution-settings-for-analytics-1.png)

1. 클릭 **Revenue Cycle Analytics**.

   ![](assets/change-attribution-settings-for-analytics-2.png)

1. 을(를) 클릭합니다. **편집** 링크 위치 **속성**.

   ![](assets/change-attribution-settings-for-analytics-3.png)

   >[!TIP]
   >
   >이 설정을 변경해도 Marketo 데이터가 수정되지 않습니다. 보고서 실행 방식을 변경하기만 하면 됩니다. 언제든지 되돌릴 수 있습니다.

1. 옵션을 선택하고 을(를) 클릭합니다. **저장**.

   ![](assets/change-attribution-settings-for-analytics-4.png)

   >[!NOTE]
   >
   >**정의**
   >
   >**명시적**: 역할이 있는 연락처만(기본값)
   >
   >**하이브리드**: 가능한 경우 역할이 있는 연락처 사용할 수 있는 연락처가 없으면 계정의 모든 연락처를 사용합니다.
   >
   >**암시적**: 역할과 관계없이 모든 연락처

>[!CAUTION]
>
>사용 시 **암시적**, Marketo은 역할에 관계없이 계정과 연결된 모든 연락처를 검사합니다. **Marketo은 명시적 모드를 사용하는 것이 좋습니다**. 암시적 사용은 긍정 오류(false positive)를 생성할 수 있습니다. 기회에는 실질적인 영향력이 없음에도 기회를 인정 받은 사람들. 암시적 사용을 신중하게 사용하십시오.
