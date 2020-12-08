---
unique-page-id: 14352480
description: 회신 로깅(SFDC) - 마케팅 문서 - 제품 설명서
title: 회신 로깅(SFDC)
translation-type: tm+mt
source-git-commit: f28ff1acb0090892bdb92b75ef90d489db7abf20
workflow-type: tm+mt
source-wordcount: '285'
ht-degree: 0%

---


# 회신 로깅(SFDC) {#reply-logging-sfdc}

Sales Connect를 사용하면 잠재 고객의 응답을 Salesforce에 자동으로 기록할 수 있습니다. 이 작업을 수행할 수 있는 구조는 이메일 회신 추적을 기반으로 합니다. 잠재 고객의 응답을 추적할 수 있는 경우 Salesforce에 해당 응답을 기록할 수 있습니다.

## 요구 사항 {#requirements}

* API 로깅을 통해 이메일을 로깅해야 함
* 답글을 [추적할 수 있어야 함](http://docs.marketo.com/x/BYPS)
* Salesforce와 연결해야 함
* Salesforce [API 호출을 사용할 수 있어야](http://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm) 합니다.

## 회신 로깅 사용 {#enable-reply-logging}

1. 회신 로깅을 사용하려면 [Salesforce 설정](http://docs.marketo.com/pages/assets/external-link.jspa) 페이지로 넘어갈 수 있습니다. API 로깅이 해제되면 *답글 로그 확인 옵션이 표시됩니다.\
   *

   >[!NOTE]
   >
   >회신 로깅은 전송된 이메일을 로깅하기 위해 사용자가 지정한 것과 동일한 규칙을 따릅니다. 여기에는 이메일이 기록된 방법이 포함됩니다.대상 및 연락처중복 레코드가 있는 경우;일치하는 레코드를 찾을 수 없는 경우.

## Salesforce에서 회신 유형 설정 {#setting-type-to-reply-in-salesforce}

Salesforce 보고서에서 의미 있는 데이터를 얻는 것이 중요합니다. 유형 필드가 &#39;응답&#39;으로 채워지도록 하면 보고서를 통해 해당 데이터를 가져올 수 있습니다. 이 설정 `Salesforce admin` 을 받기 위해 파트너에게 문의하십시오.

1. **설정 **> **사용자 정의 **> **활동 **> **작업 필드로 이동합니다**.
1. 유형을 **클릭합니다**.
1. 작업 유형 선택 목록 값에서 새로 만들기를 **클릭합니다**.
1. 빈 상자에 &quot;Reply&quot;를 입력합니다. &#39;R&#39;을 대문자로 사용하고 [저장]을 **클릭합니다**.

   >[!NOTE]
   >
   >유형 선택 목록에서 기본값을 선택할 필요가 없습니다. Sales Connect는 이 활동 유형을 Salesforce 인스턴스에서 사용할 수 있으며 그에 따라 들어오는 활동의 작업 필드를 채웁니다.

