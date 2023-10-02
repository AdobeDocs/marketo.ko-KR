---
description: 트랜잭션 판매 이메일 템플릿 - Marketo 문서 - 제품 설명서
title: 트랜잭션 판매 이메일 템플릿
hide: true
hidefromtoc: true
feature: Marketo Sales Connect
source-git-commit: ee0f005bb00a7233725d788c318630af90616174
workflow-type: tm+mt
source-wordcount: '161'
ht-degree: 0%

---

# 트랜잭션 판매 이메일 템플릿 {#transactional-sales-email-templates}

팀이 트랜잭션 또는 비상업적 이메일을 보내는 경우 이메일 템플릿을 비상업으로 표시하여 구독 취소를 우회할 수 있습니다.

## 참고할 사항 {#things-to-note}

* 비상업적인 이메일은 판매 구독 취소 및 [Marketo Engage 구독 취소 확인](/help/marketo/product-docs/marketo-sales-connect/email/unsubscribes/marketo-unsubscribe-check.md){target="_blank"}, but will not bypass [blocked domains](/help/marketo/product-docs/marketo-sales-connect/admin/blocked-domains.md){target="_blank"}.

* 구독 취소 메시지는 다음과 같은 경우에도 자동으로 비상업적인 이메일에 추가되지 않습니다. [구독 취소 메시지 관리자 설정 추가](/help/marketo/product-docs/marketo-sales-connect/email/unsubscribes/auto-append-unsubscribe-message-setting.md){target="_blank"} is enabled. However, the `{{team_unsubscribe}}` [dynamic field](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/dynamic-fields-glossary.md){target="_blank"} 팀 구독 취소 메시지가 계속 채워집니다.

## 비상업적 사용을 위한 이메일 템플릿 구성 {#configure-an-email-template-for-non-commercial-use}

1. 헤더에서 를 클릭합니다. **템플릿**.

   ![](assets/transactional-sales-email-templates-1.png)

1. 업데이트할 템플릿을 찾아 선택합니다.

   ![](assets/transactional-sales-email-templates-2.png)

1. 템플릿 설정에서 비상업적인 이메일 토글을 활성화합니다.

   ![](assets/transactional-sales-email-templates-3.png)

## 비상업적인 이메일 보내기 {#send-a-non-commercial-email}

>[!NOTE]
>
>구독 취소한 사람을 선택하면 주황색으로 강조 표시됩니다.

1. 헤더에서 를 클릭합니다. **작성**. 원하는 비상업적 템플릿을 찾아 선택합니다.

   ![](assets/transactional-sales-email-templates-4.png)

1. 사용자에게는 비상업적인 이메일 템플릿을 선택했음을 보여 주는 배너가 표시됩니다.

   ![](assets/transactional-sales-email-templates-5.png)

1. 클릭 **보내기**.

   ![](assets/transactional-sales-email-templates-6.png)

구독을 취소한 경우에도 이메일이 계속 전송됩니다.
