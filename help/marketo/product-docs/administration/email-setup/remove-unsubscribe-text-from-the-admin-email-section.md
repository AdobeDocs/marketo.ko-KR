---
unique-page-id: 2360245
description: 템플릿에 링크를 작성할 때 HTML 주석을 사용하여 관리자 이메일에서 기본 구독 취소 콘텐츠를 제거합니다.
title: 관리자 이메일 섹션에서 구독 취소 텍스트 제거
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
feature: Email Setup
source-git-commit: e894ece3a643113fd3e1d8df9f8addefea5553f5
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 3%

---

# 관리자 > 이메일 섹션에서 구독 취소 텍스트 제거 {#remove-unsubscribe-text-from-the-admin-email-section}

**[!UICONTROL Admin]** > **[!UICONTROL Email]** 영역에서 구독 취소 콘텐츠를 완전히 제거해야 하는 유일한 이유는 이메일 템플릿 자체에 구독 취소 링크를 빌드하도록 선택하는 경우입니다. 텍스트 상자에 유효성 검사가 있어 콘텐츠 없이 저장할 수 없습니다. 작은 HTML 주석을 추가하여 이 문제를 해결할 수 있습니다. HTML 주석은 HTML에서 이메일을 렌더링하고 주석이 생략되므로 이메일 클라이언트에 표시되지 않습니다. 방법은 다음과 같습니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-1.png)

1. **[!UICONTROL Email]**&#x200B;를 클릭합니다.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-2.png)

1. 모든 텍스트를 선택하고 **[!UICONTROL Delete]** 키를 누릅니다.

   >[!CAUTION]
   >
   >삭제하기 전에 텍스트 문서에 백업으로 복사/붙여넣습니다.

1. `<!--This is a comment -->`에 입력하십시오.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-3.png)

1. **[!UICONTROL Save Changes]**&#x200B;를 클릭합니다.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-4.png)

>[!NOTE]
>
>**텍스트 구독 취소**&#x200B;의 경우 한 글자를 추가해야 합니다. 대시 또는 마침표를 사용합니다.
