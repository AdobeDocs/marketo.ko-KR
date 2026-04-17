---
description: Marketo AI 권한을 활성화하고 조직 규칙을 구성하고 통합 및 알림과 같은 설정을 관리하는 방법을 알아봅니다.
title: 설정 및 설정
hide: true
hidefromtoc: true
source-git-commit: 47389ec9d7974d5f75a68bfbb0e32e8147d8eaaa
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 2%

---

# 설정 및 설정 {#settings-setup}

권한을 활성화하고 설정 영역을 사용하여 연결 세부 정보를 보고, 조직 규칙을 정의하고, 통합 및 알림을 설정하는 방법을 알아봅니다.

## 권한 및 역할 {#permission-and-role}

관리자가 _AI가 있는 빌드_ 기능에 액세스할 수 있는 사용자를 보다 강력하게 제어할 수 있도록 AI가 있는 _액세스 빌드_ 권한과 AI가 있는 **빌드** 역할이 있습니다. 권한은 역할 수준에서 할당됩니다. _AI가 있는 빌드_ 역할은 기본적으로 _AI가 있는 빌드 액세스_ 권한이 활성화되어 있습니다.

>[!IMPORTANT]
>
>_AI로 빌드 액세스_ 권한이 모든 역할에 대해 기본적으로 활성화되어 있지 않습니다. 자세한 내용은 아래 표를 참조하십시오.

<table><thead>
  <tr>
    <th>역할</th>
    <th>기본 상태</th>
  </tr></thead>
<tbody>
  <tr>
    <td>관리</td>
    <td>활성화됨</td>
  </tr>
  <tr>
    <td>Adobe 제품 관리자</td>
    <td>활성화됨</td>
  </tr>
  <tr>
    <td>마케팅 사용자</td>
    <td>비활성화됨</td>
  </tr>
  <tr>
    <td>표준 사용자</td>
    <td>사용할 수 없음</td>
  </tr>
  <tr>
    <td>AI 사용자로 빌드</td>
    <td>활성화됨</td>
  </tr>
  <tr>
    <td>사용자 정의 역할</td>
    <td>비활성화됨</td>
  </tr>
</tbody>
</table>

### AI 권한으로 빌드에 액세스 {#access-build-with-ai-permission}

아직 활성화되지 않은 자격을 갖춘 역할에 대해 _AI로 빌드 액세스_&#x200B;를 활성화하려면 아래 단계를 따르십시오.

1. 내 Marketo에서 **관리자**&#x200B;를 클릭한 다음 **사용자 및 역할**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-1.png)

1. _역할_ 탭에서 원하는 역할을 선택하고 **역할 편집**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-2.png)

1. 아래로 스크롤하여 _AI로 빌드 액세스_ 확인란을 선택하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-3.png)

   >[!NOTE]
   >
   >**실행** AI로 빌드 액세스&#x200B;_확인란을 선택하여 권한을 제거하는 동일한 단계를 사용할 수 있습니다._

### AI 사용자 역할로 빌드 {#build-with-ai-user-role}

다음 단계에 따라 특정 사용자를 _AI 사용자로 빌드_ 역할에 할당합니다.

1. 내 Marketo에서 **관리자**&#x200B;를 클릭한 다음 **사용자 및 역할**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-1.png)

1. 원하는 사용자를 선택하고 **사용자 편집**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-5b.png)

1. _역할 및 작업 공간_&#x200B;에서 _AI 사용자로 빌드_ 확인란을 선택하십시오. 작업 영역이 두 개 이상 있는 경우 **+** 서명 드롭다운에서 액세스할 작업 영역을 지정할 수 있습니다. 완료되면 **저장**&#x200B;을 클릭합니다.

   ![](assets/settings-setup-6b.png)

### 사용자 정의 역할 {#custom-role}

[새 역할을 만들고](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role#create-a-role){target="_blank"} 사용 권한을 사용자 지정하는 옵션이 있습니다. _AI로 빌드에 액세스_&#x200B;를 추가하고 [특정 사용자에게 해당 역할을 할당](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user){target="_blank"}합니다.

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
