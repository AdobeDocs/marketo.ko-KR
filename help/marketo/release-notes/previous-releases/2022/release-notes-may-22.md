---
description: 릴리스 노트 - 2022년 5월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2022년 5월
exl-id: f591ab95-5ad8-45fa-8c4e-8e42b5d1359a
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '818'
ht-degree: 0%

---

# 릴리스 노트: 2022년 5월 {#release-notes-may-22}

아래에는 2022년 5월 릴리스에 포함된 모든 기능이 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별(![별](assets/yellow-star.png))로 표시되는 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_**

다음 기능은 **2022년 5월 6일**&#x200B;에 릴리스되기 시작하며, 이후 몇 주 동안 남은 기능의 단계적 롤아웃이 적용됩니다(달리 지정되지 않은 경우).

## 기본 CRM 통합 {#native-crm-integration}

**[기본 Veeva CRM 통합](/help/marketo/product-docs/crm-sync/veeva-crm-sync/understanding-the-veeva-crm-sync.md){target="_blank"}(제한된 가용성)**: 기본 통합을 통해 Veeva CRM과 Marketo Engage 간의 활동을 동기화하여 의료 전문가와의 참여를 향상시키십시오. 이러한 통합을 통해 마케터는 의료 전문가를 위한 보다 개인화되고 원활한 크로스 채널 경험을 만들 수 있습니다. 참여에 관심이 있는 경우 Adobe 계정 팀(계정 관리자)에 문의하십시오.

## 크로스 채널 오케스트레이션 {#cross-channel-orchestration}

**Dynamic Chat에 대한 챗봇 이벤트**: 웹 방문자에 대한 보다 자세한 동작 데이터(예: 페이지 체류 시간, 사이트 체류 시간 및 페이지 스크롤 백분율)를 활용하여 채팅 대화 상자가 표시되는 시기를 정의합니다.

**Dynamic Chat에 대한 PDF 포함**: 채팅 대화 상자에 PDF을 포함시켜 참여를 늘리고 의미 있는 콘텐츠를 공유하며 참여 활동 추적을 통해 콘텐츠 성능을 측정합니다.

**Dynamic Chat에 대한 확장 언어 지원**: 이제 Dynamic Chat 사용자 인터페이스를 프랑스어, 독일어, 일본어, 포르투갈어 및 스페인어로도 사용할 수 있습니다. 이러한 언어로 채팅 대화 상자를 구성할 수도 있습니다.

**Dynamic Chat에 대한 URL 제외**: 타깃팅 기준에서 특정 URL을 제외하는 기능으로 웹 페이지 Dynamic Chat 중 어떤 페이지에 표시되는지 제어합니다.

**[전자 메일 보트 활동 필터링 개선 사항](/help/marketo/product-docs/administration/email-setup/filtering-email-bot-activity.md){target="_blank"}**: 기존 IAB 목록 일치 식별뿐 아니라 숨겨진 링크 사용자 에이전트 또는 IP 및 근접 패턴을 기반으로 보트 동작을 식별하는 기능을 사용하여 데이터베이스의 상태를 계속 보호합니다. 각 유형에 대해 식별된 보트 활동의 수를 이해할 수 있는 보트 활동 통계를 봅니다.

**[전자 메일 추적 링크에 대한 STS 헤더](/help/marketo/product-docs/administration/settings/email-tracking-link-headers.md){target="_blank"}**: 추적된 링크에 대한 트래픽이 항상 안전하도록 보안 전송 보안 헤더를 적용하는 기능으로 보안 모범 사례를 충족합니다.

## 차세대 경험 {#modern-ux}

**전환 스위치를 차세대 환경으로 기본 설정**: 전환 스위치는 사용 가능한 모든 화면에서 새로운 환경으로 기본 설정되므로 사용자가 업데이트된 디자인과 유용성 개선 사항을 쉽게 확인할 수 있습니다.

