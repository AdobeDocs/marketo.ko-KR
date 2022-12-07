---
unique-page-id: 2360335
description: 신뢰할 수 없는 소스로부터 목록을 가져오는 동안 차단 필드 업데이트 - Marketo 문서 - 제품 설명서
title: 신뢰할 수 없는 원본에서 목록을 가져오는 동안 차단 필드 업데이트
exl-id: 0fd59f0c-6cb9-442c-937b-da18a4466873
source-git-commit: 2776969be44ba1a3d795e99986d10cf0470fb9e9
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 0%

---

# 신뢰할 수 없는 원본에서 목록을 가져오는 동안 차단 필드 업데이트 {#block-field-updates-during-list-import-from-untrusted-sources}

일부 목록의 데이터는 다른 것보다 더 신뢰할 수 있습니다. 의심스러운 데이터가 있고 필드가 비어 있는 경우 가져가려고 하지만, 기존 값이 있는 경우에는 가져오려고 합니다. 키 필드에서 필드 업데이트를 차단하여 이 작업을 수행할 수 있습니다.

>[!NOTE]
>
>**관리 권한 필요**

## 신뢰할 수 없는 소스로부터 필드 업데이트 차단 {#blocking-field-updates-from-untrusted-sources}

1. 로 이동합니다. **관리** 영역.

   ![](assets/blocking-field-updates-from-untrusted-sources-1.png)

1. 클릭 **필드 관리**.

   ![](assets/blocking-field-updates-from-untrusted-sources-2.png)

1. 원하는 필드를 찾아 선택한 다음 **필드 작업**&#x200B;를 클릭합니다. **블록 필드 업데이트**.

   ![](assets/blocking-field-updates-from-untrusted-sources-3.png)

1. 확인 **신뢰할 수 없는 원본 가져오기 목록** 을(를) 클릭합니다. **적용**.

   ![](assets/blocking-field-updates-from-untrusted-sources-4.png)

>[!TIP]
>
>또한 를 확인하여 신뢰할 수 있고 신뢰할 수 없는 모든 목록에서 필드를 안전하게 유지할 수 있습니다 **목록 가져오기 신뢰할 수 있는 원본**.

신뢰할 수 없는 목록에서 안전하게 유지할 다른 필드에 위의 단계를 반복합니다.

## 신뢰할 수 없는 목록 가져오기 실행 {#running-an-untrusted-list-import}

1. 목록 가져오기를 실행할 때는 **신뢰할 수 없음** 이전 단계에서 설정한 모든 필드를 안전하게 만들려면

   ![](assets/blocking-field-updates-from-untrusted-sources-5.png)

목록 가져오기에 대한 자세한 지침은 [사람 목록 가져오기](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md).

잘 했어요! 이제 신뢰할 수 없는 목록에서 키 필드를 안전하게 유지하는 방법을 알 수 있습니다.
