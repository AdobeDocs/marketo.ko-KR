---
unique-page-id: 4720151
description: Marketo 랜딩 페이지에서 RTP 구현 - Marketo 문서 - 제품 설명서
title: Marketo 랜딩 페이지에서 RTP 구현
exl-id: fd19c3ad-d3f6-44a3-9f7a-d518e2d3f02a
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 0%

---

# Marketo 랜딩 페이지에서 RTP 구현 {#implementing-rtp-on-marketo-landing-pages}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. 로 이동합니다. **디자인 스튜디오.** 편집할 항목을 엽니다. 선택 **템플릿 작업**, 선택 **초안 편집**.

   ![](assets/image2015-4-26-18-3a27-3a4.png)

1. 에서 템플릿을 변경합니다. **HTML 소스** 탭.

   ![](assets/image2015-4-26-18-3a28-3a17.png)

1. RTP 계정에서 다음 위치로 이동합니다. **계정 설정**.

   a. 지원에서 이미 JavaScript 태그를 받은 경우 5단계로 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-2.png)

1. 도메인 아래에서 관련 도메인을 찾아 를 클릭합니다 **태그 생성**.

   ![](assets/image2015-4-26-18-3a27-3a35.png)

   ![](assets/image2014-11-30-15-3a20-3a17-2.png)

1. RTP JavaScript 태그를 복사하여 다음 사이에 있는 모든 랜딩 페이지 템플릿에 붙여넣습니다 **`<head> </head>`** 태그 사이에 Analytics JavaScript 코드를 배치했습니다.

1. 클릭 **저장** 및 **닫기** 창

1. 다시 **Design Studio**&#x200B;에서 랜딩 페이지를 승인합니다. **템플릿 작업**&#x200B;를 클릭합니다. **승인**.

   ![](assets/image2015-4-26-18-3a28-3a30.png)

1. 마지막으로, **재승인** 템플릿 변경 사항을 적용하려면 해당 템플릿을 사용하는 모든 랜딩 페이지를 변경해야 합니다. 기본 랜딩 페이지 섹션에서 모두 한 번에 다시 승인할 수 있습니다.

   ![](assets/image2015-4-26-18-3a28-3a49.png)

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 확인합니다.

   웹 사이트의 페이지를 마우스 오른쪽 단추로 클릭하여 이 작업을 수행할 수 있습니다. 이동 **페이지 소스 보기.** 검색 대상 **RTP** 를 눌러 태그를 찾습니다.
