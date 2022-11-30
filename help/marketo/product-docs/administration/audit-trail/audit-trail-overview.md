---
unique-page-id: 11377945
description: 감사 추적 개요 - Marketo 문서 - 제품 설명서
title: 감사 추적 개요
exl-id: e8aff7b7-72ca-4d4e-9159-56ff65f6345c
source-git-commit: 5f509a7aa27692e54bf129b94c657aff0f645f2b
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 0%

---

# 감사 추적 개요 {#audit-trail-overview}

감사 추적을 사용하면 Marketo 인스턴스 내에서 수행된 변경 내용의 전체 내역(6개월 가치)을 얻을 수 있습니다.

>[!NOTE]
>
>감사 추적 데이터 기록은 2016년 9월 14일에 다시 시작되었습니다.

![](assets/audit-trail-overview-1.png)

## 감사 추적 소개 {#what-is-audit-trail}

감사 추적은 Marketo 구독 내에서 발생하는 작업 및 이벤트의 포괄적인 목록을 실시간으로 캡처합니다. 여기에는 다음과 같은 질문에 답변할 수 있도록 6개월 데이터 기록에 액세스하는 셀프서비스 방법이 포함되어 있습니다.

이 자산 또는 설정은 어떻게 되었으며 마지막으로 업데이트한 사람은 누구입니까?

사용자 X는 어떤 작업을 수행했습니까?

누가 우리 계정에 로그인합니까?

## Adobe 감사 {#what-we-audit}

Marketo이 감사 [만들기, 편집 및 삭제](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md) 다음에 대한 작업:

* 디자인 스튜디오 자산
* 모든 Marketo 프로그램
* 스마트 캠페인
* 목록(스마트/정적)
* 사용자(관리자)
* 역할 및 권한(관리자)
* 작업 공간 및 파티션(관리)
* 사용자 로그인 내역

>[!NOTE]
>
>Marketo은 _not_ 는 현재 웹 개인화, 예측 컨텐츠 또는 판매 인사이트 내에서 수행된 변경 사항을 감사합니다.

## 감사 추적 구성 요소 {#audit-trail-components}

감사 추적은 세 가지 구성 요소로 구성됩니다.

**1) [자산 감사 추적](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#asset-audit-trail)**

특정 자산에 대한 활동 완료 를 참조하십시오.

**2) [관리 감사 추적](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#admin-audit-trail)**

사용자 기반 세부 사항을 모니터링합니다.

**3) [사용자 로그인 내역](/help/marketo/product-docs/administration/audit-trail/user-login-history.md)**

구독에 로그인한 사용자 및 시간을 확인합니다. 로그인 시도 실패도 포함됩니다.

>[!TIP]
>
>감사 추적을 사용하여 감사할 수 있는 많은 정보가 있으며, 반드시 활용하십시오 [필터링](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md)!

## 데이터 내보내기 {#exporting-data}

인스턴스에서 30일 동안의 데이터만 볼 수 있습니다. 최대 6개월 가치를 얻으려면 내보내기 옵션을 사용하십시오.

![](assets/two.png)

>[!NOTE]
>
>**정의**
>
>**알 수 없음:** 감사 추적에서 &quot;알 수 없음&quot;으로 나열된 사용자 이름과 이메일을 볼 수 있습니다. 이 문제는 CRM에서 선택 목록 값을 변경할 때 발생합니다. 이 값은 Marketo 양식 및 랜딩 페이지에 표시됩니다. CRM 측에서 이 업데이트를 수행하면 양식을 참조하는 랜딩 페이지의 초안이 자동으로 표시됩니다. 감사 추적에서는 랜딩 페이지가 작성되었음을 캡처하지만, CRM 측에서 사용자 정보를 캡처할 수 없으므로 사용자 이름과 이메일은 &quot;알 수 없음&quot;으로 표시됩니다.

>[!MORELIKETHIS]
>
>[감사 추적 활성화](/help/marketo/product-docs/administration/audit-trail/enable-audit-trail.md)
