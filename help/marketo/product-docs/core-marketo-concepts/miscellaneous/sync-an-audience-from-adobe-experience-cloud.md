---
description: Adobe Experience Cloud에서 대상 동기화 - Marketo 문서 - 제품 설명서
title: Adobe Experience Cloud에서 대상 동기화
exl-id: 2288ee01-2c2e-4f33-b5c9-da3a431c1816
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '274'
ht-degree: 0%

---

# Adobe Experience Cloud {#sync-an-audience-from-adobe-experience-cloud}에서 대상 동기화

>[!NOTE]
>
>Marketo 인스턴스의 HIPAA용 배포에서는 이 통합을 사용할 수 없습니다.

>[!PREREQUISITES]
>
>[Adobe Experience Cloud 대상 공유 설정](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/set-up-adobe-experience-cloud-audience-sharing.md)

## 대상 {#how-to-sync-an-audience} 동기화 방법

1. 내 Marketo에서 **데이터베이스** 타일을 클릭합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-1.png)

1. **새로 만들기** 드롭다운을 클릭하고 Experience Cloud 대상의 동기화&#x200B;**를 선택합니다.**

   ![](assets/sync-an-audience-from-adobe-experience-cloud-2.png)

1. **대상 라이브러리 폴더** 드롭다운을 클릭하고 원하는 원본 폴더를 선택합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-3.png)

1. **대상자 이름**&#x200B;을 선택합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-4.png)

1. 대상에 대해 기존 목록을 선택하거나 새 목록의 이름을 입력할 수 있습니다. 이 예에서는 새 항목을 만듭니다. 완료되면 **동기화**&#x200B;를 클릭합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-5.png)

1. **확인**&#x200B;을 클릭합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-6.png)

## FAQ {#faq}

**쿠키 동기화는 어떻게 작동합니까?**

쿠키 동기화가 Marketo 구독에 대해 활성화되면 Marketo의 munchkin.js는 통합 설정 중에 지정한 Adobe IMS 조직에 대한 Adobe ECID를 캡처 및 저장하려고 하며 이러한 ECID를 해당 Marketo 쿠키 식별자와 일치시킵니다. 이를 통해 Marketo의 익명의 사용자 프로필은 Adobe ECID를 통해 더욱 풍부해집니다.

일반 텍스트 이메일을 사용하여 식별되는 리드 프로필에 익명 사용자 프로필을 연결하려면 추가 단계가 필요합니다. 정확히 이 작업이 작동하는 방식은 [에 설명되어 있습니다](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md).

**Marketo의 목록 크기가 Adobe의 목록 크기와 다른 이유는 무엇입니까?**

ECID 쿠키 ID를 Marketo의 알려진 사람에게 연결할 수 없는 경우에도 한 사람은 동기화되지 않습니다.

**일회성 동기화입니까?**

한 번만 동기화를 시작하면 됩니다. 이후에는 레코드가 자동으로 동기화됩니다. 초기 동기화에는 최대 24시간이 걸릴 수 있습니다.앞으로 2-3시간 후에 새 레코드가 동기화됩니다.
