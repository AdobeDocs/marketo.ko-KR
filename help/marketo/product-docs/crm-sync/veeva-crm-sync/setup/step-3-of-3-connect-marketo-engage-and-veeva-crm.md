---
description: 3/3단계 - Marketo Engage 및 Veeva CRM 연결 - Marketo 문서 - 제품 설명서
title: 3/3단계 - Marketo Engage 및 Veeva CRM 연결
exl-id: aff91540-1d9d-448c-aae9-e6fa92a8ae01
feature: Veeva CRM
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---

# 3/3단계: Marketo Engage 및 Veeva CRM 연결 {#step-3-of-3-connect-marketo-engage-and-veeva-crm}

이 문서에서는 구성된 Veeva CRM 인스턴스와 동기화하도록 Marketo Engage을 구성합니다. Veeva CRM이 Salesforce 플랫폼에 구축되어 있으므로 **일부 팝업에 Salesforce가 표시됩니다**.

>[!PREREQUISITES]
>
>* [3단계 중 1단계: Veeva에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target="_blank"}
>* [3단계 중 2단계: Marketo용 Veeva 사용자 만들기](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-2-of-3-create-a-veeva-crm-user-for-marketo-engage.md){target="_blank"}

>[!IMPORTANT]
>
>한 번에 하나의 Marketo 인스턴스만 Veeva CRM 인스턴스에 연결할 수 있습니다.

## OAuth를 사용하여 Veeva CRM에 연결 {#connect-to-veeva-crm-using-oauth}

1. Marketo에서 **[!UICONTROL 관리자]**&#x200B;를 클릭합니다. **[!UICONTROL CRM]**&#x200B;을 선택하고 **[!UICONTROL Veeva와 동기화]**&#x200B;를 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-1.png)

   >[!NOTE]
   >
   >동기화 필드 를 클릭하기 전에 동기화 사용자로부터 Marketo에서 [필요하지 않은 모든 필드를 숨기십시오](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync.md){target="_blank"}. 필드 동기화 를 클릭하면 사용자가 볼 수 있는 모든 필드가 Marketo에 영구적으로 만들어지며 삭제할 수 없습니다.

1. **[!UICONTROL Veeva로 로그인]**&#x200B;을 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-2.png)

   >[!NOTE]
   >
   >Marketo 샌드박스를 Veeva CRM 샌드박스와 동기화하는 경우 샌드박스 를 선택합니다.

1. **[!UICONTROL 자격 증명 확인]**&#x200B;을 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-3.png)

1. Salesforce 로그인 페이지가 표시되는 팝업이 나타납니다. &quot;Marketo 동기화 사용자&quot; 자격 증명을 입력하고 **[!UICONTROL 로그인]**&#x200B;을 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-4.png)

1. Salesforce에서 보낸 전자 메일을 통해 받은 확인 코드를 입력하고 **[!UICONTROL 확인]**&#x200B;을 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-5.png)

1. 확인이 성공하면 액세스 페이지에 액세스 요청이 표시됩니다. **[!UICONTROL 허용]**&#x200B;을 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-6.png)

1. 몇 분 후에 Marketo Engae에 팝업이 나타납니다. **[!UICONTROL 자격 증명 확인]**&#x200B;을 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-7.png)

## Veeva 동기화 시작 {#start-veeva-sync}

1. **[!UICONTROL Veeva Sync 시작]**&#x200B;을(를) 클릭하여 영구 Marketo-Veeva CRM 동기화를 시작합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-8.png)

   >[!CAUTION]
   >
   >Marketo은 Veeva CRM 동기화나 리드를 수동으로 입력하는 경우 중복 제거를 자동으로 수행하지 않습니다.

1. **[!UICONTROL 동기화 시작]**&#x200B;을 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-9.png)

>[!NOTE]
>
>초기 동기화를 완료하는 시간은 데이터베이스의 크기와 복잡성에 따라 다릅니다.

## 동기화 확인 {#verify-sync}

Marketo은 관리 영역에서 Veeva CRM 동기화에 대한 상태 메시지를 제공합니다. 다음 단계에 따라 동기화가 올바르게 작동하는지 확인할 수 있습니다.

1. Marketo에서 **[!UICONTROL 관리자]**&#x200B;를 클릭한 다음 **[!UICONTROL Veeva]**&#x200B;를 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-10.png)

1. 동기화 상태가 오른쪽 상단 모서리에 표시됩니다. 마지막 동기화, 동기화 진행 중 또는 실패의 세 메시지 중 하나가 표시됩니다.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 구성](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/custom-object-sync.md){target="_blank"}
