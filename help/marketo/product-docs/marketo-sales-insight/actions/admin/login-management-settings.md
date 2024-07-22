---
description: 로그인 관리 설정 - Marketo 문서 - 제품 설명서
title: 로그인 관리 설정
exl-id: 077f7f97-1413-4495-b2c9-94194e8dbcc2
feature: Sales Insight Actions
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '471'
ht-degree: 0%

---

# 로그인 관리 설정 {#login-management-settings}

관리자는 로그인 관리 설정을 사용하여 글로벌 수준에서 Sales Insight 작업 사용자에 대한 인증 환경 설정을 지정할 수 있습니다.

>[!NOTE]
>
>기본적으로 Salesforce 전용 옵션은 Sales Insight Actions 인스턴스에 대해 선택됩니다. 사용자가 Salesforce에서 [자동 로그인](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md)할 수 있도록 이 설정을 사용하는 것이 좋습니다.

## 로그인 관리 설정 업데이트 {#update-login-management-settings}

>[!NOTE]
>
>**관리자 권한 필요**

로그인 관리 환경 설정을 업데이트하려면 다음 단계를 따르십시오.

1. 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/login-management-settings-1.png)

1. 관리자 설정에서 **일반**&#x200B;을 클릭합니다.

   ![](assets/login-management-settings-2.png)

1. Login Management 카드로 아래로 스크롤하고 원하는 설정을 선택합니다(이 예에서는 Salesforce만 선택). 완료되면 **저장**&#x200B;을 클릭합니다.

   ![](assets/login-management-settings-3.png)

## Salesforce만 해당 FAQ {#salesforce-only-faq}

Salesforce는 사용자가 Salesforce에서 Sales Insight 작업을 사용하기 위해서만 인증할 수 있음을 의미합니다. Sales Insight Actions 인스턴스의 기본 선택 항목이며, 사용자가 사용자 이름과 암호를 관리할 필요 없이 원활하게 인증할 수 있도록 하기 때문에 사용하는 것이 좋습니다.

### &quot;Salesforce만&quot;을 선택한 경우 내 인스턴스에 새 사용자는 어떻게 계정을 활성화합니까? {#activate-when-salesforce-only-is-selected}

초대 이메일에서 **시작하기** 버튼을 클릭하면 신규 사용자가 계정 활성화 화면으로 보내지며, 이 화면에서 Salesforce 인스턴스를 연결하여 Sales Insight Actions 계정을 활성화해야 합니다.

![](assets/login-management-settings-4.png)

### &quot;Salesforce만&quot;을 선택한 경우 내 사용자가 로 인증할 수 있는 인증 방법은 무엇입니까? {#what-authentication-methods}

로그인 화면으로 이동하면 사용자는 먼저 이메일 주소를 입력합니다. 그런 다음 Salesforce One Click Login 단추를 클릭하여 로그인한 Salesforce 계정을 사용하여 인증할 수 있습니다.

>[!NOTE]
>
>로그인 화면으로 직접 이동하는 사용자에게만 해당됩니다. Salesforce에서 작업에 액세스하는 사용자는 [자동 로그인](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md)을 통해 로그인됩니다.

![](assets/login-management-settings-5.png)

### 사용자가 Salesforce에서 작업 기능에 액세스하고 &quot;Salesforce만&quot;을 선택한 경우 작업에 대한 사용자 인증은 어떻게 처리됩니까? {#how-is-user-authentication-handled}

사용자가 작업(호출, 이메일, 캠페인, 작업, 캠페인 목록 등) 중 하나를 클릭하면 SFDC 인증을 사용하여 자동으로 Sales Insight Actions 계정에 로그인됩니다. 이 인증을 [자동 로그인](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md)이라고 합니다.

## 모든 로그인 방법 FAQ {#all-login-methods-faq}

### &quot;모든 로그인 방법&quot;을 선택한 경우 내 인스턴스에 새 사용자는 어떻게 계정을 활성화합니까? {#activate-when-all-login-methods-is-selected}

새 사용자가 인스턴스에 초대되면 계정 활성화 이메일을 받게 됩니다. &quot;시작&quot;이라는 버튼을 클릭하면 암호를 만들고 확인하라는 페이지로 이동합니다. 이를 만들면 계정이 활성화되고 온보딩 워크플로우를 통해 처리됩니다.

![](assets/login-management-settings-6.png)

### &quot;모든 로그인 방법&quot;을 선택한 경우 내 인스턴스 사용자가 로 로그인할 수 있는 것은 무엇입니까? {#what-are-users-allowed-to-log-in-with-all-login}

로그인 페이지를 사용할 때 사용자는 먼저 이메일 주소를 입력합니다. 그러면 인증할 모든 로그인 옵션(사용자 이름/암호, SFDC, Gmail, SSO)을 제공하는 페이지로 전송됩니다.
