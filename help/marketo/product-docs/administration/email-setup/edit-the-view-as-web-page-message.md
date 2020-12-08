---
unique-page-id: 2360253
description: '"웹 페이지로 보기" 메시지 편집 - 마케팅 문서 - 제품 설명서'
title: '"웹 페이지로 보기" 메시지 편집'
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 0%

---


# &quot;웹 페이지로 보기&quot; 메시지 편집 {#edit-the-view-as-web-page-message}

&quot;웹 페이지로 [보기&quot; 텍스트를 편집해야](../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md)하는 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

## &quot;웹 페이지로 보기&quot; 메시지 편집 {#edit-the-view-as-web-page-message-1}

1. 관리에서 **이메일을**&#x200B;클릭합니다 ****.

   ![](assets/image2014-9-18-17-3a13-3a2.png)

   >[!CAUTION]
   >
   >다음 변수는 매우 중요합니다. 삭제하지 마십시오!
   >
   >    
   >    
   >    * %mkt_webview_url%?mkt_tok=##MKT_TOK##
   >    
   >    
   >둘째 부분 ##MKT_TOK##은 해당 사람의 문킨 쿠키입니다. 링크를 클릭할 때 적절하게 쿠키를 받을 수 있습니다.

1. 원하는 대로 **보기를 웹 페이지 HTML** 및 **웹 페이지 텍스트로 보기를 편집하고 변경 내용 **저장을 클릭합니다**.

   ![](assets/image2016-8-26-14-3a40-3a29.png)

>[!CAUTION]
>
>다음 사항에 주의하십시오.
>
>* HTML 상자 중 하나에 추가 URL 추가
>* 텍스트 버전에 HTML 추가

>



여기 있습니다. 테스트 이메일을 전송하여 서식을 지정할 수 있습니다.

## 기본 &quot;웹 페이지로 보기&quot; 텍스트 {#default-view-as-web-page-text}

기본 시스템 &quot;웹 페이지로 보기&quot;로 되돌려야 하는 경우 다음을 복사/붙여 넣습니다.

**웹 페이지 HTML로 보기:**`<pre data-theme="Confluence"><div style="text-align: center"><font face="Verdana" size="1">To view this email as a web page, <a href="%mkt_webview_url%?mkt_tok=##MKT_TOK##">click here</a></font></div></pre>` **웹 페이지 텍스트로 보기:**

이 이메일을 웹 페이지로 보려면 다음 주소로 이동합니다.`<pre data-theme="Confluence">%mkt_webview_url%?mkt_tok=##MKT_TOK##</pre>` 쾅! 이제 모든 작업이 끝났습니다.
