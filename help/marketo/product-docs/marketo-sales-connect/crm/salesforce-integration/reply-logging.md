---
unique-page-id: 14352480
description: 응답 로깅(SFDC) - Marketo 문서 - 제품 설명서
title: 회신 로깅(SFDC)
exl-id: 11f84157-55b7-42a7-81d0-f5848adbb9f4
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---

# 회신 로깅(SFDC) {#reply-logging-sfdc}

Sales Connect를 통해 잠재 고객의 답변을 Salesforce에 자동으로 기록할 수 있습니다. 이를 수행할 수 있는 구조는 이메일 회신 추적을 기반으로 합니다. 잠재 고객의 회신을 추적할 수 있는 경우 Salesforce에 해당 회신을 기록할 수 있습니다.

## 요구 사항 {#requirements}

* API 로깅을 통해 이메일을 로깅해야 합니다.
* [회신을 추적할 수 있어야 합니다](/help/marketo/product-docs/marketo-sales-connect/email/common-tracking-questions/how-reply-tracking-works.md)
* [!DNL Salesforce]에 연결되어야 합니다.
* 사용 가능한 [!DNL Salesforce]개의 [API 호출](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm)이 있어야 합니다.

## 응답 로깅 활성화 {#enable-reply-logging}

1. 회신 로깅을 사용하려면 [!DNL Salesforce] 설정 페이지로 이동하세요. API 로깅을 해제하면 _Log Replies_&#x200B;을(를) 확인하는 옵션이 표시됩니다.

   >[!NOTE]
   >
   >회신 로깅은 전송된 전자 메일을 로깅하기 위해 적용한 것과 동일한 규칙을 따릅니다. 여기에는 이메일이 기록되는 방법, 잠재 고객 및 연락처에 대한 방법, 중복 레코드가 있는 경우, 일치하는 레코드가 없는 경우 등이 포함됩니다.

## [!DNL Salesforce]에서 형식을 회신으로 설정 중 {#setting-type-to-reply-in-salesforce}

[!DNL Salesforce] 보고서에서 의미 있는 데이터를 가져오는 것이 중요합니다. 유형 필드를 &#39;회신&#39;으로 채우게 하면 보고서를 통해 해당 데이터를 가져올 수 있습니다. 이 설정을 사용하려면 `[!DNL Salesforce] admin`과(와) 협력하세요.

1. **[!UICONTROL Setup]** > **[!UICONTROL Customize]** > **[!UICONTROL Activities]** > **[!UICONTROL Task Fields]**(으)로 이동합니다.
1. **[!UICONTROL Type]**&#x200B;를 클릭합니다.
1. 작업 유형 선택 목록 값에서 **[!UICONTROL New]**&#x200B;을(를) 클릭합니다.
1. 빈 상자에 &quot;Reply&quot;를 입력합니다. &#39;R&#39;을 대문자로 사용하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   >[!NOTE]
   >
   >유형 선택 목록에서 기본값 을 선택할 필요가 없습니다. [!DNL Sales Connect]은(는) 이 활동 유형을 [!DNL Salesforce] 인스턴스에서 사용할 수 있음을 확인하고 그에 따라 수신 활동의 작업 필드를 채웁니다.
