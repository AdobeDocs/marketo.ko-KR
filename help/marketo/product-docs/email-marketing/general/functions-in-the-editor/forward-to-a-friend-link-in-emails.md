---
unique-page-id: 1900581
description: 이메일의 친구 링크에 전달 - Marketo 문서 - 제품 설명서
title: 이메일의 친구 링크로 전달
exl-id: 7addac65-4207-419f-845c-d6b2d08d299c
feature: Email Editor
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '681'
ht-degree: 0%

---

# 이메일의 친구 링크로 전달 {#forward-to-a-friend-link-in-emails}

이메일에 &#39;친구에게 전달&#39; 링크를 추가하면 이 링크를 통해 전달된 이메일을 받은 사람을 추적할 수 있으며, 데이터베이스에 아직 없는 경우 자동으로 새 사람으로 추가됩니다.

예를 들어 Keith가 &#39;친구에게 전달&#39; 링크를 사용하여 이메일을 알 수 없는 사람인 Mark에게 전달한다고 가정해 보겠습니다. Mark는 자동으로 새 사용자로 추가되고, 자신의 쿠키가 할당되며, 이메일 및 웹 활동이 Mark와 연결됩니다. 그러나 Keith가 이메일 클라이언트에서 전달 버튼을 사용하는 경우 Mark는 Keith로 잘못 요리되고 그의 활동은 Keith로 기록됩니다.

## 이메일 템플릿에 링크 추가 {#add-the-link-to-an-email-template}

1. **[!UICONTROL Design Studio]**(으)로 이동합니다.

   ![](assets/one-8.png)

1. 링크를 추가할 이메일 템플릿을 찾아 선택합니다. **[!UICONTROL Edit Draft]**&#x200B;을(를) 클릭합니다.

   ![](assets/two-7.png)

1. &#39;친구에게 전달&#39; 링크를 표시할 다음 HTML 코드를 붙여넣습니다(이 부분에 대한 도움이 필요한 경우 웹 개발자에게 문의하십시오).

   `<a href="{{system.forwardToFriendLink}}">Forward to Friend</a>`

   ![](assets/three-7.png)

   >[!TIP]
   >
   >
   >링크에 스타일을 추가하여 더 보기 좋게 만들 수 있습니다. 예:
   >
   >`<a href="{{system.forwardToFriendLink}}" style="font-family:arial, sans-serif; padding:10px; position:absolute; right:0px;">Forward to Friend</a>`

   >[!CAUTION]
   >
   >이메일 템플릿에서 스타일 **position:relative**&#x200B;을(를) 사용하지 않는 것이 좋습니다. &#39;친구에게 전달&#39; 상자의 위치 및 표시에 문제가 발생할 수 있습니다.

1. **[!UICONTROL Preview Draft]**&#x200B;을(를) 클릭하여 서식 파일이 원하는 대로 보이는지 확인하십시오.

   ![](assets/four-5.png)

   >[!NOTE]
   >
   >변경 사항을 적용하려면 템플릿 초안을 승인해야 합니다.

   이제 해당 템플릿을 사용하는 모든 이메일에 &#39;친구에게 전달&#39; 링크가 생깁니다. 이메일 수신자가 이를 클릭하면 &#39;친구에게 전달&#39; 상자가 있는 이메일 웹 버전으로 이동합니다.

   ![](assets/f2afbox.png)

## 개별 이메일에 링크 추가 {#add-the-link-to-an-individual-email}

&#39;친구에게 전달&#39; 링크를 이메일에 바로 추가할 수도 있습니다.

1. 링크를 포함할 이메일을 열고 편집 가능 영역을 두 번 클릭합니다.

   ![](assets/five-4.png)

1. 링크를 표시할 위치에 커서를 놓고 **토큰 삽입** 단추를 클릭합니다.

   ![](assets/six-2.png)

