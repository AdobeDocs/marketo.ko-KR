---
unique-page-id: 10094188
description: 사용자 지정 개체 승인 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 승인
exl-id: 8bae94df-91fe-4722-8c75-c26df882c65d
source-git-commit: 4a33b192cc22550c75769b383e261ac0a86e7ddb
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---

# 사용자 지정 개체 승인 {#approve-a-custom-object}

사용자 지정 개체를 사용하려면 먼저 승인해야 합니다. 새 사용자 지정 개체와 편집한 개체의 프로세스는 약간 다릅니다.

## 새 사용자 지정 개체 승인 {#approve-a-new-custom-object}

완전히 새로운 사용자 지정 개체를 만들었습니다. 승인 방법은 다음과 같습니다.

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/approve-a-custom-object-1.png)

1. 클릭 **[!UICONTROL Marketo 사용자 지정 개체]**.

   ![](assets/approve-a-custom-object-2.png)

1. 초안 상태의 객체를 선택합니다.

   ![](assets/approve-a-custom-object-3.png)

1. 다음을 클릭합니다. **[!UICONTROL 사용자 지정 개체 작업]** 드롭다운 및 선택 **[!UICONTROL 개체 승인]**.

   ![](assets/approve-a-custom-object-4.png)

1. 상태가 (으)로 변경됩니다. [!UICONTROL 승인됨].

   ![](assets/approve-a-custom-object-5.png)

   >[!NOTE]
   >
   >에 사용되는 사용자 지정 개체 _일대다 구조_ 최소 하나 이상의 중복 제거 필드, 링크 필드, 연결된 개체 이름 및 연결된 필드 이름이 있어야 승인할 수 있습니다.
   >
   >에 사용되는 사용자 지정 개체 _다대다 구조_ **다음과 같지 않음** 승인할 때 링크 필드, 연결된 개체 이름 또는 연결된 필드 이름이 필요합니다(중간 개체에 있기 때문).
   >
   >다음으로 사용되는 사용자 지정 개체 _매개체_ 링크 필드, 연결된 개체 이름 및 연결된 필드 이름이 필요하지만 **다음과 같지 않음** 중복 제거 필드가 필요합니다.
   >
   >다음을 참조하십시오 [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) 추가 정보.

다 됐습니다! 이제 캠페인에서 사용할 필터 및 트리거의 제한 내에서 사용자 지정 개체를 선택할 수 있습니다.

## 편집된 사용자 지정 개체 승인 {#approve-an-edited-custom-object}

승인된 사용자 지정 개체를 편집한 후 사용자 지정 개체를 승인됨 상태로 되돌리려면 초안을 승인해야 합니다.

1. 이미 승인된 사용자 지정 개체를 편집하면 [!UICONTROL 초안으로 승인됨] 주.

   ![](assets/approve-a-custom-object-6.png)

1. 초안을 승인할 준비가 되면 **[!UICONTROL 사용자 지정 개체 작업]** 드롭다운 및 선택 **[!UICONTROL 개체 승인]**.

   ![](assets/approve-a-custom-object-7.png)

1. 미리보기에는 초안에서 변경된 항목이 표시됩니다. 클릭 **[!UICONTROL 승인]**.

   ![](assets/approve-a-custom-object-8.png)
