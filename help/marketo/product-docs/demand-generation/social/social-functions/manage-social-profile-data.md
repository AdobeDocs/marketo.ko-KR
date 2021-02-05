---
unique-page-id: 2950578
description: 소셜 프로필 데이터 관리 - 마케팅 문서 - 제품 설명서
title: 소셜 프로필 데이터 관리
translation-type: tm+mt
source-git-commit: 074701d1a5f75fe592ac7f44cce6fb3571e94710
workflow-type: tm+mt
source-wordcount: '304'
ht-degree: 0%

---


# 소셜 프로필 데이터 관리 {#manage-social-profile-data}

누군가 Marketing[소셜 앱](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md)과 상호 작용하거나, 소셜 네트워크를 통해 [소셜 양식 채우기](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md)로 마케팅 양식을 미리 채우도록 승인하면, Marketing은 소셜 프로필에서 사용할 수 있는 모든 데이터를 캡처합니다. [사람 세부 정보 페이지](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md)에서 이 정보를 보거나, 스마트 목록](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/create-and-change-views-for-lists-and-smart-list.md)의 [사용자 정의 보기에서 열로 추가할 수 있습니다.

소셜 양식 채우기 및 소셜 앱은 약간 다른 필드 세트를 캡처합니다.아래 각 섹션을 참조하십시오.

>[!AVAILABILITY]
>
>모든 고객이 이 기능을 구입하지는 않았습니다. 자세한 내용은 영업 담당자에게 문의하십시오.

## 소셜 앱 {#captured-via-social-app}을(를) 통해 캡처됨

네트워크 및 사용자의 개인 정보 설정에 따라 다음 필드 중 하나 이상이 검색됩니다.

>[!NOTE]
>
>소셜 네트워크의 추가 정보는 개인이 승인하고 약 5분 후에 개인 세부 사항 페이지에 표시됩니다.

## Twitter에서:{#from-twitter}

* 이름(표시 이름에서 파싱됨)
* 성(표시 이름에서 파싱됨)
* 프로필 사진 URL
* 프로필 페이지 URL
* 소셜 도달(팔로워 수)

>[!NOTE]
>
>Social 앱은 사람의 이메일 주소를 가져오지 않습니다.

## Facebook에서:{#from-facebook}

* 이름
* 성
* 프로필 URL
* 프로필 사진 URL
* 성별
* 소셜 도달(친구 수)

### 소셜 양식 채우기 {#captured-via-social-form-fill}를 통해 캡처됨

네트워크 및 사용자의 개인 정보 설정에 따라 다음 필드 중 하나 이상이 검색됩니다.

>[!CAUTION]
>
>양식 수준](/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md)에서 해당 필드에 대한 업데이트를 [차단하지 않으면 소셜 양식 채우기로 캡처된 데이터가 일치하는 필드를 덮어씁니다.

## Twitter에서:{#from-twitter-1}

* 이름(표시 이름에서 파싱됨)
* 성(표시 이름에서 파싱됨)
* 이메일

## Facebook에서:{#from-facebook-1}

* 이름
* 성
* 이메일
* 생년월일
* 직함
* 회사

>[!NOTE]
>
>소셜 양식 채우기는 사용자가 양식에 입력하는 경우 이메일 주소 _만_&#x200B;을 캡처합니다. 이메일 주소가 필요한 경우 [양식에 필수 필드로 지정해야 합니다](/help/marketo/product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md).

>[!MORELIKETHIS]
>
>양식에서 이 정보를 캡처하려면 [소셜 양식 채우기](/help/marketo/product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md)를 활성화합니다.
