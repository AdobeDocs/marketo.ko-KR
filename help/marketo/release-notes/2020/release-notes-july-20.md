---
unique-page-id: 45416698
description: 릴리스 노트 -20년 7월 - Marketing To Docs - 제품 설명서
title: 릴리스 노트 - 2007년 7월
translation-type: tm+mt
source-git-commit: 313266a67243f0c70c25010cb4825efb7f3db0ab
workflow-type: tm+mt
source-wordcount: '658'
ht-degree: 0%

---


# 릴리스 노트:1920년 7월 {#release-notes-july}

2007년 7월 릴리스에는 다음 기능이 포함됩니다. 기능 가용성을 확인하려면 Marketing Edition을 확인하십시오.

>[!NOTE]
>
>**가용성**
>
>현재 패키지에 따라, 별( ![(star)](assets/star-yellow.svg))가 있는 항목은 값 추가 기능을 구입해야 할 수 있습니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

***분기별 릴리스*** 다음 기능은 2020년  **7월 31일에 릴리스됩니다**.

## 관리 {#administration}

* ** [&quot;사용됨&quot; 필드 관리에서 내보내기](https://docs.marketo.com/x/hAK1Ag)**:관리자는 이제 선택한 필드에 대한 모든 &quot;사용 방법&quot; 자산 링크를 CSV 파일로 내보낼 수 있습니다. 이 개선 사항은 관리자와 관리자가 아닌 사용자 모두 사용하지 않는 필드를 정리하는 데 도움이 될 수 있습니다. 또한 이제 새 브라우저 탭 또는 창에서 자산을 열 수 있습니다.

**계정 기반 마케팅 ![(스타)](assets/star-yellow.svg)

**

* **계정 프로파일링을 위해 업데이트된 UI:**단일 화면에서 간소화된 단계를 통해 계정 프로파일링에서 타겟 계정 목록 생성을 간소화할 수 있습니다.

<br> 

**

***분기 전체 릴리즈***

다음 기능은 분기별로 판매되지 않는 주기에 있으며 향후 몇 개월 동안 출시될 예정입니다.

* **Forms 서비스:**새로운 랜딩 페이지용 보안 도메인 기능을 사용하여 더욱 강력한 양식 필드 구문 유효성 검사와 일반적인 보트 패턴을 차단하는 기능을 소개합니다. 보트 패턴을 차단하면 스팸 양식 제출이 줄어들고 데이터베이스 품질이 향상될 수 있습니다.
* **향상된 자산 API URI 크기 제한**:&quot;_method&quot; 매개 변수를 제거하기 전에 동일한 리소스 ID(URI) 크기 제한이 8KB에서 65KB로 증가됩니다. 긴 쿼리 문자열을 수행할 때 이 크기 제한을 늘리면 데이터가 보다 쉽게 전달될 수 있습니다. &quot;_method&quot; 매개 변수의 제거는 예정된 보안 업그레이드의 일부입니다.

**Sales Insight ![(star)](assets/star-yellow.svg)

**

* ** [기본 Salesforce CRM 통합이 없는 고객을 위한 Sales Insight 사용](https://docs.marketo.com/x/pQK1Ag)(베타)**:네이티브 Salesforce CRM 통합을 사용하는 Marketo Engage 고객은 이제 Sales Insight를 사용하여 세일즈 팀이 가장 참여도가 높은 리드 및 기회를 파악, 우선 순위 지정 및 상호 작용하여 보다 신속하게 세일즈 및 거래를 할 수 있습니다.

**Sales Connect ![(star)](assets/star-yellow.svg)

**

* ** [영업 호출에 대한 개선된 2자 동의:](https://docs.marketo.com/x/dgC1Ag)** 관리자가 이제 콜 기록 구성을 보다 완벽하게 제어할 수 있습니다. [양당 ](https://docs.marketo.com/x/dAC1Ag) 동의 법을 준수한다는 확신을 갖고 전화 기록을 활성화합니다. 녹음되는 호출에 대한 알림을 자동화하고 호출 전에 재생되는 오디오 클립을 활성화합니다.

<br> 

## 공지 및 사용 중단 {#announcements-deprecations}

* **자산 API &quot;_method&quot; 매개 변수 제거**:2020년 9월 이후 자산 API 끝점은 더 이상 &quot;_method&quot;를 통해 POST 본문에 쿼리 매개 변수를 전달하여 URI 길이 제한을 우회하지 않습니다. 이 매개 변수가 필요한 요청을 수용하기 위해 자산 API에 대한 URI 제한이 8KB에서 65KB로 증가합니다.
* ** [Munchkin 연관 리드](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/)**:Munchkin JavaScript Client 버전 159의 이번 릴리스부터 Munchkin Associate Lead 메서드의 사용 중단을 시작할 것입니다. 호출되면 향후 릴리스에서 메서드가 제거된다는 경고가 표시됩니다. 제거되면 해당 메서드가 더 이상 작동하지 않으며 해당 메서드를 사용하려고 시도해도 실패합니다. 최근 이 방법을 사용한 Marketo Engage 고객은 개별적으로 사용 사실을 통보받게 됩니다.
* **Internet Explorer** 지원:이전에 발표했듯이 Internet Explorer 11에 대한 Marketo Engage 지원은 2020년 **7월 31일에 종료됩니다**. Google Chrome, Mozilla Firefox, Apple Safari 및 Microsoft Edge를 계속 지원할 예정입니다.

* **하늘 기본 경험**:관리자 또는 사용자가 Marketo Sky을 기본 경험으로 설정할 수 있는 옵션은 기본 사용자 환경에 대한 업데이트를 준비할 때 이 릴리스에서 제거됩니다. 올해 말로 예정되어 있는 기본 경험에 대한 업데이트에 대한 더 자세한 내용은 7월에 제공될 예정입니다. Marketo Sky을 기본 경험으로 설정했거나 Marketo Sky에 대한 액세스 권한을 받은 사용자는 내 마케팅 홈 페이지의 타일에서 Marketo Sky에 계속 액세스할 수 있습니다.
* **EdgeHTML(Chromium 아님) Microsoft Edge 지원**:Marketo Engage은 2020년 말 Microsoft Edge의 EdgeHTML 버전을 더 이상 지원하지 않습니다. 2021년 1월 1일부터 최신 Chromium 버전의 Microsoft Edge만 지원할 예정입니다.

