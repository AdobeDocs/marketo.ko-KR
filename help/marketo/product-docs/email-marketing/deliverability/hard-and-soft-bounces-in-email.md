---
unique-page-id: 1147328
description: 이메일의 하드 및 소프트 바운스 - Marketo 문서 - 제품 설명서
title: 이메일의 하드 및 소프트 바운스
exl-id: 53298562-76b6-473a-bf9f-2bec682f4d35
feature: Deliverability
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 15%

---

# 이메일의 하드 및 소프트 바운스 {#hard-and-soft-bounces-in-email}

하드 바운스는 메일 서버가 사용자에게 이메일을 전달할 수 없다고 Marketo에 알릴 때 사용자의 이메일 주소를 무효화할 수 있습니다. 소프트 바운스는 사용자에게 이메일을 전달하는 데 문제가 있음을 의미합니다. 이 문제는 자동으로 해결되며 경우에 따라 며칠이 걸릴 수 있습니다. 하드 바운스와 소프트 바운스 모두 [여러 카테고리](https://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838)로 구성됩니다.

## 바운스 분류 {#bounce-classification}

Marketo에는 문제 있는 이메일 게재와 관련된 5가지 유형의 문자열이 있습니다.

1. **전자 메일 일시 중단** - 특정 유형의 하드 바운스가 발생하면 True로 설정합니다.
1. **전자 메일 일시 중단 이유** - 여러 가지 이유가 있습니다. 이 필드는 원인을 설명하려고 합니다.
1. **다음 시간에 전자 메일 일시 중단됨** - 문제가 되는 바운스가 발생하면 Marketo에서 이 타임스탬프부터 24시간 동안 해당 사용자에 대한 메일링을 일시 중단합니다.
1. **전자 메일이 잘못됨** - 특정 유형의 하드 바운스가 발생하면 True로 설정합니다.
1. **전자 메일이 잘못되었습니다.** - 하드 바운스의 원인입니다.

>[!NOTE]
>
>사용자가 **이메일 일시 중단** 상태에 도달하면 이메일 일시 중단 확인란을 지울 수 없습니다. 그러나 최초 운행정지 24시간 후에도 우편물을 배달할 수 있게 됩니다.
>
>사용자가 **유효하지 않은 전자 메일**(으)로 표시된 경우 해당 레코드의 개인 정보 탭에서 &quot;유효하지 않은 전자 메일&quot; 상자를 선택 취소하여 수동으로 재설정할 수 있습니다(특정 전자 메일이 유효한 경우에만 재설정하는 것이 좋습니다).

>[!PREREQUISITES]
>
>[다음 단계](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md)에 따라 바운스 데이터를 생성하는 전자 메일 성능 보고서를 만드십시오.

이메일 성과 보고서를 만들면 화면이 다음과 같이 표시됩니다.

![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>스팸 필터는 경우에 따라 하드 바운스를 만듭니다. 이러한 &quot;긍정 오류(false-positives)&quot;는 해당 사용자 이메일 주소의 실제 유효성을 나타내는 것이 아닙니다.
