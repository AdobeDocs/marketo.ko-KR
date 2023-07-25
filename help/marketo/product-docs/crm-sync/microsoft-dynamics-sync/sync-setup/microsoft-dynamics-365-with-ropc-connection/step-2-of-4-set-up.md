---
description: 2단계/4단계 - 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정 - Marketo 문서 - 제품 설명서
title: 2단계/4단계 - 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정
exl-id: 41c05910-d8e3-4fb7-8f68-17ee10294e57
feature: Microsoft Dynamics
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '440'
ht-degree: 0%

---

# 2단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정 {#step-2-of-4-set-up-the-marketo-solution-ropc}

사용자 계정을 만들어 시작하겠습니다.

>[!PREREQUISITES]
>
>[1단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md)

## 새 사용자 만들기 {#create-a-new-user}

1. Dynamics에 로그인합니다. 설정 아이콘을 클릭하고 다음을 선택합니다. **고급 설정**.

   ![](assets/one.png)

1. 클릭 **설정** 및 선택 **보안**.

   ![](assets/two.png)

1. 클릭 **사용자**.

   ![](assets/three.png)

1. 클릭 **신규.**

   ![](assets/four.png)

1. 클릭 **사용자 추가 및 라이센스 부여** 새 창에서 을 클릭합니다.

   ![](assets/five.png)

1. 새 탭이 열립니다. 클릭 **관리자** 을 클릭합니다.

   ![](assets/six.png)

1. 다른 새 탭이 열립니다. 클릭 **사용자 추가**.

   ![](assets/seven.png)

   >[!IMPORTANT]
   >
   >동기화 사용자는 Marketo 구성에 대한 읽기 권한이 있어야 합니다.

1. 모든 정보를 입력하십시오. 완료되면 다음을 클릭합니다. **추가**.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >이 이름은 기존 CRM 사용자의 계정이 아닌 전용 동기화 사용자여야 합니다. 실제 이메일 주소일 필요는 없습니다.

1. 새 사용자 자격 증명을 받을 이메일을 입력하고 **이메일 전송 및 닫기**.

   ![](assets/nine.png)

## 동기화 사용자 역할 할당 {#assign-sync-user-role}

Marketo 동기화 사용자 역할만 Marketo 동기화 사용자에게 할당합니다. 다른 사용자에게 할당할 필요가 없습니다.

>[!NOTE]
>
>이 기능은 Marketo 버전 4.0.0.14 이상에 적용됩니다. 이전 버전의 경우 모든 사용자에게 동기화 사용자 역할이 있어야 합니다. Marketo을 업그레이드하려면 다음을 참조하십시오. [Microsoft Dynamics용 Marketo 솔루션 업그레이드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
>
>동기화 사용자의 언어 설정 [영어로 설정해야 함](https://portal.dynamics365support.com/knowledgebase/article/KA-01201/en-us).

1. 활성화된 사용자 탭으로 돌아가서 사용자 목록을 새로 고칩니다.

   ![](assets/ten.png)

1. 새로 생성된 Marketo 동기화 사용자 옆에 마우스를 가져다 대면 확인란이 표시됩니다. 클릭하여 선택합니다.

   ![](assets/eleven.png)

1. 클릭 **역할 관리**.

   ![](assets/twelve.png)

1. 확인 **Marketo 동기화 사용자** 및 클릭 **확인**.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >동기화 사용자가 CRM을 업데이트하면 **아님** Marketo에 다시 동기화됩니다.

## Marketo 솔루션 구성 {#configure-marketo-solution}

거의 다 됐어! 이제 새로 만든 사용자에 대해 Marketo 솔루션에 알리는 일만 남았습니다.

1. 고급 설정 섹션으로 돌아가서 ![](assets/image2015-5-13-15-3a49-3a19.png) 아이콘을 클릭하고 **Marketo 구성**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >표시되지 않으면 **Marketo 구성** 설정 메뉴에서 페이지를 새로 고칩니다. 그래도 안 되면 [Marketo 솔루션 게시](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md) 다시 로그인하거나 로그아웃했다가 다시 로그인합니다.

1. 클릭 **기본값**.

   ![](assets/fifteen.png)

1. 에서 검색 단추를 클릭합니다. **Marketo 사용자** 을(를) 필드에 추가하고 생성한 동기화 사용자를 선택합니다.

   ![](assets/sixteen.png)

1. 다음을 클릭합니다. ![](assets/image2015-3-13-15-3a10-3a11.png) 아이콘을 클릭하여 변경 내용을 저장합니다.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. 다음을 클릭합니다. **X** 오른쪽 상단에서 화면을 닫습니다.

   ![](assets/seventeen.png)

1. 다음을 클릭합니다. ![](assets/image2015-5-13-15-3a49-3a19-1.png) 아이콘을 클릭하고 **솔루션**.

   ![](assets/eighteen.png)

1. 다음을 클릭합니다. **모든 사용자 지정 게시** 단추를 클릭합니다.

   ![](assets/nineteen.png)

>[!MORELIKETHIS]
>
>[3단계/4단계: 리소스 소유자 암호 제어 연결과 Marketo 솔루션 연결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md)
