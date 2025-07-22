---
description: 다시 구성 [!DNL Dynamics] 인증 방법 - Marketo 문서 - 제품 설명서
title: ' [!DNL Dynamics] 인증 방법 다시 구성'
exl-id: 2bd6a992-3dfd-4e91-bec5-9fb3f7bbb840
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '253'
ht-degree: 0%

---

# Dynamics 인증 방법 다시 구성 {#reconfigure-dynamics-authentication-method}

[!DNL Dynamics] 인증 방법을 업데이트하려면 아래 단계를 따르십시오.

>[!PREREQUISITES]
>
>다음 문서 중 하나에서 원하는 인증 방법을 사용하여 [!DNL Microsoft Dynamics] 및 Active Directory(Azure AD/ADFS)에서 응용 프로그램을 설정합니다.
>
>* [2단계/3단계: 서버 간 연결을 통해 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md){target="_blank"}
>* [2단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/reconfigure-dynamics-authentication-method-1.png)

1. **Microsoft Dynamics**&#x200B;을 클릭한 다음 **[!UICONTROL Disable Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/reconfigure-dynamics-authentication-method-2.png)

   >[!NOTE]
   >
   >인증 방법을 업데이트하려면 전역 동기화를 일시적으로 비활성화해야 합니다.

1. **[!UICONTROL Reconfigure New Auth Method]** 탭을 클릭합니다.

   ![](assets/reconfigure-dynamics-authentication-method-3.png)

1. 원하는 새 인증 방법을 선택합니다(이 예에서는 웹 API를 선택함).

   ![](assets/reconfigure-dynamics-authentication-method-4.png)

1. 새 인증 방법에 필요한 자격 증명을 입력하고 **[!UICONTROL Validate]**&#x200B;을(를) 클릭합니다.

   ![](assets/reconfigure-dynamics-authentication-method-5.png)

   >[!NOTE]
   >
   >* 특정 필드는 선택한 인증 방법에 따라 다르며 이전 인증 방법에 따라 양식이 자동으로 업데이트됩니다.
   >* 이전에 동기화한 경우 위의 양식의 데이터가 미리 채워질 수 있습니다. 모든 자격 증명을 다시 입력하여 정확한 값을 확인하십시오.

1. 모든 항목이 정상이면 동기화 유효성 검사 기능이 모든 녹색 확인 표시 ![](assets/green-check.png)을(를) 생성합니다. 메시지를 검토하고 **[!UICONTROL Switch]**&#x200B;을(를) 클릭하여 인증 방법을 업데이트합니다.

   ![](assets/reconfigure-dynamics-authentication-method-6.png)

   >[!NOTE]
   >
   >![](assets/red-x.png)이(가) 표시되면 해당 단계에 문제가 있습니다. 문제를 식별하고 해결하려면 [해결 [!DNL Dynamics] 유효성 검사 동기화 문제](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md)를 참조하십시오. 그런 다음 결과가 위의 이미지와 같이 나타날 때까지 동기화 유효성 검사 단계를 다시 실행하십시오.

1. 계속하려면 **[!UICONTROL Confirm]**&#x200B;을(를) 클릭하십시오.

   ![](assets/reconfigure-dynamics-authentication-method-7.png)

1. **[!UICONTROL Confirm]**&#x200B;을(를) 다시 클릭합니다.

   ![](assets/reconfigure-dynamics-authentication-method-8.png)

1. **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   >[!IMPORTANT]
   >
   >시스템에서 새 인증 모드를 수락하는 데 15분이 소요됩니다. 동기화를 다시 활성화하기 전에 전환 시점부터 15분 정도 기다리십시오.
