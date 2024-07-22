---
unique-page-id: 9438139
description: 개인 차단 목록에 추가하다 추가 - Marketo 문서 - 제품 설명서
title: 차단 목록에 추가하다 Person 추가
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
feature: Smart Lists
source-git-commit: de8eb7dd1b7f1da5d219ec8c182a02eb998a2a22
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# 차단 목록에 추가하다 Person 추가 {#add-person-to-blocklist}

차단 목록에 사람들을 추가하면 그들은 당신의 서신을 받지 못하게 됩니다.

1. 새 [기본 프로그램을 만들고](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md){target="_blank"} 이름을 &quot;차단 목록에 추가&quot;로 지정합니다.

1. **[!UICONTROL 새로 만들기]**&#x200B;를 클릭하고 **[!UICONTROL 새 로컬 자산]**&#x200B;을 선택합니다.

   ![](assets/add-person-to-blocklist-1.png)

1. **[!UICONTROL 스마트 목록]**&#x200B;을 선택하세요.

   ![](assets/add-person-to-blocklist-2.png)

1. 목록의 이름을 지정하고 **[!UICONTROL 만들기]**&#x200B;를 클릭합니다.

   ![](assets/add-person-to-blocklist-3.png)

1. 당신이 당신의 스마트 목록에 추가하려는 모든 사람들을 추가 차단 목록에 추가하다.

   ![](assets/add-person-to-blocklist-4.png)

   >[!NOTE]
   >
   >차단 목록 중인 사용자는 운영 이메일을 받지 않습니다.

1. 프로그램으로 돌아갑니다.

   ![](assets/add-person-to-blocklist-5.png)

1. **[!UICONTROL 새로 만들기]**&#x200B;를 클릭하고 **[!UICONTROL 새 스마트 캠페인]**&#x200B;을 선택합니다.

   ![](assets/add-person-to-blocklist-6.png)

1. 새 스마트 캠페인에 이름을 지정합니다. **[!UICONTROL 만들기]**&#x200B;를 클릭합니다.

   ![](assets/add-person-to-blocklist-7.png)

1. **[!UICONTROL 스마트 목록 구성원]**&#x200B;을(를) 끌어다 놓습니다.

   ![](assets/add-person-to-blocklist-8.png)

1. 방금 만든 스마트 목록을 선택합니다.

   ![](assets/add-person-to-blocklist-9.png)

1. **[!UICONTROL 흐름]** 탭을 클릭합니다. **[!UICONTROL 데이터 값 변경]** 흐름 작업을 끌어서 놓습니다.

   ![](assets/add-person-to-blocklist-10.png)

1. **[!UICONTROL 특성]** 드롭다운에서 **[!UICONTROL 나열된 블록]**&#x200B;을(를) 선택하고 **[!UICONTROL 새 값]**&#x200B;을(를) **[!UICONTROL true]**(으)로 설정합니다.

   ![](assets/add-person-to-blocklist-11.png)

1. **[!UICONTROL 일정]** 탭을 클릭하고 **[!UICONTROL 한 번 실행]**&#x200B;을 선택합니다.

   ![](assets/add-person-to-blocklist-12.png)

1. **[!UICONTROL 지금 실행]**&#x200B;을 선택하고 **[!UICONTROL 실행]**&#x200B;을 클릭합니다.

   ![](assets/add-person-to-blocklist-13.png)

1. **[!UICONTROL 실행]**&#x200B;을 다시 클릭합니다.

   ![](assets/add-person-to-blocklist-14.png)

이러한 사용자는 더 이상 이메일을 받지 않습니다.

>[!TIP]
>
>다음에 차단 목록에 추가하다 가능 특성이 있는 모든 사용자에 대해 **나열된 블록이 true**&#x200B;인 **데이터 값 변경**&#x200B;을 사용하여 [캠페인 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md){target="_blank"}를 만듭니다.
