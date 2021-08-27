---
unique-page-id: 4719308
description: Marketo Sync - Marketo 문서 - 제품 설명서에 기존 Salesforce 필드 추가
title: Marketo 동기화에 기존 Salesforce 필드 추가
exl-id: 6030aedd-9c4b-411f-89c7-f35fd39b0066
source-git-commit: 7376804bda915d7ff25cdc50cb78a6686bd36882
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---

# Marketo 동기화에 기존 Salesforce 필드 추가 {#add-an-existing-salesforce-field-to-the-marketo-sync}

>[!NOTE]
>
>**관리 권한 필요**

일반적으로 Salesforce의 새 사용자 지정 필드는 Marketo에 자동으로 동기화됩니다. 그렇지 않으면 Marketo 동기화 사용자가 필드를 볼 수 없을 수 있습니다. 이 문제를 해결하는 방법은 다음과 같습니다.

1. 이름을 클릭한 다음 **설치**&#x200B;를 선택합니다.

   ![](assets/image2015-6-30-14-3a20-3a6.png)

1. 왼쪽 검색 막대에서 **profile**&#x200B;을 입력하고 **사용자 관리**&#x200B;에서 **프로필**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-14-3a20-3a52.png)

1. 동기화 사용자의 프로필을 클릭합니다.

   ![](assets/image2015-6-30-14-3a23-3a41.png)

1. **필드 수준 보안** 섹션에서 필드를 포함하는 개체 옆에 있는 **보기**&#x200B;를 클릭합니다.

   ![](assets/image2015-6-30-14-3a23-3a59.png)

1. **편집**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-14-3a24-3a28.png)

1. 동기화에 추가할 필드에 대해 **Visible** 확인란을 선택하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-14-3a24-3a49.png)

   달콤해! 다음 동기화 주기에서 Marketo이 해당 필드를 보고 마법을 시작합니다.

   >[!NOTE]
   >
   > 필드에 이미 Salesforce 값이 있는 경우, 해당 값은 다음 레코드 업데이트가 있을 때까지 Marketo에 동기화되지 않습니다.
