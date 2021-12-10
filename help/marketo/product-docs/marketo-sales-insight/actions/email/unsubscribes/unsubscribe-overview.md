---
description: 가입 해지 개요 - Marketo 문서 - 제품 설명서
title: 구독 취소 개요
hide: true
hidefromtoc: true
exl-id: 7598efa9-9686-4dd0-840b-f8b6de4ab2be
source-git-commit: fda1bf51d4016a61c41be9acba4771db1797a552
workflow-type: tm+mt
source-wordcount: '348'
ht-degree: 0%

---

# 구독 취소 개요 {#unsubscribe-overview}

조직에서 전자 메일 개인 정보 보호 법을 준수하는 것이 점점 중요해지고 있습니다. 이를 지원하기 위해 Adobe는 구독 취소 경험을 일부 개선했습니다.

* 구독 취소 링크는 Marketo 판매 및 Salesforce에서 보낸 모든 이메일에 배치됩니다(Outlook 또는 Gmail에서 보낸 사용자 지정 이메일에는 적용되지 않음)
* 관리자는 전체 팀에 대한 구독 취소 메시지를 편집할 수 있습니다
* 구독 취소 정보는 PDV에 저장됩니다
* 가입 해제는 수동으로 수행할 수 있습니다. 링크, Salesforce 동기화 및 바운스를 클릭함
* 새 구독 취소 링크 랜딩 페이지

## 링크 랜딩 페이지 구독 취소 {#unsubscribe-link-landing-page}

사용자가 가입 해지 링크를 클릭하면 가입 해지 랜딩 페이지로 이동되며, 여기에서 가입 해지할 사항과 그 이유를 선택할 수 있습니다.

![](assets/unsubscribe-overview-1.png)

이 정보는 나중에 볼 수 있도록 개인 세부 사항 보기에 저장됩니다.

## 그룹 가입 해지 {#unsubscribe-group}

구독하지 않은 모든 사용자를 한 곳에서 확인하고 관리합니다.

![](assets/unsubscribe-overview-2.png)

검색 막대를 사용하여 구독하지 않은 사람을 조회합니다.

![](assets/unsubscribe-overview-3.png)

관리자는 가입 해지됨 그룹으로 이동하여 계정 가입 해지 별로 필터링하고 사람 데이터베이스에 수집된 모든 가입 해지 수를 볼 수 있습니다.

![](assets/unsubscribe-overview-4.png)

## 기록 카드 가입 해지 {#unsubscribe-history-card}

가입 해지 내역 카드는 관리자와 사용자가 연락처의 가입 해지 기록에 대한 상황별 정보를 얻을 수 있도록 해줍니다. 사람 탭으로 이동하여 사람을 선택하여 해당 페이지로 이동합니다. 개인 세부 사항 보기의 정보 탭 하단에 있습니다.

>[!NOTE]
>
>수신자가 가입 해지 내역 카드만 있습니다 _재구독_ 어느 시점에서

![](assets/unsubscribe-overview-5.png)

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>날짜</strong></td> 
   <td><p>가입 해지/재구독한 날짜를 표시합니다.</p></td> 
  </tr> 
  <tr> 
   <td><strong>세부 사항</strong></td> 
   <td><p>다시 구독: Sales Connect 관리자가 수동으로 연락처 레코드에서 가입을 제거했습니다. 연락처가 구독을 취소한 이유와 관련된 세부 정보도 표시될 수 있습니다.</p><p>구독 취소: 연락처가 가입 해지되었습니다.</p></td> 
  </tr> 
  <tr> 
   <td><strong>원문</strong></td> 
   <td><p>Salesforce 동기화: Salesforce의 동기화를 통해 구독을 해지했습니다.</p><p>수동: 사용자가 가입 해지 단추를 클릭하여 옵트아웃합니다.</p><p>클릭한 링크: 이메일 수신자가 가입 해지 링크를 클릭합니다.</p><p>"관리자 이름": 연락처에 다시 가입하는 작업이 수행된 관리 이름이 표시됩니다. 이를 통해 사용자는 누가 구독을 취소한 것인지 알 수 있습니다.</p></td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[구독 취소 링크 메시지 사용자 지정](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/customize-unsubscribe-link-message.md)
