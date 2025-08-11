---
unique-page-id: 37356194
description: Adobe Experience Cloud에 목록 보내기 - Marketo 문서 - 제품 설명서
title: Adobe Experience Cloud에 목록 보내기
exl-id: 770eefe1-05f9-409d-8e7c-b3f1e6ba8139
feature: Static Lists
source-git-commit: 8bc619b9b9a75c3b20a8f30ebf902ab4b881e627
workflow-type: tm+mt
source-wordcount: '783'
ht-degree: 1%

---

# Adobe Experience Cloud에 목록 보내기 {#send-a-list-to-adobe-experience-cloud}

>[!NOTE]
>
>Marketo Engage 인스턴스의 HIPAA 준비 배포에서는 이 기능을 사용할 수 없습니다.

>[!PREREQUISITES]
>
>[Adobe 조직 매핑 설정](/help/marketo/product-docs/adobe-experience-cloud-integrations/set-up-adobe-organization-mapping.md){target="_blank"}

## 지원되는 대상 애플리케이션 {#supported-destination-applications}

* Adobe Advertising Cloud
* Adobe Analytics(_Adobe Audience Manager 라이선스가 있는 경우에만_)
* Adobe Audience Manager
* Adobe Experience Manager
* Adobe Real-Time Customer Data Platform
* Adobe Target

## 정적 목록을 보내는 방법 {#how-to-send-a-static-list}

정적 목록은 정적입니다. 수동으로 변경하지 않는 한 Adobe Experience Cloud의 목록은 변경되지 않습니다.

1. Marketo에서 내보낼 목록을 찾습니다. 마우스 오른쪽 단추를 클릭하고 **[!UICONTROL Send to Experience Cloud]**&#x200B;을(를) 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-1.png)

1. **[!UICONTROL Audience Manager Folder]** 드롭다운을 클릭하고 Experience Cloud에서 원하는 대상 폴더를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-2.png)

1. 새 대상을 만들지 또는 기존 대상을 덮어쓸지 여부를 선택합니다(이 예제에서는 새 대상을 만드는 것입니다). 새 대상 이름을 입력하고 **[!UICONTROL Send]**&#x200B;을(를) 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-3.png)

1. **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-4.png)

   >[!NOTE]
   >
   >대상 멤버십이 Adobe에 완전히 채워지는 데 최대 6~8시간이 걸릴 수 있습니다.

## 동기화된 목록을 보내는 방법 {#how-to-send-a-synced-list}

목록 동기화는 Marketo에서 목록을 업데이트할 때마다 해당 변경 사항이 Adobe Experience Cloud의 해당 대상자에게 자동으로 동기화됨을 의미합니다.

1. Marketo에서 내보낼 목록을 찾습니다. 마우스 오른쪽 단추를 클릭하고 **[!UICONTROL Send to Experience Cloud]**&#x200B;을(를) 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-5.png)

1. **[!UICONTROL Audience Library Folder]** 드롭다운을 클릭하고 Experience Cloud에서 원하는 대상 폴더를 선택합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-6.png)

1. 새 대상을 만들지 또는 기존 대상을 덮어쓸지 여부를 선택합니다(이 예제에서는 새 대상을 만드는 것입니다). 새 대상 이름을 입력하고 **[!UICONTROL Keep Audience Membership in Sync]** 상자를 선택한 다음 **[!UICONTROL Send]**&#x200B;을(를) 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-7.png)

1. **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-8.png)

## 목록 동기화를 중지하는 방법 {#how-to-stop-a-list-sync}

언제든지 목록 동기화를 중지할 수 있습니다.

1. Marketo에서 동기화를 중지할 목록을 찾아 마우스 오른쪽 버튼으로 클릭합니다. **[!UICONTROL Stop List Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-9.png)

1. 동기화 중지를 원하는 대상자를 선택하고 **[!UICONTROL Stop]**&#x200B;을(를) 클릭합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-10.png)

1. **[!UICONTROL Stop]**&#x200B;을(를) 클릭하여 확인합니다.

   ![](assets/send-a-list-to-adobe-experience-cloud-11.png)

## 참고할 사항 {#things-to-note}

