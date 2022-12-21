---
description: 개인 계정 동기화 FAQ - Marketo 문서 - 제품 설명서
title: 개인 계정 동기화 FAQ
exl-id: b77bb44f-94d0-40b2-9955-9636421ac468
source-git-commit: bb020cba0bb0cb65761e15cba05147b6e9fffe50
workflow-type: tm+mt
source-wordcount: '489'
ht-degree: 0%

---

# 개인 계정 동기화 FAQ {#person-account-sync-faq}

Marketo Engage은 전체 데이터베이스를 개인 계정 유형의 레코드에 대한 Vevar와 동기화합니다. 동기화 후 5분을 기다린 다음, 하루 종일 다시 동기화합니다.

조직의 요구 사항에 맞게 Veeva에서 개인 계정을 설정할 수 있습니다.

>[!NOTE]
>
>&quot;Professional&quot; 계층 계정만 개인 계정으로 동기화합니다.

**개인 계정이란 무엇입니까?**

개인 계정은 Veeva CRM의 계정 개체와 매우 유사합니다. 그러나 개인 계정은 계정 필드와 연락처 필드 모두에 액세스할 수 있습니다.

**개인 계정이 Marketo에 동기화되면 어떻게 됩니까?**

개인 계정은 회사 및 개인으로서 Marketo에 동기화됩니다.

>[!NOTE]
>
>개인 계정에 대한 사용자 지정 필드는 Marketo의 회사와 개인 모두에 복사됩니다.

**비즈니스 계정과 개인 계정을 어떻게 구분합니까?**

Smart List의 &quot;개인&quot; 계정 필터를 사용하여 개인 계정을 표준 비즈니스 계정과 구분하십시오.

**개인 계정에 사용할 이메일 필드는 무엇입니까?**

개인 계정에 대한 두 개의 이메일 필드가 있습니다. 양식(개인 이메일 주소 아님)의 이메일 주소 필드를 사용하여 Marketo의 중복 제거 및 기타 이메일 처리가 제대로 작동하는지 확인합니다.

## 동기화 방향 {#sync-direction}

개인 계정의 연락처 관련 필드 동기화는 양방향 필드입니다. Veva CRM 또는 Marketo에서 연락처를 변경하면 업데이트가 두 시스템 모두에 반영됩니다. 계정의 필드는 Vec CRM에서 Marketo에 대해 한 방향으로만 동기화됩니다.

**두 시스템에서 개인 계정의 연락처 필드를 동시에 변경하면 어떻게 됩니까?**

우린 괜찮을거야. 그리고 베에바 CRM이 이길 수 있게. 그러나 이런 종류의 데이터 충돌이 발생하는 것은 드문 일이다.

**Lead 또는 Contact 유형의 레코드가 Veeva CRM에 동기화됩니까?**

Veva CRM은 개인 계정 개체만 처리하고 비즈니스 계정도 포함합니다. 기존의 Lead, Contact 및 Opportunity 의 기존 CRM 유형은 기존 Veeva CRM 시스템에서 실제로 사용되지 않습니다. 이러한 구성 요소는 Veva CRM에서 만들 수 있지만 이 커넥터를 사용하여 공식적으로 지원되지 않습니다.

**Marketo에서 사람을 연락처로 변환할 수 있습니까?**

아니요. Lead 및 Contact 는 Veva CRM과의 동기화를 위해 지원되지 않습니다. 따라서 전환이 지원되지 않습니다.

**수동으로 연락처 동기화를 수행할 수 있습니까?**

아니요. Contact는 독립적인 유형의 레코드가 아니므로 Vevar에 개인 동기화가 지원되지 않습니다.

**모든 표준 필드가 Marketo과 동기화됩니까?**

아니요. 모든 표준 필드가 유용하지는 않습니다. 모든 사용자 지정 필드는 동기화의 일부일 수 있습니다.

>[!NOTE]
>
>Marketo은 Marketo 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

**Marketo이 Veva 유효성 검사 규칙을 준수합니까?**

예, 충돌이 있으면 리드의 활동 로그에 결과를 기록합니다.

>[!MORELIKETHIS]
>
>* [기본 경험 필드 매핑](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/default-veeva-field-mapping.md){target=&quot;_blank&quot;}
>* [호출 및 호출 키 메시지 동기화](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target=&quot;_blank&quot;}

