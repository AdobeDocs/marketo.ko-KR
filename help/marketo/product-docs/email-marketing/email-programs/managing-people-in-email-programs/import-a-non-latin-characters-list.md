---
unique-page-id: 5472678
description: 라틴어가 아닌 문자 목록 가져오기 - Marketo 문서 - 제품 설명서
title: 라틴어가 아닌 문자 목록 가져오기
exl-id: 11519e2c-ab01-4164-8ce3-0717e4c13ae6
feature: Email Programs
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '292'
ht-degree: 0%

---

# 라틴어가 아닌 문자 목록 가져오기 {#import-a-non-latin-characters-list}

영어가 아닌 파일을 가져오려고 합니까? Excel로 목록을 열면 목록이 완벽해 보입니다.

![](assets/image2015-2-10-9-3a34-3a57.png)

하지만 Marketo으로 가져오면 영어가 아닌 문자가 올바르게 선택되지 않을 수 있습니다.

![](assets/image2015-2-10-9-3a35-3a49.png)

Marketo에서 라틴어가 아닌 모든 문자를 인식하도록 파일이 제대로 저장되지 않았기 때문입니다. 좋은 소식은, 당신이 그것을 해결하기 위해 따를 수있는 몇 가지 간단한 단계가 있다는 것입니다.

1. Excel의 **[!UICONTROL Save As]메뉴에서**..**[!UICONTROL File]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-2-10-9-3a46-3a44.png)

1. **[!UICONTROL UTF-16 Unicode Text (.txt)]**&#x200B;을(를) **[!UICONTROL Format]** 옵션으로 선택합니다. 이렇게 하면 Marketo이 파일을 표시할 수 있는 방식으로 인코딩됩니다.

   ![](assets/image2015-2-10-9-3a48-3a7.png)

   >[!NOTE]
   >
   >Marketo은 UTF-8, Shift-JIS 또는 EUC-JP도 지원합니다.

1. Excel에서는 새 파일이 확장명이 .txt인 텍스트 파일로 저장됩니다. 그러나 또한 파일의 모든 쉼표를 탭으로 변환합니다. 다시 바꿔야 합니다.

   >[!TIP]
   >
   >Windows를 사용하는 경우 **[!DNL Notepad]**&#x200B;을(를) 사용하여 텍스트 파일을 열 수 있으며, Mac을 사용하는 경우 **[!DNL TextEdit]**&#x200B;을(를) 사용하여 텍스트 파일을 열 수 있습니다.

   ![](assets/image2015-2-10-9-3a51-3a41.png)

1. 문서에서 탭을 선택하고 복사합니다.

   ![](assets/image2015-2-10-9-3a55-3a53.png)

1. **[!UICONTROL Find and Replace]메뉴에서**..**[!UICONTROL Edit]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-2-10-9-3a59-3a8.png)

   >[!TIP]
   >
   >Windows 사용자에 대한 동등한 작업은 다음과 같습니다. **[!UICONTROL Edit]> [!UICONTROL Replace]...**

1. 4단계에서 복사한 탭을 첫 번째(바꿀 내용) 상자에 붙여 넣고 두 번째(바꿀 내용) 상자에 쉼표를 입력합니다. **[!UICONTROL All]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-2-10-10-3a8-3a53.png)

1. 그리고 짜잔, 모든 쉼표가 돌아왔고 우리는 굴러갈 준비가 되었습니다.

   ![](assets/image2015-2-10-10-3a14-3a45.png)

1. 새 파일을 Marketo으로 가져오면 이번에는 정보가 올바르게 표시됩니다.

   ![](assets/image2015-2-10-10-3a16-3a9.png)

   >[!NOTE]
   >
   >가져오는 모든 날짜/시간 필드는 중앙 시간으로 처리됩니다. 다른 시간대에 날짜/시간 필드가 있는 경우 Excel 공식을 사용하여 중부 표준시(아메리카/시카고)로 변환할 수 있습니다.

우리는 이것이 이상하다는 것을 알지만, 그것은 효과가 있습니다. 해피 가져오기!
