---
unique-page-id: 1900589
description: 텍스트 이메일에 추적된 링크 추가 - Marketo 문서 - 제품 설명서
title: 텍스트 이메일에 추적된 링크 추가
exl-id: 10b4e029-de23-4054-83f7-b68fea68c838
feature: Email Editor
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '162'
ht-degree: 0%

---

# 텍스트 이메일에 추적된 링크 추가 {#add-tracked-links-to-a-text-email}

>[!PREREQUISITES]
>
>* [텍스트 전용 전자 메일 만들기](/help/marketo/product-docs/email-marketing/general/creating-an-email/create-a-text-only-email.md)
>* [전자 메일의 요소 편집](/help/marketo/product-docs/email-marketing/general/email-editor-2/edit-elements-in-an-email.md)

텍스트 이메일 링크는 Marketo에서 추적할 수 있습니다. 어떻게 작동하는지 알아보겠습니다.

1. 이메일을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

1. 전자 메일을 선택하고 **[!UICONTROL Edit Draft]**&#x200B;을(를) 클릭합니다.

   ![](assets/one-9.png)

1. 링크를 추가할 편집 가능 영역을 두 번 클릭합니다.

   ![](assets/two-8.png)

1. `[[www.domain.com/path/page.html]]`과(와) 같이 이중 대괄호로 URL을 입력하십시오.

   ![](assets/three-8.png)

   >[!CAUTION]
   >
   >365일 전 **및** 지난 180일 동안 아무도 링크를 클릭하지 않은 전자 메일이 전송된 경우, Marketo Engage이 데이터베이스에서 URL로 가는 경로를 잘라냅니다. 이렇게 되면 링크가 끊어집니다. 링크를 영구적으로 유지해야 하는 경우 추적을 사용하지 마십시오.

1. 편집기를 닫고 초안 승인 잊지 마십시오.

   ![](assets/four-6.png)

>[!NOTE]
>
>mktNoTok 클래스 기능은 텍스트 이메일의 추적 가능한 링크에서 작동하지 않습니다. HTML 이메일에만 해당됩니다.
