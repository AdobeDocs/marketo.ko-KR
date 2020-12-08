---
unique-page-id: 2360219
description: 사용자 지정 DKIM 서명 - 마케팅 문서 - 제품 설명서 설정
title: 사용자 지정 DKIM 서명 설정
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 0%

---


# 사용자 지정 DKIM 서명 설정 {#set-up-a-custom-dkim-signature}

최고의 전달을 보장하기 위해 공유 Marketing To DKIM 서명을 사용하여 모든 아웃바운드 메일에 자동으로 서명합니다.

>[!NOTE]
>
>이 문서의 일부 단계를 완료하려면 IT 팀의 도움이 필요할 수 있습니다.

원하는 도메인을 반영하도록 DKIM 서명을 개인화할 수 있습니다. 방법

1. 관리 **섹션으로** 이동합니다.

   ![](assets/adminhand.png)

   >[!NOTE]
   >
   >
   >기존 방식으로 사용자 지정 DKIM 서명을 설정하면 계속 사용할 수 있으며 여기에 표시됩니다.

1. 이메일 ****, DKIM **탭** , 마지막으로 도메인 **추가를**&#x200B;클릭합니다.

   ![](assets/image2014-9-18-15-3a39-3a30.png)

1. 마케팅 이메일에 사용할 도메인을 보낸 사람 주소로 입력하고 **추가를 클릭합니다**.

   >[!TIP]
   >
   >
   >보낸 사람 주소에 다른 도메인을 사용하는 경우 Marketing To 공유 DKIM 서명을 사용합니다.

   ![](assets/image2014-9-18-15-3a40-3a28.png)

1. 호스트 **레코드** 및 **TXT 값** 을 IT로 전송합니다. 사용자를 위해 레코드를 만들고 보낸 사람과 연관된 모든 이름 서버에 전파되도록 요청합니다. Marketing의 DKIM 확인을 사용하려면 DKIM 키가 DKIM이 서명된 도메인과 연결된 모든 이름 서버로 전파되어야 합니다.

   ![](assets/image2014-9-18-15-3a40-3a44.png)

1. 레코드를 만들었는지 확인한 후 Marketing To로 돌아와 도메인을 선택한 다음 **DNS 확인을 클릭합니다**.

   ![](assets/check.png)

   >[!NOTE]
   >
   >**미리 알림**
   >
   >확인이 실패하고 IT 팀에서 레코드를 올바르게 생성한 경우 DNS 전달의 문제일 수 있습니다. 나중에 다시 시도하십시오.

   >[!CAUTION]
   >
   >
   >해당 DNS 레코드를 수정/제거하면 수신 기능이 손상될 수 있습니다. DNS를 변경하기 전에 Marketing에서 항목을 삭제해야 합니다.

   이메일 전달 시 도움이 됩니다. 기록이 있고 정확하다는 확인을 받아야 한다.

