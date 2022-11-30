---
unique-page-id: 2360350
description: ReST API와 함께 사용할 사용자 지정 서비스 만들기 - Marketo 문서 - 제품 설명서
title: ReST API에서 사용할 사용자 지정 서비스 만들기
exl-id: d94f723b-2e98-4350-a9e5-bd57aff2303b
source-git-commit: 5f509a7aa27692e54bf129b94c657aff0f645f2b
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---

# ReST API에서 사용할 사용자 지정 서비스 만들기 {#create-a-custom-service-for-use-with-rest-api}

ReST API를 통해 Marketo과 통합하려면 사용자 지정 서비스를 만듭니다. 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>* [API 전용 사용자 역할 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [API 전용 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md)
>


>[!NOTE]
>
>**관리 권한 필요**

>[!TIP]
>
>자세한 내용은 개발자 설명서 를 참조하십시오. [ReST API](https://developers.marketo.com/documentation/rest/). 또한 [SOAP API](https://developers.marketo.com/documentation/soap/) 그게 필요하시면

## 사용자 지정 서비스 만들기 {#create-custom-service}

1. 로 이동합니다. **관리** 영역.

   ![](assets/create-a-custom-service-for-use-with-rest-api-1.png)

1. 클릭 **LaunchPoint**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-2.png)

1. 선택 **새로 만들기** 그리고 **새 서비스**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-3.png)

1. 을(를) 입력합니다. **표시 이름** 을 참조하십시오. 을(를) 선택합니다 **API 전용 사용자** [이전에 만든](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md).

   ![](assets/create-a-custom-service-for-use-with-rest-api-4.png)

   >[!NOTE]
   >
   >이미 인기 있는 웨비나 서비스를 위한 기본 통합이 있습니다.

1. 클릭 **만들기**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-5.png)

   오 그래! 이제 서비스가 생성되었습니다. 계속 진행하여 액세스를 위해 제공할 모든 자격 증명을 가져오겠습니다.

## API 액세스에 대한 자격 증명 {#credentials-for-api-access}

1. 로 이동합니다. **관리** 영역.

   ![](assets/create-a-custom-service-for-use-with-rest-api-6.png)

1. 클릭 **LaunchPoint**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-7.png)

1. 클릭 **세부 사항 보기** 을 위에서 만든 사용자 지정 LaunchPoint 서비스의 경우 입니다.

   ![](assets/create-a-custom-service-for-use-with-rest-api-8.png)

1. 클릭 **토큰 가져오기**.

   ![](assets/create-a-custom-service-for-use-with-rest-api-9.png)

1. 다음을 제공합니다. **클라이언트 Id**, **클라이언트 암호**, **인증된 사용자**, 및 **토큰** 그 연결을 수립하는 책임자에게.

   ![](assets/create-a-custom-service-for-use-with-rest-api-10.png)

>[!CAUTION]
>
>이 정보를 공유하지 마십시오; 당신 데이터의 뒷문입니다. 안전하게 보관해!
