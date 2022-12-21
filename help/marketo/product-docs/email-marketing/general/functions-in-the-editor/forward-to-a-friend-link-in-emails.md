---
unique-page-id: 1900581
description: 이메일의 친구 링크로 전달 - Marketo 문서 - 제품 설명서
title: 이메일의 친구 링크로 전달
exl-id: 7addac65-4207-419f-845c-d6b2d08d299c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '703'
ht-degree: 0%

---

# 이메일의 친구 링크로 전달 {#forward-to-a-friend-link-in-emails}

이메일에 &#39;친구에게 전달&#39; 링크를 추가하면 이 링크를 통해 전달된 이메일을 받은 사용자를 추적하고 데이터베이스에 아직 없는 경우 자동으로 새 사람으로 추가할 수 있습니다.

예를 들어, Keith가 &#39;Forward to Friend&#39; 링크를 사용하여 이메일을 알 수 없는 사람 Mark에게 전달했다고 가정해 보겠습니다. Mark는 자동으로 새 사람으로 추가되고, 자신의 쿠키가 할당되고, 자신의 이메일 및 웹 활동이 그에 연결되어 있습니다. 그러나 Keith가 이메일 클라이언트에서 전달 단추를 사용하는 경우 Mark가 Keith로 잘못 쿠킹되고 해당 활동이 Keith의 활동으로 기록됩니다.

## 이메일 템플릿에 링크 추가 {#add-the-link-to-an-email-template}

1. 로 이동합니다. **Design Studio**.

   ![](assets/one-8.png)

1. 링크를 추가할 이메일 템플릿을 찾아 선택합니다. 클릭 **초안 편집**.

   ![](assets/two-7.png)

1. &#39;친구에게 전달&#39; 링크를 표시할 다음 HTML 코드를 붙여 넣습니다(이 부분에 대한 도움이 필요한 경우 웹 개발자에게 문의하십시오.).

   `<pre data-theme="Confluence"><a href="{{system.forwardToFriendLink}}">Forward to Friend</a></pre>`

   ![](assets/three-7.png)

   >[!TIP]
   >
   >
   >링크를 더 멋있게 보이도록 스타일을 추가할 수 있습니다. For example:
   >
   >`<a href="{{system.forwardToFriendLink}}" style="font-family:arial, sans-serif; padding:10px; position:absolute; right:0px;">Forward to Friend</a>`

   >[!CAUTION]
   >
   >스타일링을 사용하지 않는 것이 좋습니다 **position:상대** 이메일 템플릿에 추가합니다. &#39;친구에게 전달&#39; 상자의 위치 및 표시에 문제가 발생할 수 있습니다.

1. 클릭 **초안 미리 보기** 템플릿이 원하는 방식으로 표시되는지 확인합니다.

   ![](assets/four-5.png)

   >[!NOTE]
   >
   >변경 사항을 적용하려면 템플릿 초안을 승인해야 합니다.

   이제 해당 템플릿을 사용하는 모든 이메일에는 &#39;친구에게 전달&#39; 링크가 있습니다. 이메일 수신자가 클릭하면 &#39;친구에게 전달&#39; 상자가 있는 이메일의 웹 버전으로 이동합니다.

   ![](assets/f2afbox.png)

## 개별 전자 메일에 링크 추가 {#add-the-link-to-an-individual-email}

&#39;친구에게 전달&#39; 링크를 이메일에 직접 추가할 수도 있습니다.

1. 링크를 포함할 이메일을 열고 편집 가능한 영역을 두 번 클릭합니다.

   ![](assets/five-4.png)

1. 링크를 표시할 위치에 커서를 놓고 **토큰 삽입** 버튼을 클릭합니다.

   ![](assets/six-2.png)

1. 을(를) 선택합니다 **`{{system.forwardToFriendLink}}`** 토큰.

   ![](assets/seven-1.png)

   >[!NOTE]
   >
   >이 토큰은 &#39;친구에게 전달&#39; 상자가 있는 전자 메일의 웹 버전 URL입니다.

1. 링크의 표시 텍스트를 원하는 대로 입력합니다(예: &quot;친구에게 전달&quot;).

   ![](assets/seven-1.png)

1. 잘라내기 **`{{system.forwardToFriendLink}}`** Ctrl+X(Windows) 또는 Cmd+X(Mac)을 사용한 토큰. &quot;친구에게 전달&quot;을 강조 표시하고 **링크 삽입/편집** 버튼을 클릭합니다.

   ![](assets/eight-1.png)

1. 붙여넣기 **`{{system.forwardToFriendLink}}`** 토큰으로 **URL** Ctrl/Cmd+V를 사용한 상자를 클릭한 다음 **삽입**.

   ![](assets/nine.png)

1. 편집 내용을 저장하고 새 링크를 미리 봅니다!

   ![](assets/ten-1.png)

   >[!NOTE]
   >
   >&#39;친구에게 전달&#39; 이메일을 수신하여 추가된 새 사용자는 기본적으로 마케팅 이메일에 대한 구독을 취소합니다.

## 전달 활동 보기 {#view-forwarding-activity}

개인 활동 로그에서 전자 메일을 보내고 받은 사용자를 확인할 수 있습니다.

1. 로 이동합니다. **`Database`**.

   ![](assets/db.png)

1. 활동을 보려는 사람을 두 번 클릭합니다.

   ![](assets/fourteen.png)

1. 로 이동합니다. **활동 로그** 탭. 두 번 클릭 **친구에게 전달 전자 메일 수신** 또는 **친구 전자 메일로 보내기** 자세히 보기.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >**정의**
   >
   >Received Forward to Friend Email의 경우 개인 ID는 이메일을 전달한 사용자입니다.
   >
   >Sent Email로 보내기 의 경우 개인 ID는 이메일을 받은 사용자입니다.

   ![](assets/sixteen.png)

1. ID별로 사람을 보려면 **개인 ID** url의 끝(이 URL의 시작 부분은 Marketo 인스턴스에 따라 다릅니다.):

   `<pre data-theme="Confluence">...marketo.com/Database/loadPersonDetail?personId=</pre>`

   >[!NOTE]
   >
   >우리는 그것을 만들 것입니다 **개인 ID** 을 클릭하여 예정된 패치의 사람에게 직접 연결합니다.

   ![](assets/seventeen.png)

   >[!NOTE]
   >
   >&#39;친구에 전달&#39;이란 미지의 인물이 있을 경우 &#39;친구에 전달&#39;이라는 새로운 인물이 등장한다 **소스**.
   >이메일이 프로그램의 로컬 자산인 경우 프로그램은 개인의 자산으로 표시됩니다 **획득 프로그램**.

## 전달 활동을 사용하여 트리거 또는 필터링 {#trigger-or-filter-using-forwarding-activity}

6개의 트리거/필터를 사용하여 플로우 작업을 트리거하거나 &#39;친구에게 전달&#39; 활동을 통해 사람을 필터링합니다.

스마트 캠페인의 스마트 목록에서 &quot;앞으로&quot;를 검색하는 경우 사용 가능한 트리거와 필터를 찾을 수 있습니다.

![](assets/nineteen.png)

## 친구에게 전달 테스트 {#test-forward-to-friend}

&#39;Forward to Friend&#39;를 테스트하려면 Forward 링크가 포함된 이메일을 자신에게 보냅니다. 을 통해 전송해야 합니다. **이메일 보내기** 흐름 단계, *not* through **테스트 이메일 보내기**.
