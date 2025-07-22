---
unique-page-id: 1147340
description: 리드 소유자로부터 이메일 보내기 - Marketo 문서 - 제품 설명서
title: 잠재 고객 소유자로부터 이메일 보내기
exl-id: b7ceb976-f52f-4134-8b7e-1c18d09af5de
feature: Email Editor
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# 잠재 고객 소유자로부터 이메일 보내기 {#send-emails-from-the-lead-owner}

잠재 고객 소유자를 대신하여 잠재 고객에게 이메일을 보내려면 어떻게 해야 합니까?  방법은 다음과 같습니다.

1. 전자 메일을 찾아 선택하고 **[!UICONTROL Edit Draft]**&#x200B;을(를) 클릭합니다.

   ![](assets/one.png)

1. **[!UICONTROL From]** 필드(기존 이름 삭제)를 클릭하고 **토큰 삽입** 단추를 클릭합니다.

   ![](assets/two.png)

1. &quot;`{{lead.Lead Owner`&quot;을(를) 입력하고 **`{{lead.Lead Owner First Name}}`** 토큰을 선택하십시오.

   ![](assets/image2014-9-11-13-3a7-3a43.png)

1. 잠재 고객에 아직 잠재 고객 소유자가 없는 경우 기본값을 입력하고 **[!UICONTROL Insert]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-11-13-3a7-3a58.png)

1. 첫 번째 토큰 뒤에 클릭하여 공백을 추가한 다음 **토큰 삽입** 단추를 클릭합니다.

   ![](assets/five.png)

1. &quot;`{{lead.Lead Owner`&quot;을(를) 입력하고 **`{{lead.Lead Owner Last Name}}`** 토큰을 선택하십시오.

   ![](assets/image2014-9-11-13-3a8-3a24.png)

1. 잠재 고객에 아직 잠재 고객 소유자가 없는 경우 기본값을 입력하고 **[!UICONTROL Insert]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-11-13-3a8-3a39.png)

   >[!TIP]
   >
   >이름과 성 토큰 사이에 공백을 추가해야 합니다.

1. **[!UICONTROL From Address]** 필드(기존 전자 메일 주소 삭제)를 클릭하고 **토큰 삽입** 단추를 클릭합니다.

   ![](assets/eight.png)

1. &quot;`{{lead.Lead Owner`&quot;을(를) 입력하고 **`{{lead.Lead Owner Email Address}}`** 토큰을 선택하십시오.

   ![](assets/image2014-9-11-13-3a9-3a33.png)

1. 잠재 고객에 아직 잠재 고객 소유자가 없는 경우 기본값을 입력하고 **[!UICONTROL Insert]**&#x200B;을(를) 클릭합니다.

   ![](assets/ten.png)

1. **[!UICONTROL Reply-to]** 및 **[!UICONTROL Subject]** 필드가 채워져 있는지 확인하세요!

   ![](assets/eleven.png)
