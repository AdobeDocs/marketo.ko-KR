---
unique-page-id: 2360253
description: '"웹 페이지로 보기" 메시지 편집 - Marketo 문서 - 제품 설명서'
title: “웹 페이지로 보기” 메시지 편집
exl-id: 5541fe6c-7297-4277-8355-ba7b4ac73e2e
feature: Email Setup
source-git-commit: 65d607e279fb86b0816ccaec2f4bf3c69e309cb9
workflow-type: tm+mt
source-wordcount: '155'
ht-degree: 16%

---

# “웹 페이지로 보기” 메시지 편집 {#edit-the-view-as-web-page-message}

&quot;[웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md)&quot; 텍스트를 편집해야 하는 경우 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

## “웹 페이지로 보기” 메시지 편집 {#edit-the-view-as-web-page-message-1}

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/edit-the-view-as-web-page-message-1.png)

1. **[!UICONTROL Email]**&#x200B;를 클릭합니다.

   ![](assets/edit-the-view-as-web-page-message-2.png)

   >[!CAUTION]
   >
   >다음 변수는 중요합니다. 삭제하지 마십시오!
   >
   >`%mkt_webview_url%?mkt_tok=##MKT_TOK##`
   >
   >두 번째 부분 `##MKT_TOK##`은(는) 해당 사용자의 [!UICONTROL munchkin] 쿠키입니다. 링크를 클릭할 때 쿠키가 적절히 요리되도록 해줍니다.

1. **[!UICONTROL View as Web Page HTML]** 및 **[!UICONTROL View as Web Page Text]** 버전을 원하는 대로 편집하고 **[!UICONTROL Save Changes]**&#x200B;을(를) 클릭합니다.

   ![](assets/edit-the-view-as-web-page-message-3.png)

>[!CAUTION]
>
>다음을 피하십시오.
>
>* HTML 상자 중 하나에 추가 URL 추가
>* 텍스트 버전에 HTML 넣기

여기 있습니다. 형식을 지정하기 위해 테스트 이메일을 전송합니다.

## 기본 &quot;웹 페이지로 보기&quot; 텍스트 {#default-view-as-web-page-text}

기본 시스템 &quot;[!UICONTROL View as Web Page]&quot;(으)로 되돌려야 하는 경우 다음을 복사/붙여넣습니다.

**[!UICONTROL View as Web Page HTML]**:

`<div style="text-align: center"><font face="Verdana" size="1">To view this email as a web page, <a href="%mkt_webview_url%?mkt_tok=##MKT_TOK##">click here</a></font></div>`

**[!UICONTROL View as Web Page Text]**:

이 이메일을 웹 페이지로 보려면 다음 주소로 이동하십시오.
`%mkt_webview_url%?mkt_tok=##MKT_TOK##`

다 됐습니다!
