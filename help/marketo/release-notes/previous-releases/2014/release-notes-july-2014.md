---
unique-page-id: 2951040
description: 릴리스 노트 - 2014년 7월 - Marketo 설명서 - 제품 설명서
title: 릴리스 노트 - 2014년 7월
exl-id: 0f0b4ad4-0ca7-4f43-bc08-5e555890d289
feature: Release Information
source-git-commit: ecd225af3ecfd7cb9159faf5a9d384d47ee6312c
workflow-type: tm+mt
source-wordcount: '410'
ht-degree: 0%

---

# 릴리스 노트: 2014년 7월 {#release-notes-july}

다음 기능은 2014년 7월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오. 자세한 기능 설명서에 대한 링크를 보려면 릴리스 이후 다시 돌아오십시오.

## 마케팅 캘린더 {#marketing-calendar}

프로그램 전체에서 모든 이벤트, 이메일 등을 볼 수 있습니다. [이 새 제품](/help/marketo/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.md)은(는) 10명 이하의 [!DNL Marketo Lead Management] 또는 대화 상자를 사용하는 고객에게 무료로 제공됩니다.

![](assets/image2014-9-22-14-3a22-3a27.png)

마케팅 캘린더에 대한 설명서는 릴리스 시 사용할 수 있습니다.

## 새로운 디자인 {#new-look-and-feel}

![](assets/image2014-9-22-14-3a22-3a47.png)

[!DNL Marketo Lead Management]은(는) 현대적이고 세련된 새로운 모양과 느낌으로 업데이트되며 업데이트된 탐색이 포함됩니다.

## 날짜 연산자 {#date-operators}

&quot;[!UICONTROL in past before]&quot;, &quot;[!UICONTROL in future]&quot; 및 &quot;[!UICONTROL in future after]&quot;에 대한 [고급 필터](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md). 예를 들어, 생년월일이 3개월 이내인 잠재 고객 또는 6개월 후 만료되는 계약을 찾습니다.

![](assets/image2014-9-22-14-3a23-3a56.png)

![](assets/image2014-9-22-14-3a24-3a39.png)

## 프로그램 일정 보기 {#program-schedule-view}

마케팅 달력 이외에도 를 사용하여 이벤트 및 기본 프로그램을 관리할 수 있으며, 프로그램의 새 일정 보기 권한도 있습니다.

* 한 번에 모든 일자 예약 조정
* 새로운 임시 일자 - 연필로 입력해 보십시오.
* 사용자 지정 항목 유형 - 할 일, 보도 자료 등 원하는 모든 것

## REST API의 목록 작업 {#list-operations-in-the-rest-api}

ReST의 목록 작업과 관련하여 아래에 호출을 추가했습니다. 전체 설명서는 [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api)을(를) 참조하십시오.

* ID별 목록 가져오기
* 여러 목록 가져오기
* 목록으로 가져오기
* 목록 상태로 가져오기

## 빠른 목록 가져오기 {#fast-list-import}

**50배 더 빠르게**&#x200B;하면 파일이 Marketo으로 확대/축소됩니다! 이전 &quot;일반&quot; 및 &quot;새 리드에 맞게 최적화&quot; 가져오기 옵션이 &quot;기본값(빠른 가져오기)&quot;으로 대체되었습니다.

새 리드 및 업데이트 건너뛰기 옵션은 변경되지 않습니다.

## 새롭게 향상된 Munchkin! {#new-improved-munchkin}

롤아웃은 7월 중순부터 시작하여 향후 몇 달 동안 진행될 예정입니다.

* 전체 및 향후 호환성을 위해 [!DNL jQuery] 종속성을 제거합니다.
* 사이트의 다른 JavaScript과 더 호환됩니다.
* 지난 1년 동안 많은 사이트에서 완전히 테스트되었습니다!

## RTP: 실시간 Personalization Campaign 템플릿 {#rtp-real-time-personalization-campaign-templates}

이제 RTP Set Campaign 페이지 [준비된 템플릿을 포함합니다](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md). 웨비나, 사례 연구, 전자 책을 포함한 다양한 스타일 중에서 선택하십시오.

![](assets/image2014-9-22-14-3a25-3a13.png)

![](assets/image2014-9-22-14-3a25-3a47.png)

## RTP: JavaScript API 개선 사항 {#rtp-javascript-api-enhancements}

조직, 업계, 위치 및 세그먼트 코드 일치와 같은 실시간 방문자 데이터를 가져오기 위한 새로운 RTP API 호출입니다. 또한 세그먼트 페이지의 세그먼트 이름 위로 마우스를 가져가면 세그먼트 코드를 보여주는 도구 설명이 표시됩니다. 자세한 내용은 [개발자 사이트](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/rich-media-recommendation)를 참조하십시오.

![](assets/image2014-9-22-14-3a26-3a11.png)

## RTP: Campaign 컨텐츠 편집기의 HTML5 지원 {#rtp-html-support-in-campaign-content-editor}

이제 캠페인 설정 페이지의 콘텐츠 WYSIWYG 편집기에 전체 HTML5 호환성이 있습니다. 편집기 내의 &quot;HTML&quot; 아이콘을 클릭하여 HTML5 코드를 삽입합니다.
