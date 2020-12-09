---
unique-page-id: 2950578
description: 소셜 프로필 데이터 관리 - 마케팅 문서 - 제품 설명서
title: 소셜 프로필 데이터 관리
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '396'
ht-degree: 0%

---


# 소셜 프로필 데이터 관리 {#manage-social-profile-data}

누군가 Marketing to [소셜 앱과](../../../../product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md)상호 작용하거나 소셜 네트워크에 [소셜 양식 채우기](../../../../product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md)기능을 부여하면 Marketing to는 소셜 프로필에서 사용할 수 있는 모든 데이터를 캡처합니다. [ [개인 세부 사항] 페이지에서](http://docs.marketo.com/display/DOCS/Using+the+Person+Detail+Page)이 정보를 보거나 스마트 목록의 [사용자 정의 보기에서 열로 추가할 수 있습니다](http://docs.marketo.com/display/DOCS/Create+and+Change+Views+for+Lists+and+Smart+List).

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

소셜 양식 채우기 및 소셜 앱은 약간 다른 필드 집합을 캡처합니다.아래 각 섹션을 참조하십시오.

>[!NOTE]
>
>**가용성**
>
>모든 고객이 이 기능을 구입하지는 않았습니다. 자세한 내용은 영업 담당자에게 문의하십시오.

## 소셜 앱을 통해 캡처 {#captured-via-social-app}

네트워크 및 사용자의 개인 정보 설정에 따라 다음 필드 중 하나 이상이 검색됩니다.

>[!NOTE]
>
>소셜 네트워크의 추가 정보는 허가 후 약 5분 후에 개인 세부 사항 페이지에 나타납니다.

## Twitter에서: {#from-twitter}

* 이름(표시 이름에서 파싱됨)
* 성(표시 이름에서 파싱됨)
* 프로필 사진 URL
* 프로필 페이지 URL
* 소셜 도달(팔로워 수)

>[!NOTE]
>
>Social 앱은 사람의 이메일 주소를 가져오지 않습니다.

## Facebook에서: {#from-facebook}

* 이름
* 성
* 프로필 URL
* 프로필 사진 URL
* 성별
* 소셜 도달(친구 수)

### 소셜 양식 채우기를 통해 캡처 {#captured-via-social-form-fill}

네트워크 및 사용자의 개인 정보 설정에 따라 다음 필드 중 하나 이상이 검색됩니다.

>[!CAUTION]
>
>소셜 양식 채우기로 캡처된 데이터는 양식 수준에서 해당 필드에 대한 업데이트를 [차단하지 않는 한 일치하는 필드를 덮어씁니다](../../../../product-docs/administration/field-management/block-updates-to-a-field.md).

## Twitter에서: {#from-twitter-1}

* 이름(표시 이름에서 파싱됨)
* 성(표시 이름에서 파싱됨)
* 이메일

## Facebook에서: {#from-facebook-1}

* 이름
* 성
* 이메일
* 생년월일
* 직함
* 회사

>[!NOTE]
>
>소셜 양식 채우기는 사용자가 양식에 입력하는 *경우에만* 이메일 주소를 캡처합니다. 이메일 주소가 필요한 경우 양식에서 필수 [필드로 만들어야 합니다](../../../../product-docs/demand-generation/forms/creating-a-form/make-a-form-field-required.md).

>[!MORELIKETHIS]
>
>양식에서 이 정보를 캡처하려면 [소셜 양식 채우기를 활성화합니다](../../../../product-docs/demand-generation/forms/form-actions/enable-social-form-fill-on-a-form.md).

>[!NOTE]
>
>**딥 다이브**
>
>자세한 내용은 [Forms](http://docs.marketo.com/display/docs/forms) 심층 분석 자료를 참조하십시오.

