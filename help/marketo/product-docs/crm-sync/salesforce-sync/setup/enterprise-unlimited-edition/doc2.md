---
description: 2단계/3단계 - Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited) - Marketo 문서 - 제품 설명서
title: 2/3단계 - Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited)
hide: true
hidefromtoc: true
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '421'
ht-degree: 4%

---

# 3단계 중 2단계: Marketo용 Salesforce 사용자 만들기 (엔터프라이즈/무제한) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>이 단계는 Salesforce 관리자가 완료해야 합니다

>[!PREREQUISITES]
>
>[3단계 중 1단계: Salesforce(Enterprise/Unlimited)에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md){target="_blank"}

이 문서에서는 Salesforce 프로필에서 사용자 권한을 설정하고 Marketo-Salesforce 통합 계정을 만듭니다.

## 프로필 만들기 {#create-a-profile}

1. **[!UICONTROL Setup]**&#x200B;를 클릭합니다.

   스크린샷

1. 탐색 검색 막대에 &quot;profiles&quot;를 입력하고 프로필 링크를 클릭합니다.

   스크린샷

1. 새 프로필 을 클릭합니다.

   스크린샷

1. 표준 사용자 를 선택하고 프로필 이름을 &quot;Marketo-Salesforce Sync&quot;로 지정한 다음 저장 을 클릭합니다.

   스크린샷

## 프로필 권한 설정 {#set-profile-permissions}

1. 편집 을 클릭하여 보안 권한을 설정합니다.

   스크린샷

1. 관리 권한 섹션에서 다음 확인란이 선택되어 있는지 확인합니다.

   * API 활성화됨
   * HTML 템플릿 편집
   * 공개 문서 관리
   * 공개 템플릿 관리

   >[!TIP]
   >
   >암호 만료 안 함 상자를 선택해야 합니다.

1. 일반 사용자 권한 섹션에서 다음 확인란이 선택되어 있는지 확인합니다.

   * 리드 전환
   * 이벤트 편집
   * 작업 편집

1. 표준 객체 권한 섹션에서 읽기, 만들기, 편집 및 삭제 권한이 선택되어 있는지 확인합니다.

   * 계정
   * 캠페인
   * 연락처
   * 잠재 고객
   * 기회

   >[!NOTE]
   >
   >Campaign Sync를 사용하려면 캠페인에 권한을 부여합니다.

   스크린샷

1. 완료되면 페이지 하단에 있는 저장 을 클릭합니다.

   스크린샷

## 필드 권한 설정 {#set-field-permissions}

1. 동기화에 필요한 사용자 지정 필드를 확인하려면 마케터와 상의하십시오.

   >[!NOTE]
   >
   >이 단계는 Marketo에 필요하지 않은 필드가 표시되지 않도록 하여 혼란을 줄이고 동기화 속도를 높입니다.

1. 프로필 세부 정보 페이지에서 필드 수준 보안 섹션으로 이동합니다. 보기 를 클릭하여 객체에 대한 액세스 가능성을 편집합니다.

   * 리드
   * 연락처
   * 계정
   * 기회

   >[!TIP]
   >
   >조직의 필요에 따라 다른 객체를 구성할 수 있습니다.

1. 각 객체에 대해 [편집]을 클릭합니다.

   스크린샷

1. 필요 없는 필드를 찾아 읽기 액세스 및 액세스 편집 이 선택 취소되어 있는지 확인합니다. 완료되면 저장 을 클릭합니다.

   >[!NOTE]
   >
   >사용자 정의 필드에 대한 액세스 가능성만 편집하십시오.

   스크린샷

1. 필요하지 않은 모든 필드 비활성화를 완료한 후 다음 객체 필드에 대해 읽기 액세스 및 액세스 편집 을 선택해야 합니다. 완료되면 저장 을 클릭합니다.

   표

   스크린샷

## Marketo-Salesforce 동기화 계정 만들기 {#create-marketo-salesforce-sync-account}

>[!TIP]
>
>전용 Salesforce 계정(예: `marketo@yourcompany.com`)을 만들어 Marketo 사용자와 다른 Salesforce 사용자가 변경한 내용을 구별합니다.

1. 탐색 검색 창에 &quot;사용자 관리&quot;를 입력한 다음 사용자를 클릭합니다. 새 사용자를 클릭합니다.

   스크린샷

   스크린샷

1. 필수 필드를 채웁니다. 그런 다음 사용자 라이선스: Salesforce 및 이전에 만든 프로필을 선택합니다. 완료되면 저장 을 클릭합니다.

   스크린샷

3단계 중 2단계가 완료되었습니다.
