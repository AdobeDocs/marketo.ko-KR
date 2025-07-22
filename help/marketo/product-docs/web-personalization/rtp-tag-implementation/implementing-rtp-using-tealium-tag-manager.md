---
unique-page-id: 9437340
description: Tealium Tag Manager를 사용하여 RTP 구현 - Marketo 문서 - 제품 설명서
title: Tealium Tag Manager를 사용하여 RTP 구현
exl-id: 7a099184-625c-46b2-a741-3bcdad0a238e
feature: Web Personalization
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 1%

---

# [!DNL Tealium] 태그 관리자를 사용하여 RTP 구현 {#implementing-rtp-using-tealium-tag-manager}

RTP 태그를 구현하려면 아래의 설치 지침을 따르십시오.

1. [!DNL Tealium] 태그 관리자 계정에 로그인합니다.

1. [!UICONTROL Tags] 탭으로 이동하여 태그 마켓플레이스의 [!UICONTROL Tealium Custom Container Tag] 탭에 있는 [!UICONTROL Misc]을(를) 추가합니다.

1. [!UICONTROL Title field]에서 **Marketo RTP**&#x200B;을 입력하고 **[!UICONTROL Finish]**&#x200B;을 클릭합니다.

1. 변경 내용을 저장합니다.

   >[!NOTE]
   >
   >아직 새 컨테이너를 게시할 필요가 없습니다.

1. 프로필이 저장되면 Tealium iQ 콘솔의 오른쪽 상단에 있는 이름/이메일 주소를 클릭합니다.

1. [!UICONTROL Admin] 메뉴에서 **[!UICONTROL Manage Templates]** 아래의 [!UICONTROL Account Admin]을(를) 클릭합니다.

1. 드롭다운 목록에서 **[!UICONTROL Tealium Custom Container]: Marketo RTP**&#x200B;을 선택하여 태그 템플릿을 엽니다.

1. RTP 계정에 로그인합니다.

1. [!UICONTROL Account Settings]&#x200B;(으)로 이동합니다.

   >[!NOTE]
   >
   >지원에서 이미 JavaScript 태그를 받은 경우 11단계를 계속 진행합니다.

1. 도메인에서 관련 도메인을 찾아 **[!UICONTROL Generate Tag]**&#x200B;을(를) 클릭합니다.

1. RTP JavaScript 태그를 복사하여 Tealium 프로필 템플릿의 [!UICONTROL Start Tag Library Code]과(와) [!UICONTROL End Tag Library Code] 사이에 붙여 넣습니다.

   >[!NOTE]
   >
   >**중요 단계**
   >
   >이 파일에 배치한 코드에서 `<!-- RTP tag -->` 및 `<!-- End of RTP tag -->` 태그를 제거합니다.
   >
   >이 파일에 배치한 코드에서 `<script type='text/javascript'>` 및 `</script>` 태그를 제거하십시오.

1. **[!UICONTROL Save Profile Template]**&#x200B;을(를) 클릭하고 새 프로필을 게시합니다.
