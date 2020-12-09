---
title: define-a-smart-list-for-a-batch-campaign
description: 배치 캠페인에 대한 스마트 목록 정의
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '256'
ht-degree: 0%

---


# 배치 캠페인에 대한 스마트 목록 정의

<br> 

스마트 목록은 Marketing에서 포함할 &quot;사용자&quot;(사람)를 정의하는 메커니즘으로, 보고서, 목록 또는 스마트 캠페인입니다. 다음은 일괄 처리 캠페인에 대한 스마트 목록을 정의하는 방법입니다.

1. 스마트 캠페인을 선택한 다음 을 클릭합니다 **[!UICONTROL Smart List]**.

   ![이미지 원](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-1.png)

1. 필터를 검색할 필터를 입력한 다음 캔버스에 드래그하여 놓습니다. 여러 필터에 대해 반복합니다.

   ![이미지 2](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-2.png)

   >[!NOTE]
   >
   >필터만 있는 스마트 캠페인은 일괄 처리 모드에서 실행됩니다. 데이터베이스에 있는 사용자가 필터를 기반으로 자격을 얻게 되고 한 번에 모든 흐름을 통해 실행됩니다.

   >[!IMPORTANT]
   >
   >스마트 캠페인을 트리거 모드로 전환시키는 트리거를 추가하여 실시간 이벤트를 기반으로 한 시간에 한 사람씩 스마트 캠페인을 실행할 수 있습니다.

1. 드롭다운을 클릭하고 필터 연산자(예: **[!UICONTROL is]**, **[!UICONTROL is not]** etc.)을 선택합니다.

   ![이미지 3](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-3.png)

   >[!CAUTION]
   >
   >빨간색 줄은 오류나 누락된 정보를 나타냅니다. 수정되지 않으면 캠페인이 잘못되고 실행되지 않습니다.

1. 필터 값을 입력합니다.

   ![이미지 4](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-4.png)

>[!NOTE]
>
>기본적으로 ALL을 만족하는 사용자는
>자격 조건을 갖추고 있습니다. 캠페인 요구에 맞게 수정할 수 있습니다. 자세한 내용은 [복잡한 로직을 위한 스마트 목록](https://docs.marketo.com/display/DOCS/Using+Advanced+Smart+List+Rule+Logic) 규칙을 참조하십시오.
>
>한 번에 한 명의 라이브 이벤트를 트리거하려면 스마트 캠페인에 대한 [스마트 목록 정의 방법을 알아봅니다 | 트리거](https://docs.marketo.com/display/DOCS/Define+Smart+List+for+Smart+Campaign+%7C+Trigger).
