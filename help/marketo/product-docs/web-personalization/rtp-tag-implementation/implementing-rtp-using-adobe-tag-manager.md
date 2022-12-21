---
unique-page-id: 4720218
description: Adobe Tag Manager을 사용하여 RTP 구현 - Marketo 문서 - 제품 설명서
title: Adobe Tag Manager을 사용하여 RTP 구현
exl-id: 5a938d02-6b09-45d5-94b0-dbb50b5d62b6
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---

# Adobe Tag Manager을 사용하여 RTP 구현 {#implementing-rtp-using-adobe-tag-manager}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. RTP 계정에 로그인합니다.

1. 이동 **계정 설정**.

   a. 지원에서 이미 JavaScript 태그를 받은 경우 4단계로 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-4.png)

1. 도메인 아래에서 관련 도메인을 찾아 를 클릭합니다 **태그 생성**.

   ![](assets/image2014-11-30-15-3a20-3a17-4.png)

1. Dynamic Tag Manager 계정에 로그인합니다([https://dtm.adobe.com/sign_in](https://dtm.adobe.com/sign_in)).

1. 이동 **대시보드.** 관련 웹 속성을 클릭합니다.

   ![](assets/image2014-12-3-17-3a58-3a17.png)

1. 이동 **규칙**&#x200B;를 클릭합니다. **새 규칙 만들기**.

1. 다음을 입력합니다

   1. 이름: **Marketo RTP**
   1. 조건(축소) : 트리거 규칙: **페이지 상단**
   1. Javascript(축소): click **새 스크립트 추가**

   ![](assets/image2014-12-3-17-3a59-3a40.png)

1. 새 태그를 호출합니다. **Marketo RTP 태그**

1. RTP 태그에서 다음 코드를 제거합니다

   * `<script type='text/javascript'>`
   * `</script>`

1. RTP JavaScript 태그를 붙여넣습니다.

   ![](assets/image2014-12-3-18-3a3-3a45.png)

   >[!CAUTION]
   >
   >모든 태그를 제거하고 스크립트 자체만 남겨둡니다(아니요) `<script type='text/javascript'>` , `</script>` )

1. 클릭 **코드 저장** 스크립트 편집기 및 **규칙 저장** 규칙 편집기에서 을 참조하십시오.

1. 규칙 패널에서 Marketo RTP 페이지 로드 규칙 및 **작업** 드롭다운 선택 **규칙 활성화**.

   ![](assets/image2014-12-3-18-3a4-3a14.png)

1. **확인** 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시됩니다.

   웹 사이트의 페이지를 마우스 오른쪽 단추로 클릭하여 이 작업을 수행할 수 있습니다. 이동 **Inspect 요소**&#x200B;를 클릭하고 **네트워크**, 검색: **RTP**.
