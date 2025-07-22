---
description: 개인 계정 동기화 FAQ - Marketo 문서 - 제품 설명서
title: 개인 계정 동기화 FAQ
exl-id: b77bb44f-94d0-40b2-9955-9636421ac468
feature: Veeva CRM
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '472'
ht-degree: 0%

---

# 개인 계정 동기화 FAQ {#person-account-sync-faq}

Marketo Engage은 레코드의 개인 계정 유형에 대해 전체 데이터베이스를 [!DNL Veeva]과(와) 동기화합니다. 동기화 후 5분 동안 기다렸다가 다시 동기화합니다(하루 종일, 매일).

조직의 필요에 맞게 [!DNL Veeva]에서 개인 계정을 설정할 수 있습니다.

>[!NOTE]
>
>&quot;Professional&quot; 계층 계정만 개인 계정으로 동기화합니다.

**개인 계정이란?**

사용자 계정이 [!DNL Veeva] CRM의 계정 개체와 매우 유사합니다. 단, 개인 계정은 계정 필드와 연락처 필드 모두에 액세스할 수 있습니다.

**개인 계정이 Marketo에 동기화되면 어떻게 됩니까?**

개인 계정은 회사 및 개인으로 Marketo에 동기화됩니다.

>[!NOTE]
>
>개인 계정에 대한 사용자 정의 필드는 Marketo의 회사와 사용자 모두에게 복사됩니다.

**비즈니스 계정과 개인 계정을 어떻게 구분합니까?**

스마트 목록의 &quot;개인 계정&quot; 필터를 사용하여 개인 계정을 표준 비즈니스 계정과 구분합니다.

**개인 계정에 어떤 전자 메일 필드를 사용해야 합니까?**

개인 계정에는 두 개의 이메일 필드가 있습니다. 양식의 이메일 주소 필드(개인 이메일 주소가 아님)를 사용하여 Marketo의 중복 제거 및 기타 이메일 처리가 제대로 작동하도록 합니다.

## 동기화 방향 {#sync-direction}

개인 계정의 연락처 관련 필드 동기화는 양방향입니다. [!DNL Veeva] CRM 또는 Marketo에서 연락처를 변경하면 업데이트가 두 시스템에 모두 반영됩니다. 계정의 필드는 [!DNL Veeva] CRM에서 Marketo으로 한 방향으로만 동기화됩니다.

**두 시스템에서 동시에 개인 계정의 연락처 필드가 변경되면 어떻게 합니까?**

[!DNL Veeva]개의 CRM이 성공하도록 하겠습니다. 그러나 이러한 데이터 충돌이 발생하는 경우는 거의 없습니다.

**잠재 고객 또는 연락처 유형의 레코드가 [!DNL Veeva] CRM과 동기화됩니까?**

[!DNL Veeva] CRM은 실제 개인 계정 개체만 취급하고 비즈니스 계정도 가지고 있습니다. 기존 [!DNL Veeva] CRM 시스템에서는 기존 CRM 유형의 잠재 고객, 연락처 및 기회를 실제로 사용하지 않습니다. 이러한 ID는 [!DNL Veeva] CRM에서 만들 수 있지만 이 커넥터를 사용하여 공식적으로 지원되지 않습니다.

**Marketo에서 사용자를 연락처로 전환할 수 있습니까?**

[!DNL Veeva] CRM과의 동기화에 대해 Lead 및 Contact는 지원되지 않으므로 지원되지 않습니다. 따라서 전환은 지원되지 않습니다.

**연락처의 동기화를 수동으로 강제할 수 있습니까?**

아니요. 연락처는 독립적인 레코드 종류가 아니므로 [!DNL Veeva]&#x200B;(으)로의 개인 동기화는 지원되지 않습니다.

**모든 단일 표준 필드가 Marketo에 동기화됩니까?**

아니요. 모든 표준 필드가 유용한 것은 아닙니다. 모든 사용자 지정 필드는 동기화의 일부가 될 수 있습니다.

>[!NOTE]
>
>Marketo은 Marketo 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

**Marketo에서 [!DNL Veeva] 유효성 검사 규칙을 준수합니까?**

예. 충돌이 발생하면 잠재 고객의 Activity Log에 결과를 기록합니다.

>[!MORELIKETHIS]
>
>* [기본 [!DNL Veeva] 필드 매핑](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/default-veeva-field-mapping.md){target="_blank"}
>* [통화 및 통화 키 메시지 동기화](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
