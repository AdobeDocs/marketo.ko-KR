---
unique-page-id: 45416698
description: 릴리스 노트 - 2020년 7월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2020년 7월
exl-id: 3c9b1f1d-961c-4bf8-8b99-37b483230506
feature: Release Information
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '629'
ht-degree: 2%

---

# 릴리스 정보: 2020년 7월 {#release-notes-july}

다음 기능은 2020년 7월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>현재 패키지에 따라 별(![(별)](assets/yellow-star.png))이 있는 항목은 값 추가 기능을 구입해야 할 수 있습니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_** 다음 기능은 **2020년 7월 31일**&#x200B;에 릴리스됩니다.

## 관리 {#administration}

* **[필드 관리에서 &quot;Used By&quot; 내보내기](/help/marketo/product-docs/administration/field-management/export-used-by-data-for-a-field.md)**: 관리자는 이제 선택한 필드에 대한 모든 &quot;Used By&quot; 자산 링크를 CSV 파일로 내보낼 수 있습니다. 이 개선 사항은 관리자와 관리자가 아닌 사용자 모두 사용하지 않는 필드를 정리하는 데 도움이 될 수 있습니다. 또한 이제 새 브라우저 탭이나 창에서 에셋을 열 수 있습니다.

## Account-Based Marketing {#account-based-marketing}

![(별)](assets/yellow-star.png)

* **계정 프로파일링에 대한 UI를 업데이트했습니다**: 단일 화면에서 간소화된 단계를 통해 계정 프로파일링에서 대상 계정 목록 만들기를 단순화하십시오.

<br> 

**_분기 내내 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

* **Forms 서비스**: 더 강력한 양식 필드 구문 유효성 검사와 랜딩 페이지 기능에 대한 새로운 보안 도메인으로 일반적인 봇 패턴을 차단하는 기능을 도입했습니다. 보트 패턴을 차단하면 스팸 양식 제출을 줄이고 데이터베이스 품질을 향상시킬 수 있습니다.

>[!NOTE]
>
>향상된 양식 필드 구문 유효성 검사의 전체 롤아웃이 2021년 1월 릴리스 이후로 연기되었습니다.

* **자산 API URI 크기 제한 늘림**: &quot;_method&quot; 매개 변수를 제거하기 전에 URI(Uniform Resource Identifier) 크기 제한을 8KB에서 65KB로 늘리고 있습니다. 긴 쿼리 문자열을 수행할 때 이 크기 제한을 늘리면 데이터를 보다 쉽게 전달할 수 있습니다. &quot;_method&quot; 매개 변수의 제거는 향후 보안 업그레이드의 일부입니다.

## [!DNL Sales Insight] {#sales-insight}

![(별)](assets/yellow-star.png)

* **[[!DNL Sales Insight] 기본이 아닌 고객에 대해 활성화됨 [!DNL Salesforce] CRM 통합](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md)(Beta)**: 기본이 아닌 [!DNL Salesforce] CRM 통합을 사용하는 Marketo Engage 고객은 이제 [!DNL Sales Insight]을(를) 사용하여 영업 팀이 가장 많이 참여하는 리드 및 기회를 이해하고, 우선 순위를 지정하고, 상호 작용하여 스마트 판매 및 더 빠른 거래를 활성화할 수 있습니다.

## [!DNL Sales Connect] {#sales-connect}

![(별)](assets/yellow-star.png)

* **[판매 전화에 대한 양사 동의 향상:](/help/marketo/product-docs/marketo-sales-connect/phone/two-party-consent-settings.md)** 관리자는 이제 통화 녹음 구성을 보다 세밀하게 제어할 수 있습니다. [통화 녹음/녹화를 사용](/help/marketo/product-docs/marketo-sales-connect/phone/enable-call-recording.md)할 수 있습니다. 통화 녹음 알림을 자동화하고 통화 전에 재생할 오디오 클립을 활성화합니다.

<br> 

## 공지 및 중단 {#announcements-deprecations}

* **자산 API &quot;_method&quot; 매개 변수 제거**: 2020년 9월 이후, 자산 API 끝점은 이제 &quot;_method&quot;를 사용하여 쿼리 매개 변수를 URI 길이 제한을 무시하도록 POST 본문에 전달하지 않습니다. 이 매개 변수를 필요로 하는 요청을 수용하기 위해 자산 API의 URI 제한이 8KB에서 65KB로 늘어납니다.
* **[[!DNL Munchkin] 리드 연결](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/)**: Munchkin JavaScript 클라이언트 버전 159의 이번 릴리스를 통해 [!DNL Munchkin] 리드 연결 방법의 사용 중단을 시작합니다. 호출되면 메서드가 향후 릴리스에서 제거됨을 나타내는 경고가 표시됩니다. 제거하면 메서드가 더 이상 작동하지 않으며 해당 메서드를 사용하려고 시도해도 실패합니다. 최근 이 방법을 사용한 Marketo Engage 고객은 사용 여부를 개별적으로 알 수 있습니다.
* **Internet Explorer 지원**: 이전에 발표된 대로 Internet Explorer 11에 대한 Marketo Engage 지원은 **2020년 7월 31일**&#x200B;에 종료됩니다. [!DNL Google Chrome], [!DNL Mozilla Firefox], [!DNL  Apple Safari] 및 [!DNL Microsoft Edge]을(를) 계속 지원합니다.
* **Sky 기본 경험**: 관리자 또는 사용자가 [!DNL Marketo Sky]을(를) 기본 경험으로 설정하는 옵션은 기본 사용자 경험으로 업데이트할 준비를 위해 이 릴리스에서 제거됩니다. 기본 경험에 대한 업데이트에 대한 자세한 내용은 올해 말로 예정되어 있으며 7월에 제공될 예정입니다. [!DNL Marketo Sky]을(를) 기본 경험으로 설정하거나 [!DNL Marketo Sky]에 대한 액세스 권한이 부여된 사용자는 내 Marketo 홈 페이지의 타일에서 [!DNL Marketo Sky]에 계속 액세스할 수 있습니다.
* **EdgeHTML(비 Chromium) [!DNL Microsoft Edge] 지원**: Marketo Engage은 2020년 말에 더 이상 Microsoft Edge의 EdgeHTML 버전을 지원하지 않습니다. 2021년 1월 1일부터 Microsoft Edge의 최신 Chromium 버전만 지원합니다.
