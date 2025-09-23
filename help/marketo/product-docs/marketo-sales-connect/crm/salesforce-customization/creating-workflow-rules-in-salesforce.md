---
unique-page-id: 14745823
description: Salesforce - Marketo 문서 - 제품 설명서에서 워크플로우 규칙 만들기
title: Salesforce에서 워크플로 규칙 만들기
exl-id: 0cfce178-453b-4949-96aa-c327278a267d
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 4%

---

# Salesforce에서 워크플로 규칙 만들기 {#creating-workflow-rules-in-salesforce}

Marketo Sales Insight(MSI) 및 Marketo Sales Connect(MSC)를 동시에 사용하는 경우 [!DNL Salesforce]의 MSI Best Bets 기능이 업데이트되지 않습니다. 다른 모든 MSI 기능은 평소대로 작동합니다 (iFrame에서 흥미로운 순간 보기, 이메일 보내기, 캠페인에 추가 등). 이 문서에서는 Best Bets가 다시 작동하도록 하는 해결 방법을 제공합니다.

>[!NOTE]
>
>이는 **MSI와 MSE를 모두**&#x200B;사용 중인 고객 및 MSI에서 최상의 선택 기능을 사용하려는 고객에게만 영향을 줍니다. 최상의 베팅이 필요/필요하지 않다면 무시할 수 있습니다.

## 시작하기 {#getting-started}

해결 방법에는 새 MSE 필드의 값을 이전 MSI 필드로 복사하는 새 워크플로우 규칙 생성이 포함되어 있습니다. 연락처 개체에 대해 4개의 워크플로 규칙을 만들고 [!DNL Salesforce] 인스턴스의 잠재 고객 개체에 대해 동일한 4개의 워크플로 규칙을 만들어야 합니다. 이렇게 하려면 CRM 관리자 권한(CRM의 역할 및 설정에 따라)이 필요할 수 있습니다.

아래는 워크플로우 규칙의 권장 이름과 각 규칙에 대한 설명입니다. 이는 [!UICONTROL Contact] 및 [!UICONTROL Lead] 개체에 적용됩니다.

<table>
 <colgroup>
  <col>
  <col>
 </colgroup>
 <tbody>
  <tr>
   <td>관심 순간 설명 필드 업데이트</td>
   <td><p>복사 위치: 마지막 Marketo 참여 설명<br>복사 위치: 마지막 관심 순간 설명</p></td>
  </tr>
  <tr>
   <td>관심 순간 유형 필드 업데이트</td>
   <td><p>복사 위치: 마지막 Marketo 참여 유형<br>복사 위치: 마지막 관심 순간 유형</p></td>
  </tr>
  <tr>
   <td>즐거운 순간 Source 필드 업데이트</td>
   <td><p>복사 위치: 마지막 Marketo 참여 Source<br>복사 위치: 마지막 관심 있는 순간 Source</p></td>
  </tr>
  <tr>
   <td>관심 순간 날짜 필드 업데이트</td>
   <td><p>복사 위치: 마지막 Marketo 참여 날짜<br>복사 위치: 마지막 관심 순간 날짜</p></td>
  </tr>
 </tbody>
</table>

## 지침 {#instructions}

1. **[!UICONTROL Setup]**&#x200B;을(를) 클릭한 후 **워크플로**&#x200B;를 검색하고 **[!UICONTROL Workflow Rules]**&#x200B;을(를) 선택하십시오.

   ![](assets/one-1.png)

1. **[!UICONTROL New Rule]**&#x200B;를 선택합니다.

   ![](assets/two-1.png)

1. [!UICONTROL Object] 드롭다운을 클릭하고 **[!UICONTROL Lead]**&#x200B;을(를) 선택한 다음 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/three-1.png)

1. [!UICONTROL Rule Name]&#x200B;(으)로 &quot;관심 순간 설명 필드 업데이트&quot;를 입력하십시오. 라디오 단추 **[!UICONTROL created, and every time it’s edited]**&#x200B;을(를) 선택합니다. [!UICONTROL Rule Criteria] 드롭다운에서 **[!UICONTROL formula evaluates to true]**&#x200B;을(를) 선택합니다. ISCHANGED 함수를 검색하여 선택합니다. 그런 다음 기본 필드 값을 강조 표시하고 **[!UICONTROL Insert Field]**&#x200B;을(를) 클릭합니다.

   ![](assets/four-1.png)

1. &quot;[!UICONTROL Insert Field]&quot; 팝업에서 **[!UICONTROL Last Marketo Engagement Desc]**&#x200B;을(를) 선택하고 **[!UICONTROL Insert]**&#x200B;을(를) 클릭합니다.

   ![](assets/five-1.png)

1. **[!UICONTROL Save & Next]**&#x200B;를 클릭합니다.

   ![](assets/6.png)

1. [!UICONTROL Add Workflow Action] 드롭다운에서 **[!UICONTROL New Field Update]**&#x200B;을(를) 선택합니다.

   ![](assets/seven.png)

1. [!UICONTROL Name] 필드에 &quot;Update Interesting Moment Desc Field&quot;를 입력합니다([!UICONTROL Unique Name]이(가) 자동 생성됩니다). [!UICONTROL Field to Update] 드롭다운에서 **[!UICONTROL Last Interesting Moment Desc]**&#x200B;을(를) 선택합니다. **[!UICONTROL Use a formula to set new value]** 라디오 단추를 선택한 다음 **[!UICONTROL Show Formula Editor]**&#x200B;을(를) 클릭합니다.

   ![](assets/eight.png)

1. **[!UICONTROL Insert Field]** 단추를 클릭합니다.

   ![](assets/9a.png)

1. **[!UICONTROL Last Marketo Engagement Desc]**&#x200B;을(를) 선택하고 **[!UICONTROL Insert]**&#x200B;을(를) 클릭합니다. 다음 페이지에서 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/nine.png)

1. **[!UICONTROL Done]**&#x200B;를 클릭합니다.

   ![](assets/twelve.png)

1. 워크플로 규칙을 설정하려면 **[!UICONTROL Activate]**&#x200B;을(를) 클릭하십시오.

   ![](assets/thirteen.png)

   마지막 단계 후에는 [!UICONTROL Getting Started] 섹션에 나열된 다른 필드(설명, 유형, Source, 날짜)에 대한 워크플로 규칙을 복제하도록 선택할 수 있습니다. [!UICONTROL Contact] 개체에서 4개의 워크플로 규칙을 완료한 후 [!UICONTROL Lead] 개체에 대해 동일한 규칙을 반복합니다.
