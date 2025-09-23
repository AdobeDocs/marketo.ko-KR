---
unique-page-id: 2360219
description: 사용자 지정 DKIM 서명 설정 - Marketo 문서 - 제품 설명서
title: 사용자 정의 DKIM 서명 설정
exl-id: a7c6429e-14ee-439e-9f47-1b25b98d41e7
feature: Deliverability
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 4%

---

# 사용자 정의 DKIM 서명 설정 {#set-up-a-custom-dkim-signature}

최고의 전달 가능성을 보장하기 위해 공유 Marketo DKIM 서명을 사용하여 모든 아웃바운드 메일에 자동으로 서명합니다.

>[!NOTE]
>
>이 문서의 일부 단계를 완료하려면 IT 팀의 도움이 필요할 수 있습니다.

원하는 도메인을 반영하도록 DKIM 서명을 개인화할 수 있습니다. 방법은 다음과 같습니다.

1. **[!UICONTROL Admin]** 섹션으로 이동합니다.

   ![](assets/set-up-a-custom-dkim-signature-1.png)

   >[!NOTE]
   >
   >이전 방식으로 사용자 지정 DKIM 서명을 설정하는 경우 계속 작동하며 여기에 표시됩니다.

1. **전자 메일**&#x200B;을 클릭하세요.

   ![](assets/set-up-a-custom-dkim-signature-2.png)

1. **SPF/DKIM** 탭을 클릭한 다음 **도메인 추가**&#x200B;를 클릭합니다.

   ![](assets/set-up-a-custom-dkim-signature-3.png)

1. Marketo 이메일에서 사용할 도메인을 보낸 사람 주소로 입력합니다. 선택기 및 키 크기를 선택합니다. 완료되면 **추가**&#x200B;를 클릭하세요.

   ![](assets/set-up-a-custom-dkim-signature-4.png)

   <table>
   <tr>
   <td width="20%"><b>선택기</b></td>
   <td>DKIM 레코드의 공개 키 부분을 찾는 데 사용되는 고유한 문자열/식별자입니다. 임의의 문자열이거나, 고유한 식별자일 수 있으며, 이를 통해 해당 DKIM 키/레코드의 목적을 구분하여 식별할 수 있습니다.</td>
   </tr>
   <tr>
   <td width="20%"><b>키 크기</b></td>
   <td>DKIM 서명을 암호화할 보안 수준입니다.</td>
   </tr>
   </tbody>
   </table>

   <p>

   >[!TIP]
   >
   >* 2048의 키 크기를 권장합니다.
   >* 보낸 사람 주소에서 다른 도메인을 사용하는 경우 Marketo 공유 DKIM 서명을 사용합니다.

   >[!IMPORTANT]
   >
   >도메인의 DKIM 선택기 또는 DKIM 암호화 크기 를 업데이트해야 하는 경우 기존 레코드를 삭제하고 새로 생성된 레코드를 새 값으로 다시 게시해야 합니다.
   >
   >이 경우 새 레코드가 게시되고 시스템에 의해 확인될 때까지 DKIM에 도메인에 대한 서명이 없습니다. 새로운 DKIM 레코드가 인터넷에 완전히 전파되기까지 24~48시간이 걸릴 수 있으므로 변경 사항을 계획하십시오.

1. IT에 **[!UICONTROL Host Record]** 및 **[!UICONTROL TXT Value]**&#x200B;을(를) 보냅니다. 레코드를 만들도록 요청하고 이 레코드가 from 도메인과 연결된 모든 이름 서버에 전파되는지 확인하십시오. Marketo의 DKIM 확인을 사용하려면 DKIM 키가 DKIM에 서명된 도메인과 연결된 모든 이름 서버에 전파되어야 합니다.

   ![](assets/set-up-a-custom-dkim-signature-5.png)

1. 레코드를 만들었음을 확인한 후 Marketo으로 돌아와 도메인을 선택하고 **[!UICONTROL Check DNS]**&#x200B;을(를) 클릭합니다.

   ![](assets/set-up-a-custom-dkim-signature-6.png)

   >[!NOTE]
   >
   >확인에 실패하고 IT에서 레코드를 올바르게 생성한 경우 DNS 전파의 문제일 수 있습니다. 나중에 다시 시도하십시오.

   >[!CAUTION]
   >
   >해당 DNS 레코드를 수정/제거하면 전달성이 손상됩니다. DNS를 변경하기 전에 Marketo에서 항목을 삭제해야 합니다.

   이는 이메일 전달성에 절대적으로 도움이 됩니다. 레코드가 그곳에 있고 정확하다는 확인을 받아야 합니다.
