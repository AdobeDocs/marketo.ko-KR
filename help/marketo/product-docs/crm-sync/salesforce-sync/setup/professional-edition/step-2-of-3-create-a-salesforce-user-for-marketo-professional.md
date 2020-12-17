---
unique-page-id: 3571797
description: 3단계 중 2단계 - Marketing용 Salesforce 사용자 만들기(Professional) - Marketing Docs - 제품 설명서
title: 3단계 중 2단계 - Marketing용 Salesforce 사용자 만들기(Professional)
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '426'
ht-degree: 0%

---


# 3단계 중 2단계:Marketing(Professional) {#step-of-create-a-salesforce-user-for-marketo-professional}용 Salesforce 사용자 만들기

>[!NOTE]
>
>이러한 단계는 Salesforce 관리자가 완료해야 합니다.

>[!PREREQUISITES]
>
>* [3단계 중 1단계:Salesforce에 마케팅 필드 추가(Professional)](step-1-of-3-add-marketo-fields-to-salesforce-professional.md)

>



이 문서에서는 Salesforce 페이지 레이아웃을 사용하여 필드 권한을 사용자 정의하고 Marketing-Salesforce 동기화 사용자를 만듭니다.

## 페이지 레이아웃 설정 {#set-page-layouts}

Salesforce Professional은 Salesforce Enterprise/Unlimited의 프로필과 달리 페이지 레이아웃을 사용하여 필드 수준의 액세스 가능성을 설정합니다. 다음 단계를 수행하면 Marketing Cloud에서 사용자를 동기화하여 사용자 정의 필드를 업데이트할 수 있습니다.

1. **Enter**&#x200B;를 누르지 않고 탐색 검색 막대에 **페이지 레이아웃**&#x200B;을 입력하고 **리드** 아래의 **페이지 레이아웃**&#x200B;을 클릭합니다.

   ![](assets/image2016-2-26-12-3a58-3a32.png)

1. 리드 레이아웃 옆에 있는 **편집**&#x200B;을 클릭합니다.

   ![](assets/image2016-2-26-13-3a2-3a46.png)

1. 새 **섹션**&#x200B;을 클릭하고 페이지 레이아웃으로 드래그합니다.

   ![](assets/image2014-12-9-12-3a56-3a40.png)

1. **섹션 이름**&#x200B;에 &quot;Marketing&quot;을 입력하고 **확인**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-12-3a56-3a52.png)

1. **획득 날짜** 필드를 클릭하고 **Marketing** 섹션으로 드래그합니다.

   ![](assets/image2014-12-9-12-3a57-3a0.png)

1. 다음 필드에 대해 위 단계를 반복합니다.

   * 획득 프로그램
   * 획득 프로그램 ID
   * 이메일 옵트아웃
   * 유추 도시
   * 유추 회사
   * 유추 국가
   * 유추 대도시 영역
   * 유추 전화 영역 코드
   * 유추 우편 번호
   * 유추 상태 영역
   * 리드 점수
   * 원래 레퍼러
   * 원본 검색 엔진
   * 원래 검색 구문
   * 원본 소스 정보
   * 원본 소스 유형

   >[!NOTE]
   >
   >이러한 필드는 Marketing To가 해당 필드를 읽고 쓸 수 있도록 페이지 레이아웃에 있어야 합니다.

   >[!TIP]
   >
   >페이지의 오른쪽으로 아래로 드래그하여 두 개의 필드 열을 만듭니다. 열 길이를 균형을 맞추기 위해 한 쪽에서 다른 쪽으로 필드를 이동할 수 있습니다.

1. 필드 추가가 완료되면 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-12-3a57-3a10.png)

1. Salesforce **연락처 페이지 레이아웃**&#x200B;에 대해 위의 모든 단계를 반복합니다.

   ![](assets/image2016-2-26-13-3a10-3a1.png)

1. **연락처 페이지 레이아웃**&#x200B;을(를) 모두 마치면 **저장**&#x200B;을 클릭해야 합니다.

   ![](assets/image2014-12-9-12-3a57-3a30.png)

   >[!NOTE]
   >
   >**미리 알림**
   >
   >
   >**모든 날 이벤트** 필드가 **이벤트 페이지 레이아웃**&#x200B;에 추가되었는지 확인합니다.

## 동기화 사용자 만들기 {#create-sync-user}

Salesforce에 액세스하려면 Marketing에서 자격 증명이 필요합니다. 이 작업은 아래 단계를 통해 만든 전용 사용자를 사용하여 가장 잘 수행됩니다.

>[!NOTE]
>
>조직에 추가 Salesforce 라이선스가 없는 경우 **시스템 관리자** 프로필과 함께 기존 **Marketing 사용자**&#x200B;를 사용할 수 있습니다.

1. 탐색 도구 모음에서 &quot;사용자&quot;를 입력하고 **사용자 관리** 아래의 **사용자**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-12-3a57-3a42.png)

1. **새 사용자**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-12-3a58-3a1.png)

1. 필요한 필드를 입력하고 **사용자 라이센스:Salesforce**, **프로필:시스템 관리자**&#x200B;에서 **마케팅 사용자**&#x200B;를 선택하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-12-3a58-3a11.png)

   >[!TIP]
   >
   >입력한 이메일 주소가 유효한지 확인합니다. 암호를 재설정하려면 동기화 사용자로 로그인해야 합니다.

훌륭해! 이제 Marketing To가 Salesforce에 연결하는 데 사용할 수 있는 계정이 있습니다. 그렇게 합시다.

>[!NOTE]
>
>**관련 문서**
>
>* [3단계 중 3단계:Connect Marketing 및 Salesforce(Professional)](step-3-of-3-connect-marketo-and-salesforce-professional.md)

>



