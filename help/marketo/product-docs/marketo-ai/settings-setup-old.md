---
description: Marketo AI 권한을 활성화하고 조직 규칙을 구성하고 통합 및 알림과 같은 설정을 관리하는 방법을 알아봅니다.
title: 설정 및 설정
hide: true
hidefromtoc: true
exl-id: d6f37214-65b9-48c1-bf9f-d64b4eda87b9
source-git-commit: c0854d574b4fc995f249783aebcd15ed7d224851
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 0%

---

# 설정 및 설정 {#settings-setup}

권한을 활성화하고 설정 영역을 사용하여 연결 세부 정보를 보고, 조직 규칙을 정의하고, 통합 및 알림을 설정하는 방법을 알아봅니다.

## 권한 {#permissions}

>[!IMPORTANT]
>
>Marketo AI의 Alpha 단계에서 관리자, Adobe 제품 관리자, 마케팅 사용자, 표준 사용자 역할에 대해 _액세스가 기본적으로 활성화됨_&#x200B;됩니다. 따라서 액세스하려는 역할에 대해 이 기능을 켜는 대신 그렇지 않은 역할에 대해 이 기능을 꺼야 합니다.

### 모든 항목에 대한 액세스 {#access-for-all}

위에 나열된 모든 역할에 대해 Marketo AI를 활성화하려면 아무 작업도 수행할 필요가 없습니다.

### 일부 액세스 권한 {#access-for-some}

역할에 대한 액세스 권한을 제거하려면 아래 단계를 따르십시오.

1. 내 Marketo에서 **관리자**&#x200B;를 클릭한 다음 **사용자 및 역할**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-1.png)

1. _역할_ 탭에서 원하는 역할을 선택하고 **역할 편집**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-2.png)

1. 아래로 스크롤하여 _AI로 빌드 액세스_ 확인란을 **선택 취소**&#x200B;한 다음 **저장**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-3.png)

원하는 다른 역할에 대해 이 단계를 반복합니다.

### 사용자 정의 역할 {#custom-role}

[새 역할을 만들고](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role#create-a-role){target="_blank"} 사용 권한을 사용자 지정하는 옵션이 있습니다. _AI로 빌드에 액세스_&#x200B;를 추가하고 [특정 사용자에게 해당 역할을 할당](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user){target="_blank"}합니다.

<!-- 
## Permissions {#permissions}

In order to access Marketo AI, Admins must first enable role permissions. 

1. In your My Marketo, click **Admin**, then **Users & Roles**.

   ![](assets/settings-setup-1.png)

1. In the _Roles_ tab, select the desired role and click **Edit Role**.

   ![](assets/settings-setup-2.png)

1. Scroll down and select the **Access Build with AI** checkbox and click **Save**.

   ![](assets/settings-setup-3.png)

-->

## 설정 {#settings}

1. 내 Marketo에서 **AI로 빌드** 타일을 클릭합니다.

   ![](assets/settings-setup-4.png)

1. 톱니바퀴 아이콘을 클릭합니다.

   ![](assets/settings-setup-5.png)

### 연결 {#connection}

이 탭에는 편집 가능한 필드가 포함되어 있지 않습니다. Munchkin ID 및 IMS 조직과 같은 계정 정보를 표시합니다.

![](assets/settings-setup-6.png)

### 조직 규칙 {#organizational-rules}

Marketo Engage 에셋을 만들거나 수정할 때 Marketo AI가 따라야 하는 조직 지침 및 제약 조건을 정의합니다.

![](assets/settings-setup-7.png){width="800" zoomable="yes"}

>[!NOTE]
>
>규칙은 YAML 프론트매트와 함께 Markdown 형식을 사용합니다. 전역 규칙은 모든 작업 영역에 적용됩니다. Workspace 규칙은 전역 설정을 재정의합니다.

### 통합(준비 중) {#integrations}

외부 서비스 및 API에 대한 연결을 구성합니다.

_이 탭은 UI에 표시될 수 있지만 아직 사용할 수 없습니다._ 업데이트를 다시 확인하십시오.

### 알림(준비 중) {#notifications}

경고 환경 설정 및 알림 채널을 관리합니다.

_이 탭은 UI에 표시될 수 있지만 아직 사용할 수 없습니다._ 업데이트를 다시 확인하십시오.
