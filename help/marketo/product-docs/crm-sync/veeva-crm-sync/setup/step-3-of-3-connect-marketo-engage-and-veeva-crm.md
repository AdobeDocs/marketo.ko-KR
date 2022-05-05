---
description: 3단계 중 3단계 - Connect Marketo Engage 및 Evar CRM - Marketo 문서 - 제품 설명서
title: 3단계 중 3단계 - Marketo Engage 및 Veva CRM 연결
exl-id: aff91540-1d9d-448c-aae9-e6fa92a8ae01
source-git-commit: 2ce44b7c44517a6fdb3f616a3d69b25158ea4ec9
workflow-type: tm+mt
source-wordcount: '345'
ht-degree: 0%

---

# 3단계 중 3단계: Connect Marketo Engage 및 Evar CRM {#step-3-of-3-connect-marketo-engage-and-veeva-crm}

이 문서에서는 구성된 Vec CRM 인스턴스와 동기화하도록 Marketo Engage을 구성합니다. **일부 팝업에서 Salesforce를 볼 수 있습니다** veva CRM은 Salesforce 플랫폼에 구축됩니다.

>[!PREREQUISITES]
>
>* [3단계 중 1단계: Veva에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target=&quot;_blank&quot;}
>* [3단계 중 2단계: Marketo용 Veva 사용자 만들기](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-2-of-3-create-a-veeva-crm-user-for-marketo-engage.md){target=&quot;_blank&quot;}


>[!IMPORTANT]
>
>한 번에 하나의 Marketo 인스턴스만 Vec CRM 인스턴스에 연결할 수 있습니다.

## OAuth를 사용하여 Vec CRM에 연결 {#connect-to-veeva-crm-using-oauth}

1. Marketo에서 **관리**. 선택 **CRM** 을(를) 클릭합니다. **Veeva와 동기화**.

   ![](assets/step-3-of-3-connect-marketo-engage-1.png)

   >[!NOTE]
   >
   >반드시 다음을 수행하십시오 [필요하지 않은 모든 필드 숨기기](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync.md)동기화 필드를 클릭하기 전에 동기화 사용자가 Marketo에서 {target=&quot;_blank&quot;}를 클릭합니다. 동기화 필드 를 클릭하면 사용자가 볼 수 있는 모든 필드가 Marketo에 영구적으로 만들어지며 삭제할 수 없습니다.

1. 클릭 **Veva로 로그인**.

   ![](assets/step-3-of-3-connect-marketo-engage-2.png)

   >[!NOTE]
   >
   >Marketo 샌드박스를 Veva CRM 샌드박스에 동기화하는 경우 샌드박스 를 선택합니다.

1. 클릭 **자격 증명 확인**.

   ![](assets/step-3-of-3-connect-marketo-engage-3.png)

1. Salesforce 로그인 페이지에 대한 팝업이 표시됩니다. &quot;Marketo 동기화 사용자&quot; 자격 증명을 입력하고 **로그인**.

   ![](assets/step-3-of-3-connect-marketo-engage-4.png)

1. 전자 메일(Salesforce에서 전송)을 통해 받은 확인 코드를 입력하고 를 클릭합니다. **확인**.

   ![](assets/step-3-of-3-connect-marketo-engage-5.png)

1. 확인을 성공하면 액세스 페이지가 액세스 요청을 표시합니다. 클릭 **허용**.

   ![](assets/step-3-of-3-connect-marketo-engage-6.png)

1. 몇 분 후에 Marketo Engae에 팝업이 나타납니다. 클릭 **자격 증명 확인**.

   ![](assets/step-3-of-3-connect-marketo-engage-7.png)

## Veva 동기화 시작 {#start-veeva-sync}

1. 클릭 **Veva 동기화 시작** 영구적 Marketo-Veeva CRM 동기화를 시작하기 위해 다음을 수행하십시오.

   ![](assets/step-3-of-3-connect-marketo-engage-8.png)

   >[!CAUTION]
   >
   >Marketo은 Vec CRM 동기화에 대해 자동으로 중복 제거를 수행하지 않거나 수동으로 리드를 입력할 때 자동으로 중복 제거를 수행하지 않습니다.

1. 클릭 **동기화 시작**.

   ![](assets/step-3-of-3-connect-marketo-engage-9.png)

>[!NOTE]
>
>초기 동기화를 완료하는 시간은 데이터베이스의 크기와 복잡성에 따라 다릅니다.

## 동기화 확인 {#verify-sync}

Marketo은 관리 영역에서 Vec CRM 동기화에 대한 상태 메시지를 제공합니다. 다음 단계를 수행하여 동기화가 올바르게 작동하는지 확인할 수 있습니다.

1. Marketo에서 **관리**, 그런 다음 **베바**.

   ![](assets/step-3-of-3-connect-marketo-engage-10.png)

1. 동기화 상태는 오른쪽 위 모서리에 표시됩니다. 다음 세 메시지 중 하나를 표시합니다. 마지막 동기화, 동기화 진행 중 또는 실패.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 구성](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/custom-object-sync.md){target=&quot;_blank&quot;}
