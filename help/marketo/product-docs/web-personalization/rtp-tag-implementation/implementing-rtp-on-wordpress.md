---
unique-page-id: 4720149
description: Wordpress에서 RTP 구현 - Marketo 설명서 - 제품 설명서
title: Wordpress에서 RTP 구현
exl-id: f010942b-02bb-447b-a272-c4237782b2d7
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 0%

---

# Wordpress에서 RTP 구현 {#implementing-rtp-on-wordpress}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. **WordPress 테마**&#x200B;의 **header.php** 파일을 엽니다.

   FTP 클라이언트를 사용하여 서버에 액세스하거나 WordPress 대시보드에서 직접 테마 파일을 편집할 수 있습니다. 파일 편집기는 사이드바 메뉴의 **모양** 탭에 있습니다.

   ![](assets/image2014-11-30-15-3a35-3a30.png)

1. 텍스트 편집기 오른쪽의 템플릿 파일 목록에서 **header.php**&#x200B;을(를) 찾아 엽니다.

1. **계정 설정**(으)로 이동합니다.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 5단계로 이동합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-1.png)

1. 도메인에서 관련 도메인을 찾아 **태그 생성**&#x200B;을 클릭합니다.

   ![](assets/image2014-11-30-15-3a20-3a17-1.png)

1. RTP JavaScript 태그를 복사하여 웹 사이트 템플릿에 붙여넣습니다.

   a. 페이지 헤더(**`<head> </head>`** 태그 사이)의 첫 번째 스크립트인지 확인합니다.

   ![](assets/image2014-11-30-15-3a36-3a31.png)

1. header.php 파일의 **파일 업데이트**&#x200B;를 클릭합니다.

1. 랜딩 페이지 및 하위 도메인을 포함한 모든 페이지에 표시되는지 확인합니다.

   a. 웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. **페이지 보기 Source으로 이동합니다.** 태그를 찾으려면 **RTP**&#x200B;을 검색합니다.
