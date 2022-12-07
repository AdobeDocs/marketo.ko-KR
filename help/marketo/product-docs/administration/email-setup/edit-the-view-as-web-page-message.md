---
unique-page-id: 2360253
description: '"웹 페이지로 보기" 메시지 편집 - Marketo 문서 - 제품 설명서'
title: '"웹 페이지로 보기" 메시지 편집'
exl-id: 5541fe6c-7297-4277-8355-ba7b4ac73e2e
source-git-commit: 2776969be44ba1a3d795e99986d10cf0470fb9e9
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 0%

---

# &quot;웹 페이지로 보기&quot; 메시지 편집 {#edit-the-view-as-web-page-message}

를 편집해야 하는 경우[웹 페이지로 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md)&quot;텍스트, 방법이 있습니다.

>[!NOTE]
>
>**관리 권한 필요**

## &quot;웹 페이지로 보기&quot; 메시지 편집 {#edit-the-view-as-web-page-message-1}

1. 로 이동합니다. **관리** 영역.

   ![](assets/edit-the-view-as-web-page-message-1.png)

1. 클릭 **이메일**.

   ![](assets/edit-the-view-as-web-page-message-2.png)

   >[!CAUTION]
   >
   >다음 변수는 매우 중요합니다. 삭제하지 마세요!
   >
   >`%mkt_webview_url%?mkt_tok=##MKT_TOK##`
   >
   >두 번째 부분 `##MKT_TOK##` 는 해당 사용자의 munchkin 쿠키입니다. 이렇게 하면 링크를 클릭할 때 적절하게 쿠키가 생성되는지 확인합니다.

1. 편집 **웹 페이지 HTML으로 보기** 및 **웹 페이지 텍스트로 보기** 버전을 원하는 대로 설정하고 **변경 내용 저장**.

   ![](assets/edit-the-view-as-web-page-message-3.png)

>[!CAUTION]
>
>다음 사항을 방지하십시오.
>
>* HTML 상자에 추가 URL 추가
>* 텍스트 버전에 HTML 넣기


여기 있습니다. 형식을 확인하기 위해 테스트 이메일을 보냅니다.

## 기본 &quot;웹 페이지로 보기&quot; 텍스트 {#default-view-as-web-page-text}

기본 시스템 &quot;웹 페이지로 보기&quot;로 되돌려야 하는 경우 다음을 복사/붙여넣으십시오.

**웹 페이지 HTML으로 보기:**

`<pre data-theme="Confluence"><div style="text-align: center"><font face="Verdana" size="1">To view this email as a web page, <a href="%mkt_webview_url%?mkt_tok=##MKT_TOK##">click here</a></font></div></pre>`

**웹 페이지 텍스트로 보기:**

이 이메일을 웹 페이지로 보려면 다음 주소로 이동합니다.
`<pre data-theme="Confluence">%mkt_webview_url%?mkt_tok=##MKT_TOK##</pre>`

됐습니다.
