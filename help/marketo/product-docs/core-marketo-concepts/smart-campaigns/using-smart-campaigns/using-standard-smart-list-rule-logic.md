---
unique-page-id: 1147001
description: 표준 스마트 목록 규칙 논리 사용 - Marketo 문서 - 제품 설명서
title: 표준 스마트 목록 규칙 논리 사용
exl-id: 9befaa81-e50c-47d3-9edf-220cfadd00f6
feature: Smart Campaigns
source-git-commit: 47bc93665a7efa0d64cd4d5f34b868895d407527
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# 표준 스마트 목록 규칙 논리 사용 {#using-standard-smart-list-rule-logic}

캠페인 스마트 목록을 빌드할 때 &quot;필터 사용&quot; 옵션이 표시되었을 수 있습니다. 이 설정을 사용하면 AND 또는 OR 연산자로 필터를 평가해야 하는지 여부를 결정할 수 있습니다.

![](assets/using-standard-smart-list-rule-logic-1.png)

>[!NOTE]
>
>스마트 목록 규칙 논리 변경은 필터 _not_ 트리거에만 적용됩니다.

위의 설정이 ALL로 설정되어 있더라도 트리거는 항상 OR로 평가됩니다. 예를 들면 다음과 같습니다.

![](assets/using-standard-smart-list-rule-logic-2.png)

위의 스마트 목록(단어):

```box
IF person fills out Great Form
OR
IF person visits Keith's Landing Page 
AND 
Industry is Energy 
AND 
Country is US 
THEN follow the campaign's flow step(s)
```

따라서 사용자가 _또는_ 양식을 작성하여 페이지를 방문하는 경우 캠페인은 사용된 설정에 따라 후속 필터의 _모두_ 또는 _모두_&#x200B;를 기반으로 해당 사용자를 평가합니다.

>[!MORELIKETHIS]
>
>[고급 스마트 목록 규칙 논리 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md){target="_blank"}
