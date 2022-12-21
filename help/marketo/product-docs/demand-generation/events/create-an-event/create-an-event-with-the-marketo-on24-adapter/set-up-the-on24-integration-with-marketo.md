---
description: Marketo과 ON24 통합 설정 - Marketo 문서 - 제품 설명서
title: Marketo과 ON24 통합 설정
exl-id: 395ffa37-b87d-4eb4-bf9f-72aa96dc819c
source-git-commit: 3e0823976e8b837fcb2fdbbf03f26da48cbd74b7
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 1%

---

# Marketo과 ON24 통합 설정{#set-up-the-on24-integration-with-marketo}

다음은 ON24 이벤트 통합을 설정하는 방법입니다.

## API 전용 역할 만들기 {#create-an-api-only-role}

1. 내 Marketo에서 **관리**.

   ![](assets/set-up-the-on24-integration-with-marketo-1.png)

1. 보안(Security)에서 **사용자 및 역할**.

   ![](assets/set-up-the-on24-integration-with-marketo-2.png)

1. 을(를) 클릭합니다. **역할** 탭한 다음 **새 역할**.

   ![](assets/set-up-the-on24-integration-with-marketo-3.png)

1. 역할 이름을 입력합니다. 를 엽니다. **액세스 API** 메뉴를 선택하고 &quot;Read-Write Custom Object&quot; 및 &quot;Read-Write Person&quot;을 선택합니다. Click **Create**.

   ![](assets/set-up-the-on24-integration-with-marketo-4.png)

## 새 사용자 만들기 {#create-a-new-user}

1. 여전히 사용자 및 역할에서 **사용자** 탭을 클릭하고 **새 사용자 초대**.

   ![](assets/set-up-the-on24-integration-with-marketo-5.png)

1. 새 사용자 정보를 입력하고 **다음**.

   ![](assets/set-up-the-on24-integration-with-marketo-6.png)

1. 방금 만든 ON24 API 전용 역할을 선택합니다. 을(를) 선택합니다 **API만** 확인란을 선택합니다. 클릭 **다음**.

   ![](assets/set-up-the-on24-integration-with-marketo-7.png)

1. 클릭 **보내기**.

   ![](assets/set-up-the-on24-integration-with-marketo-8.png)

>[!NOTE]
>
>API 전용 사용자에게는 초대가 필요하지 않습니다.

## ON24 연결 설정 {#set-up-on24-connection}

1. 여전히 관리 섹션에서 **LaunchPoint**.

   ![](assets/set-up-the-on24-integration-with-marketo-9.png)

1. 클릭 **새로 만들기** 그런 다음 **새 서비스**.

   ![](assets/set-up-the-on24-integration-with-marketo-10.png)

1. 표시 이름을 선택합니다. 을(를) 클릭합니다. **서비스** 드롭다운 및 선택 **사용자 지정**. 설명을 입력합니다. API 전용 사용자 드롭다운을 클릭하고 생성한 사용자를 선택합니다 [위의 단계에서](#create-a-new-user). Click **Create**.

   ![](assets/set-up-the-on24-integration-with-marketo-11.png)

1. 방금 만든 사용자 지정 LaunchPoint 서비스를 찾고 세부 정보 보기를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-12.png)

1. 클라이언트 ID를 강조 표시하고 마우스 오른쪽 단추를 클릭하여 복사하고 저장합니다(나중에 필요함). Client Secret에 대해 반복합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-13.png)

1. 왼쪽의 트리에서 웹 서비스를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-14.png)

1. &quot;REST API&quot;에서 강조 표시하고 마우스 오른쪽 단추를 클릭하고, 복사하여 ID의 첫 번째 부분(.com의 &#39;m&#39;까지)을 저장합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-15.png)

1. 저장된 클라이언트 ID, 클라이언트 암호 및 ID를 사용하여 ON24 계정으로 이동합니다. 나머지 단계는 여기에서 수행되며, [여기 설명](https://on24support.force.com/Support/s/article/Connect-Marketo-ON24-Connect-Data-Integration#Step6){target=&quot;_blank&quot;}.
