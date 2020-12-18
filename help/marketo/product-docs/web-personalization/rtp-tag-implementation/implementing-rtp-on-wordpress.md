---
unique-page-id: 4720149
description: Wordpress에서 RTP 구현 - Marketing To Docs - 제품 설명서
title: Wordpress에서 RTP 구현
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---


# Word에서 RTP 구현 {#implementing-rtp-on-wordpress}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. **WordPress 테마**&#x200B;의 **header.php** 파일을 엽니다.

   FTP 클라이언트를 사용하여 서버에 액세스하거나 WordPress 대시보드에서 바로 테마 파일을 편집할 수 있습니다. 파일 편집기는 세로 막대 메뉴의 **모양** 탭 아래에 있습니다.

   ![](assets/image2014-11-30-15-3a35-3a30.png)

1. 텍스트 편집기 오른쪽의 템플릿 파일 목록에서 **header.php**&#x200B;을 찾아 엽니다.
1. **계정 설정으로 이동합니다.**

   지원에서 이미 JavaScript 태그를 수신한 경우 5단계를 계속 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-1.png)

1. 도메인에서 관련 도메인을 찾아 **태그 생성**&#x200B;을 클릭합니다.

   ![](assets/image2014-11-30-15-3a20-3a17-1.png)

1. RTP JavaScript 태그를 복사하고 웹 사이트 템플릿에 붙여 넣습니다.

   **`<head> </head>`** 태그 사이의 페이지 헤더에 있는 첫 번째 스크립트인지 확인합니다.

   ![](assets/image2014-11-30-15-3a36-3a31.png)

1. header.php 파일의 **파일 업데이트**&#x200B;를 클릭합니다.
1. 모든 `pages including` 랜딩 페이지와 하위 도메인에 표시되는지 확인합니다.

   이 작업은 `website’s` 페이지를 마우스 오른쪽 단추로 클릭하여 수행할 수 있습니다. **페이지 소스 보기로 이동합니다.** RTP를  **** 검색하여 태그를 찾습니다.
