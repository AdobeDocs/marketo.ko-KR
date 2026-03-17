---
unique-page-id: 37355768
description: AEM 에셋을 Marketo Design Studio로 가져오는 방법을 알아봅니다. 자산 선택기를 사용하여 Adobe Experience Manager에서 자산에 액세스하고 자산을 가져옵니다.
title: Adobe Experience Manager를 사용하여 자산 가져오기
exl-id: 56ccf38f-3c99-4018-9989-719854e37a20
source-git-commit: 3efcb529cd3e35027f35e51dfd91f95e94af9d61
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 6%

---

# Adobe Experience Manager를 사용하여 자산 가져오기 {#importing-assets-with-adobe-experience-manager}

Marketo 고객은 에셋 선택기를 사용하여 AEM 에셋에 액세스하고, 선택하고, Marketo의 Design Studio로 가져올 수 있습니다. **관리자 권한이 필요합니다**.

>[!AVAILABILITY]
>
>모든 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

>[!PREREQUISITES]
>
>[AEM 구성](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/configuring-adobe-experience-manager-integration.md)을 이미 수행했는지 확인하십시오.

>[!IMPORTANT]
>
>현재 이 기능은 Firefox에서만 완전히 지원됩니다. 이 기능은 Safari에서 지원되지 않으며, SameSite 쿠키 설정에 따라 최신 버전의 Chrome에서 작동하지 않을 수 있습니다.

1. **[!UICONTROL Design Studio]**&#x200B;를 클릭합니다.

   ![](assets/importing-assets-with-adobe-experience-manager-1.png)

1. 새로 만들기 드롭다운을 클릭하고 **[!UICONTROL Import from Adobe Experience Manager]**&#x200B;을(를) 선택합니다.

   ![](assets/importing-assets-with-adobe-experience-manager-2.png)

1. 이미지를 저장할 폴더를 선택합니다.

   ![](assets/importing-assets-with-adobe-experience-manager-3.png)

1. Adobe Experience Manager에 로그인합니다(아직 로그인하지 않은 경우).

   ![](assets/importing-assets-with-adobe-experience-manager-4.png)

1. 폴더를 선택합니다. 그런 다음 썸네일을 클릭하여 원하는 이미지를 선택합니다(최대 10개까지 선택할 수 있음). 완료되면 **[!UICONTROL Select]**&#x200B;를 클릭합니다.

   ![](assets/importing-assets-with-adobe-experience-manager-5.png)

   >[!NOTE]
   >
   >이미지 크기는 100MB를 초과할 수 없습니다.

1. 프로세스를 완료하려면 **[!UICONTROL Import]**&#x200B;을(를) 클릭하십시오.

   ![](assets/importing-assets-with-adobe-experience-manager-6.png)

   다 됐습니다! Design Studio로 돌아가려면 **[!UICONTROL Close]**&#x200B;을(를) 클릭하십시오.

   ![](assets/importing-assets-with-adobe-experience-manager-7.png)

## 참고할 사항 {#things-to-note}

* Marketo은 현재 Adobe Experience Manager 버전 6.4 및 6.5를 지원합니다.

* 인스턴스의 모든 사용자가 가져온 이미지를 보거나 액세스할 수 있습니다.

* 이미지는 자동으로 업데이트되지 않습니다. Marketo Design Studio로 가져온 이미지가 AEM에서 업데이트된 경우 수동으로 Marketo으로 다시 가져와야 합니다.
