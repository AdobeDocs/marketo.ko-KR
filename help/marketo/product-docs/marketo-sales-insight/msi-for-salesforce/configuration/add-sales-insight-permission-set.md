---
description: Sales Insight 권한 세트 추가 - Marketo 문서 - 제품 설명서
title: Sales Insight 권한 집합 추가
exl-id: b93ddf2e-0f7b-41e0-ba88-7363f5e34970
source-git-commit: d9876d73561d63dea4e46b0dfd191082f262baf6
workflow-type: tm+mt
source-wordcount: '379'
ht-degree: 0%

---

# Sales Insight 권한 집합 추가 {#add-sales-insight-permission-set}

다음 단계를 사용하여 Salesforce의 Sales Insight 기능에 대한 액세스를 추가합니다. Salesforce Classic 및 Lighting에 적용 가능

>[!PREREQUISITES]
>
>[Sales Insight Salesforce 패키지 업데이트](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md)이 기능을 사용하려면 {target=&quot;_blank&quot;} ~ 버전 1.8000 이상입니다.

>[!IMPORTANT]
>
>이전에 모든 프로필에 대한 Sales Insight 액세스 권한을 부여하거나 모든 사용자에 대한 Sales Insight 를 구현한 경우에는 다음을 수행해야 합니다 [프로필 수준 액세스 권한 제거](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/remove-sales-insight-access.md)이 권한 집합을 사용하려면 {target=&quot;_blank&quot;}를 사용하십시오.

## 개요 {#overview}

&quot;Marketo 앱&quot; 권한은 Sales Insight Salesforce 패키지의 일부입니다. 여기에는 아래에 언급된 개체, Apex 클래스 및 Visualforce 페이지에 대한 액세스 권한이 포함됩니다. 모든 Sales Insight 기능에 액세스하려면 이러한 기능이 필요합니다.

**개체 설정**

<table> 
 <tbody> 
 <tr> 
   <td>BestBetsCache</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>최상의 보기 세부 정보</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>최고의 보기</td> 
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
   <td>GroupedWebActivityCache</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>InterestMomentsCache</td> 
   <td>읽기, 만들기, 편집, 삭제, 모두 보기, 모두 수정</td> 
  </tr> 
  <tr> 
   <td>Marketo Sales Insight Config</td> 
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

* Apex 클래스 액세스: 159 &quot;mkto_si&quot;가 있는 Apex 클래스
* Visualforce 페이지 액세스: 64 &quot;mkto_si&quot;와 함께 있는 시각적 강제 페이지
* 사용자 지정 설정 정의: mkto_si.Marketo 설정 및 mkto_si.User 환경 설정

## 사용자에게 Marketo 앱 권한 집합 추가 {#adding-marketo-app-permission-set-to-users}

1. Salesforce 계정에 로그인합니다.

1. 클릭 **설정**.

   ![](assets/add-sales-insight-permission-set-1.png)

1. 관리자(Administrator)에서 를 클릭하여 열기 **사용자 관리**, 그런 다음 **사용자**.

   ![](assets/add-sales-insight-permission-set-2.png)

1. 모든 사용자에서 액세스 권한을 제공할 사용자를 선택한 다음 **권한 집합 지정**.

   ![](assets/add-sales-insight-permission-set-3.png)

1. 클릭 **할당 편집**.

   ![](assets/add-sales-insight-permission-set-4.png)

1. 선택 **Marketo 앱 액세스** 사용 가능한 사용 권한 세트에서 **추가**. 클릭 **저장**.

   ![](assets/add-sales-insight-permission-set-5.png)

1. 이제 사용자 세부 사항 페이지를 아래로 스크롤하면 권한 집합 지정 아래에 &quot;Marketo 앱 액세스&quot;가 표시됩니다.

   ![](assets/add-sales-insight-permission-set-6.png)

>[!NOTE]
>
>Sales Insight에 액세스할 수 없는 사용자에게는 다음 메시지가 표시됩니다. &quot;이 탭에 액세스할 수 있는 권한이 없습니다.&quot;

됐습니다. Sales Insight 액세스를 추가했습니다. 액세스를 추가할 다른 프로필에 대해 동일한 단계를 반복합니다.
