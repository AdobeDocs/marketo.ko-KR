---
unique-page-id: 10094188
description: 사용자 지정 개체 승인 - Marketo 문서 - 제품 설명서
title: 사용자 정의 오브젝트 승인
exl-id: 8bae94df-91fe-4722-8c75-c26df882c65d
feature: Custom Objects
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 8%

---

# 사용자 정의 오브젝트 승인 {#approve-a-custom-object}

사용자 지정 개체를 사용하려면 먼저 승인해야 합니다. 새 사용자 지정 개체와 편집한 개체의 프로세스는 약간 다릅니다.

## 새 사용자 지정 개체 승인 {#approve-a-new-custom-object}

완전히 새로운 사용자 지정 개체를 만들었습니다. 승인 방법은 다음과 같습니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/approve-a-custom-object-1.png)

1. **[!UICONTROL Marketo Custom Objects]**&#x200B;를 클릭합니다.

   ![](assets/approve-a-custom-object-2.png)

1. 초안 상태의 객체를 선택합니다.

   ![](assets/approve-a-custom-object-3.png)

1. **[!UICONTROL Custom Object Actions]** 드롭다운을 클릭하고 **[!UICONTROL Approve Object]**&#x200B;를 선택합니다.

   ![](assets/approve-a-custom-object-4.png)

1. 상태가 [!UICONTROL Approved]&#x200B;(으)로 변경됩니다.

   ![](assets/approve-a-custom-object-5.png)

   >[!NOTE]
   >
   >_일대다 구조_&#x200B;에서 사용되는 사용자 지정 개체에는 최소 하나 이상의 중복 제거 필드, 연결 필드, 연결된 개체 이름 및 연결된 필드 이름이 있어야 승인할 수 있습니다.
   >
   >_다대다 구조_ **에서 사용되는 사용자 지정 개체는 승인할 때 연결 필드, 연결된 개체 이름 또는 연결된 필드 이름이 필요하지 않습니다**(매개 개체에 있기 때문).
   >
   >_중간 개체_(으)로 사용되는 사용자 지정 개체에는 링크 필드, 연결된 개체 이름 및 연결된 필드 이름이 필요하지만 **중복 제거 필드가 필요하지 않습니다**.
   >
   >자세한 내용은 [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)를 참조하십시오.

됐습니다. 이제 캠페인에서 사용할 필터 및 트리거의 제한 내에서 사용자 지정 개체를 선택할 수 있습니다.

## 편집된 사용자 지정 개체 승인 {#approve-an-edited-custom-object}

승인된 사용자 지정 개체를 편집한 후 사용자 지정 개체를 승인됨 상태로 되돌리려면 초안을 승인해야 합니다.

1. 이미 승인된 사용자 지정 개체를 편집하면 [!UICONTROL Approved with Draft] 상태가 표시됩니다.

   ![](assets/approve-a-custom-object-6.png)

1. 초안을 승인할 준비가 되면 **[!UICONTROL Custom Object Actions]** 드롭다운을 클릭하고 **[!UICONTROL Approve Object]**&#x200B;을(를) 선택합니다.

   ![](assets/approve-a-custom-object-7.png)

1. 미리보기에는 초안에서 변경된 항목이 표시됩니다. **[!UICONTROL Approve]**&#x200B;를 클릭합니다.

   ![](assets/approve-a-custom-object-8.png)