**차세대 환경에서 업데이트된 화면**:

Design Studio 내에서 차세대 환경으로 제공되는 이메일 템플릿 세부 사항 보기를 통해 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공합니다.

## Experience Automated {#experience-automation}

**셀프 서비스 흐름 단계(연속 베타)**: 스마트 캠페인에 사용할 사용자 지정 흐름 단계를 작성하는 기능을 사용하여 Marketo Engage과 스택의 나머지 부분 간의 연결을 확장합니다. Marketo Engage 사용자와 파트너 모두 이 기능을 활용하여 트리거, 일괄 처리 및 실행 가능한 캠페인에서 외부 웹 서비스를 사용할 수 있습니다(트리거 캠페인에만 사용할 수 있는 웹 후크와 대조적으로).

## API 개선 사항 {#api-enhancements}

* **CRM 사용 구독에 대한 확장된 API 액세스**: 사용자가 Marketo Engage에서 회사, 기회 및 영업 직원을 검색할 수 있도록 CRM 동기화를 사용하도록 설정한 구독에 대한 API 액세스를 확장하고 있습니다.
* **Forms에서 &quot;숨겨진&quot; 데이터 형식 지원**: API를 통해 숨겨진 양식 필드를 관리할 수 있는 기능을 제공합니다.
* **규칙을 통해 isNot Form에 대한 여러 비교 값 지원**: 다른 필드의 값이 지정된 목록에 있는 값 중 하나가 아닌지 여부를 기준으로 양식 필드의 가시성을 관리합니다.
* **별도로 선택 목록에서 표시 값과 제출된 값을 설정할 수 있도록 허용**: 필드에 표시 값과 제출된 값을 별도로 설정합니다. 예를 들어 호텔 이름을 표시하지만 내부 ID를 백엔드에 제출합니다.
* **전자 메일 만들기 또는 업데이트 시 열기 추적을 사용하지 않도록 설정할 수 있도록 허용**: 열기 추적을 사용하지 않는 전자 메일을 만듭니다.

## 공지 {#announcements}

**전자 메일 확인 및 고유성**: 4월부터 전자 메일 확인 롤아웃이 시작됩니다. 이때 Marketo Engage 사용자 이메일 주소에는 확인 및 고유성이 필요합니다(API 전용 사용자에게는 적용되지 않음). 이메일 확인을 통해 구독이 활성화되면 디렉터리 서비스 인증된 사용자의 이메일이 자동으로 확인됩니다.

&quot;사용자 초대 대화 상자에서 로그인&quot; 기능을 사용하거나 여러 사용자와 연결된 단일 이메일이 있는 가입에 대한 이메일 확인은 5월 릴리스와 일치합니다. 여러 사용자와 연결된 하나의 이메일이 있는 구독은 이메일 확인을 통해 활성화되며 이러한 사용자가 충돌을 해결하고 사용자당 고유한 이메일을 사용해야 합니다. &#39;사용자 초대 대화 상자에서 로그인&#39; 기능을 활성화하면 이 기능을 통해 초대된 사용자의 이메일 주소가 고유해야 합니다. 이 기능을 통해 초대된 API 전용 사용자의 경우 이메일 주소가 고유할 필요가 없습니다.

**보관 폴더 동작 변경**: 이 릴리스에서는 보관 폴더에 새 자산을 만드는 기능을 트리 컨텍스트 메뉴에서 더 이상 사용할 수 없습니다. 새 에셋을 만들기 위한 메뉴 옵션은 모든 에셋에 대해 숨겨집니다. [자세히 알아보기](https://nation.marketo.com/t5/product-discussions/archive-folder-change-in-may-2022-release/m-p/324369#M183235){target="_blank"}.

**_제품 릴리스 웨비나_**

[2022년 3월 및 5월 Marketo Engage 릴리스 웨비나](https://engage.marketo.com/2022_March_May_Release_Webinar_DemandPage.html){target="_blank"}
