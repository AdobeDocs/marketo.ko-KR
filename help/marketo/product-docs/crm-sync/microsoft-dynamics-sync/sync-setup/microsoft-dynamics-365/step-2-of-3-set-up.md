---
unique-page-id: 3571827
description: 3단계 중 2단계 - Dynamics에서 Marketing To Docs - 제품 문서 설정
title: 3단계 중 2단계 - Dynamics에서 Marketing to Sync 사용자 설정
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 0%

---


# 3단계 중 2단계:Dynamics에서 Marketing To 동기화 사용자 설정 {#step-of-set-up-marketo-sync-user-in-dynamics}

사용자 계정을 만들어 시작하십시오.

>[!PREREQUISITES]
>
>[3단계 중 1단계:Marketing To 솔루션(온라인) 설치](step-1-of-3-install.md)

## 새 사용자 만들기 {#create-a-new-user}

1. Dynamics에 로그인합니다. 설정 아이콘을 클릭하고 **고급 설정을 선택합니다**.

   ![](assets/one.png)

1. *** 설정**을 클릭하고 **보안을 선택합니다**.

   ![](assets/two.png)

1. 사용자를 **클릭합니다**.

   ![](assets/three.png)

1. 새로 **만들기를 클릭합니다.**

   ![](assets/four.png)

1. 새 **창에서 사용자** 추가 및 라이센스 부여를 클릭합니다.

   ![](assets/five.png)

1. 새 탭이 열립니다. 페이지 **맨** 위에 있는 관리자를 클릭합니다.

   ![](assets/six.png)

1. 다른 새 탭이 열립니다. 사용자 **추가를 클릭합니다**.

   ![](assets/seven.png)

1. 모든 정보를 입력합니다. 완료되면 **추가를 클릭합니다**.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >이 이름은 기존 CRM 사용자 계정이 아닌 전용 동기화 사용자여야 합니다. 실제 이메일 주소가 될 필요는 없습니다.

1. 새 사용자 자격 증명을 받을 이메일을 입력하고 [이메일 **보내기]를 클릭하고 [닫기]를 클릭합니다**.

   ![](assets/nine.png)

## 동기화 사용자 역할 할당 {#assign-sync-user-role}

Marketing to Sync 사용자 역할만 Marketing to 동기화 사용자에게 할당합니다. 다른 사용자에게 할당할 필요는 없습니다.

>[!NOTE]
>
>이는 Marketing 버전 4.0.0.14 이상에 적용됩니다. 이전 버전의 경우 모든 사용자는 동기화 사용자 역할이 있어야 합니다. Marketing to를 업그레이드하려면 Microsoft Dynamics [용 Marketing Solution 업그레이드를 참조하십시오](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md).

1. 활성화된 사용자 탭으로 돌아가서 사용자 목록을 새로 고칩니다.

   ![](assets/ten.png)

1. 새로 만든 Marketing To Sync 사용자 옆에 마우스를 가져가면 확인란이 나타납니다. 클릭하여 선택합니다.

   ![](assets/eleven.png)

1. 역할 **관리를 클릭합니다**.

   ![](assets/twelve.png)

1. Marketing **to Sync 사용자** 를 선택하고 **확인을 클릭합니다**.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >동기화 사용자가 CRM에서 만든 모든 업데이트는 Marketing To로 다시 동기화되지 **않습니다** .

## 마케팅 솔루션 구성 {#configure-marketo-solution}

거의 다 왔어! 이제 Marketing To Solution에서 만든 신규 사용자에 대해 알리는 일만 남았습니다.

1. 고급 설정 섹션으로 돌아가서 설정 옆에 있는 ![](assets/image2015-5-13-15-3a49-3a19.png)아이콘을 클릭하고 마케팅 **구성을 선택합니다**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >설정 메뉴에 **마케팅** 구성이 표시되지 않으면 페이지를 새로 고칩니다. 그렇지 않으면 Marketing To 솔루션 [을](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) 다시 게시하거나 로그아웃했다가 다시 [](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) 로그인하십시오.

1. 기본값 **을 클릭합니다**.

   ![](assets/fifteen.png)

1. Marketing to User **** 필드에서 검색 단추를 클릭하고 만든 사용자 동기화를 선택합니다.

   ![](assets/sixteen.png)

1. 오른쪽 아래 모서리의 ![](assets/image2015-3-13-15-3a10-3a11.png)아이콘을 클릭하여 변경 사항을 저장합니다.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. 화면 **을** 닫으려면 오른쪽 상단의 X를 클릭합니다.

   ![](assets/seventeen.png)

1. 설정 옆에 있는 ![](assets/image2015-5-13-15-3a49-3a19-1.png)아이콘을 클릭하고 **솔루션을 선택합니다**.

   ![](assets/eighteen.png)

1. 모든 사용자 지정 **게시 단추를** 클릭합니다.

   ![](assets/nineteen.png)

## 3단계로 이동하기 전 {#before-proceeding-to-step}

    * 동기화되는 레코드 수를 제한하려면 지금 [사용자 정의 동기화 필터 설정](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md)을 참조하십시오.
    * [Microsoft Dynamics 동기화 유효성 검사](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) 프로세스를 실행합니다. 초기 설정이 올바르게 수행되었는지 확인합니다.
    * Microsoft Dynamics CRM에서 Marketing to Sync 사용자에 로그인합니다.

>[!NOTE]
>
>**관련 문서**
>
>
>[3단계 중 3단계:Microsoft Dynamics와 Marketing(온라인) 연결](step-3-of-3-connect.md)
