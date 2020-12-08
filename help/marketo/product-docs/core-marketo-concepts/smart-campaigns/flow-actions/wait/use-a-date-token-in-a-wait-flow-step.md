---
unique-page-id: 1146997
description: 대기 흐름 단계에서 날짜 토큰 사용 - Marketing To Docs - 제품 설명서
title: 대기 흐름 단계에서 날짜 토큰 사용
translation-type: tm+mt
source-git-commit: 728066ab05de82f6123bfaa1f0b05af8632e32b2
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 0%

---


# 대기 흐름 단계에서 날짜 토큰 사용 {#use-a-date-token-in-a-wait-flow-step}

대기 흐름 단계를 사용하여 날짜 토큰을 사용하는 특정 날짜가 될 때까지 스마트 캠페인을 통해 개인의 여행을 일시 중지할 수 있습니다. 종료 날짜를 일부 일수로 수정할 수도 있습니다.

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

>[!NOTE]
>
>캠페인 트리거 목적으로만 적용됩니다. 일괄 캠페인에서는 이 기능을 사용할 수 없습니다.

1. 스마트 캠페인 흐름 **탭에서** 대기 **흐름** 단계 위로드래그합니다.

   ![](assets/image2014-9-22-14-3a8-3a22.png)

1. 오른쪽에 있는 톱니바퀴 아이콘을 클릭합니다.

   ![](assets/image2014-9-22-14-3a8-3a37.png)

1. 유형 **드롭다운에서** 날짜 **토큰을 선택합니다**.

   ![](assets/image2014-9-22-14-3a8-3a41.png)

1. 날짜 토큰을 선택하여 대기 단계가 종료되어야 하는 시점을 지정합니다.

   * `{{my._____}}`
   * `{{lead.______}}`
   * `{{company.______}}`
   * `{{system._______}}`

   ![](assets/image2014-9-22-14-3a9-3a33.png)

1. 현재 또는 다음 달력 연도에 발생하는 날짜의 다음 주기를 기다리려면 확인란을 선택합니다.

   ![](assets/image2014-9-22-14-3a9-3a37.png)

   >[!TIP]
   >
   >생일 또는 계약 시작 날짜 등 과거 날짜를 참조하는 날짜 토큰에 이 옵션을 사용합니다.

1. 종료 날짜를 지정된 일 수로 수정할 수도 있습니다.

   ![](assets/image2014-9-22-14-3a9-3a57.png)

   >[!NOTE]
   >
   >정수 필드를 나타내는 `{{lead.` 또는 `{{company.` 토큰 또는 숫자 유형의 `{{my.` 토큰을 사용하여 일 수를 지정할 수도 있습니다.

1. 저장을 클릭합니다.

   ![](assets/image2014-9-22-14-3a11-3a3.png)

   >[!NOTE]
   >
   >**관련 문서**
   >
   >* [대기 흐름 단계에서 지속 시간 사용](use-a-duration-in-a-wait-flow-step.md)
   >* [대기 흐름 단계에서 특정 날짜 사용](use-a-specific-date-in-a-wait-flow-step.md)


