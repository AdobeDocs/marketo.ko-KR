---
unique-page-id: 2360287
description: Marketo - Marketo 문서 - 제품 설명서에서 사용자 정의 필드 만들기
title: Marketo에서 사용자 정의 필드 만들기
exl-id: 6face1d7-6a4e-412b-9708-6aa7e43e8c11
feature: Field Management
source-git-commit: dcc2af51726db6f503486fb0553fb32fc65495ce
workflow-type: tm+mt
source-wordcount: '179'
ht-degree: 1%

---

# Marketo에서 사용자 정의 필드 만들기 {#create-a-custom-field-in-marketo}

데이터를 저장/캡처하기 위해 Marketo Engage에 새 사용자 정의 필드가 필요한 경우 만드는 방법은 다음과 같습니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/create-a-custom-field-in-marketo-1.png)

1. **[!UICONTROL Field Management]**&#x200B;을(를) 클릭합니다.

   ![](assets/create-a-custom-field-in-marketo-2.png)

   >[!TIP]
   >
   >필드가 CRM과 계속 동기화되도록 하려면 CRM에서 필드를 만들면 Marketo에서 자동으로 만들어집니다.

1. **[!UICONTROL New Custom Field]**&#x200B;을(를) 클릭합니다.

   ![](assets/create-a-custom-field-in-marketo-3.png)

1. _[!UICONTROL Object]_&#x200B;선택.

   ![](assets/create-a-custom-field-in-marketo-4.png)

   >[!NOTE]
   >
   >_회사_ 개체를 직접 선택할 수는 없지만 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 연락하여 요청할 수 있습니다.

1. 필드 _[!UICONTROL Type]_&#x200B;을(를) 선택합니다. 이렇게 하면 Marketo의 스마트 목록 및 양식에서 렌더링되는 방법이 변경됩니다.

   >[!TIP]
   >
   >[사용자 지정 필드 형식 용어집](/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md){target="_blank"}을 확인하십시오.

   ![](assets/create-a-custom-field-in-marketo-5.png)

1. Marketo에 표시할 _[!UICONTROL Name]_&#x200B;을(를) 입력하십시오(_[!UICONTROL API Name]_&#x200B;이(가) 자동으로 생성됨). 저장한 후에는 이름을 바꿀 수 없으므로 신중하게 선택합니다. 완료되면 **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

>[!CAUTION]
>
>필드 이름은 **. &amp; +[]** 문자로 시작할 수 없습니다.

![](assets/create-a-custom-field-in-marketo-6.png)

>[!NOTE]
>
>API 이름은 SOAP API 및 기타 백엔드 프로세스에서 사용됩니다.

이제 양식, 흐름 단계 및 스마트 목록에서 이 사용자 정의 필드를 사용할 수 있습니다!
