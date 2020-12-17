---
unique-page-id: 10095429
description: Dynamics 유효성 검사 동기화 문제 수정 - Marketing To Docs - 제품 설명서
title: Dynamics 유효성 검사 동기화 문제 수정
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---


# Dynamics 유효성 검사 동기화 문제 수정 {#fix-dynamics-validation-sync-issues}

## 동기화 도구 결과 유효성 확인 {#validate-sync-tool-results}

Dynamics 유효성 검사 동기화를 실행하면 이 보고서가 생성됩니다. 단계 옆에 ![delete](assets/delete.png)이 있는 경우 아래 항목을 참조하여 문제를 식별하고 해결하십시오. 그런 다음 확인 표시 외에는 아무 것도 표시되지 않을 때까지 동기화 유효성 검사 단계를 다시 실행합니다.

![](assets/image2015-9-22-15-3a58-3a12.png)

## URL이 유효한 {#url-is-valid}입니다.

여기에 ![delete](assets/delete.png)가 있는 경우 URL이 유효한지 확인합니다. 개발자 리소스에서 이 리소스를 찾아 조직 서비스를 살펴보십시오. 여러 가지 이유로 URL이 유효하지 않을 수 있습니다.

1. Dynamics에 로그인합니다. 설정 아이콘을 클릭하고 **고급 설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. 설정을 클릭하고 **사용자 지정**&#x200B;을 선택합니다.

   ![](assets/two.png)

1. **개발자 리소스**&#x200B;를 클릭합니다.

   ![](assets/three.png)

1. 조직 서비스 URL은 서비스 끝점에서 찾을 수 있습니다.

   ![](assets/four.png)

## 사용자 이름 및 암호는 유효한 {#username-and-password-are-valid}

여기에 ![—](assets/delete.png)이 있는 경우 Microsoft Dynamics 사용자 이름과 암호가 올바른지 확인하십시오.

## 동기화 사용자가 Marketing To Sync 사용자 역할 {#sync-user-is-assigned-to-the-marketo-sync-user-role}에 할당되었습니다.

여기에 ![—](assets/delete.png)이 있는 경우 Marketing to Sync 사용자 역할이 Microsoft Dynamics에서 선택되었는지 확인해야 합니다. Microsoft Dynamics 설치 설명서의 2단계를 참조하십시오.

1. Dynamics에서 설정 아이콘을 클릭하고 **고급 설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. **설정**&#x200B;을 클릭하고 **보안**&#x200B;을 선택합니다.

   ![](assets/six.png)

1. **사용자를 클릭합니다.**

   ![](assets/image2015-9-24-9-3a47-3a25.png)

1. 동기화 사용자의 링크를 클릭합니다.

   ![](assets/seven.png)

1. **역할 관리**&#x200B;를 클릭합니다.

   ![](assets/eight.png)

1. Marketing To Sync 사용자 역할이 선택되어 있는지 확인합니다. 없는 경우 확인하고 **확인**&#x200B;을 클릭합니다.

   ![](assets/image2015-9-24-9-3a59-3a21.png)

## Marketing Solution이 {#marketo-solution-is-properly-installed}에 올바르게 설치됨

여기에 ![—](assets/delete.png)가 있는 경우 Microsoft Dynamics로 이동하여 Marketing To 설치가 있는지 확인합니다. Microsoft Dynamics 설정 설명서의 1단계를 참조하십시오.

1. Dynamics에서 설정 아이콘을 클릭하고 **고급 설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. **설정 **을 클릭하고 **솔루션을 선택합니다.**

   ![](assets/eleven.png)

1. 솔루션이 나열되었는지 확인합니다.

   ![](assets/twelve.png)

## 솔루션의 모든 단계가 {#all-steps-in-the-solution-are-enabled}으로 활성화됩니다.

여기에 ![—](assets/delete.png)이 있는 경우 기본 단계가 비활성화되지 않았는지 확인합니다. 모든 단계는 설치 시 자동으로 활성화되지만 사용자 정의 시 비활성화할 수 있습니다.

## 동기화 사용자가 Marketing To 솔루션 {#sync-user-is-assigned-to-the-marketo-solution}에 할당되었습니다.

여기에 ![—](assets/delete.png)이 있는 경우 동기화 사용자가 Microsoft Dynamics의 Marketing to 기본 페이지에 할당되었는지 확인하십시오.

1. Dynamics에서 설정 아이콘을 클릭하고 **고급 설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. **설정 **을 클릭하고 **마케팅 구성**&#x200B;을 선택합니다.

   ![](assets/thirteen.png)

1. 동기화 사용자가 기본값으로 지정되었는지 확인합니다.

   ![](assets/fourteen.png)

## 동기화 사용자가 사용자 이름 및 암호 {#sync-user-matches-username-and-password}과(와) 일치합니다.

여기에 ![—](assets/delete.png)가 있는 경우 Microsoft Dynamics의 Marketing to Config Default 설정 단계의 Marketing To 사용자 필드에 적절한 동기화 사용자를 할당해야 합니다.

>[!MORELIKETHIS]
>
>[Microsoft Dynamics 동기화 유효성 검사](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md)

