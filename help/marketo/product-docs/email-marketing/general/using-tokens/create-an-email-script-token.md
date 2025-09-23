---
unique-page-id: 1900577
description: 이메일 스크립트 토큰 만들기 - Marketo 문서 - 제품 설명서
title: 이메일 스크립트 토큰 만들기
exl-id: c7f8c3e0-6d64-4115-b9b6-261576360ba1
feature: Tokens
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '203'
ht-degree: 4%

---

# 이메일 스크립트 토큰 만들기 {#create-an-email-script-token}

고급 개발자의 경우 전자 메일에서 [속도 스크립트](https://velocity.apache.org/engine/1.7/user-guide.html)를 사용할 수 있습니다. 방법은 다음과 같습니다.

1. **[!UICONTROL Marketing Activities]**(으)로 이동합니다.

   ![](assets/ma.png)

1. 프로그램(이벤트, 기본값 또는 참여 등)을 찾아 선택합니다.

   ![](assets/image2014-9-17-22-3a21-3a24.png)

1. **[!UICONTROL My Tokens]** 탭에서 **[!UICONTROL Email Script]** 토큰을 드래그합니다.

   ![](assets/image2014-9-17-22-3a21-3a29.png)

1. 전자 메일 스크립트 토큰에 이름을 지정하고 해당 콘텐츠를 **[!UICONTROL Click to Edit]**&#x200B;합니다.

   ![](assets/image2014-9-17-22-3a21-3a46.png)

1. 오른쪽의 트리를 사용하여 **[!UICONTROL Person]**, **[!UICONTROL Opportunity]** 또는 **[!UICONTROL Custom Object]** 토큰을 끌어옵니다.

   ![](assets/five-2.png)

   >[!NOTE]
   >
   >배열(영업 기회 또는 사용자 지정 개체)에 액세스할 때는 사용자와 연결된 가장 최근 10개 항목으로 제한됩니다.

1. 토큰을 스크립트 편집기로 드래그하면 선택/활성화됩니다.

   ![](assets/image2014-9-17-22-3a22-3a33.png)

   >[!NOTE]
   >
   >자유 형식의 토큰을 입력하는 경우 트리에서 해당 토큰을 모두 확인/활성화해야 합니다. 그렇지 않으면 일반 텍스트로 처리되고 작동하지 않습니다.

1. Velocity에서 스크립트를 작성합니다. 다음은 유용한 리소스입니다.

   * [Marketo 개발자 전자 메일 스크립팅 설명서](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/email-scripting)
   * [속도 사용 안내서](https://velocity.apache.org/engine/devel/user-guide.html)
   * [속도 참조 안내서](https://velocity.apache.org/engine/devel/vtl-reference-guide.html)
   * [Velocity 도구 Javadoc](https://velocity.apache.org/tools/releases/2.0/javadoc/index.html)

1. 스크립트가 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-17-22-3a23-3a1.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 한 번 더 클릭합니다.

   ![](assets/image2014-9-17-22-3a23-3a13.png)

이제 이메일에서 이 토큰을 사용할 수 있습니다. 이메일이 전송될 때마다 스크립트가 실행됩니다.

>[!MORELIKETHIS]
>
>[전자 메일에 전자 메일 스크립트 토큰 추가](/help/marketo/product-docs/email-marketing/general/using-tokens/add-an-email-script-token-to-your-email.md)
