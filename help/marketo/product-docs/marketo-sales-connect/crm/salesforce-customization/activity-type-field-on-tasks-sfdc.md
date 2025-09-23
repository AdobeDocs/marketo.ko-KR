---
unique-page-id: 14352476
description: 작업(SFDC)의 활동 유형 필드 - Marketo 문서 - 제품 설명서
title: 작업의 활동 유형 필드 (SFDC)
exl-id: b291e641-d3af-4667-a01c-cd491cd87add
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 7%

---

# 작업의 활동 유형 필드 (SFDC) {#activity-type-field-on-tasks-sfdc}

[!DNL Sales Connect]을(를) 통해 [!DNL Salesforce]의 활동으로 전자 메일 및 호출을 기록할 수 있습니다. [!DNL Salesforce]에 중요한 데이터가 있는 핵심 부분에 [!UICONTROL Type] 필드가 올바른 값을 채우는 중입니다.

>[!NOTE]
>
>BCC를 통해 전자 메일을 로깅하면 작업 유형 선택 목록이 표시되지 않고 BCC 주소를 통해 [!DNL Salesforce]에 전달되므로 대신 형식 필드를 자동으로 &quot;전자 메일&quot;로 채웁니다.

## 요구 사항 {#requirements}

* [!DNL Salesforce]과(와) 연결
* 작업 유형 선택 목록에서 선택한 기본 유형 값 없음
* 호출, 회신 및 이메일은 모두 작업 유형 선택 목록에 있어야 합니다(대소문자 구분 안 함).
* 유형 필드의 값에 대해 작업을 수행하는 워크플로우 또는 트리거 없음

## 설정 {#setup}

먼저 올바른 선택 목록 값이 있는지 확인합니다. 선택 목록을 변경하려면 [!DNL Salesforce] 관리자의 도움이 필요합니다.

1. [Salesforce.com](https://salesforce.com)&#x200B;(으)로 이동하여 오른쪽 상단의 설치 프로그램을 클릭합니다.
1. **[!UICONTROL Customize]**&#x200B;를 클릭합니다.
1. **[!UICONTROL Activities]**&#x200B;를 클릭합니다.
1. **[!UICONTROL Task Fields]**&#x200B;를 클릭합니다.
1. **[!UICONTROL Type]**&#x200B;를 클릭합니다.
1. 이제 작업 유형 선택 목록에 있습니다. &#39;기본값&#39;이 선택되어 있지 않은지 확인하십시오.
1. [!UICONTROL Type], [!UICONTROL Email] 및 [!UICONTROL Call]에 대해 [!UICONTROL Reply] 값이 나열되어 있는지 확인하십시오.

이제 이 기능이 제대로 작동했으므로 유형 필드가 기록된 이메일, 호출 및 답글에 대한 해당 값을 채우는 것을 볼 수 있습니다. 이 값은 Sales Connect 미리 알림 작업에 _not_&#x200B;이(가) 채워집니다.

>[!NOTE]
>
>&#39;답글&#39;이 값으로 표시되지 않으면 **[!UICONTROL New]**&#x200B;을(를) 클릭하여 추가하십시오. [!DNL Salesforce]에서 &#39;Reply&#39;는 표준 값이 아닙니다.
