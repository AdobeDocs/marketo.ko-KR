---
description: MSI 작업 관리 안내서 - Marketo 문서 - 제품 설명서
title: MSI 작업 관리 안내서
hide: true
hidefromtoc: true
exl-id: 339d518d-445b-4634-ab81-92c9d5541927
source-git-commit: 8d19489d50213f81097307eded9f9d21c6537143
workflow-type: tm+mt
source-wordcount: '556'
ht-degree: 0%

---

# MSI 작업 관리 안내서 {#msi-actions-admin-guide}

>[!PREREQUISITES]
>
>* Customer Success Manager에게 MSI 작업이 Marketo 계정에 대해 활성화되었는지 확인합니다(CSM이 없는 경우, [Marketo 지원 문의](https://nation.marketo.com/t5/support/ct-p/Support)).
>* Marketo/Salesforce 동기화를 설정해야 합니다.


<table>
 <tr>
  <th>페르소나</th>
  <th>단계</th>
 </tr>
 <tr>
  <td>Marketo 관리</td>
  <td>Marketo 판매 계정 설정</td>
 </tr>
 <tr>
  <td>Marketo 관리자 또는 <br/>Salesforce 관리</td>
  <td>Salesforce에 Marketo 영업 계정 연결</td>
 </tr>
 <tr>
  <td>Marketo 관리</td>
  <td>Marketo에 Marketo 영업 계정 연결</td>
 </tr>
 <tr>
  <td>Marketo 관리</td>
  <td>Marketo에서 Marketo Sales Account로 데이터 동기화 시작</td>
 </tr>
 <tr>
  <td>Marketo 관리</td>
  <td>MSI-작업에 사용자 초대</td>
 </tr>
 <tr>
  <td>Salesforce 관리</td>
  <td>Salesforce에서 MSI 패키지 설치/업그레이드</td>
 </tr>
 <tr>
  <td>Salesforce 관리</td>
  <td>Salesforce에서 MSI-작업 구성</td>
 </tr>
</table>

## Marketo 판매 계정 설정 {#set-up-marketo-sales-account}

1. Marketo에서 **관리**.

   ![](assets/msi-actions-admin-guide-1.png)

1. 클릭 **Sales Insight**, 그런 다음 **작업 구성**. 초대할 Marketo 관리자 목록에서 선택하고 **초대 보내기**.

   ![](assets/msi-actions-admin-guide-2.png)

사용자는 계정에 액세스할 수 있는 단계를 포함하는 이메일을 받게 됩니다.

>[!NOTE]
>
>추가 사용자는 Marketo을 통해 추가되지 않고 대신 판매 계정 사용자 관리 페이지를 통해 추가됩니다. [여기를 클릭하십시오.](/help/marketo/product-docs/marketo-sales-connect/admin/invite-users.md) 추가 사용자 추가에 대해 자세히 알아보십시오.

## Salesforce에 Marketo 영업 계정 연결 {#connect-marketo-sales-account-to-salesforce}

1. Marketo Sales 계정에서 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/msi-actions-admin-guide-3.png)

1. 관리자 설정에서 을 클릭합니다. **Salesforce**.

   ![](assets/msi-actions-admin-guide-4.png)

1. 연결 및 사용자 지정 탭에서 **Connect**.

   ![](assets/msi-actions-admin-guide-5.png)

1. 클릭 **확인**.

   ![](assets/msi-actions-admin-guide-6.png)

Salesforce에 이미 로그인한 경우 연결됩니다. 그렇지 않으면 로그인하라는 메시지가 표시됩니다.

## Sales Apps 계정에 Marketo 연결 {#connect-marketo-to-your-sales-apps-account}

1. Marketo Sales 계정에서 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/msi-actions-admin-guide-7.png)

1. 관리자 설정에서 을 클릭합니다. **Marketo**.

   ![](assets/msi-actions-admin-guide-8.png)

1. 클릭 **connect**. 그러면 계정이 연결됩니다.

   ![](assets/msi-actions-admin-guide-9.png)

>[!NOTE]
>
>연결되지 않은 경우 Marketo Sales Insight &quot;작업 구성&quot; 탭에서 자격 증명을 복사하여 설정 탭에 붙여넣습니다.

## 데이터 동기화 시작 {#initiate-data-sync}

Sales Insight Actions에 대한 데이터 통합 필드 동기화를 사용하면 시스템에서 Marketo Engage 데이터베이스의 개인 정보를 Sales Insight Actions 데이터베이스로 가져와서 사용자 데이터를 최신 상태로 유지하고 Marketo 및 Salesforce에서 올바른 레코드에 활동이 기록되도록 할 수 있습니다.

1. Marketo에서 **관리**.

   ![](assets/msi-actions-admin-guide-10.png)

1. 클릭 **Sales Insight**.

   ![](assets/msi-actions-admin-guide-11.png)

1. 을(를) 클릭합니다. **작업 구성** 탭. 작업 필드 동기화 카드에서 **동기화**.

   ![](assets/msi-actions-admin-guide-12.png)

1. 동기화할 필드의 미리 보기가 표시됩니다. 클릭 **동기화 시작**.

   ![](assets/msi-actions-admin-guide-13.png)

Marketo 및 Salesforce에 있는 개인 레코드는 Marketo Sales Apps 계정에 동기화됩니다.

>[!NOTE]
>
>Sales Insight Actions, Marketo 및 Salesforce 간에 사람 및 활동 데이터가 동기화되는 방법에 대해 자세히 알아보려면 [여기를 클릭하십시오.](/help/marketo/product-docs/marketo-sales-insight/actions/admin/actions-data-sync-faq.md).

## 개별 사용자를 MSI 작업에 초대 {#invite-individual-users-to-msi-actions}

1. Marketo Sales 계정에서 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/msi-actions-admin-guide-14.png)

1. 관리자 설정에서 을 선택합니다. **사용자 관리**.

   ![](assets/msi-actions-admin-guide-15.png)

1. 클릭 **작업** 을(를) 선택합니다. **사용자 초대**.

   ![](assets/msi-actions-admin-guide-16.png)

1. 이메일 주소를 입력하고 을(를) 클릭합니다. **초대**.

   ![](assets/msi-actions-admin-guide-17.png)

>[!NOTE]
>
>기본적으로 새 모든 구성원이 모든 사용자 팀에 추가됩니다.

확인 메시지가 나타납니다.

## CSV를 통해 MSI 작업에 사용자 초대 {#invite-users-via-csv-to-msi-actions}

1. Marketo Sales 계정에서 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/msi-actions-admin-guide-18.png)

1. 관리자 설정에서 을 선택합니다. **사용자 관리**.

   ![](assets/msi-actions-admin-guide-19.png)

1. 클릭 **작업** 을(를) 선택합니다. **CSV를 통해 사용자 초대**.

   ![](assets/msi-actions-admin-guide-20.png)

1. 컴퓨터에서 CSV를 찾아 선택한 다음 를 클릭합니다 **다음**.

   ![](assets/msi-actions-admin-guide-21.png)

1. 필드가 제대로 매핑되었는지 확인하고 를 클릭합니다 **초대**.

   ![](assets/msi-actions-admin-guide-22.png)

초대가 전송되면 확인 메시지가 표시됩니다.

>[!NOTE]
>
>이 작업이 완료되면 기존 MSI 패키지를 업그레이드하거나 새 패키지를 설치하고 다음 위치로 이동할 수 있습니다 [salesforce에서 MSI 작업 구성](/help/marketo/product-docs/marketo-sales-insight/actions/salesforce-configuration/msi-actions-configuration-in-salesforce.md).
