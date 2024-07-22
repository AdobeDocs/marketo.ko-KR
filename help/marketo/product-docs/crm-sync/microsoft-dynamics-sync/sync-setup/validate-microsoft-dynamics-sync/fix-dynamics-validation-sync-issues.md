---
unique-page-id: 10095429
description: Dynamics 유효성 검사 동기화 문제 해결 - Marketo 문서 - 제품 설명서
title: Dynamics 유효성 검사 동기화 문제 해결
exl-id: 1a300249-65b7-49b1-bf50-82236916298f
feature: Microsoft Dynamics
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '487'
ht-degree: 0%

---

# Dynamics 유효성 검사 동기화 문제 해결 {#fix-dynamics-validation-sync-issues}

## 동기화 도구 결과 확인 {#validate-sync-tool-results}

Dynamics Validate Sync를 실행하면 보고서가 생성됩니다. 단계 옆에 ![x](assets/delete.png)이(가) 있는 경우 아래 옵션을 참조하여 문제를 식별하고 해결하십시오. 그런 다음 결과가 녹색 확인 표시만 표시될 때까지 동기화 유효성 검사 단계를 다시 실행하십시오.

![](assets/image2015-9-22-15-3a58-3a12.png)

## 유효한 URL {#url-is-valid}

여기에 ![x](assets/delete.png)이(가) 있는 경우 URL이 올바른지 확인하십시오. 여기 개발자 리소스에서 찾은 다음 조직 서비스를 참조하십시오. 여러 가지 이유로 URL이 유효하지 않을 수 있습니다.

1. Dynamics에 로그인합니다. 설정 아이콘을 클릭하고 **고급 설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. [설정]을 클릭하고 **사용자 지정**&#x200B;을 선택합니다.

   ![](assets/two.png)

1. **개발자 리소스**&#x200B;를 클릭합니다.

   ![](assets/three.png)

1. 조직 서비스 URL은 서비스 끝점에서 찾을 수 있습니다.

   ![](assets/four.png)

## 사용자 이름과 암호가 유효합니다. {#username-and-password-are-valid}

여기에 ![x](assets/delete.png)이(가) 있으면 Microsoft Dynamics 자격 증명이 유효한지 확인하십시오. 웹 API S2S 인증의 경우 Marketo의 사용자 이름은 CRM에 있는 애플리케이션 사용자의 [이메일 주소](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user)와 일치해야 합니다. 다른 유형의 경우 동기화 사용자의 사용자 이름과 일치해야 합니다.

## 동기화 사용자가 Marketo 동기화 사용자 역할에 할당됨 {#sync-user-is-assigned-to-the-marketo-sync-user-role}

여기에 ![x](assets/delete.png)이(가) 있는 경우 아래 세 가지 문제 중 하나일 수 있습니다.

**옵션 1 - Microsoft Dynamics에서 Marketo 동기화 사용자 역할이 선택되어 있는지 확인**:

1. Dynamics에서 설정 아이콘을 클릭하고 **고급 설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. **설정**&#x200B;을 클릭하고 **보안**&#x200B;을 선택합니다.

   ![](assets/six.png)

1. **사용자**&#x200B;를 클릭합니다.

   ![](assets/image2015-9-24-9-3a47-3a25.png)

1. 동기화 사용자에 대한 링크를 클릭합니다.

   ![](assets/seven.png)

1. **역할 관리**&#x200B;를 클릭합니다.

   ![](assets/eight.png)

1. Marketo 동기화 사용자 역할이 선택되어 있는지 확인합니다. 그렇지 않은 경우 확인하고 **확인**&#x200B;을 클릭하세요.

   ![](assets/image2015-9-24-9-3a59-3a21.png)

**옵션 2 - 동의 승인 확인**:

1. [클라이언트 ID 및 앱 등록에 대한 동의 부여](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md)를 검토하여 앱에 API 호출에 대한 관리자 동의가 있는지 확인하십시오.

**옵션 3 - 사용자 동기화**:

1. 동기화 사용자가 Marketo 구성에 추가되었는지 확인합니다.

## Marketo 솔루션이 올바르게 설치됨 {#marketo-solution-is-properly-installed}

여기에 ![x](assets/delete.png)이(가) 있는 경우 Microsoft Dynamics로 이동하여 Marketo 설치가 있는지 확인하십시오. Microsoft Dynamics 설정 설명서의 1단계를 참조하십시오.

1. Dynamics에서 설정 아이콘을 클릭하고 **고급 설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. **설정**&#x200B;을 클릭하고 **솔루션을 선택합니다.**

   ![](assets/eleven.png)

1. 솔루션이 나열되는지 확인합니다.

   ![](assets/twelve.png)

## 솔루션의 모든 단계가 활성화됩니다 {#all-steps-in-the-solution-are-enabled}

여기에 ![x](assets/delete.png)이(가) 있는 경우 기본 단계가 비활성화되지 않았는지 확인하십시오. 모든 단계는 설치 시 자동으로 활성화되지만, 사용자 지정 중에 비활성화될 수도 있습니다.

## 동기화 사용자가 Marketo 솔루션에 할당됨 {#sync-user-is-assigned-to-the-marketo-solution}

여기에 ![x](assets/delete.png)이(가) 있는 경우 Microsoft Dynamics의 Marketo 기본 페이지에서 동기화 사용자가 할당되었는지 확인하십시오.

1. Dynamics에서 설정 아이콘을 클릭하고 **고급 설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. **설정**&#x200B;을 클릭하고 **Marketo 구성**&#x200B;을 선택합니다.

   ![](assets/thirteen.png)

1. 동기화 사용자가 기본값으로 할당되었는지 확인합니다.

   ![](assets/fourteen.png)

## 동기화 사용자가 사용자 이름 및 암호와 일치함 {#sync-user-matches-username-and-password}

여기에 ![x](assets/delete.png)이(가) 있는 경우 Microsoft Dynamics의 Marketo 구성 기본 설정 단계에서 Marketo 사용자 필드에 올바른 동기화 사용자를 할당하십시오.

>[!MORELIKETHIS]
>
>[Microsoft Dynamics 동기화 확인](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md)
