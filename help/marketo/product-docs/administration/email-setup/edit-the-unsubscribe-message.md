---
unique-page-id: 2360251
description: 구독 취소 메시지 편집 - Marketo 문서 - 제품 설명서
title: 구독 취소 메시지 편집
exl-id: 68a3ebc1-b2c9-4e6c-bb13-e5a94c9596d2
source-git-commit: 931b42d7266b9c57308567527042dfcad9847993
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---

# 구독 취소 메시지 편집 {#edit-the-unsubscribe-message}

>[!NOTE]
>
>**관리 권한 필요**

마케팅 이메일을 보낼 때(비)[운영](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md)), 구독 취소 텍스트 및 링크가 맨 아래에 추가됩니다. 기본값을 변경할 수 있습니다. 방법은 다음과 같습니다.

## 구독 취소 메시지 편집 {#edit-the-unsubscribe-message-1}

1. 아래 **관리**&#x200B;를 클릭합니다. **이메일**.

   ![](assets/image2014-9-18-16-3a52-3a1.png)

   >[!CAUTION]
   >
   >다음 변수는 매우 중요합니다. 삭제하지 마세요!
   >
   >* `%mkt_opt_out_prefix%`
   >* `mkt_unsubscribe=1&mkt_tok=##MKT_TOK##`


1. 편집 **구독 취소 HTML** 및 **텍스트 구독 취소** 버전을 원하는 대로 설정하고 **변경 내용 저장**.

   ![](assets/image2016-8-26-13-3a40-3a55.png)

   여기 있습니다. _반드시 테스트해 보십시오!_ 마케팅 이메일에 끊어진 구독 취소 링크가 포함되면 안 됩니다.

>[!TIP]
>
>를 사용하여 이메일에서 가입 해지됨 HTML 위치를 사용자 지정할 수 있습니다 [토큰](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md).

## 기본 가입 해지 텍스트 {#default-unsubscribe-text}

기본 시스템 가입 해지로 되돌려야 하는 경우 다음을 복사/붙여넣으십시오.

구독 취소 HTML:
`<pre data-theme="Confluence"><p><font face="Verdana" size="1">If you no longer wish to receive these emails, click on the following link: <a href="%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##">Unsubscribe</a><br/></font></p></pre>` 텍스트 구독 취소:
`<pre data-theme="Confluence">%mkt_opt_out_prefix%UnsubscribePage.html?mkt_unsubscribe=1&mkt_tok=##MKT_TOK##</pre>`

>[!MORELIKETHIS]
>
>[&quot;웹 페이지로 보기&quot; 메시지 편집](/help/marketo/product-docs/administration/email-setup/edit-the-view-as-web-page-message.md)
