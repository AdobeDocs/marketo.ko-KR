---
description: Marketo 가입 해지 확인 - Marketo 문서 - 제품 설명서
title: Marketo 가입 해지 확인
exl-id: 3c242d04-cf6c-466b-9bcd-e77c6d97d308
source-git-commit: d9b8b92ac5f051178b8eb9b450c4949b56d50b99
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---

# Marketo 가입 해지 확인 {#marketo-unsubscribe-check}

Marketo 가입 해지 확인은 Marketo에 대한 팀의 연결을 사용하여 Marketo의 리드 관리 시스템에서 구독을 취소한 사람에게 이메일이 전송되지 않도록 합니다. 판매 사용자가 Marketo Sales로 이메일을 보내면 이메일 ID가 가입 해지되었는지 확인하기 위해 Marketo에 API 호출이 수행됩니다. 이 경우 이메일이 전송되지 않도록 차단합니다.

>[!NOTE]
>
>**관리 권한 필요**

## 켜기 {#turning-it-on}

1. 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/marketo-unsubscribe-check-1.png)

1. 관리자 설정에서 을 클릭합니다. **가입 해지됨**.

   ![](assets/marketo-unsubscribe-check-2.png)

1. 을(를) 클릭합니다. **통합** 탭. Marketo 가입 해지 확인 섹션에서 슬라이더를 클릭하여 검사를 활성화합니다.

   ![](assets/marketo-unsubscribe-check-3.png)

## 알아야 할 사항 {#things-to-know}

Marketo 가입 해지 확인...

* API 제한에 따르지 않습니다
* Marketo 연결을 설정해야 합니다.
* 전역 설정입니다
* 웹 애플리케이션, 이메일 클라이언트 및 Salesforce에서 보낸 이메일을 차단합니다.
