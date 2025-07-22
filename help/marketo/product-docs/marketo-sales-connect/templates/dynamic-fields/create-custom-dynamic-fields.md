---
unique-page-id: 14352508
description: 사용자 정의 동적 필드 만들기 - Marketo 문서 - 제품 설명서
title: 사용자 지정 동적 필드 만들기
exl-id: 860511d2-4a8a-47a4-8362-ba4e715e44e9
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 0%

---

# 사용자 지정 동적 필드 만들기 {#create-custom-dynamic-fields}

사용자 지정 동적 필드를 만드는 방법에는 두 가지가 있습니다.

## 한 명 또는 몇 명의 대화 상대에 대한 사용자 정의 필드 저장 {#saving-custom-fields-for-one-or-a-few-contacts}

1. [!UICONTROL People] 페이지에서 연락처 이름을 클릭합니다.

1. [!UICONTROL Unsubscribe] 옆에 있는 드롭다운을 선택하고 **[!UICONTROL Edit]**&#x200B;을(를) 선택합니다.

1. 편집 페이지 아래쪽으로 스크롤합니다. 그런 다음 필드의 이름과 값을 만들 수 있습니다.

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

## 여러 연락처에 대한 사용자 정의 필드 저장 {#saving-custom-fields-for-many-contacts}

1. 사용자 정의 필드가 포함된 CSV 스프레드시트를 자체 열에 만듭니다.

1. [일반 CSV 업로드 프로세스](/help/marketo/product-docs/marketo-sales-connect/people/managing-contacts/import-contacts-via-csv.md)를 수행하고 필드 매핑 화면에서 중지합니다.

1. 사전 설정 필드 중 하나 대신 드롭다운에서 **[!UICONTROL Add a new Custom Field]**&#x200B;을(를) 선택합니다.

1. 원하는 필드 이름을 입력하고 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

1. CSV 업로드를 완료합니다. 연락처는 추가된 사용자 정의 필드를 통해 전달됩니다.

>[!NOTE]
>
>사용자 정의 필드를 만든 후 템플릿 편집기의 동적 필드 드롭다운에 필드가 표시되는 데 약 30분이 걸릴 수 있습니다.

## 템플릿에서 사용자 정의 필드를 사용하는 방법 {#how-to-use-your-custom-fields-in-a-template}

위의 방법을 사용하여 사용자 정의 필드를 저장하면 템플릿에서 참조할 수 있습니다.

1. [템플릿을 만들고](/help/marketo/product-docs/marketo-sales-connect/templates/create-a-new-template.md) 평소처럼 **[!UICONTROL Dynamic Fields]** 단추를 클릭합니다.

1. 표시되는 드롭다운에서 **[!UICONTROL Custom Fields]**&#x200B;을(를) 선택합니다.

1. 미리 저장된 사용자 정의 필드가 표시되고 템플릿에서 작성할 사용자 정의 필드를 선택할 수 있습니다.
