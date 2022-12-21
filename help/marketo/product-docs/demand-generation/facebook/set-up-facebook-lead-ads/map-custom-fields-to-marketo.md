---
unique-page-id: 12983101
description: 사용자 지정 필드를 Marketo에 매핑 - Marketo 문서 - 제품 설명서
title: Marketo에 사용자 지정 필드 매핑
exl-id: c52c9bcb-6448-4ebe-b87f-9e3a48e3d27d
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '258'
ht-degree: 0%

---

# Marketo에 사용자 지정 필드 매핑 {#map-custom-fields-to-marketo}

facebook에서 기본적으로 제공하는 표준 정보(예: 사용자가 온라인 게재 서비스를 사용하는 빈도)보다 많은 정보를 수집하려는 경우. 다음을 통해 이 작업을 수행할 수 있습니다. [사용자 지정 질문 만들기](https://www.facebook.com/business/help/774623835981457?helpref=uf_permalink) facebook 리드 광고입니다.

하지만, **Marketo에서 이 데이터 수집을 자동으로 시작하지 않습니다**. Marketo에서 사용자 지정 필드 값 캡처를 시작하려면 다음을 수행합니다 **반드시** 이러한 사용자 지정 필드를 Marketo의 필드에 매핑합니다.

다음은 관리자의 LaunchPoint 영역에서 설정하는 방법입니다.

>[!NOTE]
>
>**관리 권한 필요**

1. Admin Area 로 이동하고 **LaunchPoint**. 설치된 서비스에서 를 찾아 편집합니다 **Facebook 리드 광고**.

   ![](assets/image2017-10-24-9-3a32-3a16.png)

1. 클릭 **다음**.

   ![](assets/image2017-10-24-14-3a55-3a13.png)

1. 인증된 계정을 그대로 둡니다. **not** 변경합니다. 클릭 **다음**.

   ![](assets/image2017-10-24-14-3a56-3a48.png)

1. 전과 같이 선택한 페이지를 그대로 둡니다. **not** 변경합니다. 클릭 **다음**.

   ![](assets/image2017-10-24-15-3a0-3a54.png)

1. 여기에서는 사용자 지정 Facebook 필드를 Marketo 필드에 매핑합니다. 클릭 **추가.**

   ![](assets/image2017-10-24-9-3a33-3a49.png)

1. 새 행에서 Facebook 사용자 지정 필드의 이름을 입력합니다.

   ![](assets/image2017-10-24-9-3a37-3a3.png)

   >[!NOTE]
   >
   >facebook 양식 템플릿에 저장된 필드만 옵션으로 표시됩니다.

1. 을(를) 클릭합니다. **Marketo 필드** 열. 매핑할 필드를 검색할 을 입력합니다. 필드를 선택하면 **저장**.

   ![](assets/image2017-10-24-11-3a16-3a42.png)

   >[!NOTE]
   >
   >Marketo에 Facebook 필드를 매핑할 필드가 아직 없다면 방법을 알아보십시오 [사용자 지정 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md).

>[!CAUTION]
>
>사용자 **반드시** Marketo에서 데이터를 수집하려면 새로운 Facebook 필드에 대해 이 프로세스를 진행하십시오.
