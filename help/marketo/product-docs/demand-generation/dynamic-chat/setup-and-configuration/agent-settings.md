---
description: 에이전트 설정 - Marketo 문서 - 제품 설명서
title: 에이전트 설정
feature: Dynamic Chat
source-git-commit: 9a8f6fe57b585ba0eac6a577bf99e0419d8818a1
workflow-type: tm+mt
source-wordcount: '486'
ht-degree: 2%

---

# 에이전트 설정 {#agent-settings}

일정을 구성하고 모임/라이브 채팅 가용성을 설정합니다.

![](assets/agent-settings-1.png)

## 캘린더 연결 {#connect-calendar}

캘린더 구성 탭에서 챗봇의 약속 예약에 사용할 Outlook 또는 Gmail 캘린더를 연결합니다.

![](assets/agent-settings-2.png)

사용자의 캘린더가 Dynamic Chat에 연결되면 해당 캘린더가 큐에 추가되고 웹 사이트 방문자가 약속을 예약할 수 있습니다.

>[!NOTE]
>
>사용자당 하나의 달력을 연결할 수 있습니다. 여러 캘린더에서 모임을 받으려면 여러 사용자를 추가하고 각 사용자를 캘린더에 연결하도록 해야 합니다.

사용자는 사용자 달력에서 약속을 예약할 때 방문자에게 전송되는 초대 본문을 사용자 지정할 수도 있습니다. 하단의 확인란을 선택하여 Google 모임 또는 Microsoft Teams 링크를 포함할 수도 있습니다(연결된 캘린더에 따라 다름).

![](assets/agent-settings-3.png)

>[!TIP]
>
>토큰 아이콘(중괄호)을 사용하여 개인 또는 회사 특성을 사용하여 모임 예약 확인 이메일을 개인화할 수 있습니다.

### 권한 {#permissions}

Outlook으로 구성하면 Dynamic Chat에 다음 권한이 부여됩니다.

* 캘린더에 대한 전체 액세스
* 로그인 및 프로필 읽기
* 액세스 권한을 부여한 데이터에 대한 액세스 유지
* 사서함 설정 읽기

Google으로 구성하면 Dynamic Chat에 대한 다음 권한이 부여됩니다.

* 캘린더 만들기, 변경 또는 삭제
* 개별 달력 이벤트 업데이트
* 이벤트를 볼 수 있는 사람을 포함하여 설정 변경
* 캘린더를 공유한 사람 변경
* 이름, 이메일 주소, 언어 환경 설정 및 프로필 사진에 액세스

## 모임 예약 가용성 {#meeting-booking-availability}

시간대 및 가능한 시간/요일을 설정하여 모임 예약을 받을 수 있습니다.

![](assets/agent-settings-4.png)

<table> 
 <tbody> 
  <tr> 
   <td><b>회의 기간</b></td>
   <td>방문자가 사용 가능한 모임 슬롯에서 볼 수 있는 시간을 결정합니다.</td>
  </tr> 
  <tr> 
   <td><b>회의 간 여유 시간</b></td>
   <td>회의 후 버퍼로 설정한 시간입니다. 30분 동안 설정하면 캘린더에서 예약된 회의가 끝난 후 30분이 지날 때까지 아무도 귀하와의 회의를 예약할 수 없습니다.</td>
  </tr>
 </tbody> 
</table>

>[!TIP]
>
>같은 날 여러 개의 시간 블록을 선택할 수 있습니다(예: 8a-12p의 금요일) _및_ 1p-5p)를 클릭합니다. **+** 오른쪽에 사인하세요.

## 라이브 채팅 사용 가능 여부 {#live-chat-availability}

실시간 채팅을 받을 수 있는 표준 시간대와 시간/요일을 설정하십시오.

![](assets/agent-settings-5.png)

앱에 로그인하면 수신 채팅에 대한 인앱 알림을 받게 됩니다. 로그인하지 않은 경우 브라우저 알림을 받게 됩니다(다음을 보유한 경우). [설정](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md#live-chat-notifications){target="_blank"}).

>[!IMPORTANT]
>
>다음 [가용성 전환](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md#availability-toggle){target="_blank"} 에이전트 받은 편지함에서 **재정의** 라이브 채팅 가용성 탭에 입력하는 내용. 따라서 1p-5p부터 사용할 수 있도록 예약되어 있지만 3p에 잠깐 쉬어야 하는 경우에는 에이전트 설정을 변경할 필요가 없습니다. 가용성 전환 상태는 수동으로 변경하거나 가용성의 다음 블록에 도달할 때까지 유지됩니다.

>[!TIP]
>
>같은 날 여러 개의 시간 블록을 선택할 수 있습니다(예: 8a-12p의 금요일) _및_ 1p-5p)를 클릭합니다. **+** 오른쪽에 사인하세요.
