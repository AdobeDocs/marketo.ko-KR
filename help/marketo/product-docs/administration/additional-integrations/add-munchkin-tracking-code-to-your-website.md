---
unique-page-id: 2360354
description: "추가 [!DNL Munchkin] 웹 사이트에 대한 추적 코드 - Marketo 문서 - 제품 설명서"
title: "추가 [!DNL Munchkin] 웹 사이트에 대한 추적 코드"
exl-id: a03a7f11-8d5e-4325-b975-8fc350711da0
feature: Administration, Munchkin Tracking Code
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '666'
ht-degree: 0%

---

# 추가 [!DNL Munchkin] 웹 사이트에 대한 추적 코드 {#add-munchkin-tracking-code-to-your-website}

호출된 Marketo 사용자 지정 JavaScript 추적 코드 [!DNL Munchkin]는 자동화된 마케팅 캠페인으로 방문에 대응할 수 있도록 웹 사이트를 방문하는 모든 개인을 추적합니다. 익명 방문자도 IP 주소 및 기타 정보와 함께 추적됩니다. **이 추적 코드가 없으면 웹 사이트에서 방문 횟수 또는 기타 활동을 추적할 수 없습니다**!

>[!PREREQUISITES]
>
>숙련된 JavaScript 개발자에게 액세스할 수 있는지 확인하십시오. Marketo 기술 지원 은 사용자 지정 JavaScript의 문제 해결을 지원하도록 설정되지 않았습니다.

## 웹 사이트에 추적 코드 추가 {#add-tracking-code-to-your-website}

>[!NOTE]
>
>Adobe Experience Cloud 사용자는 [Adobe Launch의 Marketo 통합](https://exchange.adobe.com/apps/ec/100223/adobe-launch-core-extension){target="_blank"} 포함할 항목 [!DNL Munchkin] 스크립트를 웹 페이지에 추가합니다. Adobe 실행을 사용하는 경우, _다음 [!DNL Munchkin] 스크립트가 자동으로 추가됩니다_&#x200B;따라서 직접 추가할 필요가 없습니다.

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-1.png)

1. 클릭 **[!UICONTROL 먼치킨]**.

   ![](assets/add-munchkin-tracking-code-to-your-website-2.png)

1. 선택 **[!UICONTROL 비동기]** 대상 **[!UICONTROL 추적 코드 유형]**.

   ![](assets/add-munchkin-tracking-code-to-your-website-3.png)

   >[!NOTE]
   >
   >거의 모든 경우에 비동기 코드를 사용해야 합니다. [자세히 알아보기](#types-of-munchkin-tracking-codes).

1. 을(를) 클릭하고 Javascript 추적 코드를 복사하여 웹 사이트에 넣습니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-4.png)

   >[!CAUTION]
   >
   >이 스크린샷에 표시된 코드를 사용하지 마십시오. 계정에 표시되는 고유 코드를 사용해야 합니다!

   >[!TIP]
   >
   >추적할 웹 페이지에 추적 코드를 넣습니다. 소규모 사이트의 모든 페이지이거나 웹 페이지, 사용자 포럼 등이 동적으로 많이 생성된 사이트의 주요 페이지일 수 있습니다.

   최상의 결과를 얻으려면 비동기식 을 사용하십시오. [!DNL Munchkin] 코드를 만든 다음 내부에 넣습니다. `<head>` 페이지의 요소입니다. 단순 코드(권장되지 않음)를 사용하는 경우 `</body>` 태그에 가깝게 배치하십시오.

   ![](assets/add-munchkin-tracking-code-to-your-website-5.png)

   >[!TIP]
   >
   >많은 양의 트래픽(즉, 매월 수십만 건의 방문)이 표시되는 사이트의 경우 익명의 사용자를 추적하지 않도록 선택하는 것이 좋습니다. [자세히 알아보기](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/lead-tracking/){target="_blank"}.

## 여러 작업 공간을 사용할 때 추적 코드 추가 {#add-tracking-code-when-using-multiple-workspaces}

Marketo 계정에서 Workspaces를 사용하는 경우 작업 공간에 해당하는 별도의 웹 존재도 있을 수 있습니다. 이 경우 [!DNL Munchkin] javascript를 추적하여 익명 사용자를 올바른 작업 영역 및 파티션에 할당합니다.

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-6.png)

