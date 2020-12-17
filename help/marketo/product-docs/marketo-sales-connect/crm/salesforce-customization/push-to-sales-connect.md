---
unique-page-id: 14352477
description: 판매 연결 푸시 - Marketing To Docs - 제품 설명서
title: Sales Connect로 푸시
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 0%

---


# 판매 연결에 푸시 {#push-to-sales-connect}

[종료 상태로 푸시] 단추를 누르면 Salesforce의 리드/연락처 목록이 표시되며 Sales Connect의 그룹으로 푸시됩니다. 그런 다음 Tout 추적이 첨부된 사용자 정의 가능한 그룹 이메일을 빠르게 보낼 수 있습니다.

## 요구 사항 {#requirements}

* `Salesforce Admin`에 의해 설치된 영업 연결 [Salesforce 패키지](http://docs.marketo.com/x/C4PS)

* `Push to Sales Connect`목록 보기에 설치된  `Salesforce Admin`

* Salesforce 연결 - 사용자가 Push를 사용할 수 있도록 Sales Connect 제작

## 방법 {#how-to}

1. Salesforce에서 **리드/연락처** 탭을 클릭합니다.
1. 이동 단추 옆에 있는 Sales Connect로 푸시할 목록 보기로 전환합니다.
1. **이동**&#x200B;을 클릭합니다.
1. 푸시할 리드/연락처를 모두 선택합니다.
1. **MSE**&#x200B;로 푸시를 선택합니다.
1. 푸시할 리드/연락처 수를 확인하는 새 창이 나타납니다. **그룹**&#x200B;으로 계속을 선택합니다. Sales Connect `will not push over` Salesforce의 `Email Opt Out` 또는 Sales Connect의 `Unsubscribed`로 표시된 모든 연락처

   >[!NOTE]
   >
   >Sales Connect는 &quot;SFDC-...&quot;라는 제목의 이 그룹을 추가합니다. 를 [웹 응용 프로그램](http://toutapp.com/login)의 [관계] 페이지로 이동합니다.

1. **전체 그룹에 이메일**&#x200B;을 선택하여 이 그룹 이메일을 보냅니다.

