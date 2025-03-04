---
unique-page-id: 2359476
description: 이메일 프로그램 대시보드 - Marketo 문서 - 제품 설명서 사용
title: 이메일 프로그램 대시보드 사용
exl-id: 47c1925a-144b-4277-a08d-1af660ed3d50
feature: Email Programs
source-git-commit: b2ceefb068005d916027fb71be0dc4e25849ae23
workflow-type: tm+mt
source-wordcount: '397'
ht-degree: 0%

---

# 이메일 프로그램 대시보드 사용 {#use-the-email-program-dashboard}

이 대시보드 보기에서 이메일 프로그램의 성능을 확인하십시오.

>[!CAUTION]
>
>정확한 보고를 위해 Smart Campaign에서 참조하거나 시작한 전자 메일 프로그램에서 새 전자 메일 프로그램으로 자산을 이동하여 전자 메일 프로그램에서 전자 메일을 _다시 사용_&#x200B;하지 마십시오. 이렇게 하면 해당 이메일에 첨부된 모든 보고 대시보드의 모든 데이터가 집계됩니다. 이메일을 다시 사용해야 하는 경우 [복제](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/clone-an-asset-in-a-program.md){target="_blank"}하십시오. 복사한 이메일은 새 이메일 ID로 새로 만듭니다.

>[!NOTE]
>
>프로그램에 A/B 테스트가 있는 경우 [이메일 프로그램 대시보드 - A/B 테스트 보기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/use-the-email-program-dashboard-a-b-test-view.md){target="_blank"}를 확인하십시오.

![](assets/image2014-9-12-14-3a12-3a56.png)

>[!NOTE]
>
>이 보기의 모든 데이터는 집계됩니다(A/B 테스트와 최종 이메일 전송 포함).

## 이메일 전송 {#email-send}

여기에서 전송, 반송 및 게재된 이메일 수를 확인할 수 있습니다.

![](assets/image2014-9-12-14-3a13-3a3.png)

>[!NOTE]
>
>Marketo의 제어 범위를 벗어나는 이메일 게재 기능 표준으로 인해 바운스 및 게재됨 통계는 정확하지 않고 근사적입니다.

## 열람/클릭 수 {#opens-clicks}

이 차트는 이메일 프로그램이 실행된 후 특정 기간 동안 열고 클릭한 이메일 수를 보여 줍니다.

![](assets/image2014-9-12-14-3a13-3a7.png)

>[!TIP]
>
>시간이 지남에 따라 열기/클릭 수가 어떻게 감소하는지 확인합니다.

## 요약 - 참여 {#summary-engagement}

전체 [참여 점수](/help/marketo/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.md){target="_blank"}를 보여 줍니다.

![](assets/image2014-9-12-14-3a13-3a11.png)

## 요약 - 나머지 {#summary-rest}

나머지 데이터에는 열기, 클릭 수, 클릭/열기 비율 및 가입 해제가 표시됩니다.

![](assets/image2014-9-12-14-3a13-3a15.png)

>[!TIP]
>
>위의 예에서 **구독 취소** 비율이 너무 낮아서 Marketo이 확대되어 더 잘 보일 수 있습니다. 막대 내의 두 번째 숫자는 배율을 위해 추가되었을 뿐입니다.

>[!NOTE]
>
>**정의**
>
>**열기**&#x200B;는 전자 메일 받는 사람이 Marketo에 삽입된 추적 픽셀이 포함된 전자 메일 이미지를 다운로드할 때 계산됩니다. 수신자가 이메일을 보지만 이미지를 다운로드하지 않기로 선택한 경우 이는 열림으로 계산되지 않습니다. 이미지가 수신자의 미리 보기 창에 로드되면 일반적으로 열린 것으로 계산되지만 이메일 클라이언트에 따라 달라집니다.
>
>**열려면 클릭**&#x200B;은(는) 열려 있고 링크가 전자 메일에서 클릭한 전자 메일의 비율을 측정합니다. 고유한 클릭 수를 고유한 열기 수로 나눈 다음 100을 곱하면 백분율로 표시됩니다.

## 대시보드 새로 고침 {#refresh-dashboard}

최신 데이터를 보려면 대시보드에서 새로 고침 아이콘을 클릭하면 됩니다.

![](assets/refreshicon.png)

>[!MORELIKETHIS]
>
>[전자 메일 프로그램 대시보드 사용 - A/B 테스트 보기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/use-the-email-program-dashboard-a-b-test-view.md){target="_blank"}
