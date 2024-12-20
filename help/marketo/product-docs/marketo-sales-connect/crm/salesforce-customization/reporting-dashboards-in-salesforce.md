---
unique-page-id: 14352464
description: Salesforce의 보고 대시보드 - Marketo 문서 - 제품 설명서
title: Salesforce의 보고 대시보드
exl-id: f27ba3e1-210b-46df-81b5-e794826d36c7
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '201'
ht-degree: 0%

---

# Salesforce의 보고 대시보드 {#reporting-dashboards-in-salesforce}

아래에서 대시보드를 설정하는 방법을 알아봅니다.

## 보고서 열기 및 클릭 {#open-and-click-report}

1. **작업 및 이벤트** 레코드 종류를 선택하십시오.
1. 원하는 기간 및 계층 구조를 기반으로 보고서 매개 변수를 정의합니다.
1. 필터를 추가하여 Salesforce에 기록된 내부 이메일을 제거합니다(예: 회사/계정이 Marketo과 같지 않음).
1. **요약** 보고서 형식을 선택하십시오.
1. 제목, 할당됨 및 Marketo Sales Clicked/Marketo Sales Viewed 필드를 보고서에 추가합니다.
1. 필드 창에서 **수식 추가**&#x200B;를 두 번 클릭합니다.
1. 수식에 이름을 추가하고 형식에서 **백분율**&#x200B;을 선택한 다음 **그룹화 1**&#x200B;을 선택하십시오.
1. 요약 필드에서 **Marketo Sales Clicked/Marketo Sales Viewed,**, **합계**&#x200B;를 선택합니다.
1. 수식에 나누기 기호를 추가한 다음 요약 필드에서 **레코드 수**&#x200B;을(를) 선택합니다. _다른 이름으로 저장_.

## 템플릿 성능 보고서 {#template-performance-report}

1. 열기 및 클릭 보고서를 사용자 지정하여 _다른 이름으로 저장_ 필드를 포함합니다.

## 템플릿 볼륨 보고서 {#template-volume-report}

1. 템플릿 성과 보고서를 수정하고 &quot;Marketo 판매 템플릿이 공백과 같지 않음&quot; 필터를 포함합니다.
1. Marketo Sales Clicked 필드를 제거합니다. _다른 이름으로 저장_.

## 트렌드 계정 보고서 {#trending-accounts-report}

1. 계정 레코드 유형의 활동을 선택합니다.
1. 아래 표시된 대로 보고서 매개 변수 및 필드를 설정합니다. _다른 이름으로 저장_.
