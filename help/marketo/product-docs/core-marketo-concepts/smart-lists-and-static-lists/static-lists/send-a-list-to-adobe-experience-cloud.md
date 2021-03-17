---
unique-page-id: 37356194
description: Adobe Experience Cloud - Marketing To Docs - 제품 문서로 목록 보내기
title: Adobe Experience Cloud으로 목록 보내기
translation-type: tm+mt
source-git-commit: 96d6cc030ecd9d1da844fe27e1c6f62bbd181d62
workflow-type: tm+mt
source-wordcount: '787'
ht-degree: 0%

---


# 목록을 Adobe Experience Cloud {#send-a-list-to-adobe-experience-cloud}에 보내기

>[!NOTE]
>
>Marketing 인스턴스의 HIPAA용 배포에서는 이 기능을 사용할 수 없습니다.

>[!PREREQUISITES]
>
>[Adobe Experience Cloud 대상 공유 설정](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/set-up-adobe-experience-cloud-audience-sharing.md)

## 지원되는 대상 응용 프로그램 {#supported-destination-applications}

* Adobe Advertising Cloud
* Adobe Analytics(**Adobe Audience Manager 라이선스를 소유하고 있는 경우에만**)
* Adobe Audience Manager
* Adobe Experience Manager
* 실시간 고객 데이터 플랫폼 Adobe
* Adobe Target

## 정적 목록 {#how-to-send-a-static-list}을 보내는 방법

정적인 목록은 정적인 것입니다. 수동으로 변경하지 않는 한 Adobe Experience Cloud의 목록은 변경되지 않습니다.

1. Marketing To에서 내보낼 목록을 찾아 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-1.png)

1. **목록 작업** 드롭다운을 클릭하고 **Experience Cloud에 보내기**&#x200B;를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-2.png)

1. **Audience Manager 폴더** 드롭다운을 클릭하고 Experience Cloud에서 원하는 대상 폴더를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-3.png)

1. 새 대상자를 만들지, 기존 대상자를 덮어쓸지를 선택합니다(이 예에서는 새 대상자를 만듭니다.). 새 대상 이름을 입력하고 **보내기**&#x200B;를 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-4.png)

1. **확인**&#x200B;을 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-5.png)

   >[!NOTE]
   >
   >대상 멤버십이 Adobe에 완전히 채워지는 데에는 최대 6-8시간이 걸릴 수 있습니다.

## 동기화된 목록 {#how-to-send-a-synced-list}을 보내는 방법

목록 동기화는 Marketing To에서 목록을 업데이트할 때마다 변경 사항이 Adobe Experience Cloud의 대상에 자동으로 동기화됨을 의미합니다.

1. Marketing To에서 동기화할 목록을 찾아 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-6.png)

1. **목록 작업** 드롭다운을 클릭하고 **Experience Cloud에 보내기**&#x200B;를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-7.png)

1. **대상 라이브러리 폴더** 드롭다운을 클릭하고 Experience Cloud에서 원하는 대상 폴더를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-8.png)

1. 새 대상자를 만들지, 기존 대상자를 덮어쓸지를 선택합니다(이 예에서는 새 대상자를 만듭니다.). 새 대상 이름을 입력하고 **대상 구성원 자격 동기화** 상자를 선택한 다음 **보내기**&#x200B;를 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-9.png)

1. **확인**&#x200B;을 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-10.png)

## 목록 동기화 중지 방법 {#how-to-stop-a-list-sync}

언제든지 목록의 동기화를 중지할 수 있습니다.

1. Marketing To에서 동기화를 중지할 목록을 찾아 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-11.png)

1. **목록 작업** 드롭다운을 클릭하고 **목록 동기화 중지**&#x200B;를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-12.png)

1. 동기화를 중지할 대상을 선택하고 **중지**&#x200B;를 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-13.png)

1. **중지**&#x200B;를 클릭하여 확인합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-14.png)

## 참고 사항 {#things-to-note}

**Adobe Analytics에 공유**

Adobe Audience Manager과 Adobe Analytics을 모두 보유한 고객의 경우, 이 통합을 통해 대상을 Marketing To에서 Adobe Analytics 보고서 세트로 공유할 수 있지만, 이 기능을 사용하려면 Adobe Audience Manager에서 수행해야 하는 몇 가지 추가 구성 단계가 있습니다. 설정 방법에 대한 자세한 내용은 Adobe Audience Manager 설명서를 참조하십시오.[https://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html](https://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html).

**Adobe Audience Manager 고객을 위한 트레이트 사용량**

Marketing To에서 목록 내보내기를 시작하면 Adobe Audience Manager 인스턴스에 다음과 같은 변경 사항이 반영됩니다.

* 내보낸 목록의 모든 리드에 대해 Marketing은 리드의 해시된 이메일을 장치 간 식별자로 사용하여 트레이트를 작성합니다. 트레이트 이름은 내보내기 중에 지정한 대상 이름과 일치합니다.
* Marketing에서 내보낸 목록의 리드와 일치하도록 관리되는 모든 ECID에 대해 Marketing에서는 ECID 장치 식별자를 사용하여 트레이트를 작성합니다. 트레이트 이름은 내보내기 중에 지정한 대상 이름과 일치합니다.
* 또한 Marketing에서는 ECID 트레이트를 단독 세그먼테이션 기준으로 Audience Manager 인스턴스에 세그먼트를 만듭니다. 세그먼트 이름은 내보내기 중에 지정한 대상 대상 이름과 일치합니다.

## FAQ {#faq}

**Marketing의 목록 크기가 Adobe의 목록 크기와 다른 이유는 무엇입니까?**

백그라운드에서 대상 통합은 Marketing to Munchkin 쿠키를 해당 Adobe ECID 쿠키와 동기화하여 작동합니다. Marketing To는 Marketing To가 ECID를 동기화한 리드의 멤버십 데이터만 공유할 수 있습니다. 최상의 결과를 얻으려면 마케팅 목적으로 추적하려는 모든 페이지에서 Adobe의 visitor.js 추적 코드와 함께 Marketing의 munchkin.js 추적 스크립트를 로드하는 것이 좋습니다.

**쿠키 동기화는 어떻게 작동합니까?**

Marketing To 구독에 쿠키 동기화가 활성화되어 있으면 Marketing의 munchkin.js는 통합 설정 중에 지정한 Adobe IMS 조직에 대한 Adobe ECID를 캡처하고 저장하려고 하며 이러한 ECID를 해당 Marketing To 쿠키 식별자와 일치시킵니다. 이를 통해 Marketing의 익명 사용자 프로필은 Adobe ECID를 통해 더욱 풍부해집니다.

일반 텍스트 이메일을 사용하여 식별되는 리드 프로필에 익명 사용자 프로필을 연결하려면 추가 단계가 필요합니다. 정확히 이러한 작업이 작동하는 방식은 [여기에 설명되어 있습니다](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md).

**어떤 정보가 공유됩니까?**

이 통합은 Marketing To에서 Adobe(예: 리드 X가 목록 Y의 멤버라는 지식)에 대한 멤버십 정보만 공유합니다. 이 통합을 통해 추가 리드 속성이 Adobe에 공유되지 않습니다.
