---
unique-page-id: 14352480
description: 회신 로깅(SFDC) - Marketo 문서 - 제품 설명서
title: 회신 로깅(SFDC)
exl-id: 11f84157-55b7-42a7-81d0-f5848adbb9f4
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---

# 회신 로깅(SFDC) {#reply-logging-sfdc}

Sales Connect 는 Salesforce에 잠재 고객의 응답을 자동으로 기록하는 기능을 제공합니다. 이 작업을 수행할 수 있는 구조는 이메일 회신 추적을 기반으로 합니다. 잠재 고객의 응답을 추적할 수 있는 경우 Salesforce에 해당 응답을 기록할 수 있습니다.

## 요구 사항 {#requirements}

* API 로깅을 통해 이메일을 로깅해야 합니다
* 다음을 수행할 수 있어야 합니다. [회신 추적](/help/marketo/product-docs/marketo-sales-connect/email/common-tracking-questions/how-reply-tracking-works.md)
* Salesforce와 연결되어 있어야 함
* Salesforce가 있어야 함 [API 호출](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm) 사용 가능

## 회신 로깅 활성화 {#enable-reply-logging}

1. 회신 로깅을 사용하려면 Salesforce 설정 페이지로 연결될 수 있습니다. API 로깅을 해제하면 확인 옵션이 표시됩니다 _답글 로그_.

   >[!NOTE]
   >
   >회신 로깅은 전송된 전자 메일 로깅에 대해 제자리에 있는 것과 동일한 규칙을 따릅니다. 여기에는 전자 메일이 기록되는 방식이 포함됩니다. 대상 및 연락처 중복 레코드가 있는 경우 일치하는 레코드가 없으면

## Salesforce에서 유형을 응답으로 설정 {#setting-type-to-reply-in-salesforce}

Salesforce 보고서에서 의미 있는 데이터를 가져오는 것이 중요합니다. 유형 필드를 &#39;회신&#39;으로 채우는 기능을 사용하면 보고서를 통해 해당 데이터를 가져올 수 있습니다. 파트너 관계 설정 `Salesforce admin` 이 설정을 가져오려면 다음을 수행하십시오.

1. 이동 **설정** > **사용자 지정** > **활동** > **작업 필드**.
1. 클릭 **유형**.
1. 작업 유형 선택목록 값에서 **새로 만들기**.
1. 빈 상자에 &quot;회신&quot;을 입력합니다. &#39;R&#39;을 대문자로 사용하고 **저장**.

   >[!NOTE]
   >
   >유형 선택 목록에서 기본값을 선택할 필요는 없습니다. Sales Connect에서 Salesforce 인스턴스에서 이 활동 유형을 사용할 수 있음을 확인하고 그에 따라 수신 활동의 작업 필드를 채웁니다.
