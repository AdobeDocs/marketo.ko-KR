---
unique-page-id: 2953373
description: Marketo Sales Insight에서 가입 해지 바닥글 구성 - Marketo 문서 - 제품 설명서
title: Marketo Sales Insight에서 가입 해지 바닥글 구성
exl-id: 16c1fcba-6826-400c-ab7c-371d8653d4ad
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '205'
ht-degree: 0%

---

# Marketo Sales Insight에서 가입 해지 바닥글 구성 {#configure-unsubscribe-footers-in-marketo-sales-insight}

영업 이메일은 자동으로 구독 취소 바닥글을 맨 아래에 추가합니다. 그러나 필요에 맞게 설정을 조정할 수 있습니다.

>[!NOTE]
>
>**관리 권한 필요**

>[!NOTE]
>
>**정의**
>
>**영업 이메일** 는 Sales Insight에서 전송되는 개체입니다(Marketo Outlook 플러그인에서 전송된 것은 포함되지 않음).

1. 로 이동합니다. **관리** 영역.

   ![](assets/one-1.png)

1. 클릭 **Sales Insight**, 그런 다음 **설정 편집**.

   ![](assets/two-1.png)

   몇 가지 옵션이 있습니다. 먼저 설정을 변경할 수 있는 이메일 유형을 살펴보겠습니다.

   ![](assets/three-1.png)

   * **템플릿 없음** - 영업 사용자가 수동으로 구성합니다.
   * **표준 이메일** - 템플릿을 기반으로 한 이메일.
   * **운영 이메일** - 가입 해지됨, 마케팅 일시 중단 및 통신 제한을 무시하는 이메일(어떤 경우에도 보내기).

   각 유형에 대해 서로 다른 동작을 설정할 수 있는 선택 사항이 있습니다.

   >[!CAUTION]
   >
   >**가입 해지 설정 준수**: 구독하지 않은 리드는 게시된 이메일이 &quot;작동 중&quot;인 경우에도 이메일을 받지 않습니다
   >
   >**가입 해지 설정 무시**: 가입 해지된 리드는 이메일을 받게 됩니다

1. 원하는 대로 변경한 다음 **저장**.

   >[!TIP]
   >
   >마지막 두 가지 선택 사항을 사용하면 수신자 수(1보다 크거나 5 보다 큼)에 따라 구독 취소 바닥글을 동적으로 포함/제외할 수 있습니다.

   ![](assets/four-1.png)

휴! 좀 복잡하지만 유연하죠?
