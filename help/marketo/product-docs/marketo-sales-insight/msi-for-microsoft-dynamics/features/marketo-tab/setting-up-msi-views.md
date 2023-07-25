---
description: MSI 보기 설정 - Marketo 문서 - 제품 설명서
title: MSI 보기 설정
exl-id: 8a45c006-73d4-4af8-ad62-b084056d1f7d
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 0%

---

# MSI 보기 설정 {#setting-up-msi-views}

Dynamics에 Sales Insight 플러그인을 설치하면 사이트 맵에 최상의 선택 및 관련 대시보드가 자동으로 추가됩니다. 어떤 이유로든 대시보드가 추가되지 않는 경우, 대시보드를 수동으로 추가하는 방법은 다음과 같습니다.

1. Dynamics에서 톱니바퀴 아이콘을 클릭하고 **고급 설정** 드롭다운에서 을 클릭합니다.

1. 화면 왼쪽 상단에서 **설정**. 사용자 지정에서 **사용자 정의**.

1. 클릭 **시스템 사용자 정의**.

1. 왼쪽의 트리에서 를 클릭합니다. **클라이언트 확장** 및 두 번 클릭 **사이트 맵**.

1. 오른쪽 화살표를 클릭하여 다음 페이지로 이동합니다. Sales 아래에 Marketo이 표시됩니다. 그렇지 않으면 패키지를 제대로 가져왔는지 확인하십시오.

   >[!NOTE]
   >
   >Marketo에는 최상의 선택, 내 이메일, 웹 활동 및 익명 웹 활동이 있어야 합니다. 누락된 대시보드가 있는 경우 판매 위의 + 기호를 클릭하고 하위 영역으로 추가합니다.

1. 대시보드에서 을(를) 클릭하여 선택합니다. 오른쪽 열에 각 항목에 대한 정보를 아래에 입력합니다. 나열되지 않은 범주는 무시할 수 있습니다.

   **최상의 선택**</br>
URL: MainviewBestbets.html</br>
아이콘: /WebResources/mkt_/_MainView/_imgs/icons/bestbets.svg</br>
ID: marketo_bestbets</br>
제목: Best Bets

   **내 이메일**</br>
URL: mkt_/MainViewMyEmail.html</br>
아이콘: /WebResources/mkt_/_MainView/_imgs/icons/email.svg</br>
ID: marketo_myemail</br>
제목: 내 이메일

   **웹 활동**</br>
URL: mkt_/MainViewWebActivity.html</br>
아이콘: /WebResources/mkt_/_MainView/_imgs/icons/web_activity.svg</br>
ID: marketo_webactivity</br>
제목: 웹 활동

   **익명 웹 활동**</br>
URL: mkt_/MainViewWebActivity.html</br>
아이콘: /WebResources/mkt_/_MainView/_imgs/icons/anonymous_web_activity.svg</br>
ID: marketo_anonymous_webactivity</br>
제목: 익명 웹 활동

1. 클릭 **저장** 완료 시.
