---
unique-page-id: 2360253
description: '"웹 페이지로 보기" 메시지 편집 - Marketo 문서 - 제품 설명서'
title: '"웹 페이지로 보기" 메시지 편집'
exl-id: 5541fe6c-7297-4277-8355-ba7b4ac73e2e
source-git-commit: 81ee349dbbe48c70b040751cae750c3684b71c78
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 0%

---

# &quot;웹 페이지로 보기&quot; 메시지 편집 {#edit-the-view-as-web-page-message}

를 편집해야 하는 경우[웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md)&quot; 텍스트, 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

## &quot;웹 페이지로 보기&quot; 메시지 편집 {#edit-the-view-as-web-page-message-1}

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/edit-the-view-as-web-page-message-1.png)

1. 클릭 **[!UICONTROL 이메일]**.

   ![](assets/edit-the-view-as-web-page-message-2.png)

   >[!CAUTION]
   >
   >다음 변수는 중요합니다. 삭제하지 마십시오!
   >
   >`%mkt_webview_url%?mkt_tok=##MKT_TOK##`
   >
   >두 번째 부분 `##MKT_TOK##` 은(는) [!UICONTROL 먼치킨] 쿠키를 가져왔습니다 링크를 클릭할 때 쿠키가 적절히 요리되도록 해줍니다.

1. 편집 **[!UICONTROL 웹 페이지로 보기 HTML]** 및 **[!UICONTROL 웹 페이지 텍스트로 보기]** 원하는 버전 및 클릭 **[!UICONTROL 변경 내용 저장]**.

   ![](assets/edit-the-view-as-web-page-message-3.png)

>[!CAUTION]
>
>다음을 피하십시오.
>
>* HTML 상자 중 하나에 추가 URL 추가
>* 텍스트 버전에 HTML 넣기


여기 있습니다. 형식을 지정하기 위해 테스트 이메일을 전송합니다.

## 기본 &quot;웹 페이지로 보기&quot; 텍스트 {#default-view-as-web-page-text}

기본 시스템 &quot; (으)로 되돌리려면[!UICONTROL 웹 페이지로 보기]&quot;, 다음을 복사/붙여넣습니다.

**[!UICONTROL 웹 페이지로 보기 HTML]**:

`<pre data-theme="Confluence"><div style="text-align: center"><font face="Verdana" size="1">To view this email as a web page, <a href="%mkt_webview_url%?mkt_tok=##MKT_TOK##">click here</a></font></div></pre>`

**[!UICONTROL 웹 페이지 텍스트로 보기]**:

이 이메일을 웹 페이지로 보려면 다음 주소로 이동하십시오.
`<pre data-theme="Confluence">%mkt_webview_url%?mkt_tok=##MKT_TOK##</pre>`

다 됐습니다!
