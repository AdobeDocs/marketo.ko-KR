---
unique-page-id: 14745823
description: Salesforce에서 워크플로 규칙 만들기 - Marketo 문서 - 제품 설명서
title: Salesforce에서 워크플로 규칙 만들기
exl-id: 0cfce178-453b-4949-96aa-c327278a267d
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '470'
ht-degree: 0%

---

# Salesforce에서 워크플로 규칙 만들기 {#creating-workflow-rules-in-salesforce}

Marketo Sales Insight(MSI) 및 Marketo Sales Connect(MSC)를 동시에 사용하는 경우 Salesforce의 MSI Best Bets 기능이 업데이트되지 않습니다. 다른 모든 MSI 기능은 평소대로 작동합니다 (iFrame에서 흥미로운 순간 보기, 이메일 보내기, 캠페인에 추가 등). 이 문서에서는 Best Bets가 다시 작동하도록 하는 해결 방법을 제공합니다.

>[!NOTE]
>
>를 사용하는 고객에게만 영향을 줍니다 **모두** MSI에서 최상의 선택 기능을 사용하려는 MSI 및 MSE. 최상의 베팅이 필요/필요하지 않다면 무시할 수 있습니다.

## 시작 {#getting-started}

해결 방법에는 새 MSE 필드의 값을 이전 MSI 필드로 복사하는 새 워크플로우 규칙 생성이 포함되어 있습니다. Contact 객체에 대한 4개의 워크플로 규칙과 고유한 Salesforce 인스턴스에 있는 Lead 객체에 대한 동일한 4개의 워크플로 규칙을 만들어야 합니다. 이렇게 하려면 CRM 관리자 권한(CRM의 역할 및 설정에 따라)이 필요할 수 있습니다.

아래는 워크플로우 규칙의 권장 이름과 각 규칙에 대한 설명입니다. Contact 및 Lead 객체에 적용됩니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td>관심 순간 설명 필드 업데이트</td> 
   <td><p>복사 대상: 마지막 Marketo 참여 설명<br>복사 위치: 마지막 관심 순간 설명</p></td> 
  </tr> 
  <tr> 
   <td>관심 순간 유형 필드 업데이트</td> 
   <td><p>복사 대상: 마지막 Marketo 참여 유형<br>복사 위치: 마지막 관심 순간 유형</p></td> 
  </tr> 
  <tr> 
   <td>관심 순간 소스 필드 업데이트</td> 
   <td><p>복사 원본: 마지막 Marketo 참여 소스<br>복사 위치: 마지막 관심 순간 소스</p></td> 
  </tr> 
  <tr> 
   <td>관심 순간 날짜 필드 업데이트</td> 
   <td><p>복사 대상: 마지막 Marketo 참여 날짜<br>복사 위치: 마지막 관심 순간 날짜</p></td> 
  </tr> 
 </tbody> 
</table>

## 지침 {#instructions}

1. 클릭 후 **설정**, 검색 **워크플로** 및 선택 **워크플로 규칙**.

   ![](assets/one-1.png)

1. 선택 **새 규칙**.

   ![](assets/two-1.png)

1. Object 드롭다운을 클릭하고 을 선택합니다. **리드**&#x200B;을 클릭한 다음 을 클릭합니다 **다음**.

   ![](assets/three-1.png)

1. 규칙 이름으로 &quot;Update Interesting Moment Desc Field&quot;를 입력합니다. 라디오 단추를 선택합니다. **을 만들고 편집할 때마다**. 규칙 기준 드롭다운에서 다음을 선택합니다. **공식이 true로 평가됨**. ISCHANGED 함수를 검색하여 선택합니다. 그런 다음 기본 필드 값을 강조 표시하고 **필드 삽입**.

   ![](assets/four-1.png)

1. &quot;필드 삽입&quot; 팝업에서 **마지막 Marketo 참여 설명** 및 클릭 **삽입**.

   ![](assets/five-1.png)

1. 클릭 **저장 후 다음**.

   ![](assets/6.png)

1. 워크플로 작업 추가 드롭다운에서 다음을 선택합니다. **새 필드 업데이트**.

   ![](assets/seven.png)

1. 이름 필드에 &quot;Update Interest Moment Desc Field&quot;를 입력합니다(고유 이름이 자동으로 생성됨). 업데이트할 필드 드롭다운에서 **마지막 관심 순간 설명**. 다음 항목 선택 **공식을 사용하여 새 값 설정** 라디오 단추를 클릭한 다음 **수식 편집기 표시**.

   ![](assets/eight.png)

1. 다음을 클릭합니다. **필드 삽입** 단추를 클릭합니다.

   ![](assets/9a.png)

1. 선택 **마지막 Marketo 참여 설명**, 및 클릭 **삽입**. 다음 페이지에서 를 클릭합니다. **저장**.

   ![](assets/nine.png)

1. 클릭 **완료**.

   ![](assets/twelve.png)

1. 클릭 **활성화** 워크플로 규칙을 설정합니다.

   ![](assets/thirteen.png)

   마지막 단계 후에는 시작 섹션에 나열된 다른 필드에 대해 워크플로 규칙을 복제하도록 선택할 수 있습니다(설명, 유형, 소스, 날짜). Contact 개체에서 4개의 워크플로우 규칙을 완료한 후 Lead 개체에 대해 동일한 규칙을 반복합니다.
