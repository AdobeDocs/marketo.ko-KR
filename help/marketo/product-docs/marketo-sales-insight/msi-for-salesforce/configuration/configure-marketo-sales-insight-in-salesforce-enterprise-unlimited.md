---
unique-page-id: 2360368
description: Salesforce Enterprise/Unlimited Editions에서 Marketo Sales Insight를 구성하는 방법에 대해 알아봅니다.
title: Salesforce Enterprise/Unlimited에서 Marketo Sales Insight 구성
exl-id: a33ed396-8d26-403f-b6d8-fe7c55ce76ba
feature: Marketo Sales Insights
source-git-commit: 3cbefabe80778b0502eaecd733b5732fd9003316
workflow-type: tm+mt
source-wordcount: '885'
ht-degree: 0%

---

# Salesforce Enterprise/Unlimited에서 Marketo Sales Insight 구성 {#configure-marketo-sales-insight-in-salesforce-enterprise-unlimited}

다음 단계를 완료하여 Salesforce Enterprise/Unlimited Edition에서 Marketo Sales Insight를 구성합니다.

>[!PREREQUISITES]
>
>[Salesforce AppExchange에 Marketo Sales Insight 패키지 설치](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)

>[!NOTE]
>
>**관리자 권한이 필요합니다.**

## Marketo Engage에서 Sales Insight 구성 {#configure-sales-insight-in-marketo}

1. Marketo Engage에서 Marketo Sales Insight 자격 증명을 가져오려면 **[!UICONTROL 관리자]** 영역 및 선택 **[!UICONTROL Sales Insight]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-1.png)

1. 클릭 **[!UICONTROL API 구성 편집]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-2.png)

1. 선택한 API 비밀 키를 입력하고 클릭 **[!UICONTROL 저장]**. 앰퍼샌드 사용 안 함(`&`)을 클릭하여 제품에서 사용할 수 있습니다.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-3.png)

   >[!NOTE]
   >
   >API 비밀 키는 조직의 암호와 같으며 안전해야 합니다.

1. 자격 증명을 채우려면 **[!UICONTROL 보기]** 다음에서 _[!UICONTROL Rest API 구성]_ 패널.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-4.png)

1. 확인 대화 상자가 표시되면 **[!UICONTROL 확인]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-5.png)

   >[!TIP]
   >
   >이 창을 열어 두십시오. 이 정보는 나중에 Salesforce 구성에 필요합니다.

## Salesforce에서 Sales Insight 구성 {#configure-sales-insight-in-salesforce}

1. Salesforce에서 **[!UICONTROL 설정]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-6.png)

1. &quot;원격 사이트&quot;를 검색하고 선택 **[!UICONTROL 원격 사이트 설정]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-7.png)

1. 클릭 **[!UICONTROL 새 원격 사이트]**.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-8.png)

1. 원격 사이트 이름 입력(과 비슷할 수 있음) `MarketoSoapAPI`). 원격 사이트 URL(Marketo 호스트 URL)을 _[!UICONTROL Soap API 구성]_ Marketo Engage의 패널 클릭 **[!UICONTROL 저장]**. 이제 Soap API에 대한 원격 사이트 설정을 만들었습니다.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-9.png)

1. 클릭 **[!UICONTROL 새 원격 사이트]** 다시.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-10.png)

1. 원격 사이트 이름 입력(과 비슷할 수 있음) `MarketoAPI`). API URL인 원격 사이트 URL을 입력합니다. _[!UICONTROL Rest API 구성]_ Marketo Engage의 패널 클릭 **[!UICONTROL 저장]**. 이제 Rest API에 대한 원격 사이트 설정을 만들었습니다.

   >[!NOTE]
   >
   >_본인_ 선택 **[!UICONTROL 원격 사이트 이름]** (`MarketoAPI` 여기서 사용). 다음 **[!UICONTROL 원격 사이트 URL]** Marketo에서 Sales Insight 구성 섹션의 3단계에 있는 API 구성 편집 대화 상자에 있는 Marketo 호스트 필드에서 확인할 수 있습니다.

## 표준 Salesforce 개체에 대한 Sales Insight 사용자 프로필 액세스 권한 부여 {#grant-sales-insight-users-profile-access}

