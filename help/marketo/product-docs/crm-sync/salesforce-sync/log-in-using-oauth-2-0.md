---
description: OAuth 2.0을 사용하여 로그인 - Marketo 문서 - 제품 설명서
title: OAuth 2.0을 사용하여 로그인
exl-id: 0a70505d-d2b8-4dc9-ad11-decc86588f7f
source-git-commit: 88c4e844f7ce26b12bae8177dd5311813fb4adcb
workflow-type: tm+mt
source-wordcount: '493'
ht-degree: 0%

---

# OAuth 2.0을 사용하여 로그인 {#log-in-using-oauth-2-0}

Salesforce는 OAuth 프로토콜을 사용하여 응용 프로그램 사용자가 로그인 자격 증명을 표시하지 않고 데이터에 안전하게 액세스(OAuth 2.0을 사용하여 응용 프로그램 인증)할 수 있도록 합니다. 다음은 Marketo을 Salesforce와 안전하게 연결하고 동기화하기 위해 수행하는 단계입니다.

>[!IMPORTANT]
>
>OAuth를 사용하여 Marketo 및 Salesforce를 연결하려면 비공개(incognito) 브라우저를 통해 Marketo에 로그인하여 잘못된 사용자 이름과 Salesforce에 연결하지 마십시오.

## 연결된 앱 설정 {#set-up-connected-app}

1. Salesforce의 설정, 플랫폼 도구 내에서 앱, 앱 관리자로 이동한 후 를 클릭합니다 **새로 연결된 앱**.

   ![](assets/setting-up-oauth-2-1.png)

1. 세부 사항을 입력하고 **저장**.

   ![](assets/setting-up-oauth-2-2.png)

1. 을(를) 클릭합니다. **OAuth 설정 활성화** 확인란을 선택합니다. 콜백 URL의 경우 다음을 입력합니다. `https://app.marketo.com/salesforce/getSfdcOAuthTokensRedirect`. 사용 가능한 모든 OAuth 범위를 선택하고 를 클릭합니다 **추가**.

   ![](assets/setting-up-oauth-2-3.png)

1. 클릭 **저장**.

   ![](assets/setting-up-oauth-2-4.png)

1. 클릭 **계속**.

   ![](assets/setting-up-oauth-2-5.png)

1. 소비자 키와 소비자 암호를 복사합니다.

   ![](assets/setting-up-oauth-2-6.png)

>[!NOTE]
>
>나중에 Marketo에서 사용할 수 있도록 소비자 키 및 소비자 암호 정보를 저장합니다.

## Marketo 설정 {#set-up-marketo}

>[!PREREQUISITES]
>
>* Salesforce 동기화 사용자에 대해 API 액세스를 활성화해야 합니다(Salesforce Professional Edition 사용자인 경우 기본적으로 해당 액세스를 사용할 수 없습니다. Salesforce 계정 담당자에게 문의하십시오.).
>* Marketo 동기화 사용자는 Salesforce에서 만들어야 합니다.
>* 기존 고객의 경우 고객의 구독에서 &quot;SFDC 동기화용 OAuth 활성화&quot; 기능이 활성화됩니다.
>* 팝업 차단기가 비활성화되어 있습니다.
>* 연결된 앱이 만들어졌고 소비자 키 및 소비자 암호를 사용할 수 있습니다.


>[!CAUTION]
>
>동기화 사용자가 클릭하기 전에 Marketo에서 필요로 하지 않는 모든 필드를 숨기십시오 **동기화 필드**. 동기화 필드 를 클릭하면 SFDC에서 사용자가 볼 수 있는 모든 필드가 Marketo에 영구적으로 만들어지며 삭제할 수 없습니다.

1. Marketo 관리 섹션에서 **CRM**, 그런 다음 **Salesforce와 동기화**.

   ![](assets/setting-up-oauth-2-7.png)

1. 이전에 기록한 소비자 키 및 소비자 암호 정보를 추가하고 을(를) 클릭하고 **저장**.

   ![](assets/setting-up-oauth-2-8.png)

1. Marketo Salesforce 동기화 페이지에서 **Salesforce로 로그인** 버튼을 클릭합니다.

   ![](assets/setting-up-oauth-2-9.png)

   >[!CAUTION]
   >
   >Salesforce로 로그인 단추가 아닌 사용자 이름/암호/토큰 필드가 표시되는 경우 Marketo 구독이 기본 인증에 활성화됩니다. 자세한 내용은 [기본 인증을 사용하여 Marketo 설정](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md). 자격 증명 집합을 사용하여 동기화가 시작되면 Salesforce 자격 증명 또는 구독을 전환하지 않습니다. Oauth 2.0을 사용하려면 Adobe 계정 팀(계정 관리자)에 문의하십시오.

1. salesforce 로그인 페이지가 표시되는 팝업이 나타납니다. 키를 &quot;Marketo 동기화 사용자&quot; 자격 증명에 입력하고 로그인합니다.

   ![](assets/setting-up-oauth-2-10.png)

1. 전자 메일(Salesforce에서 전송)을 통해 받은 확인 코드를 입력하고 를 클릭합니다. **확인**.

   ![](assets/setting-up-oauth-2-11.png)

1. 확인을 성공하면 액세스 페이지가 액세스 요청을 표시합니다. 클릭 **허용**.

   ![](assets/setting-up-oauth-2-12.png)

1. 몇 분 후에 Marketo에 팝업이 나타납니다. 클릭 **자격 증명 확인**.

   ![](assets/setting-up-oauth-2-13.png)

1. 필드 동기화가 완료되면 **Salesforce 동기화 시작**.

   ![](assets/setting-up-oauth-2-14.png)

1. 클릭 **동기화 시작**.

   ![](assets/setting-up-oauth-2-15.png)

Marketo과 Salesforce 간의 동기화가 현재 진행 중입니다.

![](assets/setting-up-oauth-2-16.png)

>[!MORELIKETHIS]
>
>* [3단계 중 1단계: Salesforce에 Marketo 필드 추가(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [3단계 중 2단계: Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [Salesforce AppExchange에 Marketo Sales Insight Package 설치](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)
>* [Salesforce Enterprise/Unlimited에서 Marketo Sales Insight 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)

