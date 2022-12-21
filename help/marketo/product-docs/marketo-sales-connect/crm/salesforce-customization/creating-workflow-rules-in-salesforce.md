---
unique-page-id: 14745823
description: Salesforce에서 워크플로우 규칙 만들기 - Marketo 문서 - 제품 설명서
title: Salesforce에서 워크플로우 규칙 만들기
exl-id: 0cfce178-453b-4949-96aa-c327278a267d
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '470'
ht-degree: 0%

---

# Salesforce에서 워크플로우 규칙 만들기 {#creating-workflow-rules-in-salesforce}

Marketo Sales Insight(MSI) 및 Marketo Sales Connect(MSC)를 동시에 사용하는 경우 Salesforce의 MSI Best Bets 기능이 업데이트되지 않습니다. 다른 모든 MSI 기능은 평소대로 작동합니다(iFrame에서 흥미로운 시간 보기, 이메일 보내기, 캠페인에 추가 등). 이 문서에서는 Best Bets 가 다시 작동하도록 하는 해결 방법을 제공합니다.

>[!NOTE]
>
>이 기능은 **둘 다** MSI 및 MSE이며 MSI에서 최고의 최상의 선택 기능을 사용하려는 사용자입니다. Best Bets가 필요/사용되지 않으면 무시해도 됩니다.

## 시작하기 {#getting-started}

해결 방법에는 새 MSE 필드의 값을 이전 MSI 필드에 복사하는 새 워크플로우 규칙을 만드는 작업이 포함됩니다. Contact 개체에 대해 4개의 워크플로우 규칙을 만들고 Salesforce 인스턴스에 있는 Lead 개체에 대해 동일한 4개의 워크플로우 규칙을 만들어야 합니다. 이렇게 하려면 CRM 관리 권한이 있어야 할 수 있습니다(CRM의 역할 및 설정에 따라 다름).

다음은 워크플로우 규칙의 권장 이름과 각 규칙에 대한 설명입니다. Contact 및 Lead 객체에 적용됩니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td>관심 모멘트 설명 필드 업데이트</td> 
   <td><p>복사 위치: 마지막 Marketo 참여 설명<br>복사 대상: 마지막 흥미로운 모멘트 설명</p></td> 
  </tr> 
  <tr> 
   <td>관심 모멘트 유형 필드 업데이트</td> 
   <td><p>복사 위치: 마지막 Marketo 참여 유형<br>복사 대상: 마지막 흥미로운 모멘트 유형</p></td> 
  </tr> 
  <tr> 
   <td>관심 모멘트 소스 필드 업데이트</td> 
   <td><p>복사 위치: 마지막 Marketo 참여 소스<br>복사 대상: 마지막 관심 영역 소스</p></td> 
  </tr> 
  <tr> 
   <td>관심 모멘트 날짜 필드 업데이트</td> 
   <td><p>복사 위치: 마지막 Marketo 참여 날짜<br>복사 대상: 마지막 흥미로운 모멘트 날짜</p></td> 
  </tr> 
 </tbody> 
</table>

## 지침 {#instructions}

1. 클릭 후 **설정**, 검색 **워크플로우** 을(를) 선택합니다. **워크플로우 규칙**.

   ![](assets/one-1.png)

1. 선택 **새 규칙**.

   ![](assets/two-1.png)

1. 개체 드롭다운을 클릭하고 을 선택합니다 **리드**&#x200B;를 클릭한 다음 **다음**.

   ![](assets/three-1.png)

1. 규칙 이름으로 &quot;관심 모멘트 설명 필드 업데이트&quot;를 입력합니다. 라디오 단추를 선택합니다 **만들 때마다**. 규칙 기준 드롭다운에서 을 선택합니다. **수식은 true로 평가됩니다.**. ISCHANGED 함수를 검색하고 선택합니다. 그런 다음 기본 필드 값을 강조 표시하고 를 클릭합니다 **필드 삽입**.

   ![](assets/four-1.png)

1. &quot;필드 삽입&quot; 팝업에서 **마지막 Marketo 참여 설명** 을(를) 클릭합니다. **삽입**.

   ![](assets/five-1.png)

1. 클릭 **저장 및 다음**.

   ![](assets/6.png)

1. 워크플로우 작업 추가 드롭다운에서 을 선택합니다 **새 필드 업데이트**.

   ![](assets/seven.png)

1. 이름 필드에 &quot;관심 모멘트 설명 필드 갱신&quot;을 입력합니다(고유 이름은 자동으로 생성됩니다). 업데이트할 필드 드롭다운에서 을 선택합니다. **마지막 흥미로운 모멘트 설명**. 을(를) 선택합니다 **수식을 사용하여 새 값 설정** 라디오 단추를 클릭한 다음 **수식 편집기 표시**.

   ![](assets/eight.png)

1. 을(를) 클릭합니다. **필드 삽입** 버튼을 클릭합니다.

   ![](assets/9a.png)

1. 선택 **마지막 Marketo 참여 설명**&#x200B;를 클릭하고 **삽입**. 다음 페이지에서 **저장**.

   ![](assets/nine.png)

1. 클릭 **완료**.

   ![](assets/twelve.png)

1. 클릭 **활성화** 을 눌러 워크플로우 규칙을 설정합니다.

   ![](assets/thirteen.png)

   마지막 단계 후에는 시작하기 섹션에 나열된 다른 필드에 대해 워크플로우 규칙을 복제하도록 선택할 수 있습니다. 설명, 유형, 출처, 일자 Contact 개체에서 4개의 워크플로우 규칙을 완료하면 Lead 개체에 대해 같은 작업을 반복합니다.
