---
unique-page-id: 14352475
description: Activity History에 Sales Connect 이벤트 필드 설치 - Marketo 문서 - 제품 설명서
title: Activity History에 Sales Connect 이벤트 필드 설치
exl-id: c1bdb5a6-04f0-4579-84b6-33f4a301128f
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 0%

---

# Activity History에 Sales Connect 이벤트 필드 설치 {#install-sales-connect-event-fields-on-activity-history}

Enterprise 패키지를 Salesforce에 설치하면 Sales Connect 이벤트 필드를 활동 기록 섹션에 설치할 수 있습니다. Sales Connect 이벤트 필드에는 보기, 클릭, 캠페인 등의 정보가 포함됩니다. Salesforce로 직접 가져온 이메일에 대한 정보를 보유할 수 있습니다.

이러한 단계를 수행할 때 Salesforce 관리자에게 문의하십시오. 이 예제에서는 필드에 필드를 설치합니다 **리드 페이지 레이아웃**. 연락처, 계정 및 기회 페이지 레이아웃에 필드를 설치할 수도 있습니다. 계정 및 Opportunity에 전자 메일을 기록할 때 연락처 역할로 전자 메일을 보낼 담당자가 필요합니다.

1. 클릭 **설정**.
1. 클릭 **사용자 지정**.
1. 클릭 **리드**.
1. 클릭 **페이지 레이아웃**.
1. 클릭 **편집** 변경할 페이지 레이아웃 옆에 있습니다.

   >[!NOTE]
   >
   >Sales Connect에서 일부 페이지 레이아웃을 설치하지만, 기본 페이지 레이아웃이 이미 있는 경우 팀에서 사용하는 페이지 레이아웃이 설치될 것입니다. 사용하지 않으려면 Sales Connect 페이지 레이아웃을 삭제할 수 있습니다.

1. 활동 내역 섹션으로 스크롤합니다.
1. 편집할 렌치를 클릭합니다.
1. Activity History 섹션에 포함할 Sales Connect 필드를 선택합니다. 여기에 Sales Connect 필드가 표시되지 않으면 잘못된 Salesforce 패키지를 설치했을 수 있습니다.
1. 클릭 **추가** 원하는 필드를 위로 이동하려면 다음을 수행하십시오.
1. 클릭 **확인**.
1. 클릭 **저장**.

   이제 사용자는 Salesforce에서 이메일에 대한 중요한 정보와 업데이트를 볼 수 있습니다.
