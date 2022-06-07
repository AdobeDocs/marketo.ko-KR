---
description: 프로그램 구성원 사용자 지정 필드 - Marketo 문서 - 제품 설명서
title: 프로그램 구성원 사용자 정의 필드
hide: true
hidefromtoc: true
source-git-commit: 09e9ee74c32f81fdc826454266d3e16826a09eae
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 4%

---

# 프로그램 구성원 사용자 지정 필드 동기화 {#program-member-custom-field-sync}

>[!PREREQUISITES]
>
>작성 [프로그램 구성원 사용자 정의 필드](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md){target=&quot;_blank&quot;}

>[!NOTE]
>
>프로그램 멤버 개체에는 최대 20개의 사용자 지정 필드가 있을 수 있습니다. 이러한 필드는 모든 프로그램에서 사용할 수 있습니다.

## Salesforce 필드를 프로그램 구성원 사용자 정의 필드에 매핑 {#map-salesforce-fields-to-program-member-custom-fields}

1. Marketo에서 **관리**.

   ![](assets/program-member-custom-field-sync-1.png)

1. 클릭 **Salesforce**&#x200B;를 클릭한 다음 **편집** 프로그램 멤버 사용자 지정 필드 동기화 옆에 있습니다.

   ![](assets/program-member-custom-field-sync-2.png)

1. 검색 상자를 사용하여 매핑할 Salesforce 필드를 찾습니다. 이 예에서는 Do Not Call을 사용합니다.

   ![](assets/program-member-custom-field-sync-3.png)

1. 드롭다운을 클릭합니다.

   ![](assets/program-member-custom-field-sync-4.png)

1. 매핑할 Marketo 프로그램 구성원 사용자 지정 필드를 선택합니다.

   ![](assets/program-member-custom-field-sync-5.png)

   >[!NOTE]
   >
   >드롭다운에는 Salesforce 필드의 데이터 유형과 일치하는 프로그램 구성원 사용자 지정 필드만 표시됩니다.

1. 추가 필드 매핑에 대해서는 검색 상자를 지우고 3~5단계를 반복합니다.

1. 클릭 **저장** 완료 시.

   ![](assets/program-member-custom-field-sync-6.png)

   >[!IMPORTANT]
   >
   >매핑된 필드의 프로그램 멤버 데이터에 대한 변경 사항은 앞으로 Marketo과 Salesforce 간에 동기화됩니다.

   >[!NOTE]
   >
   >Salesforce에서 필드의 데이터 유형의 이름을 바꾸거나 변경하면 프로그램 멤버 사용자 지정 필드를 사용하여 해당 필드의 매핑을 제거합니다. 하지만 검토 후 새 필드로 다시 매핑할 수 있습니다.

## 프로그램 구성원 사용자 정의 필드에서 Salesforce 필드 매핑 해제 {#unmap-salesforce-fields-from-program-member-custom-fields}

교체하기 위해 필드를 비워 두거나 일반적인 변경을 하려는 경우 먼저 매핑 해제를 수행해야 합니다. 방법은 다음과 같습니다.

1. Marketo에서 **관리**.

   ![](assets/program-member-custom-field-sync-7.png)

1. 클릭 **Salesforce**&#x200B;를 클릭한 다음 **편집** 프로그램 멤버 사용자 지정 필드 동기화 옆에 있습니다.

   ![](assets/program-member-custom-field-sync-8.png)

1. 검색 상자를 사용하여 매핑을 해제할 필드를 찾습니다. 이 예에서는 Do Not Call을 사용합니다.

   ![](assets/program-member-custom-field-sync-9.png)

   >[!TIP]
   >
   >을(를) 선택할 수 있습니다 **매핑된** 매핑된 필드만 보는 확인란

1. 을 클릭하여 매핑 해제 **X** 필드 옆에 있습니다.

   ![](assets/program-member-custom-field-sync-10.png)

1. 이제 매핑이 제거됩니다. 클릭 **저장**.

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
      <th>프로그램 멤버 사용자 지정 필드 데이터 유형</th>
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
      <td>복수 선택 선택 선택 선택 선택 목록</td>
      <td>문자열</td>
    </tr>
    <tr>
      <td>휴대폰</td>
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
      <td>Datetime</td>
      <td>Datetime</td>
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
>* [프로그램 멤버 데이터 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-member-data.md){target=&quot;_blank&quot;}
>* [프로그램 멤버 그리드에서 데이터 보기](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/manage-and-view-members.md){target=&quot;_blank&quot;}

