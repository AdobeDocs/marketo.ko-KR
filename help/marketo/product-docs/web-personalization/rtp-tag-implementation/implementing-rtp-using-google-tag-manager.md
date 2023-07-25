---
unique-page-id: 4720145
description: Google Tag Manager를 사용하여 RTP 구현 - Marketo 문서 - 제품 설명서
title: Google Tag Manager를 사용하여 RTP 구현
exl-id: f7f06779-8abe-4c8c-9197-9d0c6bcfed49
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# Google Tag Manager를 사용하여 RTP 구현 {#implementing-rtp-using-google-tag-manager}

RTP 태그를 구현하려면 아래의 설치 지침을 따르십시오.

1. Google Tag Manager 계정에 로그인합니다.

1. 새 태그 추가 > 태그 구성 > 사용자 지정 HTML 태그**.** 호출 **RTP**.

1. RTP 계정에 로그인합니다****

1. 다음으로 이동 **계정 설정**.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 6단계로 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21.png)

1. 도메인 아래에서 관련 도메인을 찾아 **태그 생성**.

   ![](assets/image2014-11-30-15-3a20-3a17.png)

1. RTP JavaScript 태그를 복사하여 새 태그에 붙여넣습니다 **사용자 지정 HTML 태그** 을(를) 만들었습니다(1단계).

1. 클릭 **+태그를 실행하는 규칙 추가**. 선택 **모든 페이지**.

1. 클릭 **저장** 및 [새 버전 게시](https://support.google.com/tagmanager/answer/2699097?hl=en).

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 확인합니다.

   a. 웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. 다음으로 이동 **Inspect 요소**, 검색 **RTP** 태그를 찾습니다.
