---
unique-page-id: 10095429
description: Dynamics 유효성 검사 동기화 문제 수정 - Marketo 문서 - 제품 설명서
title: Dynamics 유효성 검사 동기화 문제 해결
exl-id: 1a300249-65b7-49b1-bf50-82236916298f
source-git-commit: b4fafa28d9a38504a29c25700496d8376c4fe47b
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 0%

---

# Dynamics 유효성 검사 동기화 문제 해결 {#fix-dynamics-validation-sync-issues}

## 동기화 도구 결과 유효성 검사 {#validate-sync-tool-results}

Dynamics 유효성 검사 동기화를 실행하면 보고서가 생성됩니다. 만약 ![x](assets/delete.png) 한 단계 옆에서 문제를 식별하고 수정하려면 아래 옵션을 참조하십시오. 그런 다음 결과가 녹색 확인 표시만 표시될 때까지 동기화 유효성 검사 단계를 다시 실행합니다.

![](assets/image2015-9-22-15-3a58-3a12.png)

## URL이 유효합니다. {#url-is-valid}

만약 ![x](assets/delete.png) 여기에서 URL이 올바른지 확인합니다. 개발자 리소스에서 찾은 다음 조직 서비스를 참조하십시오. 여러 가지 이유로 인해 URL이 유효하지 않을 수 있습니다.

1. Dynamics에 로그인합니다. 설정 아이콘을 클릭하고 을 선택합니다 **고급 설정**.

   ![](assets/one.png)

1. 설정 을 클릭하고 을 선택합니다 **사용자 지정**.

   ![](assets/two.png)

1. 클릭 **개발자 리소스**.

   ![](assets/three.png)

1. 조직 서비스 URL은 서비스 끝점에 있습니다.

   ![](assets/four.png)

## 사용자 이름과 암호가 유효합니다. {#username-and-password-are-valid}

만약 ![x](assets/delete.png) 여기에서 Microsoft Dynamics 사용자 이름과 암호가 올바른지 확인합니다.

## 동기화 사용자가 Marketo 동기화 사용자 역할에 할당됩니다 {#sync-user-is-assigned-to-the-marketo-sync-user-role}

만약 ![x](assets/delete.png) 여기에서, 이것은 아래의 두 가지 이유 중 하나일 수 있습니다.

**옵션 1 - Microsoft Dynamics에서 Marketo 동기화 사용자 역할이 선택되어 있는지 확인합니다.**:

1. Dynamics에서 설정 아이콘을 클릭하고 을 선택합니다 **고급 설정**.

   ![](assets/one.png)

1. 클릭 **설정** 을(를) 선택합니다. **보안**.

   ![](assets/six.png)

1. 클릭 **사용자.**

   ![](assets/image2015-9-24-9-3a47-3a25.png)

1. 동기화 사용자에 대한 링크를 클릭합니다.

   ![](assets/seven.png)

1. 클릭 **역할 관리**.

   ![](assets/eight.png)

1. Marketo 동기화 사용자 역할이 선택되어 있는지 확인합니다. 없는 경우 확인하고 를 클릭합니다 **네.**

   ![](assets/image2015-9-24-9-3a59-3a21.png)

**옵션 2 - 승인 확인**:

1. 를 검토합니다. [클라이언트 ID 및 앱 등록에 대한 동의 부여](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md) 앱에 API 호출에 대한 관리자 동의가 있는지 확인합니다.

## Marketo 솔루션이 제대로 설치되어 있습니다. {#marketo-solution-is-properly-installed}

만약 ![x](assets/delete.png) 여기에서 Microsoft Dynamics 로 이동하여 Marketo 설치가 있는지 확인합니다. Microsoft Dynamics 설정 설명서의 1단계를 참조하십시오.

1. Dynamics에서 설정 아이콘을 클릭하고 을 선택합니다 **고급 설정**.

   ![](assets/one.png)

1. 클릭 **설정** 을(를) 선택합니다. **솔루션.**

   ![](assets/eleven.png)

1. 솔루션이 나열되는지 확인합니다.

   ![](assets/twelve.png)

## 솔루션의 모든 단계가 활성화됩니다 {#all-steps-in-the-solution-are-enabled}

만약 ![x](assets/delete.png) 여기에서 기본 단계가 비활성화되지 않았는지 확인합니다. 모든 단계는 설치 시 자동으로 활성화되지만 사용자 지정 중에 비활성화할 수 있습니다.

## 동기화 사용자가 Marketo 솔루션에 할당됩니다 {#sync-user-is-assigned-to-the-marketo-solution}

만약 ![x](assets/delete.png) 여기서는 동기화 사용자가 Microsoft Dynamics의 Marketo 기본 페이지에서 할당되었는지 확인합니다.

1. Dynamics에서 설정 아이콘을 클릭하고 을 선택합니다 **고급 설정**.

   ![](assets/one.png)

1. 클릭 **설정** 을(를) 선택합니다. **Marketo 구성**.

   ![](assets/thirteen.png)

1. 동기화 사용자가 기본값으로 할당되었는지 확인합니다.

   ![](assets/fourteen.png)

## 동기화 사용자가 사용자 이름과 암호를 일치함 {#sync-user-matches-username-and-password}

만약 ![x](assets/delete.png) 여기에서는 Microsoft Dynamics의 Marketo 구성 기본 설정 단계의 Marketo 사용자 필드에 적절한 동기화 사용자를 할당합니다.

>[!MORELIKETHIS]
>
>[Microsoft Dynamics 동기화 유효성 검사](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md)
