---
unique-page-id: 10098379
description: 새 사용자 정의 필드 - Microsoft 문서 - 제품 설명서에 대해 Marketo Dynamics와 빠른 동기화 사용
title: 새 사용자 정의 필드에 대해 Microsoft Dynamics와 빠른 동기화 사용
exl-id: c98f1443-c0dd-40e1-919b-f8110088b38a
feature: Microsoft Dynamics
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '355'
ht-degree: 0%

---

# 새 사용자 정의 필드에 대해 Microsoft Dynamics와 빠른 동기화 사용 {#use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field}

마케팅 또는 영업 팀이 새 필드를 원합니다. 또는 초기 필드 선택에서 하나를 잊어버렸을 수 있습니다. 또는 요구 사항이 변경되었습니다. 어떤 경우든 빠른 동기화를 사용하여 특정 필드를 다시 동기화할 수 있습니다.

일반적으로 빠른 동기화를 사용하여 새 필드를 추가하고 값을 새로 고칩니다. 그러나 기존 필드를 동기화할 수 있는 경우가 있습니다. 업데이트되거나 생성된 날짜 범위에 따라 필드 동기화를 제한할 수 있습니다. 다음을 참조하십시오 [고급 동기화 옵션](#Advanced_Sync_Options) 자세한 내용은 아래를 참조하십시오.

빠른 동기화는 null 값을 동기화할 수 있습니다. 예를 들어 값 A와 B를 사용하고 Dynamics에서 B 값을 null로 변경하면 null 값이 Marketo에 동기화됩니다.

## 모든 레코드에 대한 빠른 동기화 {#quick-sync-for-all-records}

빠른 동기화를 사용하여 새 필드를 재동기화하는 방법은 다음과 같습니다.

1. Marketo에서 **관리자**.

   ![](assets/image2016-8-19-11-3a14-3a5.png)

1. 클릭 **Microsoft Dynamics**.

   ![](assets/image2016-8-19-11-3a15-3a8.png)

1. 필드 동기화 세부 정보에서 **편집**.

   ![](assets/image2016-8-19-11-3a16-3a22.png)

1. 빠르게 동기화할 필드를 선택하고 **저장**.

   ![](assets/image2016-8-25-15-3a26-3a11.png)

   >[!NOTE]
   >
   >여러 엔티티에서 필드를 선택할 수 있습니다.

1. 동기화가 완료되면 알림을 받게 됩니다.

   ![](assets/field-sync-update-notification.png)

   >[!CAUTION]
   >
   >동기화는 다른 동기화와 나란히 실행되며 데이터베이스 크기에 따라 완료하는 데 시간이 오래 걸릴 수 있습니다. 동기화 큐에 필드가 있으면 선택을 해제할 수 없습니다.

## 고급 동기화 옵션 {#advanced-sync-options}

기존 필드를 동기화하되, 제한된 데이터 세트에만 동기화하려면 어떻게 해야 합니까? 방법은 다음과 같습니다.

1. 기존 필드에 대한 확인란의 선택을 취소합니다. 클릭 **저장**.

   ![](assets/image2016-8-25-16-3a16-3a32.png)

1. 팝업을 다시 열고 필드를 다시 선택합니다.

   ![](assets/select-field-reselect-hand.png)

1. 클릭 **고급 동기화**.

   ![](assets/image2016-8-25-15-3a52-3a9.png)

1. 선택 **업데이트됨** 날짜 선택기를 사용하여 날짜 범위를 선택합니다. 클릭 **저장**.

   ![](assets/image2016-8-25-16-3a0-3a3.png)

   2016년 8월 19일과 2016년 9월 19일 사이에 업데이트된 레코드만 필드에 대해 빠른 동기화됩니다.

## 동기화 필드 문제 해결 {#fixing-out-of-sync-fields}

Dynamics와 Marketo 필드가 동기화되지 않는 드문 경우 빠르고 간편하게 다시 동기화할 수 있습니다.

1. 필드 선택을 취소하고 클릭 **저장**.

   ![](assets/image2016-8-25-16-3a16-3a32-1.png)

1. 필드를 다시 선택하고 **저장**. 그게 다야!

   ![](assets/image2016-8-25-16-3a20-3a45.png)

   그럼 고쳐지겠네!
