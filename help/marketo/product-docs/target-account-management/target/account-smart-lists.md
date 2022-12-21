---
unique-page-id: 11378814
description: Account Smart List - Marketo 문서 - 제품 설명서
title: 계정 스마트 목록
exl-id: fbdfb2b8-0061-467d-be89-527744a659a9
source-git-commit: e4d581ab258a875747a6d5323764e8b4a3949cba
workflow-type: tm+mt
source-wordcount: '467'
ht-degree: 0%

---

# 계정 스마트 목록 {#account-smart-lists}

다음은 고부가가치 고객을 신속하고 정확하게 식별하는 방법입니다.

>[!NOTE]
>
>이 기능은 Target 계정 관리 추가 기능 및 TAM 라이센스가 발급된 사용자만 사용할 수 있습니다.

## 계정 스마트 목록 만들기 {#create-an-account-smart-list}

1. Marketo에서 **마케팅 활동**.

   ![](assets/account-smart-lists-1.png)

1. 원하는 프로그램을 찾아 선택합니다.

   ![](assets/account-smart-lists-2.png)

1. 을(를) 클릭합니다. **새로 만들기** 드롭다운 및 선택 **새 로컬 자산**.

   ![](assets/account-smart-lists-3.png)

1. 클릭 **계정 Smart List**.

   ![](assets/account-smart-lists-4.png)

1. 이름을 입력하고 **만들기** (설명 및 레이블은 선택 사항입니다).

   ![](assets/account-smart-lists-5.png)

계정 스마트 목록이 생성되었습니다! 해당 규칙을 정의하는 단계는 아래를 참조하십시오.

## 계정 Smart List 규칙 {#account-smart-list-rules}

계정 스마트 목록은 표준 Smart List와 유사하며, 주목할 만한 예외가 있습니다. 컨테이너.

1. 계정 Smart List를 정의하려면 **계정 Smart List 규칙** 탭.

   ![](assets/account-smart-lists-6.png)

1. 원하는 계정 필터를 선택합니다. 이 예제에서는 _의료 분야는 산업입니다_.

   ![](assets/account-smart-lists-7.png)

   ![](assets/account-smart-lists-8.png)

1. 일치하는 개인 필터를 선택합니다. 이 예제에서는 _주: 캘리포니아_.

   ![](assets/account-smart-lists-9.png)

**옵션 단계**: 여기 컨테이너가 들어오는 곳이에요. 추가 대응 개인 필터를 선택하는 경우 첫 번째 필터 아래에 놓을 수 있습니다. 또는 _in_ 컨테이너를 만들고, 이 예제에서는 컨테이너를 추가하고 _직함은 CFO입니다._.

![](assets/account-smart-lists-10.png)

여기 컨테이너가 어떻게 보이는지 나와 있습니다.

![](assets/account-smart-lists-11.png)

>[!NOTE]
>
>필터 컨테이너를 만들면 &quot;and&quot; 규칙이 만들어집니다. 이는 결합된 모든 결과만 반환함을 의미합니다. 이 예에서는 캘리포니아에 있는 와 함께 의료 산업과 관련됩니다 _및_ CFO로 등록된 사람과 컨테이너를 사용하지 않으려면 기존 필터 아래/위에 필터를 놓습니다.

그게 다야! 계정 Smart List를 활용하는 방법을 보려면 아래 섹션을 확인하십시오.

>[!TIP]
>
>표준 스마트 목록과 마찬가지로 고급 논리를 사용하여 결과를 세분화할 수 있습니다. 세 개 이상의 필터가 필요하며, 계정 스마트 목록에서 한 개의 컨테이너(필터 자체에 포함된 필터 수에 상관없이)가 하나의 필터와 동일합니다.

## 계정 Smart List 작업 {#account-smart-list-actions}

계정 스마트 목록의 개요 탭에서 몇 가지 작업 옵션을 볼 수 있습니다.

**내보내기**: 이렇게 하면 계정 스마트 목록 결과가 CSV로 내보내집니다.

**복제**: 계정 Smart List를 복사합니다.

**광고 네트워크로 보내기**: 목록을 새 일치하는 대상으로 LinkedIn에 보냅니다.

표준 Smart Campaign/List에서 _계정 스마트 목록의 사용자_ 필터.

![](assets/account-smart-lists-12.png)

>[!NOTE]
>
>계정 스마트 목록의 사람 구성원 결과는 계정 스마트 목록에서 일치하는 사람 필터를 통해 발견된 사람뿐만 아니라 식별된 계정의 모든 사람을 표시합니다.

>[!NOTE]
>
>**정의**
>
>**계정 스마트 목록의 사용자**: 이 경우 &quot;member&quot;라는 단어는 계정 자체를 의미하므로 &quot;people member&quot;는 해당 계정의 실제 사람(Marketo 레코드)을 의미합니다.
