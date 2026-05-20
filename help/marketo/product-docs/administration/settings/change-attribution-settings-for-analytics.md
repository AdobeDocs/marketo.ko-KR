---
unique-page-id: 2360217
description: 수익 주기 분석에서 첫 번째 및 다중 접점 속성, 리드 전환 및 마케팅에 영향을 주는 기회 옵션을 설정하는 방법.
title: 분석용 속성 설정 변경
exl-id: 4740b0fa-ddaf-46ed-87d6-8b3f8d35afe3
feature: Administration
TQID: https://experienceleague.adobe.com/AjpEYRzLKRQQsTmYdQUvAVnlcmG-Q6nbVjaZCuQYaUc
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: d1d0a9cd-295d-4976-8c39-ddae266f240eid: ea90ebee-5c84-42d9-8b21-006bdabc95a3
subfeature_v2: id: e5d29014-8a81-4c0c-845b-2adc7a5d6258
topic_v2: id: aa2f3246-cb95-4b30-8899-fdf7d73550ccid: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 160
ht-degree: 9%

---

# 분석용 속성 설정 변경 {#change-attribution-settings-for-analytics}

Marketo에서 첫 번째 및 다중 접점 속성, 잠재 고객 전환 지표 및 마케팅에 영향을 주는 영업 기회 플래그에 연락처를 연결하는 방식을 변경할 수 있습니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/change-attribution-settings-for-analytics-1.png)

1. **[!UICONTROL Revenue Cycle Analytics]**&#x200B;를 클릭합니다.

   ![](assets/change-attribution-settings-for-analytics-2.png)

1. **[!UICONTROL Attribution]** 아래의 **[!UICONTROL Edit]** 링크를 클릭합니다.

   ![](assets/change-attribution-settings-for-analytics-3.png)

   >[!TIP]
   >
   >이 설정을 변경해도 Marketo 데이터는 수정되지 않고 보고서 실행 방식도 변경됩니다. 언제든지 되돌릴 수 있습니다.

1. 옵션을 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/change-attribution-settings-for-analytics-4.png)

   >[!NOTE]
   >
   >**정의**
   >
   >**[!UICONTROL Explicit]**: 역할이 있는 연락처만(기본값).
   >
   >**[!UICONTROL Hybrid]**: 가능한 경우 역할을 가진 대화 상대. 사용 가능한 연락처가 없으면 계정의 모든 연락처를 사용합니다.
   >
   >**[!UICONTROL Implicit]**: 역할에 관계없이 모든 연락처입니다.

>[!CAUTION]
>
>**[!UICONTROL Implicit]**&#x200B;을(를) 사용하는 경우 Marketo은 역할에 관계없이 항상 계정과 연결된 모든 연락처를 검사합니다. **Marketo은 [!UICONTROL Explicit] 모드**&#x200B;를 사용할 것을 강력히 권장합니다. [!UICONTROL Implicit]을(를) 사용하면 긍정 오류(false positive), 즉 기회에 실제 영향을 주지 않았음에도 불구하고 기회에 대한 크레딧이 있는 사람이 생성될 수 있습니다. 주의해서 [!UICONTROL Implicit]을(를) 사용하십시오.
