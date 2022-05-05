---
description: 사용자 지정 개체 동기화 활성화/비활성화 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 동기화 활성화/비활성화
exl-id: 01417fb6-70f5-449b-ad56-42e1c0b2ff68
source-git-commit: 2ce44b7c44517a6fdb3f616a3d69b25158ea4ec9
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---

# 사용자 지정 개체 동기화 활성화/비활성화 {#enable-disable-custom-object-sync}

Vec CRM 인스턴스에서 만든 사용자 지정 개체도 Marketo Engage의 일부일 수 있습니다. 설정 방법은 다음과 같습니다.

## 사용자 지정 개체 동기화 활성화 또는 비활성화 {#enable-or-disable-the-custom-object-sync}

>[!NOTE]
>
>**관리자 권한이 필요합니다.**

1. Marketo에서 **관리**, 그런 다음 **Veva 개체 동기화**.

   ![](assets/enable-disable-custom-object-sync-1.png)

1. 첫 번째 사용자 지정 개체인 경우 스키마 동기화를 클릭합니다. 없는 경우 을 클릭합니다. **스키마 새로 고침** 최신 정보를 얻을 수 있습니다.

   ![](assets/enable-disable-custom-object-sync-2.png)

1. 글로벌 동기화가 실행 중인 경우 **전역 동기화 비활성화**.

   ![](assets/enable-disable-custom-object-sync-3.png)

   >[!NOTE]
   >
   >Veeva 사용자 지정 개체 스키마를 동기화하는 데 몇 분 정도 걸릴 수 있습니다.

1. 클릭 **스키마 새로 고침**.

   ![](assets/enable-disable-custom-object-sync-4.png)

동기화할 개체를 선택하고 동기화 사용을 클릭합니다.

![](assets/enable-disable-custom-object-sync-5.png)

>[!TIP]
>
>Marketo은 Vec CRM의 연락처 또는 계정 개체와 직접 관계가 있는 경우에만 사용자 지정 개체를 동기화할 수 있습니다.

1. 클릭 **동기화 활성화** 다시 한 번

   ![](assets/enable-disable-custom-object-sync-6.png)

1. Veva 탭으로 돌아가서 를 클릭합니다. **동기화 활성화**.

   ![](assets/enable-disable-custom-object-sync-7.png)

## 사용자 정의 개체 사용 {#using-your-custom-objects}

>[!NOTE]
>
>트리거가 있는 스마트 캠페인에서는 사용자 지정 개체를 사용할 수 없습니다.

1. Smart List에서 &quot;Has Opportunity&quot; 필터를 드래그하고 **True**.

   ![](assets/enable-disable-custom-object-sync-8.png)

1. 선택적으로 필터 제약 조건을 사용하여 포커스 범위를 좁힐 수 있습니다.

   ![](assets/enable-disable-custom-object-sync-9.png)

훌륭해요! 이제 스마트 캠페인 및 스마트 목록에서 이 사용자 지정 개체의 데이터를 사용할 수 있습니다.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target=&quot;_blank&quot;}
