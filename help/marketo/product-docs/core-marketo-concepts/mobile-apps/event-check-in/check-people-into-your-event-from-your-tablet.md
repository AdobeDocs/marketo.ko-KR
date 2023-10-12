---
unique-page-id: 2949839
description: 태블릿에서 이벤트 직원 확인 - Marketo 문서 - 제품 설명서
title: 태블릿에서 다른 사람을 내 이벤트에 체크 인
exl-id: b48f5f95-8e36-441f-a785-1651f42f9f60
feature: Mobile Marketing
source-git-commit: 0abb315be0f9cb5f42fa41d72b446de8c2f62c1e
workflow-type: tm+mt
source-wordcount: '842'
ht-degree: 0%

---

# 태블릿에서 다른 사람을 내 이벤트에 체크 인 {#check-people-into-your-event-from-your-tablet}

사람들이 이벤트에 나타나면 앱에서 해당 정보를 찾을 수 있습니다. 체크인 후 Marketo에 동기화하면 출석됨 상태로 승격됩니다.

>[!IMPORTANT]
>
>2023년 10월 2일에 Adobe은 모든 앱스토어에서 Marketo 이벤트 앱을 제거했습니다. 태블릿/모바일 장치에 이미 앱이 설치되어 있는 경우 당분간 앱을 계속 사용할 수 있습니다. Marketo 인증을 위해 Marketo Engage 인스턴스가 Adobe ID로 마이그레이션되면 더 이상 앱에 액세스할 수 없습니다. [자세히 알아보기](https://nation.marketo.com/t5/product-discussions/marketo-events-app-and-marketo-moments-app-end-of-life/m-p/340712/highlight/true#M193869){target="_blank"}.

이 앱은 두 앱에서 동일하게 작동합니다 [!DNL iPad] 및 [!DNL Android], 일부 레이아웃 및 디자인 차이점 제외.

>[!PREREQUISITES]
>
>* Marketo에서 이벤트를 만들고 초대됨 및 등록된 사용자로 채웁니다.

## 등록된 게스트 체크인 {#check-in-registered-guests}

1. 에서 앱 아이콘 탭하기 [!DNL iPad] 또는 [!DNL Android] 태블릿.

1. 누르기 **[!UICONTROL 로그인]** Marketo 이벤트 앱을 시작합니다.

   ![](assets/1.jpg)

1. Marketo 사용자 이름과 암호를 입력하고 **[!UICONTROL 로그인]**.

   >[!NOTE]
   >
   >앱에서 사용자를 보려면 데이터베이스에 액세스할 수 있는 역할이 있어야 합니다.

1. 선택 **[!UICONTROL 이벤트]**.

   ![](assets/2.jpg)

   >[!TIP]
   >
   >오늘 날짜의 1주일 전 및 1주일 후에 예약된 이벤트 프로그램(웨비나 제외)만 표시됩니다.

1. 홈 화면에서 등록된 게스트를 찾습니다. 목록에서 개인을 찾으려면 다음을 수행할 수 있습니다.

   * 스크롤하여 이름 찾기
   * 검색 필드에 이름을 입력합니다
   * 목록의 오른쪽에서 탭하여 성의 특정 첫 글자로 이동

   >[!NOTE]
   >
   >프로세스는 동일합니다 [!DNL iPad] 및 [!DNL Android]: 화면이 다르고 항목이 다른 위치에 있을 수 있습니다. 이 문서에서는 [!DNL iPad] 인터페이스. 비교 [!DNL Android] 참조를 위해 이 섹션의 화면입니다.

   **[!DNL iPad]**

   ![](assets/image2016-4-15-11-3a55-3a11.png)

   **[!DNL Android]**

   ![](assets/image2016-4-15-14-3a50-3a19.png)

1. 선택한 이름을 탭하고 개인 레코드에서 을 누릅니다. **[!UICONTROL 체크인]**.

   ![](assets/img-0068-35-hands.png)

이제 게스트가 출석함 상태이며 확인 표시를 받습니다. 개인 레코드는 Marketo과 동기화할 때 업데이트됩니다. 동기화 버튼의 빨간색 카운터는 Marketo과의 마지막 동기화 이후 체크인 수를 표시하도록 증가합니다. 동기화 버튼이 다르게 보이며 다음에 대한 다른 위치에 있습니다. [!DNL iPad] 및 [!DNL Android]:

**[!DNL iPad]**

![](assets/image2016-4-12-14-3a25-3a13.png)

**[!DNL Android]**

![](assets/image2016-4-15-14-3a58-3a6.png)

>[!TIP]
>
>초대를 받았지만 등록하지 않은 경우 다음을 클릭하여 이름을 검색할 수 있습니다. **[!UICONTROL 서버에서 검색]**&#x200B;검색 상자 바로 아래에 있습니다. 초대됨 상태가 다음으로 변경됨: **[!UICONTROL 출석함]** 이벤트용.

## 태블릿에서 새 사용자 만들기 {#create-a-new-person-on-the-tablet}

Marketo 데이터베이스에 기존 사람이 아닌 게스트를 수동으로 추가할 수 있습니다. Marketo과 동기화할 때 자동으로 체크인되고 데이터베이스에 추가됩니다.

1. 클릭 **[!UICONTROL 추가]**.

   **[!DNL iPad]**

   ![](assets/image2016-4-15-11-3a58-3a51.png)

   **[!DNL Android]**

   ![](assets/image2016-4-15-15-3a2-3a38.png)

1. 가능한 한 많은 기본 정보 필드를 작성하고 탭합니다. **[!UICONTROL 완료]**.

   ![](assets/image2016-4-15-11-3a33-3a59.png)

   >[!NOTE]
   >
   >기존 필드만 사용할 수 있습니다. 사용자 지정 항목을 만들 수 없습니다.

   >[!CAUTION]
   >
   >이메일 주소를 다시 확인하십시오. 다른 필드는 나중에 수정할 수 있지만 이메일 주소가 게스트에 연락하는 기본 방법입니다.

새로운 사용자는 이벤트에 체크 인된 것으로 등록되고, Marketo에 동기화할 때 출석함 상태로 Marketo 데이터베이스에 추가됩니다.

## 체크인 취소 {#reverse-a-check-in}

실수로 체크인하셨다면, _Marketo과 동기화하기 전_&#x200B;을 눌러 출석됨 상태를 취소할 수 있습니다.

1. 목록에서 이름을 탭하고 개인 레코드에서 을 누릅니다. **[!UICONTROL 실행 취소]**.

   ![](assets/image2016-4-15-11-3a38-3a31.png)

   모두 해결되었습니다!

## 체크인 시 개인 레코드 편집 {#edit-a-person-record-at-check-in}

이벤트에서 바로 게스트 정보를 추가하고 수정할 수 있습니다!

1. 인물 목록에서 이름을 탭한 다음 탭합니다. **[!UICONTROL 편집]**.

   ![](assets/image2016-4-15-11-3a43-3a46.png)

1. 정보를 편집하고 필드에 추가한 다음 을 누릅니다 **[!UICONTROL 완료]**.

   ![](assets/image2016-4-15-11-3a50-3a18.png)

   >[!NOTE]
   >
   >위치 [!DNL Android], **[!UICONTROL 완료]** 단추가 숨겨져 있을 수 있습니다. 아래로 스크롤하여 찾습니다.

앱을 Marketo과 동기화하면 정보가 업데이트됩니다.

## 앱을 Marketo과 동기화 {#sync-the-app-with-marketo}

Marketo 이벤트 앱은 활동을 Marketo 데이터베이스에 다시 동기화할 때까지 독립적으로 작동합니다. 마지막 체크인 후 가능한 한 빨리 동기화하는 것이 가장 좋습니다. 태블릿이 인터넷에 연결되어 있어야 합니다.

>[!CAUTION]
>
>동기화한 후에는 앱에서 체크 인을 되돌릴 수 없습니다.

1. 태블릿에서 앱을 열고 이벤트로 이동합니다.

1. 누르기 **[!UICONTROL 동기화]**.

   이벤트가 Marketo 데이터베이스의 새 체크 인으로 업데이트됩니다. [동기화] 단추의 빨간색 카운터는 다른 사용자를 체크 인할 때까지 지워집니다.

   보안상의 이유로 동기화를 완료한 후에는 Marketo 이벤트 앱을 종료해야 합니다.

## 제한된 인터넷 액세스 사용 {#working-with-limited-internet-access}

일부 경기장은 인터넷 접속이 안 된다. 다음과 같은 작업을 수행하는 데 유용한 연결이 필요합니다.

* 앱 다운로드 및 설치
* 로그인
* 이벤트 선택
* 앱을 Marketo과 동기화

행사장 내 인터넷 접속이 걱정된다면 Marketo 이벤트 앱에 로그인하고 인터넷 접속성이 좋은 곳에서 미리 이벤트를 선택해 두는 것이 좋다. 그런 식으로 앱을 오프라인으로 사용할 수 있습니다. 그런 다음 인터넷 연결을 다시 얻으면 즉시 Marketo 데이터베이스에 동기화합니다.

>[!TIP]
>
>인터넷에 연결되어 있지 않아도 체크 인할 사람을 새로 만들 수 있습니다. 앱을 동기화할 때 기존 사용자와 조정됩니다.

>[!NOTE]
>
>8시간 동안 활동이 없으면 앱에서 자동으로 로그아웃됩니다.
