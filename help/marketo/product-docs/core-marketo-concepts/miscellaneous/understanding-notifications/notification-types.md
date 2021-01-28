---
unique-page-id: 2953243
description: 알림 유형 - 마케팅 문서 - 제품 설명서
title: 알림 유형
translation-type: tm+mt
source-git-commit: e5050328cbddaf072dd60ddd8d7363a704e720b5
workflow-type: tm+mt
source-wordcount: '246'
ht-degree: 0%

---


# 알림 유형 {#notification-types}

여러 가지 알림 유형이 있습니다.

## 캠페인 실패 {#campaign-failure}

캠페인 실패로 인해 스마트 캠페인의 오류가 표시됩니다.

## CRM 동기화 {#crm-sync}

CRM 동기화 알림은 잘못된 권한 또는 동기화가 중단되는 등 CRM 동기화 시 발견된 중요한 문제를 알려줍니다.

**Microsoft Dynamics**

Dynamics 알림은 24시간마다 한 번 전송되며 해당 기간에 동기화하지 못한 리드가 포함됩니다. 실패의 일반적인 원인은 리드 중복(위와 같이) 또는 필드 길이 불일치 오류입니다.

![](assets/image2016-1-20-11-3a19-3a58.png)

**Salesforce**

Salesforce를 사용하는 경우 동기화 오류 알림은 아래와 같습니다. 일반적인 오류는 만료된 자격 증명과 API 제한을 초과했습니다.

![](assets/salesforcesyncerror.png)

참여

리드가 스트림에 고갈되면 알림을 보냅니다.  알림에는 지친 리드 수와 기타 정보가 포함됩니다.

![](assets/image2014-10-14-10-3a57-3a9.png)

Facebook

서비스 약관에 동의하지 않고 리드를 Facebook으로 보내려고 하거나 Marketing To 앱을 제거한 후 리드를 Facebook으로 보내려고 하는 경우.

유휴 트리거 캠페인 정리

더 이상 활동이 없는 트리거된 스마트 캠페인 비활성화. [자동 트리거 캠페인 정리](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/automatic-trigger-campaign-cleanup.md)에 대해 자세히 알아보십시오.

LinkedIn

3번 시도해도 Marketing에서 새 대상을 만들거나, 로그인하거나, 이메일을 LinkedIn에 푸시할 수 없는 경우.

![](assets/linkedin.png)

웹 서비스

일별 할당량에 도달하면 알림을 받게 됩니다. 할당량은 매일 밤 중부 시간으로 재설정됩니다.

>[!NOTE]
>
>받을 수 있는 오류 코드 중 일부는 [개발자 설명서](https://developers.marketo.com/rest-api/error-codes/#response_level_error_codes)에 요약되어 있습니다.
