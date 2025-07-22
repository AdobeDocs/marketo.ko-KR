---
unique-page-id: 37355600
description: MS [!DNL Dynamics] 인스턴스 - Marketo 문서 - 제품 설명서에서 MSI 제거
title: MS [!DNL Dynamics] 인스턴스에서 MSI 제거
exl-id: 86e8dbc9-236f-42ad-96e8-cdb1b4c3bed2
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '131'
ht-degree: 3%

---

# MS [!DNL Dynamics] 인스턴스에서 MSI 제거 {#uninstall-msi-from-your-ms-dynamics-instance}

MS [!DNL Dynamics] 인스턴스에서 MSI를 제거하려면 Marketo 및 MS [!DNL Dynamics]에서 모두 단계를 수행해야 합니다.

>[!PREREQUISITES]
>
>[글로벌 MS 비활성화 [!DNL Dynamics] 동기화](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/uninstalling/disable-global-ms-dynamics-sync.md)

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/one-1.png)

1. **[!UICONTROL Sales Insight]**&#x200B;을(를) 클릭합니다.

   ![](assets/six.png)

1. **[!UICONTROL Edit Field Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/seven.png)

1. **[!UICONTROL Disable Sync]** 확인란을 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   >[!NOTE]
   >
   >필드 동기화를 비활성화하기 전에 [전역 MS Dynamics 동기화를 비활성화](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/uninstalling/disable-global-ms-dynamics-sync.md)하십시오.

   ![](assets/eight.png)

## MS [!DNL Dynamics] 인스턴스에서 다음 단계를 수행합니다. {#the-following-steps-take-place-in-your-ms-dynamics-instance}

1. **[!UICONTROL Advanced Settings]**&#x200B;을(를) 클릭합니다.

1. **[!UICONTROL Solutions]**&#x200B;을(를) 클릭합니다.

1. **[!UICONTROL Marketo Sales Insight]**&#x200B;을(를) 선택하고 삭제 아이콘을 클릭합니다.

1. 제거 솔루션 모달 팝업이 나타나면 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   MS [!DNL Dynamics] 솔루션을 완전히 제거하는 데 보통 약 20분이 소요됩니다. 그러나 큰 MS [!DNL Dynamics] 인스턴스가 있으면 시간이 조금 더 걸릴 수 있습니다.

   >[!NOTE]
   >
   >MSI를 제거하면 글로벌 MS [!DNL Dynamics] 동기화를 켜야 합니다.
