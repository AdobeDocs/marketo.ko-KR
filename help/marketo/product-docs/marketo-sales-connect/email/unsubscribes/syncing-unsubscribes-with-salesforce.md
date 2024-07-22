---
unique-page-id: 14746188
description: Salesforce - Marketo 문서 - 제품 설명서와 구독 취소 동기화
title: Salesforce와 구독 취소 동기화
exl-id: 1694d7bf-d2f6-4950-8a3e-c7d89c37b276
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '436'
ht-degree: 0%

---

# Salesforce와 구독 취소 동기화 {#syncing-unsubscribes-with-salesforce}

## Salesforce에 동기화하기 위한 구독 취소 요구 사항 {#requirements-for-unsubscribes-to-sync-to-salesforce}

* 구독 취소 동기화를 활성화해야 합니다(야간 동기화의 경우).
* 옵트아웃 필드는 Salesforce에 설치해야 합니다.
* Sales Connect의 개인 레코드에는 Salesforce ID가 있어야 합니다.

**구독 취소 푸시**

Sales Connect에서 구독 취소가 수집되면 실시간으로 Salesforce에 푸시하고 동기화하도록 선택한 옵트아웃 필드 중 하나를 업데이트합니다. Salesforce 동기화를 비활성화한 경우에도 구독 취소가 이메일 옵트아웃에 푸시됩니다.

**동기화 구독 취소**

구독 취소 동기화(아래 3단계)를 활성화하면 야간 동기화가 켜집니다. 동기화는 매일 오후 8시(PST) 경에 한 번 발생합니다. Marketo Sales의 모든 구독 취소 와 Salesforce의 옵트아웃 필드를 양방향으로 동기화합니다.

## Salesforce에 구독 취소 동기화 구성 {#configure-unsubscribe-sync-to-salesforce}

사용자는 Marketo도 동기화할 수 있는 표준 이메일 옵트아웃 필드를 사용하여 구독 취소를 동기화할 것인지 또는 판매 구독 취소와 마케팅 구독 취소를 구분할 수 있도록 Marketo 판매 옵트아웃 필드를 사용하여 동기화할 수 있는지 여부를 결정할 수 있습니다.

1. [웹 응용 프로그램](https://toutapp.com/login)(으)로 이동하여 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-1.png)

1. 관리자 설정에서 **구독 취소**&#x200B;를 선택합니다.

   ![](assets/two-2.png)

1. **Salesforce와 동기화**&#x200B;를 클릭한 다음 야간 동기화를 활성화합니다.

   ![](assets/three-2.png)

1. 동기화할 필드를 선택합니다.

   ![](assets/4.png)

   | 필드 | 설명 |
   |---|---|
   | **Salesforce 옵트아웃 필드에 동기화** | 기본적으로 선택되어 있으며 Salesforce 옵트아웃 필드만 업데이트합니다. |
   | **Marketo 판매 옵트아웃 필드에 동기화** | 판매 및 마케팅 구독 취소를 구분하려면 이 옵션을 선택하여 [Marketo 판매 옵트아웃 필드를 추가로 업데이트합니다.](#msoo) |

## 페이지 레이아웃에 옵트아웃 필드 설치 {#installing-the-opt-out-field-in-the-page-layout}

**이메일 옵트아웃**

이메일 옵트아웃은 Salesforce에서 설치할 수 있는 Salesforce의 표준 필드입니다. 설치하려면 Salesforce 관리자여야 합니다.

1. [Salesforce.com](https://salesforce.com)(으)로 이동하여 로그인합니다.

   ![](assets/five-1.png)

1. 사용자 이름을 클릭하고 **설치**&#x200B;를 선택합니다.

   ![](assets/six-1.png)

1. 빠른 찾기 상자에서 연락처 또는 잠재 고객을 검색합니다. 이 시나리오에서는 연락처 페이지 레이아웃에 필드를 설치하고 있지만 두 개인 레코드 모두에 대해 설치해야 합니다.

   ![](assets/seven-1.png)

1. **페이지 레이아웃**&#x200B;을 선택합니다.

   ![](assets/eight-1.png)

1. 필드를 추가할 페이지 레이아웃 옆에 있는 **편집**&#x200B;을(를) 선택합니다.

   ![](assets/nine.png)

1. **필드**&#x200B;을(를) 선택하십시오.

   ![](assets/ten.png)

1. 이메일 옵트아웃을 페이지 레이아웃으로 끌어서 놓습니다.

   ![](assets/11.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/twelve.png)

## Marketo 판매 옵트아웃 {#marketo-sales-opt-out}

Marketo 판매 옵트아웃 필드는 Marketo Sales Connect 사용자 정의 를 설치한 사용자가 사용할 수 있는 사용자 정의 필드입니다.

Salesforce에 Marketo Sales Connect 사용자 정의 기능을 성공적으로 설치하면 Marketo Sales Opt Out 필드가 표시됩니다.
