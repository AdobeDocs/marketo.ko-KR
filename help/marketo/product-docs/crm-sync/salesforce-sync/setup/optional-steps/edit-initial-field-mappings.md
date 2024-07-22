---
unique-page-id: 4719287
description: 초기 필드 매핑 편집 - Marketo 문서 - 제품 설명서
title: 초기 필드 매핑 편집
exl-id: 320613d1-3845-4e05-a704-0db0f8027dc8
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---

# 초기 필드 매핑 편집 {#edit-initial-field-mappings}

>[!NOTE]
>
>이 기능은 Salesforce에 처음 동기화하기 전에만 액세스할 수 있습니다. **[!UICONTROL 지금 동기화]** 단추를 누르면 더 이상 이 작업을 수행할 수 없습니다.

Salesforce에 처음 동기화하는 동안 Marketo Engage은 유사하게 명명된 사용자 지정 필드를 Marketo 측의 단일 필드에 자동으로 결합하여 CRM의 리드 및 연락처 개체 모두와 데이터를 교환할 수 있도록 합니다. 이 문서에서는 이러한 매핑을 사용자 지정하는 방법을 설명합니다.

## 매핑되지 않은 필드 매핑 {#map-unmapped-fields}

[!UICONTROL 매핑되지 않은 필드] 폴더에 필드가 표시되면 Salesforce의 잠재 고객 또는 연락처의 유사한 필드에 매핑되지 않은 것입니다. 고칠 수 있어요

1. **[!UICONTROL 매핑 편집]**&#x200B;을 클릭합니다.

![](assets/image2014-12-9-13-3a31-3a0.png)

1. **[!UICONTROL 매핑되지 않은 사용자 지정 필드]** 폴더를 엽니다.

   ![](assets/two.png)

1. 매핑되지 않은 사용자 정의 필드 하나를 다른 필드로 드래그하여 함께 매핑합니다.

   >[!NOTE]
   >
   >사용자 정의 필드 매핑만 편집할 수 있습니다. 표준 필드 매핑은 수정할 수 없습니다.

   ![](assets/three.png)

1. 완료되면 **[!UICONTROL 매핑 완료]**&#x200B;를 클릭하세요.

   ![](assets/four.png)

## 기존 매핑 나누기 {#break-existing-mapping}

리드에 유사한 이름의 필드가 있고 연락처 개체 Marketo이 이 필드를 자동으로 함께 매핑합니다. 서로 다르며 서로 다른 데이터를 보유하고 있다고 간주할 수 있습니다. 이렇게 매핑을 중단합니다.

1. **[!UICONTROL 매핑 편집]**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-13-3a31-3a37.png)

1. 매핑된 필드를 강조 표시하고 **[!UICONTROL 매핑 나누기]**&#x200B;를 클릭하여 필드를 구분합니다.

   ![](assets/image2014-12-9-13-3a31-3a47.png)

1. 완료되면 **[!UICONTROL 매핑 완료]**&#x200B;를 클릭하세요.

   ![](assets/image2014-12-9-13-3a31-3a58.png)

   좋네! 초기 동기화가 거의 완료되었습니다.

## 스키마 재설정 {#reset-schema}

1. 매핑을 작업하는 동안 Salesforce에서 스키마를 일부 변경하는 경우 **[!UICONTROL 스키마 재설정]**&#x200B;을 클릭하여 변경 내용을 가져올 수 있습니다.

   * 모든 매핑 변경 사항이 재설정됩니다!
   * 스키마를 재설정하면 동기화 사용자로부터 필드를 숨기더라도 제거되지 않고 필드만 추가됩니다.

   ![](assets/image2014-12-9-13-3a32-3a8.png)
