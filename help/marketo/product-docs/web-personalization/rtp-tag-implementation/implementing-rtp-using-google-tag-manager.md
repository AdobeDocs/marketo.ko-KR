---
unique-page-id: 4720145
description: Google Tag Manager를 사용하여 RTP 구현 - Marketo 문서 - 제품 설명서
title: Google Tag Manager를 사용하여 RTP 구현
exl-id: f7f06779-8abe-4c8c-9197-9d0c6bcfed49
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '156'
ht-degree: 0%

---

# Google Tag Manager를 사용하여 RTP 구현 {#implementing-rtp-using-google-tag-manager}

RTP 태그를 구현하려면 아래의 설치 지침을 따르십시오.

1. Google Tag Manager 계정에 로그인합니다.

1. 새 태그 추가 > 태그 구성 > 사용자 지정 HTML 태그&#x200B;**.**&#x200B;0&rbrace;RTP **로 호출합니다.**

1. RTP 계정에 로그인합니다&#x200B;**&#x200B;**

1. **계정 설정**(으)로 이동합니다.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 6단계로 이동합니다.

   ![](assets/image2014-11-30-15-3a19-3a21.png)

1. 도메인에서 관련 도메인을 찾아 **태그 생성**&#x200B;을 클릭합니다.

   ![](assets/image2014-11-30-15-3a20-3a17.png)

1. RTP JavaScript 태그를 복사하여 새로 만든 **사용자 지정 HTML 태그**&#x200B;에 붙여넣습니다(1단계).

1. **+태그를 실행할 규칙 추가**&#x200B;를 클릭합니다. **모든 페이지**&#x200B;를 선택하십시오.

1. **저장** 및 [새 버전을 게시](https://support.google.com/tagmanager/answer/2699097?hl=en)합니다.

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 확인합니다.

   a. 웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. **Inspect 요소**(으)로 이동하여 태그를 찾으려면 **RTP**&#x200B;을 검색하십시오.
