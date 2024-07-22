---
unique-page-id: 2360362
description: 1단계/3단계 - Salesforce에 Marketo 필드 추가(Enterprise/Unlimited) - Marketo 문서 - 제품 설명서
title: 1단계/3단계 - Salesforce에 Marketo 필드 추가(Enterprise/Unlimited)
exl-id: bcfba281-0d4b-42c3-b52a-ce1c3da884ba
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '766'
ht-degree: 7%

---

# 1단계/3단계: Salesforce에 Marketo 필드 추가(Enterprise/Unlimited) {#step-of-add-marketo-fields-to-salesforce-enterprise-unlimited}

>[!PREREQUISITES]
>
>Marketo Engage과 Salesforce 간에 동기화하려면 Salesforce API에 대한 액세스 권한이 있어야 합니다.

Marketo은 일련의 필드를 사용하여 특정 종류의 마케팅 관련 정보를 캡처합니다. 이 데이터를 Salesforce에 보관하려면 아래 지침을 따르십시오.

1. Salesforce에서 잠재 고객 및 연락처 개체에 대한 세 가지 사용자 지정 필드(점수, 획득 프로그램 및 획득 날짜)를 만듭니다.
1. Salesforce에서 전환 시 값이 이월되도록 이러한 사용자 정의 필드를 리드와 연락처 간에 매핑합니다.
1. 필요한 경우 다른 추가 필드를 만들 수 있습니다(아래 표 참조).

이러한 모든 사용자 정의 필드는 선택 사항이며 Marketo 및 Salesforce를 동기화하는 데 필요하지 않습니다. 가장 좋은 방법은 점수, 획득 프로그램 및 획득 날짜에 대한 필드를 만드는 것입니다.

## Salesforce에 Marketo 필드 추가 {#add-marketo-fields-to-salesforce}

위에 나열된 Salesforce의 리드 및 연락처 개체에 세 개의 사용자 지정 필드를 추가합니다. 더 추가하려면 이 섹션의 끝에 있는 사용 가능한 필드 표를 참조하십시오.

세 개의 사용자 정의 필드 각각에 대해 다음 단계를 수행하여 추가합니다. 점수로 시작합니다.

1. Salesforce에 로그인하고 **[!UICONTROL 설정]**&#x200B;을 클릭합니다.

   ![](assets/image2016-5-23-13-3a15-3a21.png)

1. 왼쪽의 [!UICONTROL 빌드] 메뉴에서 **[!UICONTROL 사용자 지정]**&#x200B;을 클릭하고 **[!UICONTROL 리드]**&#x200B;를 선택합니다. **[!UICONTROL 필드]**&#x200B;를 클릭합니다.

   ![](assets/image2016-5-23-13-3a20-3a5.png)

1. 페이지 하단의 사용자 지정 필드 및 관계 섹션에서 **[!UICONTROL 새로 만들기]**&#x200B;를 클릭합니다.

   ![](assets/image2016-5-26-14-3a41-3a40.png)

1. 적절한 필드 유형(점수 - 숫자, 획득 프로그램 - 텍스트, 획득 일자 - 날짜/시간)을 선택합니다.

   ![](assets/choose-field-type-2-hand.png)

1. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2016-5-26-14-3a51-3a14.png)

1. 아래 표와 같이 필드에 대한 [!UICONTROL 필드 레이블], [!UICONTROL 길이] 및 [!UICONTROL 필드 이름]을 입력하십시오.

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      필드 레이블 
    </div></th> 
   <th> 
    <div>
      필드 이름 
    </div></th> 
   <th> 
    <div>
      데이터 유형 
    </div></th> 
   <th> 
    <div>
      필드 속성 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>스코어</td> 
   <td>mkto71_Lead_Score</td> 
   <td>숫자</td> 
   <td>길이 10<br>소수점 이하 자리 수 0 </td> 
  </tr> 
  <tr> 
   <td>획득 날짜</td> 
   <td>mkto71_Acquisition_Date</td> 
   <td>날짜/시간</td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td>고객 확보 프로그램</td> 
   <td>mkto71_Acquisition_Program</td> 
   <td>텍스트</td> 
   <td>길이 255</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Salesforce는 __c를 사용하여 API 이름을 만들 때 필드 이름에 추가합니다.

![](assets/image2016-5-26-14-3a55-3a33.png)

>[!NOTE]
>
>텍스트 및 숫자 필드는 길이가 필요하지만 날짜/시간 필드는 길이가 필요하지 않습니다. 설명은 선택 사항입니다.

1. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/image2016-5-23-14-3a50-3a5.png)

