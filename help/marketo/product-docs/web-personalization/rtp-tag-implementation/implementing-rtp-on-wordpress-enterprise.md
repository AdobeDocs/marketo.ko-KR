---
unique-page-id: 4720215
description: Wordpress Enterprise에서 RTP 구현 - Marketing Docs - 제품 설명서
title: Wordpress Enterprise에서 RTP 구현
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 0%

---


# Wordpress Enterprise에서 RTP 구현 {#implementing-rtp-on-wordpress-enterprise}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. ** 계정 설정으로 이동합니다.**

   1. 지원으로부터 JavaScript 태그를 이미 받은 경우 3단계로 이동합니다.\
      ![](assets/image2014-11-30-15-3a19-3a21-3.png)

1. 도메인에서 관련 도메인을 찾아 태그 **생성을 클릭합니다**.

   ![](assets/image2014-11-30-15-3a20-3a17-3.png)

1. RTP JavaScript 태그를 복사합니다.
1. WordPress 계정에 관리자 사용자로 로그인

   1. 모양 **아래에서****사용자 지정 JavaScript로**&#x200B;이동합니다.
   1. 기존 코드 바로 뒤에 RTP Javascript 태그를 붙여넣습니다.

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
   >스크립트 자체만 삽입

1. 업데이트를 **클릭합니다**.
