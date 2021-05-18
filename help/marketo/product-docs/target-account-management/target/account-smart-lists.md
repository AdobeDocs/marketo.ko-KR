---
unique-page-id: 11378814
description: 계정 스마트 목록 - Marketo 문서 - 제품 설명서
title: 계정 스마트 목록
exl-id: fbdfb2b8-0061-467d-be89-527744a659a9
source-git-commit: b491f476c4facc6343559a0acf5d5527e9afc618
workflow-type: tm+mt
source-wordcount: '467'
ht-degree: 0%

---

# 계정 스마트 목록 {#account-smart-lists}

고부가가치 계정을 빠르고 정확하게 식별하는 방법을 설명합니다.

>[!NOTE]
>
>이 기능은 TAM과 Adobe Marketo Engage 차세대 사용자 환경이 모두 활성화된 사용자만 사용할 수 있습니다.

## 계정 스마트 목록 만들기 {#create-an-account-smart-list}

1. Marketo에서 **마케팅 활동**&#x200B;으로 이동합니다.

   ![](assets/account-smart-lists-1.png)

1. 원하는 프로그램을 찾아 선택합니다.

   ![](assets/account-smart-lists-2.png)

1. **새로 만들기** 드롭다운을 클릭하고 **새 로컬 자산**&#x200B;을 선택합니다.

   ![](assets/account-smart-lists-3.png)

1. **계정 스마트 목록**&#x200B;을 클릭합니다.

   ![](assets/account-smart-lists-4.png)

1. 이름을 입력하고 **만들기**(설명 및 레이블은 선택 사항)를 클릭합니다.

   ![](assets/account-smart-lists-5.png)

계정 스마트 목록이 생성되었습니다! 규칙을 정의하는 단계는 아래를 참조하십시오.

## 계정 스마트 목록 규칙 {#account-smart-list-rules}

Account Smart Lists는 다음과 같이 표준 Smart Lists와 유사하게 작동하며 주목할 만한 예외 사항이 있습니다.컨테이너.

1. 계정 스마트 목록을 정의하려면 **계정 스마트 목록 규칙** 탭을 클릭합니다.

   ![](assets/account-smart-lists-6.png)

1. 원하는 계정 필터를 선택합니다. 이 예에서는 _산업이 의료_&#x200B;입니다.

   ![](assets/account-smart-lists-7.png)

   ![](assets/account-smart-lists-8.png)

1. 일치하는 사람 필터를 선택합니다. 이 예에서는 _주가 캘리포니아_&#x200B;임을 선택합니다.

   ![](assets/account-smart-lists-9.png)

**선택적 단계**:여기 컨테이너가 들어 있습니다. 추가 일치된 사람 필터를 선택하는 경우 첫 번째 필터 아래에 놓거나 _에서_&#x200B;을(를) 드래그하여 컨테이너를 만들 수 있습니다. 이 예에서는 _작업 제목이 CFO_&#x200B;를 추가하여 컨테이너를 만듭니다.

![](assets/account-smart-lists-10.png)

컨테이너가 어떻게 보이는지 여기 있습니다.

![](assets/account-smart-lists-11.png)

>[!NOTE]
>
>필터 컨테이너를 만들면 &quot;and&quot; 규칙이 만들어지고, 이것은 결합된 모든 결과만 반환합니다. 이 예에서, CFO로 등록된 사람과 함께 캘리포니아에 _와_&#x200B;에 있는 것과 함께 의료 업계에 해당하는 계정을 만듭니다. 컨테이너를 사용하지 않으려면 기존 컨테이너 아래/위에 필터를 놓으면 됩니다.

바로 그거야! Account Smart List를 활용할 수 있는 방법을 보려면 아래 섹션을 확인하십시오.

>[!TIP]
>
>표준 스마트 목록과 마찬가지로 고급 로직을 사용하여 결과를 더 세밀하게 조정할 수 있습니다. 3개 이상의 필터가 필요합니다. Account Smart Lists에서는 필터 자체에 포함된 필터 수에 관계없이 하나의 컨테이너가 하나의 필터와 같습니다.

## 계정 스마트 목록 작업 {#account-smart-list-actions}

계정 스마트 목록의 개요 탭에서 몇 가지 작업 옵션을 확인할 수 있습니다.

**내보내기**:이렇게 하면 계정 스마트 목록 결과가 CSV로 내보내집니다.

**클론**:계정 스마트 목록 사본을 만듭니다.

**광고 네트워크에 보내기**:목록을 새 일치 대상으로 LinkedIn에 보냅니다.

_계정 스마트 목록의 사람 구성원_ 필터를 사용하여 표준 스마트 캠페인/목록에서 계정 스마트 목록을 참조할 수도 있습니다.

![](assets/account-smart-lists-12.png)

>[!NOTE]
>
>계정 스마트 목록의 사람 구성원 결과는 계정 스마트 목록에서 일치하는 사람 필터를 통해 찾은 사람뿐만 아니라 식별된 계정의 모든 사람을 표시합니다.

>[!NOTE]
>
>**정의**
>
>**계정 스마트 목록의 사람**:이 경우 단어 &quot;member&quot;는 계정 자체를 의미하므로 &quot;people member&quot;는 해당 계정의 실제 사람(Marketo 레코드)을 의미합니다.
