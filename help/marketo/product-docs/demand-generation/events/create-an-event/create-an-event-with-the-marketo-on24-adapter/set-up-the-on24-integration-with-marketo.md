---
description: Marketo - Marketo 문서 - 제품 설명서와 ON24 통합 설정
title: Marketo과 ON24 통합 설정
exl-id: 395ffa37-b87d-4eb4-bf9f-72aa96dc819c
feature: Events
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# Marketo과 ON24 통합 설정{#set-up-the-on24-integration-with-marketo}

다음은 ON24 이벤트 통합을 설정하는 방법입니다.

## API 전용 역할 만들기 {#create-an-api-only-role}

1. 내 Marketo에서 **관리자**&#x200B;를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-1.png)

1. 보안에서 **사용자 및 역할**&#x200B;을 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-2.png)

1. **역할** 탭을 클릭한 다음 **새 역할**&#x200B;을 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-3.png)

1. 역할 이름을 입력합니다. **API 액세스** 메뉴를 열고 &quot;사용자 지정 개체 읽기-쓰기&quot; 및 &quot;사용자 읽기-쓰기&quot;를 선택하십시오. **만들기**&#x200B;를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-4.png)

## 새 사용자 만들기 {#create-a-new-user}

1. 여전히 사용자 및 역할에서 **사용자** 탭을 클릭하고 **새 사용자 초대**&#x200B;를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-5.png)

1. 새 사용자 정보를 입력하고 **다음**&#x200B;을(를) 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-6.png)

1. 방금 만든 ON24 API 전용 역할을 선택합니다. **API만** 확인란을 선택하십시오. **다음**&#x200B;을 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-7.png)

1. **보내기**&#x200B;를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-8.png)

>[!NOTE]
>
>API 전용 사용자에게는 초대가 필요하지 않습니다.

## ON24 연결 설정 {#set-up-on24-connection}

1. 관리자 섹션에서 **LaunchPoint**&#x200B;을(를) 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-9.png)

1. **새로 만들기**&#x200B;를 클릭한 다음 **새 서비스**&#x200B;를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-10.png)

1. 표시 이름을 선택합니다. **서비스** 드롭다운을 클릭하고 **사용자 지정**&#x200B;을 선택합니다. 설명을 입력합니다. API 전용 사용자 드롭다운을 클릭하고 위의 단계[&#128279;](#create-a-new-user)에서 을(를) 만든 사용자를 선택합니다. **만들기**&#x200B;를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-11.png)

1. 방금 만든 사용자 지정 LaunchPoint 서비스를 찾은 다음 세부 정보 보기를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-12.png)

1. 클라이언트 ID를 강조 표시하고, 마우스 오른쪽 단추로 클릭하고, 복사한 다음 저장합니다(나중에 필요함). 클라이언트 암호에 대해 이 작업을 반복합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-13.png)

1. 왼쪽의 트리에서 웹 서비스를 클릭합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-14.png)

1. &quot;REST API&quot;에서 ID의 첫 번째 부분(.com의 &#39;m&#39;까지)을 강조 표시하고, 마우스 오른쪽 단추로 클릭하고, 복사하고, 저장합니다.

   ![](assets/set-up-the-on24-integration-with-marketo-15.png)

1. 저장된 클라이언트 ID, 클라이언트 암호 및 ID를 사용하여 ON24 계정으로 이동합니다. 나머지 단계는 여기에서 수행되며 [여기](https://on24support.force.com/Support/s/article/Connect-Marketo-ON24-Connect-Data-Integration#Step6){target="_blank"}에 요약되어 있습니다.
