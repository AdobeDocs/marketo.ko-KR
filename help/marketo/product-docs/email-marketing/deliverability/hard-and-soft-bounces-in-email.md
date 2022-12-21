---
unique-page-id: 1147328
description: 이메일의 하드 및 소프트 바운스 수 - Marketo 문서 - 제품 설명서
title: 이메일의 하드 및 소프트 바운스 수
exl-id: 53298562-76b6-473a-bf9f-2bec682f4d35
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---

# 이메일의 하드 및 소프트 바운스 수 {#hard-and-soft-bounces-in-email}

이메일 서버가 사용자의 이메일을 배달할 수 없다고 Marketo에 알려줄 때 하드 바운스는 사람의 이메일 주소를 유효하지 않게 렌더링할 수 있습니다. 소프트 바운스는 사람에게 이메일을 전달하는 데 잘못된 내용이 있음을 의미합니다. 이 문제는 자동으로 해결되며 때로는 며칠이 걸릴 수 있습니다. 하드 바운스와 소프트 바운스는 모두 [여러 범주](https://nation.marketo.com/t5/Knowledgebase/Maintaining-a-Directory-of-Leads-Bouncing-Emails/ta-p/300838).

## 바운스 분류 {#bounce-classification}

Marketo에는 문제 있는 이메일 게재와 관련된 5개의 개인 문자열이 있습니다.

1. **전자 메일 일시 중단** - 특정 유형의 하드 바운스가 발생하면 True로 설정합니다.
1. **전자 메일 일시 중단 원인** - 여러 가지 이유가 있을 수 있습니다. 이 필드는 원인을 설명하려고 합니다.
1. **이메일 일시 중단 위치** - 잘못된 바운스가 발생하면 Marketo에서 이 타임스탬프에서 24시간 동안 사람에게 메일을 일시 중단합니다.
1. **이메일이 잘못되었습니다.** - 특정 유형의 하드 바운스가 발생하면 True로 설정합니다.
1. **전자 메일 잘못된 원인** - 하드 바운스의 이유

>[!NOTE]
>
>사람이 도달한 후 **이메일 일시 중단됨** 상태: 일시 중단된 전자 메일 확인란을 지울 방법이 없습니다. 하지만, 그 사람은 첫 정지 후 24시간 후에도 우편 배달이 될 것이다.
>
>개인이 **잘못된 이메일**&#x200B;를 채울 때는 레코드의 개인 정보 탭에서 &quot;잘못된 이메일&quot; 상자를 선택 취소하여 수동으로 재설정할 수만 있습니다(해당 이메일이 유효한 경우 알고 있는 경우에만 권장).

>[!PREREQUISITES]
>
>팔로우 [다음 단계](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md) 바운스 데이터를 생성하는 이메일 성과 보고서를 만들려면

이메일 성과 보고서를 만든 후 화면은 다음과 같아야 합니다.

![](assets/soft-hard-bounce.png)

>[!NOTE]
>
>스팸 필터는 때로 하드 바운스를 만듭니다. 이러한 &quot;긍정 오류&quot;는 개인 이메일 주소의 실제 유효성을 나타내는 것이 아닙니다.
