---
unique-page-id: 2360364
description: 3단계 중 2단계 - Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited) - Marketo 문서 - 제품 설명서
title: 2/3단계 - Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited)
exl-id: 871f335c-7b1e-47e1-8320-a18fbf21a970
feature: Salesforce Integration
source-git-commit: 989804463f44afbf35ab11c0f23c37b0d328e652
workflow-type: tm+mt
source-wordcount: '428'
ht-degree: 3%

---

# 2단계/3단계: Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>이 단계는 Salesforce 관리자가 완료해야 합니다

>[!PREREQUISITES]
>
>[3단계 중 1단계: Salesforce(Enterprise/Unlimited)에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md){target="_blank"}

이 문서에서는 Salesforce 프로필에서 사용자 권한을 설정하고 Marketo-Salesforce 통합 계정을 만듭니다.

## 프로필 만들기 {#create-a-profile}

1. **[!UICONTROL 설치]**&#x200B;를 클릭합니다.

   ![](assets/image2015-6-11-16-3a15-3a27.png)

1. 탐색 창 검색 창에 &quot;profiles&quot;를 입력하고 **[!UICONTROL 프로필]** 링크를 클릭합니다.

   ![](assets/sfdc-profiles-hands.png)

1. **[!UICONTROL 새로 만들기]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-9-3a19-3a15.png)

1. **[!UICONTROL 표준 사용자]**&#x200B;를 선택하고 프로필 이름을 &quot;Marketo-Salesforce 동기화&quot;로 지정한 다음 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a19-3a22.png)

## 프로필 권한 설정 {#set-profile-permissions}

1. 보안 권한을 설정하려면 **[!UICONTROL 편집]**&#x200B;을 클릭하세요.

   ![](assets/image2014-12-9-9-3a19-3a30.png)

1. **[!UICONTROL 관리 권한]** 섹션에서 다음 확인란이 선택되어 있는지 확인하십시오.

   * API 활성화됨
   * HTML 템플릿 편집
   * 공개 문서 관리
   * 공개 템플릿 관리

   ![](assets/image2014-12-9-9-3a19-3a38.png)

   >[!TIP]
   >
   >**[!UICONTROL 암호 만료되지 않음]** 상자를 확인하십시오.

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

1. 완료되면 페이지 하단의 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a20-3a5.png)

## 필드 권한 설정 {#set-field-permissions}

1. 동기화에 필요한 사용자 지정 필드를 확인하려면 마케터와 상의하십시오.

   >[!NOTE]
   >
   >이 단계는 Marketo에 필요하지 않은 필드가 표시되지 않도록 하여 혼란을 줄이고 동기화 속도를 높입니다.

1. 프로필 세부 정보 페이지에서 **[!UICONTROL 필드 수준 보안]** 섹션으로 이동합니다. **[!UICONTROL 보기]**&#x200B;를 클릭하여 개체에 대한 액세스 가능성을 편집합니다.

   * 리드
   * 연락처
   * 계정
   * 기회

   >[!TIP]
   >
   >조직의 필요에 따라 다른 객체를 구성할 수 있습니다.

   ![](assets/image2014-12-9-9-3a20-3a14.png)

1. 각 개체에 대해 **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/sfdc-sync-field-edit1.png)

1. 필요 없는 필드를 찾아 **[!UICONTROL 액세스 권한 읽기]** 및 **[!UICONTROL 액세스 권한 편집]**&#x200B;이 선택 취소되어 있는지 확인하세요. 완료되면 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   >[!NOTE]
   >
   >사용자 정의 필드에 대한 액세스 가능성만 편집하십시오.

   ![](assets/sfdc-sync-field-edit2.png)

1. 필요하지 않은 모든 필드 비활성화가 끝나면 다음 개체 필드에 대해 **[!UICONTROL 액세스 읽기 및 액세스 편집]**&#x200B;을 확인해야 합니다. 완료되면 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

<table> 
 <tbody> 
  <tr> 
   <th>오브젝트</th> 
   <th>필드</th> 
  </tr> 
  <tr> 
   <td>계정</td> 
   <td>필드 입력</td> 
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

![](assets/sfdc-check-the-boxes.png)

## Marketo-Salesforce 동기화 계정 만들기 {#create-marketo-salesforce-sync-account}

>[!TIP]
>
>전용 Salesforce 계정(예: `marketo@yourcompany.com`)을 만들어 Marketo 사용자와 다른 Salesforce 사용자가 변경한 내용을 구별합니다.

1. 탐색 검색 창에 &quot;사용자 관리&quot;를 입력한 다음 **[!UICONTROL 사용자]**&#x200B;를 클릭합니다. **[!UICONTROL 새 사용자]**&#x200B;를 클릭합니다.

   ![](assets/sfdc-new-users.png)

1. 필수 필드를 채웁니다. 그런 다음 **[!UICONTROL 사용자 라이선스: Salesforce]** 및 이전에 만든 프로필을 선택합니다. 완료되면 **[!UICONTROL 저장]**&#x200B;을 클릭하세요.

   ![](assets/image2014-12-9-9-3a20-3a56.png)

3단계 중 2단계가 완료되었습니다.

>[!NOTE]
>
>[3단계 중 3단계: Marketo 및 Salesforce(Enterprise/Unlimited) 연결](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md){target="_blank"}