Salesforce 보안 향상으로 인해 AppExchange 패키지는 더 이상 표준 오브젝트에 대한 권한을 부여할 수 없으며 Salesforce 사용자 프로필에서 관련 Salesforce 오브젝트에 대한 액세스 권한을 부여해야 합니다. 필요한 권한을 부여하려면 다음 단계를 따르십시오.

1. 클릭 **[!UICONTROL 설정]**.

1. 빠른 찾기에서 &quot;프로필&quot;을 검색합니다.

1. 클릭 **[!UICONTROL 편집]** salesforce 사용자가 사용하는 프로필 옆에 있습니다.

1. 아래 _[!UICONTROL 표준 개체 권한]_ 섹션, 활성화 **[!UICONTROL 읽기]** 다음 객체에 대한 액세스 권한: [!UICONTROL 리드], [!UICONTROL 연락처], [!UICONTROL 계정], 및 [!UICONTROL 영업 기회].

1. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

## 페이지 레이아웃 사용자 지정 {#customize-page-layouts}

1. 클릭 **[!UICONTROL 설정]**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. &quot;페이지 레이아웃&quot;을 검색하고 **[!UICONTROL 페이지 레이아웃]** 아래에 **[!UICONTROL 잠재 고객]**.

   ![](assets/image2015-5-28-14-3a58-3a39.png)

1. 클릭 **[!UICONTROL Visualforce 페이지]** 왼쪽이요 드래그 **[!UICONTROL 섹션]** 아래 레이아웃에 _[!UICONTROL 사용자 지정 링크]_ 섹션.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

1. &quot;Marketo Sales Insight&quot;를 **[!UICONTROL 섹션 이름]**, 선택 **[!UICONTROL 열 1개]**, 및 클릭 **[!UICONTROL 확인]**.

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. 드래그 앤 드롭 **[!UICONTROL 리드]** 을 새 섹션에 추가합니다.

   ![](assets/image2014-9-24-17-3a33-3a45.png)

   >[!TIP]
   >
   >이 상자의 이름은 객체 유형에 따라 변경됩니다. 예를 들어 연락처에 대한 페이지 레이아웃을 수정하는 경우 연락처가 표시됩니다.

1. 를 두 번 클릭합니다. **[!UICONTROL 리드]** 방금 추가한 블록을 차단합니다.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. 높이 편집 대상 **450** 픽셀 및 클릭 **[!UICONTROL 확인]**.

   ![](assets/image2014-9-24-17-3a34-3a26.png)

   >[!NOTE]
   >
   >확인 **[!UICONTROL 스크롤 막대 표시]** 스크롤스루 활동에 대한 액세스 권한이 필요한 경우.

   >[!TIP]
   >
   >Accounts 및 Opportunities 객체의 권장 높이는 410픽셀입니다.

1. 클릭 **[!UICONTROL 필드]** 왼쪽이요 그런 다음 을(를) 검색하고 드래그합니다. **[!UICONTROL 긴급도]** 에 레이블 지정 **[!UICONTROL Marketo Sales Insight]** 레이아웃.

   ![](assets/configure-marketo-sales-insight-in-salesforce-professional-edition-18.png)

1. 이러한 필드에 대해서도 위의 단계를 반복합니다.

   * 마지막 흥미로운 순간
   * 마지막 관심 순간 날짜
   * 마지막 관심 순간 설명
   * 마지막 관심 순간 소스
   * 마지막 관심 순간 유형
   * 판매별 마지막 활동
   * 영업 팀별 마지막 참여
   * MSI 연락처 Id
   * 상대 스코어
   * 상대 점수 값
   * 긴급도
   * 긴급도 값
   * Marketo에서 보기

1. 클릭 **[!UICONTROL 저장]** 완료 시.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

1. 5-7단계를 반복하여 Visualforce 페이지 섹션 및 Sales Insight 필드를 추가합니다. **[!UICONTROL 연락처]**, **[!UICONTROL 계정]**, 및 **[!UICONTROL 영업 기회]**.

