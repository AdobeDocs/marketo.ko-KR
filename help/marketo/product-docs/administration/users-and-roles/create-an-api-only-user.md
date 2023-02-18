---
unique-page-id: 2360207
description: API 전용 사용자 만들기 - Marketo 문서 - 제품 설명서
title: API 전용 사용자 만들기
exl-id: 23c92255-07a8-41c2-b7b8-8e495d135671
source-git-commit: 07ebe804d9888c214f9e1ae246ab80dafad54ea3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 0%

---

# API 전용 사용자 만들기 {#create-an-api-only-user}

을 통해 Marketo과 통합하려면 [REST API](https://developers.marketo.com/documentation/rest/)를 채울 때는 API 전용 사용자를 만들어야 합니다. 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>[API 전용 사용자 역할 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)

>[!NOTE]
>
>**관리 권한 필요**

1. 로 이동합니다. **관리** 영역.

   ![](assets/create-an-api-only-user-1.png)

1. 클릭 **사용자 및 역할**.

   ![](assets/create-an-api-only-user-2.png)

1. 클릭 **새 사용자 초대**.

   ![](assets/create-an-api-only-user-3.png)

1. API 전용 사용자의 이메일, 이름 및 성을 입력합니다. 클릭 **다음**.

   ![](assets/create-an-api-only-user-4.png)

   >[!TIP]
   >
   >선택적인 이유 또는 액세스 만료 날짜를 추가합니다. 액세스 만료 날짜는 단기 직원에게 유용합니다.

1. 을(를) 선택합니다 **API만** 역할 및 확인 **API만** 확인란을 선택합니다. 클릭 **다음**.

   ![](assets/create-an-api-only-user-5.png)

1. 클릭 **보내기**.

   ![](assets/create-an-api-only-user-6.png)

>[!NOTE]
>
>팝업에서는 &quot;API에만 초대장이 필요하지 않습니다&quot;라고 표시하지만 이는 잘못된 작업을 수행했음을 의미하지는 않습니다. 이는 초대 이메일을 보낼 필요 없이 역할을 만들겠다는 의미일 뿐입니다.

그럼! 이제 사용자 정의 서비스를 만들어 보겠습니다.

>[!MORELIKETHIS]
>
>[ReST API에서 사용할 사용자 지정 서비스 만들기](/help/marketo/product-docs/administration/additional-integrations/create-a-custom-service-for-use-with-rest-api.md)
