---
unique-page-id: 4719302
description: 영어가 아닌 사용자 지정 개체 동기화 활성화 - Marketo 문서 - 제품 설명서
title: 비영어 사용자 지정 개체 동기화 활성화
exl-id: 5d1c5b52-5323-4f68-847b-7d24e6acd6c4
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '138'
ht-degree: 1%

---

# 비영어 사용자 지정 개체 동기화 활성화 {#enable-non-english-custom-object-sync}

Marketo 동기화 사용자가 영어 이외의 언어로 설정된 경우 사용자 지정 개체 동기화를 활성화하려고 하면 오류가 발생할 수 있습니다.

## 오류 {#the-error}

![](assets/image2014-12-10-13-3a17-3a51.png)

## 둘러보기 {#getting-around-it}

1. Marketo 동기화 사용자를 사용하여 [!DNL Salesforce]에 로그인합니다.

   ![](assets/image2014-12-10-13-3a18-3a1.png)

1. 사용자 이름 아래에서 **[!UICONTROL Setup]**(으)로 이동합니다.

   ![](assets/image2014-12-10-13-3a18-3a11.png)

1. **[!UICONTROL Personal Information]**&#x200B;에서 **[!UICONTROL My Personal Information]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a18-3a22.png)

1. **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a18-3a32.png)

1. **[!UICONTROL Language]**&#x200B;을(를) **[!UICONTROL English]**(으)로 변경합니다.

   ![](assets/image2014-12-10-13-3a18-3a45.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a18-3a55.png)

1. Marketo으로 돌아가서 **[!UICONTROL Admin]** > **[!UICONTROL Salesforce]** > **[!UICONTROL Objects]**&#x200B;에서 **[!UICONTROL Refresh Schema]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a19-3a6.png)

1. 그러면 개체 목록이 영어로 당겨집니다. 이제 선택한 개체를 선택하고 **[!UICONTROL Enable Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a19-3a16.png)

1. 이제 사용자 지정 개체가 활성화되고 동기화됩니다.

   ![](assets/image2014-12-10-13-3a19-3a26.png)

1. 이제 [!DNL Salesforce]&#x200B;(으)로 돌아가서 위의 단계를 사용하여 동기화 사용자를 기본 언어로 다시 변경합니다.

>[!NOTE]
>
>마지막으로 스키마를 새로 고쳐 언어에서 개체를 다시 가져오는 것을 잊지 마십시오.
