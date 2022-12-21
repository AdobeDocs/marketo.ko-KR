---
unique-page-id: 2360309
description: 작업 공간 및 개인 파티션 이해 - Marketo 문서 - 제품 설명서
title: 작업 공간 및 개인 분할 영역 이해
exl-id: 27d00a0d-ebf1-4dff-b41e-1644ec9dbd28
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '514'
ht-degree: 0%

---

# 작업 공간 및 개인 분할 영역 이해 {#understanding-workspaces-and-person-partitions}

## 작업 공간 {#workspaces}

>[!CAUTION]
>
>작업 공간은 설정하기 복잡할 수 있습니다. 연락처 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support) 그들이 당신에게 맞는지를 알아내기 위해

작업 공간은 프로그램, 랜딩 페이지, 이메일 등과 같은 마케팅 자산을 보유하는 Marketo의 별도의 영역입니다. 여러 사용자가 사용할 수 있습니다. 각 사용자는 하나 이상의 작업 공간에 액세스할 수 있습니다.

>[!NOTE]
>
>**예**
>
>작업 공간을 사용할 수 있는 몇 가지 이유는 다음과 같습니다.
>
>* 지역: 유럽, 아시아 및 북미 마케팅 부서는 각각 작업 공간을 확보합니다
>* 비즈니스 단위: Quicken, Quickbook 및 TurboTax에서 작업 공간을 얻을 수 있습니다
>
>각 경우 마케팅 자산이 완전히 다르기 때문에 구분됩니다. 마케팅 자산을 공유하는 경우 작업 공간이 사용자에게 적합한 도구가 아닐 수 있습니다.

>[!NOTE]
>
>만드는 방법 알아보기 [새 작업 공간 만들기](/help/marketo/product-docs/administration/workspaces-and-person-partitions/create-a-new-workspace.md).

## 작업 공간 간 공유 {#sharing-across-workspaces}

작업 공간에서 자산을 공유하는 방법은 다음과 같습니다. 공유하려는 모든 항목에 대해서도 동일하게 작동합니다. 이 예는 세그먼트를 보여줍니다.

>[!NOTE]
>
>자산이 들어 있는 상위 폴더는 하위 폴더가 아니라 공유할 수 있는 유일한 폴더입니다.

1. 새 폴더를 만듭니다.

   ![](assets/one.png)

1. 공유할 폴더의 이름을 지정합니다.

   ![](assets/two.png)

1. 공유할 자산을 폴더로 이동합니다.

   ![](assets/three.png)

1. 폴더를 마우스 오른쪽 단추로 클릭하고 를 선택합니다. **폴더 공유**.

   ![](assets/four.png)

1. 폴더를 공유할 작업 영역을 선택하고 **저장**. 폴더 공유 대화 상자에는 볼 수 있는 권한이 있는 작업 영역만 표시됩니다.

   ![](assets/image2015-5-27-11-3a6-3a40.png)

   >[!NOTE]
   >
   >이제 원래 폴더에는 공유되었음을 나타내는 작은 녹색 화살표가 있습니다. 공유된 작업 영역에서 폴더에는 읽기 전용임을 나타내는 자물쇠가 있습니다.

작업 공간에서 이러한 항목을 공유할 수 있습니다.

* 이메일 템플릿
* 랜딩 페이지 템플릿
* 모델
* 스마트 캠페인
* [스마트 목록](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/reference-a-list-or-smart-list-across-workspaces.md)
* [세그먼테이션](/help/marketo/product-docs/administration/workspaces-and-person-partitions/share-segmentations-across-workspaces-and-partitions.md)
* 코드 조각

## 작업 공간 간 복제 {#cloning-across-workspaces}

템플릿이 아닌 자산의 경우 프로그램 내의 로컬 자산으로 복제하는 것이 가장 좋습니다.  적절한 액세스 수준을 사용하여 이러한 자산을 다른 작업 공간으로 끌어서 놓을 수 있습니다.

* 프로그램
* 이메일
* 랜딩 페이지
* Forms

>[!NOTE]
>
>템플릿이 있는 자산을 복제할 때 이러한 템플릿은 대상 작업 공간과 공유해야 합니다.

## 자산을 다른 작업 공간으로 이동 {#moving-assets-to-other-workspaces}

자산을 새 작업 공간으로 이동하려면 해당 자산을 폴더에 넣고 폴더를 다른 작업 공간으로 드래그합니다.

>[!NOTE]
>
>한 작업 공간에서 다른 작업 공간으로 멤버를 포함하는 프로그램을 이동할 수 없습니다.

## 개인 파티션 {#person-partitions}

개인 파티션은 별도의 데이터베이스와 같습니다. 각 파티션에는 중복 제거 또는 다른 파티션과 혼합되지 않는 고유한 사용자가 있습니다. 동일한 전자 메일 주소를 사용하여 중복 레코드를 만들어야 하는 비즈니스 사용 사례가 있을 경우, [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support).

개인 파티션을  [작업 공간](create-a-new-workspace.md) 다음 구성에서 다음을 수행합니다.

* 하나의 개인 파티션에 대한 하나의 작업 영역(1:1)
* 하나의 작업 영역 - 여러 개인 분할 영역(1:x)
* 하나의 개인 파티션에 여러 작업 공간(x:1)

>[!NOTE]
>
>개인 파티션을 사용하는 이유:
>
>* 작업 영역에는 서로 다른 자산뿐만 아니라 다른 사람도 공유하지 않습니다
>* 다른 비즈니스 이유로 중복 항목을 사용할 수 있습니다


>[!CAUTION]
>
>개인 파티션은 서로 상호 작용하지 않으므로 설정할 때 주의하십시오.

>[!NOTE]
>
>방법 알아보기 [개인 파티션 만들기](/help/marketo/product-docs/administration/workspaces-and-person-partitions/create-a-person-partition.md).
