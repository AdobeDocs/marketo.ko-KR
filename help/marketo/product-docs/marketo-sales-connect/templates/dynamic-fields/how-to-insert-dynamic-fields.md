---
unique-page-id: 14352592
description: 동적 필드를 삽입하는 방법 - Marketing Docs - 제품 설명서
title: 동적 필드 삽입 방법
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '231'
ht-degree: 0%

---


# 동적 필드 삽입 방법 {#how-to-insert-dynamic-fields}

Adobe 솔루션을 사용하면 `{{first_name}}` 또는 `{{company}}`과 같은 사전 정의된 속성을 통해 이메일 템플릿을 개인화할 수 있습니다. 이러한 필드를 사용하면 각 연락처에 대해 개별적으로 입력하지 않고도 여러 연락처를 이메일로 보내고 이러한 필드를 자동으로 완료할 수 있습니다.

>[!TIP]
>
>&quot;first_name&quot; 및 &quot;company&quot; 필드는 `only fields that will look to both Sales Connect and Salesforce.` 웹 애플리케이션에 [](http://toutapp.com/login)연락처가 없는 경우 Salesforce를 통해 일치하는 이메일 주소로 연락처/리드 레코드를 찾을 수 있는지 확인합니다. 그런 다음 해당 레코드의 정보를 사용하여 필드를 채웁니다.

## 템플릿에 동적 필드 삽입 {#insert-a-dynamic-field-into-a-template}

1. 템플릿 및 **캠페인에서**&#x200B;편집할 템플릿을 찾아 템플릿 **편집을 클릭합니다**.
1. 동적 필드 **아웃을 클릭합니다**.

   >[!NOTE]
   >
   >Sales Connect에 있는 연락처를 이메일로 전송할 때 기본 동적 필드를 사용할 수 있습니다. 이러한 항목은 연락처에서 바로 가져옵니다.

Salesforce에 있는 연락처를 이메일로 전송하는 경우 Salesforce 동적 필드를 활용할 수 있습니다. 이 모든 것은 &quot;sfdc&quot;로 시작됩니다. Salesforce와 연결되어 있는 경우 이러한 필드는 Salesforce의 리드/연락처로 바로 연락하여 템플릿의 정보를 채웁니다.

## 제목 줄에 동적 필드 삽입 {#insert-dynamic-fields-in-a-subject-line}

적절한 서식을 유지할 수 있도록 이메일 제목 필드에 수동으로 복사하여 붙여넣으면 됩니다.
