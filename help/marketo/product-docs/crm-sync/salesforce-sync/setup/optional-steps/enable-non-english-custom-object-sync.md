---
unique-page-id: 4719302
description: Marketo 동기화 사용자가 영어가 아닌 언어를 사용할 때 사용자 지정 개체 동기화를 활성화하는 방법을 알아봅니다. Salesforce에서 동기화 사용자 언어를 영어로 설정하고 스키마를 새로 고칩니다.
title: 영어 이외의 사용자 정의 오브젝트 동기화 활성화
exl-id: 5d1c5b52-5323-4f68-847b-7d24e6acd6c4
feature: Salesforce Integration
TQID: https://experienceleague.adobe.com/kPzDEdjDnDAvuJmCtPj0I2Lfl63Lset00t-LwB8DDhI
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
source-git-commit: 67c57a9162946c4b9c424ab3fd445b70e90b530a
workflow-type: tm+mt
source-wordcount: 176
ht-degree: 10%

---

# 영어 이외의 사용자 정의 오브젝트 동기화 활성화 {#enable-non-english-custom-object-sync}

Marketo 동기화 사용자가 영어 이외의 언어로 설정된 경우 사용자 지정 개체 동기화를 활성화하려고 하면 오류가 발생할 수 있습니다.

![](assets/image2014-12-10-13-3a17-3a51.png)

## 해결 방법 {#how-to-fix}

1. Marketo 동기화 사용자를 사용하여 [!DNL Salesforce]에 로그인합니다.

   ![](assets/image2014-12-10-13-3a18-3a1.png)

1. 사용자 이름 드롭다운을 클릭하고 **[!UICONTROL Setup]**&#x200B;을(를) 선택합니다.

   ![](assets/image2014-12-10-13-3a18-3a11.png)

1. **[!UICONTROL Personal Information]**&#x200B;에서 **[!UICONTROL My Personal Information]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a18-3a22.png)

1. **[!UICONTROL Edit]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-10-13-3a18-3a32.png)

1. **[!UICONTROL Language]**&#x200B;을(를) **[!UICONTROL English]**(으)로 변경합니다.

   ![](assets/image2014-12-10-13-3a18-3a45.png)

1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-10-13-3a18-3a55.png)

1. [Adobe 계정 프로필](https://account.adobe.com/kr/profile){target="_blank"}에서 **[!UICONTROL Preferred languages]**(으)로 스크롤하고 첫 번째 언어가 영어로 설정되어 있는지 확인하십시오.

   ![](assets/enable-non-english-custom-object-sync-step-6.5.png)

1. Marketo Engage에서 **[!UICONTROL Admin]** > **[!UICONTROL Salesforce]** > **[!UICONTROL Objects]**(으)로 이동합니다. **[!UICONTROL Refresh Schema]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-10-13-3a19-3a6.png)

1. 이렇게 하면 오브젝트 목록이 영어로 가져옵니다. 선택한 개체를 선택하고 **[!UICONTROL Enable Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a19-3a16.png)

1. 이제 사용자 지정 개체가 활성화되고 동기화됩니다.

   ![](assets/image2014-12-10-13-3a19-3a26.png)

1. [!DNL Salesforce]&#x200B;(으)로 돌아가서 위의 단계에 따라 동기화 사용자를 기본 언어로 다시 변경합니다.

>[!NOTE]
>
>마지막으로 스키마를 새로 고쳐 언어로 개체를 다시 가져옵니다.
