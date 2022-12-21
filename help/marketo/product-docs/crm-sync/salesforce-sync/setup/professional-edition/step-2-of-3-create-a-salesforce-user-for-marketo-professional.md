---
unique-page-id: 3571797
description: 3단계 중 2단계 - Marketo용 Salesforce 사용자 만들기(Professional) - Marketo 문서 - 제품 설명서
title: 3단계 중 2단계 - Marketo용 Salesforce 사용자 만들기(Professional)
exl-id: 7eb4bf89-b6e4-45e0-adee-e2976cb01dd3
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '423'
ht-degree: 4%

---

# 3단계 중 2단계: Marketo용 Salesforce 사용자 만들기(Professional) {#step-of-create-a-salesforce-user-for-marketo-professional}

>[!NOTE]
>
>Salesforce 관리자가 이러한 단계를 완료해야 합니다

>[!PREREQUISITES]
>
>[3단계 중 1단계: Salesforce(Professional)에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-1-of-3-add-marketo-fields-to-salesforce-professional.md)

이 문서에서는 Salesforce 페이지 레이아웃으로 필드 권한을 사용자 지정하고 Marketo-Salesforce 동기화 사용자를 만듭니다.

## 페이지 레이아웃 설정 {#set-page-layouts}

Salesforce Professional은 Salesforce Enterprise/Unlimited의 프로필과 대조적으로 페이지 레이아웃을 사용하여 필드 수준 액세스 가능성을 설정합니다. 이 단계를 수행하면 Marketo 동기화 사용자가 사용자 지정 필드를 업데이트할 수 있습니다.

1. 유형 **페이지 레이아웃** 탐색 막대에서 **Enter 키**&#x200B;를 클릭하고 **페이지 레이아웃** 아래에 **리드**.

   ![](assets/image2016-2-26-12-3a58-3a32.png)

1. 클릭 **편집** 리드 레이아웃 옆에 표시됩니다.

   ![](assets/image2016-2-26-13-3a2-3a46.png)

1. 를 클릭하고 새 항목을 드래그합니다. **섹션** 참조하십시오.

   ![](assets/image2014-12-9-12-3a56-3a40.png)

1. 에 &quot;Marketo&quot;을 입력합니다. **섹션 이름** 을(를) 클릭합니다. **확인**.

   ![](assets/image2014-12-9-12-3a56-3a52.png)

1. 필드를 클릭하고 드래그합니다. **획득 날짜** 로 **Marketo** 섹션을 참조하십시오.

   ![](assets/image2014-12-9-12-3a57-3a0.png)

1. 다음 필드에 대해 위의 단계를 반복합니다.

   * 획득 프로그램
   * 획득 프로그램 Id
   * 이메일 옵트아웃
   * 유추된 시
   * 추론된 회사
   * 추론된 국가
   * 대도시 지역 유추
   * 전화번호 지역코드 유추
   * 우편번호 유추
   * 유추된 주 지역
   * 잠재 고객 점수
   * 원래 레퍼러
   * 원래 검색 엔진
   * 원래 검색 구
   * 원본 소스 정보
   * 원본 소스 유형

   >[!NOTE]
   >
   >Marketo에서 이러한 필드를 읽고/쓸 수 있도록 페이지 레이아웃에 이러한 필드가 있어야 합니다.

   >[!TIP]
   >
   >페이지 오른쪽으로 끌어서 두 개의 필드 열을 만듭니다. 필드를 한 쪽에서 다른 쪽으로 이동하여 열 길이의 균형을 맞출 수 있습니다.

1. 클릭 **저장** 필드 추가를 완료하면 됩니다.

   ![](assets/image2014-12-9-12-3a57-3a10.png)

1. Salesforce에 대해 위의 단계를 모두 반복합니다 **연락처 페이지 레이아웃**.

   ![](assets/image2016-2-26-13-3a10-3a1.png)

1. 클릭 기억 **저장** 당신이 **연락처 페이지 레이아웃**.

   ![](assets/image2014-12-9-12-3a57-3a30.png)

   >[!NOTE]
   >
   >다음을 확인합니다. **하루 종일 이벤트** 필드가 **이벤트 페이지 레이아웃**.

## 동기화 사용자 만들기 {#create-sync-user}

Marketo에는 Salesforce에 액세스하려면 자격 증명이 필요합니다. 이 작업은 아래 단계를 사용하여 만든 전용 사용자로 가장 잘 수행됩니다.

>[!NOTE]
>
>조직에 추가 Salesforce 라이센스가 없는 경우 기존 **마케팅 사용자** 사용 **시스템 관리자** 프로필 참조.

1. 탐색 검색 막대에서 &quot;users&quot;를 입력하고 **사용자** 아래에 **사용자 관리**.

   ![](assets/image2014-12-9-12-3a57-3a42.png)

1. 클릭 **새 사용자**.

   ![](assets/image2014-12-9-12-3a58-3a1.png)

1. 필수 필드를 입력하고 을(를) 선택합니다. **사용자 라이센스: Salesforce**, 설정 **프로필: 시스템 관리자**, check **마케팅 사용자** 을(를) 클릭합니다. **저장**.

   ![](assets/image2014-12-9-12-3a58-3a11.png)

   >[!TIP]
   >
   >입력한 전자 메일 주소가 올바른지 확인하십시오. 암호를 재설정하려면 동기화 사용자로 로그인해야 합니다.

훌륭해요! 이제 Marketo에서 Salesforce에 연결하는 데 사용할 수 있는 계정이 있습니다. 그렇게 합시다

>[!MORELIKETHIS]
>
>[3단계 중 3단계: Marketo 및 Salesforce 연결(Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-3-of-3-connect-marketo-and-salesforce-professional.md)
