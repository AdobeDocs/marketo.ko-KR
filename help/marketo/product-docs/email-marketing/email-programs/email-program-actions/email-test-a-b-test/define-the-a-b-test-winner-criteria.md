---
unique-page-id: 2359545
description: A/B 테스트 승자 기준 정의 - Marketo 문서 - 제품 설명서
title: A/B 테스트 승자 기준 정의
exl-id: be8a0887-70f4-4667-93a6-d982a16cdfdb
source-git-commit: 67ae4605d541a475b42a5094a5588c469a9d975d
workflow-type: tm+mt
source-wordcount: '439'
ht-degree: 0%

---

# A/B 테스트 승자 기준 정의 {#define-the-a-b-test-winner-criteria}

When [A/B 테스트 추가](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md)이메일 프로그램에 대해 {target=&quot;_blank&quot;} 테스트 유형을 선택해야 합니다. [A/B 테스트 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md){target=&quot;_blank&quot;} 님이 승자 기준을 정의합니다. 다음은 어떤 이메일이 승리하는지 결정하는 방법입니다.

>[!PREREQUISITES]
>
>[A/B 테스트 추가](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md){target=&quot;_blank&quot;}

## 승자 기준 {#winner-criteria}

1. 기본값 **승자 기준** 옵션이 먼저 나열됩니다.

   ![](assets/image2014-9-12-15-3a51-3a3.png)

   <table>
   <tr>
   <td><b>열기</b></td>
   <td>이미지를 전자 메일로 다운로드하면 열린 상태로 등록됩니다. 이미지를 포함하지 않더라도 기본적으로 Marketo에서는 모든 HTML 전자 메일에 단일 추적 픽셀을 삽입합니다.</td>
   </tr>
   <tr>
   <td><b>클릭 수</b></td>
   <td>기본적으로 이메일에 포함된 링크에는 어느 링크를 클릭했는지, 클릭한 총 링크의 수 등을 확인할 수 있는 추적이 포함되어 있습니다.</td>
   </tr>
   <tr>
   <td><b>클릭으로 % 열기</b></td>
   <td>이메일을 열고 링크를 클릭한 이메일의 비율입니다. 이렇게 하면 고유한 클릭 수를 고유한 열기 수로 나눈 다음 100을 곱하여 이메일의 관련성 및 컨텍스트를 측정합니다.</td>
   </tr>
   <tr>
   <td><b>참여 점수</b></td>
   <td>다음 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.html" target="_blank">참여 점수</a> 은 컨텐츠의 효과를 판별하는 데 도움이 됩니다.</td>
   </tr>
   </table>

   >[!TIP]
   >
   >참여 점수를 선택하는 경우 적어도 24시간 동안 테스트를 실행해야 합니다. 추가 정보 [참여 점수 이해](/help/marketo/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.md){target=&quot;_blank&quot;}.

1. 사용자 지정 전환을 선택하고 편집을 클릭하여 기준을 사용자 지정할 수도 있습니다.

   ![](assets/image2014-9-12-15-3a51-3a53.png)

   >[!NOTE]
   >
   >사용자 지정 전환을 사용하면 트리거와 필터를 사용하여 이벤트를 전환으로 선택할 수 있습니다.

1. 창이 열립니다. 원하는 트리거를 찾아 캔버스로 드래그합니다.

   ![](assets/image2014-9-12-15-3a52-3a18.png)

1. 트리거를 정의합니다.

   ![](assets/image2014-9-12-15-3a53-3a11.png)

   >[!IMPORTANT]
   >
   >Marketo에서는 이 이메일 프로그램에서 이메일을 보낸 사람에 대한 트리거/필터만 허용하므로 &#39;이메일을 전송함&#39; 필터를 추가할 필요가 없습니다. 또한 전자 메일 관련 트리거/필터를 사용할 때는 &quot;is any&quot;를 연산자로 사용해야 합니다.

1. Click **Close**.

   ![](assets/image2014-9-12-15-3a53-3a36.png)

   좋아요! 이제 승자가 어떻게 결정되는지 결정할 차례다.

## 승자 선언 {#declare-winner}

1. 사용 가능한 두 옵션 중 하나를 선택합니다.

   ![](assets/image2014-9-12-15-3a53-3a44.png)

   >[!NOTE]
   >
   >만약 **날짜/시간** A/B 테스트만 선택할 수 있습니다 **수동**.

   A/B 테스트가 끝나면 Marketo은 예약된 시간에 우승 이메일을 자동으로 전송하거나 결과를 검토하고 언제 발송되는지 결정할 수 있습니다.

1. 자동 은 뛰어난 기능이며 기본 옵션입니다. 클릭 **다음**.

   ![](assets/image2014-9-12-15-3a54-3a35.png)

   >[!TIP]
   >
   >선택 **수동** 은(는) 테스트를 보내고 우승자를 선언할 때까지 기다립니다. 결과 보고서를 받게 됩니다.

완벽해! 이제 [A/B 테스트 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md){target=&quot;_blank&quot;}.
