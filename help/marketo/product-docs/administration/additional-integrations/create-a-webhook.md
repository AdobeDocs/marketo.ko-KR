---
unique-page-id: 2360360
description: 웹 후크 만들기 - 마케팅 문서 - 제품 설명서
title: 웹 후크 만들기
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '200'
ht-degree: 0%

---


# 웹 후크 만들기 {#create-a-webhook}

웹 후크를 사용하여 제3자 웹 서비스를 활용하여 문자 메시지를 전송하고 개인 데이터를 확장하는 등 다양한 작업을 할 수 있습니다.

>[!NOTE]
>
>**가용성**
>
>모든 고객이 이 기능을 구입하지는 않았습니다. 자세한 내용은 영업 담당자에게 문의하십시오.

1. **Admin **으로 이동하고 **Webhook**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-14-3a52-3a57.png)

1. **새 웹 후크**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-24-14-3a53-3a9.png)

1. 웹 후크의 이름을 지정하고 구성합니다.

   ![](assets/image2014-9-24-14-3a53-3a19.png)

   >[!NOTE]
   >
   >종종 URL 매개 변수 또는 POST 템플릿에 타사 서비스 자격 증명을 입력하는 것이 포함됩니다.

   * **URL**:웹 서비스에 요청을 POST하는 데 사용하는 URL을 입력합니다. 사용자의 이메일 주소(**`{{lead.Email Address}}`**)와 같은 토큰을 삽입하려면 요청에서 **토큰 삽입**&#x200B;을 클릭합니다.

   * **템플릿**:POST 본문에 정보를 전송하려면 템플릿을 입력합니다. XML, JSON, SOAP 등 HTTP POST을 지원하는 모든 데이터 형식을 사용합니다. 템플릿에 토큰을 삽입하려면 **토큰 삽입**&#x200B;을 클릭합니다.

   * **요청 토큰 인코딩**:토큰 값에 앰퍼샌드, &#39;&amp;&#39; 등의 특수 문자가 포함되어 있는 경우, 요청의 형식(**** JSON 또는  **양식/Url**)을 지정합니다.

   * **응답 유형**:서비스에서 받는 응답 형식(**** JSON 또는  **XML**)을 선택합니다.

   만들기를 클릭합니다.

   ![](assets/image2014-9-24-14-3a53-3a35.png)

>[!NOTE]
>
>**자세히 알아보기**
>
>[웹후크](http://developers.marketo.com/documentation/webhooks/)에서 자세한 내용을 살펴보십시오.

