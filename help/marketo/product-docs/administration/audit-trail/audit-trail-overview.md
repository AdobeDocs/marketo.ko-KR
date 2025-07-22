---
unique-page-id: 11377945
description: 감사 추적&rbrack; 개요 - Marketo 문서 - 제품 설명서
title: 감사 추적 개요
exl-id: e8aff7b7-72ca-4d4e-9159-56ff65f6345c
feature: Audit Trail
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 0%

---

# 감사 추적 개요 {#audit-trail-overview}

감사 추적 은 Marketo 인스턴스 내에서 수행된 변경 사항의 전체 내역(6개월치)을 확인할 수 있는 기능을 제공합니다.

>[!NOTE]
>
>감사 추적 데이터 기록은 2016년 9월 14일에 시작되었습니다.

![](assets/audit-trail-overview-1.png)

## 감사 추적이란? {#what-is-audit-trail}

감사 추적 은 Marketo 구독 내에서 발생하는 작업 및 이벤트의 포괄적인 목록을 실시간으로 캡처합니다. 여기에는 다음과 같은 질문에 답변할 수 있도록 6개월 분량의 데이터 기록에 액세스하는 셀프서비스 방법이 포함되어 있습니다.

이 에셋 또는 설정이 어떻게 되었으며 마지막으로 업데이트한 사람은 누구입니까?

사용자 X는 무엇을 하고 있었습니까?

누가 우리의 계정에 로그인하고 있습니까?

## 당사가 감사하는 내용 {#what-we-audit}

Marketo은 다음에 대한 [만들기, 편집 및 삭제](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md) 작업을 감사합니다.

* Studio 자산 디자인
* 모든 Marketo 프로그램
* 스마트 캠페인
* 목록(스마트/정적)
* 사용자(관리자)
* 역할 및 권한(관리자)
* Workspace 및 파티션(관리)
* 사용자 로그인 기록

>[!NOTE]
>
>현재 Marketo은 Web Personalization, Predictive Content 또는 Sales Insight 내에서 변경된 내용을 _감사하지_&#x200B;않습니다.

## 감사 추적 구성 요소 {#audit-trail-components}

감사 추적은 세 가지 구성 요소로 구성됩니다.

**1) [자산 감사 추적](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#asset-audit-trail)**

특정 자산에 대해 수행된 활동을 참조하십시오.

**2) [관리자 감사 추적](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#admin-audit-trail)**

사용자 기반 세부 정보 모니터링

**3) [사용자 로그인 기록](/help/marketo/product-docs/administration/audit-trail/user-login-history.md)**

구독에 로그인한 사람과 시점을 확인합니다. 실패한 로그인 시도도 포함됩니다.

>[!TIP]
>
>감사 추적을 사용하여 감사할 수 있는 내용이 너무 많습니다. [필터링](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md)을(를) 활용하세요!

## 데이터 내보내기 {#exporting-data}

인스턴스에서는 30일 분량의 데이터만 볼 수 있습니다. 6개월치를 얻으려면(최대) 내보내기 옵션을 사용합니다.

![](assets/two.png)

>[!NOTE]
>
>**정의**
>
>**알 수 없음:** [!DNL Webhook]에서 사용자 이름과 전자 메일이 &quot;알 수 없음&quot;으로 표시될 수 있습니다. 이 문제는 CRM에서 선택 목록 값을 변경할 때 발생합니다. 이 값은 Marketo Forms 및 랜딩 페이지에 표시됩니다. CRM 측에서 이 업데이트를 수행하면 양식을 참조하는 랜딩 페이지가 자동으로 초안으로 작성됩니다. [!DNL Webhook]에서 랜딩 페이지가 작성되었지만 CRM측에서 사용자 정보를 캡처할 수 없으므로 사용자 이름과 전자 메일이 &quot;알 수 없음&quot;으로 표시됩니다.

>[!MORELIKETHIS]
>
>[감사 추적 사용](/help/marketo/product-docs/administration/audit-trail/enable-audit-trail.md)
