---
unique-page-id: 1147328
description: 이메일의 하드 및 소프트 바운스 - Marketo 문서 - 제품 설명서
title: 이메일의 하드 및 소프트 바운스
exl-id: 53298562-76b6-473a-bf9f-2bec682f4d35
feature: Deliverability
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---

# 이메일의 하드 및 소프트 바운스 {#hard-and-soft-bounces-in-email}

하드 바운스로 인해 메일 서버가 Marketo에 개인 이메일을 배달할 수 없다고 지시할 때 개인 이메일 주소가 유효하지 않게 될 수 있습니다. 소프트 바운스는 사용자에게 이메일을 전달하는 데 문제가 있음을 의미합니다. 이 문제는 자동으로 해결되며 경우에 따라 며칠이 걸릴 수 있습니다. 하드 바운스와 소프트 바운스는 모두 다음으로 구성됩니다. [여러 범주](https://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838).

## 바운스 분류 {#bounce-classification}

Marketo에는 문제 있는 이메일 게재와 관련된 5가지 유형의 문자열이 있습니다.

1. **이메일 일시 중단됨** - 특정 유형의 하드 바운스가 발생하면 True로 설정합니다.
1. **이메일 일시 중단 원인** - 많은 이유가 있을 수 있습니다. 이 필드는 원인을 설명하려고 합니다.
1. **다음 시간에 이메일 일시 중단됨** - 문제가 되는 바운스가 발생하면 Marketo은 이 타임스탬프에서 24시간 동안 해당 사용자로의 메일링을 일시 중단합니다.
1. **이메일 잘못됨** - 특정 유형의 하드 바운스가 발생하면 True로 설정합니다.
1. **잘못된 이메일 원인** - 하드 바운스의 원인.

>[!NOTE]
>
>다음 시간 이후 **이메일 일시 중단됨** 상태, 이메일 일시 중단 확인란을 선택 취소하는 방법이 없습니다. 그러나 최초 운행정지 24시간 후에도 우편물을 배달할 수 있게 됩니다.
>
>개인이 다음으로 표시된 경우 **이메일 잘못됨**, 이러한 전자 메일은 레코드의 개인 정보 탭에서 &quot;이메일 잘못됨&quot; 상자를 선택 취소하여 수동으로 재설정할 수만 있습니다(특정 전자 메일이 유효한 경우에만 아는 경우).

>[!PREREQUISITES]
>
>팔로우 [다음 단계](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md) 바운스 데이터를 생성하는 이메일 성능 보고서를 만듭니다.

이메일 성과 보고서를 만들면 화면이 다음과 같이 표시됩니다.

![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>스팸 필터는 경우에 따라 하드 바운스를 만듭니다. 이러한 &quot;긍정 오류(false-positives)&quot;는 해당 사용자 이메일 주소의 실제 유효성을 나타내는 것이 아닙니다.
