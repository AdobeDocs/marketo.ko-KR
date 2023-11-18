---
unique-page-id: 2360364
description: 2단계/3단계 - Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited) - Marketo 문서 - 제품 설명서
title: 2/3단계 - Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited)
exl-id: 871f335c-7b1e-47e1-8320-a18fbf21a970
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '416'
ht-degree: 3%

---

# 2단계/3단계: Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>Salesforce 관리자가 이러한 단계를 완료해야 합니다.

>[!PREREQUISITES]
>
>[1단계/3단계: Salesforce에 Marketo 필드 추가(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md){target="_blank"}

이 문서에서는 Salesforce 프로필에 사용자 권한을 설정하고 Marketo-Salesforce 통합 계정을 만듭니다.

## 프로필 만들기 {#create-a-profile}

1. 클릭 **[!UICONTROL 설정]**.

   ![](assets/image2015-6-11-16-3a15-3a27.png)

1. 탐색 검색 막대에 &quot;profiles&quot;를 입력하고 **[!UICONTROL 프로필]** 링크를 클릭합니다.

   ![](assets/sfdc-profiles-hands.png)

1. 클릭 **[!UICONTROL 신규]**.

   ![](assets/image2014-12-9-9-3a19-3a15.png)

1. 선택 **[!UICONTROL 표준 사용자]**&#x200B;프로필 이름을 &quot;Marketo-Salesforce Sync&quot;로 지정하고 **[!UICONTROL 저장]**.

   ![](assets/image2014-12-9-9-3a19-3a22.png)

## 프로필 권한 설정 {#set-profile-permissions}

1. 클릭 **[!UICONTROL 편집]** 보안 권한을 설정합니다.

   ![](assets/image2014-12-9-9-3a19-3a30.png)

1. 아래 **[!UICONTROL 관리 권한]** 섹션에서 다음 상자가 선택되어 있는지 확인합니다.

   * API 활성화됨
   * HTML 템플릿 편집
   * 공개 문서 관리
   * 공개 템플릿 관리

   ![](assets/image2014-12-9-9-3a19-3a38.png)

   >[!TIP]
   >
   >다음을 확인하십시오. **[!UICONTROL 암호가 만료되지 않음]** 상자.

1. 일반 사용자 권한 섹션에서 다음 확인란이 선택되어 있는지 확인합니다.

   * 리드 전환
   * 이벤트 편집
   * 작업 편집

   ![](assets/image2014-12-9-9-3a19-3a47.png)

1. 표준 객체 권한 섹션에서 읽기, 만들기, 편집 및 삭제 권한이 선택되어 있는지 확인합니다.

   * 계정
   * 캠페인
   * 연락처
   * 잠재 고객
   * 기회

   >[!NOTE]
   >
   >Campaign Sync를 사용하려면 캠페인에 권한을 부여합니다.

   ![](assets/image2014-12-9-9-3a19-3a57.png)

1. 완료되면 다음을 클릭하십시오. **[!UICONTROL 저장]** 페이지 하단에 있습니다.

   ![](assets/image2014-12-9-9-3a20-3a5.png)

## 필드 권한 설정 {#set-field-permissions}

1. 동기화에 필요한 사용자 지정 필드를 확인하려면 마케터와 상의하십시오.

   >[!NOTE]
   >
   >이 단계는 Marketo에 필요하지 않은 필드가 표시되지 않도록 하여 혼란을 줄이고 동기화 속도를 높입니다.

1. 프로필 세부 사항 페이지에서 **[!UICONTROL 필드 수준 보안]** 섹션. 클릭 **[!UICONTROL 보기]** 객체에 대한 액세스 가능성을 편집하려면 다음과 같이 하십시오.

   * 리드
   * 연락처
   * 계정
   * 기회

   >[!TIP]
   >
   >조직의 필요에 따라 다른 객체를 구성할 수 있습니다.

   ![](assets/image2014-12-9-9-3a20-3a14.png)

1. 각 개체에 대해 **[!UICONTROL 편집]**.

   ![](assets/sfdc-sync-field-edit1.png)

1. 불필요한 필드를 찾아 다음을 확인하십시오. **[!UICONTROL 읽기 액세스]** 및 **[!UICONTROL 액세스 권한 편집]** 이 선택되지 않습니다. 클릭 **[!UICONTROL 저장]** 완료 시.

   >[!NOTE]
   >
   >사용자 정의 필드에 대한 액세스 가능성만 편집하십시오.

   ![](assets/sfdc-sync-field-edit2.png)

1. 필요하지 않은 모든 필드 비활성화가 끝나면 다음을 확인해야 합니다. **[!UICONTROL 읽기 액세스 및 편집 액세스 권한]** (다음 오브젝트 필드) 클릭 **[!UICONTROL 저장]** 완료 시.

<table> 
 <tbody> 
  <tr> 
   <th colspan="1" rowspan="1"><p>오브젝트</p></th> 
   <th colspan="1" rowspan="1"><p>필드</p></th> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>계정</p></td> 
   <td colspan="1" rowspan="1"><p>필드 입력</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Event</p></td> 
   <td colspan="1" rowspan="1"><p>모든 필드</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>작업</p></td> 
   <td colspan="1" rowspan="1"><p>모든 필드</p></td> 
  </tr> 
 </tbody> 
</table>

![](assets/sfdc-check-the-boxes.png)

## Marketo-Salesforce 동기화 계정 만들기 {#create-marketo-salesforce-sync-account}

>[!TIP]
>
>전용 Salesforce 계정 만들기(예: `marketo@yourcompany.com`)를 사용하여 Marketo 사용자와 다른 Salesforce 사용자가 변경한 내용을 구별할 수 있습니다.

1. 탐색 검색 창에 &quot;Manage users&quot;를 입력한 다음 를 클릭합니다. **[!UICONTROL 사용자]**. 클릭 **[!UICONTROL 새 사용자]**.

   ![](assets/sfdc-new-users.png)

1. 필수 필드를 채웁니다. 그런 다음 **[!UICONTROL 사용자 라이선스: Salesforce]** 이전에 만든 프로필입니다. 클릭 **[!UICONTROL 저장]** 다 끝나면.

   ![](assets/image2014-12-9-9-3a20-3a56.png)

2/2단계가 완료되었습니다.

>[!NOTE]
>
>[3단계/3: Marketo 및 Salesforce 연결(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md){target="_blank"}
