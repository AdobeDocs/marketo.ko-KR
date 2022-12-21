---
unique-page-id: 2360219
description: 사용자 지정 DKIM 서명 설정 - Marketo 문서 - 제품 설명서
title: 사용자 지정 DKIM 서명 설정
exl-id: a7c6429e-14ee-439e-9f47-1b25b98d41e7
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 1%

---

# 사용자 지정 DKIM 서명 설정 {#set-up-a-custom-dkim-signature}

최고의 배달 가능성을 보장하기 위해 공유 Marketo DKIM 서명을 사용하여 모든 아웃바운드 메일에 자동으로 서명합니다.

>[!NOTE]
>
>이 문서의 절차 중 일부를 완료하려면 IT 팀의 도움이 필요할 수 있습니다.

원하는 도메인을 반영하도록 DKIM 서명을 개인화할 수 있습니다. 방법은 다음과 같습니다.

1. 로 이동합니다. **관리** 섹션을 참조하십시오.

   ![](assets/adminhand.png)

   >[!NOTE]
   >
   >기존의 방식으로 사용자 지정 DKIM 서명을 설정하면 계속 작동하며 여기에 표시됩니다.

1. 클릭 **이메일**, 그런 다음 **DKIM** 탭하고 마지막으로 **도메인 추가**.

   ![](assets/image2014-9-18-15-3a39-3a30.png)

1. Marketo 이메일에 사용할 도메인을 보낸 사람 주소로 입력하고 을 클릭합니다 **추가**.

   >[!TIP]
   >
   >보낸 사람 주소에서 다른 도메인을 사용하는 경우 Adobe에서는 Marketo 공유 DKIM 서명을 사용합니다.

   ![](assets/image2014-9-18-15-3a40-3a28.png)

1. 보내기 **호스트 레코드** 및 **TXT 값** IT에 연결 레코드를 만들어 from 도메인과 연관된 모든 이름 서버로 전달되도록 합니다. Marketo의 DKIM 확인을 사용하려면 DKIM 키가 DKIM 서명 도메인과 연결된 모든 이름 서버에 전파되어야 합니다.

   ![](assets/image2014-9-18-15-3a40-3a44.png)

1. 레코드가 만들어졌는지 확인했으면 Marketo으로 돌아가서 도메인을 선택하고 을 클릭합니다 **DNS 확인**.

   ![](assets/check.png)

   >[!NOTE]
   >
   >확인이 실패하고 IT에서 레코드를 올바르게 생성한 경우, DNS 전달의 문제일 수 있습니다. 나중에 다시 시도하십시오.

   >[!CAUTION]
   >
   >해당 DNS 레코드를 수정/제거하면 게재 기능이 손상될 수 있습니다. DNS를 변경하기 전에 Marketo에서 항목을 삭제해야 합니다.

   이 기능은 이메일 게재 기능에 절대적으로 도움이 됩니다. 레코드가 있는지 확인하고 정확한지 확인해야 합니다.
