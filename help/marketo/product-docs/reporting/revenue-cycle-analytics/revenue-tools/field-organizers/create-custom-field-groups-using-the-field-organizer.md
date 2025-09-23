---
unique-page-id: 10094404
description: Field Organizer - Marketo 문서 - 제품 설명서를 사용하여 사용자 정의 필드 그룹 만들기
title: 필드 조직자를 사용하여 사용자 정의 필드 그룹 만들기
exl-id: 0425a446-2c92-4a2a-85c4-e05c22118035
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '951'
ht-degree: 5%

---

# 필드 조직자를 사용하여 사용자 정의 필드 그룹 만들기 {#create-custom-field-groups-using-the-field-organizer}

수익 주기 탐색기의 모델 성과 분석(리드) 영역에서 보고를 위해 사용자 정의 필드 그룹을 활성화하려면 먼저 Marketo 리드 관리의 필드 구성 관리자를 통해 표준 또는 사용자 정의 필드를 보고용 그룹으로 분류해야 합니다. 리드 및 회사 속성에만 적용됩니다.
새 필드 구성자 대화 상자의 필드 드롭다운에서 표준 또는 사용자 정의 필드를 선택하면 그룹화할 필드와 연결된 Marketo Lead Management 데이터 유형이 필드 구성자에서 사용할 수 있는 세 개의 편집기(문자열, 정수 또는 날짜) 중 하나와 매핑됩니다.

| Marketo 리드 관리 데이터 유형 | Field Organizer 편집기 데이터 유형 |
|---|---|
| 문자열 | 문자열 |
| 이메일 | 문자열 |
| 정수 | 정수 |
| 텍스트 | 문자열 |
| URL | 문자열 |
| 참조 | 지원되지 않음 |
| 통화 | 정수 |
| 날짜/시간 | Date |
| 부울 | 지원되지 않음 |
| 전화 | 문자열 |
| Date | Date |
| 부동 | 정수 |
| 계산됨 | 지원되지 않음 |

다음 세 섹션에서는 문자열, 정수 또는 날짜 유형에 대한 사용자 정의 필드 그룹을 만드는 방법을 설명합니다.

## 사용자 정의 필드 그룹 만들기 - 문자열 편집기 {#create-custom-field-group-string-editor}

1. **[!UICONTROL Lead Database]**&#x200B;를 클릭합니다.

   ![](assets/one.png)

1. **[!UICONTROL New]**&#x200B;을(를) 클릭하고 **[!UICONTROL New Field Organizer]**&#x200B;을(를) 선택합니다.

   ![](assets/two.png)

1. **[!UICONTROL Field]**&#x200B;을(를) 클릭하고 문자열 편집기에 매핑되는 데이터 형식의 표준 또는 사용자 지정 필드를 선택합니다(이전 섹션의 표 참조). [!UICONTROL Country]이(가) 여기에 사용되었습니다.

   ![](assets/three.png)

1. **[!UICONTROL Create]**&#x200B;를 클릭합니다.

   ![](assets/four.png)

   새 사용자 정의 그룹이 필드 이름 > 필드 이름 그룹으로 표시되는 잠재 고객 데이터베이스 트리에 표시됩니다(예: 국가 > 국가 그룹).

   ![](assets/4.5.png)

1. 연필 아이콘을 클릭하여 이름을 사용자 지정합니다. 예를 들어 &quot;국가 그룹&quot;의 이름을 &quot;대륙&quot;으로 바꿀 수 있습니다. 원하는 새 이름을 입력하고 상자에서 바깥쪽을 클릭하여 자동 저장합니다.

   ![](assets/five.png)

1. 기본적으로 모든 데이터 값은 &quot;[!UICONTROL Other]&quot; 하위 그룹에 배치됩니다. 데이터 값을 분류하려면 **[!UICONTROL Add Group]**&#x200B;을(를) 클릭하여 하위 그룹을 만들고 이름을 지정하십시오.

   >[!NOTE]
   >
   >최대 10개의 하위 그룹을 추가하여 데이터 값을 분류할 수 있습니다. 생성된 각 하위 그룹에는 ID 번호가 할당됩니다.

   이 예에서는 대부분의 대륙에 대해 그룹이 생성되었습니다.

   ![](assets/six.png)

   >[!NOTE]
   >
   >하위 그룹을 삭제하려면 하위 그룹 이름 옆에 있는 빨간색 X를 클릭하면 됩니다. 그룹에 데이터 값이 있으면 데이터 값이 기본 그룹인 [!UICONTROL Other]&#x200B;(으)로 이동됩니다.

1. 캔버스에서 데이터 값을 강조 표시하고 데이터 값을 적절한 하위 그룹으로 끌어다 놓습니다.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >하위 그룹에서 데이터 값을 제거하려면 데이터 값을 기타 기본 그룹에 재할당합니다.

1. 캔버스 바로 위에 있는 왼쪽 상단 모서리의 필터 옵션을 사용하여 하나 이상의 하위 그룹의 데이터 값을 선택하고 볼 수 있습니다. 필터 선택을 기반으로 한 데이터 값이 캔버스에 표시됩니다.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >그룹이 정의되면 Marketo 리드 관리의 수익 주기 분석 탭을 통해 모델 성과 분석(리드)에서 보고할 사용자 정의 필드 그룹을 활성화할 수 있습니다.

## 사용자 정의 필드 그룹 만들기 - 정수 편집기 {#create-custom-field-group-integer-editor}

1. **[!UICONTROL Lead Database]**&#x200B;를 클릭합니다.

   ![](assets/one.png)

