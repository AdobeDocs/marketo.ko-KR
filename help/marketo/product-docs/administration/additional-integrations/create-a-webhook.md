---
unique-page-id: 2360360
description: 웹 후크 만들기 - 마케팅 문서 - 제품 설명서
title: 웹 후크 만들기
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '251'
ht-degree: 0%

---


# 웹 후크 만들기 {#create-a-webhook}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

웹 후크를 사용하여 서드파티 웹 서비스를 활용하여 문자 메시지를 전송하고 개인 데이터를 확장하는 등 다양한 작업을 할 수 있습니다.

>[!NOTE]
>
>**가용성**
>
>모든 고객이 이 기능을 구입하지는 않았습니다. 자세한 내용은 영업 담당자에게 문의하십시오.

1. **Admin **으로 이동하고 Webhook를 **클릭합니다**.

   ![](assets/image2014-9-24-14-3a52-3a57.png)

1. 새 **웹 후크를 클릭합니다**.

   ![](assets/image2014-9-24-14-3a53-3a9.png)

1. 웹후크의 이름을 지정하고 구성합니다.

   ![](assets/image2014-9-24-14-3a53-3a19.png)

   >[!NOTE]
   >
   >URL 매개 변수 또는 POST 템플릿에 타사 서비스 자격 증명을 입력하는 경우가 많습니다.

   * **URL**:요청을 웹 서비스에 POST하는 데 사용하는 URL을 입력합니다. 개인의 이메일 주소(**`{{lead.Email Address}}`**)와 같은 토큰을 삽입하려면 요청에서 토큰 **삽입을 클릭합니다**.

   * **템플릿**:POST 본문에 정보를 전송하려면 템플릿을 입력합니다. XML, JSON, SOAP 등 HTTP POST을 지원하는 모든 데이터 형식을 사용하십시오. 템플릿에 토큰을 삽입하려면 토큰 **삽입을 클릭합니다**.

   * **요청 토큰 인코딩**:토큰 값에 특수 문자(예: 앰퍼샌드, &#39;&amp;&#39;)가 포함되어 있는 경우, 요청의 형식(**JSON** 또는 **양식/Url**)을 지정합니다.

   * **응답 유형**:서비스에서 받은 응답의 형식(**JSON** 또는 **XML**)을 선택합니다.

   만들기를 클릭합니다.

   ![](assets/image2014-9-24-14-3a53-3a35.png)

>[!NOTE]
>
>**딥 다이브**
>
>웹 [후크](http://developers.marketo.com/documentation/webhooks/) 심층 분석

