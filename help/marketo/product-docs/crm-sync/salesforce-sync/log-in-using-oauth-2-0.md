---
description: OAuth 2.0을 사용하여 로그인 - Marketo 문서 - 제품 설명서
title: OAuth 2.0을 사용하여 로그인
exl-id: 0a70505d-d2b8-4dc9-ad11-decc86588f7f
translation-type: tm+mt
source-git-commit: d81a4a3caa12c5ec642afadf9328b3825bde6fed
workflow-type: tm+mt
source-wordcount: '465'
ht-degree: 0%

---

# OAuth 2.0을 사용하여 로그인 {#log-in-using-oauth-2-0}

Salesforce는 OAuth 프로토콜을 사용하여 애플리케이션 사용자가 로그인 자격 증명을 표시하지 않고 안전하게 데이터에 액세스(OAuth 2.0을 사용하여 응용 프로그램 인증) 할 수 있도록 합니다. 다음은 Marketo을 Salesforce와 안전하게 연결하고 동기화하기 위해 수행하는 단계입니다.

## 연결된 앱 설정 {#set-up-connected-app}

1. Salesforce의 설정 아래의 플랫폼 도구 내에서 Apps, App Manager로 이동한 다음 **새로 연결된 앱**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-1.png)

1. 세부 사항을 채우고 **저장**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-2.png)

1. **OAuth 설정 활성화** 확인란을 클릭합니다. 콜백 URL에 `https://app.marketo.com/salesforce/getSfdcOAuthTokensRedirect`을(를) 입력합니다. 사용 가능한 모든 OAuth 범위를 선택하고 **추가**&#x200B;를 클릭합니다.

   ![](assets/setting-up-oauth-2-3.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-4.png)

1. **계속**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-5.png)

1. 소비자 키와 소비자 비밀 복사.

   ![](assets/setting-up-oauth-2-6.png)

>[!NOTE]
>
>나중에 Marketo에서 사용할 수 있도록 소비자 키 및 소비자 비밀 정보를 저장합니다.

## Marketo {#set-up-marketo} 설정

>[!PREREQUISITES]
>
>* API 액세스는 Salesforce 동기화 사용자에 대해 활성화되어 있어야 합니다(Salesforce Professional Edition 사용자이고 기본적으로 액세스할 수 없는 경우 Salesforce 계정 담당자에게 문의하십시오.).
>* Marketo Sync 사용자는 Salesforce에서 만들어야 합니다.
>* 기존 고객의 경우 고객의 구독에서 &quot;SFDC 동기화용 OAuth 활성화&quot;에 대한 기능이 활성화됩니다.
>* 팝업 차단기가 비활성화됩니다.
>* 연결된 앱이 만들어지고 소비자 키와 소비자 비밀이 사용 가능합니다.


>[!CAUTION]
>
>**필드 동기화**&#x200B;를 클릭하기 전에 Marketo에서 필요하지 않은 모든 필드를 동기화 사용자로부터 숨겨야 합니다. [필드 동기화]를 클릭하면 SFDC에서 사용자가 볼 수 있는 모든 필드가 Marketo에서 영구적으로 만들어지며 삭제할 수 없습니다.

1. Marketo 관리 섹션에서 **CRM**&#x200B;을 클릭한 다음 **Salesforce와 동기화**&#x200B;를 클릭합니다.

   ![](assets/setting-up-oauth-2-7.png)

1. 이전에 기록한 소비자 키 및 소비자 암호 정보를 추가하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-8.png)

1. Marketo Salesforce 동기화 페이지에서 **Salesforce와 로그인** 단추를 클릭합니다.

   ![](assets/setting-up-oauth-2-9.png)

   >[!CAUTION]
   >
   >&quot;Salesforce로 로그인&quot; 단추가 아닌 사용자 이름/암호/토큰 필드가 표시되는 경우 Marketo 구독이 기본 인증을 사용하도록 설정됩니다. [기본 인증을 사용하여 Marketo 설정](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)을 참조하십시오. 자격 증명 집합을 사용하여 동기화가 시작되면 Salesforce 자격 증명 또는 구독의 전환이 없습니다. Oauth 2.0을 사용하려면 고객 성공 관리자에게 문의하십시오.

1. salesforce 로그인 페이지가 표시되는 팝업이 표시됩니다. &quot;Marketo Sync 사용자&quot; 자격 증명을 입력하고 로그인합니다.

   ![](assets/setting-up-oauth-2-10.png)

1. 전자 메일(Salesforce에서 전송)을 통해 받은 확인 코드를 입력하고 **확인**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-11.png)

1. 확인 작업이 성공하면 액세스 페이지가 액세스 요청을 표시합니다. **허용**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-12.png)

1. 몇 분 후에 Marketo에 팝업이 표시됩니다. **자격 증명 확인**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-13.png)

1. 필드 동기화가 완료되면 **Salesforce 동기화 시작**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-14.png)

1. **동기화 시작**&#x200B;을 클릭합니다.

   ![](assets/setting-up-oauth-2-15.png)

Marketo과 Salesforce 간의 동기화가 진행 중입니다.

![](assets/setting-up-oauth-2-16.png)

>[!MORELIKETHIS]
>
>* [3단계 중 1단계:Salesforce에 Marketo 필드 추가(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [3단계 중 2단계:Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [Salesforce AppExchange에 Marketo Sales Insight 패키지 설치](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)
>* [Salesforce Enterprise에서 Marketo Sales Insight 구성/제한 없음](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)

