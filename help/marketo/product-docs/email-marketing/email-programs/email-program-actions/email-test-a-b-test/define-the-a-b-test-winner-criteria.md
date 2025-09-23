---
unique-page-id: 2359545
description: A/B 테스트 승자 기준 정의 - Marketo 문서 - 제품 설명서
title: A/B 테스트 우승자 기준 정의
exl-id: be8a0887-70f4-4667-93a6-d982a16cdfdb
feature: Email Programs, A/B Testing
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 21%

---

# A/B 테스트 우승자 기준 정의 {#define-the-a-b-test-winner-criteria}

전자 메일 프로그램에 [A/B 테스트를 추가](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md){target="_blank"}할 때 테스트 유형을 선택하고 [A/B 테스트를 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md){target="_blank"}한 다음 승자 기준을 정의해야 합니다. 우승 이메일을 결정하는 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>[A/B 테스트 추가](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md){target="_blank"}

## 우승자 기준 {#winner-criteria}

1. 기본 **[!UICONTROL Winner Criteria]** 옵션이 먼저 나열됩니다.

   ![](assets/image2014-9-12-15-3a51-3a3.png)

   <table>
   <tr>
   <td><b>[!UICONTROL Opens]</b></td>
   <td>열기는 이미지가 이메일에 다운로드되면 등록됩니다. 이미지를 포함하지 않더라도 기본적으로 Marketo은 모든 HTML 이메일에 단일 추적 픽셀을 삽입합니다.</td>
   </tr>
   <tr>
   <td><b>[!UICONTROL Clicks]</b></td>
   <td>기본적으로 이메일의 링크에는 추적 기능이 임베드되어 있어 누가 어떤 링크를 클릭했는지, 총 몇 개의 링크가 클릭되었는지 등을 볼 수 있습니다.</td>
   </tr>
   <tr>
   <td><b>[!UICONTROL Click to Open] %</b></td>
   <td>이메일이 열리고 이메일의 링크를 클릭한 비율입니다. 고유 클릭 수를 고유 열람 수로 나누고 100을 곱하여 백분율로 표시함으로써 이메일의 관련성과 컨텍스트를 측정합니다.</td>
   </tr>
   <tr>
   <td><b>[!UICONTROL Engagement Score]</b></td>
   <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.html" target="_blank">참여 점수</a>를 통해 콘텐츠의 효과를 확인할 수 있습니다.</td>
   </tr>
   </table>

   >[!TIP]
   >
   >참여 점수를 선택하면 테스트를 최소 24시간 실행해야 합니다. [참여 점수 이해](/help/marketo/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.md){target="_blank"}에 대해 자세히 알아보세요.

1. **[!UICONTROL Custom Conversion]**&#x200B;을(를) 선택하고 **[!UICONTROL Edit]**&#x200B;을(를) 클릭하여 조건을 사용자 지정할 수도 있습니다.

   ![](assets/image2014-9-12-15-3a51-3a53.png)

   >[!NOTE]
   >
   >사용자 지정 전환을 사용하면 트리거와 필터를 사용하여 이벤트를 전환으로 선택할 수 있습니다.

1. 창이 열립니다. 선택한 트리거를 찾아 캔버스로 드래그합니다.

   ![](assets/image2014-9-12-15-3a52-3a18.png)

1. 트리거 정의.

   ![](assets/image2014-9-12-15-3a53-3a11.png)

   >[!IMPORTANT]
   >
   >Marketo은 이 이메일 프로그램에서 이메일을 전송한 사람에 대해서만 트리거/필터를 허용하므로 &#39;전송된 이메일&#39; 필터를 추가할 필요가 없습니다. 또한 이메일 관련 트리거/필터를 사용할 때는 연산자로 &quot;is any&quot;를 사용해야 합니다.

1. **[!UICONTROL Close]**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-12-15-3a53-3a36.png)

   잘됐네! 이제 승자를 결정하는 방법을 결정할 때입니다.

## 우승자 선언 {#declare-winner}

1. 사용 가능한 두 옵션 중 하나를 선택합니다.

   ![](assets/image2014-9-12-15-3a53-3a44.png)

   >[!NOTE]
   >
   >**날짜/시간** A/B 테스트를 수행하는 경우 **[!UICONTROL Manual]**&#x200B;만 선택할 수 있습니다.

   A/B 테스트가 끝나면 Marketo에서 예약된 시간에 자동으로 우승 이메일을 보내거나 결과를 검토하고 언제 종료될지 결정할 수 있습니다.

1. 자동은 굉장하며 기본 옵션입니다. **[!UICONTROL Next]**&#x200B;을(를) 클릭하세요.

   ![](assets/image2014-9-12-15-3a54-3a35.png)

   >[!TIP]
   >
   >**[!UICONTROL Manual]**&#x200B;을(를) 선택하면 테스트가 전송되고 우승자를 선언할 때까지 기다립니다. 결과 보고서를 받게 됩니다.

완벽해! 이제 [A/B 테스트를 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md){target="_blank"}하겠습니다.
