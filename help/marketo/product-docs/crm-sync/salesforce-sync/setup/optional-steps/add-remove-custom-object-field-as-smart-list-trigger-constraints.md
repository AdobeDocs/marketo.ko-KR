---
unique-page-id: 4719300
description: 사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거
exl-id: 639e73eb-9a8c-4b10-8e97-892abf5c5db0
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 0%

---

# 사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거 {#add-remove-custom-object-field-as-smart-list-trigger-constraints}

Marketo에서는 Salesforce 사용자 지정 개체 동기화를 통해 세밀하게 제어할 수 있습니다. 이를 통해 사용자 지정 개체 필터에서 제한으로 사용할 수 있는 필드를 선택하고 스마트 캠페인에서 트리거로 사용할 수 있습니다.

>[!NOTE]
>
>**관리 권한 필요**

1. 클릭 **관리자.**

   ![](assets/image2014-12-10-13-3a9-3a47.png)

1. 클릭 **관리** 그리고 **Salesforce 개체 동기화.**

   ![](assets/image2015-12-11-15-3a11-3a41.png)

1. **Salesforce 개체 동기화** 왼쪽 열에 나타납니다.

   ![](assets/image2015-12-11-15-3a15-3a15.png)

1. 수정할 객체를 선택합니다.

   ![](assets/image2014-12-10-13-3a10-3a11.png)

1. 클릭 **표시 필드 편집**.

   >[!TIP]
   >
   >만약 **표시 필드 편집** 단추가 회색으로 표시되어 있고 개체가 현재 스마트 목록 또는 스마트 캠페인에서 사용 중입니다. 계속하려면 모든 연결을 제거하십시오.

   ![](assets/image2014-12-10-13-3a10-3a25.png)

1. 전역 동기화가 활성화된 경우 **전역 동기화 비활성화**.

   ![](assets/image2014-12-10-13-3a10-3a36.png)

1. 필요한 필터/트리거 제한 옆에 있는 상자를 선택하고 을(를) 클릭합니다 **저장**.

   ![](assets/image2014-12-10-13-3a10-3a47.png)

   >[!NOTE]
   >
   >모든 필드는 필터에 대한 제한이 되도록 기본적으로 선택됩니다.

1. 을(를) 클릭합니다. **필드** 탭을 클릭하여 변경 사항을 확인합니다.

   ![](assets/image2014-12-10-13-3a10-3a56.png)

   >[!NOTE]
   >
   >글로벌 동기화를 다시 활성화하는 것을 잊지 마십시오!

와! 이제 스마트 목록과 스마트 캠페인의 기능이 더욱 향상되었습니다.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 동기화 활성화/비활성화](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-custom-object-sync.md)
