---
unique-page-id: 42762511
description: Adobe 조직 매핑 설정 - Marketo 문서 - 제품 설명서
title: Adobe 조직 매핑 설정
exl-id: d20be0d5-508f-40b9-a267-b6752643c311
source-git-commit: 88622c5df7cf04fb9e4a3bcccbf77db5594b5fc4
workflow-type: tm+mt
source-wordcount: '201'
ht-degree: 0%

---

# Adobe 조직 매핑 설정 {#set-up-adobe-organization-mapping}

Audience Manager, B2B CDP Marketo 커넥터, 다이내믹 채팅 등과 같은 Adobe 응용 프로그램과 동기화하려면 먼저 Marketo에 Adobe IMS 조직 자격 증명을 입력해야 합니다.

>[!NOTE]
>
>Marketo 인스턴스의 HIPAA 준비 배포에서는 이 통합을 사용할 수 없습니다.

>[!CAUTION]
>
>Adobe 비즈니스 플랫폼 및 Identity Management 시스템에 온보딩된 고객의 경우 구독과 연결된 조직 ID가 이미 채워지고 읽기 전용 필드입니다.

1. Marketo에서 **관리**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-1.png)

1. 통합에서 **Adobe 조직 매핑**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-2.png)

1. 클릭 **편집**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-3.png)

1. Adobe IMS 조직 ID를 입력합니다(이를 찾는 방법을 알아봅니다.) [여기](https://experienceleague.adobe.com/docs/control-panel/using/faq.html)) 를 클릭하고 를 클릭합니다. **확인**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-4.png)

1. 클릭 **확인**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-5.png)

1. 클릭 **닫기**.

   ![](assets/set-up-adobe-experience-cloud-audience-sharing-6.png)

   >[!NOTE]
   >
   >보안상의 이유로 매핑할 Adobe 조직의 조직 관리자여야 합니다. 그렇지 않으면 작업이 실패합니다.

1. 만약 _not_ 이미 로그인되어 있으면 새 탭/창에 팝업이 나타납니다. Adobe 조직에 로그인합니다(이 작업은 조직 액세스를 확인합니다).

그게 다야! 이제 다음을 수행할 수 있습니다 [대상 데이터 공유](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/send-a-list-to-adobe-experience-cloud.md){target=&quot;_blank&quot;} 대상 또는 [대상자 동기화](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/sync-an-audience-from-adobe-experience-cloud.md)Adobe Experience Cloud의 {target=&quot;_blank&quot;}.
