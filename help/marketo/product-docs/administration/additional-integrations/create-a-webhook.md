---
unique-page-id: 2360360
description: ' [!DNL Webhook] - Marketo 문서 만들기 - 제품 설명서'
title: ' [!DNL Webhook] 만들기'
exl-id: 3e753d2d-6f33-4987-884e-8e13167cf3df
feature: Administration, Webhooks
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 3%

---

# [!DNL Webhook] 만들기 {#create-a-webhook}

[!DNL Webhooks]을(를) 사용하여 문자 메시지를 보내고 개인 데이터를 확장하는 등의 서드파티 웹 서비스를 이용하십시오.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/create-a-webhook-1.png)

1. **[!UICONTROL Webhooks]**&#x200B;를 클릭합니다.

   ![](assets/create-a-webhook-2.png)

1. **[!UICONTROL New Webhook]**&#x200B;를 클릭합니다.

   ![](assets/create-a-webhook-3.png)

1. [!DNL Webhook]의 이름을 지정하고 구성합니다.

   ![](assets/create-a-webhook-4.png)

   >[!NOTE]
   >
   >여기에는 종종 타사 서비스 자격 증명을 URL 매개 변수 또는 POST 템플릿으로 입력하는 작업이 포함됩니다.

   * **[!UICONTROL URL]**: 웹 서비스에 대한 요청에 사용하는 URL을 입력하십시오. 개인 전자 메일 주소(**`{{lead.Email Address}}`**)와 같은 토큰을 요청에서 삽입하려면 **[!UICONTROL Insert Token]**&#x200B;을(를) 클릭합니다.

   * **[!UICONTROL Template]**: 요청 본문에서 정보를 전송하려면 페이로드 템플릿을 통해 을 입력합니다. POST, DELETE, PATCH 또는 PUT 요청 유형에 허용된 템플릿. JSON 또는 XML과 같은 데이터 형식을 사용할 수 있습니다. 템플릿에 토큰을 삽입하려면 **[!UICONTROL Insert Token]**&#x200B;을(를) 클릭합니다.

   * **[!UICONTROL Request Token Encoding]**: 토큰 값에 특수 문자(예: 앰퍼샌드, &#39;&amp;&#39;)가 포함된 경우 요청 형식을 지정하십시오(**JSON** 또는 **Form/Url**).

   * **[!UICONTROL Response type]**: 서비스에서 받는 응답의 형식(**JSON** 또는 **XML**)을 선택하십시오.

   * **[!UICONTROL Request Type]**: 사용할 HTTP 메서드(DELETE, GET, PATCH, POST, PUT)를 선택합니다.

1. **[!UICONTROL Create]**&#x200B;를 클릭합니다.

   ![](assets/create-a-webhook-5.png)

>[!NOTE]
>
>[[!DNL Webhooks]](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/webhooks/webhooks){target="_blank"} 심층 분석에서 자세히 알아보세요.
