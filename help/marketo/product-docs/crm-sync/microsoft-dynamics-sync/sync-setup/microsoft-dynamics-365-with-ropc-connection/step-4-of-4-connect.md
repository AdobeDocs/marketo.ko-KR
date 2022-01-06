---
description: 4단계 - Marketo 솔루션을 리소스 소유자 암호 제어 연결과 연결 - Marketo 문서 - 제품 설명서
title: 4단계 중 4단계 - Marketo 솔루션을 리소스 소유자 암호 제어 연결과 연결
exl-id: 71a52a3e-f31e-45ee-8196-d536528e42ca
source-git-commit: 549282b11bcf5fd48d29680f196e4534063b30f6
workflow-type: tm+mt
source-wordcount: '456'
ht-degree: 0%

---

# 4단계 중 4단계: 리소스 소유자 암호 제어 연결과 Marketo 솔루션 연결 {#step-4-of-4-connect-the-marketo-solution-ropc}

이 단계는 동기화의 마지막 단계입니다. 거의 다 왔어!

>[!PREREQUISITES]
>
>* [4단계 중 1단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md)
>* [4단계 중 2단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md)
>* [4단계 중 3단계: MS Dynamics에서 클라이언트 앱 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md)


>[!NOTE]
>
>**관리 권한 필요**

>[!IMPORTANT]
>
>기본 인증에서 OAuth로 업그레이드하는 경우 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support) 추가 매개 변수 업데이트에 대한 도움말을 참조하십시오. 이 기능을 사용하면 새 자격 증명을 입력하고 동기화를 다시 사용할 수 있을 때까지 동기화가 일시적으로 중지됩니다. 이전 인증 모드로 되돌리려면 기능을 비활성화할 수 있습니다(2022년 4월까지).

## Dynamics 동기화 사용자 정보 입력 {#enter-dynamics-sync-user-information}

1. Marketo에 로그인하고 를 클릭합니다. **관리**.

   ![](assets/login-admin.png)

1. 클릭 **CRM**.

   ![](assets/image2015-3-16-9-3a47-3a34.png)

1. 선택 **Microsoft**.

   ![](assets/image2015-3-16-9-3a50-3a6.png)

1. 클릭 **편집** in **1단계: 자격 증명 입력**.

   ![](assets/image2015-3-16-9-3a48-3a43.png)

   >[!CAUTION]
   >
   >제출 후 후속 스키마 변경 사항을 되돌릴 수 없으므로 조직 URL이 올바른지 확인하십시오. 잘못된 조직 URL을 사용하는 경우 새 Marketo 구독을 받아야 합니다. URL을 모르면 [여기에서 찾는 방법 알아보기](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md).

   >[!NOTE]
   >
   >새 자격 증명을 입력하기 전에 다음을 수행할 수 있습니다 [여기에서 확인하십시오.](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md).

1. 을(를) 입력합니다. **사용자 이름**, **암호**, **클라이언트 ID**, **클라이언트 암호**, 및 Microsoft Dynamics **URL**. 클릭 **저장** 완료 시.

   ![](assets/step-4-of-4-connect-the-marketo-solution-ropc-5.png)

   >[!NOTE]
   >
   >Marketo의 사용자 이름은 CRM에서 동기화 사용자의 사용자 이름과 일치해야 합니다. 형식은 다음과 같습니다 `user@domain.com` 또는 DOMAIN\user.

## 동기화할 필드 선택 {#select-fields-to-sync}

1. 클릭 **편집** in **2단계: 동기화할 필드 선택**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Marketo에 동기화할 필드를 선택하면 미리 선택됩니다. 클릭 **저장**.

   ![](assets/image2016-8-25-15-3a6-3a11.png)

>[!NOTE]
>
>Marketo은 동기화할 필드에 대한 참조를 저장합니다. Dynamics에서 필드를 삭제하는 경우 [동기화 사용 안 함](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). 그런 다음 를 편집하고 저장하여 Marketo에서 스키마를 새로 고칩니다 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md).

## 사용자 지정 필터에 대한 필드 동기화 {#sync-fields-for-a-custom-filter}

사용자 지정 필터를 만든 경우 로 이동하여 Marketo과 동기화할 새 필드를 선택하십시오.

1. Admin으로 이동하여 를 선택합니다 **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 클릭 **편집** 필드 동기화 세부 정보

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 아래로 스크롤하여 필드를 확인합니다. 실제 이름은 new_synctokto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. 클릭 **저장**.

   ![](assets/image2016-8-25-15-3a7-3a35.png)

## 동기화 활성화 {#enable-sync}

1. 클릭 **편집** in **3단계: 동기화 활성화**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo은 Microsoft Dynamics 동기화에 대해 자동으로 중복 제거를 수행하지 않거나 수동으로 사람 또는 리드를 입력할 때 자동으로 중복 제거를 수행하지 않습니다.

1. 팝업에서 모든 내용을 읽고 전자 메일 주소를 입력한 다음 **동기화 시작**.

   ![](assets/image2015-3-16-9-3a55-3a10.png)

1. 첫 번째 동기화는 몇 시간이 걸릴 수 있습니다. 완료되면 이메일 알림을 받게 됩니다.

   ![](assets/image2015-3-16-9-3a59-3a51.png)

탁월한 작업!
