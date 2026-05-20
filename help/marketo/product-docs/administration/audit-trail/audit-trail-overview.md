---
unique-page-id: 11377945
description: 감사 추적 개요 및 Marketo 인스턴스에서 6개월 동안의 변경 사항 및 로그인 활동을 캡처하는 방법입니다.
title: 감사 추적 개요
exl-id: e8aff7b7-72ca-4d4e-9159-56ff65f6345c
feature: Audit Trail
TQID: https://experienceleague.adobe.com/4MTpv09ZFWkX6tirnq7ZIABSkfoz07qljcUUORwYNn8
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: a7170d27-32ab-462b-a333-269abc654483id: b0bb9048-d951-48d8-8232-45cf248a7e27id: b13bd2ad-8e65-49e5-9691-2a0d31067b35id: d1d0a9cd-295d-4976-8c39-ddae266f240eid: d65b4a73-87a3-4d56-b638-74e74d9939ceid: e64968b2-4ee5-47f9-8cae-0588f184b9ebid: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
topic_v2: id: e0eb8757-182f-49f3-94a4-1587d16f5094id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 354
ht-degree: 2%

---

# 감사 추적 개요 {#audit-trail-overview}

감사 추적 은 Marketo 인스턴스 내에서 수행된 변경 사항의 전체 내역(6개월치)을 확인할 수 있는 기능을 제공합니다.

>[!NOTE]
>
>감사 추적 데이터 기록은 2016년 9월 14일에 시작되었습니다.

![](assets/audit-trail-overview-1.png)

## 감사 추적이란? {#what-is-audit-trail}

감사 추적 은 Marketo 구독 내에서 발생하는 작업 및 이벤트의 포괄적인 목록을 실시간으로 캡처합니다. 여기에는 다음과 같은 질문에 답변할 수 있도록 6개월 분량의 데이터 기록에 액세스하는 셀프서비스 방법이 포함되어 있습니다.

&quot;이 에셋 또는 설정은 어떻게 되었으며 마지막으로 업데이트한 사람은 누구입니까?&quot;

&quot;사용자 X는 무엇을 하고 있었습니까?&quot;

&quot;누가 우리 계정에 로그인하고 있습니까?&quot;

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

구독에 로그인하고 있는 사용자와 (실패한 로그인 시도 포함)을 확인합니다.

>[!TIP]
>
>감사 추적을 사용하여 감사할 수 있는 작업이 너무 많기 때문에 [필터링](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md)을 통해 시간을 크게 절약할 수 있습니다.

## 데이터 내보내기 {#exporting-data}

인스턴스에서는 30일 분량의 데이터만 볼 수 있습니다. 6개월치를 얻으려면(최대) 내보내기 옵션을 사용합니다.

![](assets/two.png)

>[!NOTE]
>
>**정의**
>
>**알 수 없음:** [!DNL Webhook]에서 사용자 이름과 전자 메일이 &quot;알 수 없음&quot;으로 표시될 수 있습니다. 이 문제는 CRM에서 선택 목록 값을 변경할 때 발생합니다. 이 값은 Marketo Forms 및 랜딩 페이지에 표시됩니다. CRM 측에서 이 업데이트를 수행하면 양식을 참조하는 랜딩 페이지가 자동으로 초안으로 작성됩니다. [!DNL Webhook]에서 Marketo은 랜딩 페이지가 작성되었음을 캡처하지만, Marketo은 CRM측에서 사용자 정보를 캡처할 수 없으므로 사용자의 이름과 이메일은 &quot;알 수 없음&quot;으로 표시됩니다.

>[!MORELIKETHIS]
>
>[감사 추적 사용](/help/marketo/product-docs/administration/audit-trail/enable-audit-trail.md)
