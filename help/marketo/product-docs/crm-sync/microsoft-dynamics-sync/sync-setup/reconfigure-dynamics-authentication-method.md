---
description: Dynamics 인증 방법 다시 구성 - Marketo 문서 - 제품 설명서
title: Dynamics 인증 메서드 다시 구성
exl-id: 2bd6a992-3dfd-4e91-bec5-9fb3f7bbb840
source-git-commit: d86a8699838158631f210ea2f7acdfb88061b649
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Dynamics 인증 메서드 다시 구성 {#reconfigure-dynamics-authentication-method}

아래 절차에 따라 Dynamics 인증 방법을 업데이트하십시오.

>[!PREREQUISITES]
>
>다음 문서 중 하나에서 원하는 인증 방법을 사용하여 Microsoft Dynamics 및 active directory(Azure AD/ADFS)에서 응용 프로그램을 설정합니다.
>* [3단계 중 2단계: 서버 간 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md)
>* [4단계 중 2단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md)


1. Marketo에서 **관리**.

   ![](assets/reconfigure-dynamics-authentication-method-1.png)

1. 클릭 **Microsoft Dynamics**, 그런 다음 **동기화 비활성화**.

   ![](assets/reconfigure-dynamics-authentication-method-2.png)

   >[!NOTE]
   >
   >인증 방법을 업데이트하려면 전역 동기화를 일시적으로 비활성화해야 합니다.

1. 을(를) 클릭합니다. **새 인증 메서드 다시 구성** 탭.

   ![](assets/reconfigure-dynamics-authentication-method-3.png)

1. 원하는 새 인증 방법을 선택합니다(이 예에서는 웹 API를 선택합니다.).

   ![](assets/reconfigure-dynamics-authentication-method-4.png)

1. 새 인증 방법에 필요한 자격 증명을 입력하고 **유효성 검사**.

   ![](assets/reconfigure-dynamics-authentication-method-5.png)

   >[!NOTE]
   >
   >* 특정 필드는 선택한 인증 방법에 따라 다르며, 양식은 이전 인증 방법에 따라 자동으로 업데이트됩니다.
   >* 이전에 동기화한 적이 있는 경우, 위의 양식의 데이터가 미리 채워질 수 있습니다. 올바른 값을 확인하려면 모든 자격 증명을 다시 입력하십시오.


1. 모든 기능이 정상이면 동기화 유효성 검사가 모든 녹색 확인 표시를 생성합니다 ![](assets/green-check.png). 메시지를 검토하고 를 클릭합니다. **스위치** 인증 방법을 업데이트하려면

   ![](assets/reconfigure-dynamics-authentication-method-6.png)

   >[!NOTE]
   >
   >만약 ![](assets/red-x.png)로 설정되면 해당 단계에 문제가 발생합니다. 자세한 내용은 [Dynamics 유효성 검사 동기화 문제 해결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md) 문제를 식별하고 수정하기 위해 그런 다음 위의 이미지와 같은 결과가 나타날 때까지 동기화 유효성 검사 단계를 다시 실행합니다.

1. 클릭 **확인** 계속 진행합니다.

   ![](assets/reconfigure-dynamics-authentication-method-7.png)

1. 클릭 **확인** 다시 한 번

1. 클릭 **확인**.

   >[!IMPORTANT]
   >
   >동기화를 다시 활성화해야 합니다!
