---
unique-page-id: 4719297
description: 사용자 지정 개체 동기화 활성화/비활성화 - Marketing To Docs - 제품 설명서
title: 사용자 정의 개체 동기화 활성화/비활성화
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---


# 사용자 지정 개체 동기화 활성화/비활성화 {#enable-disable-custom-object-sync}

Salesforce 인스턴스에서 만든 사용자 정의 개체는 Marketing To의 일부일 수 있습니다. 설정 방법

## 사용자 지정 개체 동기화 활성화/비활성화 {#enable-disable-custom-object-sync-1}

>[!NOTE]
>
>관리자 권한이 필요합니다.

1. **관리**&#x200B;를 클릭합니다.

   ![](assets/one.png)

1. 데이터베이스 관리 메뉴에서 **Salesforce 개체 동기화**&#x200B;를 클릭합니다.

   ![](assets/two-2.png)

1. 첫 번째 사용자 지정 개체인 경우 **스키마 동기화를 클릭합니다.** 그렇지 않은 경우  **스키마** 새로 고침을 클릭하여 최신 정보가 있는지 확인합니다.

   ![](assets/image2014-12-10-10-3a14-3a44.png)

1. 전역 동기화가 실행 중인 경우 **전역 동기화 비활성화**&#x200B;를 클릭하여 비활성화해야 합니다.

   ![](assets/image2014-12-10-10-3a14-3a54.png)

   >[!NOTE]
   >
   >Salesforce 사용자 지정 개체 스키마의 동기화는 몇 분 정도 걸릴 수 있습니다.

1. **스키마 새로 고침**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-10-10-3a15-3a7.png)

1. 동기화할 개체를 선택하고 **동기화 활성화**&#x200B;를 클릭합니다.

   >[!TIP]
   >
   >Salesforce의 리드, 연락처 또는 계정 개체와 직접 관계가 있는 경우에만 사용자 지정 개체를 동기화할 수 있습니다.

   ![](assets/image2014-12-10-10-3a15-3a30.png)

1. **동기화 사용**&#x200B;을 다시 클릭합니다.

   ![](assets/image2014-12-10-10-3a15-3a40.png)

1. **Salesforce** 탭으로 돌아가서 **동기화 사용**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-10-10-3a15-3a49.png)

## 사용자 지정 개체 사용 {#using-your-custom-objects}

>[!NOTE]
>
>트리거가 있는 스마트 캠페인에서는 사용자 지정 개체를 사용할 수 없습니다.

1. 스마트 목록에서 **Has Opportunity** 필터 위로 드래그하고 **true**&#x200B;로 설정합니다.

   ![](assets/image2015-8-26-9-3a39-3a28.png)

1. 그런 다음 필터 제한을 사용하여 포커스를 좁힙니다.

   ![](assets/image2015-8-24-14-3a18-3a53.png)

   훌륭해! 이제 스마트 캠페인 및 스마트 목록에서 이 사용자 지정 개체의 데이터를 사용할 수 있습니다.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md)
