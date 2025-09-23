---
unique-page-id: 11380732
description: 계정 필터 - Marketo 문서 - 제품 설명서
title: 계정 필터
exl-id: a359f53b-c0a0-4b46-bad0-2840ba668892
feature: Target Account Management
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '152'
ht-degree: 1%

---

# [!UICONTROL Account Filters] {#account-filters}

새로운 계정 중심 필터를 사용하여 지정된 계정 및 해당 계정 내의 가상 사용자를 식별하고 참여합니다.

## TAM 필터 {#tam-filters}

1. 스마트 캠페인을 선택하고 **[!UICONTROL Smart List]**&#x200B;을(를) 클릭합니다.

   ![](assets/one.png)

1. **+**&#x200B;을(를) 클릭하여 **[!UICONTROL Account Filters]** 폴더를 확장합니다.

   ![](assets/two.png)

1. 사용할 필터를 캔버스로 드래그합니다.

   ![](assets/three.png)

## [!UICONTROL Member of Account List] {#member-of-account-list}

이 필터를 사용하려면 **[!UICONTROL Account List]** 드롭다운을 클릭하세요...

![](assets/four.png)

...및 원하는 계정 목록을 선택합니다.

![](assets/five.png)

>[!NOTE]
>
>[!UICONTROL Member of Account List] 필터의 경우 한정자 &quot;[!UICONTROL is]&quot;이(가) 하나만 있습니다. &quot;is not&quot; 및 &quot;is any&quot;와 같은 추가적인 한정자는 사용할 수 없습니다.

## [!UICONTROL Member of Named Account] {#member-of-named-account}

먼저 구분자를 선택합니다. 특정 명명된 계정의 경우 **[!UICONTROL is]**, 명명된 계정의 경우 **[!UICONTROL is any]**&#x200B;입니다.

![](assets/six.png)

명명된 계정 드롭다운을 클릭합니다.

![](assets/seven.png)

...및 원하는 명명된 계정을 선택합니다.

![](assets/eight.png)

&quot;[!UICONTROL is any]&quot; 한정자를 사용하는 경우 [제약 조건](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md)을 사용하여 검색 결과를 좁힐 수 있습니다. 원하는 만큼 추가합니다.

![](assets/nine.png)

단일 최상위 계정의 구성원만 원하는 경우 &quot;[!UICONTROL Include Children]&quot;을(를) **[!UICONTROL false]**(으)로 설정하십시오. 모든 하위 계정의 구성원을 원하는 경우 **[!UICONTROL true]**&#x200B;을(를) 선택하십시오.

![](assets/ten.png)

>[!MORELIKETHIS]
>
>[계정 트리거](/help/marketo/product-docs/target-account-management/engage/account-triggers.md)
