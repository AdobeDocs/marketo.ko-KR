---
description: 프로그램 구성원 사용자 정의 필드 동기화 - Marketo 문서 - 제품 설명서
title: 프로그램 구성원 사용자 정의 필드 동기화
exl-id: 7facfc79-a411-4ad9-b847-2002763af5bb
feature: Programs
source-git-commit: e49860ae611f2f77789bb491aeccbee46a911a2c
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 6%

---

# 프로그램 구성원 사용자 정의 필드 동기화 {#program-member-custom-field-sync}

>[!PREREQUISITES]
>
>* 생성 [프로그램 멤버 사용자 정의 필드](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md){target="_blank"}
>* [Salesforce 캠페인을 프로그램과 동기화](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/sync-an-sfdc-campaign-with-a-program.md){target="_blank"}

>[!NOTE]
>
>프로그램 멤버 개체에는 최대 20개의 사용자 지정 필드가 있을 수 있습니다. 이들 필드는 모든 프로그램에서 사용할 수 있습니다.

## Salesforce 필드를 프로그램 멤버 사용자 정의 필드에 매핑 {#map-salesforce-fields-to-program-member-custom-fields}

1. Marketo에서 **[!UICONTROL 관리자]**.

   ![](assets/program-member-custom-field-sync-1.png)

1. 클릭 **[!DNL Salesforce]**&#x200B;을 클릭한 다음 을 클릭합니다 **[!UICONTROL 편집]** 프로그램 멤버 사용자 정의 필드 동기화 옆에 있습니다.

   ![](assets/program-member-custom-field-sync-2.png)

1. 검색 상자를 사용하여 매핑할 Salesforce 필드를 찾습니다. 이 예제에서는 Do Not Call을 사용합니다.

   ![](assets/program-member-custom-field-sync-3.png)

1. 드롭다운을 클릭합니다.

   ![](assets/program-member-custom-field-sync-4.png)

1. 매핑할 원하는 Marketo 프로그램 멤버 사용자 정의 필드를 선택합니다.

   ![](assets/program-member-custom-field-sync-5.png)

   >[!NOTE]
   >
   >드롭다운에는 Salesforce 필드의 데이터 형식과 일치하는 프로그램 멤버 사용자 지정 필드만 표시됩니다.

1. 추가 필드 매핑의 경우 검색 상자를 지우고 3~5단계를 반복합니다.

1. 클릭 **[!UICONTROL 저장]** 완료 시.

   ![](assets/program-member-custom-field-sync-6.png)

   >[!IMPORTANT]
   >
   >매핑된 필드의 프로그램 멤버 데이터에 대한 변경 사항은 앞으로 Marketo과 Salesforce 간에 동기화됩니다.

   >[!NOTE]
   >
   >Salesforce에서 필드의 데이터 형식 이름을 바꾸거나 변경하면 해당 필드에 대한 매핑이 프로그램 멤버 사용자 지정 필드에서 제거됩니다. 하지만 검토 후 새 필드와 다시 매핑할 수 있습니다.

## 프로그램 구성원 사용자 정의 필드에서 Salesforce 필드 매핑 해제 {#unmap-salesforce-fields-from-program-member-custom-fields}

필드를 바꾸기 위해 필드를 비우거나 일반적인 변경 내용을 적용하려는 경우 먼저 매핑 해제를 수행해야 합니다. 방법은 다음과 같습니다.

1. Marketo에서 **[!UICONTROL 관리자]**.

   ![](assets/program-member-custom-field-sync-7.png)

1. 클릭 **[!DNL Salesforce]**&#x200B;을 클릭한 다음 을 클릭합니다 **[!UICONTROL 편집]** 프로그램 멤버 사용자 정의 필드 동기화 옆에 있습니다.

   ![](assets/program-member-custom-field-sync-8.png)

1. 검색 상자를 사용하여 매핑을 해제할 필드를 찾습니다. 이 예제에서는 Do Not Call을 사용합니다.

   ![](assets/program-member-custom-field-sync-9.png)

   >[!TIP]
   >
   >다음을 선택할 수 있습니다. **[!UICONTROL 매핑됨]** 매핑된 필드만 볼 수 있는 확인란입니다.

1. 을(를) 클릭하여 매핑 해제 **X** 필드 옆.

   ![](assets/program-member-custom-field-sync-10.png)

1. 이제 매핑이 제거됩니다. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/program-member-custom-field-sync-11.png)

## 데이터 유형 매핑 {#data-type-mapping}

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>SFDC 데이터 유형</th>
      <th>프로그램 멤버 사용자 정의 필드 데이터 유형</th>
    </tr>
    <tr>
      <td>텍스트</td>
      <td>문자열</td>
    </tr>
    <tr>
      <td>선택 목록</td>
      <td>문자열</td>
    </tr>
    <tr>
      <td>선택 목록 다중 선택</td>
      <td>문자열</td>
    </tr>
    <tr>
      <td>전화</td>
      <td>문자열</td>
    </tr>
    <tr>
      <td>이메일</td>
      <td>문자열</td>
    </tr>
    <tr>
      <td>숫자(m)</td>
      <td>정수</td>
    </tr>
    <tr>
      <td>숫자(m,n)</td>
      <td>부동</td>
    </tr>
    <tr>
      <td>확인란</td>
      <td>부울</td>
    </tr>
    <tr>
      <td>URL</td>
      <td>URL</td>
    </tr>
    <tr>
      <td>날짜</td>
      <td>날짜</td>
    </tr>
    <tr>
      <td>날짜/시간</td>
      <td>날짜/시간</td>
    </tr>
    <tr>
      <td>조회(참조)</td>
      <td>문자열</td>
    </tr>
    <tr>
      <td>Base64</td>
      <td>문자열</td>
    </tr>
  </tbody>
</table>

>[!MORELIKETHIS]
>
>* [프로그램 멤버 데이터 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-member-data.md){target="_blank"}
>* [프로그램 멤버 그리드에서 데이터 보기](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/manage-and-view-members.md){target="_blank"}
>* [SFDC 동기화 - Campaign 동기화](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md){target="_blank"}
