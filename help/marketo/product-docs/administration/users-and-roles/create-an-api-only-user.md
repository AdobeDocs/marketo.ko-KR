---
unique-page-id: 2360207
description: API 전용 사용자 만들기 - Marketo 문서 - 제품 설명서
title: API 전용 사용자 만들기
exl-id: 23c92255-07a8-41c2-b7b8-8e495d135671
feature: Users and Roles
source-git-commit: ab1ea483998d6cb37277b18adf2c1d3371bb40e6
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 0%

---

# API 전용 사용자 만들기 {#create-an-api-only-user}

를 통해 Marketo과 통합하려는 경우 [나머지 API](https://developers.marketo.com/documentation/rest/){target="_blank"}, API 전용 사용자를 만들어야 합니다. 방법은 다음과 같습니다.

>[!IMPORTANT]
>
>Adobe ID에 온보딩된 구독에서 API 전용 사용자를 생성하는 경우 단계가 다르고 [은(는) 여기에서 찾을 수 있음](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-api-only-user-for-adobe-ims-enabled-subscriptions.md){target="_blank"}.

>[!PREREQUISITES]
>
>[API 전용 사용자 역할 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target="_blank"}

>[!NOTE]
>
>**관리자 권한 필요**

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/create-an-api-only-user-1.png)

1. 클릭 **[!UICONTROL 사용자 및 역할]**.

   ![](assets/create-an-api-only-user-2.png)

1. 클릭 **[!UICONTROL 새 사용자 초대]**.

   ![](assets/create-an-api-only-user-3.png)

1. API 전용 사용자에 대한 이메일, 이름 및 성을 입력합니다. 클릭 **[!UICONTROL 다음]**.

   ![](assets/create-an-api-only-user-4.png)

   >[!TIP]
   >
   >선택적 사유 또는 액세스 만료 날짜를 추가합니다. 액세스 만료일은 단기 사원에게 편리합니다.

1. 다음 항목 선택 **[!UICONTROL API만]** 역할 및 확인 **[!UICONTROL API만]** 확인란. 클릭 **[!UICONTROL 다음]**.

   ![](assets/create-an-api-only-user-5.png)

1. 클릭 **[!UICONTROL 보내기]**.

   ![](assets/create-an-api-only-user-6.png)

>[!NOTE]
>
>팝업에 &quot;API에만 초대가 필요하지 않습니다.&quot;라고 표시되지만 잘못된 작업을 수행했다는 의미는 아닙니다. 이는 초대 이메일을 보내지 않고 역할을 만들겠다는 의미입니다.

그럼 됐네! 이제 사용자 정의 서비스를 만들어 보겠습니다.

>[!MORELIKETHIS]
>
>[REST API와 함께 사용할 사용자 지정 서비스 만들기](/help/marketo/product-docs/administration/additional-integrations/create-a-custom-service-for-use-with-rest-api.md){target="_blank"}
