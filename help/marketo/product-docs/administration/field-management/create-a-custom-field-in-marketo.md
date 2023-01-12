---
unique-page-id: 2360287
description: Marketo에서 사용자 지정 필드 만들기 - Marketo 문서 - 제품 설명서
title: Marketo에서 사용자 지정 필드 만들기
exl-id: 6face1d7-6a4e-412b-9708-6aa7e43e8c11
source-git-commit: cd742b3c4ff464a7efeb6490b88fe78e6b3f4ae8
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 0%

---

# Marketo에서 사용자 지정 필드 만들기 {#create-a-custom-field-in-marketo}

Marketo에서 데이터를 저장/캡처하기 위해 새로운 사용자 지정 필드가 필요한 경우 여기에 데이터를 만드는 방법이 있습니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/create-a-custom-field-in-marketo-1.png)

1. 클릭 **필드 관리**.

   ![](assets/create-a-custom-field-in-marketo-2.png)

   >[!TIP]
   >
   >필드를 CRM과 계속 동기화하려면 CRM에서 만들면 Marketo에서 자동으로 만들어집니다.

1. 클릭 **새 사용자 지정 필드**.

   ![](assets/create-a-custom-field-in-marketo-3.png)

1. 유형 필드를 선택합니다. 이렇게 하면 Marketo의 스마트 목록 및 양식에서 렌더링되는 방식이 변경됩니다.

   >[!TIP]
   >
   >다음을 확인하십시오 [사용자 지정 필드 유형 용어집](/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md).

   ![](assets/create-a-custom-field-in-marketo-4.png)

1. Marketo에 표시할 이름 을 입력합니다. API 이름이 자동으로 생성됩니다. 수정할 수 있지만 한 번 설정하면 이름을 변경할 수 없습니다. 클릭 **만들기** 완료 시.

>[!CAUTION]
>
>필드 이름은 다음 문자로 시작할 수 없습니다. **. &amp; +[]**

![](assets/create-a-custom-field-in-marketo-5.png)

>[!NOTE]
>
>API 이름은 SOAP API 및 기타 백엔드 프로세스에서 사용됩니다.

이제 양식, 흐름 단계 및 스마트 목록에서 이 사용자 지정 필드를 사용할 수 있습니다.
