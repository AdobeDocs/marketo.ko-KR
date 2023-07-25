---
unique-page-id: 37355826
description: 릴리스 노트 - 2020년 2월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2020년 2월
exl-id: 6216b405-69c6-422b-a78c-7df0e8d271e9
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '650'
ht-degree: 0%

---

# 릴리스 정보: 2020년 2월 {#release-notes-feb}

다음 기능은 2020년 2월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별표로 표시되는 기능( ![(별)](assets/yellow-star.png))는 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

**_분기별 릴리스_** 다음 기능이에 릴리스되었습니다. **2020년 2월 21일**.

## 핵심 Marketo Engage {#core-marketo-engage}

* **Microsoft Dynamics &quot;Microsoft의 소유자 변경&quot; 흐름 작업**: Marketo Engage에서 직접 리드/연락처 소유자를 변경할 수 있는 기능을 사용하여 Microsoft Dynamics CRM 데이터를 제어할 수 있습니다. 이는 기본 CRM 통합 기능의 향상된 기능입니다.
* **사용자 관리 API**: 외부 ID 및 조직 관리 시스템을 통해 사용자 및 역할 관리를 자동화합니다. 이는 API 호출 기능의 개선 사항입니다.
* **사용자 지정 개체 스키마 API**: Marketo Engage의 인스턴스 간에 사용자 지정 개체 스키마를 자동으로 관리 및 프로비저닝하여 판매 및 마케팅 도구에서 데이터 모델을 일관되게 유지합니다. 이 API를 사용하면 샌드박스 또는 전문가 센터에서 사용자 정의 오브젝트를 정의하고 테스트하며 필요한 만큼 많은 인스턴스에 프로비저닝할 수 있습니다. 이는 API 호출 기능의 개선 사항입니다. 이 개선 사항에 대한 액세스 권한을 받는 방법을 알아보려면 Marketo Engage 담당자에게 문의하십시오.
* **랜딩 페이지 리디렉션 규칙 API**: 랜딩 페이지 리디렉션 규칙 관리를 자동화합니다. 이는 API 호출 기능의 개선 사항입니다.
* **양식 설명자 캐싱**: 양식을 리소스로 캐싱하여 임베드된 양식의 로드 시간을 줄이고 전반적인 응용 프로그램 안정성을 높이고 있습니다. 임베드된 양식에 대한 승인이 웹에 반영되기까지 최대 4분이 소요될 수 있습니다. 랜딩 페이지 및 Forms 기능의 개선 사항입니다.

<br> 

**_분기 전체에 출시_**

다음 기능은 비분기 주기에 있으며 향후 몇 개월 동안 릴리스될 예정입니다.

## Bizible {#bizible}

![(별)](assets/yellow-star.png)

* **계정 기반 세분화**: 계정 속성을 기반으로 검색 게시판용 세그먼트 및 필터를 만드는 기능을 사용하여 계정 수준에서 속성을 분석합니다. 이러한 세그먼트를 사용하여 계정 기반 마케팅 성과를 드릴다운할 수 있습니다.
* **필터 저장 중**: 각 사용자에 고유한 대시보드 관련 필터를 저장하여 대시보드를 빠르고 일관되게 분석합니다.
* **PDF으로 내보내기**: Bizible 대시보드를 PDF으로 내보내어 조직 전체에서 중요한 통찰력을 공유합니다.

## 영업 연결 {#sales-connect}

* **작성 창 업데이트**: Sales Connect를 통해 템플릿을 선택하고 이메일을 전송하는 프로세스를 간소화했습니다. 웹 클라이언트 및 Salesforce의 작성 창을 사용하여 템플릿 카테고리를 저장하고, 이메일을 예약하고, 이메일을 일괄적으로 보내고, 보기 및 클릭 추적과 함께 이메일을 보낼 수 있는 판매자를 위한 원스톱 샵을 구성하십시오.
* **관리 센터 업데이트**: 판매자가 Sales Connect에서 시작된 모든 이메일, 호출 및 작업에 대한 통찰력을 제공할 수 있도록 Sales Connect 명령 센터를 재구축하고 있습니다. 또한 명령 센터에서 이메일 참여 및 전달성과 같은 정보를 볼 수도 있습니다.

<br> 

## 공지 {#announcements}

* **Marketo Engage 성공 센터**: 2020년 2월에 Marketo Success Center를 시작합니다. Success Center는 Marketo Engage 인스턴스에서 바로 Product Docs 및 Community를 검색하고 사용 방법 가이드를 실행하고 Marketo University 및 피어 모범 사례 비디오와 같은 채택 콘텐츠에 액세스하는 등 다양한 작업을 할 수 있는 제품 내 도움말 센터입니다. **참고**: 이 기능은 ANZ에서 베타 버전으로 출시될 예정이며 해당 분기 말에 북미에 출시될 예정입니다.

## 사용 중단 {#deprecations}

* **자산 API &quot;_method&quot; 매개 변수**: 2020년 9월 이후, 에셋 API 끝점은 더 이상 &quot;_method&quot;를 사용하여 쿼리 매개 변수를 URI 길이 제한을 무시하도록 POST 본문에 전달하지 않습니다. 이 매개 변수를 필요로 하는 요청을 수용하기 위해 자산 API의 URI 제한이 6KiB에서 65KiB로 증가하여 긴 요청 URI가 제출될 수 있습니다.
* **Internet Explorer 지원 중단**: 2020년 7월 31일 7월 릴리스부터 Marketo Engage 사용자 인터페이스는 더 이상 Internet Explorer에서 지원되지 않습니다.

**_제품 릴리스 웨비나_** [가입](https://engage.marketo.com/Jan_Feb_20_Release_Webinar_Registration.html) 3월 3일 오전 11시(PT)/오후 2시(ET 기준) 제품 팀이 주최하는 라이브 웨비나에서 이 릴리스에 포함된 기능에 대해 자세히 알아보십시오.
