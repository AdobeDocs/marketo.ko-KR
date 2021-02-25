---
unique-page-id: 9437340
description: Tealium 태그 관리자를 사용하여 RTP 구현 - Marketing Docs - 제품 설명서
title: Tealium 태그 관리자를 사용하여 RTP 구현
translation-type: tm+mt
source-git-commit: fbaf57ec4f3532c2d71acf23171d60873b1c997c
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---


# Tealium 태그 관리자를 사용하여 RTP 구현 {#implementing-rtp-using-tealium-tag-manager}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. Teum 태그 관리자 계정에 로그인합니다.

1. 태그 탭으로 이동하여 태그 마켓플레이스의 기타 탭 아래에 있는 Telium 사용자 지정 컨테이너 태그를 추가합니다.

1. 제목 필드에 **Marketing RTP**&#x200B;를 입력하고 **완료**&#x200B;를 클릭합니다.

1. 변경 내용을 저장합니다.

   >[!NOTE]
   >
   >아직 새 컨테이너를 게시할 필요가 없습니다.

1. 프로필을 저장한 후 Telium iQ 콘솔의 오른쪽 상단에 있는 이름/이메일 주소를 클릭합니다.

1. 관리 메뉴에서 계정 관리자 아래에 있는 **템플릿 관리**&#x200B;를 클릭합니다.

1. **교육 사용자 지정 컨테이너 선택:Marketing To RTP** 드롭다운 목록에서 태그 템플릿을 엽니다.

1. RTP 계정에 로그인합니다.

1. 계정 설정으로 이동합니다.

   >[!NOTE]
   >
   >지원에서 이미 JavaScript 태그를 수신한 경우 11단계로 진행합니다.

1. 도메인에서 관련 도메인을 찾아 **태그 생성**&#x200B;을 클릭합니다.

1. RTP JavaScript 태그를 복사하여 Teum 프로필 템플릿의 태그 라이브러리 코드 시작 및 태그 라이브러리 코드 끝 사이에 붙여넣습니다.

   >[!NOTE]
   >
   >**중요 단계**
   >
   >이 파일에 배치하는 코드에서 `<!-- RTP tag -->` 및 `<!-- End of RTP tag -->` 태그를 제거합니다.
   >
   >이 파일에 배치하는 코드에서 `<script type='text/javascript'>` 및 `</script>` 태그를 제거합니다.

1. **프로필 템플릿 저장을** 클릭하고 새 프로필을 게시합니다.
