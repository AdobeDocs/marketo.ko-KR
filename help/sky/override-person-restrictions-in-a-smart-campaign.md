---
title: 스마트 캠페인 내 사람-제한-대체
description: 스마트 캠페인에서 개인 제한 무시
exl-id: efdd6c68-a95e-4b2a-9249-e2e1f550b628
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '130'
ht-degree: 0%

---

# 스마트 캠페인에서 개인 제한 무시

<br> 

Marketo을 사용하면 스마트 캠페인에 가입할 수 있는 최대 사용자 수를 설정할 수 있습니다.이로 인해 실수로 전체 데이터베이스를 이메일로 전송하지 않아도 됩니다. 이 제한을 무시하려면 다음 방법을 사용하십시오.

>[!IMPORTANT]
>
>Marketo [!UICONTROL Admin]에서 스마트 캠페인](https://docs.marketo.com/display/DOCS/Enable+Person+Restrictions+for+Smart+Campaigns)에 대해 사용자 제한 사항을 활성화해야 합니다.[

1. 스마트 캠페인을 찾고 **[!UICONTROL Schedule]**&#x200B;을 클릭합니다.

   ![이미지 원](/help/sky/assets/smart-campaigns/override-person-restrictions-in-a-smart-campaign/override-person-restrictions-in-a-smart-campaign-1.png)

1. 여기를 클릭하십시오 **[!UICONTROL Qualification Rules]**.

   ![이미지 2](/help/sky/assets/smart-campaigns/override-person-restrictions-in-a-smart-campaign/override-person-restrictions-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >기본 제한은 관리에서 설정된 것입니다.

1. **[!UICONTROL Abort campaign if qualified leads exceed]** 옆에 새 제한을 입력합니다.

   ![이미지 3](/help/sky/assets/smart-campaigns/override-person-restrictions-in-a-smart-campaign/override-person-restrictions-in-a-smart-campaign-3.png)

>[!NOTE]
>
>자격을 갖춘 사람 수가 설정된 제한을 초과하면 스마트 캠페인은 실행되지 않습니다.

>[!CAUTION]
>
>실수로 사람을 너무 많이 포함하지 않도록 이 기능을 주의하십시오.
