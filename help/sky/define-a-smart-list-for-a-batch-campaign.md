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

스마트 목록은 Marketing 전체의 메커니즘으로 보고서, 목록 또는 스마트 캠페인이든 포함할 &quot;사용자&quot;(사람)를 정의합니다. 일괄 처리 캠페인에 대한 스마트 목록을 정의하는 방법입니다.

1. 스마트 캠페인을 선택한 다음 **[!UICONTROL Smart List]**&#x200B;을 클릭합니다.

   ![이미지 원](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-1.png)

1. 필터를 검색할 필터를 입력한 다음 캔버스로 드래그하여 놓습니다. 여러 필터에 대해 반복합니다.

   ![이미지 2](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-2.png)

   >[!NOTE]
   >
   >필터만 있는 스마트 캠페인은 일괄 처리 모드에서 실행됩니다. 필터를 기반으로 자격을 갖춘 데이터베이스를 찾은 사용자가 있고 모든 사용자가 한 번에 흐름을 따라 실행됩니다.

   >[!IMPORTANT]
   >
   >스마트 캠페인을 트리거 모드에서 표시하는 트리거를 추가하여 라이브 이벤트를 기반으로 한 번에 한 사람씩 스마트 캠페인을 실행할 수 있습니다.

1. 드롭다운을 클릭하고 필터 연산자(예:선택한 필터의 **[!UICONTROL is]**, **[!UICONTROL is not]** 등)

   ![이미지 3](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-3.png)

   >[!CAUTION]
   >
   >빨간색 줄은 오류 또는 누락된 정보를 나타냅니다. 수정되지 않으면 캠페인이 유효하지 않으며 실행되지 않습니다.

1. 필터 값을 입력합니다.

   ![이미지 4](/help/sky/assets/smart-campaigns/define-a-smart-list-for-a-batch-campaign/define-a-smart-list-for-a-batch-campaign-4.png)

>[!NOTE]
>
>기본적으로 모든 스마트 목록 규칙을 만족하는 사람은
>적격한 URL. 캠페인 요구에 맞게 수정할 수 있습니다. 자세한 내용은 [복잡한 로직용 스마트 목록 규칙](https://docs.marketo.com/display/DOCS/Using+Advanced+Smart+List+Rule+Logic)을 참조하십시오.
>
>실시간 이벤트를 한 번에 하나씩 트리거하려면 [스마트 캠페인에 대한 스마트 목록 정의 방법을 학습합니다. | 트리거](https://docs.marketo.com/display/DOCS/Define+Smart+List+for+Smart+Campaign+%7C+Trigger).
