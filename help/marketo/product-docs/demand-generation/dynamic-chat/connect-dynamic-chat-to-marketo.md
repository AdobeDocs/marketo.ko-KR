---
description: Marketo에 다이내믹 채팅 연결 - Marketo 문서 - 제품 설명서
title: Marketo에 동적 채팅 연결
exl-id: bad6c2dc-d4e7-4f98-bf6d-743043f96e4e
source-git-commit: c36b9206494c14a52937fa787a37601eaf6f4bd4
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---

# Marketo에 동적 채팅 연결 {#connect-dynamic-chat-to-marketo}

을(를) 완료한 후 [초기 설정](/help/marketo/product-docs/demand-generation/dynamic-chat/initial-setup.md)Marketo 구독에 Dynamic Chat를 연결하는 1회 동기화를 수행할 차례입니다.

1. 내 Marketo에서 **다이내믹 채팅** 타일.

   ![](assets/connect-dynamic-chat-to-marketo-1.png)

   >[!NOTE]
   >
   >타일이 표시되지 않으면 Marketo 관리자에게 문의하십시오.

1. 이전에 Adobe ID으로 애플리케이션에 액세스한 적이 있는 경우 바로 Dynamic Chat로 이동합니다. 그렇지 않으면, [Adobe ID 설정](https://helpx.adobe.com/manage-account/using/create-update-adobe-id.html).

1. Marketo 인스턴스를 연결하려면 **통합**.

   ![](assets/connect-dynamic-chat-to-marketo-2.png)

1. Marketo 카드에서 **동기화 시작**.

   ![](assets/connect-dynamic-chat-to-marketo-3.png)

1. 대상 타깃팅, 데이터 매핑 및 개인화에 사용할 동적 채팅과 동기화하려면 Marketo 인스턴스에서 최대 50개의 표준 또는 사용자 지정 필드를 선택합니다. 클릭 **다음** 완료 시.

   ![](assets/connect-dynamic-chat-to-marketo-4.png)

   >[!CAUTION]
   >
   >현재 속성 선택 **사용할 수 없음** 초기 동기화 후 변경됨. 동기화가 완료되면 되돌아가서 더 추가할 수만 있습니다(50개 미만으로 선택한 경우).

1. 선택 사항 검토(미리 알림: 동기화 후 속성을 제거할 수 없으므로 **선택 항목 편집** 이 단계에서 변경할 필요가 있는 경우). 클릭 **확인** 동기화가 완료되면 됩니다.

   ![](assets/connect-dynamic-chat-to-marketo-5.png)

>[!NOTE]
>
>데이터베이스 크기에 따라 동기화가 완료되는 데 2~24시간이 걸릴 수 있습니다.

## Adobe 조직 및 Marketo 연결 {#link-your-adobe-org-and-marketo}

이제 Adobe과 Marketo을 연결할 차례입니다.

>[!IMPORTANT]
>
>이 매핑을 설정하는 Marketo Engage 사용자의 이메일 주소도 연결 중인 Adobe 조직에 액세스할 수 있어야 합니다.

1. 에 로그인합니다. [experience.adobe.com](https://experience.adobe.com).

1. Experience Cloud의 아무 곳이나 화면을 클릭하고 ctrl+i를 누릅니다. 에서 **지정된 조직** 탭에서 조직 ID 를 강조 표시하고 복사합니다(_빼기_ @AdobeOrg). 누르기 **닫기** 완료 시.

   ![](assets/connect-dynamic-chat-to-marketo-6.png)

1. Marketo에서 **관리** 섹션을 선택하고 **Adobe 조직 매핑**.

   ![](assets/connect-dynamic-chat-to-marketo-7.png)

1. 클릭 **편집**.

   ![](assets/connect-dynamic-chat-to-marketo-8.png)

1. 2단계에서 복사한 조직 ID를 붙여넣고 **확인**.

   ![](assets/connect-dynamic-chat-to-marketo-9.png)

>[!MORELIKETHIS]
>
>[초기 설정](/help/marketo/product-docs/demand-generation/dynamic-chat/initial-setup.md)
