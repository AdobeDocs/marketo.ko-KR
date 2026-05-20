---
unique-page-id: 9437340
description: dnl을 사용한 rtp 구현 등 Marketo Engage에서 tealium tag manager를 사용하여 rtp에 대해 알아봅니다. 이 안내서를 사용하여 다음 단계를 완료하십시오.
title: Tealium Tag Manager를 사용하여 RTP 구현
exl-id: 7a099184-625c-46b2-a741-3bcdad0a238e
feature: Web Personalization
TQID: https://experienceleague.adobe.com/zMs2Dii5RERdH8tKb86a6EhxXUx2IpbZkDOCklUvvY4
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: e2290edd-b061-4880-9d79-dee306cf5aa9id: ea90ebee-5c84-42d9-8b21-006bdabc95a3id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bccid: f82558ea-6af5-44eb-a424-5b3389abb0a3
topic_v2: id: aa2f3246-cb95-4b30-8899-fdf7d73550ccid: b5ce8718-c3af-4fdb-a1a9-fca32f83a87cid: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 201
ht-degree: 5%

---

# [!DNL Tealium] 태그 관리자를 사용하여 RTP 구현 {#implementing-rtp-using-tealium-tag-manager}

RTP 태그를 구현하려면 아래의 설치 지침을 따르십시오.

1. [!DNL Tealium] 태그 관리자 계정에 로그인합니다.

1. [!UICONTROL Tags] 탭으로 이동하여 태그 마켓플레이스의 [!UICONTROL Misc] 탭에 있는 [!UICONTROL Tealium Custom Container Tag]을(를) 추가합니다.

1. [!UICONTROL Title field]에서 **Marketo RTP**&#x200B;을 입력하고 **[!UICONTROL Finish]**&#x200B;을 클릭합니다.

1. 변경 내용을 저장합니다.

   >[!NOTE]
   >
   >아직 새 컨테이너를 게시할 필요가 없습니다.

1. 프로필이 저장되면 Tealium iQ 콘솔의 오른쪽 상단에 있는 이름/이메일 주소를 클릭합니다.

1. [!UICONTROL Admin] 메뉴에서 [!UICONTROL Account Admin] 아래의 **[!UICONTROL Manage Templates]**&#x200B;을(를) 클릭합니다.

1. 드롭다운 목록에서 **[!UICONTROL Tealium Custom Container]: Marketo RTP**&#x200B;을 선택하여 태그 템플릿을 엽니다.

1. RTP 계정에 로그인합니다.

1. [!UICONTROL Account Settings] 으로 이동합니다.

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