1. **[!UICONTROL New]**&#x200B;을(를) 클릭하고 **[!UICONTROL New Field Organizer]**&#x200B;을(를) 선택합니다.

   ![](assets/two.png)

1. **[!UICONTROL Field]**&#x200B;을(를) 클릭하고 문자열 편집기에 매핑되는 데이터 형식의 표준 또는 사용자 지정 필드를 선택합니다(이전 섹션의 표 참조). [!UICONTROL Annual Revenue]이(가) 여기에 사용되었습니다.

   ![](assets/nine.png)

1. **[!UICONTROL Create]**&#x200B;를 클릭합니다.

   ![](assets/9.5.png)

   새 사용자 정의 그룹이 필드 이름 > 필드 이름 그룹으로 표시되는 잠재 고객 데이터베이스 트리에 표시됩니다(예: 연간 수익 > 연간 수익 그룹).

   ![](assets/9.6.png)

1. 정수 편집기 위의 기본 사용자 지정 그룹 이름을 클릭하여 이름을 사용자 지정합니다. 예를 들어 &quot;Annual Revenue Group&quot;의 이름을 &quot;Annual Revenue by Size&quot;로 바꿀 수 있습니다. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/eleven.png)

   정수 편집기를 사용하면 여러 하위 그룹을 만들어 크기별로 각 하위 그룹을 정의할 수 있습니다. 이 예에서는 Small, Medium 및 Enterprise 비즈니스에 대해 세 개의 그룹이 생성됩니다.

1. 첫 번째 그룹을 추가하려면 **[!UICONTROL Group Name]** 필드에 이름을 입력하고(예: Small) **[!UICONTROL Group Range]** 필드에 최대값을 입력합니다(예: 200000). **[!UICONTROL Add Group]**&#x200B;를 클릭합니다.

   ![](assets/twelve.png)

   방금 입력한 그룹 아래에 빈 그룹 항목이 표시됩니다. 아래 예제는 소규모, Medium 및 엔터프라이즈 비즈니스에 대한 항목을 보여 줍니다.

   >[!NOTE]
   >
   >최대 10개의 하위 그룹을 추가하여 데이터 값을 분류할 수 있습니다. 각 그룹 범위 항목은 이전 항목을 기반으로 합니다. 마지막으로 만든 사용자 정의 하위 그룹의 마지막 그룹 범위 항목을 비워 두면 최대 데이터 값이 설정되지 않습니다.

1. 요약 탭을 클릭하여 설정을 저장하고 검토합니다.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >하위 그룹을 삭제하려면 하위 그룹 이름 옆에 있는 빨간색 X를 클릭합니다.

1. 요약 페이지에서 설정을 검토합니다.

   ![](assets/13.5.png)

   >[!NOTE]
   >
   >그룹이 정의되면 Marketo 리드 관리의 수익 주기 분석 탭을 통해 모델 성과 분석(리드)에서 보고할 사용자 정의 필드 그룹을 활성화할 수 있습니다.

## 사용자 정의 필드 그룹 만들기 - 날짜 편집기 {#create-custom-field-group-date-editor}

1. **[!UICONTROL Lead Database]**&#x200B;를 클릭합니다.

   ![](assets/one.png)

1. **[!UICONTROL New]**&#x200B;을(를) 클릭하고 **[!UICONTROL New Field Organizer]**&#x200B;을(를) 선택합니다.

   ![](assets/two.png)

1. **[!UICONTROL Field]**&#x200B;을(를) 클릭하고 문자열 편집기에 매핑되는 데이터 형식의 표준 또는 사용자 지정 필드를 선택합니다(이전 섹션의 표 참조). [!UICONTROL Acquisition Date]이(가) 여기에 사용되었습니다.

   ![](assets/fourteen.png)

1. **[!UICONTROL Create]**&#x200B;를 클릭합니다.

   ![](assets/14.5.png)

   새 사용자 정의 그룹이 필드 이름 > 필드 이름 그룹으로 표시되는 잠재 고객 데이터베이스 트리에 표시됩니다(예: 획득 날짜 > 획득 날짜 그룹).

   ![](assets/14.6.png)

1. 날짜 편집기 위의 기본 사용자 지정 그룹 이름을 클릭하여 이름을 사용자 지정합니다. 예를 들어 &quot;획득 날짜 그룹&quot;의 이름을 &quot;획득 날짜 카테고리&quot;로 변경할 수 있습니다. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/fifteen.png)

   날짜 편집기를 사용하면 여러 하위 그룹을 만들고 날짜별로 각 하위 그룹을 정의할 수 있습니다. 이 예에서는 Q1-15 리드, Q2-15 리드 및 Q3-15 리드의 세 가지 그룹이 만들어집니다.

1. 첫 번째 그룹을 추가하려면 **[!UICONTROL Group Name]** 필드에 이름을 입력하고(예: Q1-15 리드) 날짜 필드에 리드를 획득한 날짜 또는 그 이전 날짜를 입력합니다(예: Q1-15의 마지막 날 2015/3/31). **[!UICONTROL Add Group]**&#x200B;를 클릭합니다.

   ![](assets/sixteen.png)

   >[!NOTE]
   >
   >최대 10개의 하위 그룹을 추가하여 데이터 값을 분류할 수 있습니다. 각 [!UICONTROL Group Range] 항목은 이전 항목을 기반으로 합니다. 마지막으로 만든 사용자 지정 하위 그룹의 마지막 [!UICONTROL Group Range] 항목을 비워 두면 종료 날짜 값이 설정되지 않습니다.

   아래 예제는 2015년 1분기~3분기 리드에 대한 항목을 보여 줍니다.

   ![](assets/16.5.png)

   다 됐습니다! 잘했어.
