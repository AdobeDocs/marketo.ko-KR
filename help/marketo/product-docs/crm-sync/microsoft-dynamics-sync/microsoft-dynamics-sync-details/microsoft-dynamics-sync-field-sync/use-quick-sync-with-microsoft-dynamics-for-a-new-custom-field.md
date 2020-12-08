---
unique-page-id: 10098379
description: Microsoft Dynamics와 빠른 동기화를 사용하여 새로운 사용자 정의 필드 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics와 빠른 동기화를 사용하여 새 사용자 지정 필드 사용
translation-type: tm+mt
source-git-commit: 313266a67243f0c70c25010cb4825efb7f3db0ab
workflow-type: tm+mt
source-wordcount: '355'
ht-degree: 0%

---


# Microsoft Dynamics와 빠른 동기화를 사용하여 새 사용자 지정 필드 사용 {#use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field}

마케팅 또는 영업 팀이 새로운 필드를 원합니다. 또는 초기 필드 선택에 하나 잊으셨을 수도 있습니다. 또는 요구 사항이 변경되었습니다. 빠른 동기화를 사용하여 특정 필드를 다시 동기화할 수 있습니다.

일반적으로 빠른 동기화를 사용하여 새 필드를 추가하고 값을 새로 고칩니다. 하지만 기존 필드를 동기화할 경우가 있습니다. 업데이트된 날짜 또는 만들어진 날짜 범위를 기반으로 필드 동기화를 제한할 수 있습니다. 자세한 내용은 [아래 고급](#Advanced_Sync_Options) 동기화 옵션을 참조하십시오.

빠른 동기화는 null 값을 동기화할 수 있습니다. 예를 들어 값 A와 B를 사용하고 Dynamics에서 B 값을 null로 변경하면 null 값이 Marketing에 동기화됩니다.

## 모든 레코드에 대한 빠른 동기화 {#quick-sync-for-all-records}

빠른 동기화를 사용하여 새 필드를 재동기화하는 방법을 설명합니다.

1. Marketing에서 관리를 **클릭합니다**.

   ![](assets/image2016-8-19-11-3a14-3a5.png)

1. ** Microsoft Dynamics**를 클릭합니다.

   ![](assets/image2016-8-19-11-3a15-3a8.png)

1. 필드 동기화 세부 정보에서 편집을 **클릭합니다**.

   ![](assets/image2016-8-19-11-3a16-3a22.png)

1. 빠르게 동기화할 필드를 선택하고 저장을 **클릭합니다**.

   ![](assets/image2016-8-25-15-3a26-3a11.png)

   >[!NOTE]
   >
   >여러 엔티티에서 필드를 선택할 수 있습니다.

1. 동기화가 완료되면 알림을 받게 됩니다.

   ![](assets/field-sync-update-notification.png)

   >[!CAUTION]
   >
   >동기화는 다른 동기들과 나란히 실행되며 데이터베이스 크기에 따라 완료하는 데 시간이 오래 걸릴 수 있습니다. 필드가 동기화 대기열에 있으면 선택 취소할 수 없습니다.

## 고급 동기화 옵션 {#advanced-sync-options}

기존 필드를 동기화하지만 제한된 데이터 세트에서만 동기화하려면 어떻게 해야 합니까? 방법

1. 기존 필드의 확인란을 선택 취소합니다. 저장을 **클릭합니다**.

   ![](assets/image2016-8-25-16-3a16-3a32.png)

1. 팝업을 다시 열고 필드를 다시 선택합니다.

   ![](assets/select-field-reselect-hand.png)

1. 고급 **동기화를 클릭합니다**.

   ![](assets/image2016-8-25-15-3a52-3a9.png)

1. **업데이트 **를 선택하고 날짜 선택기를 사용하여 날짜 범위를 선택합니다. 저장을 **클릭합니다**.

   ![](assets/image2016-8-25-16-3a0-3a3.png)

   2016년 8월 19일과 16년 9월 19일 사이에 업데이트된 레코드만 필드에 대해 빠른 동기화됩니다.

## 동기화되지 않은 필드 수정 {#fixing-out-of-sync-fields}

Dynamics 및 Marketing 필드가 동기화되지 않은 드문 경우에는 빠르고 손쉽게 다시 동기화할 수 있습니다.

1. 필드를 선택 취소하고 **저장을 클릭합니다**.

   ![](assets/image2016-8-25-16-3a16-3a32-1.png)

1. 필드를 다시 선택하고 저장을 **클릭합니다**. 그게 다예요

   ![](assets/image2016-8-25-16-3a20-3a45.png)

   그거 고쳐야지

