---
unique-page-id: 4719297
description: 사용자 지정 개체 동기화 활성화/비활성화 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 동기화 활성화/비활성화
exl-id: f17d9135-b33e-48c0-9220-131fb437e9e5
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---

# 사용자 지정 개체 동기화 활성화/비활성화 {#enable-disable-custom-object-sync}

Salesforce 인스턴스에서 만든 사용자 지정 개체도 Marketo의 일부일 수 있습니다. 설정 방법은 다음과 같습니다.

## 사용자 지정 개체 동기화 활성화/비활성화 {#enable-disable-custom-object-sync-1}

>[!NOTE]
>
>관리 권한이 필요합니다.

1. 클릭 **관리**.

   ![](assets/one.png)

1. 데이터베이스 관리 메뉴에서 **Salesforce 개체 동기화**.

   ![](assets/two-2.png)

1. 첫 번째 사용자 지정 개체인 경우 **스키마 동기화.** 그렇지 않으면 **스키마 새로 고침** 최신 정보를 얻을 수 있습니다.

   ![](assets/image2014-12-10-10-3a14-3a44.png)

1. 글로벌 동기화가 실행 중인 경우 **전역 동기화를 사용하지 않도록 설정합니다.**

   ![](assets/image2014-12-10-10-3a14-3a54.png)

   >[!NOTE]
   >
   >Salesforce 사용자 지정 개체 스키마를 동기화하는 데 몇 분이 걸릴 수 있습니다.

1. 클릭 **스키마 새로 고침**.

   ![](assets/image2014-12-10-10-3a15-3a7.png)

1. 동기화할 개체를 선택하고 **동기화 활성화**.

   >[!TIP]
   >
   >Marketo은 Salesforce의 Lead, Contact 또는 Account 개체와 직접적인 관계가 있는 경우에만 사용자 지정 개체를 동기화할 수 있습니다.

   ![](assets/image2014-12-10-10-3a15-3a30.png)

1. 클릭 **동기화 활성화** 다시 한 번

   ![](assets/image2014-12-10-10-3a15-3a40.png)

1. 로 돌아갑니다. **Salesforce** 탭을 클릭하고 **동기화 활성화**.

   ![](assets/image2014-12-10-10-3a15-3a49.png)

## 사용자 정의 개체 사용 {#using-your-custom-objects}

>[!NOTE]
>
>트리거가 있는 스마트 캠페인에서는 사용자 지정 개체를 사용할 수 없습니다.

1. 스마트 목록에서 **기회 있음** 필터 및 설정 **true**.

   ![](assets/image2015-8-26-9-3a39-3a28.png)

1. 그런 다음 필터 제약 조건을 사용하여 포커스 범위를 좁힙니다.

   ![](assets/image2015-8-24-14-3a18-3a53.png)

   훌륭해요! 이제 스마트 캠페인 및 스마트 목록에서 이 사용자 지정 개체의 데이터를 사용할 수 있습니다.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md)
