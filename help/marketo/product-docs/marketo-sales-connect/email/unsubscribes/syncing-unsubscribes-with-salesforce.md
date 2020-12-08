---
unique-page-id: 14746188
description: Salesforce와 가입 해지 동기화 - Marketing To Docs - 제품 설명서
title: Salesforce와 가입 취소 동기화
translation-type: tm+mt
source-git-commit: 313266a67243f0c70c25010cb4825efb7f3db0ab
workflow-type: tm+mt
source-wordcount: '436'
ht-degree: 0%

---


# Salesforce와 가입 취소 동기화 {#syncing-unsubscribes-with-salesforce}

## Salesforce에 동기화 가입 해지 요구 사항 {#requirements-for-unsubscribes-to-sync-to-salesforce}

* 구독 취소 동기화를 활성화해야 합니다(야간 동기화용).
* Salesforce에 옵트아웃 필드를 설치해야 함
* Sales Connect의 개인 기록에는 Salesforce ID가 있어야 합니다.

**구독 취소 푸시**

Sales Connect에서 가입 해지가 수집되면 Salesforce에 실시간으로 푸시하여 동기화하도록 선택한 옵트아웃 필드를 업데이트합니다. Salesforce 동기화를 비활성화한 경우에도 이메일 옵트아웃으로 구독 취소를 계속 푸시합니다.

**동기화 구독 취소**

구독 취소 동기화를 활성화하면(아래 3단계) 야간 동기화를 활성화합니다. 동기화는 하루에 한 번 PST 오후 8시에 발생합니다. MSE/ToutApp의 모든 구독이 Salesforce의 옵트아웃 필드와 양방향 동기화됩니다.

## Salesforce에 구독 취소 동기화 구성 {#configure-unsubscribe-sync-to-salesforce}

사용자는 자신의 구독을 Marketing To와 동기화할 수 있는 표준 이메일 옵트아웃 필드와 동기화할지 또는 판매 구독 취소 및 마케팅 구독자를 차별화할 수 있도록 마케팅 옵트아웃 필드와 동기화할지 여부를 결정할 수 있습니다.

1. 웹 응용 프로그램으로 [가서 톱니바퀴 아이콘을 클릭하고](http://toutapp.com/login)설정을 선택합니다 ****.

   ![](assets/one-1.png)

1. 관리 설정에서 **가입 취소를 선택합니다**.

   ![](assets/two-2.png)

1. Salesforce **에 동기화를**&#x200B;클릭한 다음 야간 동기화를 활성화합니다.

   ![](assets/three-2.png)

1. 동기화할 필드를 선택합니다.

   ![](assets/4.png)

   | **Salesforce 옵트아웃 필드와 동기화 필드** | 기본적으로 선택되어 있으면 Salesforce 옵트아웃 필드만 업데이트됩니다. |
   |---|---|
   | **Marketing to Sales 옵트아웃 필드와 동기화 필드** | 판매 및 마케팅 가입을 분리하려면 이 옵션을 선택하여 추가 마케팅 대상 판매 [옵트아웃 필드를 업데이트합니다.](#msoo) |

## 페이지 레이아웃에 옵트아웃 필드 설치 {#installing-the-opt-out-field-in-the-page-layout}

**이메일 옵트아웃**

이메일 옵트아웃은 Salesforce에서 설치할 수 있는 Salesforce의 표준 필드입니다. Salesforce 관리자가 되어야 설치할 수 있습니다.

1. Salesforce.com [으로](http://Salesforce.com) 이동하여 로그인합니다.

   ![](assets/five-1.png)

1. 사용자 이름을 클릭하고 **설정을 선택합니다**.

   ![](assets/six-1.png)

1. 빠른 찾기 상자에서 연락처나 리드를 검색합니다. 이 시나리오에서는 연락처 페이지 레이아웃에 필드를 설치하지만 두 사람 모두에 대해 설치하려고 합니다.

   ![](assets/seven-1.png)

1. 페이지 레이아웃 **을 선택합니다**.

   ![](assets/eight-1.png)

1. 필드를 **추가할 페이지 레이아웃 옆에 있는 편집을** 선택합니다.

   ![](assets/nine.png)

1. 필드를 **선택합니다**.

   ![](assets/ten.png)

1. 이메일 옵트아웃을 페이지 레이아웃으로 드래그하여 놓습니다.

   ![](assets/11.png)

1. 저장을 **클릭합니다**.

   ![](assets/twelve.png)

## 마케팅 영업 그만두기 {#marketo-sales-opt-out}

마케팅 영업 그만두기 필드는 Marketing To Sales Connect 사용자 지정을 설치한 사용자가 사용할 수 있는 사용자 정의 필드입니다.

Marketing To Sales Connect Customization을 Salesforce에 성공적으로 설치한 경우 Marketing To Sales Opt Out 필드를 확인할 수 있습니다.
