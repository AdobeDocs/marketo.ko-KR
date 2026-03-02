---
description: 시스템 상태 알림 구독 - Marketo Engage 문서 - 제품 설명서
title: 시스템 상태 알림 구독
feature: Getting Started
exl-id: f4404a26-3b86-4dc7-8ecb-52a24fdb09b4
source-git-commit: b17727645a56dd4417e91ee2d94f680d4dec2ca8
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 1%

---

# 시스템 상태 알림 구독 {#subscribe-to-system-status-notifications}

다양한 상태 알림을 구독하여 현재 문제에 대한 최신 정보를 유지하는 방법을 알아봅니다.

>[!PREREQUISITES]
>
>구독을 만들려면 먼저 구독이 위치한 데이터 센터와 pod/server를 식별해야 합니다.

## 데이터 센터 식별 {#identify}

1. Marketo Engage의 **관리자** 섹션에서 **내 계정**&#x200B;을 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-1.png)

1. _지원 정보_(으)로 스크롤합니다.

   ![](assets/subscribe-to-system-status-notifications-2.png)

_데이터 센터_ 필드에서 문자는 데이터 센터이고 숫자는 pod입니다. 위의 예에서, 사용자는 pod 49의 Ashburn 데이터 센터에 있습니다.

[아래 섹션](#create-a-subscription)의 7단계에서 이 사용자는 지역 위치 **Marketo Ashburn** 및 pod **ab49**&#x200B;을(를) 선택합니다.

**데이터 센터 약어**

ab: 애쉬번
sj: 산호세
sn: Sydney
lon: 런던
nld: 암스테르담

>[!TIP]
>
>이 방법을 사용하여 구독이 있는 실시간 Personalization(RTP) pod/서버를 식별할 수도 있습니다.

## 구독 만들기 {#create-a-subscription}

[데이터 센터 및 pod/server를 식별한 후](#identify) 아래 단계에 따라 구독을 만드십시오.

1. [status.adobe.com](https://status.adobe.com)에서 **구독 관리**&#x200B;를 클릭하십시오.

   ![](assets/subscribe-to-system-status-notifications-3.png)

1. Adobe 자격 증명을 사용하여 로그인하거나(아직 로그인하지 않은 경우), 계정이 없는 경우 **계정 만들기**&#x200B;를 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-4.png)

1. _제품 설명_ 탭에서 **구독 만들기**&#x200B;를 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-5.png)

1. ![Experience Cloud](assets/icon-plus-sign.png) 옆에 있는 _더하기 기호 아이콘_ 아이콘을 클릭하여 메뉴를 확장합니다. _Adobe Marketo Engage_&#x200B;에 대해서도 동일한 작업을 수행합니다.

   ![](assets/subscribe-to-system-status-notifications-6.png){width="800"}

1. 알림을 받을 제품/서비스를 선택하고 **계속**&#x200B;을 클릭합니다.

   >[!TIP]
   >
   >모두 선택하려면 _Adobe Marketo Engage_&#x200B;을 확인하세요.

   ![](assets/subscribe-to-system-status-notifications-7.png){width="800"}

1. 원하는 이벤트 유형을 선택합니다.

   ![](assets/subscribe-to-system-status-notifications-8.png)

   <table style="width:500px;">
   <tr>
   <td style="width:35%;"><b>주요 서비스 문제</b></td>
   <td>운영 시스템의 여러 사용자에 대한 서비스 가용성 또는 심각한 성능 저하.</td>
   </tr>
   <tr>
   <td style="width:35%;"><b>부수적 서비스 문제</b></td>
   <td>프로덕션 시스템의 여러 사용자에 대해 부분 서비스를 사용할 수 없거나 중간 수준의 성능 저하가 발생합니다.</td>
   </tr>
   <tr>
   <td style="width:35%;"><b>서비스 유지 관리</b></td>
   <td>제품 가용성 또는 성능에 영향을 줄 수 있는 제품 유지 관리를 수행하는 예약된 창입니다.</td>
   </tr>
   <tr>
   <td style="width:35%;"><b>공지</b></td>
   <td>광범위한 영향을 미치는 글로벌, 제품군 또는 제품 관련 메시지.</td>
   </tr>
   </table>

1. 지리적 위치 및 환경을 선택합니다. **계속**&#x200B;을 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-9.png){width="900"}

   >[!NOTE]
   >
   >찾을 위치가 없으면 [데이터 센터 식별](#identify)을 참조하세요.

1. 구독 환경 설정(**이메일** 또는 **Slack**)을 선택하고 **계속**&#x200B;을 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-10.png)

1. 선택 내용을 검토하고 **환경 설정 확인**&#x200B;을 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-11.png)
