---
description: 자동 추가 구독 취소 메시지 설정 - Marketo 문서 - 제품 설명서
title: 자동 추가 구독 취소 메시지 설정
hide: true
hidefromtoc: true
feature: Marketo Sales Connect
source-git-commit: b0f62abfe04efd8e72ed8e92442d4a46ea118f33
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 0%

---

# 자동 추가 구독 취소 메시지 설정 {#auto-append-unsubscribe-message-setting}

보낸 모든 이메일에 구독 취소 메시지가 포함되어 있으므로 수신자는 커뮤니케이션을 거부할 수 있습니다. 구독 취소 메시지 추가가 활성화되면 팀이 Marketo Sales에서 보내는 모든 커뮤니케이션에 웹 애플리케이션에서 보낸 이메일, Salesforce, Gmail 플러그인 및 Outlook 플러그인을 포함한 구독 취소 메시지가 포함됩니다.

## 참고할 사항 {#things-to-note}

* 플러그인에서 보낸 이메일의 경우, 구독 취소는 템플릿을 사용할 때만 추가됩니다.

* 를 사용하는 경우 `{{team_unsubscribe}}` 이메일 템플릿의 동적 필드 및 구독 취소 메시지 추가 설정이 활성화된 경우 팀 구독 취소 동적 필드에 구독 취소 메시지가 채워집니다 _대신_ 구독 취소 메시지를 추가합니다.

## 구독 취소 추가 활성화/비활성화 {#enable-disable-unsubscribe-append}

1. 톱니바퀴 아이콘을 클릭하고 **설정**.

   ![](assets/auto-append-unsubscribe-message-setting-1.png)

1. Admin Settings 아래에서 **구독 취소**.

   ![](assets/auto-append-unsubscribe-message-setting-2.png)

1. 메시징 탭의 구독 취소 메시지 추가에서 슬라이더를 원하는 상태로 이동합니다.

   ![](assets/auto-append-unsubscribe-message-setting-3.png)

>[!TIP]
>
>구독 취소 메시지 추가 설정을 비활성화하는 경우 템플릿에 구독 취소 바닥글을 추가하여 통신에 옵트아웃 옵션이 있는지 확인하는 것이 좋습니다. 이렇게 하려면 각 템플릿에 고유한 사용자 지정 메시지를 추가하거나 다음을 사용할 수 있습니다. `{{team_unsubscribe}}` 동적 필드.