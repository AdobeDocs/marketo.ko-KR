---
unique-page-id: 2360245
description: 관리 이메일 섹션 - Marketo 문서 - 제품 설명서에서 구독 취소 텍스트 제거
title: 관리 이메일 섹션에서 텍스트 가입 해지 제거
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
source-git-commit: 2776969be44ba1a3d795e99986d10cf0470fb9e9
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 0%

---

# 관리 이메일 섹션에서 텍스트 가입 해지 제거 {#remove-unsubscribe-text-from-the-admin-email-section}

구독 취소 컨텐츠를 &quot;관리 > 이메일&quot; 영역에서 완전히 제거해야 하는 유일한 이유는 이메일 템플릿 자체에 가입 해지 링크를 만들도록 선택하는 경우에만 입니다. 텍스트 상자에는 콘텐츠가 없는 상태로 저장할 수 없는 유효성 검사가 있습니다. 작은 HTML 설명을 추가하여 이 문제를 해결할 수 있습니다. HTML 주석이 HTML에서 이메일을 렌더링하고 있으며 주석이 생략되므로 이메일 클라이언트에 표시되지 않습니다. 어떻게 하는지 알려드리겠습니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-1.png)

1. 클릭 **이메일**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-2.png)

1. 모든 텍스트를 선택하고 **삭제** 키.

   >[!CAUTION]
   >
   >삭제하기 전에 이 파일을 텍스트 문서에 백업으로 복사/붙여넣으십시오.

1. 입력 `<!--This is a comment -->`.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-3.png)

1. 클릭 **변경 내용 저장**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-4.png)

>[!NOTE]
>
>대상 **텍스트 구독 취소** 단일 문자를 추가해야 합니다. 대시 또는 기간을 사용합니다.
