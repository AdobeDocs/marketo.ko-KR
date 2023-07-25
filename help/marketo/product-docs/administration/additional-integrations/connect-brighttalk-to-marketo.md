---
unique-page-id: 15695874
description: "연결 [!DNL BrightTALK] 대상 Marketo - Marketo 문서 - 제품 설명서"
title: "연결 [!DNL BrightTALK] 대상 Marketo"
exl-id: 5c6a12ec-301b-4dec-975c-24ec759ebb37
feature: Administration, Integrations
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 1%

---

# 연결 [!DNL BrightTALK] Marketo으로 {#connect-brighttalk-to-marketo}

연결 방법 알아보기 [!DNL BrightTALK] Marketo 인스턴스로 이동합니다. 이렇게 하려면 두 그룹의 관리자여야 합니다.

>[!NOTE]
>
>**관리자 권한 필요**

## 의 단계 [!DNL BrightTALK] {#steps-in-brighttalk}

1. 에 로그인 [business.brighttalk.com/demandcentral](https://business.brighttalk.com/demandcentral/login){target="_blank"} 및 클릭 **[!UICONTROL 지금 연결]**.
1. 아래 [!UICONTROL 고급 Marketo 커넥터], 클릭 **[!UICONTROL 연결]**.
1. 자격 증명 화면으로 이동하여 클라이언트 ID, 클라이언트 암호, ID 서비스 URL 및 나머지 서비스 URL을 요청합니다. 이 정보를 얻으려면 Marketo에 로그인합니다.

## Marketo의 단계 {#steps-in-marketo}

>[!NOTE]
>
>이 시점에서 다음을 설정해야 합니다. [!DNL API Only User Role] 및 [!DNL API User] 사용 권한을 제한하기 위해 [!DNL BrightTALK] 은 Marketo 인스턴스에 를 갖게 됩니다. 해당 단계에 대한 문서가 이미 있으므로 해당 단계에 연결합니다.

1. 만들기 [API 전용 사용자 역할](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target="_blank"}.

1. [API 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md){target="_blank"}, 사용 [!DNL BrightTALK] 4단계 동안 생성한 API 역할입니다.

1. 로 돌아가기 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/connect-brighttalk-to-marketo-1.png)

1. 아래 **[!UICONTROL 통합]**, 클릭 **[!UICONTROL 시작 지점]**.

   ![](assets/connect-brighttalk-to-marketo-2.png)

1. 다음을 클릭합니다. **[!UICONTROL 신규]** 드롭다운 및 선택 **[!UICONTROL 새 서비스]**.

   ![](assets/connect-brighttalk-to-marketo-3.png)

1. 입력 **[!UICONTROL 표시 이름]** 원하는 대로 선택할 수 있습니다. 다음을 클릭합니다. **[!UICONTROL 서비스]** 드롭다운 및 선택 **[!UICONTROL 사용자 정의]** (do) _아님_ 선택 [!DNL BrightTALK]).

   ![](assets/connect-brighttalk-to-marketo-4.png)

   >[!CAUTION]
   >
   >선택하지 마십시오. [!DNL BrightTALK] 을 클릭합니다. 제거하는 중인 필드이며 이 필드를 선택하면 다음 사항에 심각한 문제가 발생할 수 있습니다. [!DNL Marketo/BrightTALK] 통합.

1. 입력 [!UICONTROL 설명] 원하는 대로 선택할 수 있습니다. 다음을 클릭합니다. **[!UICONTROL API 전용 사용자]** 드롭다운 및 선택 [!DNL BrightTALK API User] 5단계 동안 을(를) 만들었습니다. Click **[!UICONTROL Create]**.

   ![](assets/connect-brighttalk-to-marketo-5.png)

1. 클릭 **[!UICONTROL 세부 사항 보기]** 방금 생성한 사용자 정의 서비스용.

   ![](assets/connect-brighttalk-to-marketo-6.png)

1. 복사(및 저장) **[!UICONTROL 클라이언트 ID]** 및 **[!UICONTROL 클라이언트 암호]**. Click **[!UICONTROL Close]**.

   ![](assets/connect-brighttalk-to-marketo-7.png)

1. 아래 **[!UICONTROL 통합]**, 선택 **[!UICONTROL 웹 서비스]**.

   ![](assets/connect-brighttalk-to-marketo-8.png)

1. 아래 **[!UICONTROL Rest API]**, 복사(및 저장) **[!UICONTROL 엔드포인트]** 및 **[!UICONTROL 신원]**.

   ![](assets/connect-brighttalk-to-marketo-9.png)

## 의 추가 단계 [!DNL BrightTALK] {#additional-steps-in-brighttalk}

1. (으)로 돌아가기 [!DNL BrightTALK] 3단계의 커넥터 설정 화면을 누르고 12단계와 14단계에서 저장한 자격 증명을 입력합니다.

자격 증명이 인증되면 공식적으로 연결됩니다. [!DNL BrightTALK] Marketo으로. 다음 단계는 를 결정하는 것입니다. [동기화할 데이터 필드](https://support.brighttalk.com/hc/en-us/articles/115005131274-BrightTALK-Connector-for-Marketo-Choose-the-Fields-to-Sync){target="_blank"}.
