---
unique-page-id: 3571800
description: 3단계 중 3단계 - Connect Marketing & Salesforce(Professional) - Marketing Docs - 제품 설명서
title: 3단계 중 3단계 - Connect Marketing 및 Salesforce(Professional)
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '382'
ht-degree: 0%

---


# 3단계 중 3단계:Connect Marketing &amp; Salesforce(Professional) {#step-of-connect-marketo-and-salesforce-professional}

이 문서에서는 구성된 Salesforce 인스턴스와 동기화하도록 Marketing을 구성합니다.

>[!PREREQUISITES]
>
>* [3단계 중 1단계:Salesforce에 마케팅 필드 추가(Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-1-of-3-add-marketo-fields-to-salesforce-professional.md)
>* [3단계 중 2단계:Marketing용 Salesforce 사용자 만들기(Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md)


## 동기화 사용자 보안 토큰 검색 {#retrieve-sync-user-security-token}

>[!TIP]
>
>이미 보안 토큰이 있는 경우 [사용자 자격 증명 동기화 설정] 및 [kdos 설정]으로 바로 이동하여 준비하십시오!

1. Marketing To Sync 사용자를 사용하여 Salesforce에 로그인하고 동기화 사용자의 이름을 클릭한 다음 **내 설정**.

   ![](assets/image2015-5-21-14-3a11-3a17.png)

1. 탐색 도구 모음에서 &quot;reset&quot;을 입력하고 **내 보안 토큰 재설정**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a52-3a42.png)

1. **보안 토큰 재설정**&#x200B;을 클릭합니다.

   ![](assets/image2015-5-21-14-3a13-3a5.png)

   전자 메일로 보안 토큰이 전송됩니다.

## 사용자 자격 증명 동기화 설정 {#set-sync-user-credentials}

1. Marketing에서 **관리**&#x200B;로 이동하고 **CRM**&#x200B;을 선택하고 **Salesforce.com](https://Salesforce.com)**&#x200B;과 동기화를 클릭합니다.[

   ![](assets/image2014-12-9-9-3a52-3a58.png)

   >[!NOTE]
   >
   >**필드 동기화**&#x200B;를 클릭하기 전에 Marketing에서 ](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync/hide-a-salesforce-field-from-the-marketo-sync.md)이(가) 필요하지 않은 모든 필드를 동기화 사용자로부터 숨겨야 합니다. [ [필드 동기화]를 클릭하면 사용자가 볼 수 있는 모든 필드가 Marketing Cloud에서 영구적으로 만들어지며 삭제할 수 없습니다.

1. Salesforce 구성 중 2번째 부분에서 만든 Salesforce 동기화 사용자 자격 증명을 입력하고([Professional](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-2-of-3-create-a-salesforce-user-for-marketo-professional.md), [Enterprise](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)필드 동기화&#x200B;**를 클릭합니다.**

   ![](assets/image2014-12-9-9-3a53-3a8.png)

   >[!NOTE]
   >
   >Marketing To 샌드박스를 Salesforce 샌드박스와 동기화하는 경우 **샌드박스**&#x200B;를 선택합니다.

1. 경고를 읽은 다음 **자격 증명 확인**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a53-3a16.png)

   >[!CAUTION]
   >
   >[매핑을 검토하고 ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/edit-initial-field-mappings.md)을(를) 사용자 지정하려면, 이 방법만 사용하십시오! Salesforce 동기화 시작을 클릭하면 완료됩니다.

## Salesforce 동기화 시작 {#start-salesforce-sync}

1. 지속적인 Marketing-Salesforce 동기화를 시작하려면 **Salesforce 동기화 시작**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a53-3a24.png)

   >[!CAUTION]
   >
   >Salesforce 동기화에 대해 또는 리드를 수동으로 입력할 때 Marketing To는 자동으로 중복 제거 기능을 사용하지 않습니다.

1. **동기화 시작**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-9-9-3a53-3a32.png)

   >[!NOTE]
   >
   >초기 동기화를 완료하는 시간은 데이터베이스의 크기와 복잡성에 따라 다릅니다.

## 동기화 확인 {#verify-sync}

Marketing은 관리 영역에서 Salesforce 동기화에 대한 상태 메시지를 제공합니다. 다음 단계에 따라 동기화가 올바르게 작동하는지 확인할 수 있습니다.

1. Marketing에서 **관리**&#x200B;를 클릭한 다음 **Salesforce**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-9-3a53-3a40.png)

1. 동기화 상태는 오른쪽 위 모서리에 표시됩니다. 3개의 메시지 중 하나를 표시합니다.**마지막 동기화**, **진행 중 동기화** 또는 **실패**.

   ![](assets/image2014-12-9-9-3a53-3a50.png)

   ![](assets/image2014-12-9-9-3a54-3a4.png)

   ![](assets/image2014-12-9-9-3a54-3a35.png)

Marketing To의 가장 강력한 기능 중 하나를 구성하셨다면 지금 바로 경험해 보십시오!

>[!MORELIKETHIS]
>
>* [Salesforce AppExchange에 Marketing To Sales Insight 패키지 설치](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)
>* [Salesforce Professional Edition에서 Marketing To Sales Insight 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md)

