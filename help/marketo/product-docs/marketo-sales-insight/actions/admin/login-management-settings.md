---
description: 로그인 관리 설정 - Marketo 문서 - 제품 설명서
title: 로그인 관리 설정
hide: true
hidefromtoc: true
exl-id: 077f7f97-1413-4495-b2c9-94194e8dbcc2
source-git-commit: 984a6dbd19d88db942d9d10bde4880a79feabcc7
workflow-type: tm+mt
source-wordcount: '471'
ht-degree: 0%

---

# 로그인 관리 설정 {#login-management-settings}

로그인 관리 설정을 사용하여 관리자는 전역 수준에서 Sales Insight Action 사용자에 대한 인증 환경 설정을 지정할 수 있습니다.

>[!NOTE]
>
>기본적으로 Sales Insight Actions 인스턴스에 대해 Salesforce 전용 옵션이 선택됩니다. 사용자가 다음을 수행할 수 있도록 이 설정을 사용하는 것이 좋습니다 [자동 로그인](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md) Salesforce에서

## 로그인 관리 설정 업데이트 {#update-login-management-settings}

>[!NOTE]
>
>**관리자 권한이 필요합니다.**

로그인 관리 환경 설정을 업데이트하려면 다음 단계를 따르십시오.

1. 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/login-management-settings-1.png)

1. 관리자 설정에서 을 클릭합니다. **일반**.

   ![](assets/login-management-settings-2.png)

1. 로그인 관리 카드로 아래로 스크롤하여 원하는 설정을 선택합니다(이 예에서는 Salesforce만 선택합니다.). 클릭 **저장** 완료 시.

   ![](assets/login-management-settings-3.png)

## Salesforce 전용 FAQ {#salesforce-only-faq}

Salesforce만 사용하면 사용자는 Salesforce에서 Sales Insight Action을 사용하도록 인증할 수 있습니다. Sales Insight Actions 인스턴스에 대한 기본 선택 항목이며 사용자 이름과 암호를 관리하지 않고도 사용자가 원활하게 인증될 수 있으므로 권장됩니다.

### &quot;Salesforce만&quot;을 선택하면 인스턴스에 새 사용자가 계정을 어떻게 활성화합니까? {#activate-when-salesforce-only-is-selected}

를 클릭하면 **시작하기** 초대 이메일의 버튼에 새 사용자가 계정 활성화 화면으로 전송됩니다. 이 화면에서 Salesforce 인스턴스를 연결하여 Sales Insight Actions 계정을 활성화해야 합니다.

![](assets/login-management-settings-4.png)

### &quot;Salesforce만&quot;을 선택하면 사용자가 인증할 수 있는 인증 방법은 무엇입니까? {#what-authentication-methods}

로그인 화면으로 이동하면 사용자가 먼저 이메일 주소를 입력합니다. 그런 다음 Salesforce One Click 로그인 단추를 클릭합니다. 여기서 로그인한 Salesforce 계정을 사용하여 인증할 수 있습니다.

>[!NOTE]
>
>로그인 화면으로 직접 이동하는 사용자에게만 해당됩니다. Salesforce에서 작업에 액세스하는 사용자는 [자동 로그인](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md).

![](assets/login-management-settings-5.png)

### 사용자가 Salesforce에서 작업 기능에 액세스하고 &quot;Salesforce만&quot;을 선택하면 작업에 대한 사용자 인증이 어떻게 처리됩니까? {#how-is-user-authentication-handled}

사용자가 작업 중 하나(호출, 이메일, 캠페인, 작업, 캠페인 목록 등)를 클릭하면, Adobe에서는 SFDC 인증을 사용하여 자동으로 해당 Sales Insight Actions 계정에 로그인합니다. 이 인증을 호출합니다 [자동 로그인](/help/marketo/product-docs/marketo-sales-insight/actions/admin/auto-login-from-salesforce.md).

## 모든 로그인 방법 FAQ {#all-login-methods-faq}

### &quot;모든 로그인 방법&quot;을 선택한 경우 내 인스턴스에 새 사용자가 계정을 어떻게 활성화합니까? {#activate-when-all-login-methods-is-selected}

새 사용자가 인스턴스에 초대되면 계정 활성화 이메일을 받게 됩니다. &quot;시작&quot;이라는 버튼을 클릭하면 암호를 만들고 확인하는 메시지가 표시되는 페이지로 이동합니다. 계정이 만들어지면 해당 계정이 활성화되고 온보딩 워크플로우를 통해 전달됩니다.

![](assets/login-management-settings-6.png)

### &quot;모든 로그인 방법&quot;을 선택한 경우 내 인스턴스의 사용자가 로그인할 수 있는 것은 무엇입니까? {#what-are-users-allowed-to-log-in-with-all-login}

로그인 페이지를 사용할 때 사용자는 먼저 이메일 주소를 입력합니다. 그러면 인증을 받을 모든 로그인 옵션(사용자 이름/암호, SFDC, Gmail, SSO)을 제공하는 페이지로 전송됩니다.
