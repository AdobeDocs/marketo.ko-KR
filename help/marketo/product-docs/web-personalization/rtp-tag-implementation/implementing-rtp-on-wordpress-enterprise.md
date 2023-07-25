---
unique-page-id: 4720215
description: Wordpress Enterprise에서 RTP 구현 - Marketo 설명서 - 제품 설명서
title: Wordpress Enterprise에서 RTP 구현
exl-id: 61cfd3f8-0811-4352-9752-0081ce19257b
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '106'
ht-degree: 0%

---

# Wordpress Enterprise에서 RTP 구현 {#implementing-rtp-on-wordpress-enterprise}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. 다음으로 이동 **계정 설정**.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 3단계로 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-3.png)

1. 도메인 아래에서 관련 도메인을 찾아 **태그 생성**.

   ![](assets/image2014-11-30-15-3a20-3a17-3.png)

1. RTP JavaScript 태그를 복사합니다.

1. WordPress 계정에 관리자로 로그인

   a. 아래 **모양**&#x200B;로 이동합니다. **사용자 지정 JavaScript**.
b. 기존 코드 바로 뒤에 RTP Javascript 태그를 붙여 넣습니다.

   ![](assets/image2014-12-3-17-3a51-3a46.png)

   >[!CAUTION]
   >
   >코드를 붙여넣을 때 다음 태그를 제외합니다.
   >
   >* `<!-- RTP tag -->`
   >* `<script type='text/javascript'>`
   >* `</script>`
   >* `<!-- End of RTP tag -->`
   >
   >스크립트 자체만 삽입합니다.

1. 클릭 **업데이트**.
