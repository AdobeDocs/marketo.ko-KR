---
unique-page-id: 4720218
description: Adobe Tag Manager을 사용하여 RTP 구현 - Marketing To Docs - 제품 설명서
title: Adobe Tag Manager을 사용하여 RTP 구현
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 0%

---


# Adobe Tag Manager {#implementing-rtp-using-adobe-tag-manager}을(를) 사용하여 RTP 구현

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. RTP 계정에 로그인합니다.
1. **계정 설정으로 이동합니다.**

   지원에서 이미 JavaScript 태그를 수신한 경우 4단계로 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-4.png)

1. 도메인에서 관련 도메인을 찾아 **태그 생성**&#x200B;을 클릭합니다.

   ![](assets/image2014-11-30-15-3a20-3a17-4.png)

1. 다이내믹 태그 관리자 계정에 로그인합니다([https://dtm.adobe.com/sign_in](https://dtm.adobe.com/sign_in)).
1. **대시보드로 이동합니다.** 관련 웹 속성을 클릭합니다.

   ![](assets/image2014-12-3-17-3a58-3a17.png)

1. **규칙,**&#x200B;새 규칙 만들기&#x200B;**를 클릭합니다.**

1. 다음을 입력합니다.

   1. 이름:**Marketing RTP**
   1. 조건(축소):트리거 규칙 위치 - **페이지 위쪽**
   1. Javascript(축소):**새 스크립트 추가** 클릭

   ![](assets/image2014-12-3-17-3a59-3a40.png)

1. 새 태그를 호출합니다.**Marketing RTP 태그**
1. RTP 태그에서 다음 코드 제거

   * `<script type='text/javascript'>`
   * `</script>`

1. RTP JavaScript 태그를 붙여 넣습니다.

   ![](assets/image2014-12-3-18-3a3-3a45.png)

   >[!CAUTION]
   >
   >모든 태그를 제거하고 스크립트 자체만 남겨 두십시오( `<script type='text/javascript'>` , `</script>` ).

1. 스크립트 편집기에서 **코드 저장**&#x200B;을 클릭하고 규칙 편집기에서 **규칙 저장**&#x200B;을 클릭합니다.

1. 규칙 패널에서 Marketing to RTP 페이지 로드 규칙을 찾고 **작업** 드롭다운에서 **규칙 활성화**&#x200B;를 선택합니다.

   ![](assets/image2014-12-3-18-3a4-3a14.png)

1. **랜딩** 페이지 및 하위 도메인을 포함한 모든 페이지에 표시되는지 확인합니다.

   웹 사이트의 페이지를 마우스 오른쪽 단추로 클릭하면 됩니다. **Inspect 요소**&#x200B;로 이동하고 **네트워크, **검색:**RTP**.
