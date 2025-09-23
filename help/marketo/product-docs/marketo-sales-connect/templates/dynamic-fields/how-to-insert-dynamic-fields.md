---
unique-page-id: 14352592
description: 동적 필드를 삽입하는 방법 - Marketo 문서 - 제품 설명서
title: 동적 필드를 삽입하는 방법
exl-id: e4989350-872d-47a1-84b0-210e631ae23a
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 4%

---

# 동적 필드를 삽입하는 방법 {#how-to-insert-dynamic-fields}

`{{first_name}}` 또는 `{{company}}`과(와) 같은 미리 정의된 특성을 사용하여 전자 메일 템플릿을 개인화할 수 있습니다. 이러한 필드를 사용하면 각 연락처에 대해 별도로 입력할 필요 없이 여러 연락처를 이메일로 보내고 이러한 필드를 자동으로 완성할 수 있습니다.

>[!TIP]
>
>[!DNL Sales Connect]과(와) [!DNL Salesforce]을(를) 모두 볼 수 있는 필드는 &quot;first_name&quot; 및 &quot;company&quot; 필드뿐입니다. 즉, 연락처가 [웹 응용 프로그램](https://toutapp.com/login)에 없는 경우 [!DNL Salesforce]에서 일치하는 전자 메일 주소가 있는 연락처/잠재 고객 레코드를 찾을 수 있는지 확인합니다. 그런 다음 해당 레코드의 정보를 사용하여 필드를 채웁니다.

## 템플릿에 동적 필드 삽입 {#insert-a-dynamic-field-into-a-template}

1. **[!UICONTROL Templates & Campaigns]**&#x200B;에서 편집할 템플릿을 찾은 다음 **[!UICONTROL Edit Template]**&#x200B;을(를) 클릭합니다.

1. **[!UICONTROL Tout Dynamic Fields]**&#x200B;를 클릭합니다.

   >[!NOTE]
   >
   >[!DNL Sales Connect]에 있는 연락처로 전자 메일을 보낼 때 기본 동적 필드를 사용할 수 있습니다. 이것들은 접촉에서 바로 당겨질 것이다.

[!DNL Salesforce]에 있는 대화 상대에게 전자 메일을 보내는 경우 [!DNL Salesforce] 동적 필드를 사용할 수 있습니다. 이러한 모든 항목은 &quot;sfdc&quot;로 시작합니다. [!DNL Salesforce]에 연결되어 있는 동안에는 해당 필드가 [!DNL Salesforce]의 잠재 고객/연락처로 직접 호출되어 템플릿의 정보를 채웁니다.

## 제목 줄에 동적 필드 삽입 {#insert-dynamic-fields-in-a-subject-line}

전자 메일의 제목 필드에 수동으로 복사하여 붙여 넣기만 하면 적절한 서식이 지정되었는지 확인할 수 있습니다.
