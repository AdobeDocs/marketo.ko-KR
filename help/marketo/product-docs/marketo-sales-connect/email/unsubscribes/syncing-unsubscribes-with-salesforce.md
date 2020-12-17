---
unique-page-id: 14746188
description: Salesforce 가입 해지 동기화 - Marketing To Docs - 제품 설명서
title: Salesforce 가입 해지 동기화
translation-type: tm+mt
source-git-commit: 313266a67243f0c70c25010cb4825efb7f3db0ab
workflow-type: tm+mt
source-wordcount: '436'
ht-degree: 0%

---


# Salesforce {#syncing-unsubscribes-with-salesforce}에 가입 해지 동기화

## Salesforce에 동기화를 구독하지 않는 요구 사항 {#requirements-for-unsubscribes-to-sync-to-salesforce}

* 구독 취소 동기화를 활성화해야 합니다(야간 동기화용).
* Salesforce에 옵트아웃 필드를 설치해야 함
* Sales Connect의 개인 레코드에 Salesforce ID가 있어야 합니다.

**구독 취소 푸시**

Sales Connect에서 가입 해지가 수집되면 Salesforce에 실시간으로 푸시하여 동기화하도록 선택한 옵트아웃 필드를 업데이트합니다. Salesforce 동기화를 비활성화한 경우에도 이메일 옵트아웃으로 구독 취소를 계속 푸시합니다.

**동기화 구독 취소**

구독 취소 동기화(아래 3단계)를 활성화하면 야간 동기화를 활성화합니다. 동기화는 하루에 한 번 PST 오후 8시에 발생합니다. MSE/ToutApp의 모든 구독이 Salesforce의 옵트아웃 필드와 양방향 동기화됩니다.

## Salesforce에 구독 취소 동기화 구성 {#configure-unsubscribe-sync-to-salesforce}

사용자는 자신의 구독을 Marketing To와 동기화할 수 있는 표준 이메일 옵트아웃 필드와 동기화할지 또는 판매 구독 취소 및 마케팅 구독자를 차별화할 수 있도록 Marketing To 판매 옵트아웃 필드와 동기화할 수 있는지 결정할 수 있습니다.

1. [웹 응용 프로그램](http://toutapp.com/login)으로 이동하여 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-1.png)

1. 관리 설정에서 **가입 취소**&#x200B;를 선택합니다.

   ![](assets/two-2.png)

1. **Salesforce에 동기화**&#x200B;를 클릭한 다음 야간 동기화를 활성화합니다.

   ![](assets/three-2.png)

1. 동기화할 필드를 선택합니다.

   ![](assets/4.png)

   | **Salesforce 옵트아웃 필드에 동기화** | 기본적으로 선택되어 있는 경우 Salesforce 옵트아웃 필드만 업데이트합니다. |
   |---|---|
   | **Marketing To Sales Opt Out 필드와 동기화** | 판매 및 마케팅 구독을 분리하려면 이 옵션을 선택하여 추가 [마케팅 영업 그만두기 필드를 업데이트합니다.](#msoo) |

## 페이지 레이아웃 {#installing-the-opt-out-field-in-the-page-layout}에 그만두기 필드 설치

**이메일 옵트아웃**

이메일 옵트아웃은 Salesforce에서 설치할 수 있는 Salesforce의 표준 필드입니다. 설치하려면 Salesforce 관리자여야 합니다.

1. [Salesforce.com](http://Salesforce.com)으로 이동하여 로그인합니다.

   ![](assets/five-1.png)

1. 사용자 이름을 클릭하고 **설치**&#x200B;를 선택합니다.

   ![](assets/six-1.png)

1. 빠른 찾기 상자에서 담당자 또는 리드를 검색합니다. 이 시나리오에서는 연락처 페이지 레이아웃에 필드를 설치하지만 두 사람 모두에 대해 필드를 설치합니다.

   ![](assets/seven-1.png)

1. **페이지 레이아웃**&#x200B;을 선택합니다.

   ![](assets/eight-1.png)

1. 필드를 추가할 페이지 레이아웃 옆에 있는 **편집**&#x200B;을 선택합니다.

   ![](assets/nine.png)

1. **필드**&#x200B;를 선택합니다.

   ![](assets/ten.png)

1. 이메일 옵트아웃을 페이지 레이아웃으로 드래그하여 놓습니다.

   ![](assets/11.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/twelve.png)

## 마케팅 영업 그만두기 {#marketo-sales-opt-out}

마케팅 영업 그만두기 필드는 Marketing To Sales Connect 사용자 지정을 설치한 사용자가 사용할 수 있는 사용자 정의 필드입니다.

Marketing To Sales Connect Customizations를 Salesforce에 성공적으로 설치했으면 Marketing To Sales Opt Out 필드를 사용할 수 있게 됩니다.
