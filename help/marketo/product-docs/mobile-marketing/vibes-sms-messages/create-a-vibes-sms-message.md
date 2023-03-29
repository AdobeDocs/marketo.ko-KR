---
unique-page-id: 11378869
description: 비디오 SMS 메시지 만들기 - Marketo 문서 - 제품 설명서
title: 비디오 SMS 메시지 만들기
exl-id: 9ec0da97-7a80-4c40-be79-be08d7d1d9c1
source-git-commit: 88c4e844f7ce26b12bae8177dd5311813fb4adcb
workflow-type: tm+mt
source-wordcount: '374'
ht-degree: 0%

---

# 비디오 SMS 메시지 만들기 {#create-a-vibes-sms-message}

다음은 Video SMS 메시지를 만드는 방법입니다.

>[!AVAILABILITY]
>
>이 기능은 Adobe Marketo Engage 계정의 추가 기능으로 사용할 수 있습니다. 제대로 프로비저닝하려면 Adobe을 통해 구매해야 합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

>[!NOTE]
>
>SMS 텍스트 메시지는 HIPAA를 준수하지 않습니다.

1. 이동 **마케팅 활동** 프로그램을 마우스 오른쪽 단추로 클릭합니다.

   ![](assets/mobile-right-click-hand.jpg)

1. 클릭 **새 로컬 자산**.

   ![](assets/new-local-asset-hand.jpg)

   >[!TIP]
   >
   >또는 **새로 만들기** 드롭다운.

1. 클릭 **SMS 메시지**.

   ![](assets/new-local-asset-selection-hand.jpg)

1. 새 SMS 메시지의 이름과 선택적 설명을 입력하고 을(를) 클릭합니다 **만들기**.

   ![](assets/new-sms-message-offer-ends-soon-hands.jpg)

1. 클릭 **초안 편집**.

   ![](assets/edit-draft-hand.jpg)

1. 메시지 편집기에서 파란색 풍선 내부를 클릭하고 텍스트 입력을 시작합니다.

   ![](assets/message-text-pencil.jpg)

   >[!NOTE]
   >
   >미국과 캐나다의 한계는 각각 160자와 130자로 다릅니다. 이러한 문자 제한을 초과하는 경우 메시지를 분할할 수 있습니다. 캐나다 제한을 초과하는 시점을 표시하는 동안 편집기는 미국용으로 최적화되어 있으며 미국 제한에 따라 메시지를 분할합니다.

1. 클릭 **토큰** 삽입 메뉴에서 메시지에 토큰을 추가합니다.

   ![](assets/add-token-real-hand.jpg)

   >[!NOTE]
   >
   >토큰을 추가하면 메시지가 문자 제한을 초과할 수 있습니다. 그러면 메시지가 분할되어 추가 비용이 발생합니다.

1. 클릭 **링크** 삽입 메뉴에서 메시지에 링크를 추가합니다.

   ![](assets/full-message-link-hand.jpg)

1. 링크 유형을 선택합니다. Marketo 랜딩 페이지가 기본값입니다. 이 옵션을 사용하려면 드롭다운에서 랜딩 페이지를 선택하고 을(를) 클릭해야 합니다 **삽입**.

   ![](assets/insert-link-real-hands.jpg)

   >[!NOTE]
   >
   >기본적으로 두 추적 링크가 선택됩니다.

1. 대신 외부 URL을 사용하려면 **외부 URL** 버튼을 클릭하고 URL 필드에 URL을 입력합니다. 클릭 **삽입**.

   ![](assets/insert-link-url-hands.jpg)

1. 링크가 메시지에 표시됩니다.

   ![](assets/link-added.jpg)

   >[!NOTE]
   >
   >Marketo은 브랜드 추적 도메인의 링크 미리 보기를 표시합니다. mkt_tok 링크 확인란을 선택 취소하면 링크가 변경됩니다. 링크 추적 확인란도 선택 취소하면 URL이 기본 길이(예: www.mygooglepage.com)으로 짧아집니다.

   ![](assets/image2016-7-27-16-3a20-3a16.png)

   >[!NOTE]
   >
   >문자 수는 가장 낮은 메시지에 포함된 문자만 반영합니다.

미국 제한보다 많은 값을 삽입하면 편집기가 메시지를 섹션으로 분할합니다. 절대 합계 제한은 900자입니다. 이 한도에 도달하면 메시지가 대상자에게 전송될 때 자동으로 잘립니다.
