---
unique-page-id: 1147001
description: 표준 스마트 목록 규칙 논리 사용 - 마케팅 문서 - 제품 설명서
title: 표준 스마트 목록 규칙 논리 사용
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 0%

---


# 표준 스마트 목록 규칙 논리 사용 {#using-standard-smart-list-rule-logic}

캠페인 스마트 목록을 빌드할 때 &quot;필터 사용&quot; 옵션을 알아보았을 수 있습니다. 이 설정을 사용하면 필터를 AND 또는 OR 연산자로 평가할지 여부를 결정할 수 있습니다.

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

![](assets/image2014-9-22-14-3a12-3a42.png)

>[!NOTE]
>
>스마트 목록 규칙 논리 변경은 트리거가 **아니라** 필터에만 적용됩니다.

위의 설정이 ALL으로 설정된 경우에도 트리거는 항상 OR으로 평가됩니다.  다음은 한 예입니다.

![](assets/image2014-9-22-14-3a12-3a57.png)

위의 단어:`<pre data-theme="Confluence">IF person fills out My Form OR IF person visits My Page AND Industry is Marketing AND Country is USA THEN follow the campaign's flow step(s)</pre>` 따라서 사용자가 양식을 채우거나 **** 페이지를 방문하는 경우 캠페인은 사용한 설정에 따라 다음 필터의 **all **또는 **any **를 기준으로 해당 사람을 평가합니다.

>[!MORELIKETHIS]
>
>* [고급 스마트 목록 규칙 논리 사용](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md)

>



