---
unique-page-id: 2360251
description: 구독 취소 메시지 편집 - 마케팅 문서 - 제품 설명서
title: 구독 취소 메시지 편집
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---


# 구독 취소 메시지 편집 {#edit-the-unsubscribe-message}

>[!NOTE]
>
>**관리자 권한 필요**

마케팅 이메일을 보낼 때( [작동](../../../product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md)안 함), 구독 취소 텍스트와 링크가 하단에 추가됩니다. 기본값을 변경할 수 있습니다. 방법

## 구독 취소 메시지 편집 {#edit-the-unsubscribe-message-1}

1. 관리에서 **이메일을**&#x200B;클릭합니다 ****.

   ![](assets/image2014-9-18-16-3a52-3a1.png)

   >[!CAUTION]
   >
   >
   >다음 변수는 매우 중요합니다. 삭제하지 마십시오!
   >
   >    
   >    
   >    * **%mkt_opt_out_prefix%**
   >    * **mkt_unsubscribe=1&amp;mkt_tok=##MKT_TOK##**


1. 원하는 대로 **HTML** 구독 취소 및 **텍스트** 구독 취소 버전을 편집하고 변경 내용 **저장을**&#x200B;클릭합니다.

   ![](assets/image2016-8-26-13-3a40-3a55.png)

   여기 있습니다. **반드시 테스트하십시오!** 마케팅 이메일에 구독 취소 링크가 끊기는 것을 원하지 않습니다.

>[!TIP]
>
>토큰을 사용하여 이메일의 구독 취소 HTML의 위치를 사용자 지정할 수 [있습니다](../../../product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md).

## 기본 구독 취소 텍스트 {#default-unsubscribe-text}

기본 시스템 가입 해지로 돌아가야 하는 경우 다음을 복사/붙여 넣습니다.

HTML 구독 취소:`<pre data-theme="Confluence"><p><font face="Verdana" size="1">If you no longer wish to receive these emails, click on the following link: <a href="%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##">Unsubscribe</a><br/></font></p></pre>` 텍스트 구독 취소:
`<pre data-theme="Confluence">%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##</pre>`

>[!MORELIKETHIS]
>
>* [&quot;웹 페이지로 보기&quot; 메시지 편집](edit-the-view-as-web-page-message.md)

>



