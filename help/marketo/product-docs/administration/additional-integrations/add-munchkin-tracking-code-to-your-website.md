---
unique-page-id: 2360354
description: 웹 사이트에 Munchkin 추적 코드 추가 - Marketo 문서 - 제품 설명서
title: 웹 사이트에 Munchkin 추적 코드 추가
exl-id: a03a7f11-8d5e-4325-b975-8fc350711da0
source-git-commit: dbb7478ac7b7e811bb9dfeb7c5e4a80ae400ab9b
workflow-type: tm+mt
source-wordcount: '672'
ht-degree: 0%

---

# 웹 사이트에 Munchkin 추적 코드 추가 {#add-munchkin-tracking-code-to-your-website}

Marketo의 사용자 지정 JavaScript 추적 코드(Munchkin)는 웹 사이트를 방문하는 모든 개인을 추적하므로 자동화된 마케팅 캠페인을 사용하여 방문에 대응할 수 있습니다. 익명의 방문자도 IP 주소 및 기타 정보와 함께 추적됩니다. **이 추적 코드가 없으면 웹 사이트에서 방문 또는 다른 활동을 추적할 수 없습니다**!

>[!PREREQUISITES]
>
>숙련된 JavaScript 개발자에게 액세스 권한이 있는지 확인하십시오. Marketo 기술 지원이 사용자 지정 JavaScript 문제 해결을 지원하기 위해 설정되어 있지 않습니다.

## 웹 사이트에 추적 코드 추가 {#add-tracking-code-to-your-website}

>[!NOTE]
>
>Adobe Experience Cloud 고객은 Adobe Launch에서 Marketo의 통합을 사용하여 웹 페이지에 Munchkin 스크립트를 포함할 수도 있습니다. 앱 가져오기 [여기](https://www.adobeexchange.com/experiencecloud.details.101054.html).

1. 로 이동합니다. **관리** 영역.

   ![](assets/add-munchkin-tracking-code-to-your-website-1.png)

1. 클릭 **Munchkin**.

   ![](assets/add-munchkin-tracking-code-to-your-website-2.png)

1. 추적 코드 유형에 대해 비동기식을 선택합니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-3.png)

   >[!NOTE]
   >
   >거의 모든 경우 비동기 코드를 사용해야 합니다. [자세히 알아보기](#types-of-munchkin-tracking-codes).

1. 을(를) 클릭하고 Javascript 추적 코드를 복사하여 웹 사이트에 붙여넣습니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-4.png)

   >[!CAUTION]
   >
   >이 스크린샷에 표시된 코드를 사용하지 마십시오. 계정에 나타나는 고유한 코드를 사용해야 합니다.

   >[!TIP]
   >
   >추적할 웹 페이지에 추적 코드를 넣습니다. 이 페이지는 작은 사이트의 모든 페이지나 동적으로 생성된 웹 페이지, 사용자 포럼 등이 많은 사이트의 주요 페이지일 수 있습니다.

   최상의 결과를 얻으려면 비동기 Munchkin 코드를 사용하고 `<head>` 페이지의 요소. 간단한 코드(권장되지 않음)를 사용하는 경우 바로 앞에 있습니다. `</body>` 태그에 가깝게 포함했습니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-5.png)

   >[!TIP]
   >
   >트래픽이 많은 사이트(즉, 한 달에 수백 만 명이 방문)의 경우 익명의 사용자를 추적하지 않도록 선택하는 것이 좋습니다. [자세히 알아보기](https://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/).

## 여러 작업 공간을 사용할 때 추적 코드 추가 {#add-tracking-code-when-using-multiple-workspaces}

Marketo 계정에서 작업 공간을 사용하는 경우 작업 공간에 해당하는 별도의 웹 기준도 있을 수 있습니다. 이러한 경우 Munchkin 추적 Javascript를 사용하여 익명의 사용자를 올바른 작업 공간 및 파티션에 할당할 수 있습니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/add-munchkin-tracking-code-to-your-website-6.png)

1. 클릭 **Munchkin**.

   ![](assets/add-munchkin-tracking-code-to-your-website-7.png)

1. 추적할 웹 페이지에 대한 적절한 작업 공간을 선택합니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-8.png)

   >[!NOTE]
   >
   >특수 workspace Munchkin 코드를 사용하지 않는 경우 계정을 설정할 때 생성된 기본 파티션에 사람이 할당됩니다. 처음에는 &quot;기본값&quot;이라고 하지만 고유한 Marketo 계정에서 변경한 것일 수 있습니다.

1. 선택 **비동기** 추적 코드 유형에 사용할 수 있습니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-9.png)

1. 을(를) 클릭하고 JavaScript 추적 코드를 복사하여 웹 사이트에 붙여넣습니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-10.png)

   >[!CAUTION]
   >
   >이 스크린샷에 표시된 코드를 사용하지 마십시오. 계정에 나타나는 고유한 코드를 사용해야 합니다.

1. 웹 페이지에 추적 코드를 페이지의 `<head>` 요소를 생성하지 않습니다. 이 페이지를 방문하는 새 사용자가 이 파티션에 할당됩니다.

   ![](assets/add-munchkin-tracking-code-to-your-website-11.png)

   >[!CAUTION]
   >
   >한 페이지의 단일 파티션 및 작업 공간에 대해 하나의 Munchkin 추적 스크립트만 사용할 수 있습니다. 웹 사이트에 여러 파티션/작업 공간에 대한 추적 스크립트를 포함하지 마십시오.

   >[!NOTE]
   >
   >Marketo에서 만든 랜딩 페이지에는 추적 코드가 자동으로 포함되어 있으므로 이 코드를 여기에 넣을 필요가 없습니다.

## Munchkin 추적 코드 유형 {#types-of-munchkin-tracking-codes}

선택할 수 있는 Munchkin 추적 코드에는 세 가지 유형이 있습니다. 각 영향은 웹 페이지 로드 시간을 다르게 합니다.

1. **단순**: 에는 코드 줄이 거의 없지만 웹 페이지 로드 시간은 최적화되지 않습니다. 이 코드는 웹 페이지가 로드될 때마다 jQuery 라이브러리를 로드합니다.
1. **비동기**: 웹 페이지 로드 시간을 줄입니다.
1. **비동기 jQuery**: 웹 페이지 로드 시간을 줄이고 시스템 성능을 향상시킵니다. 이 코드에서는 이미 jQuery가 있다고 가정하고 jQuery를 로드할지 확인하지 않습니다.

## Munchkin 코드가 작동하는지 테스트합니다 {#test-if-your-munchkin-code-is-working}

추가한 후 Munchkin 코드가 작동하는지 확인하려면:

1. 웹 페이지를 방문합니다.

1. 내 Marketo에서 **Analytics** 타일.

   ![](assets/add-munchkin-tracking-code-to-your-website-12.png)

1. 클릭 **웹 페이지 활동**.

   ![](assets/add-munchkin-tracking-code-to-your-website-13.png)

1. 을(를) 클릭합니다. **설정** 탭에서 두 번 클릭합니다 **활동 소스**.

   ![](assets/add-munchkin-tracking-code-to-your-website-14.png)

1. 활동 소스를 **익명 방문자(ISP 포함)** 을(를) 클릭합니다. **적용**.

   ![](assets/add-munchkin-tracking-code-to-your-website-15.png)

1. 을(를) 클릭합니다. **보고서** 탭.

   ![](assets/add-munchkin-tracking-code-to-your-website-16.png)

   >[!NOTE]
   >
   >데이터가 표시되지 않는 경우 몇 분 정도 기다린 다음 맨 아래에 있는 새로 고침 아이콘을 클릭합니다.
