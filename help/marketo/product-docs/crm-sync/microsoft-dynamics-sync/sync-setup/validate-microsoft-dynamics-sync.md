---
unique-page-id: 8783322
description: 유효성 검사 [!DNL Microsoft Dynamics] 동기화 - Marketo 문서 - 제품 설명서
title: ' [!DNL Microsoft Dynamics] 동기화 확인'
exl-id: 00297a8d-36c3-42f6-a9b8-4a8dd7c1f30d
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] 동기화 유효성 검사 {#validate-microsoft-dynamics-sync}

>[!CAUTION]
>
>[!DNL Dynamics] 동기화에 MFA(Multi-Factor Authentication)를 사용하도록 설정한 경우 [!DNL Dynamics]이(가) Marketo과 올바르게 동기화되도록 비활성화해야 합니다. 자세한 내용은 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하십시오.

## Marketo에서 동기화 유효성 검사 실행 {#run-validate-sync-in-marketo}

동기화 유효성 검사 도구를 실행하여 Marketo과 [!DNL Microsoft Dynamics] 동기화가 올바르게 설정되었는지 확인한 후 마지막으로 연결하는 것이 매우 중요합니다. 이 프로세스는 문제가 있는 위치를 정확히 찾아내는 7가지 설정 단계의 체크리스트를 생성합니다. 이러한 작업이 올바르게 수행되었는지 확인하는 것은 나중에 많은 시간을 절약할 수 있습니다.

1. **[!UICONTROL Admin]** 탭을 클릭한 다음 통합 영역에서 **[!DNL Microsoft Dynamics]** 링크를 클릭합니다.

   ![](assets/image2015-9-28-16-3a7-3a51.png)

1. **[!DNL Microsoft]**&#x200B;를 선택합니다.

   ![](assets/image2015-9-28-16-3a10-3a47.png)

1. **[!UICONTROL Validate Sync Setup]** 탭을 클릭합니다.

   ![](assets/image2015-9-28-16-3a11-3a45.png)

1. 사용자 이름, 암호 및 URL을 입력합니다(클라이언트 ID 및 클라이언트 암호는 선택 사항). 완료되면 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >이전에 동기화한 경우 왼쪽 트리의 **CRM**&#x200B;에서 **[!DNL Microsoft Dynamics]**&#x200B;을(를) 읽고 위 양식의 데이터를 미리 채울 수 있습니다.

1. 모든 것이 정상인 경우 동기화 유효성 검사가 녹색 확인 표시 ![—](assets/check.png)로 가득 찬 검사 목록을 생성합니다.

   ![](assets/image2015-9-22-15-3a58-3a12.png)

1. ![—](assets/delete.png)이(가) 표시되면 해당 단계에 문제가 있는 것입니다. 문제를 식별하고 해결하려면 [해결 [!DNL Dynamics] 유효성 검사 동기화 문제](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md)를 참조하십시오. 그런 다음 결과가 위의 이미지와 같이 나타날 때까지 동기화 유효성 검사 단계를 다시 실행하십시오.

   >[!CAUTION]
   >
   >현재 [!DNL Marketo Dynamics] 동기화에 대한 샌드박스 새로 고침을 지원하지 않습니다. [!DNL Dynamics] CRM 샌드박스를 새로 고쳐야 하는 경우 새 Marketo 샌드박스가 필요합니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

>[!MORELIKETHIS]
>
>[해결 [!DNL Dynamics] 유효성 검사 동기화 문제](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md)
