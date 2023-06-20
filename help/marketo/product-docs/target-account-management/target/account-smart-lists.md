---
unique-page-id: 11378814
description: 계정 스마트 목록 - Marketo 문서 - 제품 설명서
title: 계정 스마트 목록
exl-id: fbdfb2b8-0061-467d-be89-527744a659a9
source-git-commit: 4d88547ecdc25a2a1e0de49fab1493bbefd6800b
workflow-type: tm+mt
source-wordcount: '508'
ht-degree: 0%

---

# 계정 스마트 목록 {#account-smart-lists}

다음은 고가치 계정을 빠르고 정확하게 식별하는 방법입니다.

>[!NOTE]
>
>이 기능은 Target 계정 관리 추가 기능과 라이선스가 부여된 TAM이 모두 있는 사용자만 사용할 수 있습니다.

## 계정 스마트 목록 만들기 {#create-an-account-smart-list}

1. Marketo에서 **마케팅 활동**.

   ![](assets/account-smart-lists-1.png)

1. 원하는 프로그램을 찾아 선택합니다.

   ![](assets/account-smart-lists-2.png)

1. 다음을 클릭합니다. **신규** 드롭다운 및 선택 **새 로컬 자산**.

   ![](assets/account-smart-lists-3.png)

1. 클릭 **계정 스마트 목록**.

   ![](assets/account-smart-lists-4.png)

1. 이름을 입력하고 클릭 **만들기** (설명 및 레이블은 선택 사항입니다.)

   ![](assets/account-smart-lists-5.png)

계정 스마트 목록이 생성되었습니다! 해당 규칙을 정의하는 단계는 아래를 참조하십시오.

## 계정 스마트 목록 규칙 {#account-smart-list-rules}

계정 스마트 목록은 표준 스마트 목록과 유사하게 작동하며, 주목할 만한 예외는 컨테이너입니다.

1. 계정 스마트 목록을 정의하려면 **계정 스마트 목록 규칙** 탭.

   ![](assets/account-smart-lists-6.png)

1. 원하는 계정 필터를 선택합니다. 이 예제에서는 다음을 선택합니다 _헬스케어라는 산업_.

   ![](assets/account-smart-lists-7.png)

   ![](assets/account-smart-lists-8.png)

   >[!NOTE]
   >
   >에 사용된 ICP 지표 데이터 [계정 프로파일링 순위 및 조정](/help/marketo/product-docs/target-account-management/account-profiling/account-profiling-ranking-and-tuning.md) 은 계정 스마트 목록에서 사용할 사용자 지정 계정 속성으로 표시됩니다. 이 사용자 지정 속성 데이터는 계정 프로필 모델이 생성/업데이트된 시기를 기반으로 합니다.

1. 일치하는 개인 필터를 선택합니다. 이 예제에서는 다음을 선택합니다 _캘리포니아 주_.

   ![](assets/account-smart-lists-9.png)

**선택적 단계**: 컨테이너가 들어오는 위치입니다. 추가 [일치하는 사용자] 필터를 선택한 경우 첫 번째 필터 아래에 놓을 수 있습니다. 또는 _위치:_ 컨테이너 만들기. 이 예제에서는 를 추가하여 컨테이너를 생성합니다 _직함이 CFO임_.

![](assets/account-smart-lists-10.png)

컨테이너의 모습은 다음과 같습니다.

![](assets/account-smart-lists-11.png)

>[!NOTE]
>
>필터 컨테이너를 만들면 &quot;and&quot; 규칙이 만들어집니다. 즉, 결합된 모든 결과만 반환됩니다. 이 예에서는 캘리포니아에 있는 의료 산업과 함께 계정이 있습니다 _및_ CFO로 나열된 다른 사용자와 컨테이너를 활용하지 않으려면 필터를 기존 필터 아래/위에 놓기만 하면 됩니다.

다 됐습니다! 계정 스마트 목록을 활용하는 방법을 살펴보려면 아래 섹션을 확인하십시오.

>[!TIP]
>
>표준 스마트 목록과 마찬가지로 고급 로직을 사용하여 결과를 세분화할 수 있습니다. 이렇게 하려면 필터가 세 개 이상 필요하며 계정 스마트 목록에서 하나의 컨테이너(필터 자체에 포함된 필터의 수에 관계없이)는 하나의 필터와 같습니다.

## 계정 스마트 목록 작업 {#account-smart-list-actions}

계정 스마트 목록의 개요 탭에 몇 가지 작업 옵션이 표시됩니다.

**내보내기**: 계정 스마트 목록의 결과를 CSV로 내보냅니다.

**복제**: 계정 스마트 목록의 복사본을 만듭니다.

**광고 네트워크로 보내기**: 목록을 새로운 일치하는 대상자로 LinkedIn에 보냅니다.

다음을 사용하여 표준 스마트 캠페인/목록에서 계정 스마트 목록을 참조할 수도 있습니다. _계정 스마트 목록의 사용자 멤버_ 필터.

![](assets/account-smart-lists-12.png)

>[!NOTE]
>
>계정 스마트 목록의 사람 구성원의 결과는 계정 스마트 목록에서 일치하는 사람 필터를 통해 발견되는 사람뿐만 아니라 식별된 계정의 모든 사람을 표시합니다.

>[!NOTE]
>
>**정의**
>
>**계정 스마트 목록의 사용자 멤버**: 이 경우 &quot;구성원&quot;이라는 단어는 계정 자체를 의미하므로 &quot;구성원&quot;은 해당 계정의 실제 사용자(Marketo 레코드)를 의미합니다.
