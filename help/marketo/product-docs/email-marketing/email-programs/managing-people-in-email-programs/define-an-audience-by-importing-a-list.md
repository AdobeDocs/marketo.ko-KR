---
unique-page-id: 1900597
description: 목록을 가져와서 대상자 정의 - Marketo 문서 - 제품 설명서
title: 목록을 가져와서 대상자 정의
exl-id: 9a63f4a5-1d76-4671-9622-19eb368d196f
feature: Email Programs
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 0%

---

# 목록을 가져와서 대상자 정의 {#define-an-audience-by-importing-a-list}

>[!PREREQUISITES]
>
>[전자 메일 프로그램을 위한 전자 메일 만들기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/create-an-email-for-an-email-program.md)

전자 메일 프로그램을 만든 후에는 전자 메일을 누구에게 보낼 것인지 알려 주어야 합니다. [스마트 목록을 만들거나](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 목록을 가져와서 이 작업을 수행할 수 있습니다. 목록을 가져와서 이렇게 하는 방법은 다음과 같습니다.

>[!NOTE]
>
>대상자 정의는 이메일 프로그램이 승인되지 않은 경우에만 작동합니다.
>
>가져오는 모든 날짜/시간 필드는 중앙 시간으로 처리됩니다. 다른 시간대에 날짜/시간 필드가 있는 경우 Excel 공식을 사용하여 중부 표준시(아메리카/시카고)로 변환할 수 있습니다.

1. **[!UICONTROL Marketing Activities]**(으)로 이동합니다.

   ![](assets/login-marketing-activities-1.png)

1. 전자 메일 프로그램을 선택한 다음 **[!UICONTROL Import List]** 타일 아래의 **[!UICONTROL Audience]**&#x200B;을(를) 클릭합니다.

   ![](assets/importlist.png)

1. 목록 가져오기 창이 열리고 **[!UICONTROL Browse]**&#x200B;을(를) 클릭하고 가져올 파일을 선택합니다. 사용자 목록을 선택한 후 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/importlist1.png)

   >[!CAUTION]
   >
   >목록이 인코딩된 UTF-8, UTF-16, Shift-JIS 또는 EUC-JP이고 파일 크기가 50MB를 초과하지 않아야 합니다.

1. 파일의 필드가 올바르게 매핑되었는지 확인하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-12-11-3a10-3a7.png)

   >[!TIP]
   >
   >Marketo은 향후 가져오기에 대한 매핑을 기억합니다!

1. 목록에 대한 **[!UICONTROL Name]**&#x200B;을(를) 입력하고 **[!UICONTROL Import]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-12-11-3a10-3a13.png)

1. 가져오기가 완료되면 기본 프로그램 탭으로 돌아갑니다. 여러분은 얼마나 많은 사람들이 자격을 갖는지 볼 것입니다.

   ![](assets/myemailprogram-1.jpg)

>[!NOTE]
>
>**정의**
>
>차단된 번호를 아시나요? 이 숫자는 적격 직원의 하위 집합이며, 다음과 같은 이유로 이 이메일을 보낼 수 없는 직원을 나타냅니다.
>
>* 주소 삭제
>* 마케팅 중단
>* 차단 목록에 추가된
>* 이메일 잘못됨
>* 빈 이메일
>
>메일링이 차단된 사람들의 자세한 목록을 보려면 번호를 클릭하십시오.
>
>![ 타일의 ](assets/image2014-10-23-16-3a32-3a36-1.png)—**[!UICONTROL Audience]** 단추를 사용하여 스마트 목록 조건에 따라 전자 메일을 받을 자격이 있는 사람 수를 확인합니다. 사람 수에서 차단된 수를 빼면 이메일을 받을 총 사람 수를 가져옵니다.

>[!TIP]
>
>목록 가져오기가 완료될 때까지 기다릴 필요가 없습니다. 원한다면 계속 일해도 돼.

환상적이에요! 이제 이미 존재하는 이메일을 선택하거나 이러한 직원들에게 보낼 새 이메일을 만들 차례입니다.

>[!MORELIKETHIS]
>
>* [기존 전자 메일 선택](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/choose-an-existing-email.md)
>* [전자 메일 프로그램을 위한 전자 메일 만들기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/create-an-email-for-an-email-program.md)
