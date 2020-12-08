---
unique-page-id: 2360350
description: ReST API와 함께 사용할 사용자 지정 서비스 만들기 - Marketing To Docs - 제품 설명서
title: ReST API와 함께 사용할 사용자 지정 서비스 만들기
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---


# ReST API와 함께 사용할 사용자 지정 서비스 만들기 {#create-a-custom-service-for-use-with-rest-api}

ReST API를 통해 Marketing To와 통합하려면 사용자 지정 서비스를 만들어야 합니다. 방법

>[!NOTE]
>
>**사전 요구 사항**
>
>* [API 전용 사용자 역할 만들기](../../../product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [API 전용 사용자 만들기](../../../product-docs/administration/users-and-roles/create-an-api-only-user.md)

>



>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>**딥 다이브**
>
>ReST [API에 대한 자세한 내용은 개발자 설명서를 참조하십시오](http://developers.marketo.com/documentation/rest/). 필요한 경우 [SOAP API도](http://developers.marketo.com/documentation/soap/) 제공됩니다.

>[!NOTE]
>
>Spark 수준의 Marketing Cloud를 사용하는 경우 사용자 정의 서비스를 만들 수 없습니다.

## 사용자 지정 서비스 만들기 {#create-custom-service}

1. 관리자로 **이동하고 LaunchPoint** 를 **클릭합니다**.

   ![](assets/image2014-9-19-10-3a38-3a15.png)

1. 새로 **만들기**&#x200B;아래에서 **새 서비스를 클릭합니다**.

   ![](assets/image2014-9-19-10-3a38-3a22.png)

1. 서비스의 **표시** 이름을 입력합니다. 이전에 만든 **API** 사용자만 [을 선택합니다](../../../product-docs/administration/users-and-roles/create-an-api-only-user.md).

   >[!NOTE]
   >
   >**미리 알림**
   >
   >널리 사용되는 웨비나 서비스를 위한 기본 통합이 이미 있습니다.

   ![](assets/image2014-9-19-10-3a38-3a32.png)

1. 만들기를 **클릭합니다**.

   ![](assets/image2014-9-19-10-3a39-3a28.png)

   오 그래 이제 서비스가 생성되었습니다. 액세스를 위해 제공하는 모든 자격 증명을 가져오겠습니다.

## API 액세스에 대한 자격 증명 {#credentials-for-api-access}

1. 관리자로 **이동하고 LaunchPoint** 를 **클릭합니다**.

   ![](assets/image2014-9-19-10-3a42-3a11.png)

1. 위에서 **만든 사용자 지정 LaunchPoint 서비스에 대한 세부 사항** 보기를 클릭합니다.

   ![](assets/image2014-9-19-10-3a42-3a16.png)

1. 토큰 **가져오기를 클릭합니다**.

   ![](assets/image2014-9-19-10-3a42-3a24.png)

1. 연결 설정 담당자에게** 클라이언트 ID*, **클라이언트 암호**, **승인된 사용자**&#x200B;및 **토큰을** 제공합니다.

   ![](assets/image2014-9-19-10-3a42-3a38.png)

>[!CAUTION]
>
>이 정보를 공유하지 마십시오.데이터의 뒷문입니다. 안전하게 지켜라!

