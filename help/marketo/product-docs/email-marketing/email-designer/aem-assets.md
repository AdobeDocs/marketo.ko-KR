---
title: Experience Manager Assets 작업
description: Adobe Marketo Engage에서 콘텐츠를 작성할 때 연결된 AEM Assets 저장소의 이미지 에셋을 사용하는 방법을 알아봅니다.
hide: true
hidefromtoc: true
source-git-commit: 723caafc41da6d4aeb9101bb6f9a999b45d72dd9
workflow-type: tm+mt
source-wordcount: '626'
ht-degree: 1%

---

# Experience Manager 에셋으로 작업 {#work-with-experience-manager-assets}

_Adobe Experience Manager Assets as a Cloud Service_&#x200B;이(가) Adobe Marketo Engage과 통합되면 마케팅 콘텐츠에서 사용할 디지털 에셋에 쉽게 액세스할 수 있습니다. 콘텐츠를 작성할 때 왼쪽 탐색 메뉴의 _[!UICONTROL Assets]_ 항목에서 전자 메일 콘텐츠를 작성할 때 자산에 액세스할 수 있습니다. 연결된 _AEM Assets as a Cloud Service_ 저장소에 Marketo Engage에서 직접 에셋을 업로드할 수도 있습니다. &lt;------- NILESH는 다음을 확인합니다.

>[!NOTE]
>
>현재 _Adobe Experience Manager Assets_&#x200B;의 이미지 자산만 Marketo Engage에서 지원됩니다. &lt;---- NILESH가 확인합니다 — 에셋을 변경하려면 Adobe Experience Manager Assets 중앙 저장소에서 수행해야 합니다. [자세히 알아보기](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/manage/manage-digital-assets)

이러한 디지털 에셋을 사용하는 경우 _Assets as a Cloud Service 이메일_&#x200B;의 최신 변경 사항이 연결된 참조를 통해 캠페인에 자동으로 전파됩니다. _Adobe Experience Manager Assetsas a Cloud Service 에서 이미지가 삭제되면_ 이메일에 손상된 참조가 표시됩니다. 현재 Marketo Engage에서 사용 중인 에셋이 수정되거나 삭제되면 이메일 작성자에게 이미지 변경 사항에 대한 알림이 표시됩니다. 에셋에 대한 모든 변경 작업은 Adobe Experience Manager Assets 중앙 저장소에서 수행해야 합니다.

## AEM Assets을 이미지 소스로 사용 {#use-aem-assets-as-the-image-source}

환경에 Assets 저장소 연결이 하나 이상 있는 경우 이메일, 이메일 템플릿 또는 시각적 조각에 대한 세부 사항을 만들거나 볼 때 AEM Assets을 에셋의 소스로 지정할 수 있습니다.

* 새 콘텐츠를 만들 때 대화 상자에서 `AEM Assets`을(를) **[!UICONTROL Image Source]** 항목으로 선택하십시오.

![만들기 대화 상자에서 이미지 소스로 AEM Assets 선택](assets/work-with-experience-manager-assets-1.png){width="400"}

* 기존 콘텐츠 리소스를 열 때 오른쪽의 _[!UICONTROL 본문]_ 패널에서 `AEM Assets`을(를) 선택합니다.

![속성에서 이미지 소스로 AEM Assets 선택](assets/work-with-experience-manager-assets-2.png){width="700" zoomable="yes"}

## 작성을 위해 에셋에 액세스

>[!IMPORTANT]
>
>관리자는 자산에 액세스해야 하는 사용자를 Assets 소비자 사용자 및/또는 Assets 사용자 제품 프로필에 추가해야 합니다. [자세히 알아보기](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/security/ims-support#managing-products-and-user-access-in-admin-console)

시각적 콘텐츠 편집기에서 왼쪽 사이드바의 _자산 선택기_ 아이콘을 클릭합니다. 이렇게 하면 도구 패널이 선택한 저장소에서 사용 가능한 에셋 목록으로 변경됩니다.

![Assets 선택기 아이콘을 클릭하여 이미지 자산에 액세스합니다](assets/work-with-experience-manager-assets-3.png){width="700" zoomable="yes"}

연결된 AEM 저장소가 두 개 이상 있는 경우 **[!UICONTROL 저장소]**&#x200B;의 메뉴 화살표를 클릭하여 사용할 저장소를 선택합니다.

![이미지 자산에 액세스할 AEM Assets 저장소를 선택하십시오](assets/work-with-experience-manager-assets-4.png){width="700" zoomable="yes"}

이미지 에셋을 시각적 캔버스에 추가하는 방법에는 여러 가지가 있습니다.

* 왼쪽 탐색에서 이미지 썸네일을 끌어서 놓습니다.

![이미지 자산에 액세스할 AEM Assets 저장소를 선택하십시오](assets/work-with-experience-manager-assets-5.png){width="700" zoomable="yes"}

* 캔버스에 이미지 구성 요소를 추가하고 **[!UICONTROL 찾아보기]**&#x200B;를 클릭하여 _[!UICONTROL Assets 선택]_ 대화 상자를 엽니다.

  대화 상자에서 선택한 저장소에서 이미지를 선택할 수 있습니다.

  필요한 에셋을 찾는 데 도움이 되는 여러 가지 도구가 있습니다.

![Assets 선택 대화 상자에서 도구를 사용하여 이미지 자산을 찾아 선택합니다](assets/work-with-experience-manager-assets-6.png){width="700" zoomable="yes"}

* 오른쪽 상단에서 **[!UICONTROL 저장소]**&#x200B;를 변경합니다.

* 오른쪽 상단의 **[!UICONTROL 자산 관리]**&#x200B;를 클릭하여 다른 브라우저 탭에서 Assets 저장소를 열고 AEM Assets 관리 도구를 사용합니다.

* 표시를 **[!UICONTROL 목록 보기]**, **[!UICONTROL 눈금 보기]**, **[!UICONTROL 갤러리 보기]** 또는 **[!UICONTROL 폭포 보기]**(으)로 변경하려면 오른쪽 상단의 _보기 유형_ 선택기를 클릭하십시오.

* 오름차순과 내림차순 사이의 정렬 순서를 변경하려면 _정렬 순서_ 아이콘을 클릭하십시오.

* **[!UICONTROL 정렬 기준]** 메뉴 화살표를 클릭하여 정렬 기준을 **[!UICONTROL 이름]**, **[!UICONTROL 크기]** 또는 **[!UICONTROL 수정됨]**(으)로 변경합니다.

* 조건에 따라 표시된 항목을 필터링하려면 왼쪽 상단의 _필터_ 아이콘을 클릭하십시오.

* 표시된 항목을 자산 이름과 일치하도록 필터링하려면 검색 필드에 텍스트를 입력합니다.

![필터 및 검색 필드를 사용하여 자산을 찾습니다](assets/work-with-experience-manager-assets-7.png){width="700" zoomable="yes"}
