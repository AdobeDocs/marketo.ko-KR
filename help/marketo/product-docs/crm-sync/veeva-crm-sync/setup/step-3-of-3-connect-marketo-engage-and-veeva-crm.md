---
description: 3단계/3단계 - Marketo Engage 및 [!DNL Veeva] CRM 연결 - Marketo 문서 - 제품 설명서
title: 3단계/3단계 - Marketo Engage 및 [!DNL Veeva] CRM 연결
exl-id: aff91540-1d9d-448c-aae9-e6fa92a8ae01
feature: Veeva CRM
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '305'
ht-degree: 1%

---

# 3단계/3단계: Marketo Engage 및 [!DNL Veeva] CRM 연결 {#step-3-of-3-connect-marketo-engage-and-veeva-crm}

이 문서에서는 구성된 [!DNL Veeva] CRM 인스턴스와 동기화하도록 Marketo Engage을 구성합니다. **CRM이 [!DNL Salesforce] 플랫폼에 구축되어 있으므로**&#x200B;일부 팝업에 [!DNL Veeva]이(가) 표시됩니다[!DNL Salesforce].

>[!PREREQUISITES]
>
>* [3단계 중 1단계:  [!DNL Veeva]](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target="_blank"}에 Marketo 필드 추가
>* [3단계 중 2단계:  [!DNL Veeva] Marketo용 사용자 만들기](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-2-of-3-create-a-veeva-crm-user-for-marketo-engage.md){target="_blank"}

>[!IMPORTANT]
>
>한 번에 하나의 Marketo 인스턴스만 [!DNL Veeva] CRM 인스턴스에 연결할 수 있습니다.

## OAuth를 사용하여 [!DNL Veeva] CRM에 연결 {#connect-to-veeva-crm-using-oauth}

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다. **[!UICONTROL CRM]**&#x200B;을(를) 선택하고 **[!UICONTROL Sync with Veeva]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-1.png)

   >[!NOTE]
   >
   >동기화 필드 를 클릭하기 전에 동기화 사용자로부터 Marketo에서 [필요하지 않은 모든 필드를 숨기십시오](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync.md){target="_blank"}. 필드 동기화 를 클릭하면 사용자가 볼 수 있는 모든 필드가 Marketo에 영구적으로 만들어지며 삭제할 수 없습니다.

1. **[!UICONTROL Login with Veeva]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-2.png)

   >[!NOTE]
   >
   >Marketo 샌드박스를 [!UICONTROL Sandbox] CRM 샌드박스와 동기화하는 경우 [!DNL Veeva]을(를) 확인하십시오.

1. **[!UICONTROL Confirm Credentials]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-3.png)

1. [!DNL Salesforce] 로그인 페이지가 포함된 팝업이 표시됩니다. &quot;Marketo 동기화 사용자&quot; 자격 증명을 입력하고 **[!UICONTROL Log In]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-4.png)

1. 전자 메일을 통해 받은 인증 코드([!DNL Salesforce]에서 보낸 코드)를 입력하고 **[!UICONTROL Verify]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-5.png)

1. 확인이 성공하면 액세스 페이지에 액세스 요청이 표시됩니다. **[!UICONTROL Allow]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-6.png)

1. 몇 분 후에 Marketo Engae에 팝업이 나타납니다. **[!UICONTROL Confirm Credentials]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-7.png)

## [!DNL Veeva] 동기화 시작 {#start-veeva-sync}

1. **[!UICONTROL Start Veeva Sync]**&#x200B;을(를) 클릭하여 영구 [!DNL Marketo-Veeva] CRM 동기화를 시작합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-8.png)

   >[!CAUTION]
   >
   >Marketo은 [!DNL Veeva] CRM 동기화에 대해 자동으로 중복 제거되지 않습니다. 또는 수동으로 잠재 고객을 입력해도 중복 제거되지 않습니다.

1. **[!UICONTROL Start Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-9.png)

>[!NOTE]
>
>초기 동기화를 완료하는 시간은 데이터베이스의 크기와 복잡성에 따라 다릅니다.

## 동기화 확인 {#verify-sync}

Marketo은 관리 영역에서 [!DNL Veeva] CRM 동기화에 대한 상태 메시지를 제공합니다. 다음 단계에 따라 동기화가 올바르게 작동하는지 확인할 수 있습니다.

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Veeva]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-3-connect-marketo-engage-10.png)

1. 동기화 상태가 오른쪽 상단 모서리에 표시됩니다. 마지막 동기화, 동기화 진행 중 또는 실패의 세 메시지 중 하나가 표시됩니다.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 구성](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/custom-object-sync.md){target="_blank"}