### Adobe Analytics에 공유 {#sharing-to-adobe-analytics}

* Adobe Audience Manager과 Adobe Analytics을 모두 소유하는 사용자의 경우, 이 통합을 통해 대상을 Marketo에서 Adobe Analytics 보고서 세트로 공유할 수 있지만, 이를 활성화하기 위해 Adobe Audience Manager에서 수행해야 하는 몇 가지 추가 구성 단계가 있습니다. 설정 방법에 대한 자세한 내용은 [Adobe Audience Manager의 설명서](https://experienceleague.adobe.com/docs/analytics/integration/audience-analytics/mc-audiences-aam.html){target="_blank"}를 검토하십시오.

* 목록이 Marketo에서 Adobe Audience Manager으로 업로드된 후 Adobe Target에서 액세스할 수도 있습니다. Adobe Target[에서 해당 구성 ](https://experienceleague.adobe.com/en/docs/target/using/integrate/audience-manager-target-integration){target="_blank"}을(를) 사용하도록 설정해야 합니다.

* 목록이 비어 있거나 ECID 값을 가진 사용자가 없는 경우 Marketo 외부에서 참조하도록 목록 이름이 푸시되지 않습니다.

### Adobe Audience Manager 고객을 위한 트레이트 사용 {#trait-usage-aam}

Marketo에서 목록 내보내기를 시작하면 Adobe Audience Manager 인스턴스에 다음과 같은 변경 사항이 반영됩니다.

* 내보낸 목록에 있는 모든 사람에 대해 Marketo은 해시된 이메일을 교차 장치 식별자로 사용하여 트레이트를 기록합니다. 트레이트 이름은 내보내는 동안 지정한 대상 대상 대상 이름과 일치합니다.
* Marketo에서 관리한 모든 ECID가 내보낸 목록의 사용자에 해당하는 경우 Marketo은 ECID 장치 식별자를 사용하여 트레이트를 기록합니다. 트레이트 이름은 내보내는 동안 지정한 대상 대상 대상 이름과 일치합니다.
* Marketo은 또한 ECID 트레이트를 유일한 세그멘테이션 기준으로 사용하여 Audience Manager 인스턴스에 세그먼트를 만듭니다. 세그먼트 이름은 내보내는 동안 지정한 대상 대상 대상 이름과 일치합니다.

## FAQ {#faq}

**Marketo의 목록 크기가 Adobe의 목록 크기와 다른 이유는 무엇입니까?**

Audience Integration은 Adobe Munchkin 쿠키를 해당 Marketo ECID 쿠키와 동기화하여 작동됩니다. Marketo은 Marketo이 ECID를 동기화한 사용자에 대한 멤버십 데이터만 공유할 수 있습니다. 최상의 결과를 얻으려면 마케팅 목적으로 추적하려는 모든 페이지에서 Marketo의 munchkin.js 추적 스크립트를 Adobe의 visitor.js 추적 코드와 동시에 로드하는 것이 좋습니다.

**쿠키 동기화는 어떻게 작동합니까?**

Marketo 구독에 대해 쿠키 동기화가 활성화되면 Marketo의 munchkin.js가 통합 설정 중에 지정한 Adobe IMS 조직에 대한 Adobe ECID를 캡처하고 저장하고 이 ECID를 해당 Marketo 쿠키 식별자와 일치시키려고 합니다. 이렇게 하면 Marketo의 익명 사용자 프로필이 Adobe ECID로 보강될 수 있습니다.

일반 텍스트 이메일을 사용하여 식별된 개인 프로필에 익명 사용자 프로필을 연결하는 추가 단계가 필요합니다. 작동 방식은 [여기에서 설명](/help/marketo/product-docs/reporting/basic-reporting/report-activity/tracking-anonymous-activity-and-people.md){target="_blank"}됩니다.

**어떤 정보가 공유됩니까?**

이 통합은 목록 멤버십 정보(예: 개인 X가 목록 Y의 멤버라는 지식)만 Marketo에서 Adobe으로 공유합니다. 이 통합을 통해 추가적인 개인 속성이 Adobe에 공유되지 않습니다.
