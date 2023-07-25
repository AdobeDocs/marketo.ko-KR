---
unique-page-id: 2360368
description: Salesforce Enterprise/Unlimited에서 Marketo Sales Insight 구성 - Marketo 문서 - 제품 설명서
title: Salesforce Enterprise/Unlimited에서 Marketo Sales Insight 구성
exl-id: a33ed396-8d26-403f-b6d8-fe7c55ce76ba
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '849'
ht-degree: 0%

---

# Salesforce Enterprise/Unlimited에서 Marketo Sales Insight 구성 {#configure-marketo-sales-insight-in-salesforce-enterprise-unlimited}

Salesforce Enterprise/Unlimited Editions에서 Marketo Sales Insight를 구성하는 데 필요한 단계는 다음과 같습니다. 시작하겠습니다.

>[!PREREQUISITES]
>
>[Salesforce AppExchange에 Marketo Sales Insight 패키지 설치](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)

>[!NOTE]
>
>**관리자 권한 필요**

## Marketo에서 Sales Insight 구성 {#configure-sales-insight-in-marketo}

1. Marketo에서 MSI 자격 증명을 획득합니다. 관리 영역으로 이동하여 을(를) 선택합니다. **Sales Insight**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-1.png)

1. 클릭 **API 구성 편집**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-2.png)

1. 선택한 API 비밀 키를 입력하고 클릭 **저장**. API 비밀 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-3.png)

   >[!NOTE]
   >
   >API 비밀 키는 조직의 암호와 같으며 안전해야 합니다.

1. 클릭 **보기** REST API 구성 패널에서 자격 증명을 채울 수 있습니다.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-4.png)

1. 확인 팝업이 표시됩니다. 클릭 **확인**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-5.png)

   >[!TIP]
   >
   >이 창을 열어 두십시오. 이 정보는 나중에 Salesforce에서 필요합니다.

## Salesforce에서 Sales Insight 구성 {#configure-sales-insight-in-salesforce}

1. Salesforce에서 **설정**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-6.png)

1. &quot;원격 사이트&quot;를 검색하고 선택 **원격 사이트 설정**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-7.png)

1. 클릭 **새 원격 사이트**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-8.png)

1. 원격 사이트 이름을 입력합니다(&quot;MarketoSoapAPI&quot;와 같은 것일 수 있음). Marketo의 Soap API 구성 패널에서 Marketo 호스트 URL인 원격 사이트 URL을 입력합니다. 클릭 **저장**. 이제 Soap API에 대한 원격 사이트 설정을 만들었습니다.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-9.png)

1. 클릭 **새 원격 사이트** 다시.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-10.png)

1. 원격 사이트 이름을 입력합니다(&quot;MarketoAPI&quot;와 같은 것일 수 있음). Marketo의 Rest API 구성 패널에서 API URL인 원격 사이트 URL을 입력합니다. 클릭 **저장**. 이제 Rest API에 대한 원격 사이트 설정을 만들었습니다.

   >[!NOTE]
   >
   >_본인_ 선택 **원격 사이트 이름** (여기서는 MarketoAPI가 사용됩니다.) 다음 **원격 사이트 URL** API 구성 편집 대화 상자의 Marketo 호스트 필드에 있는 &quot;Marketo에서 Sales Insight 구성&quot; 섹션의 3단계를 참조하십시오.

## 페이지 레이아웃 사용자 지정 {#customize-page-layouts}

1. 클릭 **설정**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. &quot;페이지 레이아웃&quot;을 검색하고 **페이지 레이아웃** 아래에 **잠재 고객**.

   ![](assets/image2015-5-28-14-3a58-3a39.png)

1. 클릭 **Visualforce 페이지** 왼쪽이요 드래그 **섹션** 을 클릭하여 사용자 지정 링크 섹션 아래의 레이아웃으로 이동합니다.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

1. &quot;Marketo Sales Insight&quot;를 **섹션 이름**. 선택 **열 1개** 및 클릭 **확인**.

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. 드래그 앤 드롭 **리드** 을 새 섹션에 추가합니다.

   ![](assets/image2014-9-24-17-3a33-3a45.png)

   >[!TIP]
   >
   >이 상자의 이름은 개체 유형에 따라 변경됩니다. 예를 들어 연락처에 대한 페이지 레이아웃을 수정하는 경우 연락처라고 표시됩니다.

