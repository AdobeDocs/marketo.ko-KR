---
unique-page-id: 2360360
description: 웹 후크 만들기 - Marketo 문서 - 제품 설명서
title: 웹 후크 만들기
exl-id: 3e753d2d-6f33-4987-884e-8e13167cf3df
source-git-commit: 6f17d79344653d1b2c364753d774998e343c9808
workflow-type: tm+mt
source-wordcount: '209'
ht-degree: 0%

---

# 웹 후크 만들기 {#create-a-webhook}

웹 후크를 사용하여 서드파티 웹 서비스를 활용하여 텍스트 메시지를 전송하고 개인 데이터를 확장하는 등의 작업을 수행할 수 있습니다.

>[!AVAILABILITY]
>
>모든 고객이 이 기능을 구입한 것은 아닙니다. 자세한 내용은 영업 담당자에게 문의하십시오.

1. 이동 **관리** 을(를) 클릭합니다. **Webhooks**.

   ![](assets/image2014-9-24-14-3a52-3a57.png)

1. 클릭 **새 웹 후크**.

   ![](assets/image2014-9-24-14-3a53-3a9.png)

1. 웹 후크에 이름을 지정하고 구성합니다.

   ![](assets/image2014-9-24-14-3a53-3a19.png)

   >[!NOTE]
   >
   >여기에는 종종 URL 매개 변수 또는 POST 템플릿에 타사 서비스 자격 증명을 입력하는 작업이 포함됩니다.

   * **URL**: 웹 서비스에 대한 요청에서 사용하는 URL을 입력합니다. 개인의 이메일 주소( )와 같은 토큰을 삽입하려면&#x200B;**`{{lead.Email Address}}`**) 내의 아무 곳에나 있는 **토큰 삽입**.

   * **템플릿**: POST 본문에 정보를 전송하려면 템플릿을 입력합니다. XML, JSON 또는 SOAP를 포함하여 HTTP POST을 지원하는 모든 데이터 형식을 사용합니다. 템플릿에 토큰을 삽입하려면 **토큰 삽입**.

   * **토큰 인코딩 요청**: 토큰 값에 특수 문자(예: 앰퍼샌드, &#39;&amp;&#39;)가 포함된 경우, 요청 형식을 나타냅니다(**JSON** 또는 **양식/Url**).

   * **응답 유형**: 서비스에서 받은 응답 형식(**JSON** 또는 **XML**).

   * **요청 유형**: 사용할 HTTP 메서드(DELETE, GET, PATCH, POST, PUT)을 선택합니다

   클릭 **만들기**.

   ![](assets/image2014-9-24-14-3a53-3a35.png)

>[!NOTE]
>
>자세한 내용은 [webhooks](https://developers.marketo.com/documentation/webhooks/) 심층 잠수
