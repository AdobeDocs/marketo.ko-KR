---
unique-page-id: 9437340
description: Tealium Tag Manager를 사용하여 RTP 구현 - Marketing Docs - 제품 설명서
title: Teum Tag Manager를 사용하여 RTP 구현
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---


# Teum Tag Manager를 사용하여 RTP 구현 {#implementing-rtp-using-tealium-tag-manager}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. Teum Tag Manager 계정에 로그인합니다.
1. 태그 탭으로 이동하여 태그 마켓플레이스의 기타 탭 아래에 있는 Telium 사용자 지정 컨테이너 태그를 추가합니다.
1. 제목 필드에서 Marketing **RTP를 입력하고** 마침을 **클릭합니다**.
1. 변경 내용을 저장합니다.

   >[!NOTE]
   >
   >새 컨테이너를 아직 게시할 필요가 없습니다.

1. 프로필을 저장한 후 Tealium iQ 콘솔의 오른쪽 위 모서리에 있는 이름/이메일 주소를 클릭합니다.
1. 관리 메뉴에서 계정 관리자 **아래의 템플릿** 관리를 클릭합니다.
1. 교육 **사용자 지정 컨테이너 선택:Marketing** to RTP를 사용하여 태그 템플릿을 엽니다.
1. RTP 계정에 로그인합니다.
1. 계정 설정으로 이동합니다.

   >[!NOTE]
   >
   >지원에서 JavaScript 태그를 이미 받은 경우 11단계로 진행합니다.

1. 도메인에서 관련 도메인을 찾아 태그 **생성을 클릭합니다**.
1. RTP JavaScript 태그를 복사하고 Teum 프로필 템플릿의 태그 라이브러리 코드 시작과 끝 태그 라이브러리 코드 사이에 붙여 넣습니다.

   >[!NOTE]
   >
   >**중요 단계**
   >
   >이 파일에 `<!-- RTP tag -->` 저장한 코드에서 및 `<!-- End of RTP tag -->` 태그를 제거합니다.
   >
   >이 파일 `<script type='text/javascript'>` 에 저장한 코드에서 모든 및 `</script>` 태그를 제거합니다.

1. **프로필 템플릿 저장을** 클릭하고 새 프로필을 게시합니다.

