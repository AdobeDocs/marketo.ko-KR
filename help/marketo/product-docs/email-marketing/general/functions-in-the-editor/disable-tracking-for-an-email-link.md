---
unique-page-id: 1900579
description: 이메일 링크에 대한 추적 비활성화 - 마케팅 문서 - 제품 설명서
title: 이메일 링크에 대한 추적 비활성화
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 0%

---


# 이메일 링크에 대한 추적 비활성화 {#disable-tracking-for-an-email-link}

이메일의 링크에서 **마케팅** 추적 URL을 활성화하지 않으려는 경우가 있습니다. 이 기능은 대상 페이지가 URL 매개 변수를 지원하지 않고 링크가 끊어질 수 있는 경우에 유용합니다.

>[!NOTE]
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](/help/marketo/getting-started/updates-to-marketo-terminology.md)내용

1. 이메일을 선택하고 **초안 편집** 을 **클릭합니다**.

   ![](assets/one-7.png)

1. 링크가 포함된 편집 가능 섹션을 두 번 클릭합니다.

   ![](assets/two-6.png)

1. 해당 링크를 클릭한 다음 링크 **삽입/편집** 단추를 클릭합니다.

   ![](assets/three-6.png)

1. [링크 편집] 팝업에서 [링크 **추적] 확인란의 선택을** 취소합니다.

   ![](assets/four-4.png)

1. mkt_tok **포함 상자가** 사라집니다. 적용을 **클릭합니다**.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >mkt_tok만 **포함을** 선택 해제하면 여전히 링크를 추적할 수 있지만, 리디렉션 후 대상 URL에는 mkt_tok 쿼리 문자열 매개 변수가 포함되지 않습니다. 이 매개 변수는 Marketing Landing Pages 및 Munchkin에서 사용하여 개인 활동을 적절히 추적합니다(예를 들어, 사용자가 이메일에 가입하지 않은 경우). 매개 변수가 있기 때문에 웹 사이트에서 이상한 동작을 보지 않는 한 이 기능을 사용하지 마십시오.

1. 저장을 **클릭합니다**.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!TIP]
   >
   >이메일 **템플릿의 링크에 대한 클릭 추적을 비활성화하시겠습니까**? 다음 형식을 사용하십시오.
   >`<a class="mktNoTrack" href="http://www.mywebsite.com">This link does not have tracking</a>`\
   >이 기능의 구현에 도움이 필요한 경우 웹 개발자에게 문의하십시오.

좋아! 이제 링크에 대한 추적을 비활성화했습니다.
