---
unique-page-id: 14352480
description: 회신 로깅(SFDC) - 마케팅 문서 - 제품 설명서
title: 회신 로깅(SFDC)
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# 회신 로깅(SFDC) {#reply-logging-sfdc}

Sales Connect를 사용하면 잠재 고객의 응답을 Salesforce에 자동으로 기록할 수 있습니다. 이 작업을 수행할 수 있는 구조는 Adobe의 이메일 회신 추적을 기반으로 합니다. 잠재 고객의 응답을 추적할 수 있는 경우 Salesforce에 해당 응답을 기록할 수 있습니다.

## 요구 사항 {#requirements}

* API 로깅을 통해 이메일을 로깅해야 함
* [응답](/help/marketo/product-docs/marketo-sales-connect/email/common-tracking-questions/how-reply-tracking-works.md)을 추적할 수 있어야 합니다.
* Salesforce와 연결되어 있어야 함
* Salesforce [API 호출](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm)을 사용할 수 있어야 합니다.

## 회신 로깅 사용 {#enable-reply-logging}

1. 회신 로깅을 사용하려면 Salesforce 설정 페이지로 리디렉션할 수 있습니다. API 로깅이 해제되면 _답글 로그_&#x200B;를 확인하는 옵션이 표시됩니다.

   >[!NOTE]
   >
   >회신 로깅은 전송된 이메일을 기록할 때 사용한 규칙과 동일한 규칙을 따릅니다. 여기에는 이메일이 로깅되는 방식이 포함됩니다.리드 및 연락처중복 레코드가 있을 때;일치하는 레코드를 찾을 수 없는 경우.

## Salesforce {#setting-type-to-reply-in-salesforce}에서 회신으로 유형 설정

Salesforce 보고서에서 의미 있는 데이터를 얻는 것이 중요합니다. 유형 필드를 &#39;응답&#39;으로 채울 수 있는 기능을 사용하면 보고서를 통해 해당 데이터를 가져올 수 있습니다. `Salesforce admin`과(와) 협력하여 이 설정을 가져옵니다.

1. **설정** > **사용자 지정** > **활동** > **작업 필드**&#x200B;로 이동합니다.
1. **유형**&#x200B;을 클릭합니다.
1. 작업 유형 선택 목록 값에서 **새로 만들기**&#x200B;를 클릭합니다.
1. 빈 상자에 &quot;응답&quot;을 입력합니다. &#39;R&#39;을 대문자로 사용하고 **저장**&#x200B;을 클릭합니다.

   >[!NOTE]
   >
   >유형 선택 목록에서 기본값을 선택할 필요가 없습니다. Sales Connect는 Salesforce 인스턴스에서 이 활동 유형을 사용할 수 있으며 이에 따라 들어오는 활동의 작업 필드를 채웁니다.
