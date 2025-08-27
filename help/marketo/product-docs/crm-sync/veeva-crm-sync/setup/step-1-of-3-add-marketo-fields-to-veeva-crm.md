---
description: 1단계/3단계 -  [!DNL Veeva] CRM에 Marketo 필드 추가 - Marketo 문서 - 제품 설명서
title: 1단계/3단계 -  [!DNL Veeva] CRM에 Marketo 필드 추가
exl-id: a9a59e76-a7a4-4391-8169-922bd6acfb6d
feature: Veeva CRM
source-git-commit: 0c0dd3355f979577ec194f9e8f935615515905c0
workflow-type: tm+mt
source-wordcount: '485'
ht-degree: 8%

---

# 1단계/3단계: [!DNL Veeva] CRM에 Marketo 필드 추가 {#step-1-of-3-add-marketo-fields-to-veeva-crm}

>[!PREREQUISITES]
>
>[!DNL Veeva] CRM 인스턴스는 Salesforce API에 액세스하여 Marketo Engage과 [!DNL Veeva] CRM 간에 데이터를 동기화해야 합니다.

Marketo Engage은 일련의 필드를 사용하여 특정 종류의 마케팅 관련 정보를 캡처합니다. 이 데이터를 [!DNL Veeva] CRM에 포함하려면 아래 지침을 따르십시오.

1. 연락처 개체의 [!DNL Veeva] CRM에 사용자 지정 필드를 만듭니다. 점수
1. 원하는 경우 추가 필드를 만들 수 있습니다(아래 표 참조).

이러한 사용자 지정 필드는 모두 선택 사항이며 Marketo Engage 및 [!DNL Veeva] CRM을 동기화하는 데 필요하지 않습니다.

## [!DNL Veeva] CRM에 Marketo 필드 추가 {#add-marketo-fields-to-veeva-crm}

위에 나열된 [!DNL Veeva] CRM의 잠재 고객 및 연락처 개체에 사용자 지정 필드를 추가합니다. 더 추가하려면 이 섹션의 끝에 있는 사용 가능한 필드 표를 참조하십시오.

점수 필드에 대해 다음 단계를 수행하여 추가합니다.

1. [!DNL Veeva] CRM에 로그인하고 **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-1-of-3-add-marketo-fields-1.png)

1. **[!UICONTROL Objects and Fields]**&#x200B;을(를) 클릭하고 **[!UICONTROL Object Manager]**&#x200B;을(를) 선택합니다.

   ![](assets/step-1-of-3-add-marketo-fields-2.png)

1. 검색 창에서 &quot;Contact&quot;를 검색합니다.

   ![](assets/step-1-of-3-add-marketo-fields-3.png)

1. **[!UICONTROL Contact]** 개체를 클릭합니다.

1. **[!UICONTROL Fields and Relationships]**&#x200B;를 선택합니다.

1. **[!UICONTROL New]**&#x200B;를 클릭합니다.

   ![](assets/step-1-of-3-add-marketo-fields-4.png)

1. 적절한 필드 유형을 선택합니다(점수 - 숫자의 경우).

   ![](assets/step-1-of-3-add-marketo-fields-5.png)

1. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/step-1-of-3-add-marketo-fields-6.png)

1. 아래 표에 표시된 대로 필드에 대한 **[!UICONTROL Field Label]**, **[!UICONTROL Length]** 및 **[!UICONTROL Field Name]**&#x200B;을(를) 입력합니다.

<table>
 <tbody>
  <tr>
   <th>필드 레이블
   <th>필드 이름
   <th>데이터 유형
   <th>필드 속성
  </tr>
  <tr>
   <td>점수</td>
   <td>mkto71_Lead_Score</td>
   <td>숫자</td>
   <td>길이 10<br/>
소수점 이하 자리 수 0</td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>[!DNL Veeva] CRM에서 __c를 사용하여 API 이름을 만들 때 필드 이름에 추가합니다.

![](assets/step-1-of-3-add-marketo-fields-7.png)

>[!NOTE]
>
>텍스트 및 숫자 필드는 길이가 필요하지만 날짜/시간 필드는 길이가 필요하지 않습니다. 설명은 선택 사항입니다.

1. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/step-1-of-3-add-marketo-fields-8.png)

1. 액세스 설정을 지정하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

1. 모든 역할을 **[!UICONTROL Visible]** 및 **[!UICONTROL Read-Only]**(으)로 설정합니다.

1. 동기화 사용자의 프로필에 대한 **[!UICONTROL Read-Only]** 확인란의 선택을 취소합니다.

* 시스템 관리자 프로필을 동기화 사용자로 가진 사용자가 있는 경우 시스템 관리자 프로필에 대한 [!UICONTROL Read-Only] 확인란의 선택을 취소합니다(아래 참조).
* 동기화 사용자에 대한 사용자 지정 프로필을 만든 경우 해당 사용자 지정 프로필에 대한 [!UICONTROL Read-Only] 확인란의 선택을 취소합니다.

  ![](assets/step-1-of-3-add-marketo-fields-9.png)

1. 필드를 표시할 페이지 레이아웃을 선택합니다.

1. **[!UICONTROL Save & New]**&#x200B;을(를) 클릭하여 돌아가서 다른 두 개의 사용자 지정 필드를 각각 만드십시오.

1. 세 가지 작업을 모두 마치면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-1-of-3-add-marketo-fields-10.png)

>[!NOTE]
>
>연락처 개체에 필드를 추가하면 개인 계정 개체에도 추가됩니다.

선택 사항: 아래 표의 추가 사용자 정의 필드에 대해 위의 절차를 사용하십시오.

<table>
 <tbody>
  <tr>
   <th>필드 레이블
   <th>필드 이름
   <th>데이터 유형
   <th>필드 속성
  </tr>
  <tr>
   <td>추론된 시</td>
   <td>mkto71_Inferred_City</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>추론된 회사</td>
   <td>mkto71_Inferred_Company</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>추론된 국가</td>
   <td>mkto71_Inferred_Country</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>대도시 지역 유추</td>
   <td>mkto71_Inferred_Metropolitan_Area</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>전화번호 지역코드 유추</td>
   <td>mkto71_Inferred_Phone_Area_Code</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>추론된 우편번호</td>
   <td>mkto71_Inferred_Postal_Code</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
  <tr>
   <td>유추된 주 지역</td>
   <td>mkto71_Inferred_State_Region</td>
   <td>텍스트</td>
   <td>길이 255</td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>새 필드를 만들 때 Marketo에서 자동으로 할당한 필드의 값을 [!DNL Veeva] CRM에서 바로 사용할 수 없습니다. Marketo은 두 시스템의 레코드에 대한 다음 업데이트(즉, Marketo과 [!DNL Veeva] CRM 간에 동기화되는 필드 중 하나에 대한 업데이트) 시 데이터를 [!DNL Veeva] CRM에 동기화합니다.
