---
unique-page-id: 1900597
description: 목록 가져오기 - Marketing To Docs - 제품 설명서를 통해 대상 정의
title: 목록을 가져와서 대상 정의
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '374'
ht-degree: 0%

---


# 목록 {#define-an-audience-by-importing-a-list}을(를) 가져와 대상 정의

>[!PREREQUISITES]
>
>[이메일 프로그램용 이메일 만들기](../../../../product-docs/email-marketing/email-programs/email-program-actions/create-an-email-for-an-email-program.md)

이메일 프로그램을 만든 후에는 이메일을 보낼 사람을 알려주어야 합니다. 이 작업은 [스마트 목록](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)을 만들거나 목록을 가져와서 수행할 수 있습니다. 목록을 가져와서 이를 수행하는 방법입니다.

>[!NOTE]
>
>대상자 정의는 이메일 프로그램이 승인되지 않은 경우에만 작동합니다.
>
>가져오는 모든 날짜/시간 필드는 중부 시간으로 처리됩니다. 날짜/시간 필드가 다른 시간대에 있는 경우 Excel 공식을 사용하여 중부 시간(미국/시카고)으로 변환할 수 있습니다.

1. **마케팅 활동**&#x200B;으로 이동합니다.

   ![](assets/login-marketing-activities-1.png)

   이메일 프로그램을 선택한 다음 대상 타일 아래에 있는 목록 가져오기를 클릭합니다.
   ![](assets/importlist.png)

1. 목록 가져오기 창이 열리고 **찾아보기**&#x200B;를 클릭하고 가져올 파일을 선택합니다. 인물 목록을 선택하고 나면 다음을 클릭합니다.
1. ![](assets/importlist1.png)

   >[!CAUTION]
   >
   >목록이 UTF-8, UTF-16, Shift-JIS 또는 EUC-JP로 인코딩되어 파일 크기가 50MB를 초과하지 않아야 합니다.

   파일의 필드가 올바르게 매핑되었는지 확인하고 [다음]을 클릭합니다.
   ![](assets/image2014-9-12-11-3a10-3a7.png)

   >[!TIP]
   >
   >향후 가져오기에 대한 매핑이 기억됩니다!

1. 목록에 대해 **이름**&#x200B;을 입력하고 **가져오기**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-12-11-3a10-3a13.png)

1. 가져오기가 완료되면 기본 프로그램 탭으로 돌아갑니다. 자격 조건을 갖춘 사용자가 몇 명인지 확인할 수 있습니다.

   ![](assets/myemailprogram-1.jpg)

>[!NOTE]
>
>**정의**
>
>차단된 번호를 알고 계십니까? 이 숫자는 자격을 갖춘 사람의 하위 집합이며 다음과 같은 이유로 이 이메일을 보낼 수 없는 사람을 나타냅니다.
>
>* 구독 취소
>* 마케팅 일시 중단
>* 차단 목록에 추가된
>* 이메일 잘못됨
>* 빈 이메일

>
>
우편물로부터 차단된 사람의 세부 목록을 보려면 번호를 클릭합니다.
>
>스마트 목록 기준을 기반으로 이메일을 수신할 자격이 있는 사람 수를 보려면 **대상자** 타일의 ![—](assets/image2014-10-23-16-3a32-3a36-1.png) 단추를 사용합니다. [사람] 숫자에서 [차단된] 번호를 빼어 이메일을 받을 총 사람 수를 가져옵니다.

>[!TIP]
>
>목록 가져오기가 완료될 때까지 기다리지 않아도 됩니다. 원하신다면 작업을 계속할 수 있습니다.

환상적이야! 이제 기존 이메일을 선택하거나 새 이메일을 만들어 해당 사용자에게 보내야 합니다.

>[!NOTE]
>
>**관련 문서**
>
>* [기존 이메일 선택](../../../../product-docs/email-marketing/email-programs/email-program-actions/choose-an-existing-email.md)
>* [이메일 프로그램용 이메일 만들기](../../../../product-docs/email-marketing/email-programs/email-program-actions/create-an-email-for-an-email-program.md)

>



