---
description: 프로필에 Sales Insight Access 추가 - Marketo 문서 - 제품 설명서
title: 프로필에 Sales Insight Access 추가
exl-id: 269f9093-f530-4e3b-aac7-e317976cf0f0
source-git-commit: 5c4bce6ab6801b861f70722b6782df34f96fed10
workflow-type: tm+mt
source-wordcount: '438'
ht-degree: 0%

---

# 프로필에 Sales Insight Access 추가 {#add-sales-insight-access-to-profiles}

다음은 다른 프로필에 대한 액세스를 제거하면서 Sales Insight에 액세스할 수 있는 프로필을 만드는 방법입니다. 이미 을 설치한 사용자를 위한 것입니다. [Sales Insight AppExchange 패키지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target=&quot;_blank&quot;}.

>[!IMPORTANT]
>
>이전에 모든 프로필에 대한 Sales Insight 액세스 권한을 부여했다면 [프로필 수준 액세스 권한 제거](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md)이 권한 집합을 사용하려면 {target=&quot;_blank&quot;}를 사용하십시오.

## Sales Insight에 새 프로필 만들기 {#create-a-new-profile-for-sales-insight}

Sales Insight 사용자를 위한 전용 프로필이 있는 경우 이 단계를 건너뛸 수 있습니다.

1. Salesforce에서 설정 페이지로 이동합니다.

1. 빠른 찾기에서 프로필을 검색하고 **프로필** 선택 사항입니다.

1. 을(를) 클릭합니다. **새 프로필** 단추 를 클릭합니다.

1. 복제할 프로필을 선택하고 이름을 지정합니다(예: Sales Insight User).

1. 클릭 **저장** 완료 시.

## Sales Insight 권한 추가 {#add-sales-insight-permissions}

1. 프로필 목록으로 돌아갑니다.

1. 을(를) 클릭합니다. **편집** 방금 만든 새 프로필(또는 Sales Insight Access에 제공할 다른 기존 프로필)에 대한 링크입니다.

1. 편집 페이지에서 몇 가지 설정을 변경해야 합니다.

   **Sales Insight에 액세스할 수 있는 프로필의 경우**:

   * 탭 설정에서 Marketo 탭을 기본값으로 변경합니다.
   * 사용자 지정 개체 권한에서 Marketo Sales Insight Config에서 읽기, 만들기, 편집 및 삭제를 선택합니다(사용자가 구성 설정에 액세스할 수 있어야 하는 경우(일반적으로 관리자에 사용됨).

   **Sales Insight에 액세스할 수 없는 프로필의 경우**:

   * 탭 설정에서 Marketo 탭을 숨겨진 탭으로 변경합니다
   * 사용자 지정 개체 권한에서 Marketo Sales Insight Config에 대한 읽기, 만들기, 편집 및 삭제를 선택 취소합니다.


1. 클릭 **저장** 완료 시.

## Sales Insight에 대한 레이아웃 만들기 {#create-layout-for-sales-insight}

1. Setup 페이지로 이동한 다음 를 클릭합니다. **앱 설정** > **사용자 지정** > **리드** > **페이지 레이아웃**. 그런 다음 **새로 만들기** 버튼을 클릭합니다.

1. 선택한 레이아웃을 복제하고 레이아웃에 적절한 이름을 지정합니다(예: Sales Insight Layout).

1. 클릭 **저장** 완료 시.

1. 연락처, 기회 및 계정 페이지 레이아웃에 대해 이러한 단계를 반복합니다.

## 레이아웃에 프로필 할당 {#assign-profile-to-layout}

1. 페이지 레이아웃 섹션으로 돌아가서 **페이지 레이아웃 지정** 버튼을 클릭합니다.

1. 선택 **할당 편집**.

1. 목록에서 Sales Insight 프로필을 선택한 다음 &quot;페이지 레이아웃 선택&quot; 드롭다운에서 Sales Insight 레이아웃을 선택합니다.

1. 클릭 **저장** 완료 시.

1. 연락처, 기회 및 계정 페이지 레이아웃에 대해 이러한 단계를 반복합니다.

## 기타 변경 사항 {#other-changes}

다음은 Sales Insight 항목이 표시될 수 있는 몇 가지 다른 위치입니다. 프로필을 사용하여 액세스를 제한할 수 없으므로 완전히 제거해야 합니다.

* 연락처, 리드 및 계정에 대한 검색 레이아웃에서 판매 통찰력 버튼을 제거합니다.
* 연락처 및 리드 목록에서 판매 통찰력 열 제거