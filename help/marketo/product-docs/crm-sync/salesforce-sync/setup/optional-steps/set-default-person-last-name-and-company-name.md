---
unique-page-id: 4719291
description: 기본 개인 성 및 회사 이름 설정 - Marketo 문서 - 제품 설명서
title: 기본 개인 성 및 회사 이름 설정
exl-id: 0216fb41-adf0-4ccf-be22-c064e90be65a
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '142'
ht-degree: 0%

---

# 기본 개인 성 및 회사 이름 {#set-default-person-last-name-and-company-name} 설정

Salesforce의 리드 및 연락처에 대한 (최소) 성 및 회사 이름이 필요합니다. 불완전한 레코드는 Salesforce와 동기화되지 않습니다. 부분 레코드를 동기화하려면 Marketo에서 Salesforce에 사용할 기본값을 설정해야 합니다.

1. **관리**&#x200B;로 이동하고 **Salesforce**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. **동기화 옵션 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. **기본 개인 성** 및 **기본 개인 회사**&#x200B;를 입력한 다음 **저장**&#x200B;을 클릭합니다.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo은 레코드가 처음에 Salesforce에 동기화될 때만 기본값을 할당합니다. 필수 필드 중 하나가 비어 있는 경우에만 해당합니다.

바로 그거야! 성이 누락되거나 회사 이름이 누락될 때마다 Marketo은 레코드를 동기화하면서 기본값을 추가합니다.
