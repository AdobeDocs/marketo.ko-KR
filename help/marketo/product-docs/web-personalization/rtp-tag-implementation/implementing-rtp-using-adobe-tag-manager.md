---
unique-page-id: 4720218
description: Adobe Tag Manager을 사용하여 RTP 구현 - Marketo 문서 - 제품 설명서
title: Adobe Tag Manager을 사용하여 RTP 구현
exl-id: 5a938d02-6b09-45d5-94b0-dbb50b5d62b6
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '211'
ht-degree: 0%

---

# Adobe Tag Manager을 사용하여 RTP 구현 {#implementing-rtp-using-adobe-tag-manager}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. RTP 계정에 로그인합니다.

1. **계정 설정**(으)로 이동합니다.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 4단계를 계속 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-4.png)

1. 도메인에서 관련 도메인을 찾아 **태그 생성**&#x200B;을 클릭합니다.

   ![](assets/image2014-11-30-15-3a20-3a17-4.png)

1. Dynamic Tag Manager 계정([https://dtm.adobe.com/sign_in](https://dtm.adobe.com/sign_in))에 로그인합니다.

1. **대시보드로 이동합니다.** 관련 웹 속성을 클릭합니다.

   ![](assets/image2014-12-3-17-3a58-3a17.png)

1. **규칙**(으)로 이동하고 **새 규칙 만들기**&#x200B;를 클릭합니다.

1. 다음을 작성하십시오.

   1. 이름: **Marketo RTP**
   1. 조건(접기) : - **페이지 상단**&#x200B;에서 규칙 트리거
   1. Javascript(축소): **새 스크립트 추가**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-3-17-3a59-3a40.png)

1. 새 태그 호출: **Marketo RTP 태그**

1. RTP 태그에서 다음 코드를 제거합니다

   * `<script type='text/javascript'>`
   * `</script>`

1. RTP JavaScript 태그를 붙여 넣습니다.

   ![](assets/image2014-12-3-18-3a3-3a45.png)

   >[!CAUTION]
   >
   >모든 태그를 제거하고 스크립트 자체만 남겨둡니다(`<script type='text/javascript'>`, `</script>` 없음).

1. 스크립트 편집기에서 **코드 저장**&#x200B;을 클릭하고 규칙 편집기에서 **규칙 저장**&#x200B;을 클릭합니다.

1. 규칙 패널에서 Marketo RTP 페이지 로드 규칙을 찾고 **작업** 드롭다운 내에서 **규칙 활성화**&#x200B;를 선택합니다.

   ![](assets/image2014-12-3-18-3a4-3a14.png)

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 **확인**&#x200B;합니다.

   웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 수행할 수 있습니다. **Inspect 요소**(으)로 이동하고 **네트워크**, 검색: **RTP**&#x200B;을 클릭합니다.
