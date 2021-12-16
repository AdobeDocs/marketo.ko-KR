---
unique-page-id: 18317340
description: Marketo 가입 해지 확인 - Marketo 문서 - 제품 설명서
title: Marketo 가입 해지 확인
exl-id: b8bd5b38-a4f5-4ac7-a5ce-a155fce57998
source-git-commit: 82c75d52caf3a0320cd3e8534b3b0870cf12d660
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 0%

---

# Marketo 가입 해지 확인 {#marketo-unsubscribe-check}

Marketo 가입 해지 확인은 Marketo에 대한 팀의 연결을 사용하여 Marketo의 리드 관리 시스템에서 구독을 취소한 사람에게 이메일이 전송되지 않도록 합니다. 판매 사용자가 Sales Connect를 사용하여 이메일을 보내면 Marketo에 이메일 ID가 가입 해지되었는지 API 호출이 수행됩니다. 이 경우 이메일이 전송되지 않도록 차단합니다.

>[!NOTE]
>
>**관리 권한 필요**

## 켜기 {#turning-it-on}

1. 웹 응용 프로그램에서 톱니바퀴 아이콘을 클릭하고 **설정**.

   ![](assets/one-2.png)

1. 관리자 설정에서 을 클릭합니다. **가입 해지됨**.

   ![](assets/two-3.png)

1. 클릭 **통합**.

   ![](assets/three-3.png)

1. Marketo 가입 해지 확인 섹션에서 슬라이더를 클릭하여 검사를 활성화합니다.

   ![](assets/four-2.png)

## 알아야 할 사항 {#things-to-know}

Marketo 가입 해지 확인...

* API 제한에 따르지 않습니다
* Marketo 연결을 설정해야 합니다.
* 전역 설정입니다
* 웹 애플리케이션, 이메일 클라이언트 및 Salesforce에서 보낸 이메일을 차단합니다.
* 을(를) 제외한 모든 워크플로우(이메일 플러그인 전송, 개별 전송, 판매 캠페인 전송, 여러 선택 및 보내기)에 대해 보낼 때 실패한 이메일을 기록하거나 사용자가 보내지 못하게 합니다 [그룹 이메일](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md)- 이메일이 자동으로 전송되지 않도록 합니다.
