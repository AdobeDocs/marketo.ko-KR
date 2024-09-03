---
description: 권한 - Marketo 문서 - 제품 설명서
title: 권한
feature: Dynamic Chat
exl-id: 06798ac4-636b-476e-bbb1-498062844406
source-git-commit: 38e1e2d8c2fef7163f77d7774837571008075b5f
workflow-type: tm+mt
source-wordcount: '712'
ht-degree: 4%

---

# 권한 {#permissions}

Dynamic Chat에서 편집할 수 있는 사전 정의된 권한이 있는 5개의 기본 프로필이 있습니다. 사용자 지정 권한 집합으로 사용자 지정 프로필을 만들 수도 있습니다. 둘 다 검토해 보겠습니다.

## 기존 권한 편집 {#edit-existing-permissions}

1. [Adobe Admin Console](https://adminconsole.adobe.com/){target="_blank"}에서 **Dynamic Chat**&#x200B;을 클릭합니다.

   ![](assets/permissions-1.png)

1. **제품 프로필** 탭에서 편집할 프로필을 선택합니다. 이 예제에서는 **Live 에이전트**&#x200B;을(를) 선택합니다.

   ![](assets/permissions-2.png)

1. **권한** 탭을 클릭합니다.

   ![](assets/permissions-3.png)

1. 편집할 프로필 영역을 선택합니다. 이 예제에서는 라이브 채팅을 선택합니다. 연필 아이콘을 클릭합니다.

   ![](assets/permissions-4.png)

1. 사용 가능한 권한 항목은 왼쪽에 나열됩니다. 권한을 하나씩 또는 모두 한 번에 추가하도록 선택할 수 있습니다. **+** 기호를 클릭합니다.

   ![](assets/permissions-5.png)

   >[!NOTE]
   >
   >자동 포함을 활성화하면 모든 권한 항목이 포함 목록에 추가됩니다. 새 권한 항목을 사용할 수 있게 되면 해당 제품 프로필에 자동으로 포함됩니다.

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/permissions-6.png)

이제 다른 모든 Dynamic Chat 영역에 대해 이 프로세스를 반복할 수 있습니다.

![](assets/permissions-7.png)

## 프로필 만들기 {#create-a-profile}

