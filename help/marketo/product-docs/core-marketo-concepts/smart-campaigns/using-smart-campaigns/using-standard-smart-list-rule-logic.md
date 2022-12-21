---
unique-page-id: 1147001
description: 표준 Smart List 규칙 논리 사용 - Marketo 문서 - 제품 설명서
title: 표준 스마트 목록 규칙 논리 사용
exl-id: 9befaa81-e50c-47d3-9edf-220cfadd00f6
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# 표준 스마트 목록 규칙 논리 사용 {#using-standard-smart-list-rule-logic}

Campaign 스마트 목록을 작성할 때 &quot;필터 사용&quot; 옵션을 알아차렸을 수 있습니다. 이 설정을 사용하면 필터를 AND 또는 OR 연산자로 평가해야 하는지 여부를 결정할 수 있습니다.

![](assets/image2014-9-22-14-3a12-3a42.png)

>[!NOTE]
>
>스마트 목록 규칙 논리 변경은 필터에만 적용됩니다. **not** 트리거 .

위의 설정이 ALL로 설정되어 있어도 트리거는 항상 OR로 평가됩니다.  다음은 한 예입니다.

![](assets/image2014-9-22-14-3a12-3a57.png)

위의 스마트 목록은 다음과 같습니다.

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

따라서, 만약 누군가가 그 양식을 작성한다면 **또는** 페이지를 방문하면 캠페인이 다음을 기준으로 해당 사람을 평가합니다 **모두** 또는 **임의** 사용된 설정에 따라 다음 필터를 확인하십시오.

>[!MORELIKETHIS]
>
>[고급 스마트 목록 규칙 논리 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md)
