---
unique-page-id: 2360350
description: ReST API와 함께 사용할 사용자 정의 서비스 만들기 - Marketo 문서 - 제품 설명서
title: ReST API와 함께 사용할 사용자 정의 서비스 만들기
exl-id: d94f723b-2e98-4350-a9e5-bd57aff2303b
feature: Administration
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '207'
ht-degree: 0%

---

# ReST API와 함께 사용할 사용자 정의 서비스 만들기 {#create-a-custom-service-for-use-with-rest-api}

ReST API를 통해 Marketo과 통합하려면 사용자 지정 서비스를 만들어야 합니다. 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>* [API 전용 사용자 역할 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)
>* [API 전용 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md)
>

>[!NOTE]
>
>**관리자 권한 필요**

>[!TIP]
>
>[REST API](https://developer.adobe.com/marketo-apis/)에 대한 자세한 내용은 개발자 설명서를 확인하십시오. 필요한 경우 [SOAP API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/soap/soap-api)도 있습니다.

## 사용자 정의 서비스 만들기 {#create-custom-service}

1. **[!UICONTROL 관리자]** 영역으로 이동합니다.

   ![](assets/create-a-custom-service-for-use-with-rest-api-1.png)

1. **LaunchPoint**&#x200B;을 클릭합니다.

   ![](assets/create-a-custom-service-for-use-with-rest-api-2.png)

1. **[!UICONTROL 새로 만들기]**&#x200B;를 선택한 다음 **[!UICONTROL 새 서비스]**&#x200B;를 선택하십시오.

   ![](assets/create-a-custom-service-for-use-with-rest-api-3.png)

1. 서비스에 대한 **[!UICONTROL 표시 이름]**&#x200B;을(를) 입력하십시오. **[!UICONTROL API 전용 사용자]** [이전에 만든](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md)을(를) 선택하십시오.

   ![](assets/create-a-custom-service-for-use-with-rest-api-4.png)

   >[!NOTE]
   >
   >인기 웨비나 서비스에 대한 기본 통합이 이미 있습니다.

1. **[!UICONTROL 만들기]**&#x200B;를 클릭합니다.

   ![](assets/create-a-custom-service-for-use-with-rest-api-5.png)

   오, 그래! 이제 서비스가 생성되었습니다. 계속 진행하여 액세스를 위해 제공할 모든 자격 증명을 가져오겠습니다.

## API 액세스용 자격 증명 {#credentials-for-api-access}

1. **[!UICONTROL 관리자]** 영역으로 이동합니다.

   ![](assets/create-a-custom-service-for-use-with-rest-api-6.png)

1. **[!UICONTROL LaunchPoint]**&#x200B;을 클릭합니다.

   ![](assets/create-a-custom-service-for-use-with-rest-api-7.png)

1. 위에서 만든 사용자 지정 [!UICONTROL LaunchPoint] 서비스에 대해 **[!UICONTROL 세부 정보 보기]**&#x200B;를 클릭합니다.

   ![](assets/create-a-custom-service-for-use-with-rest-api-8.png)

1. **[!UICONTROL 토큰 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/create-a-custom-service-for-use-with-rest-api-9.png)

1. 연결 설정 담당자에게 **[!UICONTROL 클라이언트 ID]**, **[!UICONTROL 클라이언트 암호]**, **[!UICONTROL 인증된 사용자]** 및 **[!UICONTROL 토큰]**&#x200B;을 제공하십시오.

   ![](assets/create-a-custom-service-for-use-with-rest-api-10.png)

>[!CAUTION]
>
>이 정보를 공유하지 마십시오. 데이터는 뒷문입니다. 안전하게 보관해!
