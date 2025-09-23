---
unique-page-id: 2951220
description: 모바일 플랫폼 열을 사용하여 직원 성과 보고서 작성 - Marketo 문서 - 제품 설명서
title: 모바일 플랫폼 열을 사용하여 사용자 성과 보고서 만들기
exl-id: 93fb6cb4-a6ca-4b35-b8bf-c6657eb9343b
feature: Reporting
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 8%

---

# 모바일 플랫폼 열을 사용하여 사용자 성과 보고서 만들기 {#build-a-people-performance-report-with-mobile-platform-columns}

모바일 플랫폼(iOS/Android) 열을 사용하여 사람 성과 보고서를 만들려면 다음 단계를 따르십시오.

## 모바일 스마트 목록 만들기 {#create-mobile-smart-lists}

1. **[!UICONTROL Marketing Activities]**(으)로 이동합니다.

   ![](assets/ma.png)

1. 프로그램을 선택합니다.

   ![](assets/two-1.png)

1. **[!UICONTROL New]**&#x200B;에서 **[!UICONTROL New Local Asset]**&#x200B;을(를) 선택합니다.

   ![](assets/three-1.png)

1. **[!UICONTROL Smart List]**&#x200B;를 클릭합니다.

   ![](assets/four-1.png)

1. 이름을 입력하고 **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/five-1.png)

1. [!UICONTROL Opened Email] 필터를 찾아 캔버스로 드래그합니다.

   ![](assets/six-1.png)

1. 전자 메일을 **[!UICONTROL is any]**(으)로 설정합니다.

   ![](assets/seven.png)

1. **[!UICONTROL Add Constraint]**&#x200B;을(를) 클릭하고 **[!UICONTROL Platform]**&#x200B;을(를) 선택합니다.

   ![](assets/eight.png)

   >[!TIP]
   >
   >이 예제에서는 [!UICONTROL Opened Email] 필터를 사용했습니다. 플랫폼 제약 조건이 있으므로 [!UICONTROL Clicked Email] 필터를 사용할 수도 있습니다.

1. [!UICONTROL Platform]을(를) **[!UICONTROL iOS]**(으)로 설정합니다.

   ![](assets/nine.png)

   >[!NOTE]
   >
   >Marketo의 자동 제안에서 찾을 수 있도록 하려면 적어도 한 명이 iOS 장치에서 이메일 중 하나를 열어야 합니다. 표시되지 않는 경우 수동으로 입력하고 저장할 수 있습니다.

   이제 &quot;Android&quot; 플랫폼에 대한 두 번째 스마트 목록을 만듭니다. 작업이 완료되면 다음 섹션으로 이동하십시오.

## 사람 성과 보고서 만들기 {#create-a-people-performance-report}

1. 마케팅 활동에서 **[!UICONTROL iOS]** 및 **[!UICONTROL Android]** 스마트 목록을 포함하는 프로그램을 선택합니다.

   ![](assets/ten.png)

1. **[!UICONTROL New]**&#x200B;에서 **[!UICONTROL New Local Asset]**&#x200B;을(를) 선택합니다.

   ![](assets/eleven.png)

1. **[!UICONTROL Report]**&#x200B;를 클릭합니다.

   ![](assets/twelve.png)

1. Type을 **[!UICONTROL People Performance]**(으)로 설정합니다.

   ![](assets/thirteen.png)

1. **[!UICONTROL Create]**&#x200B;를 클릭합니다.

   ![](assets/fourteen.png)

   잘하고 있어! 이제 다음 섹션으로 넘어가십시오.

## 모바일 스마트 목록을 열로 추가 {#add-mobile-smart-lists-as-columns}

1. 방금 만든 보고서에서 **[!UICONTROL Setup]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Custom Columns]**&#x200B;을(를) 캔버스로 드래그합니다.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >기본적으로 사람 성과 보고서는 지난 7일 동안 표시됩니다. 시간표를 두 번 클릭하여 변경할 수 있습니다.

1. 이전에 만든 스마트 목록을 찾아 선택하고 **[!UICONTROL Apply]**&#x200B;을(를) 클릭합니다.

   ![](assets/sixteen.png)

1. 보고서를 실행하고 데이터를 보려면 **[!UICONTROL Report]**&#x200B;을(를) 클릭하십시오.

   ![](assets/seventeen.png)

   꽤 멋지지? 잘했어!