1. 를 두 번 클릭합니다. **리드** 방금 추가한 블록을 차단합니다.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. 높이 편집 대상 **450** 픽셀 및 클릭 **확인**.

   ![](assets/image2014-9-24-17-3a34-3a26.png)

   >[!NOTE]
   >
   >확인 **스크롤 막대 표시** 스크롤스루 활동에 대한 액세스 권한이 필요한 경우.

   >[!TIP]
   >
   >Accounts 및 Opportunities 객체의 경우 높이 410픽셀이 권장됩니다.

1. 클릭 **필드** 왼쪽이요 그런 다음 을(를) 검색하고 드래그합니다. **긴급도** 에 레이블 지정 **Marketo Sales Insight** 레이아웃.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-18.png)

1. 이러한 필드에 대해서도 위의 단계를 반복합니다.

   <table> 
    <tbody> 
     <tr> 
      <td>마지막 흥미로운 순간</td> 
     </tr> 
     <tr> 
      <td>마지막 관심 순간 날짜</td> 
     </tr> 
     <tr> 
      <td>마지막 관심 순간 설명</td> 
     </tr> 
     <tr> 
      <td>마지막 관심 순간 소스</td> 
     </tr> 
     <tr> 
      <td>마지막 관심 순간 유형</td> 
     </tr> 
     <tr> 
      <td>영업별 마지막 Marketo 활동</td> 
     </tr> 
     <tr> 
      <td>영업 팀별 마지막 Marketo 계약</td> 
     </tr> 
     <tr> 
      <td>MSI 연락처 Id</td> 
     </tr> 
     <tr> 
      <td>상대 스코어</td> 
     </tr> 
     <tr> 
      <td>상대 점수 값</td> 
     </tr> 
     <tr> 
      <td>긴급도</td> 
     </tr> 
     <tr> 
      <td>긴급도 값</td> 
     </tr> 
     <tr> 
      <td>Marketo에서 보기</td> 
     </tr> 
    </tbody> 
   </table>

1. 클릭 **저장** 완료 시.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

1. 5-7단계를 반복하여 Visualforce 페이지 섹션 및 Sales Insight 필드를 추가합니다. **연락처**, **계정** 및 **영업 기회**.

1. 8~10단계를 반복하여 아래 목록에서 Sales Insight 필드를 추가합니다. **연락처**. 모든 변경 사항을 저장하십시오.

<table> 
    <tbody> 
     <tr> 
      <td>마지막 흥미로운 순간</td> 
     </tr> 
     <tr> 
      <td>마지막 관심 순간 날짜</td> 
     </tr> 
     <tr> 
      <td>마지막 관심 순간 설명</td> 
     </tr> 
     <tr> 
      <td>마지막 관심 순간 소스</td> 
     </tr> 
     <tr> 
      <td>마지막 관심 순간 유형</td> 
     </tr> 
     <tr> 
      <td>영업별 마지막 Marketo 활동</td> 
     </tr> 
     <tr> 
      <td>영업 팀별 마지막 Marketo 계약</td> 
     </tr> 
     <tr> 
      <td>MKTO 리드 점수</td> 
     </tr> 
     <tr> 
      <td>상대 스코어</td> 
     </tr> 
     <tr> 
      <td>상대 점수 값</td> 
     </tr> 
     <tr> 
      <td>Sales Insight - 연락처 전체 목록 페이지를 엽니다.</td> 
     </tr> 
     <tr> 
      <td>긴급도</td> 
     </tr> 
     <tr> 
      <td>긴급도 값</td> 
     </tr> 
    </tbody> 
   </table>

## 사용자 정의 개인 필드 매핑 {#map-custom-person-fields}

Marketo 사용자 필드를 Salesforce 연락처 필드에 매핑하여 전환이 제대로 작동하도록 해야 합니다. 방법은 다음과 같습니다.

1. 클릭 **설정**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. 검색 막대에서 &quot;필드&quot;를 검색하고 **필드** 아래에 **잠재 고객**.

   ![](assets/image2015-6-1-9-3a54-3a50.png)

