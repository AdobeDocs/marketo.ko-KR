---
unique-page-id: 14352592
description: 동적 필드를 삽입하는 방법 - Marketo 문서 - 제품 설명서
title: 동적 필드를 삽입하는 방법
exl-id: e4989350-872d-47a1-84b0-210e631ae23a
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 0%

---

# 동적 필드를 삽입하는 방법 {#how-to-insert-dynamic-fields}

Adobe에서는 다음과 같은 사전 정의된 특성을 사용하여 이메일 템플릿을 개인화할 수 있습니다 `{{first_name}}` 또는 `{{company}}`. 이러한 필드를 사용하면 각 연락처에 대해 별도로 입력하지 않고도 여러 연락처를 이메일로 보내고 이러한 필드를 자동으로 완료할 수 있습니다.

>[!TIP]
>
>first_name 및 &quot;company&quot; 필드는 Sales Connect와 Salesforce를 모두 확인할 유일한 필드입니다. 즉, 연락처가 [웹 애플리케이션](https://toutapp.com/login), Salesforce에서 이메일 주소가 일치하는 연락처/리드 레코드를 찾을 수 있는지 확인합니다. 그런 다음 해당 레코드의 정보를 사용하여 필드를 채웁니다.

## 템플릿에 동적 필드 삽입 {#insert-a-dynamic-field-into-a-template}

1. in **템플릿 및 캠페인**&#x200B;편집할 템플릿을 찾은 다음 **템플릿 편집**.

1. 클릭 **동적 필드 옵트아웃**.

   >[!NOTE]
   >
   >Sales Connect에 있는 담당자에게 이메일을 보낼 때 기본 동적 필드를 사용할 수 있습니다. 이러한 정보는 연락처에서 바로 가져옵니다.

Salesforce에 있는 연락처로 이메일을 보내는 경우 Salesforce 동적 필드를 활용할 수 있습니다. 이 모든 것은 &quot;sfdc&quot;로 시작합니다. Salesforce에 연결된 한 이러한 필드는 Salesforce에서 리드/연락처에 직접 호출하여 템플릿에 정보를 채웁니다.

## 제목 줄에 동적 필드 삽입 {#insert-dynamic-fields-in-a-subject-line}

이메일의 제목 필드에 수동으로 복사하여 붙여넣으면 서식이 제대로 지정되는지 확인합니다.
