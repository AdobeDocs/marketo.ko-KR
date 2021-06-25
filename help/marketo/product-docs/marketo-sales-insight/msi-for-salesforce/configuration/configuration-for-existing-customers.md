---
unique-page-id: 42762519
description: 기존 고객을 위한 구성 - Marketo 문서 - 제품 설명서
title: 기존 고객을 위한 구성
exl-id: e365f6b5-a3ec-492e-9348-2d3226e6c7eb
source-git-commit: 0701121597f33580ada09fe975c1740cb55f945d
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# 기존 고객을 위한 구성 {#configuration-for-existing-customers}

새 인사이트 대시보드 사용을 시작하려면 다음 구성을 설정하십시오.

>[!PREREQUISITES]
>
>Salesforce 패키지를 최신 버전으로 업그레이드했는지 확인하십시오

## Marketo에서 Sales Insight 구성 {#configure-sales-insight-in-marketo}

1. 브라우저에서 새 탭을 열어 Marketo 계정에서 Marketo 영업 인사이트 자격 증명을 가져옵니다.

1. **Admin** 영역으로 이동합니다.

   ![](assets/configuration-for-existing-customers-1.png)

1. **Sales Insight**&#x200B;를 클릭합니다.

   ![](assets/configuration-for-existing-customers-2.png)

1. **보기**&#x200B;를 클릭하여 Rest API 자격 증명을 채웁니다.

   ![](assets/configuration-for-existing-customers-3.png)

1. 확인 팝업이 표시됩니다. **확인**&#x200B;을 클릭합니다.

## Salesforce에서 Sales Insight 구성 {#configure-sales-insight-in-salesforce}

1. Salesforce에서 **설정**&#x200B;을 클릭합니다.

   ![](assets/configuration-for-existing-customers-4.png)

1. **원격 사이트 설정**&#x200B;을 검색하고 선택합니다.

   ![](assets/configuration-for-existing-customers-5.png)

1. **새 원격 사이트**&#x200B;를 클릭합니다.

   ![](assets/configuration-for-existing-customers-6.png)

1. 원격 사이트 이름(&quot;MarketoRestAPI&quot; 등)과 원격 사이트 URL(Marketo의 Rest API 구성 패널에서 API URL)을 입력합니다.

   ![](assets/configuration-for-existing-customers-7.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/configuration-for-existing-customers-8.png)

   이제 Rest API에 대한 원격 사이트 설정을 만들었습니다.

## Marketo Sales Insight 액세스 {#access-marketo-sales-insight}

1. Marketo의 Sales Insight Admin 페이지에 있는 Rest API 패널에서 자격 증명을 복사합니다. Salesforce의 Sales Insight Configuration 페이지에 있는 Rest API 섹션에 붙여넣습니다.

1. API 암호 키를 입력합니다.

   ![](assets/configuration-for-existing-customers-9.png)
