---
unique-page-id: 2950578
description: 소셜 프로필 데이터 관리 - Marketo 문서 - 제품 설명서
title: 소셜 프로필 데이터 관리
exl-id: 9b20c6fc-5c80-4665-9c93-1bb6e53a29ae
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '304'
ht-degree: 5%

---

# 소셜 프로필 데이터 관리 {#manage-social-profile-data}

누군가 Marketo과 상호 작용하는 경우 [소셜 앱](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md)또는 소셜 네트워크에 다음 방법으로 Marketo 양식을 미리 채우도록 허용합니다. [소셜 양식 채우기](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md), Marketo 은 해당 소셜 프로필에서 사용할 수 있는 모든 데이터를 캡처합니다. 다음에서 이 정보를 볼 수 있습니다. [개인 세부 정보 페이지](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md)또는 열을 [스마트 목록의 사용자 지정 보기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/create-and-change-views-for-lists-and-smart-list.md).

소셜 양식 채우기 및 소셜 앱은 약간 다른 필드 집합을 캡처합니다. 아래의 각 섹션을 참조하십시오.

>[!AVAILABILITY]
>
>모든 고객이 이 기능을 구입한 것은 아닙니다. 자세한 내용은 영업 담당자에게 문의하십시오.

## 소셜 앱을 통해 캡처됨 {#captured-via-social-app}

네트워크 및 사용자의 개인 정보 설정에 따라 다음 필드 중 하나 이상이 검색됩니다.

>[!NOTE]
>
>소셜 네트워크의 추가 정보는 개인이 승인하면 5분 후에 개인 세부 사항 페이지에 표시됩니다.

## twitter: {#from-twitter}

* 이름(표시 이름에서 구문 분석됨)
* 성(표시 이름에서 구문 분석됨)
* 프로필 사진 URL
* 프로필 페이지 URL
* 소셜 도달 범위(팔로워수)

>[!NOTE]
>
>Social 앱이 사용자의 이메일 주소를 가져오지 않습니다.

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
>소셜 양식 채우기로 캡처된 데이터는 [양식 수준에서 해당 필드에 대한 업데이트를 차단합니다.](/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md).

## twitter: {#from-twitter-1}

* 이름(표시 이름에서 구문 분석됨)
* 성(표시 이름에서 구문 분석됨)
* 이메일

## facebook에서: {#from-facebook-1}

* 이름
* 성
* 이메일
* 출생일
* 직위
* 회사

>[!NOTE]
>
>소셜 양식 채우기가 이메일 주소를 캡처합니다 _전용_ 사용자가 양식에 입력하는 경우. 이메일 주소가 필요한 경우 [양식에서 필수 필드로 만듭니다](/help/marketo/product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md).

>[!MORELIKETHIS]
>
>양식에서 이 정보를 캡처하려면 [소셜 양식 채우기](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md).
