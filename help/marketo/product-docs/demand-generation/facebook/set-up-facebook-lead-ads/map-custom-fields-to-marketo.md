---
unique-page-id: 12983101
description: 사용자 정의 필드를 Marketo - Marketo 문서 - 제품 설명서에 매핑
title: Marketo에 사용자 정의 필드 매핑
exl-id: c52c9bcb-6448-4ebe-b87f-9e3a48e3d27d
feature: Integrations
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '252'
ht-degree: 0%

---

# Marketo에 사용자 정의 필드 매핑 {#map-custom-fields-to-marketo}

누군가 온라인 게재 서비스를 사용하는 빈도와 같이 기본적으로 Facebook에서 저장하는 표준 정보보다 더 많은 정보를 수집할 수 있습니다. facebook 리드 광고에서 [사용자 지정 질문을 만들기](https://www.facebook.com/business/help/774623835981457?helpref=uf_permalink)하여 이를 수행할 수 있습니다.

그러나 **Marketo에서 자동으로 이 데이터 수집을 시작하지 않습니다**. Marketo에서 사용자 지정 필드 값을 캡처하려면 **반드시**&#x200B;이(가) 이러한 사용자 지정 필드를 Marketo의 필드에 매핑해야 합니다.

다음은 관리자의 LaunchPoint 영역에서 설정하는 방법입니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. 관리 영역으로 이동하여 **LaunchPoint**&#x200B;을(를) 클릭합니다. 설치된 서비스에서 **Facebook 리드 광고**&#x200B;를 찾아 편집합니다.

   ![](assets/image2017-10-24-9-3a32-3a16.png)

1. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2017-10-24-14-3a55-3a13.png)

1. 승인된 계정을 그대로 둡니다. **변경하지 마십시오**. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2017-10-24-14-3a56-3a48.png)

1. 이전처럼 선택한 페이지를 그대로 둡니다. **변경하지 마십시오**. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2017-10-24-15-3a0-3a54.png)

1. 사용자 지정 Facebook 필드를 Marketo 필드에 매핑하는 위치는 다음과 같습니다. **추가**&#x200B;를 클릭합니다.

   ![](assets/image2017-10-24-9-3a33-3a49.png)

1. 새 행에서 Facebook 사용자 정의 필드의 이름을 입력합니다.

   ![](assets/image2017-10-24-9-3a37-3a3.png)

   >[!NOTE]
   >
   >facebook 양식 템플릿에 저장된 필드만 여기에 옵션으로 표시됩니다.

1. **Marketo 필드** 열을 클릭합니다. 매핑할 필드를 검색하려면 을(를) 입력합니다. 필드를 선택하면 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2017-10-24-11-3a16-3a42.png)

   >[!NOTE]
   >
   >Marketo에 Facebook 필드를 매핑할 필드가 없는 경우 [사용자 정의 필드를 만드는 방법](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)을 알아보세요.

>[!CAUTION]
>
>Marketo에서 데이터를 수집하려면 새 Facebook 필드에 대해 **반드시** 이 프로세스를 수행해야 합니다.
