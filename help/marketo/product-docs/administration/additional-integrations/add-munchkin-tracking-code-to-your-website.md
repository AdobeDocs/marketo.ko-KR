---
unique-page-id: 2360354
description: 웹 사이트에 Munchkin 추적 코드 추가 - Marketing Docs - 제품 설명서
title: 웹 사이트에 문킨 추적 코드 추가
translation-type: tm+mt
source-git-commit: 44ed91b485b52173922c709de63a4353e16c5072
workflow-type: tm+mt
source-wordcount: '673'
ht-degree: 0%

---


# 웹 사이트에 문킨 추적 코드 추가 {#add-munchkin-tracking-code-to-your-website}

Munchkin이라고 하는 Marketing의 사용자 지정 JavaScript 추적 코드는 자동화된 마케팅 캠페인을 통해 방문자의 방문에 대응할 수 있도록 웹 사이트를 방문하는 모든 사람을 추적합니다. 익명의 방문자도 IP 주소 및 기타 정보와 함께 추적됩니다. ** 이 추적 코드가 없으면 웹 사이트에서 방문 또는 기타 활동을 추적할 수 없습니다.**

>[!NOTE]
>
>**사전 요구 사항**
>
>숙련된 JavaScript 개발자에 대한 액세스 권한이 있는지 확인하십시오. 사용자 지정 JavaScript 문제 해결을 지원하기 위해 Marketing To 기술 지원이 설정되지 않았습니다.

## 웹 사이트에 추적 코드 추가 {#add-tracking-code-to-your-website}

>[!NOTE]
>
>또한 Adobe Experience Cloud 고객은 Adobe Launch에서 Marketing의 통합을 사용하여 웹 페이지에 Munchkin 스크립트를 포함할 수 있습니다. 앱을 [여기로 다운로드하십시오](https://www.adobeexchange.com/experiencecloud.details.101054.html).

1. 관리자로 **이동한** 다음 **왼쪽** 트리에서 문킨 을 클릭합니다.

   ![](assets/image2015-8-25-16-3a21-3a14.png)

   추적 코드 유형에 대해 비동기식을 선택합니다.

   ![](assets/image2015-8-25-16-3a24-3a33.png)

   >[!NOTE]
   >
   >거의 모든 경우 비동기 코드를 사용해야 합니다. [자세한 내용](#types-of-munchkin-tracking-codes)

   웹 사이트에 게시할 Javascript 추적 코드를 클릭하고 복사합니다.

   ![](assets/image2015-8-25-16-3a26-3a12.png)

   >[!CAUTION]
   >
   >이 스크린샷에 표시된 코드는 사용하지 마십시오. 계정에 나타나는 고유한 코드를 사용해야 합니다.

   >[!TIP]
   >
   >추적할 웹 페이지에 추적 코드를 삽입합니다. 작은 사이트의 모든 페이지이거나 동적으로 생성된 웹 페이지, 사용자 포럼 등이 많은 사이트의 주요 페이지일 수 있습니다.

   최상의 결과를 얻으려면 비동기 문킨 코드를 사용하여 페이지의 `<head>` 요소 안에 배치합니다. 단순 코드를 사용하는 경우(권장되지 않음) 태그 바로 앞에 `</body>` 있습니다.
   ![](assets/image2015-8-25-16-3a5-3a20.png)

>[!TIP]
>
>트래픽이 많은 사이트(예: 매월 수십만 회 방문)의 경우 익명 사용자를 추적하지 않도록 선택하는 것이 좋습니다. [자세한 내용](http://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/)

## 여러 작업 영역을 사용할 때 추적 코드 추가 {#add-tracking-code-when-using-multiple-workspaces}

Marketing To 계정에서 작업 영역을 사용하는 경우 작업 영역에 해당하는 별도의 웹 프레젠테이션도 있을 수 있습니다. 이 경우 Munchkin 추적 Javascript를 사용하여 익명 사용자를 올바른 작업 공간과 파티션에 할당할 수 있습니다.

1. 관리자로 이동하고 왼쪽에 있는 트리에서 문킨을 클릭합니다.

![](assets/image2015-8-25-16-3a28-3a41.png)

1. 추적할 웹 페이지에 적합한 작업 영역을 선택합니다.

![](assets/image2015-8-25-16-3a30-3a32.png)

>[!NOTE]
>
>특수 작업 공간 Munchkin 코드를 사용하지 않으면 계정이 설정되었을 때 생성된 기본 파티션에 사람들이 할당됩니다. 초기에는 &quot;기본값&quot;으로 이름이 지정되었지만 자체 Marketing 계정에서 변경했을 수 있습니다.

1. 추적 코드 유형에 대해 비동기식을 선택합니다.

   ![](assets/image2015-8-25-16-3a32-3a42.png)

1. JavaScript 추적 코드를 클릭하고 복사하여 웹 사이트에 넣습니다.

![](assets/image2015-8-25-16-3a34-3a7.png)

>[!CAUTION]
>
>이 스크린샷에 표시된 코드는 사용하지 마십시오. 계정에 나타나는 고유한 코드를 사용해야 합니다.

1. 웹 페이지에 추적 코드를 요소에 `<head>` 배치합니다. 이 페이지를 방문하는 새 사용자가 이 파티션에 할당됩니다.

![](assets/image2015-8-25-16-3a5-3a20.png)

>[!CAUTION]
>
>한 페이지의 단일 분할 영역 및 작업 영역에 대해 하나의 문킨 추적 스크립트만 사용할 수 있습니다. 웹 사이트에 여러 파티션/작업 영역에 대한 추적 스크립트를 포함하지 마십시오.

>[!NOTE]
>
>Marketing To에서 만든 랜딩 페이지에는 추적 코드가 자동으로 포함되어 있으므로 이 코드를 여기에 넣을 필요가 없습니다.

## 문킨 추적 코드 유형 {#types-of-munchkin-tracking-codes}

선택할 수 있는 3가지 유형의 Munchkin 추적 코드가 있습니다. 웹 페이지 로드 시간이 다르게 영향을 미칩니다.

1. **단순**:에는 코드 줄이 거의 없지만 웹 페이지 로드 시간에 맞게 최적화되지는 않습니다. 이 코드는 웹 페이지가 로드될 때마다 jQuery 라이브러리를 로드합니다.
1. **비동기**:웹 페이지 로드 시간 단축
1. **비동기 jQuery**:웹 페이지 로드 시간을 줄이고 시스템 성능을 향상시킵니다. 이 코드에서는 이미 jQuery가 있다고 가정하고, 로드하기 위해 확인하지 않습니다.

## 문킨 코드가 작동하는지 테스트 {#test-if-your-munchkin-code-is-working}

Munchkin 코드가 추가된 후 작동하는지 확인하려면:

1. 웹 페이지를 참조하십시오.
1. Analytics로 **이동합니다**.

   ![](assets/mainnav-analytics-hand.png)

1. 웹 **페이지 활동을 클릭합니다**.

   ![](assets/webanalytics.png)

1. [ **설정** ] 탭을 클릭하고 **활동 소스**&#x200B;를 두 번 클릭한 다음 **익명 방문자(ISP 포함)로 변경합니다**.

   ![](assets/analytics-activity-source.png)

   ![](assets/activitysource.png)

1. 보고서 **탭을** 클릭합니다. 데이터가 표시되지 않으면 몇 분 정도 기다린 다음 맨 아래에 있는 새로 고침 아이콘을 클릭합니다.

