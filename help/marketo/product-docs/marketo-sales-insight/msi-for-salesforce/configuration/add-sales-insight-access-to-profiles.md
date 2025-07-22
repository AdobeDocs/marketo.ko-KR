---
description: 프로필에 Sales Insight 액세스 추가 - Marketo 문서 - 제품 설명서
title: 프로필에 Sales Insight 액세스 추가
exl-id: 269f9093-f530-4e3b-aac7-e317976cf0f0
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 0%

---

# 프로필에 [!DNL Sales Insight] 액세스 추가 {#add-sales-insight-access-to-profiles}

다른 프로필에 대한 액세스를 제거하면서 [!DNL Sales Insight]에 대한 액세스 권한을 가진 프로필을 만드는 방법은 다음과 같습니다. 이미 [[!DNL Sales Insight] AppExchange 패키지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}를 설치한 사용자를 위한 것입니다.

>[!IMPORTANT]
>
>이전에 모든 프로필에 [!DNL Sales Insight] 액세스 권한을 부여한 경우 이 권한 집합을 사용하려면 [프로필 수준 액세스 권한을 제거](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md){target="_blank"}해야 합니다.

## [!DNL Sales Insight]에 대한 새 프로필 만들기 {#create-a-new-profile-for-sales-insight}

[!DNL Sales Insight] 사용자에 대한 전용 프로필이 있는 경우 이 단계를 건너뛸 수 있습니다.

1. [!DNL Salesforce]에서 설정 페이지로 이동합니다.

1. [빠른 찾기]에서 프로필을 검색하고 **[!UICONTROL Profile]** 옵션을 선택합니다.

1. 페이지 상단의 **[!UICONTROL New Profile]** 단추를 클릭합니다.

1. 복제할 프로필을 선택하고 이름을 지정합니다(예: Sales Insight 사용자).

1. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

## [!DNL Sales Insight] 권한 추가 {#add-sales-insight-permissions}

1. 프로필 목록으로 돌아갑니다.

1. 방금 만든 새 프로필(또는 **[!UICONTROL Edit]**&#x200B;에게 액세스 권한을 부여할 다른 기존 프로필)에 대한 [!DNL Sales Insight] 링크를 클릭합니다.

1. 편집 페이지에서 몇 가지 설정을 변경해야 합니다.

   **액세스가 허용된 프로필의 경우[!DNL Sales Insight]**:

   * 탭 설정에서 Marketo 탭을 기본값 설정으로 변경합니다.
   * 사용자 지정 개체 권한에서 [!DNL Marketo Sales Insight] 구성에 대한 읽기, 만들기, 편집 및 삭제를 선택합니다(사용자가 구성 설정에 액세스할 수 있어야 하는 경우 - 일반적으로 관리자를 위해 사용됨).

   **에 액세스할 수 없는 프로필의 경우[!DNL Sales Insight]**:

   * 탭 설정에서 Marketo 탭을 탭 숨김으로 변경합니다
   * 사용자 지정 개체 권한에서 [!DNL Marketo Sales Insight] 구성에서 읽기, 만들기, 편집 및 삭제 선택을 취소합니다

1. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

## [!DNL Sales Insight]에 대한 레이아웃 만들기 {#create-layout-for-sales-insight}

1. 설정 페이지로 이동한 다음 **[!UICONTROL App Setup]** > **[!UICONTROL Customize]** > **[!UICONTROL Leads]** > **[!UICONTROL Page Layouts]**&#x200B;을(를) 클릭합니다. **[!UICONTROL New]** 단추를 클릭합니다.

1. 선택한 레이아웃을 복제하고 레이아웃에 적절한 이름을 지정합니다(예: Sales Insight Layout).

1. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

1. [!UICONTROL Contacts], [!UICONTROL Opportunities] 및 [!UICONTROL Accounts] 페이지 레이아웃에 대해 이 단계를 반복합니다.

## 레이아웃에 프로필 할당 {#assign-profile-to-layout}

1. [페이지 레이아웃] 섹션으로 돌아가서 **[!UICONTROL Page Layout Assignment]** 단추를 클릭합니다.

1. **[!UICONTROL Edit Assignment]**&#x200B;를 선택합니다.

1. 목록에서 [!DNL Sales Insight] 프로필을 선택한 다음 &quot;[!DNL Sales insight]&quot; 드롭다운에서 [!UICONTROL Select Page Layout] 레이아웃을 선택합니다.

1. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

1. [!UICONTROL Contacts], [!UICONTROL Opportunities] 및 [!UICONTROL Accounts] 페이지 레이아웃에 대해 이 단계를 반복합니다.

## 기타 변경 사항 {#other-changes}

[!DNL Sales Insight]개 항목이 나타날 수 있는 다른 위치도 있습니다. 프로필을 사용하여 액세스 권한을 제한할 수 없으므로 즉시 제거해야 합니다.

* [!DNL Sales Insight], [!UICONTROL Contacts] 및 [!UICONTROL Leads]의 검색 레이아웃에서 [!UICONTROL Accounts] 단추 제거
* 연락처 및 잠재 고객 목록에서 [!DNL Sales Insight]개 열 제거
