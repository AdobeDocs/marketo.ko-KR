---
unique-page-id: 13795727
description: 수신자 시간대로 예약된 이메일 프로그램의 배달 중단 - Marketo 문서 - 제품 설명서
title: 수신자 시간대로 예약된 이메일 프로그램의 배달 중단
exl-id: e69afa4a-32fb-4791-a9b6-683d64d610d6
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---

# 수신자 시간대로 예약된 이메일 프로그램의 배달 중단 {#abort-delivery-of-email-programs-scheduled-with-recipient-time-zone}

응급 경우에는 수신자 시간대가 활성화된 상태에서 이미 실행을 시작한 이메일 프로그램 배달을 중단할 수 있습니다.

수신자 시간대와 예약된 이메일 프로그램은 최대 24시간 동안 실행될 수 있으므로 프로그램 배달을 중단하면 해당 시점 이후 모든 후속 전송이 취소됩니다.

1. 취소할 이메일 프로그램을 선택하고 **배달 중단** ( 컨트롤 패널의 승인 타일 아래)

   ![](assets/ptz-abortdelivery.png)

1. 을(를) 클릭하여 게재를 취소할지 확인합니다 **Abort**.

   ![](assets/image2018-2-23-11-3a20-3a27.png)

1. 취소 후 **결과** 이메일 프로그램의 격자는 아래 격자와 비슷합니다. 후속 전송은 취소되며 에는 &quot;이메일 바운스된 소프트&quot;으로 표시됩니다 **활동 유형** 열.

   ![](assets/image2018-2-23-11-3a22-3a11.png)

   >[!NOTE]
   >
   >취소된 전자 메일은 **not** 소프트 바운스로 표시 *까지* 원래 시간대에서 배달될 예정이었던 시간이었다. 그때까지 이 프로필은 여전히 &quot;이메일 전송&quot;으로 표시됩니다.

1. 그리드에서 전자 메일을 클릭하여 활동 세부 사항을 볼 수 있습니다. 취소된 전송의 경우 세부 사항 팝업은 다음과 같이 표시됩니다.

   ![](assets/image2018-2-23-11-3a30-3a46.png)

>[!MORELIKETHIS]
>
>* [수신자 시간대 이해](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
>* [수신자 시간대로 이메일 프로그램 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)

