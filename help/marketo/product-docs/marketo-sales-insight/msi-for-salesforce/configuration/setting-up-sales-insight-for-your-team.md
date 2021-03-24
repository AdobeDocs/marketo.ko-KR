---
description: 팀에 대한 Sales Insight 설정 - Marketing To Docs - 제품 설명서
title: 팀에 대한 Sales Insight 설정
translation-type: tm+mt
source-git-commit: ed9399396c82a3b2fb93c83ffdaa1dc7b0827306
workflow-type: tm+mt
source-wordcount: '439'
ht-degree: 0%

---


# 팀의 Sales Insight 설정 {#setting-up-sales-insight-for-your-team}

다른 프로파일에 대한 액세스를 제거하는 동안 Sales Insight에 액세스할 수 있는 프로필을 만드는 방법을 설명합니다. 이것은 이미 [Sales Insight AppExchange 패키지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)를 설치한 사용자를 위한 것입니다.

## 영업 인사이트에 대한 새 프로필 만들기 {#create-a-new-profile-for-sales-insight}

Sales Insight 사용자를 위한 전용 프로필이 있으면 이 단계를 건너뛸 수 있습니다.

1. Salesforce에서 설정 페이지로 이동합니다.

1. 빠른 찾기에서 프로필을 검색하고 **프로필** 옵션을 선택합니다.

1. 페이지 맨 위에 있는 **새 프로필** 단추를 클릭합니다.

1. 복제할 프로파일을 선택하고 이름을 지정합니다(예:Sales Insight 사용자).

1. 완료되면 **저장**&#x200B;을 클릭합니다.

## 영업 통찰력 권한 추가 {#add-sales-insight-permissions}

1. 프로필 목록으로 돌아갑니다.

1. 방금 만든 새 프로필(또는 Sales Insight 액세스 권한을 부여할 다른 기존 프로필)에 대한 **편집** 링크를 클릭합니다.

1. 편집 페이지에서 몇 가지 설정을 변경해야 합니다.

   **Sales Insight에 액세스할 수 있는 프로필의 경우**:

   * 사용자 지정 앱 설정에서 마케팅을 선택하여 마케팅 앱을 표시합니다.
   * 탭 설정에서 마케팅 탭을 기본값으로 변경
   * 사용자 지정 개체 권한에서 Marketing To Sales Insight 구성에서 읽기, 만들기, 편집 및 삭제를 선택합니다(사용자가 일반적으로 관리자에 사용됨).

   **Sales Insight에 액세스할 수 없는 프로필의 경우**:

   * 사용자 지정 앱 설정에서 마케팅을 선택 취소하여 마케팅 앱 숨기기
   * 탭 설정에서 마케팅 탭을 탭 숨김으로 변경합니다.
   * 사용자 지정 개체 권한에서 Marketing To Sales Insight 구성에서 읽기, 만들기, 편집 및 삭제를 선택 취소합니다


1. 완료되면 **저장**&#x200B;을 클릭합니다.

## 영업 인사이트를 위한 레이아웃 만들기 {#create-layout-for-sales-insight}

1. 설정 페이지로 이동한 다음 **앱 설정** > **사용자 지정** > **리드** > **페이지 레이아웃**&#x200B;을 클릭합니다. 그런 다음 **새로 만들기** 단추를 클릭합니다.

1. 원하는 레이아웃을 복제하고 레이아웃에 적절한 이름을 지정합니다(예:Sales Insight 레이아웃 참조).

1. 완료되면 **저장**&#x200B;을 클릭합니다.

1. 연락처, 기회 및 계정의 페이지 레이아웃에 대해 다음 단계를 반복합니다.

## 레이아웃 {#assign-profile-to-layout}에 프로필 할당

1. 페이지 레이아웃 섹션으로 돌아가서 **페이지 레이아웃 할당** 단추를 클릭합니다.

1. **할당 편집**&#x200B;을 선택합니다.

1. 목록에서 Sales Insight 프로필을 선택한 다음 &quot;페이지 레이아웃 선택&quot; 드롭다운에서 Sales Insight 레이아웃을 선택합니다.

1. 완료되면 **저장**&#x200B;을 클릭합니다.

1. 연락처, 기회 및 계정의 페이지 레이아웃에 대해 다음 단계를 반복합니다.

## 기타 변경 사항 {#other-changes}

다음은 Sales Insight 항목이 표시될 수 있는 다른 장소입니다. 프로필을 사용하여 액세스를 제한할 수 없으므로 이 파일을 완전히 제거해야 합니다.

* 연락처, 리드 및 계정에 대한 검색 레이아웃에서 판매 통찰력 단추 제거
* 연락처 및 리드 목록에서 판매 통찰력 열 제거
