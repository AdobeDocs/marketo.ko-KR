---
unique-page-id: 9438139
description: 개인 차단 목록에 추가하다 추가 - Marketo 문서 - 제품 설명서
title: 차단 목록에 추가하다 Person 추가
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
feature: Smart Lists
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 1%

---

# 차단 목록에 추가하다 Person 추가 {#add-person-to-blocklist}

차단 목록에 사람들을 추가하면 그들은 당신의 서신을 받지 못하게 됩니다.

1. 새 [기본 프로그램을 만들고](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md){target="_blank"} 이름을 &quot;차단 목록에 추가&quot;로 지정합니다.

1. **[!UICONTROL New]**&#x200B;을(를) 클릭하고 **[!UICONTROL New Local Asset]**&#x200B;을(를) 선택합니다.

   ![](assets/add-person-to-blocklist-1.png)

1. **[!UICONTROL Smart List]**&#x200B;를 선택합니다.

   ![](assets/add-person-to-blocklist-2.png)

1. 목록의 이름을 지정하고 **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/add-person-to-blocklist-3.png)

1. 당신이 당신의 스마트 목록에 추가하려는 모든 사람들을 추가 차단 목록에 추가하다.

   ![](assets/add-person-to-blocklist-4.png)

   >[!NOTE]
   >
   >차단 목록 중인 사용자는 운영 이메일을 받지 않습니다.

1. 프로그램으로 돌아갑니다.

   ![](assets/add-person-to-blocklist-5.png)

1. **[!UICONTROL New]**&#x200B;을(를) 클릭하고 **[!UICONTROL New Smart Campaign]**&#x200B;을(를) 선택합니다.

   ![](assets/add-person-to-blocklist-6.png)

1. 새 스마트 캠페인에 이름을 지정합니다. **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/add-person-to-blocklist-7.png)

1. **[!UICONTROL Member of Smart List]**&#x200B;을(를) 끌어서 놓습니다.

   ![](assets/add-person-to-blocklist-8.png)

1. 방금 만든 스마트 목록을 선택합니다.

   ![](assets/add-person-to-blocklist-9.png)

1. **[!UICONTROL Flow]** 탭을 클릭합니다. **[!UICONTROL Change Data Value]** 흐름 작업을 끌어서 놓습니다.

   ![](assets/add-person-to-blocklist-10.png)

1. **[!UICONTROL Attribute]** 드롭다운에서 **[!UICONTROL Block Listed]**&#x200B;을(를) 선택하고 **[!UICONTROL New Value]**&#x200B;을(를) **[!UICONTROL true]**(으)로 설정합니다.

   ![](assets/add-person-to-blocklist-11.png)

1. **[!UICONTROL Schedule]** 탭을 클릭하고 **[!UICONTROL Run Once]**&#x200B;을(를) 선택합니다.

   ![](assets/add-person-to-blocklist-12.png)

1. **[!UICONTROL Run Now]**&#x200B;을(를) 선택하고 **[!UICONTROL Run]**&#x200B;을(를) 클릭합니다.

   ![](assets/add-person-to-blocklist-13.png)

1. **[!UICONTROL Run]**&#x200B;을(를) 다시 클릭합니다.

   ![](assets/add-person-to-blocklist-14.png)

이러한 사용자는 더 이상 이메일을 받지 않습니다.

>[!TIP]
>
>다음에 차단 목록에 추가하다 가능 특성이 있는 모든 사용자에 대해 [나열된 블록이 true](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md){target="_blank"}인 **데이터 값 변경**&#x200B;을 사용하여 **캠페인 트리거**&#x200B;를 만듭니다.