1. **`{{system.forwardToFriendLink}}`** 토큰을 선택하십시오.

   ![](assets/seven-1.png)

   >[!NOTE]
   >
   >이 토큰은 &#39;친구에게 전달&#39; 상자가 있는 이메일 웹 버전의 URL입니다.

1. 링크 표시 텍스트를 작성할 내용(예: &quot;친구에게 전달&quot;)을 작성합니다.

   ![](assets/seven-1.png)

1. Ctrl+X(Windows) 또는 Cmd+X(Mac)를 사용하여 **`{{system.forwardToFriendLink}}`** 토큰을 잘라냅니다. &quot;친구에게 전달&quot;을 강조 표시하고 **링크 삽입/편집** 단추를 클릭합니다.

   ![](assets/eight-1.png)

1. Ctrl/Cmd+V를 사용하여 **`{{system.forwardToFriendLink}}`** 토큰을 **URL** 상자에 붙여 넣은 다음 **[!UICONTROL Insert]**&#x200B;을(를) 클릭합니다.

   ![](assets/nine.png)

1. 편집 내용을 저장하고 새 링크를 미리 봅니다!

   ![](assets/ten-1.png)

   >[!NOTE]
   >
   >&#39;친구에게 전달&#39; 이메일 수신을 통해 추가되는 새 사용자는 기본적으로 마케팅 이메일 구독을 취소합니다.

## 전달 활동 보기 {#view-forwarding-activity}

사용자의 활동 로그에서 이메일을 보낸 사람과 받은 사람을 볼 수 있습니다.

1. **[!UICONTROL Database]**(으)로 이동합니다.

   ![](assets/db.png)

1. 활동을 보려는 사람을 두 번 클릭합니다.

   ![](assets/fourteen.png)

1. **[!UICONTROL Activity Log]** 탭으로 이동합니다. 자세한 내용을 보려면 **[!UICONTROL Received Forward to Friend Email]** 또는 **[!UICONTROL Sent Forward to Friend Email]**&#x200B;을(를) 두 번 클릭하십시오.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >**정의**
   >
   >친구에게 전송 받은 이메일의 경우 개인 ID는 이메일을 전송한 사람입니다.
   >
   >친구에게 보낸 이메일의 경우 개인 ID는 이메일을 받은 사람입니다.

   ![](assets/sixteen.png)

1. ID별로 개인을 보려면 **개인 ID**&#x200B;를 복사하여 URL 끝에 붙여넣습니다(URL의 시작 부분은 Marketo 인스턴스에 따라 다름).

   `...marketo.com/Database/loadPersonDetail?personId=`

   >[!NOTE]
   >
   >**[!UICONTROL Person ID]**&#x200B;을(를) 클릭할 수 있게 만들고 향후 패치의 사용자에게 직접 연결합니다.

   ![](assets/seventeen.png)

   >[!NOTE]
   >
   >전달을 받는 친구가 알 수 없는 사람인 경우 &#39;친구에게 전달&#39;이 해당 사용자의 **Source**(으)로 표시된 새 사람이 만들어집니다.
   >전자 메일이 프로그램의 로컬 자산인 경우 프로그램이 개인의 **획득 프로그램**(으)로 표시됩니다.

## 전달 활동을 사용하여 트리거 또는 필터링 {#trigger-or-filter-using-forwarding-activity}

&#39;친구에게 전달&#39; 활동을 보내고 받음으로써 흐름 작업을 트리거하거나 사람을 필터링하는 데 사용할 수 있는 6개의 트리거/필터가 있습니다.

스마트 캠페인의 스마트 목록에서 &quot;앞으로&quot;를 검색하면 사용 가능한 트리거 및 필터를 찾을 수 있습니다.

![](assets/nineteen.png)

## 친구에게 테스트 전달 {#test-forward-to-friend}

&#39;친구에게 전달&#39;을 테스트하려면 전달 링크가 포함된 이메일을 자신에게 보내십시오. **전자 메일 보내기** 흐름 단계, *아님*&#x200B;부터 **테스트 전자 메일 보내기**&#x200B;를 통해 보내십시오.
