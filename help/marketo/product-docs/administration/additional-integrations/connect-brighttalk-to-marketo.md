---
unique-page-id: 15695874
description: Marketo - Marketo 문서 - 제품 설명서에  [!DNL BrightTALK] 연결
title: Marketo에  [!DNL BrightTALK] 연결
exl-id: 5c6a12ec-301b-4dec-975c-24ec759ebb37
feature: Administration, Integrations
source-git-commit: b95458ffab422901ef5e674756ae5e413ec542fd
workflow-type: tm+mt
source-wordcount: '285'
ht-degree: 0%

---

# Marketo에 [!DNL BrightTALK] 연결 {#connect-brighttalk-to-marketo}

[!DNL BrightTALK] 채널을 Marketo 인스턴스에 연결하는 방법을 알아봅니다. 이렇게 하려면 두 그룹의 관리자여야 합니다.

>[!NOTE]
>
>**관리자 권한 필요**

## [!DNL BrightTALK]의 단계 {#steps-in-brighttalk}

1. [business.brighttalk.com/demandcentral](https://business.brighttalk.com/demandcentral/login){target="_blank"}에 로그인하고 **[!UICONTROL Connect Now]**&#x200B;을(를) 클릭합니다.
1. [!UICONTROL Advanced Marketo Connector]에서 **[!UICONTROL Connect]**&#x200B;을(를) 클릭합니다.
1. 자격 증명 화면으로 이동하여 클라이언트 ID, 클라이언트 암호, ID 서비스 URL 및 나머지 서비스 URL을 요청합니다. 이 정보를 얻으려면 Marketo에 로그인합니다.

## Marketo의 단계 {#steps-in-marketo}

>[!NOTE]
>
>이 시점에서 [!DNL BrightTALK]이(가) Marketo 인스턴스에서 갖게 될 권한을 제한하려면 [!DNL API Only User Role] 및 [!DNL API User]을(를) 설정해야 합니다. 해당 단계에 대한 문서가 이미 있으므로 해당 단계에 연결합니다.

1. [API 전용 사용자 역할](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target="_blank"}을(를) 만듭니다.

1. 4단계에서 만든 [!DNL BrightTALK] API 역할을 사용하여 [API 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md){target="_blank"}.

1. **[!UICONTROL Admin]** 영역으로 돌아갑니다.

   ![](assets/connect-brighttalk-to-marketo-1.png)

1. **[!UICONTROL Integration]**&#x200B;에서 **[!UICONTROL LaunchPoint]**&#x200B;을(를) 클릭합니다.

   ![](assets/connect-brighttalk-to-marketo-2.png)

1. **[!UICONTROL New]** 드롭다운을 클릭하고 **[!UICONTROL New Service]**&#x200B;을(를) 선택합니다.

   ![](assets/connect-brighttalk-to-marketo-3.png)

1. 선택한 **[!UICONTROL Display Name]**&#x200B;을(를) 입력하십시오. **[!UICONTROL Service]** 드롭다운을 클릭하고 **[!UICONTROL Custom]**&#x200B;을(를) 선택합니다(_하지_&#x200B;하고 [!DNL BrightTALK]을(를) 선택하십시오).

   ![](assets/connect-brighttalk-to-marketo-4.png)

   >[!CAUTION]
   >
   >드롭다운에서 [!DNL BrightTALK]을(를) 선택하지 마십시오. 이 필드를 제거하는 중입니다. 이 필드를 선택하면 [!DNL Marketo/BrightTALK] 통합에 심각한 문제가 발생할 수 있습니다.

1. 선택한 [!UICONTROL Description]을(를) 입력하십시오. **[!UICONTROL API Only User]** 드롭다운을 클릭하고 5단계 동안 만든 [!DNL BrightTALK API User]을(를) 선택합니다. **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/connect-brighttalk-to-marketo-5.png)

1. 방금 만든 사용자 지정 서비스에 대해 **[!UICONTROL View Details]**&#x200B;을(를) 클릭합니다.

   ![](assets/connect-brighttalk-to-marketo-6.png)

1. **[!UICONTROL Client ID]** 및 **[!UICONTROL Client Secret]**&#x200B;을(를) 복사(및 저장)합니다. **[!UICONTROL Close]**&#x200B;을(를) 클릭합니다.

   ![](assets/connect-brighttalk-to-marketo-7.png)

1. **[!UICONTROL Integration]**&#x200B;에서 **[!UICONTROL Web Services]**&#x200B;을(를) 선택합니다.

   ![](assets/connect-brighttalk-to-marketo-8.png)

1. **[!UICONTROL Rest API]**&#x200B;에서 **[!UICONTROL Endpoint]** 및 **[!UICONTROL Identity]**&#x200B;을(를) 복사(및 저장)합니다.

   ![](assets/connect-brighttalk-to-marketo-9.png)

## [!DNL BrightTALK]의 추가 단계 {#additional-steps-in-brighttalk}

1. 3단계에서 [!DNL BrightTALK] 커넥터 설정 화면으로 돌아가서 12단계와 14단계에서 저장한 자격 증명을 입력합니다.

자격 증명이 인증되면 공식적으로 [!DNL BrightTALK]을(를) Marketo에 연결했습니다. 다음 단계는 동기화할 데이터 필드를 결정하는 것입니다. 도움이 필요한 경우 [BrightTALK](https://www.brighttalk.com/){target="_blank"}의 지원 팀에 문의하십시오.
