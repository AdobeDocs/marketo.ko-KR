---
unique-page-id: 1147328
description: 이메일의 하드 및 소프트 바운스 수 - 마케팅 문서 - 제품 설명서
title: 이메일의 하드 및 소프트 바운스 수
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---


# 이메일 {#hard-and-soft-bounces-in-email}의 하드 바운스 및 소프트 바운스

이메일 서버가 사용자의 이메일을 배달할 수 없다고 Marketing Cloud에 알릴 때 하드 바운스는 사람의 이메일 주소를 잘못 렌더링할 수 있습니다. 바운스는 해당 고객에게 이메일을 전달하는 과정에서 잘못된 것을 의미합니다.이러한 문제를 자동으로 해결하면 몇 일이 걸릴 수 있습니다. 하드 바운스와 소프트 바운스는 모두 [여러 카테고리](http://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838)로 구성됩니다.

## 바운스 분류 {#bounce-classification}

Marketing To에는 문제가 있는 이메일 전달과 관련된 5개의 사람 문자열이 있습니다.

1. **이메일 일시 중단됨**  - 특정 유형의 하드 바운스가 발생하면 True로 설정됩니다.
1. **이메일 일시 중단 원인**  - 많은 이유가 있을 수 있습니다. 이 필드는 원인을 설명하려고 합니다.
1. **다음에서 일시 중단된 이메일 **- 문제가 발생하는 경우 Marketing Cloud는 이 타임스탬프에서 24시간 동안 사용자에게 메일을 일시 중단합니다.
1. **이메일 잘못됨**  - 특정 유형의 하드 바운스가 발생하면 True로 설정됩니다.
1. **이메일 잘못된 원인**  - 하드 바운스의 이유입니다.

>[!NOTE]
>
>한 사람이 **전자 메일 일시 중단된** 상태에 도달하면 일시 중단된 전자 메일 확인란을 해제할 수 없습니다. 그러나, 이 사람은 첫 번째 중단 이후 24시간 동안 우편 배달이 가능하다.
>
>사용자가 **전자 메일 invalid**&#x200B;로 표시된 경우, 본인의 레코드의 [개인 정보] 탭에서 &quot;잘못된 이메일&quot; 상자를 선택 취소하여 수동으로 재설정할 수만 있습니다(해당 이메일이 유효한 경우 알고 있는 경우에만 권장됨).

>[!PREREQUISITES]
>
>바운스 데이터를 생성하는 이메일 성능 보고서를 만들려면 [다음 단계](../../../product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md)를 따릅니다.

이메일 성능 보고서를 만든 후 화면이 다음과 같아야 합니다.![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>스팸 필터는 때로 하드 바운스를 만듭니다. 이러한 &quot;거짓&quot;은 이메일 주소의 진정한 유효성을 나타내는 것이 아니다.

