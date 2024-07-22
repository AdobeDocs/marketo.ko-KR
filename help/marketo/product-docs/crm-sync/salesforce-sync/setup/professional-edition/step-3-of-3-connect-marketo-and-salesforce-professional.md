---
unique-page-id: 3571800
description: 3단계 중 3단계 - Marketo 및 Salesforce 연결(전문가) - Marketo 문서 - 제품 설명서
title: 3단계/3단계 - Marketo 및 Salesforce 연결(전문가)
exl-id: a35e22ef-6378-45e0-be7e-687b0832ecf3
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---

# 3단계/3단계: Marketo 및 Salesforce 연결(전문가) {#step-of-connect-marketo-and-salesforce-professional}

이 문서에서는 구성된 Salesforce 인스턴스와 동기화하도록 Marketo Engage을 구성합니다.

>[!PREREQUISITES]
>
>* [3단계 중 1단계: Salesforce(Professional)에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-1-of-3-add-marketo-fields-to-salesforce-professional.md){target="_blank"}
>* [3단계 중 2단계: Marketo(Professional)용 Salesforce 사용자 만들기](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md){target="_blank"}

## 동기화 사용자 보안 토큰 검색 {#retrieve-sync-user-security-token}

>[!TIP]
>
>이미 보안 토큰이 있는 경우 준비하려면 [동기화 사용자 자격 증명 및 쿠도 설정]으로 바로 진행하십시오.

1. Marketo 동기화 사용자로 Salesforce에 로그인하고 동기화 사용자 이름을 클릭한 다음 **[!UICONTROL 내 설정]**&#x200B;을 클릭합니다.

   ![](assets/image2015-5-21-14-3a11-3a17.png)

1. 탐색 검색 창에서 &quot;reset&quot;을 입력하고 **[!UICONTROL 내 보안 토큰 재설정]**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a52-3a42.png)

1. **[!UICONTROL 보안 토큰 재설정]**&#x200B;을 클릭합니다.

   ![](assets/image2015-5-21-14-3a13-3a5.png)

   보안 토큰이 이메일로 전송됩니다.

## 동기화 사용자 자격 증명 설정 {#set-sync-user-credentials}

1. Marketo에서 **[!UICONTROL 관리자]**(으)로 이동하고 **[!UICONTROL CRM]**&#x200B;을 선택한 다음 **[!UICONTROL Salesforce.com과 동기화]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-9-3a52-3a58.png)

   >[!NOTE]
   >
   >Marketo **[!UICONTROL 필드 동기화]**&#x200B;를 클릭하기 전에 동기화 사용자로부터 [필요하지 않은 모든 필드 숨기기](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync.md){target="_blank"}를 확인하세요. 필드 동기화 를 클릭하면 사용자가 볼 수 있는 모든 필드가 Marketo에 영구적으로 만들어지며 삭제할 수 없습니다.

1. Salesforce 구성 2부([Professional](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md), [Enterprise](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md))에서 만든 Salesforce 동기화 사용자 자격 증명을 입력하고 **[!UICONTROL 필드 동기화]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-9-3a53-3a8.png)

   >[!NOTE]
   >
   >Marketo 샌드박스를 Salesforce 샌드박스와 동기화하는 경우 **[!UICONTROL 샌드박스]**&#x200B;를 확인하세요.

1. 경고를 읽은 다음 **[!UICONTROL 자격 증명 확인]**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a53-3a16.png)

   >[!CAUTION]
   >
   >[매핑을 확인하고 맞춤화](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/edit-initial-field-mappings.md){target="_blank"}하려면 지금이 유일한 기회입니다! Salesforce 동기화 시작을 클릭하면 동기화가 완료되었습니다.

## Salesforce 동기화 시작 {#start-salesforce-sync}

1. **[!UICONTROL Salesforce 동기화 시작]**&#x200B;을 클릭하여 영구 Marketo-Salesforce 동기화를 시작합니다.

   ![](assets/image2014-12-9-9-3a53-3a24.png)

   >[!CAUTION]
   >
   >Marketo은 Salesforce 동기화나 가망 고객을 수동으로 입력하는 경우 자동으로 중복 제거되지 않습니다.

1. **[!UICONTROL 동기화 시작]**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a53-3a32.png)

   >[!NOTE]
   >
   >초기 동기화를 완료하는 시간은 데이터베이스의 크기와 복잡성에 따라 다릅니다.

## 동기화 확인 {#verify-sync}

Marketo은 관리 영역에서 Salesforce 동기화에 대한 상태 메시지를 제공합니다. 다음 단계에 따라 동기화가 올바르게 작동하는지 확인할 수 있습니다.

1. Marketo에서 **[!UICONTROL 관리자]**&#x200B;를 클릭한 다음 **Salesforce**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a53-3a40.png)

1. 동기화 상태가 오른쪽 상단 모서리에 표시됩니다. 세 개의 메시지 중 하나가 표시됩니다. **[!UICONTROL 마지막으로 동기화됨]**, **[!UICONTROL 동기화 진행 중]** 또는 **[!UICONTROL 실패]**.

   ![](assets/image2014-12-9-9-3a53-3a50.png)

   ![](assets/image2014-12-9-9-3a54-3a4.png)

   ![](assets/image2014-12-9-9-3a54-3a35.png)

Marketo의 가장 강력한 기능 중 하나를 구성했습니다. 바로 여기에서 확인하십시오.

>[!MORELIKETHIS]
>
>* [Salesforce AppExchange에 Marketo Sales Insight 패키지 설치](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}
>* [Salesforce Professional Edition에서 Marketo Sales Insight 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md){target="_blank"}
