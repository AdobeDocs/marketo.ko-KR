---
unique-page-id: 4720145
description: Google Tag Manager를 사용하여 RTP 구현 - Marketo 문서 - 제품 설명서
title: Google 태그 관리자를 사용하여 RTP 구현
exl-id: f7f06779-8abe-4c8c-9197-9d0c6bcfed49
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# Google 태그 관리자를 사용하여 RTP 구현 {#implementing-rtp-using-google-tag-manager}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. Google Tag Manager 계정에 로그인합니다.

1. 새 태그 > 태그 구성 > 사용자 지정 HTML 태그를 추가합니다**.** **RTP**.

1. RTP 계정에 **.**

1. 이동 **계정 설정**.

   a. 지원에서 이미 JavaScript 태그를 받은 경우 6단계로 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21.png)

1. 도메인 아래에서 관련 도메인을 찾아 를 클릭합니다 **태그 생성**.

   ![](assets/image2014-11-30-15-3a20-3a17.png)

1. RTP JavaScript 태그를 복사하여 새 태그에 붙여넣습니다 **사용자 지정 HTML 태그** 생성됨(1단계).

1. 클릭 **+Fire 태그에 규칙 추가**. 선택 **모든 페이지**.

1. 클릭 **저장** 및 [새 버전 게시](https://support.google.com/tagmanager/answer/2699097?hl=en).

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 확인합니다.

   a. 웹 사이트의 페이지를 마우스 오른쪽 단추로 클릭하여 이 작업을 수행할 수 있습니다. 이동 **Inspect 요소**, 을 검색합니다. **RTP** 를 눌러 태그를 찾습니다.
