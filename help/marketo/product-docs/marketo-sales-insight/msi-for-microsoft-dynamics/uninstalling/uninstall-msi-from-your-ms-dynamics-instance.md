---
unique-page-id: 37355600
description: MS Dynamics 인스턴스에서 MSI 제거 - Marketo 문서 - 제품 설명서
title: MS Dynamics 인스턴스에서 MSI 제거
exl-id: 86e8dbc9-236f-42ad-96e8-cdb1b4c3bed2
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 0%

---

# MS Dynamics 인스턴스에서 MSI 제거 {#uninstall-msi-from-your-ms-dynamics-instance}

MS Dynamics 인스턴스에서 MSI를 제거하려면 Marketo 및 MS Dynamics 모두에서 단계를 수행해야 합니다.

>[!PREREQUISITES]
>
>[전역 MS Dynamics 동기화 비활성화](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/uninstalling/disable-global-ms-dynamics-sync.md)

1. Marketo에서 **관리자**&#x200B;를 클릭합니다.

   ![](assets/one-1.png)

1. **판매 인사이트**&#x200B;를 클릭합니다.

   ![](assets/six.png)

1. **필드 동기화 편집**&#x200B;을 클릭합니다.

   ![](assets/seven.png)

1. **동기화 비활성화** 확인란을 선택하고 **저장**&#x200B;을 클릭합니다.

   >[!NOTE]
   >
   >필드 동기화를 비활성화하기 전에 [전역 MS Dynamics 동기화를 비활성화](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/uninstalling/disable-global-ms-dynamics-sync.md)하십시오.

   ![](assets/eight.png)

## MS Dynamics 인스턴스에서는 다음 단계가 수행됩니다. {#the-following-steps-take-place-in-your-ms-dynamics-instance}

1. **고급 설정**&#x200B;을 클릭합니다.

1. **솔루션**&#x200B;을 클릭합니다.

1. **Marketo Sales Insight**&#x200B;를 선택하고 삭제 아이콘을 클릭합니다.

1. 제거 솔루션 모달이 나타나면 **확인**&#x200B;을 클릭합니다.

   MS Dynamics 솔루션을 완전히 제거하는 데 일반적으로 약 20분이 소요됩니다. 그러나 큰 MS Dynamics 인스턴스가 있는 경우 시간이 조금 더 걸릴 수 있습니다.

   >[!NOTE]
   >
   >MSI를 제거하면 글로벌 MS Dynamics 동기화를 켜야 합니다.
