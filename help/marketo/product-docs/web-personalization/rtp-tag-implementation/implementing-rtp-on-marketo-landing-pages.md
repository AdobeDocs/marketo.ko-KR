---
unique-page-id: 4720151
description: Marketo 랜딩 페이지에서 RTP 구현 - Marketo 문서 - 제품 설명서
title: Marketo 랜딩 페이지에서 RTP 구현
exl-id: fd19c3ad-d3f6-44a3-9f7a-d518e2d3f02a
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 0%

---

# Marketo 랜딩 페이지에서 RTP 구현 {#implementing-rtp-on-marketo-landing-pages}

RTP 태그를 구현하려면 아래 설치 지침을 따르십시오.

1. 로 이동 **디자인 스튜디오.** 편집할 항목을 엽니다. 선택 **템플릿 작업**, 선택 **초안 편집**.

   ![](assets/image2015-4-26-18-3a27-3a4.png)

1. 에서 템플릿 변경 **HTML 소스** 탭.

   ![](assets/image2015-4-26-18-3a28-3a17.png)

1. RTP 계정에서 **계정 설정**.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 5단계로 진행합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-2.png)

1. 도메인 아래에서 관련 도메인을 찾아 **태그 생성**.

   ![](assets/image2015-4-26-18-3a27-3a35.png)

   ![](assets/image2014-11-30-15-3a20-3a17-2.png)

1. RTP JavaScript 태그를 복사하여 사이에 있는 모든 랜딩 페이지 템플릿에 붙여넣습니다. **`<head> </head>`** 태그 사이에 코드를 삽입하지 마십시오.

1. 클릭 **저장** 및 **닫기** 창문이요

1. 뒤로 이동 **Design Studio**&#x200B;에서 랜딩 페이지 승인 **템플릿 작업**, 클릭 **승인**.

   ![](assets/image2015-4-26-18-3a28-3a30.png)

1. 마지막으로, 다음을 수행해야 합니다. **재승인** 템플릿 변경 내용을 적용하기 위해 해당 템플릿을 사용하는 모든 랜딩 페이지 기본 랜딩 페이지 섹션에서 한 번에 모두 다시 승인할 수 있습니다.

   ![](assets/image2015-4-26-18-3a28-3a49.png)

1. 랜딩 페이지 및 하위 도메인을 포함한 모든 페이지에 표시되는지 확인합니다.

   웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. 다음으로 이동 **페이지 소스 보기** 검색 대상 **RTP** 태그를 찾습니다.
