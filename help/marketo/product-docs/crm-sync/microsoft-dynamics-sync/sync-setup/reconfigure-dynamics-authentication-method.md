---
description: Dynamics 인증 방법 재구성 - Marketo 문서 - 제품 설명서
title: Dynamics 인증 방법 다시 구성
exl-id: 2bd6a992-3dfd-4e91-bec5-9fb3f7bbb840
feature: Microsoft Dynamics
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 0%

---

# Dynamics 인증 방법 다시 구성 {#reconfigure-dynamics-authentication-method}

아래 단계에 따라 Dynamics 인증 방법을 업데이트하십시오.

>[!PREREQUISITES]
>
>다음 문서 중 하나에서 원하는 인증 방법을 사용하여 Microsoft Dynamics 및 Active Directory(Azure AD/ADFS)에서 애플리케이션을 설정합니다.
>
>* [2단계/3단계: 서버 간 연결을 통해 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md){target="_blank"}
>* [2단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}

1. Marketo Engage에서 **[!UICONTROL 관리자]**.

   ![](assets/reconfigure-dynamics-authentication-method-1.png)

1. 클릭 **[!DNL Microsoft Dynamics]**, 그런 다음 **[!UICONTROL 동기화 비활성화]**.

   ![](assets/reconfigure-dynamics-authentication-method-2.png)

   >[!NOTE]
   >
   >인증 방법을 업데이트하려면 전역 동기화를 일시적으로 비활성화해야 합니다.

1. 다음을 클릭합니다. **[!UICONTROL 새 인증 방법 재구성]** 탭.

   ![](assets/reconfigure-dynamics-authentication-method-3.png)

1. 원하는 새 인증 방법을 선택합니다(이 예에서는 웹 API를 선택함).

   ![](assets/reconfigure-dynamics-authentication-method-4.png)

1. 새 인증 방법에 필요한 자격 증명을 입력하고 **[!UICONTROL 유효성 검사]**.

   ![](assets/reconfigure-dynamics-authentication-method-5.png)

   >[!NOTE]
   >
   >* 특정 필드는 선택한 인증 방법에 따라 다르며 이전 인증 방법에 따라 양식이 자동으로 업데이트됩니다.
   >* 이전에 동기화한 경우 위의 양식의 데이터가 미리 채워질 수 있습니다. 모든 자격 증명을 다시 입력하여 정확한 값을 확인하십시오.

1. 모든 것이 정상인 경우 동기화 유효성 검사 가 모든 녹색 확인 표시를 생성합니다 ![](assets/green-check.png). 메시지를 검토하고 **[!UICONTROL 전환]** 을 클릭하여 인증 방법을 업데이트합니다.

   ![](assets/reconfigure-dynamics-authentication-method-6.png)

   >[!NOTE]
   >
   >다음 항목이 표시되면 ![](assets/red-x.png), 해당 단계에 문제가 있습니다. 다음을 참조하십시오 [Dynamics 유효성 검사 동기화 문제 해결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md){target="_blank"} 문제를 식별하고 해결하기 위해. 그런 다음 결과가 위의 이미지와 같이 나타날 때까지 동기화 유효성 검사 단계를 다시 실행하십시오.

1. 클릭 **[!UICONTROL 확인]** 계속합니다.

   ![](assets/reconfigure-dynamics-authentication-method-7.png)

1. 클릭 **[!UICONTROL 확인]** 다시.

   ![](assets/reconfigure-dynamics-authentication-method-8.png)

1. 클릭 **[!UICONTROL 확인]**.

   >[!IMPORTANT]
   >
   >시스템에서 새 인증 모드를 수락하는 데 15분이 소요됩니다. 동기화를 다시 활성화하기 전에 전환 시점부터 15분 정도 기다리십시오.
