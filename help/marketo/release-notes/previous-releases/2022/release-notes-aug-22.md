---
description: 릴리스 노트 - 2022년 8월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2022년 8월
exl-id: 7a224fa7-0aec-4d0d-9535-c35241a45654
feature: Release Information
source-git-commit: 206952c2aaa9b568a9312def6d36b15f699791b3
workflow-type: tm+mt
source-wordcount: '529'
ht-degree: 0%

---

# 릴리스 노트: 2022년 8월 {#release-notes-aug-22}

아래에는 2022년 8월 릴리스에 포함된 모든 기능이 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별(![별](assets/yellow-star.png))로 표시되는 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

다음 기능은 **2022년 8월 26일**&#x200B;에 단계적으로 롤아웃을 시작했습니다.

## 크로스 채널 오케스트레이션 {#cross-channel-orchestration}

* **[Dynamic Chat에 대해 게시된 모든 대화 상자를 한 번에 활성화/비활성화](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/dialogue-overview.md#disable-enable-all-dialogues){target="_blank"}**: 단추를 눌러 [구성] 페이지에서 게시된 모든 대화 상자를 한 번에 전체적으로 활성화/비활성화합니다.

* **[Dynamic Chat에 대한 사용자 지정 아바타](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/configuration.md#agent-settings){target="_blank"}**: 사용자 지정 챗봇 아바타를 업로드하여 내 브랜드에 맞게 개인화할 수 있습니다.

* **Dynamic Chat에 대한 채팅 트랜스크립트**: 모든 대화에 대한 채팅 트랜스크립트를 보고 각 웹 방문자가 관심 있는 내용에 대해 더 자세한 통찰력을 얻으십시오.

## 차세대 경험

* **Adobe 브랜딩**: 새로운 Adobe Experience Cloud 브랜딩으로 편집자 및 개인 세부 정보 페이지의 모양과 느낌을 업데이트했습니다.

* **이동 대화 상자에 대상 폴더의 폴더 계층 구조 표시**: 각 폴더에 대한 폴더 계층 구조를 보면 자산을 더 쉽게 이동할 수 있으며 잘못된 폴더에 넣을 수 있는 가능성이 줄어듭니다.

* **[차세대 경험에서 업데이트된 Screens](/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md){target="_blank"}**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 경험에서 새로 고친 화면을 추가로 제공합니다.

   * 코드 조각 세부 사항
   * &quot;이미지 및 파일&quot; 세부 정보

>[!NOTE]
>
>예외적으로 마케팅 활동의 프로그램 내에서 자산을 폴더로 이동합니다. 프로그램 내의 폴더에는 중복 이름을 사용할 수 없으므로 이 이동 작업으로 폴더 계층 구조가 표시되지 않습니다.

## Experience Automated {#experience-automation}

* **[셀프 서비스 흐름 단계 - 프로그램 가져오기 개선 사항](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/flow-step-service.md){target="_blank"}**: 이제 동일한 서비스 공급자의 여러 인스턴스를 사용하고 해당 서비스 공급자와 호환되는 흐름 단계가 있는 프로그램을 가져올 수 있는 사용자 지정 흐름 단계로 프로그램 가져오기에 대한 지원이 개선되었습니다.

* **Munchkin - 확장된 링크 추적**: 확장된 웹 동작 집합을 추적하기 위해 Munchkin이 있는 `tel` 및 `mailto` 링크 추적에 대한 지원을 확장합니다.

* **Webhook 사용자 지정 헤더 가시성**: 이제 더 나은 가시성을 위해 Webhook 사용자 지정 헤더가 관리 > Webhooks 탭에 표시됩니다.

* **CAPTCHA**: 들어오는 양식 트래픽을 평가할 때 [reCAPTCHA v3](/help/marketo/product-docs/demand-generation/forms/using-captcha/enable-captcha-in-marketo-forms.md){target="_blank"}을(를) 사용하여 양식 제출의 유효성을 평가합니다. 의심스러운 봇 트래픽을 자동으로 제외, 격리 또는 삭제하는 마케팅 워크플로우를 빌드합니다.

* **양식 승인 권한**: 다른 Design Studio 자산과 함께 양식의 변경 내용을 승인할 수 있는 디자이너를 제어하는 새 권한입니다. 이렇게 하면 다른 디자이너가 승인 권한이 있는 다른 사람이 양식을 검토하지 않고 변경 사항을 양식에 푸시할 수 없습니다.

* **익명 병합 후 캠페인 재생을 항상 수행**: 익명 캠페인 재생이 완료되면 사용자 지정 필드 필터가 안정적으로 작동하도록 캠페인 재생 전에 익명 리드 병합이 발생합니다.

## 마케팅 데이터 환경 {#marketing-data-environment}

* **사용자 지정 개체 &quot;Used By&quot; 필드의 UI 자르기 수정**: 이제 &quot;사용 중&quot;인 사용자 지정 개체 필드를 더 쉽게 식별할 수 있으므로 필요한 경우 사용자 지정 개체에서 필드를 삭제할 수 있습니다.

## API 개선 사항 {#api-enhancements}

* **일괄 프로그램 구성원 추출 API를 위한 새로운 필터링 기능**: 프로그램 구성원 상태, updatedAt, cadence 또는 소진된 콘텐츠별로 필터링하여 추출된 데이터 집합을 구체화합니다.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **[Dynamic Chat과 Sales Insight 통합](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md){target="_blank"}**: Sales Insight 패널에서 Dynamic Chat의 활동을 보고 예상 작업에서 이 새로운 데이터 포인트를 활용하십시오.

## 공지 {#announcements}

**_제품 릴리스 웨비나_**

[2022년 6월 및 8월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_June_August_Release_Webinar_OnDemandPage.html){target="_blank"}
