---
description: 현재 릴리스 노트 - Marketo 문서 - 제품 설명서
title: 현재 릴리스 노트
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
source-git-commit: e489ab3e5e4f1d6628db525e53207d229b50a92b
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 릴리스 노트: 2022년 5월 {#release-notes-may-22}

아래에는 2022년 5월 릴리스에 포함된 모든 기능이 있습니다. 기능을 사용할 수 있는지 Adobe Marketo Engage 버전을 확인하십시오.

>[!AVAILABILITY]
>
>별로 표시된 기능(![별](assets/yellow-star.png))은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은에서 릴리스되기 시작합니다 **2022년 5월 6일**- 후속 주 동안 나머지 기능에 대한 단계적 롤아웃을 사용합니다(별도로 지정하지 않는 경우).

## 기본 CRM 통합 {#native-crm-integration}

**[기본 Veva CRM 통합](/help/marketo/product-docs/crm-sync/veeva-crm-sync/understanding-the-veeva-crm-sync.md){target=&quot;_blank&quot;}(사용 가능 제한)**: 기본 통합을 통해 Veeva CRM과 Marketo Engage 간 활동을 동기화하여 의료 전문가와의 참여를 개선할 수 있습니다. 이러한 통합을 통해 마케터는 의료 전문가를 위한 보다 개인화되고 원활한 크로스 채널 경험을 만들 수 있습니다. 참여하는 데 관심이 있는 경우 고객 성공 관리자에게 문의하십시오.

## 크로스 채널 오케스트레이션 {#cross-channel-orchestration}

**Dynamic Chat에 대한 Chatbot 이벤트**: 페이지 체류 시간, 사이트 시간, 페이지 스크롤 비율 등 웹 방문자에 대한 보다 자세한 동작 데이터를 활용하여 채팅 대화 상자가 표시되는 시점을 정의합니다.

**동적 채팅을 위한 PDF 포함**: 참여 활동 추적을 통해 PDF을 채팅 대화 상자에 포함하고 컨텐츠 성능을 측정하여 참여를 늘리고 의미 있는 컨텐츠를 공유합니다.

**Dynamic Chat를 위한 언어 지원 확장**: 이제 Dynamic Chat 사용자 인터페이스를 프랑스어, 독일어, 일본어, 포르투갈어 및 스페인어로 사용할 수 있습니다. 대화 상자는 이러한 언어로 구성할 수도 있습니다.

**다이내믹 채팅용 URL 제외**: 타깃팅 기준에서 특정 URL을 제외하는 기능을 사용하여 동적 채팅이 표시되는 웹 페이지를 제어합니다.

**[전자 메일 보트 활동 필터링 개선 사항](/help/marketo/product-docs/administration/email-setup/filtering-email-bot-activity.md){target=&quot;_blank&quot;}**: 기존 IAB 목록 일치 식별 외에도 숨겨진 링크 사용자 에이전트 또는 IP 및 근접 패턴을 기반으로 보트 동작을 식별하는 기능을 사용하여 데이터베이스의 상태를 계속 보호합니다. 각 유형에 대해 식별된 보트 활동 수를 이해할 수 있도록 해주는 보트 활동 상태를 봅니다.

**[전자 메일 추적 링크에 대한 STS 헤더](/help/marketo/product-docs/administration/settings/email-tracking-link-headers.md){target=&quot;_blank&quot;}**: 보안 모범 사례를 충족하여 추적된 링크에 대한 트래픽이 항상 안전하도록 보안 전송 보안 헤더를 적용하는 기능을 제공합니다.

## 차세대 경험 {#next-generation-experience}

**다음 세대 경험으로 기본 전환 전환**: 전환 스위치는 기본적으로 사용 가능한 모든 화면에서 새 경험으로 설정되므로 사용자가 업데이트된 디자인과 유용성 개선 사항을 보다 쉽게 찾을 수 있습니다.

**차세대 경험에서 화면이 업데이트되었습니다.**:

Adobe는 Design Studio의 차세대 환경에서 전자 메일 템플릿 세부 사항 보기를 제공하여 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공합니다.

## Experience Automation {#experience-automation}

**셀프서비스 흐름 단계(계속 베타)**: 스마트 캠페인에서 사용할 사용자 지정된 흐름 단계를 작성하는 기능을 사용하여 Marketo Engage과 나머지 스택 간의 연결을 확장합니다. Marketo Engage 사용자와 파트너는 모두 이 기능을 활용하여 트리거, 배치 및 실행 캠페인에서 외부 웹 서비스를 사용할 수 있도록 할 수 있습니다(트리거 캠페인에서만 사용할 수 있는 웹 후크와는 대조적으로).

## API 개선 사항 {#api-enhancements}

* **CRM 지원 구독에 대한 API 액세스 권한 확장**: 사용자가 Marketo Engage에서 회사, 기회 및 영업자를 검색할 수 있도록 CRM 동기화가 활성화된 가입에 대한 API 액세스를 확장하고 있습니다.
* **Forms에서 &quot;숨겨진&quot; 데이터 유형 지원**: API를 통해 숨겨진 양식 필드를 관리하는 기능을 제공합니다.
* **규칙을 통해 isNot Form에 대한 여러 비교 값 지원**: 다른 필드의 값이 지정된 목록의 값 중 하나가 아닌지 여부를 기준으로 양식 필드의 표시 여부를 관리합니다.
* **별도로 목록 선택에서 표시 및 제출된 값 설정 허용**: 필드에 표시 값과 제출된 값을 별도로 설정합니다. 예를 들어, 호텔 이름을 표시하지만 내부 ID를 백엔드에 제출합니다.
* **이메일 만들기 또는 업데이트 시 열기 추적 비활성화 설정 허용**: 열기 추적 기능이 비활성화되어 있는 이메일을 만듭니다.

## 공지 {#announcements}

**이메일 확인 및 고유성**: 4월부터 이메일 확인 롤아웃을 시작합니다. 이때 Marketo Engage 사용자 이메일 주소는 확인 및 고유성이 필요합니다(API 전용 사용자에게는 적용되지 않음). Directory Service 인증된 사용자는 이메일 확인을 통해 구독을 활성화하면 자동으로 이메일이 확인됩니다.

&quot;사용자 초대 대화 상자에 로그인&quot; 기능을 사용하거나 여러 사용자와 연결된 단일 이메일이 있는 가입에 대한 이메일 확인은 5월 릴리스와 일치합니다. 여러 사용자와 연결된 단일 이메일이 있는 가입은 이메일 확인을 통해 활성화되며 이러한 사용자가 충돌을 해결하고 사용자당 고유한 이메일을 사용해야 합니다. &#39;사용자 초대 대화 상자에 로그인&#39; 기능이 활성화되면 이 기능을 통해 초대된 사용자는 고유한 이메일 주소를 가져야 합니다. 이 기능을 통해 초대된 API 전용 사용자의 경우 이메일 주소가 고유할 필요가 없습니다.

**아카이브 폴더 동작 변경**: 이 릴리스에서는 아카이브 폴더에서 새 자산을 생성하는 기능을 트리 컨텍스트 메뉴에서 더 이상 사용할 수 없습니다. 새 자산을 만들기 위한 메뉴 옵션은 모든 자산에 대해 숨겨집니다. [여기에서 추가 정보](https://nation.marketo.com/t5/product-discussions/archive-folder-change-in-may-2022-release/m-p/324369#M183235){target=&quot;_blank&quot;}.

**_제품 릴리스 웨비나_**

2022년 5월 11일, 오전 9시/동부 시간 오후 12시에 참가하십시오. [라이브 웨비나](https://engage.marketo.com/2022_March_May_Release_Webinar_RegistrationPage.html)제품 팀에서 호스팅하는 {target=&quot;_blank&quot;}에서 최신 제품 혁신 내용을 모두 사용하는 방법을 배울 수 있습니다.