1. 클릭 **[!UICONTROL 먼치킨]**.

   ![](assets/add-munchkin-tracking-code-to-your-website-7.png)

1. 추적할 웹 페이지에 적합한 작업 영역을 선택합니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-8.png)

   >[!NOTE]
   >
   >특수 작업 영역을 사용하지 않는 경우 [!DNL Munchkin] 코드를 실행하면 계정이 설정될 때 생성된 기본 파티션에 사용자가 할당됩니다. 이름이 &quot;[!UICONTROL 기본값]처음에는 그랬지만 Marketo 계정에서 변경했을 수 있습니다.

1. 선택 **[!UICONTROL 비동기]** 대상 **[!UICONTROL 추적 코드 유형]**.

   ![](assets/add-munchkin-tracking-code-to-your-website-9.png)

1. 을(를) 클릭하고 JavaScript 추적 코드를 복사하여 웹 사이트에 넣습니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-10.png)

   >[!CAUTION]
   >
   >이 스크린샷에 표시된 코드를 사용하지 마십시오. 계정에 표시되는 고유 코드를 사용해야 합니다!

1. 웹 페이지에 추적 코드를 `<head>` 요소를 생성하지 않습니다. 이 페이지를 방문하는 새 사용자가 이 파티션에 할당됩니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-11.png)

   >[!CAUTION]
   >
   >하나만 사용할 수 있습니다. [!DNL Munchkin] 페이지의 단일 파티션 및 작업 공간에 대한 추적 스크립트. 웹 사이트의 여러 파티션/작업 공간에 대한 추적 스크립트를 포함하지 마십시오.

   >[!NOTE]
   >
   >Marketo에서 만든 랜딩 페이지에는 추적 코드가 자동으로 포함되어 있으므로 이 코드를 추가할 필요가 없습니다.

## 유형 [!DNL Munchkin] 추적 코드 {#types-of-munchkin-tracking-codes}

다음 세 가지 유형이 있습니다 [!DNL Munchkin] 선택할 수 있는 추적 코드. 각각 웹 페이지 로드 시간에 영향을 줍니다.

1. **[!UICONTROL 단순]**: 가장 적은 코드 줄이 있지만 웹 페이지 로드 시간에 최적화되지 않습니다. 이 코드는 웹 페이지가 로드될 때마다 jQuery 라이브러리를 로드합니다.
1. **[!UICONTROL 비동기]**: 웹 페이지 로드 시간을 단축합니다.
1. **[!UICONTROL 비동기 jQuery]**: 웹 페이지 로드 시간을 줄이고 시스템 성능도 향상시킵니다. 이 코드는 사용자가 이미 jQuery를 가지고 있다고 가정하고 로드를 선택하지 않습니다.

## 다음을 테스트하는 경우 [!DNL Munchkin] 코드가 작동함 {#test-if-your-munchkin-code-is-working}

다음을 확인하십시오. [!DNL Munchkin] 코드를 추가한 후 코드가 작동합니다.

1. 웹 페이지를 방문합니다.

1. 내 [!DNL My Marketo]를 클릭하고 **[!UICONTROL 분석]** 타일.

   ![](assets/add-munchkin-tracking-code-to-your-website-12.png)

1. 클릭 **[!UICONTROL 웹 페이지 활동]**.

   ![](assets/add-munchkin-tracking-code-to-your-website-13.png)

1. 다음을 클릭합니다. **[!UICONTROL 설정]** 탭, 두 번 클릭 **[!UICONTROL 활동 소스]**.

   ![](assets/add-munchkin-tracking-code-to-your-website-14.png)

1. 변경 [!UICONTROL 활동 소스] 끝 **[!UICONTROL 익명 방문자(ISP 포함)]** 및 클릭 **[!UICONTROL 적용]**.

   ![](assets/add-munchkin-tracking-code-to-your-website-15.png)

1. 다음을 클릭합니다. **[!UICONTROL 보고서]** 탭.

   ![](assets/add-munchkin-tracking-code-to-your-website-16.png)

   >[!NOTE]
   >
   >데이터가 표시되지 않으면 몇 분 정도 기다린 다음 맨 아래에 있는 새로 고침 아이콘을 클릭합니다.
