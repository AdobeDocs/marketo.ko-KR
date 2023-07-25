---
unique-page-id: 12981050
description: 판매 템플릿 잠금 - Marketo 문서 - 제품 설명서
title: 판매 템플릿 잠금
exl-id: 005dde5d-ed60-444b-b7a3-b91be72a0151
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 0%

---

# 판매 템플릿 잠금 {#lock-sales-template}

CRM 사용자가 판매 템플릿을 편집할 수 없도록 하기 위해 관리자는 템플릿을 잠글 수 있는 기능을 활성화하여 사용자가 이메일 편집기에서 개별적으로 템플릿을 잠글 수 있습니다.

>[!CAUTION]
>
>이 기능은 Salesforce에서만 작동하며 Microsoft Dynamics 또는 다른 CRM과 호환되지 않습니다. 편집기가 Marketo에 의해 제어되지 않으므로 Outlook 또는 Gmail 플러그인에서 액세스된 템플릿은 잠기지 않습니다.

## 템플릿 잠금 활성화 {#enable-lock-template}

>[!NOTE]
>
>**관리자 권한 필요**

1. 다음으로 이동 **관리자**&#x200B;을 클릭한 다음 을 클릭합니다 **Sales Insight**.

   ![](assets/1.png)

1. 아래 **설정**, 클릭 **편집**.

   ![](assets/2.png)

1. 확인 **템플릿 잠금 기능 활성화**. 클릭 **저장**.

   ![](assets/image2017-10-9-8-3a19-3a45.png)

>[!NOTE]
>
>기본적으로 이 확인란이 선택되어 있으며 템플릿 잠금 기능이 활성화되어 있습니다. 선택을 취소하면 이메일 편집기에서 템플릿 잠금 기능이 비활성화됩니다.

>[!NOTE]
>
>책임자로 이 설정을 변경하면 **아님** 기존 템플릿에 소급하여 영향을 미칩니다. 즉, 자동으로 잠기지 않습니다.

## 이메일 편집기에서 템플릿 잠금 {#lock-template-in-the-email-editor}

1. 잠그려는 이메일을 선택한 다음 **초안 편집**.

   ![](assets/5.png)

1. 이메일 편집기에서 **이메일 설정**.

   ![](assets/6.png)

1. 확인 **Marketo Sales Insight에 게시** 아직 확인하지 않았다면 가능합니다. 이제 선택을 취소할 수 있습니다. **CRM 사용자가 전자 메일을 편집하도록 허용** 템플릿을 잠그려면 다음을 수행하십시오. 클릭 **저장**.

   ![](assets/7.png)

   >[!NOTE]
   >
   >기본적으로 이 확인란이 선택되어 있으며 CRM 사용자가 이메일을 편집할 수 있습니다.
