---
description: 자동 추가 구독 취소 메시지 설정 - Marketo 문서 - 제품 설명서
title: 구독 취소 메시지 자동 추가 설정
feature: Sales Insight Actions
exl-id: 17734f62-74e6-4168-a9c8-7835e3daf5ff
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 4%

---

# 구독 취소 메시지 자동 추가 설정 {#auto-append-unsubscribe-message-setting}

보낸 모든 Sales Insight Actions 이메일에 구독 취소 메시지가 포함되어 있으므로 수신자가 커뮤니케이션을 옵트아웃할 수 있는 간편한 옵션을 사용할 수 있습니다. 구독 취소 메시지 추가 가 활성화되면 웹 애플리케이션 및 Salesforce에서 전송된 이메일을 포함하여 Marketo Sales에서 팀이 보내는 모든 통신에 구독 취소 메시지가 포함됩니다.

>[!NOTE]
>
>이메일 템플릿에 `{{team_unsubscribe}}` 동적 필드를 사용하고 구독 취소 메시지 추가 설정이 활성화된 경우 팀 구독 취소 동적 필드가 구독 취소 메시지를 _대신_&#x200B;에 추가합니다.

## 구독 취소 추가 활성화/비활성화 {#enable-disable-unsubscribe-append}

1. 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/auto-append-unsubscribe-message-setting-1.png)

1. 관리자 설정에서 **구독 취소**&#x200B;를 클릭합니다.

   ![](assets/auto-append-unsubscribe-message-setting-2.png)

1. 메시징 탭의 구독 취소 메시지 추가에서 슬라이더를 원하는 상태로 이동합니다.

   ![](assets/auto-append-unsubscribe-message-setting-3.png)

>[!TIP]
>
>구독 취소 메시지 추가 설정을 비활성화하는 경우 템플릿에 구독 취소 바닥글을 추가하여 통신에 옵트아웃 옵션이 있는지 확인하는 것이 좋습니다. 이렇게 하려면 각 템플릿에 사용자 지정 메시지를 추가하거나 `{{team_unsubscribe}}` [동적 필드](/help/marketo/product-docs/marketo-sales-insight/actions/templates/dynamic-fields.md){target="_blank"}를 사용할 수 있습니다.
