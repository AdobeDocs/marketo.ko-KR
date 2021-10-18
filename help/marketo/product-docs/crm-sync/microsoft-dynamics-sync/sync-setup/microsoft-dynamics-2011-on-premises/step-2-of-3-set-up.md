---
unique-page-id: 3571807
description: 3단계 중 2단계 - Dynamics에서 Marketo 동기화 사용자 설정(2011 온프레미스) - Marketo 문서 - 제품 설명서
title: 3단계 중 2단계 - Dynamics에서 Marketo 동기화 사용자 설정(2011 온프레미스)
exl-id: 807c8902-24a6-48b6-a5c9-96a72764fdef
source-git-commit: 41d8762203786bac9aea03ac978daa0549ac8e93
workflow-type: tm+mt
source-wordcount: '369'
ht-degree: 0%

---

# 3단계 중 2단계: Dynamics에서 Marketo 동기화 사용자 설정(2011 온프레미스) {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises}

이전 단계를 완료하는 것이 좋습니다. 이것을 계속 진행합시다.

>[!PREREQUISITES]
>
>[3단계 중 1단계: Marketo 솔루션 설치(2011 온프레미스)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md)

## 동기화 사용자 역할 할당 {#assign-sync-user-role}

Marketo 동기화 사용자 역할만 Marketo 동기화 사용자에게 할당합니다. 다른 사용자에게 할당할 필요가 없습니다.

>[!NOTE]
>
>Marketo 플러그인 버전 4.0.0.14 이상에 적용됩니다. 이전 버전의 경우 모든 사용자는 동기화 사용자 역할이 있어야 합니다. Marketo을 업그레이드하려면 다음을 참조하십시오 [Microsoft Dynamics용 Marketo 솔루션 업그레이드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
>
>동기화 사용자의 언어 설정 [영어로 설정되어야 함](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us).

1. 왼쪽 아래 메뉴에서 **설정**.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. 트리에서 를 선택합니다 **관리**.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. 선택 **사용자**.

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. 여기에 사용자 목록이 표시됩니다. 전용 Marketo 동기화 사용자를 선택하거나 [AFDS(Active Directory Federation Services)](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 관리자가 Marketo 전용 새 사용자를 만들 수 있습니다. 클릭 **역할 관리**.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. 확인 **Marketo 동기화 사용자** 을(를) 클릭합니다. **확인**.

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   >
   >역할이 표시되지 않으면 로 돌아갑니다 [3단계 중 1단계](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md) 솔루션을 가져옵니다.

   >[!NOTE]
   >
   >동기화 사용자가 CRM에서 수행한 모든 업데이트 **not** Marketo에 다시 동기화됩니다.

## Marketo 솔루션 구성 {#configure-marketo-solution}

거의 다 됐어! 다음 문서로 이동하기 전에 몇 가지 구성 만 있습니다.

1. 선택 **설정**. 그런 다음 을(를) 선택합니다 **Marketo 구성** 나무에 있습니다.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   >
   >Marketo 구성이 누락된 경우 페이지를 새로 고쳐 보십시오. 문제가 계속되면 [Marketo 솔루션 다시 게시](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-1-of-3-install.md) 또는 로그아웃한 후 다시 로그인합니다.

1. 클릭 **기본값**.

   ![](assets/image2015-4-2-14-3a27-3a30.png)

1. 클릭 ![](assets/image2015-4-2-14-3a29-3a1.png)

   ![](assets/image2015-4-2-14-3a28-3a40.png)

1. 팝업에서 동기화 사용자를 선택합니다. 그런 다음 **확인**.

   ![](assets/image2015-4-2-14-3a32-3a43.png)

1. 클릭 **저장** 변경 사항을 저장하려면 을 클릭합니다.

   ![](assets/image2015-4-2-14-3a34-3a15.png)

1. 클릭 **모든 사용자 지정 게시**.

   ![](assets/publish-all-customizations1.png)

## 3단계로 진행하기 전 {#before-proceeding-to-step}

    * 동기화하려는 레코드 수를 제한하려면 [사용자 지정 동기화 필터 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md)을 지금 설정합니다.
    * [Microsoft Dynamics 동기화 유효성 검사](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) 프로세스를 실행합니다. 초기 설정이 올바르게 수행되었는지 확인합니다.
    * Microsoft Dynamics CRM에서 Marketo 동기화 사용자에게 로그인합니다.

잘했어요!

>[!MORELIKETHIS]
>
>[3단계 중 3단계: Microsoft Dynamics와 Marketo 연결(2011 온프레미스)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2011-on-premises/step-3-of-3-connect.md)
