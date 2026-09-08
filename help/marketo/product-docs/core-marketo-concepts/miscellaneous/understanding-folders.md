---
unique-page-id: 4720779
description: 스마트 캠페인 및 자산을 구성하기 위한 프로그램 내의 폴더에 대해 알아봅니다. 폴더를 만들고 이름을 바꾸고 삭제합니다.
title: 폴더 이해
exl-id: 2ea914f6-ca64-4e87-806c-93beba075ab2
TQID: https://experienceleague.adobe.com/wAE129LK3Pk-CB5SSQqqSV50ng085soYsm4JHfh0CuI
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: a7170d27-32ab-462b-a333-269abc654483id: c5f60233-d5ea-4453-a799-0ad258b4d399id: d65b4a73-87a3-4d56-b638-74e74d9939ceid: f82558ea-6af5-44eb-a424-5b3389abb0a3
source-git-commit: b77e1a1e72b89e7cdef5733dbb2de4405ebf3b07
workflow-type: tm+mt
source-wordcount: 412
ht-degree: 4%

---

# 폴더 이해 {#understanding-folders}

프로그램 내의 폴더를 사용하여 스마트 캠페인과 자산을 구성할 수 있습니다. [캠페인 폴더](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/create-new-campaign-folder.md)와(과) 다릅니다.

## 폴더 만들기 {#create-a-folder}

1. **[!UICONTROL Marketing Activities]** 영역으로 이동합니다.

   ![](assets/ma.png)

1. 프로그램을 마우스 오른쪽 단추로 클릭하고 **[!UICONTROL New Folder]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-4-20-18-3a45-3a14.png){width="600" zoomable="yes"}

1. 새 폴더 이름을 지정하고 **[!UICONTROL Enter]**&#x200B;을 누릅니다.

   ![](assets/image2015-4-20-18-3a46-3a57.png){width="600" zoomable="yes"}

이제 새 폴더가 로컬 자산에 대해 준비되었습니다.

## 폴더 이름 바꾸기 {#rename-a-folder}

1. 폴더를 마우스 오른쪽 버튼으로 클릭하고 **[!UICONTROL Rename Folder]**&#x200B;를 선택합니다.

   ![](assets/image2015-4-20-18-3a49-3a10.png){width="600" zoomable="yes"}

1. 새 이름을 입력하고 **[!UICONTROL Enter]**&#x200B;을(를) 누릅니다.

   ![](assets/image2015-4-20-18-3a52-3a30.png){width="600" zoomable="yes"}

## 폴더 삭제 {#delete-a-folder}

>[!NOTE]
>
>삭제하기 전에 폴더가 비어 있는지 확인하십시오.

1. 폴더를 마우스 오른쪽 버튼으로 클릭하고 **[!UICONTROL Delete Folder]**&#x200B;를 선택합니다.

   ![](assets/image2015-4-20-18-3a55-3a51.png){width="600" zoomable="yes"}

## 폴더 보관 {#archive-a-folder}

Marketo에서는 기존 폴더를 보관 폴더로 변환할 수 있습니다. 보관 폴더가 [!UICONTROL Marketing Activities], [!UICONTROL Database] 및 [!UICONTROL Design Studio]에 있습니다.

![](assets/image2015-4-20-19-3a3-3a46.png){width="600" zoomable="yes"}

폴더를 보관할 때:

* 폴더 및 에셋이 더 이상 검색 결과에 표시되지 않습니다. 보관된 폴더 내에 있는 프로그램 또는 이벤트를 검색하는 경우 결과는 보관된 폴더의 축소된 보기를 반환합니다
* 폴더의 에셋이 자동 제안에 더 이상 표시되지 않습니다
* Design Studio에서 이메일 또는 랜딩 페이지를 만들 때 보관된 템플릿을 사용할 수 없습니다.
* 보관된 페이지는 랜딩 페이지 테스트 그룹에서 사용할 수 없습니다.

보관 시 **변경되지** 않는 기능:

* 글로벌 검색은 보관된 폴더에서 결과를 계속 찾음
* 필터를 사용하여 보고서에 사용할 보관된 자산을 선택할 수 있습니다

### 보관 중인 캠페인 비활성화 {#disable-campaigns-archive}

폴더나 프로그램이 보관되거나 활성 Smart Campaign이 이미 보관된 폴더로 이동되면 Marketo Engage은 영향을 받는 캠페인의 실행을 중지합니다.

* **트리거된 캠페인**&#x200B;이 비활성화되었습니다.
* **일괄 캠페인**&#x200B;에서 보류 중인 실행이 취소되었습니다.
* **실행 가능한 캠페인**&#x200B;에 실행 상태가 없으므로 아무 작업도 수행되지 않습니다.

**지원되는 작업**

다음 작업은 캠페인을 비활성화합니다.

* 활성 캠페인이 포함된 **폴더**&#x200B;을(를) 보관된 폴더로 드래그 앤 드롭
* 활성 캠페인이 포함된 **program**(모든 유형)을 보관된 폴더로 드래그 앤 드롭
* **단일 스마트 캠페인**&#x200B;을(를) 보관된 폴더로 드래그 앤 드롭
* 보관된 폴더로 단일 스마트 캠페인에서 **이동**&#x200B;을 마우스 오른쪽 단추로 클릭
* 활성 캠페인이 들어 있는 폴더에서 보관된 폴더로 **폴더 이동**&#x200B;을 마우스 오른쪽 단추로 클릭
* 보관된 폴더로 활성 캠페인이 포함된 프로그램에서 **이동**&#x200B;을 마우스 오른쪽 단추로 클릭
* 이동 없이 보관하려면 폴더에서 **보관된 폴더로 변환**&#x200B;을 마우스 오른쪽 단추로 클릭하십시오.

>[!NOTE]
>
>보관되는 폴더 또는 프로그램 내의 스마트 캠페인을 다른 곳에서 참조하는 경우(예: &quot;캠페인 요청&quot; 흐름 단계를 통해) 보관을 차단하여 다른 캠페인이 중단되지 않도록 합니다.
