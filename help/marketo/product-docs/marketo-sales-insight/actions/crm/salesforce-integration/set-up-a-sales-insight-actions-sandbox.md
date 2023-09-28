---
description: Sales Insight Actions 설정 샌드박스 - Marketo 문서 - 제품 설명서
title: Sales Insight Actions 샌드박스 설정
exl-id: 58af77ef-93ea-4149-be91-f86cdc8f7476
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '626'
ht-degree: 0%

---

# Sales Insight Actions 샌드박스 설정 {#set-up-a-sales-insight-actions-sandbox}

>[!NOTE]
>
>Marketo Sales Insight Actions 은 를 통해 Salesforce 사용자 인터페이스와 통합하는 웹 기반 애플리케이션입니다 [Marketo Sales Insight 패키지](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}. 이를 때로 &quot;Marketo 영업&quot; 또는 간단히 &quot;작업&quot;이라고 합니다.

Marketo 샌드박스가 있는 경우 테스트 목적으로 샌드박스와 함께 사용할 작업 인스턴스를 활성화할 수 있습니다.

작업 인스턴스를 설정할 때 Salesforce 샌드박스 또는 Salesforce 프로덕션으로 작동하도록 구성할지 여부를 결정해야 합니다. 이는 Salesforce에서 각 종단점에 대해 서로 다른 끝점을 사용하고 Actions에서 Salesforce에 대한 연결을 사용하여 사용자를 활성화하고 인증하기 때문입니다.

Salesforce 샌드박스 인스턴스에서 작동하도록 작업 인스턴스를 설정하려면 아래 단계를 따르십시오.

>[!NOTE]
>
>사용자가 다음 작업을 수행하는 방법에 대해 자세히 알아볼 수 있습니다 [액션 시트 활성화](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-checklist.md){target="_blank"}. You can also learn about how users will [authenticate with Salesforce](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"}. Additionally, if you prefer to have users authenticate with email and password, you can learn more about this in our [Login Management settings article](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}.

## Marketo 샌드박스에 프로비저닝할 작업 인스턴스 요청 {#request=an-actions-instance}

Sales Insight Actions 는 요청하지 않는 한 Marketo 샌드박스 인스턴스에 대해 활성화되지 않습니다. 요청을 제출하려면 Adobe 계정 팀(계정 관리자)에 문의하십시오.

## Marketo 샌드박스에 대한 작업 계정 프로비저닝 {#provision-your-actions-account}

Marketo 샌드박스에 대해 작업 이 활성화되면 아래 단계에 따라 새 인스턴스를 활성화해야 합니다.

1. Marketo 샌드박스 인스턴스에 로그인합니다.

1. 다음으로 이동 **관리자**.

1. 선택 **Sales Insight**.

1. 선택 **작업 구성**.

   >[!IMPORTANT]
   >
   >이메일 주소는 샌드박스와 프로덕션 인스턴스 모두에서 하나의 작업 인스턴스에만 사용할 수 있습니다. 프로덕션 및 샌드박스 간에 여러 인스턴스에 액세스해야 하는 관리자의 경우 각각에 대해 다른 이메일 주소를 사용해야 합니다.

1. 프로비저닝 카드에서 Sales Insight Actions 인스턴스에 초대할 사용자를 선택합니다.

## 작업 인스턴스 활성화 {#activate-your-actions-instance}

작업 인스턴스는 Salesforce 프로덕션 계정으로 활성화해야 합니다. 활성화되면 Salesforce 샌드박스 계정으로 전환할 수 있습니다.

1. 보낸 초대를 찾습니다.

1. 다음을 클릭합니다. **시작** 링크.

1. Salesforce 프로덕션 인스턴스로 활성화합니다.

1. 화면의 지침에 따라 계정을 설정합니다. 자세한 개요는 다음을 확인하십시오. [사용자 온보딩 문서](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-guide.md){target="_blank"}.

## Salesforce 샌드박스 인스턴스와 호환되도록 작업 인스턴스 준비 {#prepare-your-actions-instance}

작업을 수행하려면 먼저 Salesforce 프로덕션 사용자로 새 인스턴스를 활성화해야 합니다. 활성화하면 다음 단계를 사용하여 인스턴스가 Salesforce 샌드박스와 호환되도록 준비할 수 있습니다.

1. 필요한 경우 사용자 이름과 암호로 로그인할 수 있도록 로그인 설정을 &quot;모든 로그인 방법&quot;으로 업데이트합니다. 필요한 경우 모든 항목이 구성된 후 &quot;Salesforce만&quot;으로 다시 전환할 수 있습니다. [여기에서 방법 보기](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}.

1. Salesforce 프로덕션에서 연결을 끊고 Salesforce 샌드박스에 연결합니다. [여기에서 연결 방법 보기](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md){target="_blank"}. 3단계의 경우 &quot;Salesforce&quot; 대신 &quot;Sandbox&quot;를 선택합니다. 이미 연결되어 있는 경우 Salesforce 연결 및 사용자 지정 탭에 연결을 끊는 옵션이 표시됩니다.

>[!NOTE]
>
>Salesforce 인스턴스에 대한 사용자 정의 도메인이 있는 경우 Salesforce에 연결하거나 작업에 로그인하기 전에 Salesforce 인스턴스에 로그인하는 것이 좋습니다.

## 작업 인스턴스가 Salesforce 샌드박스와 호환되도록 변환되도록 요청 {#request-your-actions-instance-be-converted}

1. 연락처 [Marketo Engage 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} 새 Sales Insight Actions 인스턴스를 Salesforce Sandbox와 호환되도록 구성하도록 요청합니다.

1. toutapp.com/login 페이지의 &quot;Salesforce로 로그인&quot; 단추를 사용하여 로그인하여 모든 것이 올바르게 구성되어 있는지 테스트하십시오.

   ![](assets/set-up-a-sales-insight-actions-sandbox-1.png)

   >[!TIP]
   >
   >이때 문제가 발생하면 암호 재설정을 요청하고 암호를 사용하여 계정에 다시 액세스할 수 있습니다.

이제 인스턴스를 Salesforce 샌드박스 인스턴스와 함께 사용할 수 있습니다. 을(를) 사용하려면 [Salesforce 자동 로그인](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"} from Salesforce, you can switch back to "Salesforce Only" in your [Login Management settings](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}.

>[!NOTE]
>
>* [Sales Insight Actions 계정을 Salesforce에 연결](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md){target="_blank"}
>* [Sales Insight Actions 사용 온보딩 안내서](/help/marketo/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-user-onboarding-guide.md){target="_blank"}
>* [Salesforce에서 자동 로그인](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md){target="_blank"}
>* [로그인 관리 설정](/help/marketo/product-docs/marketo-sales-insight/actions/admin/login-management-settings.md){target="_blank"}
