---
unique-page-id: 2360335
description: 신뢰할 수 없는 소스에서 목록 가져오기 중 필드 업데이트 차단 - Marketo 문서 - 제품 설명서
title: 신뢰할 수 없는 소스에서 목록 가져오기 중 블록 필드 업데이트
exl-id: 0fd59f0c-6cb9-442c-937b-da18a4466873
feature: Field Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 13%

---

# 신뢰할 수 없는 소스에서 목록 가져오기 중 블록 필드 업데이트 {#block-field-updates-during-list-import-from-untrusted-sources}

일부 목록의 데이터를 다른 목록보다 더 신뢰할 수 있습니다. 때때로 의심스러운 데이터가 있고 필드가 비어 있으면 가져오려고 하지만 기존 값이 있는 경우에는 가져오지 않습니다. 주요 필드의 필드 업데이트를 차단하여 이를 수행할 수 있습니다.

>[!NOTE]
>
>**관리자 권한 필요**

## 신뢰할 수 없는 원본에서 필드 업데이트 차단 {#blocking-field-updates-from-untrusted-sources}

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/blocking-field-updates-from-untrusted-sources-1.png)

1. **[!UICONTROL Field Management]**&#x200B;를 클릭합니다.

   ![](assets/blocking-field-updates-from-untrusted-sources-2.png)

1. 원하는 필드를 찾아 선택한 다음 **[!UICONTROL Field Actions]**&#x200B;에서 **[!UICONTROL Block Field Updates]**&#x200B;을(를) 클릭합니다.

   ![](assets/blocking-field-updates-from-untrusted-sources-3.png)

1. **[!UICONTROL List Import untrusted source]**&#x200B;을(를) 확인하고 **[!UICONTROL Apply]**&#x200B;을(를) 클릭합니다.

   ![](assets/blocking-field-updates-from-untrusted-sources-4.png)

>[!TIP]
>
>**[!UICONTROL List Import trusted source]**&#x200B;을(를) 확인하여 신뢰할 수 있고 신뢰할 수 없는 모든 목록에서 필드를 안전하게 유지할 수 있습니다.

신뢰할 수 없는 목록에서 안전하게 보호할 다른 필드에 대해 위의 단계를 반복합니다.

## 신뢰할 수 없는 목록 가져오기 실행 {#running-an-untrusted-list-import}

1. 목록 가져오기를 실행할 때 이전 단계에서 설정한 모든 필드를 안전하게 하려면 **[!UICONTROL Untrusted]**&#x200B;을(를) 선택해야 합니다.

   ![](assets/blocking-field-updates-from-untrusted-sources-5.png)

목록 가져오기에 대한 자세한 지침은 [사람 목록 가져오기](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md)를 참조하십시오.

수고하셨습니다! 이제 신뢰할 수 없는 목록에서 키 필드를 안전하게 유지하는 방법을 알 수 있습니다.
