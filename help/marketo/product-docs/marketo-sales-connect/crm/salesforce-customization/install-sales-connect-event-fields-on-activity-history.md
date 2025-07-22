---
unique-page-id: 14352475
description: 활동 내역 - Marketo 문서 - 제품 설명서에 Sales Connect 이벤트 필드 설치
title: 활동 내역에 Sales Connect 이벤트 필드 설치
exl-id: c1bdb5a6-04f0-4579-84b6-33f4a301128f
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 2%

---

# 활동 내역에 Sales Connect 이벤트 필드 설치 {#install-sales-connect-event-fields-on-activity-history}

Enterprise 패키지를 [!DNL Salesforce]에 설치한 후에는 [!UICONTROL Sales Connect] 이벤트 필드를 활동 기록 섹션에 설치할 수 있습니다. [!UICONTROL Sales Connect] 이벤트 필드에는 보기, 클릭 수 및 캠페인과 같은 정보가 포함됩니다. 이를 통해 전자 메일에 대한 정보를 [!DNL Salesforce]&#x200B;(으)로 직접 가져올 수 있습니다.

이러한 단계를 수행할 때는 [!DNL Salesforce] 관리자와 협력해야 합니다. 이 예제에서는 필드를 **리드 페이지 레이아웃**&#x200B;에 설치합니다. 연락처, 계정 및 영업 기회 페이지 레이아웃에 필드를 설치할 수도 있습니다. 계정 및 영업 기회에 전자 메일을 기록할 때 전자 메일을 보내는 연락처가 연락처 역할로 연결되어 있어야 합니다.

1. **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.
1. **[!UICONTROL Customize]**&#x200B;을(를) 클릭합니다.
1. **[!UICONTROL Leads]**&#x200B;을(를) 클릭합니다.
1. **[!UICONTROL Page Layouts]**&#x200B;을(를) 클릭합니다.
1. 변경할 페이지 레이아웃 옆의 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   >[!NOTE]
   >
   >[!DNL Sales Connect]이(가) 일부 페이지 레이아웃을 설치하지만 팀에서 사용 중인 기본 레이아웃이 이미 있는 경우 해당 레이아웃은 설치할 수 있습니다. [!DNL Sales Connect] 페이지 레이아웃을 사용하지 않으려면 삭제할 수 있습니다.

1. [!UICONTROL Activity History] 섹션까지 아래로 스크롤합니다.
1. 렌치를 클릭하여 편집합니다.
1. [!UICONTROL Sales Connect] 섹션에 포함할 [!UICONTROL Activity History] 필드를 선택하십시오. 여기에 [!UICONTROL Sales Connect] 필드가 표시되지 않으면 잘못된 [!DNL Salesforce] 패키지를 설치했을 수 있습니다.
1. 원하는 필드를 이동하려면 **[!UICONTROL Add]**&#x200B;을(를) 클릭하십시오.
1. **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.
1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   이제 사용자는 [!DNL Salesforce]에서 전자 메일에 대한 중요한 정보와 업데이트를 볼 수 있습니다!
