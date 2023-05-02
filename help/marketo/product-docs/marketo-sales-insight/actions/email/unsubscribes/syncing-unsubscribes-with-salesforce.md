---
description: Salesforce와 가입 해지 동기화 - Marketo 문서 - 제품 설명서
title: Salesforce와 가입 해지 동기화
exl-id: b5b0f625-e38c-4a03-81e7-010082001636
source-git-commit: 27ca6c3efc5d49729ca4473853688be9cc8cdbc9
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Salesforce와 가입 해지 동기화 {#syncing-unsubscribes-with-salesforce}

## Salesforce에 동기화 가입 해지를 위한 요구 사항 {#requirements-for-unsubscribes-to-sync-to-salesforce}

* 동기화 구독 취소를 활성화해야 합니다(야간 동기화의 경우)
* Salesforce에 옵트아웃 필드를 설치해야 합니다.
* Marketo Sales의 개인 레코드에는 Salesforce ID가 있어야 합니다.

**가입 해지됨 푸시**

Marketo Sales에서 구독을 취소하면 Salesforce에 실시간으로 푸시하고 동기화하도록 선택한 옵트아웃 필드를 업데이트합니다. Salesforce 동기화를 비활성화한 경우에는 이메일 옵트아웃으로 구독을 다시 푸시합니다.

**동기화 구독 취소**

구독 취소 동기화(아래 3단계)를 활성화하면 야간 동기화를 켜게 됩니다. 동기화는 매일 오후 8시 PST에 한 번 발생합니다. Salesforce의 옵트아웃 필드와 Marketo Sales의 모든 구독 취소가 양방향 동기화됩니다.

## Salesforce에 동기화 구독 취소 구성 {#configure-unsubscribe-sync-to-salesforce}

사용자는 구독 취소를 Marketo이 동기화할 수 있는 표준 이메일 옵트아웃 필드와 동기화할지, 아니면 Marketo 판매 옵트아웃 필드와 동기화하여 판매 구독 취소 및 마케팅 구독 취소를 구별할 수 있는지 결정할 수 있습니다.

1. 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/syncing-unsubscribes-with-salesforce-1.png)

1. 관리자 설정에서 을 선택합니다. **가입 해지됨**.

   ![](assets/syncing-unsubscribes-with-salesforce-2.png)

1. 을(를) 클릭합니다. **통합** 탭. Salesforce에 동기화에서 야간 동기화를 활성화합니다.

   ![](assets/syncing-unsubscribes-with-salesforce-3.png)

1. 동기화할 필드를 선택합니다.

   ![](assets/syncing-unsubscribes-with-salesforce-4.png)

   | 필드 | 설명 |
   |---|---|
   | **Salesforce 옵트아웃 필드에 동기화** | 기본적으로 선택되어 있으면 Salesforce 옵트아웃 필드만 업데이트됩니다. |
   | **Marketo 영업 옵트아웃 필드에 동기화** | 판매 및 마케팅 구독을 구분하려면 이 옵션을 선택하여 추가 정보를 업데이트하십시오 [Marketo Sales Opt Out 필드.](#msoo) |

## 페이지 레이아웃에 옵트아웃 필드 설치 {#installing-the-opt-out-field-in-the-page-layout}

**이메일 옵트아웃**

이메일 옵트아웃은 Salesforce에서 설치할 수 있는 Salesforce의 표준 필드입니다. Salesforce 관리자가 있어야 설치할 수 있습니다.

1. 이동 [Salesforce.com](https://salesforce.com) 로그인하고

   ![](assets/syncing-unsubscribes-with-salesforce-5.png)

1. 사용자 이름을 클릭하고 을 선택합니다 **설정**.

   ![](assets/syncing-unsubscribes-with-salesforce-6.png)

1. 빠른 찾기 상자에서 연락처 또는 리드를 검색합니다. 이 시나리오에서는 연락처 페이지 레이아웃에 필드를 설치하지만 두 개인 레코드 모두에 대해 설치하려고 합니다.

   ![](assets/syncing-unsubscribes-with-salesforce-7.png)

1. 선택 **페이지 레이아웃**.

   ![](assets/syncing-unsubscribes-with-salesforce-8.png)

1. 선택 **편집** 페이지 레이아웃 옆에 필드를 추가할 필드를 추가합니다.

   ![](assets/syncing-unsubscribes-with-salesforce-9.png)

1. 선택 **필드**.

   ![](assets/syncing-unsubscribes-with-salesforce-10.png)

1. 이메일 옵트아웃 을 페이지 레이아웃으로 끌어다 놓습니다.

   ![](assets/syncing-unsubscribes-with-salesforce-11.png)

1. 클릭 **저장**.

   ![](assets/syncing-unsubscribes-with-salesforce-12.png)

## Marketo 판매 옵트아웃 {#marketo-sales-opt-out}

Marketo 판매 옵트아웃 필드는 Marketo 판매 사용자 지정을 설치한 사용자가 사용할 수 있는 사용자 지정 필드입니다.

Salesforce에 Marketo Sales Customizations 를 성공적으로 설치하면 사용 가능한 Marketo Sales Opt Out 필드가 표시됩니다.
