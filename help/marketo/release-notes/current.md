---
description: 현재 릴리스 노트 - Marketo 문서 - 제품 설명서
title: 현재 릴리스 노트
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
source-git-commit: 4f79308986a323c248f55c32f0d1db0d9811e6b3
workflow-type: tm+mt
source-wordcount: '558'
ht-degree: 0%

---

# 릴리스 노트: 2022년 8월 {#release-notes-aug-22}

아래에는 2022년 8월 릴리스에 포함된 모든 기능이 포함되어 있습니다. 기능을 사용할 수 있는지 Adobe Marketo Engage 버전을 확인하십시오.

>[!AVAILABILITY]
>
>별로 표시된 기능(![별](assets/yellow-star.png))은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

다음 기능은에서 릴리스되기 시작합니다 **2022년 8월 26일**- 후속 주 동안 나머지 기능에 대한 단계적 롤아웃을 사용합니다(별도로 지정하지 않는 경우). 릴리스 기능과 정확한 날짜는 변경될 수 있습니다.

## 크로스 채널 오케스트레이션 {#cross-channel-orchestration}

* **[다이내믹 채팅을 위해 게시된 모든 대화 상자를 한 번에 활성화/비활성화](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/dialogue-overview.md#disable-enable-all-dialogues){target=&quot;_blank&quot;}**: 구성 페이지에서 단추를 눌러 게시된 모든 대화 상자를 한 번에 전체적으로 활성화/비활성화합니다.

* **동적 채팅에 대한 사용자 지정 아바타**: 사용자 지정 차트 보트 아바타를 업로드하여 브랜드에 개인화할 수 있습니다.

* **동적 채팅의 채팅 스크립트**: 모든 대화의 채팅 스크립트를 보고 각 웹 방문자가 관심이 있는 내용에 대한 심층적인 통찰력을 얻을 수 있습니다.

## 차세대 경험

* **Adobe 브랜딩**: 새로운 Adobe Experience Cloud 브랜딩으로 편집자와 개인 세부 사항 페이지의 모양과 느낌을 업데이트했습니다.

* **이동 대화 상자에 대상 폴더의 폴더 계층 표시**: 각 폴더에 대한 폴더 계층 구조를 보면 자산을 쉽게 이동하고 잘못된 폴더에 넣을 가능성이 줄어듭니다.

* **차세대 경험에서 업데이트된 화면**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 환경에서 새로 고친 추가 화면을 제공하고 있습니다.

   * 코드 조각 세부 사항
   * &quot;이미지 및 파일&quot; 세부 정보

>[!NOTE]
>
>마케팅 활동의 프로그램 내에서 자산을 폴더로 이동하는 것은 예외입니다. 프로그램 내의 폴더에 중복 이름을 사용할 수 없으므로 이 이동 작업은 폴더 계층 구조를 표시하지 않습니다.

## Experience Automation {#experience-automation}

* **셀프 서비스 플로우 단계 - 프로그램 가져오기 개선 사항**: 이제 동일한 서비스 공급자의 여러 인스턴스를 사용할 수 있고 해당 서비스 공급자와 호환되는 플로우 단계가 있는 프로그램을 가져올 수 있는 사용자 지정 흐름 단계를 통해 프로그램 가져오기에 대한 지원이 개선되었습니다.

* **Munchkin - 확장된 링크 추적**: 추적 지원 확장 `tel` 및 `mailto` 확장된 웹 동작 세트를 추적하기 위해 Munchkin과 연결합니다.

* **Webhook 사용자 지정 헤더 가시성**: 이제 Webhook 사용자 지정 헤더가 관리 > Webhooks 탭에 표시되므로 더 나은 가시성을 얻을 수 있습니다.

* **CAPTCHA**: reCAPTCHA v3를 사용하여 양식 제출의 유효성을 평가하여 들어오는 양식 트래픽에 대해 점수를 지정합니다. 의심스러운 보트 트래픽을 자동으로 제외, 격리 또는 삭제하기 위한 마케팅 워크플로우를 작성합니다.

* **양식 승인 권한**: 다른 Design Studio 자산과 함께 양식에 대한 변경 사항을 승인할 수 있는 디자이너를 제어하는 새로운 권한. 이렇게 하면 다른 디자이너가 양식을 검토할 수 있는 승인 권한이 없는 상태에서 변경 내용을 양식에 푸시할 수 없습니다.

* **익명 병합 후 항상 캠페인 재생 수행**: 익명 리드 병합은 캠페인 재생 전에 발생하므로 익명 캠페인 재생이 완료되면 사용자 지정 필드 필터가 안정적으로 동작합니다.

## 마케팅 데이터 환경 {#marketing-data-environment}

* **사용자 지정 개체 &quot;사용 기준&quot; 필드의 UI 잘림 수정**: 이제 &quot;사용 중&quot;인 사용자 지정 개체 필드를 더 쉽게 식별할 수 있으므로 필요한 경우 사용자 지정 개체에서 필드를 삭제할 수 있습니다.

## API 개선 사항 {#api-enhancements}

* **벌크 프로그램 멤버 추출 API에 대한 새로운 필터링 기능**: 프로그램 멤버십 상태, updatedAt, cadence 또는 고갈된 컨텐츠별로 필터링하여 추출된 데이터 세트를 세분화합니다.

## Sales Insight {#sales-insight}

![(별)](assets/yellow-star.png)

* **Dynamic Chat와 Sales Insight 통합**: Sales Insight 패널에서 Dynamic Chat에서 활동을 보고 이 새로운 데이터 포인트를 잠재 고객 대상 작업에서 활용할 수 있습니다.

## 공지 {#announcements}

**_제품 릴리스 웨비나_**

[2022년 6월 및 8월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_June_August_Release_Webinar_OnDemandPage.html){target=&quot;_blank&quot;}
