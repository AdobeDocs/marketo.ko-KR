---
description: Marketo 구독 취소 확인 - Marketo 문서 - 제품 설명서
title: Marketo 구독 취소 확인
exl-id: 3c242d04-cf6c-466b-9bcd-e77c6d97d308
feature: Sales Insight Actions
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---

# Marketo 구독 취소 확인 {#marketo-unsubscribe-check}

Marketo 구독 취소 검사는 Marketo에 대한 팀의 연결을 사용하여 Marketo의 리드 관리 시스템에서 구독을 취소하는 사람에게 이메일이 전송되지 않도록 합니다. 영업 사용자가 Marketo Sales로 이메일을 보내면 Marketo에 API 호출이 수행되어 이메일 ID의 구독 취소가 있는지 확인합니다. 이 경우 이메일이 전송되지 않도록 차단합니다.

>[!NOTE]
>
>**관리자 권한 필요**

## 켜기 {#turning-it-on}

1. 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/marketo-unsubscribe-check-1.png)

1. 관리자 설정에서 **구독 취소**&#x200B;를 클릭합니다.

   ![](assets/marketo-unsubscribe-check-2.png)

1. **통합** 탭을 클릭합니다. Marketo 구독 취소 확인 섹션에서 슬라이더를 클릭하여 확인을 활성화합니다.

   ![](assets/marketo-unsubscribe-check-3.png)

## 알아야 할 사항 {#things-to-know}

Marketo 구독 취소 확인...

* API 제한에 포함되지 않음
* Marketo 연결을 설정해야 합니다.
* 전역 설정임
* 웹 애플리케이션, 이메일 클라이언트 및 Salesforce에서 전송된 이메일 차단
