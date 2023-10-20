---
unique-page-id: 2360219
description: 사용자 지정 DKIM 서명 설정 - Marketo 문서 - 제품 설명서
title: 사용자 지정 DKIM 서명 설정
exl-id: a7c6429e-14ee-439e-9f47-1b25b98d41e7
feature: Deliverability
source-git-commit: aed161086948aa2cec0199771ba5b3b1491600f9
workflow-type: tm+mt
source-wordcount: '345'
ht-degree: 0%

---

# 사용자 지정 DKIM 서명 설정 {#set-up-a-custom-dkim-signature}

최고의 전달 가능성을 보장하기 위해 공유 Marketo DKIM 서명을 사용하여 모든 아웃바운드 메일에 자동으로 서명합니다.

>[!NOTE]
>
>이 문서의 일부 단계를 완료하려면 IT 팀의 도움이 필요할 수 있습니다.

원하는 도메인을 반영하도록 DKIM 서명을 개인화할 수 있습니다. 방법은 다음과 같습니다.

1. 로 이동 **관리자** 섹션.

   ![](assets/set-up-a-custom-dkim-signature-1.png)

   >[!NOTE]
   >
   >이전 방식으로 사용자 정의 DKIM 서명을 설정하면 계속 작동하며 여기에 표시됩니다.

1. 클릭 **이메일**.

   ![](assets/set-up-a-custom-dkim-signature-2.png)

1. 다음을 클릭합니다. **SPF/DKIM** 탭을 선택한 다음 **도메인 추가**.

   ![](assets/set-up-a-custom-dkim-signature-3.png)

1. Marketo 이메일에서 사용할 도메인을 보낸 사람 주소로 입력합니다. 선택기 및 키 크기를 선택합니다. 클릭 **추가** 완료 시.

   ![](assets/set-up-a-custom-dkim-signature-4.png)

   >[!TIP]
   >
   >* 2048의 키 크기를 권장합니다.
   >* 보낸 사람 주소에서 다른 도메인을 사용하는 경우 Marketo 공유 DKIM 서명을 사용합니다.

   <table> 
   <tr>
   <td width="20%"><b>선택기</b></td>
   <td>DKIM 레코드의 공개 키 부분을 찾는 데 사용되는 고유한 문자열/식별자입니다. DKIM 키/레코드의 목적을 구분하여 식별하는 임의의 문자열이거나 고유 식별자일 수 있습니다.</td>
   </tr>
   <tr> 
   <td width="20%"><b>키 크기</b></td>
   <td>DKIM 서명을 암호화할 보안 수준입니다.</td>
   </tr>
   </tbody>
   </table>

1. 보내기 **호스트 레코드** 및 **TXT 값** IT에 레코드를 만들도록 요청하고 이 레코드가 from 도메인과 연결된 모든 이름 서버에 전파되는지 확인하십시오. Marketo의 DKIM 확인을 사용하려면 DKIM 키가 DKIM 서명되는 도메인과 연결된 모든 이름 서버에 전파되어야 합니다.

   ![](assets/set-up-a-custom-dkim-signature-5.png)

1. 레코드가 생성되었음을 확인하면 Marketo으로 돌아와 도메인을 선택하고 을(를) 클릭합니다. **DNS 확인**.

   ![](assets/set-up-a-custom-dkim-signature-6.png)

   >[!NOTE]
   >
   >확인에 실패하고 IT에서 레코드를 올바르게 생성한 경우 DNS 전파의 문제일 수 있습니다. 나중에 다시 시도하십시오.

   >[!CAUTION]
   >
   >해당 DNS 레코드를 수정/제거하면 전달성이 손상됩니다. DNS를 변경하기 전에 Marketo에서 항목을 삭제해야 합니다.

   이는 이메일 전달성에 절대적으로 도움이 됩니다. 레코드가 그곳에 있고 정확하다는 확인을 받아야 합니다.
