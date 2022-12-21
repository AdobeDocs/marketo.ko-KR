---
unique-page-id: 1146958
description: 경고 보내기 - Marketo 문서 - 제품 설명서
title: 경고 보내기
exl-id: 2016e2e7-0361-4bb2-8740-819e21fbd15b
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 1%

---

# 경고 보내기 {#send-alert}

## 개요 {#overview}

Marketo은 개인 정보가 있는 이메일 경고를 판매자, 파트너 또는 다른 사람에게 보낼 수 있습니다. 를 사용하십시오 **경고 보내기** 흐름 단계.

![](assets/one-1.png)

## 사용 {#usage}

1. 보낼 이메일을 찾아 선택합니다.

   ![](assets/two-1.png)

   >[!NOTE]
   >
   >이메일 경고에는 모든 헤더 정보가 포함되어야 하며 다음 위치에 있어야 합니다 **승인됨** state.

1. 미리 보기 아이콘을 클릭하여 올바른 이메일을 선택했는지 확인할 수 있습니다.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >를 사용하십시오 **경고 정보 보내기** 토큰으로 보낼 수도 있습니다.

1. 경고 수신자를 선택합니다. 판매 소유자 또는 계정 소유자를 선택할 수 있습니다.

   ![](assets/four-2.png)

1. 원하는 다른 이메일 주소(쉼표 또는 세미콜론으로 구분)를 추가할 수도 있습니다.

   ![](assets/five.png)

   >[!TIP]
   >
   >트리거 캠페인에서 토큰을 사용할 수 있습니다. **다른 전자 메일로 보내기** 예 `{{lead.Territory Owner}}` 또는 `{{my.Alert Recipient}}` 값이 유효한 이메일 주소인 한. 의 토큰 **다른 전자 메일로 보내기** 은 배치 캠페인에서 작동하지 않습니다.

됐습니다. 이제 다음을 사용하는 방법을 알 수 있습니다 **경고 보내기** 흐름 단계.

>[!MORELIKETHIS]
>
>[이메일 만들기](/help/marketo/product-docs/email-marketing/general/creating-an-email/create-an-email.md)
