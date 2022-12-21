---
unique-page-id: 4720149
description: Wordpress에서 RTP 구현 - Marketo 문서 - 제품 설명서
title: Wordpress에서 RTP 구현
exl-id: f010942b-02bb-447b-a272-c4237782b2d7
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '187'
ht-degree: 0%

---

# Wordpress에서 RTP 구현 {#implementing-rtp-on-wordpress}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. 를 엽니다. **header.php** 파일 **WordPress 테마**.

   FTP 클라이언트를 사용하여 서버에 액세스하거나 WordPress 대시보드에서 직접 테마 파일을 편집할 수 있습니다. 파일 편집기는 **모양** 탭합니다.

   ![](assets/image2014-11-30-15-3a35-3a30.png)

1. 텍스트 편집기 오른쪽의 템플릿 파일 목록에서 **header.php** 열어요

1. 이동 **계정 설정**.

   a. 지원에서 이미 JavaScript 태그를 받은 경우 5단계로 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-1.png)

1. 도메인 아래에서 관련 도메인을 찾아 를 클릭합니다 **태그 생성**.

   ![](assets/image2014-11-30-15-3a20-3a17-1.png)

1. RTP JavaScript 태그를 복사하여 웹 사이트 템플릿에 붙여넣습니다.

   a. 페이지 헤더에 있는 첫 번째 스크립트인지( **`<head> </head>`** 태그 사이에 Analytics JavaScript 코드를 배치했습니다.

   ![](assets/image2014-11-30-15-3a36-3a31.png)

1. 클릭 **파일 업데이트** header.php 파일에 사용할 수 없습니다.

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 확인합니다.

   a. 웹 사이트의 페이지를 마우스 오른쪽 단추로 클릭하여 이 작업을 수행할 수 있습니다. 이동 **페이지 소스 보기.** 검색 대상 **RTP** 를 눌러 태그를 찾습니다.
