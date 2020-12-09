---
unique-page-id: 2360327
description: 할당 규칙을 사용하여 개인 파티션 할당 - 마케팅 문서 - 제품 설명서
title: 할당 규칙에 개인 파티션 지정
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '218'
ht-degree: 0%

---


# 할당 규칙에 개인 파티션 지정 {#assigning-person-partitions-with-assignment-rules}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

>[!NOTE]
>
>**관리자 권한 필요**

>[!PREREQUISITES]
>
>* [개인 파티션 만들기](create-a-person-partition.md)

>



개인 파티션을 사용할 때는 할당 규칙을 설정하여 CRM에서 만든 사람을 각각의 파티션으로 라우팅합니다.

>[!NOTE]
>
>CRM과 SOAP API를 통해 Markto에서 만든 사람만 할당 규칙이 적용됩니다.

1. 관리에서 작업 영역 및 파티션을 클릭합니다.

![](assets/image2014-9-17-10-3a32-3a55.png)

1. **사용자 파티션 **탭 아래에서 할당 **규칙을 클릭합니다**.

   ![](assets/two-6.png)

1. 사람을 개인 파티션으로 라우팅하기 위한 조건을 추가하려면 **선택 추가 **를 클릭합니다.

   ![](assets/three-6.png)

1. 조건을 빌드할 필드를 선택합니다.

   ![](assets/four-5.png)

1. 선택 연산자를 선택하고 값을 입력합니다.
1. ![](assets/five-1.png)

1. 조건을 충족하는 사람이 포함되기를 원하는 사람 파티션을 선택합니다.

   ![](assets/six-1.png)

   >[!NOTE]
   >
   >
   >원하는 만큼 선택할 수 있습니다.

   저장을 클릭합니다.
   ![](assets/seven.png)

그리고 거기 있어! 개인 파티션을 사람으로 채우는 규칙을 지정했습니다.

>[!NOTE]
>
>이전 조건이 충족되지 않을 경우 기본 선택이 적용됩니다.

