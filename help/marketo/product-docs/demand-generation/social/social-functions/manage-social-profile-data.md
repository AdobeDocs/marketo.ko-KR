---
unique-page-id: 2950578
description: 소셜 프로필 데이터 관리 - Marketo 문서 - 제품 설명서
title: 소셜 프로필 데이터 관리
exl-id: 9b20c6fc-5c80-4665-9c93-1bb6e53a29ae
feature: Social
source-git-commit: 6c3f803104c550227aec25376778147ff92aaab9
workflow-type: tm+mt
source-wordcount: '338'
ht-degree: 5%

---

# 소셜 프로필 데이터 관리 {#manage-social-profile-data}

누군가 Marketo [소셜 앱](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md)과 상호 작용하거나 소셜 네트워크에 [소셜 양식 채우기](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md)(으)로 Marketo 양식을 미리 채우도록 권한을 부여하면 Marketo에서 소셜 프로필에서 사용할 수 있는 모든 데이터를 캡처합니다. [개인 세부 정보 페이지](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md)에서 이 정보를 보거나 [스마트 목록의 사용자 지정 보기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/create-and-change-views-for-lists-and-smart-list.md)에서 열로 추가할 수 있습니다.

>[!IMPORTANT]
>
>2024년 7월 31일에 이 기능의 사용 중단 프로세스를 시작했습니다. 더 이상 새 자산을 만들 수 없습니다. 기존 자산은 2025년 1월 31일까지 계속 작동합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

소셜 양식 채우기 및 소셜 앱은 약간 다른 필드 세트를 캡처합니다. 아래 각 섹션에 대한 섹션을 참조하십시오.

>[!AVAILABILITY]
>
>일부 Marketo Engage 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

## 소셜 앱을 통해 캡처됨 {#captured-via-social-app}

네트워크 및 사용자의 개인 정보 설정에 따라 다음 필드 중 하나 이상이 검색됩니다.

>[!NOTE]
>
>소셜 네트워크의 추가 정보는 개인이 권한을 부여한 후 약 5분 후에 개인 세부 정보 페이지에 표시됩니다.

## 출처 Twitter: {#from-twitter}

* 이름(디스플레이 이름에서 구문 분석됨)
* 성(디스플레이 이름에서 구문 분석됨)
* 프로필 사진 URL
* 프로필 페이지 URL
* 소셜 도달 범위(팔로우어 수)

>[!NOTE]
>
>소셜 앱은 사용자의 이메일 주소를 가져오지 않습니다.

## facebook에서: {#from-facebook}

* 이름
* 성
* 프로필 URL
* 프로필 사진 URL
* 성별
* 소셜 도달 범위(친구 수)

### 소셜 양식 채우기를 통해 캡처됨 {#captured-via-social-form-fill}

네트워크 및 사용자의 개인 정보 설정에 따라 다음 필드 중 하나 이상이 검색됩니다.

>[!CAUTION]
>
>[양식 수준에서 해당 필드에 대한 업데이트를 차단](/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md)하지 않는 한 소셜 양식 채우기에 의해 캡처된 데이터는 일치하는 필드를 덮어씁니다.

## 출처 Twitter: {#from-twitter-1}

* 이름(디스플레이 이름에서 구문 분석됨)
* 성(디스플레이 이름에서 구문 분석됨)
* 이메일

## facebook에서: {#from-facebook-1}

* 이름
* 성
* 이메일
* 생년월일
* 직위
* 회사

>[!NOTE]
>
>소셜 양식 채우기는 사용자가 양식에 입력한 경우 이메일 주소 _만_&#x200B;을(를) 캡처합니다. 전자 메일 주소가 필요한 경우 [양식의 필수 필드로 설정](/help/marketo/product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md)해야 합니다.

>[!MORELIKETHIS]
>
>양식에서 이 정보를 캡처하려면 [소셜 양식 채우기](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md)를 사용하도록 설정하십시오.
