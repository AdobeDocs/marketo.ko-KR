---
unique-page-id: 1147001
description: 표준 스마트 목록 규칙 논리 사용 - 마케팅 문서 - 제품 설명서
title: 표준 스마트 목록 규칙 논리 사용
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---


# 표준 스마트 목록 규칙 논리 사용 {#using-standard-smart-list-rule-logic}

캠페인 스마트 목록을 빌드할 때 &quot;필터 사용&quot; 옵션이 눈에 띄었을 수 있습니다. 이 설정을 사용하면 필터를 AND 또는 OR 연산자로 평가해야 하는지 결정할 수 있습니다.

![](assets/image2014-9-22-14-3a12-3a42.png)

>[!NOTE]
>
>스마트 목록 규칙 논리를 변경하면 트리거가 **아니라** 필터에만 적용됩니다.

위의 설정이 모두(ALL)로 설정되어 있더라도 트리거는 항상 OR로 평가됩니다.  다음은 한 예입니다.

![](assets/image2014-9-22-14-3a12-3a57.png)

위의 고급 목록은 다음과 같습니다.`<pre data-theme="Confluence">IF person fills out My Form OR IF person visits My Page AND Industry is Marketing AND Country is USA THEN follow the campaign's flow step(s)</pre>` 따라서 사용자가 양식을 채우거나 페이지 **를** 방문하는 경우 캠페인은 사용된 설정에 따라 **all** 또는****의 후속 필터를 기준으로 해당 사람을 평가합니다.

>[!MORELIKETHIS]
>
>* [고급 스마트 목록 규칙 논리 사용](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md)

>



