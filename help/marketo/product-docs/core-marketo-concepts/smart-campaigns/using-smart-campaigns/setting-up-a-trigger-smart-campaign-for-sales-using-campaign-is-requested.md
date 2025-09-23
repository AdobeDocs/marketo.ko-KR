---
unique-page-id: 7514898
description: '"캠페인이 요청됨"을 사용하여 판매용 스마트 캠페인 트리거 설정 - Marketo 문서 - 제품 설명서'
title: “캠페인 요청됨”을 사용하여 영업용 트리거 스마트 캠페인 설정
exl-id: ed6d7c27-d54b-48e3-af67-19503da4ef56
feature: Smart Campaigns
source-git-commit: 65d607e279fb86b0816ccaec2f4bf3c69e309cb9
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 11%

---

# “캠페인 요청됨”을 사용하여 영업용 트리거 스마트 캠페인 설정 {#setting-up-a-trigger-smart-campaign-for-sales-using-campaign-is-requested}

Marketo의 가장 멋진 기능 중 하나는 영업 사원이 마케팅 활동에 참여할 수 있도록 하는 기능입니다. 그들은 최전선에 있고, 사람들과 교류하고 있습니다. Sales Rep 는 올바른 방향으로 마케팅을 제어할 수 있어야 합니다.

>[!NOTE]
>
>요청할 스마트 캠페인의 예:
>
>1. **장기 육성** - 올해 예산이 없어서 미봉책에 머물고 싶을 때
>1. **활성 영업 주기** - 영업 사원이 자신의 영업 사원에 대한 메시지를 제외하고 원하지 않는 경우. (일시적으로 가입을 해지하려면 마케팅 일시 중단 플래그를 사용합니다.)
>
>창의적이 되세요. 영업 사원은 어떤 작업을 자동화하시겠습니까? 그들에게 물어보고 전선을 연결하기만 하면 됩니다!

1. 스마트 캠페인을 만듭니다.

   ![](assets/setting-up-a-trigger-smart-campaign-for-sales-1.png)

1. **[!UICONTROL Campaign is Requested]** 트리거를 찾아 캔버스로 드래그합니다.

   ![](assets/setting-up-a-trigger-smart-campaign-for-sales-2.png)

1. 소스 선택 사항은 어떤 종류의 요청을 수행할 것인지 나타냅니다. Salesforce 기능의 경우 **[!UICONTROL Sales Insight]**&#x200B;을(를) 선택하십시오.

   >[!TIP]
   >
   >소스 연산자는 보안을 위한 것입니다. 다른 스마트 캠페인 또는 개발자와 같이 특정 소스에서만 수행된 요청으로 캠페인을 제한할 수 있습니다. 모든 원본의 요청을 허용하려면 첫 번째 상자에서 **[!UICONTROL Is Any]**&#x200B;을(를) 선택하십시오.
   >
   >_기억하기_, 판매 Insight을 선택하면 판매 상자에 표시됩니다. 너무 무리하지 마세요. 너무 많으면 무시당하기 마련이다.

   ![](assets/setting-up-a-trigger-smart-campaign-for-sales-3.png)

마케팅 범위를 다른 부서로 확장하는 좋은 방법입니다. 자동화할 모든 종류의 캠페인을 설정합니다.

>[!TIP]
>
>스마트 캠페인의 이름을 명확히 지정하는 것을 잊지 마십시오. 이 이름은 Sales Insight에 이름 지정 방식을 정확하게 보여 줍니다.
