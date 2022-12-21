---
unique-page-id: 1900579
description: 이메일 링크에 대한 추적 비활성화 - Marketo 문서 - 제품 설명서
title: 이메일 링크에 대한 추적 비활성화
exl-id: 841ef605-1664-4457-bc83-50bbe5d44853
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---

# 이메일 링크에 대한 추적 비활성화 {#disable-tracking-for-an-email-link}

경우에 따라 **Marketo 추적 URL** 링크를 클릭합니다. 이 기능은 대상 페이지가 URL 매개 변수를 지원하지 않고 링크가 끊어질 수 있는 경우에 유용합니다.

1. 이메일을 선택하고 을(를) 클릭합니다 **초안 편집**.

   ![](assets/one-7.png)

1. 링크가 포함된 편집 가능한 섹션을 두 번 클릭합니다.

   ![](assets/two-6.png)

1. 해당 링크를 클릭한 다음 **링크 삽입/편집** 버튼을 클릭합니다.

   ![](assets/three-6.png)

1. 링크 편집 팝업에서 **추적 링크** 확인란을 선택합니다.

   ![](assets/four-4.png)

1. 다음 사항을 확인할 수 있습니다. **mkt_tok 상자 포함** 사라집니다. 클릭 **적용**.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >확인 취소 **mkt_tok 포함** 은 여전히 링크를 추적할 수 있도록 허용하지만, 리디렉션 후 대상 URL에 mkt_tok 쿼리 문자열 매개 변수가 포함되지 않습니다. 이 매개 변수는 Marketo 랜딩 페이지 및 Munchkin에서 개인 활동을 적절히 추적하기 위해 사용됩니다(사용자가 이메일에서 구독을 취소할 때 등). 매개 변수가 있어 웹 사이트에서 이상한 동작이 보이지 않는 경우 이 기능을 사용하지 않아야 합니다.

1. 클릭 **저장**.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!TIP]
   >
   >이메일에 있는 링크에 대한 클릭 추적을 비활성화하려고 합니다 **템플릿**? 다음 형식을 사용합니다.
   >`<a class="mktNoTrack" href="https://www.mywebsite.com">This link does not have tracking</a>`\
   >이 구현 도움말이 필요한 경우 웹 개발자에게 문의하십시오.

좋아! 이제 링크에 대한 추적을 비활성화했습니다.
