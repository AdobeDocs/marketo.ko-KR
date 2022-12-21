---
unique-page-id: 12981050
description: 영업 템플릿 잠금 - Marketo 문서 - 제품 설명서
title: 영업 템플릿 잠금
exl-id: 005dde5d-ed60-444b-b7a3-b91be72a0151
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 0%

---

# 영업 템플릿 잠금 {#lock-sales-template}

CRM 사용자가 판매 템플릿을 편집할 수 없도록 관리자가 템플릿을 잠글 수 있는 기능을 활성화하면 사용자가 이메일 편집기에서 개별적으로 템플릿을 잠글 수 있습니다.

>[!CAUTION]
>
>이 기능은 Salesforce에서만 작동하며 Microsoft Dynamics 또는 다른 CRM과 호환되지 않습니다. 편집기가 Marketo에서 제어하지 않으므로 Outlook 또는 Gmail 플러그인에서 액세스한 템플릿은 잠기지 않습니다.

## 템플릿 잠금 활성화 {#enable-lock-template}

>[!NOTE]
>
>**관리 권한 필요**

1. 이동 **관리**&#x200B;를 클릭한 다음 **Sales Insight**.

   ![](assets/1.png)

1. 아래 **설정**&#x200B;를 클릭합니다. **편집**.

   ![](assets/2.png)

1. 확인 **템플릿 잠금 기능 사용**. 클릭 **저장**.

   ![](assets/image2017-10-9-8-3a19-3a45.png)

>[!NOTE]
>
>기본적으로 이 상자는 선택되어 있으며 템플릿 잠금 기능이 활성화되어 있습니다. 선택을 취소하면 이메일 편집기에서 템플릿 잠금 기능이 비활성화됩니다.

>[!NOTE]
>
>이 설정을 관리자로 변경 **not** 기존 템플릿에 소급하여 영향 즉, 자동으로 잠기지 않습니다.

## 이메일 편집기에서 템플릿 잠금 {#lock-template-in-the-email-editor}

1. 잠글 이메일을 선택한 다음 **초안 편집**.

   ![](assets/5.png)

1. 이메일 편집기에서 을 클릭합니다. **전자 메일 설정**.

   ![](assets/6.png)

1. 확인 **Marketo Sales Insight에 게시** 아직 확인 안 된 경우 이제 선택을 취소할 수 있습니다 **CRM 사용자가 전자 메일 편집 허용** 템플릿을 잠그려면 다음을 수행하십시오. 클릭 **저장**.

   ![](assets/7.png)

   >[!NOTE]
   >
   >기본적으로 이 상자는 선택되며 CRM 사용자는 이메일을 편집할 수 있습니다.