1. 액세스 설정을 지정하고 **[!UICONTROL 다음]**&#x200B;을(를) 클릭합니다.

   * 모든 역할을 **[!UICONTROL 표시]** 및 **[!UICONTROL 읽기 전용]**(으)로 설정

   * 동기화 사용자의 프로필에 대한 **[!UICONTROL 읽기 전용]** 확인란의 선택을 취소합니다.

      * 동기화 사용자로 _시스템 관리자_&#x200B;의 프로필을 가진 사용자가 있는 경우 시스템 관리자 프로필에 대한 **[!UICONTROL 읽기 전용]** 확인란의 선택을 취소하십시오(아래 참조)
      * 동기화 사용자에 대해 _사용자 지정 프로필_&#x200B;을 만든 경우 해당 사용자 지정 프로필에 대한 **[!UICONTROL 읽기 전용]** 확인란의 선택을 취소하십시오

   ![](assets/image2016-6-30-9-3a25-3a4.png)

1. 필드를 표시할 페이지 레이아웃을 선택합니다.

   ![](assets/image2016-5-26-15-3a14-3a45.png)

1. **[!UICONTROL 저장 및 새로 만들기]**&#x200B;를 클릭하여 돌아가서 다른 두 개의 사용자 지정 필드를 각각 만드십시오. 세 가지를 모두 완료하면 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2016-5-23-15-3a8-3a43.png)

1. 왼쪽의 빌드 메뉴에서 **[!UICONTROL 사용자 지정]**&#x200B;을 클릭하고 연락처를 선택합니다. 필드를 클릭합니다.
1. 가망 고객 객체에 대해 수행한 것처럼 연락처 객체의 점수, 획득 일자 및 획득 프로그램 필드에 대해 단계 3부터 10까지를 수행합니다.
1. 필요한 경우 이 테이블의 추가 사용자 정의 필드에 대해 위의 절차를 사용합니다.

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      필드 레이블 
    </div></th> 
   <th> 
    <div>
      필드 이름 
    </div></th> 
   <th> 
    <div>
      데이터 유형 
    </div></th> 
   <th> 
    <div>
      필드 속성 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>고객 확보 프로그램 Id</td> 
   <td>mkto71_Acquisition_Program_Id</td> 
   <td>숫자</td> 
   <td>길이 18<br>소수점 이하 자리 수 0 </td> 
  </tr> 
  <tr> 
   <td>원래 레퍼러</td> 
   <td>mkto71_Original_Referrer</td> 
   <td>텍스트</td> 
   <td>길이 255</td> 
  </tr> 
  <tr> 
   <td>원본 검색 엔진</td> 
   <td>mkto71_Original_Search_Engine</td> 
   <td>텍스트</td> 
   <td>길이 255</td> 
  </tr> 
  <tr> 
   <td>원본 검색 구문</td> 
   <td>mkto71_Original_Search_Phrase</td> 
   <td>텍스트</td> 
   <td>길이 255</td> 
  </tr> 
  <tr> 
   <td>원본 소스 정보</td> 
   <td>mkto71_Original_Source_Info</td> 
   <td>텍스트</td> 
   <td>길이 255</td> 
  </tr> 
  <tr> 
   <td>원본 소스 유형</td> 
   <td>mkto71_Original_Source_Type</td> 
   <td>텍스트</td> 
   <td>길이 255</td> 
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
>새 필드를 만들 때 Marketo에서 자동으로 할당한 필드의 값을 Salesforce에서 즉시 사용할 수 없습니다. Marketo은 두 시스템 중 하나의 레코드에 대한 다음 업데이트(즉, Marketo과 Salesforce 간에 동기화되는 필드 중 하나에 대한 업데이트) 시 데이터를 Salesforce에 동기화합니다.

## 전환을 위한 사용자 정의 필드 매핑 {#map-custom-fields-for-conversions}

Salesforce의 리드 개체에 있는 사용자 지정 필드는 전환이 발생할 때 데이터가 전달되도록 연락처 개체에 있는 연락처 필드에 매핑되어야 합니다.

1. 오른쪽 상단 모서리에서 **[!UICONTROL 설정]**&#x200B;을 클릭합니다.

   ![](assets/image2016-5-26-16-3a34-3a0.png)

1. Enter 키를 누르지 않고 탐색 검색에 &quot;Fields&quot;를 입력합니다. 다른 개체에 필드가 표시됩니다. [리드]에서 **[!UICONTROL 필드]**&#x200B;를 클릭하세요.

   ![](assets/image2016-5-26-16-3a36-3a32.png)

1. 잠재 고객 사용자 지정 필드 및 관계 섹션으로 이동한 다음 **[!UICONTROL 잠재 고객 필드 매핑]**&#x200B;을 클릭합니다.

   ![](assets/image2016-5-26-16-3a39-3a29.png)

1. 매핑할 필드 옆에 있는 드롭다운을 클릭합니다.

   ![](assets/image2016-5-26-16-3a49-3a53.png)

1. 해당 연락처 사용자 정의 필드를 선택합니다.

   ![](assets/image2016-5-26-16-3a56-3a23.png)

1. 생성한 다른 필드에 대해 위의 단계를 반복합니다.

1. 완료되면 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

>[!MORELIKETHIS]
>
>[3단계 중 2단계: Marketo(Enterprise/Unlimited)용 Salesforce 사용자 만들기](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"}
