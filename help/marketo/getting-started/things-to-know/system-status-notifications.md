---
description: 시스템 상태 알림 구독 - Marketo Engage 문서 - 제품 설명서
title: 시스템 상태 알림 구독
feature: Getting Started
hide: true
hidefromtoc: true
source-git-commit: 5c82b2e793596878186256f993ed3d672152556d
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 1%

---

# 시스템 상태 알림 구독 {#subscribe-to-system-status-notifications}

소개 텍스트

>[!PREREQUISITES]
>
>구독을 만들려면 먼저 구독이 위치한 데이터 센터와 pod/server를 식별해야 합니다.

## 데이터 센터 식별 {#identify}

+++데이터 센터 및 pod/서버 식별

1. Marketo Engage의 **관리자** 섹션에서 **내 계정**&#x200B;을 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-1.png)

1. _지원 정보_(으)로 스크롤합니다.

   ![](assets/subscribe-to-system-status-notifications-2.png)

_데이터 센터_ 필드에서 문자는 데이터 센터이고 숫자는 pod입니다. 위의 예에서, 사용자는 pod 49의 Ashburn 데이터 센터에 있습니다.

[구독 만들기](#create-a-subscription)의 7단계에서 이 사용자는 지역 위치 **Marketo Ashburn** 및 pod **ab49**&#x200B;을(를) 선택합니다.

<table style="width:225px;">
  <tr>
    <th colspan="2">데이터 센터 약자</th>
  </tr>
  <tr>
    <td style="width:25%;">ab</td>
    <td>애쉬번</td>
  </tr>
  <tr>
    <td style="width:25%;">sj</td>
    <td>산호세</td>
  </tr>
  <tr>
    <td style="width:25%;">sn</td>
    <td>시드니</td>
  </tr>
  <tr>
    <td style="width:25%;">lon</td>
    <td>런던</td>
  </tr>
  <tr>
    <td style="width:25%;">nld</td>
    <td>암스테르담</td>
  </tr>
</table>

>[!TIP]
>
>이 방법을 사용하여 구독이 있는 실시간 Personalization(RTP) pod/서버를 식별할 수도 있습니다.

+++

## 구독 만들기 {#create-a-subscription}

[데이터 센터 및 pod/server를 식별한 후](#identify) 아래 단계에 따라 구독을 만드십시오.

1. [status.adobe.com](https://status.adobe.com)에서 **구독 관리**&#x200B;를 클릭하십시오.

   ![](assets/subscribe-to-system-status-notifications-3.png)

1. Adobe 자격 증명을 사용하여 로그인하거나(아직 로그인하지 않은 경우), 계정이 없는 경우 **계정 만들기**&#x200B;를 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-4.png)

1. _제품 설명_ 탭에서 **구독 만들기**&#x200B;를 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-5.png)

1. ![Experience Cloud](assets/icon-plus-sign.png) 옆에 있는 _더하기 기호 아이콘_ 아이콘을 클릭하여 메뉴를 확장합니다. _Adobe Marketo Engage_&#x200B;에 대해서도 동일한 작업을 수행합니다.

   ![](assets/subscribe-to-system-status-notifications-6.png)

1. 알림을 받을 제품/서비스를 선택하고 **계속**&#x200B;을 클릭합니다.

   >[!TIP]
   >
   >모두 선택하려면 _Adobe Marketo Engage_&#x200B;을 확인하세요.

   ![](assets/subscribe-to-system-status-notifications-7.png)

1. 원하는 이벤트 유형을 선택합니다.

   ![](assets/subscribe-to-system-status-notifications-8.png)

   <table style="width:600px;">
   <tr>
   <td style="width:30%;"><b>주요 서비스 문제</b></td>
   <td>운영 시스템의 여러 사용자에 대한 서비스 가용성 또는 심각한 성능 저하.</td>
   </tr>
   <tr>
   <td style="width:30%;"><b>부수적 서비스 문제</b></td>
   <td>프로덕션 시스템의 여러 사용자에 대해 부분 서비스를 사용할 수 없거나 중간 수준의 성능 저하가 발생합니다.</td>
   </tr>
   <tr>
   <td style="width:30%;"><b>서비스 유지 관리</b></td>
   <td>텍스트</td>
   </tr>
   <tr>
   <td style="width:30%;"><b>공지</b></td>
   <td>다음 항목과 관련된 공지...</td>
   </tr>
   </table>

1. 원하는 지리적 위치 및 환경을 선택합니다. **계속**&#x200B;을 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-9.png)

1. 구독 환경 설정(**이메일** 또는 **Slack**)을 선택하고 **계속**&#x200B;을 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-10.png)

1. 선택 내용을 검토하고 **환경 설정 확인**&#x200B;을 클릭합니다.

   ![](assets/subscribe-to-system-status-notifications-11.png)
