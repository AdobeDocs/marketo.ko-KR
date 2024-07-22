---
unique-page-id: 1900573
description: 시스템 토큰을 이메일에 링크로 추가 - Marketo 문서 - 제품 설명서
title: 시스템 토큰을 이메일에 링크로 추가
exl-id: 9156be24-18ae-44ea-96e5-a6257ff29b46
feature: Tokens
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 0%

---

# 시스템 토큰을 이메일에 링크로 추가 {#add-a-system-token-as-a-link-in-an-email}

이러한 시스템 토큰을 사용하여 이메일에서 특수 링크의 위치를 사용자 정의할 수 있습니다.

다음 토큰은 이메일 또는 이메일 템플릿에서 링크로 사용할 수 있습니다.

* `{{system.forwardToFriendLink}}`
* `{{system.unsubscribeLink}}`
* `{{system.viewAsWebpageLink}}`

>[!NOTE]
>
>앵커 링크 내에 있지 않으면 이 토큰을 **클릭할 수 없습니다**. 또한 **Not**&#x200B;을(를) 내 토큰에 포함할 수 있습니다.

이를 이메일에 추가하는 방법은 다음과 같습니다.

1. 이메일을 찾아 선택한 다음 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/one-1.png)

1. 편집 가능한 영역을 두 번 클릭합니다.

   ![](assets/two-1.png)

1. 토큰이 있는 링크로 변환할 텍스트를 강조 표시하고 **링크 삽입/편집** 단추를 클릭합니다.

   ![](assets/three-1.png)

1. 링크 URL에 토큰을 입력하고 **삽입**&#x200B;을 클릭합니다.

   ![](assets/four-1.png)

   >[!TIP]
   >
   >원하는 토큰 복사/붙여넣기: **`{{system.forwardToFriendLink}}`** 또는 **`{{system.unsubscribeLink}}`** 또는 **`{{system.viewAsWebpageLink}}`**

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-17-22-3a12-3a17.png)

>[!IMPORTANT]
>
>이 방법을 사용하여 &quot;viewAsWebpageLink&quot; 시스템 토큰을 추가하는 경우 토큰을 사용하여 **재정의할 수 없습니다**. 대신 토큰을 사용하여 &quot;viewAsWebPageLink&quot;를 재정의할 수 있는 [전자 메일에 웹 페이지로 보기 링크 추가](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) 방법을 사용하십시오.

>[!NOTE]
>
>완료되면 [전자 메일을 승인](/help/marketo/product-docs/email-marketing/general/creating-an-email/approve-an-email.md)하는 것을 잊지 마십시오.

잘했어! 이제 시스템 토큰을 이메일에 링크로 추가하는 방법을 알 수 있습니다.
