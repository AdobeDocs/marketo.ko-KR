---
unique-page-id: 7515767
description: 작업 공간 및 파티션에서 세그먼트 공유 - Marketo 문서 - 제품 설명서
title: 작업 공간 및 파티션 간에 세그먼트 공유
exl-id: b50f4328-fdba-4e39-bc0d-75bade1f9cbc
source-git-commit: 686530e63cffef89bc7b9cbf6affa862689c0a46
workflow-type: tm+mt
source-wordcount: '471'
ht-degree: 0%

---

# 작업 공간 및 파티션 간에 세그먼트 공유 {#share-segmentations-across-workspaces-and-partitions}

>[!PREREQUISITES]
>
>이 문서는 작업 공간 및 파티션이 있는 고객에게만 제공됩니다.

## 세그먼테이션이란 무엇입니까? {#whats-a-segmentation}

Marketo은 좋은 사람들을 좋은 프로그램이나 스마트 캠페인을 위해 골라내는 것을 아주 잘 합니다. 그러나 보다 영구적인 사용자의 경우 세그먼테이션을 사용해야 합니다. Marketo에서 고급 동적 콘텐츠를 사용해야 합니다.

>[!NOTE]
>
>학습 [세그멘테이션을 만드는 방법](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md).

이러한 가상 사용자를 설정하고 나면(_및_ 작업 공간을 사용하면) 작업 공간에서 공유할 수 있습니다. 다음은 알아야 할 몇 가지 좋은 점입니다.

## 규칙 및 팁 {#rules-tips}

* 각 Marketo 구독에는 여러 작업 공간(**작업 공간당 20개 아님**).
* 액세스 권한이 있는 작업 영역에서만 세그먼테이션을 공유할 수 있습니다.
* 을(를) 만들고 활용해야 합니다 **모든 파티션에 대한 가시성이 있는 기본 작업 영역**.

* 세분화 처리는 세그먼테이션이 만들어진 작업 공간의 사람에서만 실행됩니다.

   * 기본 작업 공간에서 공유할 세그멘테이션을 만듭니다.
      * 세그멘테이션 승인
      * 공유 작업 공간에는 잠긴 폴더가 표시되고 세그먼테이션은 읽기 전용입니다.
      * 공유 버전을 편집할 수 없습니다. 원래 세그먼테이션을 만든 위치만 편집할 수 있습니다.
   * 공유 세그멘테이션 내에서 세그먼트(예: 의료)를 클릭하면 표시되는 사용자는 보고 있는 작업 공간과 연관된 파티션의 사람일 뿐입니다.
      * 작업 공간 1(WS1)에서 세그멘테이션을 만들고 WS2 및 WS1과 공유하면 WS2에 대한 파티션에 액세스할 수 없으면 세그멘테이션을 다시 계산하지 않습니다.
      * 파티션이 제한된 작업 공간에서 세그멘테이션을 만든 다음 다른 작업 공간과 공유하는 경우 공유 세그멘테이션을 받은 해당 작업 영역은 서로 겹치는 경우에만 표시됩니다.


>[!NOTE]
>
>이 규칙들 중 일부는 약간 복잡합니다. 시작하는 가장 쉬운 방법은 특정 사용자와 테스트하는 것입니다. 항상 새로운 세그먼트를 만들고 이전 세그먼트를 제거할 수 있습니다.

## 예제 시나리오 {#example-scenarios}

![](assets/share-segmentations-across-workspaces-and-partitions-1.png)

![](assets/share-segmentations-across-workspaces-and-partitions-2.png)

## 세그멘테이션 공유 {#share-a-segmentation}

1. 로 이동합니다. **데이터베이스**.

   ![](assets/share-segmentations-across-workspaces-and-partitions-3.png)

1. 마우스 오른쪽 단추 클릭 **세그먼테이션** 을(를) 선택합니다. **새 폴더**.

   ![](assets/share-segmentations-across-workspaces-and-partitions-4.png)

1. 작업 공간에서 공유할 폴더의 이름을 지정합니다(예: 세그먼트 공유)를 클릭하고 **만들기**.

   ![](assets/share-segmentations-across-workspaces-and-partitions-5.png)

1. 공유할 세분화를 폴더로 이동합니다.

   ![](assets/share-segmentations-across-workspaces-and-partitions-6.png)

1. 폴더를 마우스 오른쪽 단추로 클릭하고 를 선택합니다. **폴더 공유**.

   ![](assets/share-segmentations-across-workspaces-and-partitions-7.png)

1. 폴더를 공유할 작업 영역을 선택합니다. 클릭 **저장**.

   ![](assets/share-segmentations-across-workspaces-and-partitions-8.png)

   >[!NOTE]
   >
   >대화 상자에는 볼 수 있는 권한이 있는 작업 공간이 표시됩니다. 따라서 Marketo에서는 모든 작업 공간 및 분할 영역에 대한 가시성이 있는 기본 작업 공간에서 세그먼트를 만들고 공유하는 것이 좋습니다.

원래 폴더는 다른 작업 공간과 공유되었음을 나타내는 화살표로 데이터베이스 트리에 표시됩니다. 공유 작업 영역에서 폴더 컨텐츠가 다른 작업 공간에서 공유되고 읽기 전용임을 나타내는 잠금이 폴더로 표시됩니다.
