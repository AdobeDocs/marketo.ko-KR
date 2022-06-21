---
description: 글로벌 양식 유효성 검사 규칙 - Marketo 문서 - 제품 설명서
title: 글로벌 양식 유효성 검사 규칙
exl-id: a44db893-00b5-40d2-8be3-41d52b2fd7b5
source-git-commit: c91fa08bcb833a4c8a65055fd2471d7bc03a4e71
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 0%

---

# 글로벌 양식 유효성 검사 규칙 {#global-form-validation-rules}

이 기능을 사용하면 특정 도메인이 Marketo Engage 양식에 전송되지 않도록 차단할 수 있습니다.

## 액세스를 활성화하는 방법 {#how-to-enable-access}

이 기능을 활용하려면 먼저 원하는 역할에 따라 해당 권한을 활성화해야 합니다.

1. Marketo에서 **관리**.

   ![](assets/global-form-validation-rules-1.png)

1. 클릭 **사용자 및 역할**.

   ![](assets/global-form-validation-rules-2.png)

1. 을(를) 클릭합니다. **역할** 탭.

   ![](assets/global-form-validation-rules-3.png)

1. 권한을 부여할 역할을 두 번 클릭합니다.

   ![](assets/global-form-validation-rules-4.png)

1. 을(를) 클릭합니다. **+** 액세스 관리자 옆에 로그인합니다.

   ![](assets/global-form-validation-rules-5.png)

1. 아래로 스크롤하여 선택합니다. **양식 검증 규칙 액세스** 을(를) 클릭합니다. **저장**.

   ![](assets/global-form-validation-rules-6.png)

## 새 양식 유효성 검사 규칙 만들기 {#create-new-form-validation-rule}

>[!IMPORTANT]
>
>이러한 규칙은 Marketo Engage 구독의 모든 양식에 적용됩니다.

1. Marketo에서 **관리**.

   ![](assets/global-form-validation-rules-7.png)

1. 클릭 **전역 양식 유효성 검사 규칙**.

   ![](assets/global-form-validation-rules-8.png)

1. 클릭 **새 양식 유효성 검사 규칙**.

   ![](assets/global-form-validation-rules-9.png)

   >[!NOTE]
   >
   >양식 검증 규칙 작업 드롭다운을 사용하면 기존 규칙을 삭제하거나 편집할 수 있습니다.

1. 규칙 이름을 지정하고, 선택적 설명을 제공하고, 양식 방문자에게 표시할 오류 메시지를 입력합니다. 규칙 상자에 차단한 도메인을 입력하고 **규칙 활성화**&#x200B;를 클릭하고 **만들기**.

   ![](assets/global-form-validation-rules-10.png)

>[!NOTE]
>
>Marketo Engage에차단 목록에 추가하다는 사전 로드된 &quot;소비자 이메일 도메인&quot; 규칙을 사용할 때 차단되는 무료 소비자 이메일 차단 목록에 추가하다 도메인의 정의된 도메인이 있습니다. [여기에서 해당 목록 보기](/help/marketo/product-docs/administration/settings/assets/freemaildomains.csv).

## 양식당 액세스를 비활성화하는 방법{#how-to-disable-access-per-form}

규칙이 활성화되면 모든 양식에 적용됩니다. 그러나 특정 요구 사항이 있는 양식이 있고 어떤 것도 거부되지 않으려면 양식의 설정에서 전역 양식 유효성 검사 규칙을 비활성화할 수 있습니다.

1. 원하는 양식에서 을 클릭합니다 **양식 설정**, 그런 다음 **설정**.

   ![](assets/global-form-validation-rules-11.png)

1. 글로벌 양식 검증 규칙 드롭다운을 클릭하고 을 선택합니다 **비활성화됨**.

   ![](assets/global-form-validation-rules-12.png)

양식을 승인하고 게시하면 글로벌 양식 유효성 검사 규칙을 무시합니다.
