---
unique-page-id: 4719291
description: 기본 개인 성 및 회사 이름 설정 - Marketo 문서 - 제품 설명서
title: 기본 개인 성 및 회사 이름 설정
exl-id: 0216fb41-adf0-4ccf-be22-c064e90be65a
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '142'
ht-degree: 0%

---

# 기본 개인 성 및 회사 이름 설정 {#set-default-person-last-name-and-company-name}

Salesforce에서는 Lead 및 Contact에 (최소) 성 및 회사 이름이 필요합니다. 완료되지 않은 레코드는 Salesforce에 동기화되지 않습니다. 부분 레코드를 동기화하려면 Salesforce에서 사용할 Marketo의 기본값을 설정해야 합니다.

1. 이동 **관리** 을(를) 클릭합니다. **Salesforce**.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. 클릭 **동기화 옵션 편집**.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. 을(를) 입력합니다. **기본 개인 성** 그리고 **기본 개인 회사** 을 클릭한 다음 **저장**.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo은 레코드가 처음에 Salesforce에 동기화될 때만 기본값을 할당하고 필수 필드 중 하나가 비어 있는 경우에만 해당 값을 할당합니다.

바로 그거야! 성이 없거나 회사 이름이 없을 때마다 Marketo에서 레코드를 동기화할 때 기본값을 추가합니다.
