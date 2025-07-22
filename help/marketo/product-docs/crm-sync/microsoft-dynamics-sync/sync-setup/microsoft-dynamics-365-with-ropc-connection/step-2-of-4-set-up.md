---
description: 2단계/4단계 - 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정 - Marketo 문서 - 제품 설명서
title: 2단계/4단계 - 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정
exl-id: 41c05910-d8e3-4fb7-8f68-17ee10294e57
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '397'
ht-degree: 1%

---

# 2단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정 {#step-2-of-4-set-up-the-marketo-solution-ropc}

사용자 계정을 만들어 시작하겠습니다.

>[!PREREQUISITES]
>
>[4단계 중 1단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md){target="_blank"}

## 새 사용자 만들기 {#create-a-new-user}

1. [!DNL Dynamics]에 로그인합니다. [!UICONTROL Settings] 아이콘을 클릭하고 **[!UICONTROL Advanced Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/one.png)

1. **[!UICONTROL Settings]**&#x200B;을(를) 클릭하고 **[!UICONTROL Security]**&#x200B;을(를) 선택합니다.

   ![](assets/two.png)

1. **[!UICONTROL Users]**&#x200B;을(를) 클릭합니다.

   ![](assets/three.png)

1. **[!UICONTROL New]**&#x200B;을(를) 클릭합니다.

   ![](assets/four.png)

1. 새 창에서 **[!UICONTROL Add and License Users]**&#x200B;을(를) 클릭합니다.

   ![](assets/five.png)

1. 새 탭이 열립니다. 페이지 맨 위에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/six.png)

1. 다른 새 탭이 열립니다. **[!UICONTROL Add a user]**&#x200B;을(를) 클릭합니다.

   ![](assets/seven.png)

   >[!IMPORTANT]
   >
   >동기화 사용자는 Marketo 구성에 대한 읽기 권한이 있어야 합니다.

1. 모든 정보를 입력하십시오. 완료되면 **[!UICONTROL Add]**&#x200B;을(를) 클릭합니다.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >이 이름은 기존 CRM 사용자의 계정이 아닌 전용 동기화 사용자여야 합니다. 실제 이메일 주소일 필요는 없습니다.

1. 새 사용자 자격 증명을 받을 전자 메일을 입력하고 **[!UICONTROL Send email and close]**&#x200B;을(를) 클릭합니다.

   ![](assets/nine.png)

## 동기화 사용자 역할 할당 {#assign-sync-user-role}

Marketo 동기화 사용자 역할만 Marketo 동기화 사용자에게 할당합니다. 다른 사용자에게 할당할 필요가 없습니다.

>[!NOTE]
>
>Marketo 버전 4.0.0.14 이상에 적용됩니다. 이전 버전의 경우 모든 사용자에게 동기화 사용자 역할이 있어야 합니다. Marketo을 업그레이드하려면 [Marketo 솔루션 업그레이드 [!DNL Microsoft Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md)를 참조하십시오.

>[!IMPORTANT]
>
>동기화 사용자 [의 언어 설정은 영어](https://learn.microsoft.com/en-us/power-platform/admin/enable-languages){target="_blank"}(으)로 설정해야 합니다.

1. [!UICONTROL Enabled Users] 탭으로 돌아가서 사용자 목록을 새로 고칩니다.

   ![](assets/ten.png)

1. 새로 생성된 Marketo 동기화 사용자 옆에 마우스를 가져다 대면 확인란이 표시됩니다. 클릭하여 선택합니다.

   ![](assets/eleven.png)

1. **[!UICONTROL Manage Roles]**&#x200B;을(를) 클릭합니다.

   ![](assets/twelve.png)

1. **[!UICONTROL Marketo Sync User]**&#x200B;을(를) 확인하고 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >동기화 사용자가 CRM에서 업데이트한 내용은 _다시 Marketo에 동기화되지 않습니다_.

## Marketo 솔루션 구성 {#configure-marketo-solution}

거의 다 됐어! 이제 새로 만든 사용자에 대해 Marketo 솔루션에 알리는 일만 남았습니다.

1. [!UICONTROL Advanced Settings] 섹션으로 돌아가서 ![](assets/image2015-5-13-15-3a49-3a19.png) 옆에 있는 [!UICONTROL Settings] 아이콘을 클릭하고 **[!UICONTROL Marketo Config]**&#x200B;을(를) 선택합니다.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >**[!UICONTROL Marketo Config]** 메뉴에 [!UICONTROL Settings]이(가) 없으면 페이지를 새로 고치세요. 그래도 작동하지 않으면 [Marketo 솔루션을 다시 게시](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md)하거나 로그아웃했다가 다시 로그인하세요.

1. **[!UICONTROL Default]**&#x200B;을(를) 클릭합니다.

   ![](assets/fifteen.png)

1. **[!UICONTROL Marketo User]** 필드의 검색 단추를 클릭하고 만든 동기화 사용자를 선택합니다.

   ![](assets/sixteen.png)

1. 오른쪽 아래 모서리에 있는 ![](assets/image2015-3-13-15-3a10-3a11.png) 아이콘을 클릭하여 변경 사항을 저장합니다.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. 화면을 닫으려면 오른쪽 상단의 **X**&#x200B;을(를) 클릭합니다.

   ![](assets/seventeen.png)

1. ![](assets/image2015-5-13-15-3a49-3a19-1.png) 옆에 있는 [!UICONTROL Settings] 아이콘을 클릭하고 **[!UICONTROL Solutions]**&#x200B;을(를) 선택합니다.

   ![](assets/eighteen.png)

1. **[!UICONTROL Publish All Customizations]** 단추를 클릭합니다.

   ![](assets/nineteen.png)

>[!MORELIKETHIS]
>
>[3단계/4단계: 리소스 소유자 암호 제어 연결과 Marketo 솔루션 연결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md){target="_blank"}
