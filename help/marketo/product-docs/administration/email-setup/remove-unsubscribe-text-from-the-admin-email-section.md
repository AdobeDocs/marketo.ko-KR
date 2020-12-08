---
unique-page-id: 2360245
description: '"관리 -> 이메일" 섹션 - Marketing Docs - 제품 문서에서 구독 취소 텍스트 제거'
title: '"관리 -> 이메일" 섹션에서 구독 취소 텍스트 제거'
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 0%

---


# &quot;관리 -> 이메일&quot; 섹션에서 구독 취소 텍스트 제거 {#remove-unsubscribe-text-from-the-admin-email-section}

&quot;관리 > 이메일&quot; 영역에서 구독 취소 컨텐츠를 완전히 제거해야 하는 유일한 이유는 이메일 템플릿 자체에 가입 해지 링크를 만들도록 선택하는 경우에만 가능합니다. 텍스트 상자에 컨텐츠 없이 저장할 수 없는 유효성 검사가 있습니다. 작은 HTML 주석을 추가하여 이 문제를 해결할 수 있습니다. HTML 주석이 HTML로 이메일을 렌더링하고 있으며 주석이 생략되기 때문에 HTML 주석이 이메일 클라이언트에 표시되지 않습니다. 방법

1. 관리자로 **이동하고** 이메일을 **클릭합니다**.

   ![](assets/image2016-8-26-13-3a57-3a9.png)

1. 모든 텍스트를 선택하고 **Delete **키를 누릅니다.

   >[!CAUTION]
   >
   >삭제하기 전에 이를 텍스트 문서에 백업으로 복사/붙여 넣습니다.

1. 입력합니다 **<!--This is a comment -->**.

   ![](assets/image2016-8-26-13-3a53-3a15.png)

1. 변경 내용 **저장을 클릭합니다**.

   ![](assets/image2016-8-26-13-3a59-3a40.png)

>[!NOTE]
>
>**구독 취소 텍스트 **에는 단일 문자를 추가해야 합니다. 대시 또는 기간을 사용합니다.

