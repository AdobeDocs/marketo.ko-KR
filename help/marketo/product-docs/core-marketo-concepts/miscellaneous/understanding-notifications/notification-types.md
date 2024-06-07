---
unique-page-id: 2953243
description: 알림 유형 - Marketo 문서 - 제품 설명서
title: 알림 유형
exl-id: 384cea0a-6252-4600-9211-aa5d6a7e875c
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 1%

---

# 알림 유형 {#notification-types}

몇 가지 알림 유형이 있습니다.

## 캠페인 실패  {#campaign-failure}

캠페인 실패는 스마트 캠페인의 오류를 알려줍니다.

## CRM 동기화 {#crm-sync}

CRM 동기화 알림은 잘못된 권한 또는 동기화 중단과 같은 CRM 동기화와 관련된 중요한 문제를 알려줍니다.

**[!DNL Microsoft Dynamics]**

Dynamics 알림은 24시간마다 한 번씩 전송되며 해당 기간에 동기화되지 않은 잠재 고객을 포함합니다. 일반적인 실패 원인은 중복 잠재 고객(위와 같음) 또는 필드 길이 불일치 오류입니다.

![](assets/image2016-1-20-11-3a19-3a58.png)

**[!DNL Salesforce]**

Salesforce를 사용하는 경우 동기화 오류 알림은 아래와 같이 표시됩니다. 일반적인 오류에는 만료된 자격 증명과 API 제한 초과가 포함됩니다.

![](assets/salesforcesyncerror.png)

## 참여 {#engagement}

사람들이 스트림에서 지치면 알림을 보냅니다. 알림에는 지친 사람 수와 기타 정보가 포함됩니다.

![](assets/image2014-10-14-10-3a57-3a9.png)

## Facebook {#facebook}

서비스 약관에 동의하지 않고 Facebook으로 사람을 보내려고 하거나, Marketo 앱을 제거한 후 Facebook으로 사람을 보내려고 하는 경우.

## 유휴 트리거 캠페인 정리 {#idle-trigger-campaign-cleanup}

더 이상 활동을 가져올 수 없는 트리거된 스마트 캠페인을 비활성화합니다. 자세히 알아보기  [캠페인 자동 정리 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/automatic-trigger-campaign-cleanup.md).

## LinkedIn {#linkedin}

Marketo에서 3회 시도 후 새 대상을 만들거나, 로그인하거나, 이메일을 LinkedIn에 푸시할 수 없는 경우.

![](assets/linkedin.png)

## 웹 서비스 {#web-services}

일일 할당량에 도달하면 알림을 받게 됩니다. 할당량은 매일 밤 중부 표준시로 재설정됩니다.

>[!NOTE]
>
>받을 수 있는 오류 코드 중 일부는 다음에 요약되어 있습니다. [개발자 설명서](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/error-codes).
