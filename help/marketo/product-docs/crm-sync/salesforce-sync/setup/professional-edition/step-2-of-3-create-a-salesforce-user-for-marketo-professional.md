---
unique-page-id: 3571797
description: 2/3단계 - Marketo용 Salesforce 사용자 만들기(전문가) - Marketo 문서 - 제품 설명서
title: 2/3단계 - Marketo용 Salesforce 사용자 만들기(Professional)
exl-id: 7eb4bf89-b6e4-45e0-adee-e2976cb01dd3
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '423'
ht-degree: 8%

---

# 2/3단계: Marketo용 Salesforce 사용자 만들기(전문가) {#step-of-create-a-salesforce-user-for-marketo-professional}

>[!NOTE]
>
>이러한 단계는 Salesforce 관리자가 완료해야 합니다.

>[!PREREQUISITES]
>
>[1단계/3단계: Salesforce에 Marketo 필드 추가(Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-1-of-3-add-marketo-fields-to-salesforce-professional.md){target="_blank"}

이 문서에서는 Salesforce 페이지 레이아웃으로 필드 권한을 사용자 지정하고 Marketo-Salesforce 동기화 사용자를 만듭니다.

## 페이지 레이아웃 설정 {#set-page-layouts}

Salesforce Professional은 Salesforce Enterprise/Unlimited의 프로필과는 대조적으로 페이지 레이아웃으로 필드 수준 접근성을 설정합니다. 이 단계를 수행하면 Marketo 동기화 사용자가 사용자 정의 필드를 업데이트할 수 있습니다.

1. 유형 &quot;[!UICONTROL 페이지 레이아웃]을 누르지 않고 탐색 검색 막대에서 &quot; **[!UICONTROL 입력]**, 및 클릭 **[!UICONTROL 페이지 레이아웃]** 아래에 **[!UICONTROL 잠재 고객]**.

   ![](assets/image2016-2-26-12-3a58-3a32.png)

1. 클릭 **[!UICONTROL 편집]** 리드 레이아웃 옆에 있습니다.

   ![](assets/image2016-2-26-13-3a2-3a46.png)

1. 새 항목 클릭 및 드래그 **[!UICONTROL 섹션]** 를 페이지 레이아웃에 추가합니다.

   ![](assets/image2014-12-9-12-3a56-3a40.png)

1. 다음에 대한 &quot;Marketo&quot; 입력: **[!UICONTROL 섹션 이름]** 및 클릭 **[!UICONTROL 확인]**.

   ![](assets/image2014-12-9-12-3a56-3a52.png)

1. 필드를 클릭하고 드래그합니다 **[!UICONTROL 획득 날짜]** 대상: **Marketo** 섹션.

   ![](assets/image2014-12-9-12-3a57-3a0.png)

1. 다음 필드에 대해 위의 단계를 반복합니다.

   * 고객 확보 프로그램
   * 고객 확보 프로그램 Id
   * 이메일 옵트아웃
   * 추론된 시
   * 추론된 회사
   * 추론된 국가
   * 대도시 지역 유추
   * 전화번호 지역코드 유추
   * 추론된 우편번호
   * 유추된 주 지역
   * 잠재 고객 점수
   * 원래 레퍼러
   * 원본 검색 엔진
   * 원본 검색 구문
   * 원본 소스 정보
   * 원본 소스 유형

   >[!NOTE]
   >
   >Marketo에서 필드를 읽고 쓸 수 있도록 이러한 필드는 페이지 레이아웃에 있어야 합니다.

   >[!TIP]
   >
   >페이지의 오른쪽으로 끌어 놓아 필드에 대한 두 개의 열을 만듭니다. 열 길이의 균형을 맞추기 위해 필드를 한 쪽에서 다른 쪽으로 이동할 수 있습니다.

1. 클릭 **[!UICONTROL 저장]** 필드 추가를 마쳤습니다.

   ![](assets/image2014-12-9-12-3a57-3a10.png)

1. Salesforce에 대해 위의 모든 단계를 반복합니다 **[!UICONTROL 연락처 페이지 레이아웃]**.

   ![](assets/image2016-2-26-13-3a10-3a1.png)

1. 다음을 클릭하십시오. **[!UICONTROL 저장]** 을(를) 완료하면 **[!UICONTROL 연락처 페이지 레이아웃]**.

   ![](assets/image2014-12-9-12-3a57-3a30.png)

   >[!NOTE]
   >
   >다음을 확인하십시오. **[!UICONTROL 종일 이벤트]** 필드가 다음에 추가되었습니다. **[!UICONTROL 이벤트 페이지 레이아웃]**.

## 동기화 사용자 만들기 {#create-sync-user}

Marketo에 액세스하려면 자격 증명이 필요합니다. 이 작업은 아래 단계로 만든 전용 사용자로 수행하는 것이 가장 좋습니다.

>[!NOTE]
>
>조직에 추가 Salesforce 라이센스가 없는 경우 시스템 관리자 프로필로 기존 마케팅 사용자를 사용할 수 있습니다.

1. 탐색 검색 막대에 &quot;users&quot;를 입력하고 **[!UICONTROL 사용자]** 아래에 **[!UICONTROL 사용자 관리]**.

   ![](assets/image2014-12-9-12-3a57-3a42.png)

1. 클릭 **[!UICONTROL 새 사용자]**.

   ![](assets/image2014-12-9-12-3a58-3a1.png)

1. 필수 필드를 입력한 다음 **[!UICONTROL 사용자 라이선스: Salesforce]**, 를 설정합니다. **[!UICONTROL 프로필: 시스템 관리자]**, 확인 **[!UICONTROL 마케팅 사용자]** 및 클릭 **[!UICONTROL 저장]**.

   ![](assets/image2014-12-9-12-3a58-3a11.png)

   >[!TIP]
   >
   >입력한 이메일 주소가 유효한지 확인하십시오. 암호를 재설정하려면 동기화 사용자로 로그인해야 합니다.

훌륭합니다! 이제 Marketo에서 Salesforce에 연결하는 데 사용할 수 있는 계정이 생겼습니다. 해보자.

>[!MORELIKETHIS]
>
>[3단계/3단계: Marketo 및 Salesforce 연결(전문가)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-3-of-3-connect-marketo-and-salesforce-professional.md){target="_blank"}
