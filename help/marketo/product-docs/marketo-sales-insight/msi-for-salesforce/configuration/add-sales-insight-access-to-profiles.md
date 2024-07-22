---
description: 프로필에 Sales Insight 액세스 추가 - Marketo 문서 - 제품 설명서
title: 프로필에 Sales Insight 액세스 추가
exl-id: 269f9093-f530-4e3b-aac7-e317976cf0f0
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 0%

---

# 프로필에 Sales Insight 액세스 추가 {#add-sales-insight-access-to-profiles}

다른 프로필에 대한 액세스를 제거하면서 Sales Insight에 액세스할 수 있는 프로필을 만드는 방법은 다음과 같습니다. 이미 [Sales Insight AppExchange 패키지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}를 설치한 사용자를 위한 것입니다.

>[!IMPORTANT]
>
>이전에 모든 프로필에 대한 Sales Insight 액세스 권한을 부여한 경우, 이 권한 집합을 사용하려면 [프로필 수준 액세스 권한을 제거](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md){target="_blank"}해야 합니다.

## Sales Insight에 대한 새 프로필 만들기 {#create-a-new-profile-for-sales-insight}

Sales Insight 사용자에 대한 전용 프로필이 있는 경우 이 단계를 건너뛸 수 있습니다.

1. Salesforce에서 설정 페이지로 이동합니다.

1. 빠른 찾기에서 프로필을 검색하고 **프로필** 옵션을 선택합니다.

1. 페이지 상단의 **새 프로필** 단추를 클릭합니다.

1. 복제할 프로필을 선택하고 이름을 지정합니다(예: Sales Insight User).

1. 완료되면 **저장**&#x200B;을 클릭합니다.

## Sales Insight 권한 추가 {#add-sales-insight-permissions}

1. 프로필 목록으로 돌아갑니다.

1. 방금 만든 새 프로필(또는 Sales Insight에 액세스 권한을 부여하려는 기존 프로필)에 대한 **편집** 링크를 클릭합니다.

1. 편집 페이지에서 몇 가지 설정을 변경해야 합니다.

   **Sales Insight에 액세스할 수 있는 프로필**:

   * 탭 설정에서 Marketo 탭을 기본값 설정으로 변경합니다.
   * 사용자 지정 개체 권한에서 Marketo Sales Insight Config에 대한 읽기, 만들기, 편집 및 삭제를 선택합니다(사용자가 구성 설정에 액세스할 수 있어야 하는 경우 - 일반적으로 관리자에 사용).

   **Sales Insight에 액세스할 수 없는 프로필**:

   * 탭 설정에서 Marketo 탭을 탭 숨김으로 변경합니다
   * 사용자 지정 개체 권한에서 Marketo Sales Insight Config의 읽기, 만들기, 편집 및 삭제 선택을 취소합니다

1. 완료되면 **저장**&#x200B;을 클릭합니다.

## Sales Insight용 레이아웃 만들기 {#create-layout-for-sales-insight}

1. 설정 페이지로 이동한 다음 **앱 설정** > **사용자 지정** > **리드** > **페이지 레이아웃**&#x200B;을 클릭합니다. **새로 만들기** 단추를 클릭합니다.

1. 선택한 레이아웃을 복제하고 레이아웃에 적절한 이름을 지정합니다(예: Sales Insight Layout).

1. 완료되면 **저장**&#x200B;을 클릭합니다.

1. 연락처, 기회 및 거래처의 페이지 레이아웃에 대해 이 단계를 반복합니다.

## 레이아웃에 프로필 할당 {#assign-profile-to-layout}

1. 페이지 레이아웃 섹션으로 돌아가서 **페이지 레이아웃 할당** 단추를 클릭합니다.

1. **할당 편집**&#x200B;을 선택합니다.

1. 목록에서 Sales Insight 프로필을 선택한 다음 &quot;페이지 레이아웃 선택&quot; 드롭다운에서 Sales Insight 레이아웃을 선택합니다.

1. 완료되면 **저장**&#x200B;을 클릭합니다.

1. 연락처, 기회 및 거래처의 페이지 레이아웃에 대해 이 단계를 반복합니다.

## 기타 변경 사항 {#other-changes}

다음은 Sales Insight 항목이 나타날 수 있는 몇 가지 다른 위치입니다. 프로필을 사용하여 액세스 권한을 제한할 수 없으므로 즉시 제거해야 합니다.

* 담당자, 가망 고객 및 거래처에 대한 검색 레이아웃에서 Sales Insight 버튼 제거
* 연락처 및 잠재 고객 목록에서 Sales Insight 열 제거
