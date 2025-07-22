---
description: Sales Insight 액세스 제거 - Marketo 문서 - 제품 설명서
title: 판매 Insight 액세스 제거
exl-id: 3cda112a-524e-469b-a222-c0192b2f5301
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '329'
ht-degree: 3%

---

# [!DNL Sales Insight] 액세스 제거 {#remove-sales-insight-access}

[!DNL Sales Insight]의 [!DNL Salesforce] 기능에 대한 액세스를 제거하려면 다음 단계를 사용하십시오. [!DNL Salesforce] 클래식 및 번개에 적용할 수 있습니다.

## 개요 {#overview}

모든 [!DNL Sales Insight] 기능에 액세스하려면 아래 언급된 개체, apex 클래스 및 visualforce 페이지에 대한 권한이 필요합니다. 이 항목을 제거하면 [!DNL Sales Insight]에 대한 액세스 권한이 제거됩니다.

**개체 설정**

<table> 
 <tbody> 
 <tr> 
   <td>BestBetsCache</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>[!DNL Best Bets] 자세히 보기</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>[!DNL Best Bets] 보기 횟수</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>EmailActivityCache</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>GetMethodArgus</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>그룹화된 웹 활동 캐시</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>InterestingMomentsCache</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>[!DNL Marketo Sales Insight] 구성</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>ScoringCache</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>값</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>WebActivityCache</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
 </tbody> 
</table>

* Apex 클래스 액세스: &quot;mkto_si&quot;로 시작하는 159개의 Apex 클래스
* Visualforce 페이지 액세스: &quot;mkto_si&quot;로 시작하는 64개의 Visualforce 페이지
* 사용자 정의 설정 정의: mkto_si.Marketo 설정 및 mkto_si.사용자 환경 설정

## [!DNL Sales Insight]에 대한 액세스 제거 중 {#removing-access-to-sales-insight}

1. [!DNL Salesforce] 계정에 로그인합니다.

1. **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.

   ![](assets/remove-sales-insight-access-1.png)

1. [!UICONTROL Administrator]에서 **[!UICONTROL Manage Users]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Profiles]**&#x200B;을(를) 클릭합니다.

1. 업데이트할 프로필을 클릭한 다음 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

1. [!UICONTROL Custom Tab Settings] 아래의 &quot;[!UICONTROL Tab Settings]&quot;(으)로 스크롤합니다.

1. [!UICONTROL Tab Hidden] 구성 및 MSI [!DNL Marketo Sales Insight] 보낼 편지함에 대한 드롭다운에서 &quot;[!DNL Marketo Sales]&quot; 옵션을 선택합니다.

   ![](assets/remove-sales-insight-access-2.png)

   ![](assets/remove-sales-insight-access-3.png)

1. &#39;[!UICONTROL Custom Object Permissions]&#39;(으)로 스크롤합니다.

1. 다음 오브젝트에서 &quot;읽기, 만들기, 편집, 삭제&quot; 액세스 제거:

   * BestBetsCache
   * [!DNL Best Bets] 세부 정보 보기
   * [!DNL Best Bets]개 보기
   * EmailActivityCache
   * GetMethodArgus
   * 그룹화된 웹 활동 캐시
   * InterestingMomentsCache
   * [!DNL Marketo Sales Insight] 구성
   * ScoringCache
   * 값
   * WebActivityCache

1. &quot;[!UICONTROL Enabled Apex Class Access]&quot; 섹션까지 아래로 스크롤합니다. **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

1. &quot;[!UICONTROL Enabled Apex Classes]&quot; 섹션에서 &quot;mkto_si&quot;로 시작하는 모든 클래스를 선택합니다. 최대 159개의 클래스가 추가되어야 합니다.

1. **[!UICONTROL Remove]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/remove-sales-insight-access-4.png)

1. &quot;[!UICONTROL Enabled Visualforce Page Access]&quot; 섹션까지 아래로 스크롤합니다. **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

1. &quot;[!UICONTROL Enabled Visualforce Pages]&quot; 섹션에서 &quot;mkto_si&quot;로 시작하는 모든 페이지를 선택합니다. 최대 64페이지까지 추가할 수 있습니다.

1. **[!UICONTROL Remove]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/remove-sales-insight-access-5.png)

1. &quot;[!UICONTROL Enabled Custom Setting Definitions Access]&quot; 섹션까지 아래로 스크롤합니다. **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

1. &quot;Marketo Sales Insight.mkto_si.Marketo 설정&quot; 및 &quot;Marketo Sales Insight.mkto_si.사용자 환경 설정&quot;을 선택합니다.

1. **[!UICONTROL Remove]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/remove-sales-insight-access-6.png)

됐습니다. [!DNL Sales Insight] 액세스를 제거했습니다. 액세스 권한을 제거하려는 다른 프로필에 대해서도 동일한 단계를 반복합니다.
