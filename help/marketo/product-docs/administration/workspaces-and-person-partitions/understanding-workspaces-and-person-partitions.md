---
unique-page-id: 2360309
description: 작업 영역 및 개인 파티션 이해 - 마케팅 문서 - 제품 설명서
title: 작업 영역 및 개인 파티션 이해
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '562'
ht-degree: 0%

---


# 작업 영역 및 개인 파티션 이해 {#understanding-workspaces-and-person-partitions}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

## 작업 영역 {#workspaces}

>[!CAUTION]
>
>작업 영역을 설정하기가 복잡할 수 있습니다.  Marketing [Support에](http://support.marketo.com/) 문의하여 귀하에게 적합한지 확인하십시오.

작업 영역은 프로그램, 랜딩 페이지, 이메일 등과 같은 마케팅 자산을 보유하는 Marketing의 별도의 영역입니다. 여러 사람이 사용할 수 있습니다. 각 사용자는 하나 이상의 작업 영역에 액세스할 수 있습니다.

>[!NOTE]
>
>**예**
>
>작업 영역을 사용할 수 있는 몇 가지 이유:
>
>* 지역:유럽, 아시아 및 북미 마케팅 부서의 각 작업 영역
>* 사업부:Quicken, Quickbooks 및 TurboTax의 각 구성 요소

>
>
각각의 경우 마케팅 자산이 완전히 다르기 때문에 구분됩니다. 마케팅 자산을 공유하는 경우 작업 영역이 사용자에게 적합한 도구가 아닐 수 있습니다.

>[!NOTE]
>
>**딥 다이브**
>
>새로운 작업 영역을 [만드는 방법을 알아봅니다](create-a-new-workspace.md).

## 작업 영역 간 공유 {#sharing-across-workspaces}

다양한 작업 영역에서 에셋을 공유하는 방법을 살펴봅니다. 원하는 모든 사용자에게 동일하게 작동합니다.이 예는 세그먼테이션을 보여줍니다.

>[!NOTE]
>
>자산이 들어 있는 상위 폴더는 하위 폴더가 아니라 공유할 수 있는 유일한 폴더입니다.

1. 새 폴더를 만듭니다.

   ![](assets/one.png)

1. 공유할 폴더의 이름을 지정합니다.

   ![](assets/two.png)

1. 공유할 자산을 폴더로 이동합니다.

   ![](assets/three.png)

1. 폴더를 마우스 오른쪽 단추로 클릭하고 폴더 **공유를 선택합니다**.

   ![](assets/four.png)

1. 폴더를 공유할 작업 영역을 선택하고 [저장]을 **클릭합니다**. 폴더 공유 대화 상자에는 볼 수 있는 권한이 있는 작업 영역만 표시됩니다.

   ![](assets/image2015-5-27-11-3a6-3a40.png)

   >[!NOTE]
   >
   >원래 폴더에는 공유 폴더임을 나타내는 작은 녹색 화살표가 표시됩니다. 공유 작업 영역에서 폴더에 읽기 전용이라는 자물쇠가 생깁니다.

이러한 항목을 작업 영역 간에 공유할 수 있습니다.

* 이메일 템플릿
* 랜딩 페이지 템플릿
* 모델
* 스마트 캠페인
* [스마트 목록](../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/reference-a-list-or-smart-list-across-workspaces.md)
* [세분화](share-segmentations-across-workspaces-and-partitions.md)
* 코드 조각

## 작업 영역 간 복제 {#cloning-across-workspaces}

템플릿이 아닌 에셋의 경우 프로그램 내에서 로컬 에셋으로 복제하는 것이 가장 좋습니다.  적절한 액세스 수준을 통해 이러한 자산을 다른 작업 영역으로 드래그하여 놓을 수 있습니다.

* 프로그램
* 이메일
* 랜딩 페이지
* Forms

>[!NOTE]
>
>템플릿이 있는 자산을 복제하는 경우 이러한 템플릿은 대상 작업 공간과 공유해야 합니다.

## 다른 작업 영역으로 자산 이동 {#moving-assets-to-other-workspaces}

에셋을 새 작업 영역으로 이동하려면 해당 에셋을 폴더에 넣고 폴더를 다른 작업 영역으로 드래그합니다.

>[!NOTE]
>
>한 작업 영역의 구성원이 포함된 프로그램을 다른 작업 영역으로 이동할 수 없습니다.

## 개인 파티션 {#person-partitions}

개인 파티션은 별도의 데이터베이스와 같습니다. 각 분할 영역에는 데이터 중복 제거 또는 다른 분할 영역과 혼합되지 않는 고유한 사용자가 있습니다. 동일한 이메일 주소로 중복 레코드가 필요할 수 있는 비즈니스 사용 사례가 있다고 생각되는 경우 [Marketing Support에 문의하십시오](http://support.marketo.com).

다음 구성에서 작업 [영역에 개인 파티션을](create-a-new-workspace.md) 할당할 수 있습니다.

* 한 사람 분할 영역(1:1)
* 여러 개인 파티션에 하나의 작업 영역(1:x)
* 하나의 개인 파티션에 많은 작업 영역(x:1)

>[!NOTE]
>
>**예**
>
>개인 파티션을 사용하는 이유:
>
>* 작업 영역에는 서로 다른 에셋이 있을 뿐만 아니라 다른 사람도 공유하지 않습니다
>* 다른 비즈니스 이유로 중복

>



>[!CAUTION]
>
>개인 파티션은 상호 작용하지 않으므로 설정할 때는 주의하십시오.

>[!NOTE]
>
>**딥 다이브**
>
> 개인 파티션 [을 만드는 방법을 알아봅니다](create-a-person-partition.md).