1. 클릭 **리드 필드 매핑**.

   ![](assets/image2015-6-1-9-3a58-3a48.png)

1. 다음에 대한 오른쪽의 드롭다운을 클릭합니다. **참여**.

   ![](assets/image2015-6-1-10-3a9-3a53.png)

1. 선택 **연락처.참여** 목록에 있습니다.

   ![](assets/image2015-6-1-10-3a12-3a11.png)

1. 이러한 필드도 반복하고 매핑합니다.

   <table> 
    <tbody> 
     <tr> 
      <th colspan="1" rowspan="1">Marketo 사용자 정의 필드</th> 
      <th colspan="1" rowspan="1">Salesforce 연락처 사용자 지정 필드</th> 
     </tr> 
     <tr> 
      <td colspan="1" rowspan="1"><p>참여</p></td> 
      <td colspan="1" rowspan="1"><p>Contact.Engagement</p></td> 
     </tr> 
     <tr> 
      <td colspan="1" rowspan="1"><p>상대 점수 값</p></td> 
      <td colspan="1" rowspan="1"><p>Contact.상대 점수 값</p></td> 
     </tr> 
     <tr> 
      <td colspan="1" rowspan="1"><p>긴급도 값</p></td> 
      <td colspan="1" rowspan="1"><p>Contact.Urgency 값</p></td> 
     </tr> 
     <tr> 
      <td colspan="1" rowspan="1"><p>마지막 관심 순간 날짜</p></td> 
      <td colspan="1" rowspan="1"><p>Contact.마지막 관심 순간 날짜</p></td> 
     </tr> 
     <tr> 
      <td colspan="1" rowspan="1"><p>마지막 관심 순간 설명</p></td> 
      <td colspan="1" rowspan="1"><p>Contact.Last Interest Moment 설명</p></td> 
     </tr> 
     <tr> 
      <td colspan="1" rowspan="1"><p>마지막 관심 순간 소스</p></td> 
      <td colspan="1" rowspan="1"><p>Contact.마지막 관심 순간 소스</p></td> 
     </tr> 
     <tr> 
      <td colspan="1" rowspan="1"><p>마지막 관심 순간 유형</p></td> 
      <td colspan="1" rowspan="1"><p>Contact.마지막 관심 순간 유형</p></td> 
     </tr> 
    </tbody> 
   </table>

1. 클릭 **저장** 다 끝나면.

## Marketo Sales Insight 구성 탭 {#marketo-sales-insight-configuration-tab}

1. Salesforce에서 **+** 탭 표시줄의 끝에서 **Marketo Sales Insight 구성**.

1. 의 Soap API 패널에서 자격 증명을 복사합니다. [Marketo의 Sales Insight Admin 페이지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} Salesforce Sales Insight 구성 페이지의 Soap API 섹션에 붙여 넣습니다.

1. 의 Rest API 패널에서 자격 증명을 복사합니다. [Marketo의 Sales Insight Admin 페이지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} Salesforce Sales Insight 구성 페이지의 Rest API 섹션에 붙여 넣습니다.

   ![](assets/configure-marketo-sales-insight-in-salesforce-enterprise-edition-25.png)

다 됐습니다! 잠재 고객, 연락처, 계정 및 기회에 대한 Marketo Sales Insight 필드를 볼 수 있어야 합니다.

>[!NOTE]
>
>진단 테스트에 실패한 경우 다음을 수행해야 합니다 [페이지 레이아웃에 더 많은 필드 추가](https://nation.marketo.com/docs/DOC-1115){target="_blank"}.

>[!NOTE]
>
>계정의 경우 Sales Insight에 모든 이메일이 포함되지만 가장 최근의 흥미로운 순간, 웹 활동 및 점수 변경만 포함됩니다.

>[!MORELIKETHIS]
>
>* [우선 순위, 긴급도, 상대 점수 및 최고 베팅](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md)
>* [Salesforce에 Marketo 탭 추가](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-marketo-tab-to-salesforce.md)
>* [프로필에 Sales Insight 액세스 추가](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target="_blank"}
