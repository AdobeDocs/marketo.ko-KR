---
unique-page-id: 4719297
description: 사용자 지정 개체 동기화 활성화/비활성화 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 동기화 활성화/비활성화
exl-id: f17d9135-b33e-48c0-9220-131fb437e9e5
feature: Salesforce Integration
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---

# 사용자 지정 개체 동기화 활성화/비활성화 {#enable-disable-custom-object-sync}

Salesforce 인스턴스에서 만든 사용자 지정 개체도 Marketo의 일부일 수 있습니다. 설정 방법은 다음과 같습니다.

## 사용자 지정 개체 동기화 활성화/비활성화 {#enable-disable-custom-object-sync-1}

>[!NOTE]
>
>관리자 권한이 필요합니다.

1. 클릭 **관리자**.

   ![](assets/one.png)

1. 데이터베이스 관리 메뉴에서 **Salesforce 개체 동기화**.

   ![](assets/two-2.png)

1. 첫 번째 사용자 지정 개체인 경우 **동기화 스키마.** 그렇지 않으면 클릭 **스키마 새로 고침** 최신 버전을 확인합니다.

   ![](assets/image2014-12-10-10-3a14-3a44.png)

1. 전역 동기화가 실행 중인 경우 다음을 클릭하여 비활성화해야 합니다. **전역 동기화를 사용하지 않도록 설정합니다.**

   ![](assets/image2014-12-10-10-3a14-3a54.png)

   >[!NOTE]
   >
   >Salesforce 사용자 지정 개체 스키마의 동기화에 몇 분 정도 걸릴 수 있습니다.

1. 클릭 **스키마 새로 고침**.

   ![](assets/image2014-12-10-10-3a15-3a7.png)

1. 동기화할 개체를 선택하고 **동기화 활성화**.

   >[!TIP]
   >
   >Marketo은 Salesforce의 잠재 고객, 연락처 또는 계정 개체와 직접 관계가 있는 경우에만 사용자 지정 개체를 동기화할 수 있습니다.

   ![](assets/image2014-12-10-10-3a15-3a30.png)

1. 클릭 **동기화 활성화** 다시.

   ![](assets/image2014-12-10-10-3a15-3a40.png)

1. 로 돌아가기 **Salesforce** tab 키를 누른 다음 클릭 **동기화 활성화**.

   ![](assets/image2014-12-10-10-3a15-3a49.png)

## 사용자 지정 개체 사용 {#using-your-custom-objects}

>[!NOTE]
>
>트리거가 있는 스마트 캠페인에서는 사용자 지정 개체를 사용할 수 없습니다.

1. 스마트 목록에서 **영업 기회 있음** 필터링 및 다음으로 설정 **true**.

   ![](assets/image2015-8-26-9-3a39-3a28.png)

1. 그런 다음 필터 제약 조건을 사용하여 포커스를 좁힙니다.

   ![](assets/image2015-8-24-14-3a18-3a53.png)

   훌륭합니다! 이제 스마트 캠페인 및 스마트 목록에서 이 사용자 지정 개체의 데이터를 사용할 수 있습니다.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md)
