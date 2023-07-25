---
unique-page-id: 9437340
description: Tealium Tag Manager를 사용하여 RTP 구현 - Marketo 문서 - 제품 설명서
title: Tealium Tag Manager를 사용하여 RTP 구현
exl-id: 7a099184-625c-46b2-a741-3bcdad0a238e
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---

# Tealium Tag Manager를 사용하여 RTP 구현 {#implementing-rtp-using-tealium-tag-manager}

RTP 태그를 구현하려면 아래의 설치 지침을 따르십시오.

1. Tealium Tag Manager 계정에 로그인합니다.

1. 태그 탭으로 이동하여 태그 마켓플레이스의 기타 탭에 있는 Tealium 사용자 지정 컨테이너 태그를 추가합니다.

1. 제목 필드에 을 입력합니다. **Marketo** 및 클릭 **완료**.

1. 변경 사항을 저장합니다.

   >[!NOTE]
   >
   >아직 새 컨테이너를 게시할 필요가 없습니다.

1. 프로필이 저장되면 Tealium iQ 콘솔의 오른쪽 상단에 있는 이름/이메일 주소를 클릭합니다.

1. 관리자 메뉴에서 **템플릿 관리** 계정 관리자 아래에 있습니다.

1. 선택 **Tealium 사용자 지정 컨테이너: Marketo RTP** 을 클릭하여 태그 템플릿을 엽니다.

1. RTP 계정에 로그인합니다.

1. 계정 설정으로 이동합니다.

   >[!NOTE]
   >
   >지원에서 이미 JavaScript 태그를 받은 경우 11단계로 진행합니다.

1. 도메인 아래에서 관련 도메인을 찾아 **태그 생성**.

1. RTP JavaScript 태그를 복사하여 Tealium 프로필 템플릿의 시작 태그 라이브러리 코드와 끝 태그 라이브러리 코드 사이에 붙여넣습니다.

   >[!NOTE]
   >
   >**중요한 단계**
   >
   >제거 `<!-- RTP tag -->` 및 `<!-- End of RTP tag -->` 이 파일에 배치한 코드의 태그
   >
   >모두 제거 `<script type='text/javascript'>` 및 `</script>` 이 파일에 배치한 코드의 태그

1. **프로필 템플릿 저장 을 클릭합니다** 새 프로필을 게시합니다.
