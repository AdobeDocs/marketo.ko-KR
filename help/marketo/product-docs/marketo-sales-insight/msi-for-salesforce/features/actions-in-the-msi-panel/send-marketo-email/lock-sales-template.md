---
unique-page-id: 12981050
description: 판매 템플릿 잠금 - Marketo 문서 - 제품 설명서
title: 판매 템플릿 잠금
exl-id: 005dde5d-ed60-444b-b7a3-b91be72a0151
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 1%

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

1. **관리자**(으)로 이동한 다음 **영업 인사이트**&#x200B;를 클릭합니다.

   ![](assets/1.png)

1. **설정**&#x200B;에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/2.png)

1. **템플릿을 잠글 수 있도록 설정**&#x200B;을 확인하세요. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2017-10-9-8-3a19-3a45.png)

>[!NOTE]
>
>기본적으로 이 확인란이 선택되어 있으며 템플릿 잠금 기능이 활성화되어 있습니다. 선택을 취소하면 이메일 편집기에서 템플릿 잠금 기능이 비활성화됩니다.

>[!NOTE]
>
>관리자로 이 설정을 변경하면 기존 템플릿에 소급하여 영향을 주지 **않습니다**. 즉, 자동으로 잠기지 않습니다.

## 이메일 편집기에서 템플릿 잠금 {#lock-template-in-the-email-editor}

1. 잠그려는 전자 메일을 선택한 다음 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/5.png)

1. 전자 메일 편집기에서 **전자 메일 설정**&#x200B;을 클릭합니다.

   ![](assets/6.png)

1. 아직 확인하지 않은 경우 **Publish to Marketo Sales Insight**&#x200B;를 확인하세요. 이제 **CRM 사용자가 전자 메일을 편집할 수 있도록 허용**&#x200B;을 선택 취소하고 템플릿을 잠글 수 있습니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/7.png)

   >[!NOTE]
   >
   >기본적으로 이 확인란이 선택되어 있으며 CRM 사용자가 이메일을 편집할 수 있습니다.