1. 8~10단계를 반복하여 다음 Sales Insight 필드를 추가합니다. **[!UICONTROL 연락처]**. 모든 변경 사항을 저장하십시오.

   * 마지막 흥미로운 순간
   * 마지막 관심 순간 날짜
   * [!UICONTROL 마지막 관심 순간 설명]
   * [!UICONTROL 마지막 관심 순간 소스]
   * [!UICONTROL 마지막 관심 순간 유형]
   * [!UICONTROL 영업별 마지막 Marketo 활동]
   * [!UICONTROL 영업 팀별 마지막 Marketo 계약]
   * [!UICONTROL MKTO 리드 점수]
   * [!UICONTROL 상대 스코어]
   * [!UICONTROL 상대 점수 값]
   * [!UICONTROL Sales Insight] - 연락처 전체 목록 페이지를 엽니다.
   * [!UICONTROL 긴급도]
   * [!UICONTROL 긴급도 값]

## 사용자 정의 개인 필드 매핑 {#map-custom-person-fields}

Marketo 사용자 필드는 전환이 제대로 작동하도록 Salesforce 연락처 필드에 매핑되어야 합니다. 매핑하려면 다음 단계를 따르십시오.

1. 클릭 **[!UICONTROL 설정]**.

   ![](assets/image2015-5-22-14-3a40-3a39.png)

1. 검색 막대에서 &quot;필드&quot;를 검색하고 **[!UICONTROL 필드]** 아래에 **[!UICONTROL 잠재 고객]**.

   ![](assets/image2015-6-1-9-3a54-3a50.png)

1. 클릭 **[!UICONTROL 리드 필드 매핑]**.

   ![](assets/image2015-6-1-9-3a58-3a48.png)

1. 다음에 대한 오른쪽의 드롭다운을 클릭합니다. **[!UICONTROL 참여]**.

   ![](assets/image2015-6-1-10-3a9-3a53.png)

1. 선택 **[!UICONTROL 연락처.참여]** 목록에 있습니다.

   ![](assets/image2015-6-1-10-3a12-3a11.png)

1. 이러한 필드도 반복하고 매핑합니다.

   | Marketo 사용자 정의 필드 | Salesforce 연락처 사용자 지정 필드 |
   |--- |--- |
   | `Engagement` | `Contact.Engagement` |
   | `Relative Score Value` | `Contact.Relative Score Value` |
   | `Urgency Value` | `Contact.Urgency Value` |
   | `Last Interesting Moment Date` | `Contact.Last Interesting Moment Date` |
   | `Last Interesting Moment Desc` | `Contact.Last Interesting Moment Desc` |
   | `Last Interesting Moment Source` | `Contact.Last Interesting Moment Source` |
   | `Last Interesting Moment Type` | `Contact.Last Interesting Moment Type` |

1. 클릭 **[!UICONTROL 저장]** 다 끝나면.

## Marketo Sales Insight 구성 탭 {#marketo-sales-insight-configuration-tab}

1. Salesforce에서 **+** 탭 표시줄의 끝에서 **[!UICONTROL Marketo Sales Insight 구성]**.

1. 의 Soap API 패널에서 자격 증명을 복사합니다. [Marketo의 Sales Insight Admin 페이지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} Salesforce Sales Insight 구성 페이지의 Soap API 섹션에 붙여 넣습니다.

1. 의 Rest API 패널에서 자격 증명을 복사합니다. [Marketo의 Sales Insight Admin 페이지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#set-up-marketo-sales-insight){target="_blank"} Salesforce Sales Insight 구성 페이지의 Rest API 섹션에 붙여 넣습니다.

   ![](assets/configure-marketo-sales-insight-in-salesforce-enterprise-edition-25.png)

잠재 고객, 연락처, 계정 및 기회에 대한 Marketo Sales Insight 필드를 볼 수 있어야 합니다.

>[!NOTE]
>
>진단 테스트에 실패한 경우 [페이지 레이아웃에 필드 더 추가](https://nation.marketo.com:443/t5/knowledgebase/how-to-repair-marketo-sales-insight-setup-configuration-problems/ta-p/248218){target="_blank"} 이(가) 문제를 해결할 수 있습니다.

>[!NOTE]
>
>계정의 경우 Sales Insight에 모든 이메일이 포함되어 있지만 가장 최근의 흥미로운 순간, 웹 활동 및 점수 변경만 가능합니다.

>[!MORELIKETHIS]
>
>* [우선 순위, 긴급도, 상대 점수 및 최고 베팅](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md)
>* [Salesforce에 Marketo 탭 추가](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-marketo-tab-to-salesforce.md)
>* [프로필에 Sales Insight 액세스 추가](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target="_blank"}
