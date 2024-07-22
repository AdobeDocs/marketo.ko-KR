---
description: Sales Insight Actions 관리 설정 안내서 - Marketo 문서 - 제품 설명서
title: Sales Insight Actions 관리 설정 안내서
exl-id: 339d518d-445b-4634-ab81-92c9d5541927
feature: Sales Insight Actions
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '655'
ht-degree: 0%

---

# Sales Insight Actions 관리 설정 안내서 {#sales-insight-actions-admin-setup-guide}

>[!NOTE]
>
>Marketo Sales Insight Actions는 [Marketo Sales Insight 패키지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}를 통해 Salesforce 사용자 인터페이스와 통합하는 웹 기반 애플리케이션입니다. 이를 때로 &quot;Marketo 영업&quot; 또는 간단히 &quot;작업&quot;이라고 합니다.

>[!PREREQUISITES]
>
>* Adobe 계정 팀(계정 관리자)에 MSI 작업이 Marketo Engage 계정에 대해 활성화되었는지 확인합니다(계정 관리자가 없는 경우 [Marketo 지원 센터](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 문의).
>* Marketo/Salesforce 동기화를 설정해야 합니다.

<table>
 <tr>
  <th>담당자</th>
  <th>단계</th>
 </tr>
 <tr>
  <td>Marketo 관리자</td>
  <td>Marketo 판매 계정 설정</td>
 </tr>
 <tr>
  <td>Marketo 관리자 또는 <br/>Salesforce 관리자</td>
  <td>Marketo 판매 계정을 Salesforce에 연결</td>
 </tr>
 <tr>
  <td>Marketo 관리자</td>
  <td>Marketo 판매 계정을 Marketo에 연결</td>
 </tr>
 <tr>
  <td>Marketo 관리자</td>
  <td>Marketo에서 Marketo 판매 계정으로 데이터 동기화 시작</td>
 </tr>
 <tr>
  <td>Marketo 관리자</td>
  <td>MSI-Actions에 사용자 초대</td>
 </tr>
 <tr>
  <td>Salesforce 관리자</td>
  <td>Salesforce의 MSI 패키지 설치/업그레이드</td>
 </tr>
 <tr>
  <td>Salesforce 관리자</td>
  <td>Salesforce에서 MSI-작업 구성</td>
 </tr>
</table>

## Marketo 판매 계정 설정 {#set-up-marketo-sales-account}

1. Marketo에서 **관리자**&#x200B;를 클릭합니다.

   ![](assets/msi-actions-admin-guide-1.png)

   >[!NOTE]
   >
   >통합 정보 카드에 클라이언트 ID 및 클라이언트 암호가 표시되지 않는 경우 첫 번째 사용자를 초대하여 작업 인스턴스를 활성화하면 클라이언트 ID 및 클라이언트 암호가 표시됩니다.

1. **판매 인사이트**&#x200B;를 클릭한 다음 **작업 구성**&#x200B;을 클릭합니다. 초대할 Marketo 관리자 목록에서 선택하고 **초대 보내기**&#x200B;를 클릭합니다.

   ![](assets/msi-actions-admin-guide-2.png)

사용자는 계정에 액세스할 수 있는 단계가 포함된 이메일을 받게 됩니다.

>[!NOTE]
>
>추가 사용자는 Marketo을 통해 추가되지 않고 대신 Sales Account User Management 페이지를 통해 추가됩니다. 추가 사용자 추가에 대한 자세한 내용을 보려면 [여기를 클릭하세요](/help/marketo/product-docs/marketo-sales-connect/admin/invite-users.md){target="_blank"}.

## Marketo 판매 계정을 Salesforce에 연결 {#connect-marketo-sales-account-to-salesforce}

1. Marketo 판매 계정에서 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/msi-actions-admin-guide-3.png)

1. 관리자 설정에서 **Salesforce**&#x200B;를 클릭합니다.

   ![](assets/msi-actions-admin-guide-4.png)

1. 연결 및 사용자 지정 탭에서 **연결**&#x200B;을 클릭합니다.

   ![](assets/msi-actions-admin-guide-5.png)

1. **확인**&#x200B;을 클릭합니다.

   ![](assets/msi-actions-admin-guide-6.png)

이미 Salesforce에 로그인한 경우에는 연결됩니다. 로그인하지 않은 경우 로그인하라는 메시지가 표시됩니다.

## Marketo을 Sales Apps 계정에 연결 {#connect-marketo-to-your-sales-apps-account}

