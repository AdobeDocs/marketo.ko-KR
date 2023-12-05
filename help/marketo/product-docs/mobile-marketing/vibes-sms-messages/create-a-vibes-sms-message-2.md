---
description: Vibes SMS 메시지 만들기 - Marketo 문서 - 제품 설명서
title: Vibes SMS 메시지 만들기
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: cd09ad43c08855af63131aa385c4fd406c963926
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 0%

---

# Vibes SMS 메시지 만들기 {#create-a-vibes-sms-message}

Vibes SMS 메시지를 만드는 방법은 다음과 같습니다.

>[!AVAILABILITY]
>
>이 기능은 Adobe Marketo Engage 계정의 추가 기능으로 사용할 수 있습니다. 제대로 프로비저닝되려면 Adobe을 통해 구매해야 합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

1. 다음으로 이동 **마케팅 활동**.

   ![](assets/mobile-right-click-hand.jpg)

1. 프로그램을 마우스 오른쪽 단추로 클릭하고 를 선택합니다. **새 로컬 자산**.

   ![](assets/mobile-right-click-hand.jpg)

1. 클릭 **새 로컬 자산**.

   ![](assets/new-local-asset-hand.jpg)

   >[!TIP]
   >
   >또는 다음을 클릭할 수 있습니다. **신규** 드롭다운.

1. 클릭 **SMS 메시지**.

   ![](assets/new-local-asset-selection-hand.jpg)

1. 새 SMS 메시지의 이름과 설명(선택 사항)을 입력하고 **만들기**.

   ![](assets/new-sms-message-offer-ends-soon-hands.jpg)

1. 클릭 **초안 편집**.

   ![](assets/edit-draft-hand.jpg)

1. 메시지 편집기에서 파란색 버블 내부를 클릭하고 텍스트 입력을 시작합니다.

   ![](assets/message-text-pencil.jpg)

   >[!NOTE]
   >
   >SMS 메시지의 문자 제한은 표준 ASCII 문자 집합을 사용하는 160자입니다. 160자를 초과하면 메시지가 총 문자 수에 따라 분할됩니다.

1. 클릭 **토큰** 삽입 메뉴에서 토큰을 메시지에 추가합니다.

   ![](assets/add-token-real-hand.jpg)

   >[!NOTE]
   >
   >토큰을 추가하면 메시지가 문자 제한을 초과할 수 있습니다. 그러면 메시지가 분할되어 추가 메시지가 발생합니다.

   >[!IMPORTANT]
   >
   >SMS 준수: 모든 아웃바운드 SMS 메시지에는 브랜드 이름 또는 프로그램 설명이 포함되어야 합니다. 도움말 및 중지 지침은 반복 메시지 프로그램의 경우 구독자당 매월 1회 이상 제공되어야 합니다.

   ?????? Marketo URL 단축키를 사용하면 메시지 이름에 X 문자가 사용됩니다??????

1. 클릭 **링크** 을 클릭하여 메시지에 대한 링크를 추가합니다.

   ![](assets/full-message-link-hand.jpg)

1. 링크 유형을 선택합니다. Marketo 랜딩 페이지가 기본값입니다. 이 옵션을 선택하면 드롭다운에서 랜딩 페이지를 선택하고 을(를) 클릭합니다. **삽입**.

   ![](assets/insert-link-real-hands.jpg)

   >[!NOTE]
   >
   >* 기본적으로 두 개의 추적 링크가 선택되어 있습니다.
   >* Marketo URL 단축키를 사용하면 메시지에 X 문자가 사용됩니다.??????????????????

1. 외부 URL을 대신 사용하려면 **외부 URL** 버튼을 클릭하고 URL 필드에 URL을 입력합니다. 클릭 **삽입**.

   ![](assets/insert-link-url-hands.jpg)

   >[!CAUTION]
   >
   >권장 사항: _아님_ 통신사가 메시지를 스팸으로 표시할 수 있으므로 URL 단축기(예: Bitly)를 사용하십시오.

1. 링크가 메시지에 표시됩니다.

   ![](assets/link-added.jpg)

   >[!NOTE]
   >
   >Marketo에 브랜드 추적 도메인의 링크 미리보기가 표시됩니다. mkt_tok 링크 확인란의 선택을 취소하면 링크가 변경됩니다. 링크 추적 확인란도 선택 취소하면 URL이 기본 길이로 짧아집니다(예: www.mygooglepage.com).

   ![](assets/image2016-7-27-16-3a20-3a16.png)

   >[!NOTE]
   >
   >문자 수는 가장 낮은 메시지에 포함된 문자만 반영합니다.

미국 한도보다 더 많이 삽입하는 경우 편집기는 메시지를 섹션으로 나눕니다. 총 길이는 900자로 제한됩니다. 제한에 도달하면 메시지가 대상자에게 전송될 때 자동으로 잘립니다.

미국 제한????????
