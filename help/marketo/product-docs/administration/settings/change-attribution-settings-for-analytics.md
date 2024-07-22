---
unique-page-id: 2360217
description: Analytics에 대한 속성 설정 변경 - Marketo 문서 - 제품 설명서
title: Analytics에 대한 속성 설정 변경
exl-id: 4740b0fa-ddaf-46ed-87d6-8b3f8d35afe3
feature: Administration
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---

# Analytics에 대한 속성 설정 변경 {#change-attribution-settings-for-analytics}

Marketo에서 첫 번째 및 다중 접점 속성, 잠재 고객 전환 지표 및 마케팅에 영향을 주는 영업 기회 플래그에 연락처를 연결하는 방식을 변경할 수 있습니다.

이 설정은 [프로그램 영업 기회 분석](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/understanding-the-program-opportunity-analysis-area.md), [영업 기회 분석](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-explorer/understanding-opportunity-analysis-in-revenue-explorer.md) 및 잠재 고객 분석 영역에 있는 [!UICONTROL 매출 탐색기] 보고서에 영향을 줍니다. 이는 [!UICONTROL 프로그램 분석기] 보고서에도 영향을 줍니다.

1. **[!UICONTROL 관리자]** 영역으로 이동합니다.

   ![](assets/change-attribution-settings-for-analytics-1.png)

1. **[!UICONTROL 수익 주기 분석]**&#x200B;을 클릭합니다.

   ![](assets/change-attribution-settings-for-analytics-2.png)

1. **[!UICONTROL 속성]** 아래의 **[!UICONTROL 편집]** 링크를 클릭합니다.

   ![](assets/change-attribution-settings-for-analytics-3.png)

   >[!TIP]
   >
   >이 설정을 변경해도 Marketo 데이터는 수정되지 않고 보고서 실행 방식만 변경됩니다. 언제든지 되돌릴 수 있습니다.

1. 옵션을 선택하고 **[!UICONTROL 저장]**&#x200B;을 클릭하세요.

   ![](assets/change-attribution-settings-for-analytics-4.png)

   >[!NOTE]
   >
   >**정의**
   >
   >**[!UICONTROL 명시적]**: 역할이 있는 연락처만(기본값).
   >
   >**[!UICONTROL 하이브리드]**: 사용 가능한 경우 역할이 있는 대화 상대. 사용 가능한 연락처가 없으면 계정의 모든 연락처를 사용합니다.
   >
   >**[!UICONTROL 암시적]**: 역할에 관계없이 모든 연락처입니다.

>[!CAUTION]
>
>**[!UICONTROL 암시적]**&#x200B;을(를) 사용하는 경우 Marketo은 역할에 관계없이 항상 계정과 연결된 모든 연락처를 검사합니다. **Marketo에서는 [!UICONTROL 명시적] 모드**&#x200B;를 사용할 것을 강력히 권장합니다. [!UICONTROL 암시적]을 사용하면 긍정 오류(false positive), 즉 기회에 실질적인 영향을 미치지 않지만 기회에 대한 크레딧이 있는 사람이 만들어질 수 있습니다. 주의해서 [!UICONTROL 암시적]을(를) 사용하십시오.