1. [Adobe Admin Console](https://adminconsole.adobe.com/){target="_blank"}에서 **Dynamic Chat**&#x200B;을 클릭합니다.

   ![](assets/permissions-8.png)

1. **제품 프로필** 탭에서 **새 프로필**&#x200B;을 클릭합니다.

   ![](assets/permissions-9.png)

1. 제품 프로필 **이름**. 선택적으로, 사용자에게 표시 이름 및/또는 설명을 지정하고, 사용자가 추가/제거될 때 알림이 표시되도록 선택할 수 있습니다. 완료되면 **저장**&#x200B;을 클릭합니다.

   ![](assets/permissions-10.png)

1. 새 프로필이 제품 프로필 탭에 나타납니다. 선택합니다.

   ![](assets/permissions-11.png)

1. 이제 원하는 각 영역에 대해 위의 [섹션](#edit-existing-permissions)에서 3~6단계를 수행합니다.

## 권한 목록 {#list-of-permissions}

아래에서는 각 영역에 대해 사용 가능한 모든 권한 목록을 확인할 수 있습니다.

<table>
<thead>
  <tr>
    <th style="width:25%">Dynamic Chat 영역</th>
    <th>권한</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>대화 관리</td>
    <td><li>대화 상자 보기</li>
    <li>대화 상자 관리(만들기, 삭제)</li>
    <li>Publish 대화 상자</li>
    <li>대화 흐름 보기</li>
    <li>대화 흐름 관리(만들기, 삭제)</li>
    <li>Publish 대화 흐름</li></td>
  </tr>
  <tr>
    <td>라이브 채팅</td>
    <td><li>내 대화 보기</li>
    <li>모든 대화 보기</li>
  </tr>
  <tr>
    <td>회의</td>
    <td><li>모든 모임 관리</li>
  </tr>
  <tr>
    <td>Analytics</td>
    <td><li>글로벌 성과 보고서 보기</li>
    <li>라이브 채팅 보고서 보기</li>
    <li>모임 보고서 보기</li>
    <li>보고서 내보내기</li></td>
  </tr>
  <tr>
    <td>에이전트 설정</td>
    <td><li>라이브 채팅 가용성 관리</li>
    <li>캘린더 연결</li>
    <li>일정 가용성 관리</li></td>
  </tr>
  <tr>
    <td>관리자 설정</td>
    <td><li>라운드 로빈 보기</li>
    <li>사용자 정의 규칙 보기</li>
    <li>사용자 정의 규칙 관리(추가, 편집, 삭제)</li>
    <li>계정 목록 <b>*</b> 보기</li>
    <li>계정 관리(추가, 편집, 삭제) <b>*</b></li>
    <li>챗봇 설정 관리</li>
    <li>대화 흐름 설정 관리</li>
    <li>개인 정보 및 보안 관리</li>
    <li>통합 관리</li>
    <li>에이전트 관리</li>
    <li>에이전트 팀 <b>*</b> 보기</li>
    <li>에이전트 팀 관리(추가, 편집, 삭제) <b>*</b></li></td>
  </tr>
</tbody>
</table>

**&#42;** 현재 Dynamic Prime 사용자만 사용할 수 있습니다.

<p>

## 기본 프로필 권한 {#default-profile-permissions}

다음은 기본적으로 활성화되어 있는 5개의 기본 프로필 및 권한입니다.

<table>
<thead>
  <tr>
    <th style="width:25%">프로필</th>
    <th>기본 권한</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>마케팅 사용자</td>
    <td><i>대화 관리</i>
    <li>대화 상자 보기</li>
    <li>대화 상자 관리(만들기, 삭제)</li>
    <li>Publish 대화 상자</li>
    <li>대화 흐름 보기</li>
    <li>대화 흐름 관리(만들기, 삭제)</li>
    <li>Publish 대화 흐름</li>
    <br>
    <i>실시간 채팅</i>
    <li>해당 사항 없음</li>
    <br>
    <i>모임</i>
    <li>해당 사항 없음</li>
    <br>
    <i>분석</i>
    <li>글로벌 성과 보고서 보기</li>
    <li>라이브 채팅 보고서 보기</li>
    <li>모임 보고서 보기</li>
    <br>
    <i>에이전트 설정</i>
    <li>해당 사항 없음</li>
    <br>
    <i>관리자 설정</i>
    <li>라운드 로빈 보기</li>
    <li>사용자 정의 규칙 보기</li>
    <li>계정 목록 <b>*</b> 보기</li>
    <li>에이전트 팀 <b>*</b> 보기</li>
    </td>
  </tr>
  <tr>
    <td><b>라이브 에이전트</b></td>
    <td><i>대화 관리</i>
    <li>대화 상자 보기</li>
    <li>대화 흐름 보기</li>
    <br>
    <i>실시간 채팅</i>
    <li>내 대화 보기</li>
    <br>
    <i>모임</i>
    <li>해당 사항 없음</li>
    <br>
    <i>분석</i>
    <li>글로벌 성과 보고서 보기</li>
    <li>라이브 채팅 보고서 보기</li>
    <li>모임 보고서 보기</li>
    <br>
    <i>에이전트 설정</i>
    <li>라이브 채팅 가용성 관리</li>
    <li>캘린더 연결</li>
    <li>일정 가용성 관리</li>
    <br>
    <i>관리자 설정</i>
    <li>라운드 로빈 보기</li>
    <li>사용자 정의 규칙 보기</li>
    <li>계정 목록 <b>*</b> 보기</li>
    <li>에이전트 팀 <b>*</b> 보기</li>
    </td>
  </tr>
  <tr>
    <td><b>캘린더 에이전트</b></td>
    <td><i>대화 관리</i>
    <li>대화 상자 보기</li>
    <li>대화 흐름 보기</li>
    <br>
    <i>실시간 채팅</i>
    <li>해당 사항 없음</li>
    <br>
    <i>모임</i>
    <li>해당 사항 없음</li>
    <br>
    <i>분석</i>
    <li>글로벌 성과 보고서 보기</li>
    <li>라이브 채팅 보고서 보기</li>
    <li>모임 보고서 보기</li>
    <br>
    <i>에이전트 설정</i>
    <li>캘린더 연결</li>
    <li>일정 가용성 관리</li>
    <br>
    <i>관리자 설정</i>
    <li>라운드 로빈 보기</li>
    <li>사용자 정의 규칙 보기</li>
    <li>계정 목록 <b>*</b> 보기</li>
    <li>에이전트 팀 <b>*</b> 보기</li>
    </td>
  </tr>
  <tr>
    <td><b>마케팅 관리자</b></td>
    <td><i>대화 관리</i>
    <li>대화 상자 보기</li>
    <li>대화 상자 관리(만들기, 삭제)</li>
    <li>Publish 대화 상자</li>
    <li>대화 흐름 보기</li>
    <li>대화 흐름 관리(만들기, 삭제)</li>
    <li>Publish 대화 흐름</li>
    <br>
    <i>실시간 채팅</i>
    <li>해당 사항 없음</li>
    <br>
    <i>모임</i>
    <li>해당 사항 없음</li>
    <br>
    <i>분석</i>
    <li>글로벌 성과 보고서 보기</li>
    <li>라이브 채팅 보고서 보기</li>
    <li>모임 보고서 보기</li>
    <li>보고서 내보내기</li>
    <br>
    <i>에이전트 설정</i>
    <li>해당 사항 없음</li>
    <br>
    <i>관리자 설정</i>
    <li>라운드 로빈 보기</li>
    <li>사용자 정의 규칙 보기</li>
    <li>사용자 정의 규칙 관리(추가, 편집, 삭제)</li>
    <li>계정 목록 <b>*</b> 보기</li>
    <li>계정 관리(추가, 편집, 삭제) <b>*</b></li>
    <li>챗봇 설정 관리</li>
    <li>대화 흐름 설정 관리</li>
    <li>개인 정보 및 보안 관리</li>
    <li>통합 관리</li>
    <li>에이전트 팀 <b>*</b> 보기</li>
    </td>
  </tr>
  <tr>
    <td><b>영업 관리자</b></td>
    <td><i>대화 관리</i>
    <li>대화 상자 보기</li>
    <li>대화 흐름 보기</li>
    <br>
    <i>실시간 채팅</i>
    <li>내 대화 보기</li>
    <li>모든 대화 보기</li>
    <br>
    <i>모임</i>
    <li>모든 모임 관리</li>
    <br>
    <i>분석</i>
    <li>글로벌 성과 보고서 보기</li>
    <li>라이브 채팅 보고서 보기</li>
    <li>모임 보고서 보기</li>
    <li>보고서 내보내기</li>
    <br>
    <i>에이전트 설정</i>
    <li>라이브 채팅 가용성 관리</li>
    <li>캘린더 연결</li>
    <li>일정 가용성 관리</li>
    <br>
    <i>관리자 설정</i>
    <li>라운드 로빈 보기</li>
    <li>사용자 정의 규칙 보기</li>
    <li>사용자 정의 규칙 관리(추가, 편집, 삭제)</li>
    <li>계정 목록 <b>*</b> 보기</li>
    <li>계정 관리(추가, 편집, 삭제) <b>*</b></li>
    <li>에이전트 관리</li>
    <li>에이전트 팀 <b>*</b> 보기</li>
    <li>에이전트 팀 관리 <b>*</b></li>
    </td>
  </tr>
</tbody>
</table>

**&#42;** 현재 Dynamic Prime 사용자만 사용할 수 있습니다.
