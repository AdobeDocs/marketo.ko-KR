---
unique-page-id: 37356194
description: 정적 목록을 Adobe Experience Cloud으로 내보내기 - Marketing Docs - 제품 문서
title: 정적 목록을 Adobe Experience Cloud으로 내보내기
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '593'
ht-degree: 0%

---


# 정적 목록을 Adobe Experience Cloud으로 내보내기 {#export-a-static-list-to-adobe-experience-cloud}

>[!NOTE]
>
>Marketing To 인스턴스의 HIPAA에서 바로 사용할 수 있는 배포에서는 이 기능을 사용할 수 없습니다.

>[!NOTE]
>
>**사전 요구 사항**
>
>[Adobe Experience Cloud 대상 공유 설정](http://docs.marketo.com/x/D4GMAg)

## 지원되는 대상 응용 프로그램 {#supported-destination-applications}

* Adobe Advertising Cloud
* Adobe Analytics(Adobe Audience Manager 라이선스를 소유하고 있는&#x200B;**경우에만** 해당)
* Adobe Audience Manager
* Adobe Experience Manager
* Adobe 실시간 고객 데이터 플랫폼
* Adobe Target

## 목록을 내보내는 방법 {#how-to-export-a-list}

1. Marketing에서 내보낼 목록을 찾아 선택합니다.

   ![](assets/one.png)

1. 작업 **목록** 드롭다운을 클릭하고 Experience Cloud에 **보내기를 선택합니다**.

   ![](assets/two-1.png)

1. Audience Manager **폴더** 드롭다운을 클릭하고 Experience Cloud에서 원하는 대상 폴더를 선택합니다.

   ![](assets/three-1.png)

1. 새 대상을 만들지 기존 대상을 덮어쓸지 여부를 선택합니다(이 예에서는 새 대상을 만듭니다.). 새 대상자 이름을 입력하고 전송을 **클릭합니다**.

   ![](assets/four.png)

1. 확인을 **클릭합니다**.

   ![](assets/five.png)

   >[!NOTE]
   >
   >대상 멤버십이 Adobe에서 완전히 채워지는 데 최대 6-8시간이 걸릴 수 있습니다.

## 참고 사항 {#things-to-note}

**Adobe Analytics에 공유**

Adobe Audience Manager과 Adobe Analytics을 모두 보유한 고객의 경우 이 통합을 통해 Marketing에서 Adobe Analytics 보고서 세트로 대상을 공유할 수 있지만, 이를 활성화하려면 Adobe Audience Manager에서 수행해야 하는 몇 가지 추가 구성 단계가 있습니다. 설정 방법에 대한 자세한 내용은 Adobe Audience Manager 설명서를 참조하십시오. [https://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html](http://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html).

**Adobe Audience Manager 고객의 특성 사용**

Marketing To에서 목록 내보내기를 시작할 때 다음 변경 사항이 Adobe Audience Manager 인스턴스에 반영됩니다.

* 내보낸 목록에 있는 모든 리드의 경우, Marketing에서는 리드의 해시된 이메일을 장치 간 식별자로 사용하여 트레이트를 작성합니다. 트레이트의 이름은 내보내기 중에 지정한 대상 이름과 일치합니다.
* Marketing to가 내보낸 목록의 리드와 일치하는 모든 ECID에 대해 Marketing에서는 ECID 장치 식별자를 사용하여 트레이트를 작성합니다. 트레이트의 이름은 내보내기 중에 지정한 대상 이름과 일치합니다.
* 또한 Marketing에서는 ECID 트레이트를 단독 세그먼테이션 기준으로 Audience Manager 인스턴스에 세그먼트를 만듭니다. 세그먼트 이름은 내보내기 중에 지정한 대상 대상 이름과 일치합니다.

## FAQ {#faq}

**Marketing의 목록 크기가 Adobe의 목록 크기와 다른 이유는 무엇입니까?**

백그라운드에서, 대상 통합은 Marketing to Munchkin 쿠키를 해당 Adobe ECID 쿠키와 동기화하여 작동합니다. Marketing to는 Marketing To가 ECID를 동기화한 리드에 대한 멤버십 데이터만 공유할 수 있습니다. 최상의 결과를 얻으려면 마케팅을 위해 추적하려는 모든 페이지에서 Adobe visitor.js 추적 코드와 함께 Marketing의 munchkin.js 추적 스크립트를 로드하는 것이 좋습니다.

**쿠키 동기화는 어떻게 작동합니까?**

Marketing to 구독에 대한 쿠키 동기화가 활성화되면 Marketing&#39;s munchkin.js는 통합 설정 중에 지정한 Adobe IMS 조직에 대한 Adobe ECID를 캡처하고 저장하려고 하며 이러한 ECID를 해당 Marketing To 쿠키 식별자와 일치시킵니다. 이를 통해 Marketing의 익명 사용자 프로필은 Adobe ECID로 더욱 풍부해집니다.

일반 텍스트 이메일을 사용하여 식별되는 리드 프로필에 익명 사용자 프로필을 연결하려면 추가 단계가 필요합니다. 이러한 작동 방식을 여기에서 정확히 설명합니다. [https://docs.marketo.com/display/public/DOCS/Tracking+Anonymous+Activity+and+People](http://docs.marketo.com/display/public/DOCS/Tracking+Anonymous+Activity+and+People).
