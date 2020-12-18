---
unique-page-id: 4720151
description: 마케팅 랜딩 페이지에서 RTP 구현 - 마케팅 문서 - 제품 설명서
title: 마케팅 랜딩 페이지에서 RTP 구현
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
workflow-type: tm+mt
source-wordcount: '190'
ht-degree: 0%

---


# 마케팅 랜딩 페이지에서 RTP 구현 {#implementing-rtp-on-marketo-landing-pages}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. **디자인 스튜디오로 이동합니다.** 편집할 항목을 엽니다. **템플릿 작업**&#x200B;을 선택하고 **초안 편집**&#x200B;을 선택합니다.

   ![](assets/image2015-4-26-18-3a27-3a4.png)

1. **HTML 소스** 탭에서 템플릿을 변경합니다.

   ![](assets/image2015-4-26-18-3a28-3a17.png)

1. RTP 계정에서 계정 설정으로 이동합니다**.**

1. 지원에서 이미 JavaScript 태그를 수신한 경우 5단계를 계속 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-2.png)

1. 도메인에서 관련 도메인을 찾아 **태그 생성**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-26-18-3a27-3a35.png)

   ![](assets/image2014-11-30-15-3a20-3a17-2.png)

1. RTP JavaScript 태그를 복사하여 **`<head> </head>`** 태그 사이에 있는 모든 랜딩 페이지 템플릿에 붙여넣습니다.
1. **저장** 및 **닫기**&#x200B;를 클릭합니다.
1. **Design Studio**&#x200B;에서 **템플릿 작업**&#x200B;에서 랜딩 페이지를 승인하고 **승인**&#x200B;을 클릭합니다.\
   ![](assets/image2015-4-26-18-3a28-3a30.png)

1. 마지막으로 템플릿 변경 사항을 적용하려면 해당 템플릿을 사용하는 랜딩 페이지를 **다시 승인**&#x200B;해야 합니다. 기본 랜딩 페이지 섹션에서 모두 한 번에 재승인할 수 있습니다.

   ![](assets/image2015-4-26-18-3a28-3a49.png)

1. 모든 `pages including` 랜딩 페이지와 하위 도메인에 표시되는지 확인합니다.

   이 작업은 `website’s` 페이지를 마우스 오른쪽 단추로 클릭하여 수행할 수 있습니다. **페이지 소스 보기로 이동합니다.** RTP를  **** 검색하여 태그를 찾습니다.
