---
unique-page-id: 42762519
description: 기존 고객을 위한 구성 - Marketing Docs - 제품 설명서
title: 기존 고객을 위한 구성
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---


# 기존 고객을 위한 구성 {#configuration-for-existing-customers}

새 인사이트 대시보드 사용을 시작하려면 다음 구성을 설정하십시오.

>[!PREREQUISITES]
>
>Salesforce 패키지를 최신 버전으로 업그레이드했는지 확인하십시오.

## Marketing To에서 판매 통찰력 구성 {#configure-sales-insight-in-marketo}

1. 브라우저에서 새 탭을 열어 Marketing To 계정에서 Marketing to Sales Insights 자격 증명을 얻으십시오.
1. 관리 **영역으로** 이동합니다.

   ![](assets/configure-1.png)

1. Sales **Insight를 클릭합니다**.

   ![](assets/configure-2.png)

1. 보기를 **클릭하여** Rest API 자격 증명을 채웁니다.

   ![](assets/configure-3.png)

1. 확인 팝업이 표시됩니다. 확인을 **클릭합니다**.

## Salesforce에서 세일즈 인사이트 구성 {#configure-sales-insight-in-salesforce}

1. Salesforce에서 **설정을 클릭합니다**.

   ![](assets/sfdc-1.png)

1. 원격 사이트 설정 **을 검색하고 선택합니다**.

   ![](assets/sfdc-2.png)

1. 새 **원격 사이트를 클릭합니다**.

   ![](assets/sfdc-3.png)

1. 원격 사이트 이름(예: &quot;MarketingRestAPI&quot;)과 원격 사이트 URL(Marketing의 Rest API 구성 패널의 API URL)을 입력합니다.

   ![](assets/sfdc-4.png)

1. 저장을 **클릭합니다**.

   ![](assets/sfdc-5.png)

   이제 Rest API에 대한 원격 사이트 설정을 만들었습니다.

## Marketing to Sales Insight 액세스 {#access-marketo-sales-insight}

1. Marketing의 Sales Insight 관리 페이지의 Rest API 패널에서 자격 증명을 복사합니다. Salesforce의 Sales Insight 구성 페이지의 Rest API 섹션에 붙여 넣습니다.
1. API 비밀 키를 입력합니다.

   ![](assets/config.png)