1. Marketo 판매 계정에서 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/msi-actions-admin-guide-7.png)

1. [관리 설정]에서 **Marketo**&#x200B;을 클릭합니다.

   ![](assets/msi-actions-admin-guide-8.png)

1. **연결**&#x200B;을 클릭합니다. 그러면 계정이 연결됩니다.

   ![](assets/msi-actions-admin-guide-9.png)

>[!NOTE]
>
>연결되지 않는 경우 Marketo Sales Insight &quot;Actions Config&quot; 탭에서 자격 증명을 복사하여 설정 탭에 붙여넣습니다.

## 데이터 동기화 시작 {#initiate-data-sync}

Sales Insight Actions에 대한 데이터 통합 필드 동기화를 사용하면 시스템이 Marketo Engage 데이터베이스의 개인 정보를 Sales Insight Actions 데이터베이스로 가져와서 직원 데이터를 최신 상태로 유지하고 Marketo 및 Salesforce에서 활동이 올바른 레코드로 기록되도록 할 수 있습니다.

>[!CAUTION]
>
>데이터 동기화를 시작하면 Sales Insight Actions 인스턴스에서 원래 사용자를 **제거하지 않음**&#x200B;해야 합니다. 첫 번째 초대가 전송된 사용자입니다.

1. Marketo에서 **관리자**&#x200B;를 클릭합니다.

   ![](assets/msi-actions-admin-guide-10.png)

1. **판매 인사이트**&#x200B;를 클릭합니다.

   ![](assets/msi-actions-admin-guide-11.png)

1. **작업 구성** 탭을 클릭합니다. 작업 필드 동기화 카드에서 **동기화**&#x200B;를 클릭합니다.

   ![](assets/msi-actions-admin-guide-12.png)

1. 동기화할 필드의 미리 보기가 표시됩니다. **동기화 시작**&#x200B;을 클릭합니다.

   ![](assets/msi-actions-admin-guide-13.png)

Marketo 및 Salesforce에 있는 개인 레코드는 Marketo Sales Apps 계정에 동기화됩니다.

>[!NOTE]
>
>Sales Insight Actions, Marketo 및 Salesforce 간에 사람 및 활동 데이터를 동기화하는 방법에 대해 자세히 알아보려면 [여기를 클릭](/help/marketo/product-docs/marketo-sales-insight/actions/admin/sync-sales-action-data-with-marketo-and-salesforce.md){target="_blank"}하세요.

## MSI 작업에 개별 사용자 초대 {#invite-individual-users-to-msi-actions}

1. Marketo 판매 계정에서 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/msi-actions-admin-guide-14.png)

1. [관리 설정]에서 **사용자 관리**&#x200B;를 선택합니다.

   ![](assets/msi-actions-admin-guide-15.png)

1. **작업**&#x200B;을 클릭하고 **사용자 초대**&#x200B;를 선택합니다.

   ![](assets/msi-actions-admin-guide-16.png)

1. 전자 메일 주소를 입력하고 **초대**&#x200B;를 클릭하세요.

   ![](assets/msi-actions-admin-guide-17.png)

>[!NOTE]
>
>기본적으로 모든 새 멤버가 모든 사용자 팀에 추가됩니다.

확인 메시지가 표시됩니다.

## CSV를 통해 사용자를 MSI 작업에 초대 {#invite-users-via-csv-to-msi-actions}

1. Marketo 판매 계정에서 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/msi-actions-admin-guide-18.png)

1. [관리 설정]에서 **사용자 관리**&#x200B;를 선택합니다.

   ![](assets/msi-actions-admin-guide-19.png)

1. **작업**&#x200B;을 클릭하고 **CSV로 사용자 초대**&#x200B;를 선택합니다.

   ![](assets/msi-actions-admin-guide-20.png)

1. 컴퓨터에서 CSV를 찾아 선택한 다음 **다음**&#x200B;을 클릭합니다.

   ![](assets/msi-actions-admin-guide-21.png)

1. 필드가 올바르게 매핑되었는지 확인하고 **초대**&#x200B;를 클릭합니다.

   ![](assets/msi-actions-admin-guide-22.png)

초대가 전송되면 확인 메시지를 받게 됩니다.

>[!NOTE]
>
>이 작업이 완료되면 기존 MSI 패키지를 업그레이드하거나 새 패키지를 설치하고 [Salesforce에서 MSI 동작 구성](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/sales-insight-actions-configuration-in-salesforce.md){target="_blank"}(으)로 이동할 수 있습니다.
