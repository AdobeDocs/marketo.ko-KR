---
description: 3단계 중 1단계 - Veva CRM에 Marketo 필드 추가 - Marketo 문서 - 제품 설명서
title: 3단계 중 1단계 - Veva CRM에 Marketo 필드 추가
exl-id: a9a59e76-a7a4-4391-8169-922bd6acfb6d
source-git-commit: bb020cba0bb0cb65761e15cba05147b6e9fffe50
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 6%

---

# 3단계 중 1단계: Veva CRM에 Marketo 필드 추가 {#step-1-of-3-add-marketo-fields-to-veeva-crm}

>[!PREREQUISITES]
>
>Marketo Engage과 Vevar CRM 간에 데이터를 동기화하려면 Salesforce API에 액세스할 수 있어야 합니다.

Marketo Engage은 필드 세트를 사용하여 특정 종류의 마케팅 관련 정보를 캡처합니다. Veva CRM에서 이 데이터를 가져오려면 아래 지침을 따르십시오.

`1.` 연락처 개체의 Vec CRM에서 사용자 지정 필드를 만듭니다. 점수

`2.` 원하는 경우 추가 필드를 만들 수 있습니다(아래 표 참조).

이러한 모든 사용자 지정 필드는 선택 사항이며 Marketo Engage 및 Veva CRM을 동기화하는 데 필요하지 않습니다.

## Veva CRM에 Marketo 필드 추가 {#add-marketo-fields-to-veeva-crm}

위에 나열된 Veva CRM에서 리드에 사용자 지정 필드를 추가하고 접촉 개체를 추가합니다. 더 추가하려면 이 섹션의 끝에서 사용 가능한 필드 표를 참조하십시오.

점수 필드에 대해 다음 단계를 수행하여 추가합니다.

1. Veva CRM에 로그인하고 **설정**.

   ![](assets/step-1-of-3-add-marketo-fields-1.png)

1. 객체 및 필드 를 클릭하고 객체 관리자를 선택합니다.

   ![](assets/step-1-of-3-add-marketo-fields-2.png)

1. 검색 창에서 연락처를 검색합니다.

   ![](assets/step-1-of-3-add-marketo-fields-3.png)

1. Contact 개체를 클릭합니다.

1. 필드 및 관계를 선택합니다.

1. 클릭 **새로 만들기**.

   ![](assets/step-1-of-3-add-marketo-fields-4.png)

1. 적절한 필드 유형(점수 — 숫자)을 선택합니다.

   ![](assets/step-1-of-3-add-marketo-fields-5.png)

1. 클릭 **다음**.

   ![](assets/step-1-of-3-add-marketo-fields-6.png)

1. 아래 표에 표시된 대로 필드의 필드 레이블, 길이 및 필드 이름을 입력합니다.

<table>
 <tbody>
  <tr>
   <th>필드 레이블
   <th>필드 이름
   <th>데이터 유형
   <th>필드 속성
  </tr>
  <tr>
   <td>스코어</td>
   <td>mkto71_Lead_Score</td>
   <td>숫자</td>
   <td>길이 10<br/>
소수점 이하 자리 수 0</td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>Vevar CRM은 이 이름을 사용하여 API 이름을 만들 때 __c를 필드 이름에 추가합니다.

![](assets/step-1-of-3-add-marketo-fields-7.png)

>[!NOTE]
>
>텍스트 및 숫자 필드에는 길이가 필요하지만 날짜/시간 필드는 길이하지 않습니다. 설명은 선택 사항입니다.

1. 클릭 **다음**.

   ![](assets/step-1-of-3-add-marketo-fields-8.png)

1. 액세스 설정을 지정하고 **다음**.

1. 모든 역할을 표시 및 읽기 전용으로 설정합니다.

1. 동기화 사용자의 프로필에 대해 읽기 전용 확인란을 선택 취소합니다.

* 동기화 사용자로 시스템 관리자의 프로파일을 가진 사용자가 있는 경우 시스템 관리자 프로파일에 대한 읽기 전용 확인란을 선택 취소합니다(아래 참조).
* 동기화 사용자에 대한 사용자 지정 프로필을 만든 경우 해당 사용자 지정 프로필에 대한 읽기 전용 확인란을 선택 취소합니다.

   ![](assets/step-1-of-3-add-marketo-fields-9.png)

1. 필드를 표시할 페이지 레이아웃을 선택합니다.

1. 클릭 **저장 및 새로 만들기** 다시 돌아가서 다른 두 사용자 지정 필드를 각각 만듭니다.

1. 클릭 **저장** 3명 모두 다 끝냈을 때

   ![](assets/step-1-of-3-add-marketo-fields-10.png)

>[!NOTE]
>
>Contact 개체에 필드를 추가하면 개인 계정 개체에도 추가됩니다.

선택 사항: 아래 표에서 추가 사용자 지정 필드에 위의 절차를 따르십시오.

<table>
 <tbody>
  <tr>
   <th>필드 레이블
   <th>필드 이름
   <th>데이터 유형
   <th>필드 속성
  </tr>
  <tr>
   <td>유추된 시</td>
   <td>mkto71_Infined_City</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>회사 유추</td>
   <td>mkto71_Infined_Company</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>추정 국가</td>
   <td>mkto71_Infined_Country</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>대도시 지역 유추</td>
   <td>mkto71_Infined_Metropolitan_Area</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>전화번호 지역코드 유추</td>
   <td>mkto71_Infined_Phone_Area_Code</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>우편번호 유추</td>
   <td>mkto71_Infined_Postal_Code</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>유추된 주 지역</td>
   <td>mkto71_Infined_State_Region</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>새 필드를 만들 때 Marketo에서 자동으로 할당한 필드의 값은 Veeva CRM에서 즉시 사용할 수 없습니다. Marketo은 다음 업데이트로 두 시스템의 레코드에 대한 업데이트(즉, Marketo과 Veveva CRM 간에 동기화된 필드 중 하나에 대한 업데이트)가 발생하면 데이터를 Veva CRM에 동기화합니다.
