---
unique-page-id: 18317340
description: Marketo 구독 취소 확인 - Marketo 문서 - 제품 설명서
title: Marketo 구독 취소 확인
exl-id: b8bd5b38-a4f5-4ac7-a5ce-a155fce57998
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 0%

---

# Marketo 구독 취소 확인 {#marketo-unsubscribe-check}

Marketo 구독 취소 검사는 Marketo에 대한 팀의 연결을 사용하여 Marketo의 리드 관리 시스템에서 구독을 취소하는 사람에게 이메일이 전송되지 않도록 합니다. 영업 사용자가 Sales Connect를 통해 이메일을 보내면 Marketo에 API 호출이 수행되어 이메일 ID의 구독 취소 여부를 확인합니다. 이 경우 이메일이 전송되지 않도록 차단합니다.

>[!NOTE]
>
>**관리자 권한 필요**

## 켜기 {#turning-it-on}

1. 웹 응용 프로그램에서 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-2.png)

1. 관리자 설정에서 **구독 취소**&#x200B;를 클릭합니다.

   ![](assets/two-3.png)

1. **통합**&#x200B;을 클릭합니다.

   ![](assets/three-3.png)

1. Marketo 구독 취소 확인 섹션에서 슬라이더를 클릭하여 확인을 활성화합니다.

   ![](assets/four-2.png)

## 알아야 할 사항 {#things-to-know}

Marketo 구독 취소 확인...

* API 제한에 포함되지 않음
* Marketo 연결을 설정해야 합니다.
* 전역 설정임
* 웹 애플리케이션, 이메일 클라이언트 및 Salesforce에서 전송된 이메일 차단
* 실패한 이메일을 기록하거나 사용자가 [그룹 이메일](/help/marketo/product-docs/marketo-sales-connect/email/using-the-compose-window/composing-bulk-emails-with-select-and-send.md)을(를) 제외한 모든 워크플로우(이메일 플러그인 보내기, 개별 보내기, 판매 캠페인 보내기, 다중 선택 및 보내기)에 대해 보내려고 하면 사용자가 보내지 못하게 합니다. 이렇게 하면 이메일이 자동으로 전송되지 않습니다.
