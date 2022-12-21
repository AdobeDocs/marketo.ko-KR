---
description: Adobe Experience Cloud에서 대상 동기화 - Marketo 문서 - 제품 설명서
title: Adobe Experience Cloud에서 대상 동기화
exl-id: 2288ee01-2c2e-4f33-b5c9-da3a431c1816
source-git-commit: 492f21f090dc2478271172cf7db470e16f202366
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---

# Adobe Experience Cloud에서 대상 동기화 {#sync-an-audience-from-adobe-experience-cloud}

>[!NOTE]
>
>Marketo 인스턴스의 HIPAA 준비 배포에서는 이 통합을 사용할 수 없습니다.

>[!PREREQUISITES]
>
>[Adobe 조직 매핑 설정](/help/marketo/product-docs/adobe-experience-cloud-integrations/set-up-adobe-organization-mapping.md){target=&quot;_blank&quot;}

## 대상을 동기화하는 방법 {#how-to-sync-an-audience}

1. 내 Marketo에서 **데이터베이스** 타일.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-1.png)

1. 을(를) 클릭합니다. **새로 만들기** 드롭다운 및 선택 **Experience Cloud 대상에서 동기화**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-2.png)

1. 을(를) 클릭합니다. **대상 라이브러리 폴더** 드롭다운을 클릭하고 원하는 원본 폴더를 선택합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-3.png)

1. 선택 **대상 이름**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-4.png)

1. 대상에 대해 기존 목록을 선택하거나 새 목록의 이름을 입력할 수 있습니다. 이 예제에서는 새 오퍼를 만듭니다. 클릭 **동기화** 완료 시.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-5.png)

1. 클릭 **확인**.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-6.png)

## FAQ {#faq}

**쿠키 동기화는 어떻게 작동합니까?**

Marketo 가입에 대해 쿠키 동기화가 활성화되면 Marketo의 munchkin.js는 통합 설정 중에 지정한 Adobe IMS 조직에 대한 Adobe ECID를 캡처하고 저장하려고 하며 이러한 ECID를 해당 Marketo 쿠키 식별자와 일치시킵니다. 이를 통해 Marketo의 익명의 사용자 프로필이 Adobe ECID로 보강될 수 있습니다.

일반 텍스트 이메일을 사용하여 식별되는 리드 프로필에 익명 사용자 프로필을 연결하려면 추가 단계가 필요합니다. 정확히 어떻게 작동합니까 [여기에 설명되어 있습니다.](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md){target=&quot;_blank&quot;}.

**Marketo의 목록 크기가 Adobe의 목록 크기와 다른 이유는 무엇입니까?**

Marketo에서 알려진 사람에게 ECID 쿠키 ID를 연결할 수 없는 경우에도 개인이 동기화되지 않습니다.

**일회성 동기화입니까?**

동기화를 한 번만 시작하면 됩니다. 그런 다음 레코드가 자동으로 동기화됩니다. 초기 동기화는 최대 24시간이 걸릴 수 있습니다. 앞으로 2-3시간 후에 새로운 레코드가 동기화됩니다.
