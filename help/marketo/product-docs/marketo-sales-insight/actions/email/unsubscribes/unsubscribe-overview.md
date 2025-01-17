---
description: 구독 취소 개요 - Marketo 문서 - 제품 설명서
title: 구독 취소 개요
exl-id: 7598efa9-9686-4dd0-840b-f8b6de4ab2be
feature: Sales Insight Actions
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 0%

---

# 구독 취소 개요 {#unsubscribe-overview}

조직이 이메일 개인정보 보호법을 준수하는 것이 점점 더 중요해지고 있습니다. 이를 위해 구독 취소 경험을 일부 개선했습니다.

* 구독 취소 링크는 Marketo Sales 및 Salesforce에서 보낸 모든 이메일에 배치됩니다(Outlook 또는 Gmail에서 보낸 사용자 정의 이메일에는 적용되지 않음).
* 관리자는 전체 팀에 대한 구독 취소 메시지를 편집할 수 있습니다.
* 구독 취소 정보는 PDV에 저장됩니다.
* 클릭 링크, Salesforce 동기화 및 바운스 수 등 구독 취소를 수동으로 수행할 수 있습니다.
* 새 구독 취소 링크 랜딩 페이지

## 구독 취소 링크 랜딩 페이지 {#unsubscribe-link-landing-page}

구독 취소 링크를 클릭하면 구독 취소 랜딩 페이지로 이동되어 구독 취소하려는 항목과 그 이유를 선택할 수 있습니다.

![](assets/unsubscribe-overview-1.png)

이 정보는 나중에 볼 수 있도록 개인 세부 정보 보기에 저장됩니다.

## 그룹 구독 취소 {#unsubscribe-group}

한 곳에서 구독 취소한 모든 사람을 보고 관리합니다.

![](assets/unsubscribe-overview-2.png)

검색 창을 사용하여 구독 취소한 사람을 조회합니다.

![](assets/unsubscribe-overview-3.png)

관리자의 경우 구독 취소 그룹으로 이동하여 계정 구독 취소 를 기준으로 필터링하고 사용자 데이터베이스에 수집된 모든 구독 취소를 볼 수 있습니다.

![](assets/unsubscribe-overview-4.png)

## 가입 해지 기록 카드 {#unsubscribe-history-card}

구독 취소 기록 카드를 사용하면 관리자와 사용자가 연락처의 구독 취소 기록에 대한 상황별 정보를 얻을 수 있습니다. 사람 탭으로 이동하여 사용자를 선택합니다. 개인 세부 정보 보기의 정보 탭 하단에 있습니다.

>[!NOTE]
>
>특정 시점에 해당 사용자가 _구독 취소_&#x200B;한 경우에만 구독 취소 기록 카드가 있습니다.

![](assets/unsubscribe-overview-5.png)

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>날짜</strong></td> 
   <td><p>구독 취소/다시 구독이 발생한 날짜를 표시합니다.</p></td> 
  </tr> 
  <tr> 
   <td><strong>세부 정보</strong></td> 
   <td><p>재가입: Sales Connect 관리자가 연락처 레코드에서 가입 해지를 수동으로 제거했습니다. 또한 연락처의 구독을 취소한 이유와 관련된 몇 가지 세부 정보가 표시될 수 있습니다.</p><p>구독 취소: 연락처의 구독을 취소했습니다.</p></td> 
  </tr> 
  <tr> 
   <td><strong>소스</strong></td> 
   <td><p>Salesforce 동기화: 구독 취소가 Salesforce의 동기화에서 캡처되었습니다.</p><p>수동: 사용자가 구독 취소 버튼을 클릭하여 옵트아웃했습니다.</p><p>클릭한 링크: 이메일 수신자가 구독 취소 링크를 클릭했습니다.</p><p>"관리자 이름": 작업을 통해 연락처를 다시 구독하면 관리자의 이름이 표시됩니다. 이를 통해 사용자는 구독 취소를 제거한 사용자를 알 수 있습니다.</p></td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[구독 취소 링크 메시지 사용자 지정](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/customize-unsubscribe-link-message.md)
