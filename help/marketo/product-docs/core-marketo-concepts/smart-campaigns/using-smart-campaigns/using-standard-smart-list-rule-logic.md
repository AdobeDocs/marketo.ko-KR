---
unique-page-id: 1147001
description: 표준 스마트 목록 규칙 논리 사용 - Marketo 문서 - 제품 설명서
title: 표준 스마트 목록 규칙 논리 사용
exl-id: 9befaa81-e50c-47d3-9edf-220cfadd00f6
feature: Smart Campaigns
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# 표준 스마트 목록 규칙 논리 사용 {#using-standard-smart-list-rule-logic}

캠페인 스마트 목록을 빌드할 때 &quot;필터 사용&quot; 옵션이 표시되었을 수 있습니다. 이 설정을 사용하면 AND 또는 OR 연산자로 필터를 평가해야 하는지 여부를 결정할 수 있습니다.

![](assets/image2014-9-22-14-3a12-3a42.png)

>[!NOTE]
>
>스마트 목록 규칙 논리 변경은 필터에만 적용되며, **아님** 트리거를 사용합니다.

위의 설정이 ALL로 설정되어 있더라도 트리거는 항상 OR로 평가됩니다.  예를 들면 다음과 같습니다.

![](assets/image2014-9-22-14-3a12-3a57.png)

위의 스마트 목록(단어):

```box
IF person fills out My Form
OR
IF person visits My Page 
AND 
Industry is Marketing 
AND 
Country is USA 
THEN follow the campaign's flow step(s)
```

따라서 사용자가 양식을 작성하는 경우 **또는** 이 페이지를 방문하면 캠페인은 다음을 기반으로 해당 사용자를 평가합니다 **모두** 또는 **임의** 사용된 설정에 따라 후속 필터.

>[!MORELIKETHIS]
>
>[고급 스마트 목록 규칙 논리 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md)
