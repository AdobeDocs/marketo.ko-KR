---
unique-page-id: 2360327
description: 할당 규칙을 사용하여 개인 파티션 할당 - Marketo 문서 - 제품 설명서
title: 할당 규칙을 사용하여 개인 분할 영역 지정
exl-id: 6b54dcb7-8da9-466b-b153-099ebcb96424
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---

# 할당 규칙을 사용하여 개인 분할 영역 지정 {#assigning-person-partitions-with-assignment-rules}

>[!NOTE]
>
>**관리 권한 필요**

>[!PREREQUISITES]
>
>[개인 파티션 만들기](/help/marketo/product-docs/administration/workspaces-and-person-partitions/create-a-person-partition.md)

개인 파티션을 사용할 때는 할당 규칙을 설정하여 CRM에서 만든 사람을 각 파티션으로 라우팅합니다.

>[!NOTE]
>
>CRM과 SOAP API를 통해 Marketo에서 만든 사용자만 할당 규칙이 적용됩니다.

1. 관리에서 작업 공간 및 파티션을 클릭합니다.

   ![](assets/image2014-9-17-10-3a32-3a55.png)

1. 아래에 **사람 파티션** 탭에서 **할당 규칙**.

   ![](assets/two-6.png)

1. 클릭 **선택 추가** 사용자를 개인 파티션으로 라우팅하기 위한 조건을 추가하려면

   ![](assets/three-6.png)

1. 조건을 빌드해야 하는 필드를 선택합니다.

   ![](assets/four-5.png)

1. 선택 연산자를 선택하고 값을 입력합니다.

   ![](assets/five-1.png)

1. 조건을 충족하는 사람이 속할 사람 파티션을 선택합니다.

   ![](assets/six-1.png)

   >[!NOTE]
   >
   >원하는 만큼 선택할 수 있습니다.

1. 클릭 **저장**.

   ![](assets/seven.png)

여기 있어요! 개인 파티션을 사용자로 채우는 규칙을 할당했습니다.

>[!NOTE]
>
>이전 조건이 충족되지 않으면 기본 선택 사항이 적용됩니다.
