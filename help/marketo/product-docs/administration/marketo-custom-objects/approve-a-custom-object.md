---
unique-page-id: 10094188
description: 사용자 지정 개체 승인 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 승인
exl-id: 8bae94df-91fe-4722-8c75-c26df882c65d
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---

# 사용자 지정 개체 승인 {#approve-a-custom-object}

사용자 지정 개체를 사용하려면 먼저 승인해야 합니다. 새 사용자 정의 객체와 편집한 객체에 대해서는 프로세스가 약간 다릅니다.

## 새 사용자 지정 개체 승인 {#approve-a-new-custom-object}

완전히 새로운 사용자 지정 개체를 만들었습니다. 여기 승인 방법이 있습니다.

1. Admin에서 **Marketo 사용자 지정 개체** 초안 상태의 객체를 선택합니다.

   ![](assets/one.png)

1. 을(를) 클릭합니다. **사용자 지정 개체 작업** 드롭다운 및 선택 **개체 승인**.

   ![](assets/two.png)

1. 상태가 승인됨으로 변경됩니다.

   ![](assets/three.png)

   >[!NOTE]
   >
   >에 사용되는 사용자 지정 개체입니다 _일대다 구조_ 승인하려면 데이터 중복 제거 필드, 링크 필드, 연결된 개체 이름 및 연결된 필드 이름이 하나 이상 있어야 합니다.
   >
   >에 사용되는 사용자 지정 개체입니다 _다대다 구조_ **does not** 이 필드를 승인할 때(중간 객체에 있으므로) 링크 필드, 링크된 객체 이름 또는 링크된 필드 이름이 필요합니다.
   >
   >로 사용되는 사용자 지정 개체 _중간 객체_ 링크 필드, 연결된 개체 이름 및 연결된 필드 이름이 필요하지만 **does not** 중복 제거 필드가 필요합니다.
   >
   >자세한 내용은 [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) 추가 정보.

됐습니다. 이제 캠페인에서 사용할 필터 및 트리거의 제한에서 사용자 지정 개체를 선택할 수 있습니다.

## 편집된 사용자 지정 개체 승인 {#approve-an-edited-custom-object}

승인된 사용자 지정 개체를 편집한 후 사용자 지정 개체를 승인함 상태로 되돌리려면 초안을 승인해야 합니다.

1. 이미 승인된 사용자 지정 객체를 편집하면 초안으로 승인됨 상태가 표시됩니다.

   ![](assets/four.png)

1. 초안을 승인할 준비가 되면 **사용자 지정 개체 작업** 드롭다운 및 선택 **개체 승인**.

   ![](assets/five-1.png)

1. 미리 보기에는 초안에서 변경된 항목이 표시됩니다. 클릭 **승인**.

   ![](assets/six-1.png)
