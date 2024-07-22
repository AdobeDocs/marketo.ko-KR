---
description: Adobe Experience Cloud - Marketo 문서 - 제품 설명서에서 대상자 동기화
title: Adobe Experience Cloud에서 대상자 동기화
exl-id: 2288ee01-2c2e-4f33-b5c9-da3a431c1816
feature: Integrations
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 0%

---

# Adobe Experience Cloud에서 대상자 동기화 {#sync-an-audience-from-adobe-experience-cloud}

>[!NOTE]
>
>HIPAA 지원 Marketo 인스턴스 배포에서는 이 통합을 사용할 수 없습니다.

>[!PREREQUISITES]
>
>[Adobe 조직 매핑 설정](/help/marketo/product-docs/adobe-experience-cloud-integrations/set-up-adobe-organization-mapping.md){target="_blank"}

## 대상자를 동기화하는 방법 {#how-to-sync-an-audience}

1. 내 Marketo에서 **[!UICONTROL 데이터베이스]** 타일을 클릭합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-1.png)

1. **[!UICONTROL 새로 만들기]** 드롭다운을 클릭하고 **[!UICONTROL Experience Cloud 대상에서 동기화]**&#x200B;를 선택합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-2.png)

1. **[!UICONTROL 대상 라이브러리 폴더]** 드롭다운을 클릭하고 원하는 원본 폴더를 선택합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-3.png)

1. **[!UICONTROL 대상 이름]**&#x200B;을 선택하세요.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-4.png)

1. 대상의 경우 기존 목록을 선택하거나 새 목록의 이름을 입력할 수 있습니다. 이 예제에서는 새 파일을 만드는 중입니다. 완료되면 **[!UICONTROL 동기화]**&#x200B;를 클릭합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-5.png)

1. **[!UICONTROL 확인]**&#x200B;을 클릭합니다.

   ![](assets/sync-an-audience-from-adobe-experience-cloud-6.png)

## FAQ {#faq}

**쿠키 동기화는 어떻게 작동합니까?**

Marketo 구독에 대해 쿠키 동기화가 활성화되면 Marketo의 munchkin.js가 통합 설정 중에 지정한 Adobe IMS 조직의 Adobe ECID를 캡처하고 저장하고 이 ECID를 해당 Marketo 쿠키 식별자와 일치시키려고 합니다. 이렇게 하면 Marketo의 익명 사용자 프로필이 Adobe ECID로 보강될 수 있습니다.

일반 텍스트 이메일을 사용하여 식별된 잠재 고객 프로필에 익명 사용자 프로필을 연결하는 추가 단계가 필요합니다. [이(가) 작동하는 정확한 방법은 여기에 설명되어 있습니다](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md){target="_blank"}.

**Marketo의 목록 크기가 Adobe의 목록 크기와 다른 이유는 무엇입니까?**

Marketo에서 ECID 쿠키 ID를 알려진 사용자에게 연결할 수 없는 경우 사용자도 (으)로 동기화되지 않습니다.

**1회 동기화입니까?**

동기화를 한 번만 시작하면 됩니다. 그런 다음 레코드가 자동으로 동기화됩니다. 초기 동기화는 최대 24시간 정도 소요될 수 있습니다. 앞으로 새 레코드는 2~3시간 후에 동기화됩니다.
