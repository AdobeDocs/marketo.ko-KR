---
unique-page-id: 37356194
description: Adobe Experience Cloud에 목록 보내기 - Marketo 문서 - 제품 설명서
title: Adobe Experience Cloud으로 목록 보내기
exl-id: 770eefe1-05f9-409d-8e7c-b3f1e6ba8139
source-git-commit: a82a2dd0a9c3a27b9b6bf3b352cd81d59932a31b
workflow-type: tm+mt
source-wordcount: '770'
ht-degree: 0%

---

# Adobe Experience Cloud으로 목록 보내기 {#send-a-list-to-adobe-experience-cloud}

>[!NOTE]
>
>Marketo 인스턴스의 HIPAA 준비 배포에서는 이 기능을 사용할 수 없습니다.

>[!PREREQUISITES]
>
>[Adobe Experience Cloud 대상 공유 설정](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/set-up-adobe-experience-cloud-audience-sharing.md)

## 지원되는 대상 응용 프로그램 {#supported-destination-applications}

* Adobe Advertising Cloud
* Adobe Analytics (**전용** Adobe Audience Manager 라이센스를 소유한 경우)
* Adobe Audience Manager
* Adobe Experience Manager
* Adobe Real-time Customer Data Platform
* Adobe Target

## 정적 목록을 보내는 방법 {#how-to-send-a-static-list}

정적인 리스트는 정적인 것입니다. 수동으로 변경하지 않으면 Adobe Experience Cloud의 목록이 변경되지 않습니다.

1. Marketo에서 내보낼 목록을 찾습니다. 마우스 오른쪽 단추를 클릭하고 을 선택합니다. **Experience Cloud으로 보내기**.

   ![](assets/send-a-list-to-adobe-experience-cloud-1.png)

1. 을(를) 클릭합니다. **Audience Manager 폴더** 드롭다운을 클릭하고 Experience Cloud에서 원하는 대상 폴더를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-2.png)

1. 새 대상을 만들지 아니면 기존 대상을 덮어쓸지 선택합니다(이 예에서는 새 대상을 만듭니다). 새 대상 이름을 입력하고 을(를) 클릭합니다 **보내기**.

   ![](assets/send-a-list-to-adobe-experience-cloud-3.png)

1. 클릭 **확인**.

   ![](assets/send-a-list-to-adobe-experience-cloud-4.png)

   >[!NOTE]
   >
   >Adobe에서 대상 멤버십을 완전히 채우는 데는 최대 6~8시간이 걸릴 수 있습니다.

## 동기화된 목록을 보내는 방법 {#how-to-send-a-synced-list}

목록 동기화는 Marketo에서 목록을 업데이트할 때마다 변경 사항이 Adobe Experience Cloud의 해당 대상으로 자동으로 동기화됨을 의미합니다.

1. Marketo에서 내보낼 목록을 찾습니다. 마우스 오른쪽 단추를 클릭하고 을 선택합니다. **Experience Cloud으로 보내기**.

   ![](assets/send-a-list-to-adobe-experience-cloud-5.png)

1. 을(를) 클릭합니다. **대상 라이브러리 폴더** 드롭다운을 클릭하고 Experience Cloud에서 원하는 대상 폴더를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-6.png)

1. 새 대상을 만들지 아니면 기존 대상을 덮어쓸지 선택합니다(이 예에서는 새 대상을 만듭니다). 새 대상 이름을 입력하고 **대상 멤버십을 동기화된 상태로 유지** 상자를 열고 **보내기**.

   ![](assets/send-a-list-to-adobe-experience-cloud-7.png)

1. 클릭 **확인**.

   ![](assets/send-a-list-to-adobe-experience-cloud-8.png)

## 목록 동기화를 중지하는 방법 {#how-to-stop-a-list-sync}

언제든지 목록의 동기화를 중지할 수 있습니다.

1. Marketo에서 동기화를 중지할 목록을 찾아 마우스 오른쪽 단추로 클릭합니다. 클릭 **목록 동기화 중지**.

   ![](assets/send-a-list-to-adobe-experience-cloud-9.png)

1. 동기화되지 않을 대상을 선택하고 을(를) 클릭합니다. **정지**.

   ![](assets/send-a-list-to-adobe-experience-cloud-10.png)

1. 클릭 **정지** 확인합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-11.png)

## 참고 사항 {#things-to-note}

**Adobe Analytics에 공유**

Adobe Audience Manager과 Adobe Analytics을 모두 소유한 고객의 경우 이 통합을 통해 대상을 Marketo에서 Adobe Analytics 보고서 세트로 공유할 수 있지만 Adobe Audience Manager에서 이 기능을 활성화하기 위해 수행해야 하는 몇 가지 추가 구성 단계가 있습니다. 설정 방법에 대한 자세한 내용은 Adobe Audience Manager 설명서를 참조하십시오. [https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html](https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html).

**Adobe Audience Manager 고객에 대한 트레이트 사용량**

Marketo에서 목록 내보내기를 시작하면 Adobe Audience Manager 인스턴스에 반영되는 다음 변경 사항이 표시됩니다.

* 내보낸 목록의 모든 리드에 대해 Marketo은 리드의 해시된 이메일을 교차 장치 식별자로 사용하여 트레이트를 작성합니다. 트레이트의 이름은 내보내기 중에 지정한 대상 이름과 일치합니다.
* Marketo이 내보낸 목록의 리드와 일치하도록 관리하는 모든 ECID에 대해 Marketo은 ECID 장치 식별자를 사용하여 트레이트를 작성합니다. 트레이트의 이름은 내보내기 중에 지정한 대상 이름과 일치합니다.
* 또한 Marketo은 ECID 트레이트를 유일한 세그멘테이션 기준으로 사용하여 Audience Manager 인스턴스에서 세그먼트를 만듭니다. 세그먼트 이름은 내보내기 중에 지정한 대상 대상 이름과 일치합니다.

## FAQ {#faq}

**Marketo의 목록 크기가 Adobe의 목록 크기와 다른 이유는 무엇입니까?**

후드에서는 대상 통합이 Marketo Munchkin 쿠키를 해당 Adobe ECID 쿠키와 동기화하여 작동합니다. Marketo은 Marketo이 ECID를 동기화한 리드에 대한 멤버십 데이터만 공유할 수 있습니다. 최상의 결과를 얻으려면 마케팅 목적으로 추적하려는 모든 페이지에서 Marketo의 munchkin.js 추적 스크립트를 Adobe의 visitor.js 추적 코드와 함께 로드하는 것이 좋습니다.

**쿠키 동기화는 어떻게 작동합니까?**

Marketo 가입에 대해 쿠키 동기화가 활성화되면 Marketo의 munchkin.js는 통합 설정 중에 지정한 Adobe IMS 조직에 대한 Adobe ECID를 캡처하고 저장하려고 하며 이러한 ECID를 해당 Marketo 쿠키 식별자와 일치시킵니다. 이를 통해 Marketo의 익명의 사용자 프로필이 Adobe ECID로 보강될 수 있습니다.

일반 텍스트 이메일을 사용하여 식별되는 리드 프로필에 익명 사용자 프로필을 연결하려면 추가 단계가 필요합니다. 정확히 어떻게 작동되는지 [여기에서 설명합니다.](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md).

**어떤 정보가 공유됩니까?**

이 통합은 Marketo에서 Adobe에 이르는 목록 멤버십 정보만 공유합니다(예: Lead X가 List Y의 구성원이라는 인식). 이 통합을 통해 Adobe에 추가 리드 속성이 공유되지 않습니다.
