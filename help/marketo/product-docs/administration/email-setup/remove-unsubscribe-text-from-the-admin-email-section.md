---
unique-page-id: 2360245
description: 관리자 이메일 섹션에서 구독 취소 텍스트 제거 - Marketo 문서 - 제품 설명서
title: 관리자 이메일 섹션에서 구독 취소 텍스트 제거
exl-id: 2961a9b6-8b35-4227-bf8a-a07b2664a6c4
source-git-commit: 81ee349dbbe48c70b040751cae750c3684b71c78
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 0%

---

# 관리자 이메일 섹션에서 구독 취소 텍스트 제거 {#remove-unsubscribe-text-from-the-admin-email-section}

에서 구독 취소 콘텐츠를 완전히 제거해야 하는 유일한 이유 **[!UICONTROL 관리자]** > **[!UICONTROL 이메일]** 영역은 구독 취소 링크를 이메일 템플릿 자체에 빌드하도록 선택하는 경우입니다. 텍스트 상자에 유효성 검사가 있어 콘텐츠 없이 저장할 수 없습니다. 여기에 작은 HTML 댓글을 추가하면 알 수 있습니다. HTML 주석은 HTML으로 이메일을 렌더링하고 주석이 생략되므로 이메일 클라이언트에 표시되지 않습니다. 방법은 다음과 같습니다.

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-1.png)

1. 클릭 **[!UICONTROL 이메일]**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-2.png)

1. 텍스트를 모두 선택하고 **[!UICONTROL 삭제]** 키.

   >[!CAUTION]
   >
   >삭제하기 전에 텍스트 문서에 백업으로 복사/붙여넣습니다.

1. 입력 `<!--This is a comment -->`.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-3.png)

1. 클릭 **[!UICONTROL 변경 내용 저장]**.

   ![](assets/remove-unsubscribe-text-from-the-admin-email-section-4.png)

>[!NOTE]
>
>의 경우 **구독 취소 텍스트** 단일 문자를 추가해야 합니다. 대시 또는 마침표를 사용합니다.
