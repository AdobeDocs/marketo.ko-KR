---
description: 3단계 중 2단계 - Marketo Engage용 Veva CRM 사용자 만들기 - Marketo 문서 - 제품 설명서
title: 3단계 중 2단계 - Marketo Engage용 Veva CRM 사용자 만들기
exl-id: 78945192-36b0-4e0b-830a-f37eb0b83484
source-git-commit: 2ce44b7c44517a6fdb3f616a3d69b25158ea4ec9
workflow-type: tm+mt
source-wordcount: '636'
ht-degree: 0%

---

# 3단계 중 2단계: Marketo Engage용 Veva CRM 사용자 만들기 {#step-2-of-3-create-a-veeva-crm-user-for-marketo-engage}

>[!NOTE]
>
>이 문서의 단계는 Veva CRM 관리자가 완료해야 합니다.

>[!PREREQUISITES]
>
>[3단계 중 1단계: Salesforce(Professional)에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target=&quot;_blank&quot;}

이 문서에서는 Vec CRM 페이지 레이아웃으로 필드 권한을 사용자 지정하고 Marketo-Vec CRM 동기화 사용자를 만듭니다.

## 페이지 레이아웃 설정 {#set-page-layouts}

이 단계를 수행하면 Marketo 동기화 사용자가 사용자 지정 필드를 업데이트할 수 있습니다.

1. Enter 키를 누르지 않고 탐색 검색 막대에서 계정(개인 계정) 페이지 레이아웃을 클릭하고 연락처 아래의 페이지 레이아웃 을 클릭합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-1.png)

1. 클릭 **페이지 레이아웃**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-2.png)

1. 클릭 **HCP - Professional**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-3.png)

1. 를 클릭하고 새 항목을 드래그합니다. **섹션** 참조하십시오.

1. 섹션 이름에 &quot;Marketo&quot;을 입력하고 **확인**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-4.png)

1. 점수 필드를 클릭하여 Marketo 섹션으로 드래그합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-5.png)

1. 다음 필드에 대해 위의 단계를 반복합니다.

   * 유추 도시
   * 추론된 회사
   * 추론된 국가
   * 유추 수도권
   * 추론된 전화 영역 코드
   * 유추 우편 번호
   * 유추 주 지역

   >[!NOTE]
   >
   >Marketo에서 이러한 필드를 읽고/쓸 수 있도록 페이지 레이아웃에 이러한 필드가 있어야 합니다.

   >[!TIP]
   >
   >페이지 오른쪽으로 끌어서 두 개의 필드 열을 만듭니다. 필드를 한 쪽에서 다른 쪽으로 이동하여 열 길이의 균형을 맞출 수 있습니다.

1. HCP-Professional 레이아웃 작업을 마치면 를 클릭합니다. **저장**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-6.png)

>[!NOTE]
>
>다른 계정 페이지 레이아웃에 대해 이 작업을 반복합니다.

## 프로필 만들기 {#create-a-profile}

1. 클릭 **설정**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-7.png)

1. 탐색 검색 모음에 &quot;profiles&quot;를 입력하고 **프로필** 링크를 클릭합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-8.png)

1. 클릭 **새로 만들기**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-9.png)

1. 표준 사용자를 선택하고 프로필 이름을 &quot;Marketo-Salesforce 동기화&quot;로 지정한 다음 를 클릭합니다 **저장**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-10.png)

## 프로필 권한 설정 {#set-profile-permissions}

1. 클릭 **편집** 보안 권한을 설정하려면 다음을 수행하십시오.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-11.png)

1. 관리 권한 섹션에서 API 활성화 가 선택되어 있는지 확인합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-12.png)

   >[!TIP]
   >
   >암호가 만료되지 않음 상자를 선택해야 합니다.

1. 일반 사용자 권한 섹션에서 이벤트 편집 및 작업 편집 이 선택되어 있는지 확인합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-13.png)

1. 표준 객체 권한 섹션에서 계정 및 연락처에 대해 읽기, 만들기, 편집 및 삭제 권한이 선택되어 있는지 확인합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-14.png)

1. 사용자 지정 개체 권한 섹션에서 호출, 호출 키 메시지 및 원하는 기타 사용자 지정 개체에 대해 읽기 권한이 확인되었는지 확인합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-15.png)

1. 완료되면 를 클릭합니다 **저장** 를 클릭합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-16.png)

## 필드 권한 설정 {#set-field-permissions}

1. 동기화하는 데 필요한 사용자 지정 필드를 확인하려면 마케터와 상의하십시오.

>[!NOTE]
>
>이 단계에서는 Marketo에 표시되지 않아도 되는 필드를 차단하므로 불필요한 것들을 줄이고 동기화 속도를 높일 수 있습니다.

1. 프로필 세부 정보 페이지에서 필드 수준 보안 섹션으로 이동합니다. 보기 를 클릭하여 연락처 및 계정 객체에 대한 액세스 가능성을 편집합니다.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-17.png)

>[!TIP]
>
>조직의 요구 사항에 따라 다른 객체를 구성할 수 있습니다.

1. 각 개체에 대해 **편집**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-18.png)

불필요한 필드를 찾으려면 읽기 액세스 및 편집 액세스 권한이 있는지 확인하십시오 **un**&#x200B;확인됨. 클릭 **저장** 완료 시.

![](assets/step-2-of-3-create-a-veeva-crm-user-19.png)

>[!NOTE]
>
>사용자 지정 필드에 대한 액세스 가능성만 편집합니다.

1. 모든 불필요한 필드를 비활성화한 후 다음 개체 필드에 대해 읽기 액세스 및 편집 액세스 를 선택합니다. 완료되면 저장 을 클릭합니다.

<table>
 <tbody>
  <tr>
   <th>개체
   <th>필드
  </tr>
  <tr>
   <td>계정</td>
   <td>유형 필드</td>
  </tr>
  <tr>
   <td>이벤트</td>
   <td>모든 필드</td>
  </tr>
  <tr>
   <td>작업</td>
   <td>모든 필드</td>
  </tr>
 </tbody>
</table>

## 동기화 사용자 만들기 {#create-sync-user}

Marketo을 사용하려면 Vevar CRM에 액세스하려면 자격 증명이 필요합니다. 이 작업은 아래 단계를 사용하여 만든 전용 사용자로 가장 잘 수행됩니다.

>[!NOTE]
>
>조직에 추가 Vec CRM 라이센스가 없는 경우 시스템 관리자 프로필에서 기존 마케팅 사용자를 사용할 수 있습니다.

1. 탐색 검색 막대에서 &quot;users&quot;를 입력하고 **사용자** 사용자 관리에서 확인하십시오.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-20.png)

1. 클릭 **새 사용자**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-21.png)

1. 필수 필드를 입력하고 사용자 라이센스를 선택합니다. Salesforce, 프로필 설정: Marketo 동기화 사용자 를 클릭하고 **저장**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-22.png)

>[!TIP]
>
>입력한 전자 메일 주소가 올바른지 확인하십시오. 암호를 재설정하려면 동기화 사용자로 로그인해야 합니다.

훌륭해요! 이제 Marketo Engage이 Vevar CRM에 연결하는 데 사용할 수 있는 계정이 있습니다. 그렇게 합시다

>[!MORELIKETHIS]
>
>[3단계 중 3단계: Marketo 및 Veeva CRM 연결](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-3-of-3-connect-marketo-engage-and-veeva-crm.md){target=&quot;_blank&quot;}
