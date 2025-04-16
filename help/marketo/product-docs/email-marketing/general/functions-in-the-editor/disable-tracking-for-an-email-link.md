---
unique-page-id: 1900579
description: 이메일 링크 추적 비활성화 - Marketo 문서 - 제품 설명서
title: 이메일 링크 추적 비활성화
exl-id: 841ef605-1664-4457-bc83-50bbe5d44853
feature: Email Editor
source-git-commit: ac2f8bf38b32344dd9414cf3611b69747e3587d4
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---

# 이메일 링크 추적 비활성화 {#disable-tracking-for-an-email-link}

전자 메일의 링크에서 **Marketo 추적 URL**&#x200B;을(를) 활성화하지 않으려는 경우가 있습니다. 이 기능은 대상 페이지가 URL 매개 변수를 지원하지 않아 링크가 끊어질 수 있는 경우에 유용합니다.

또한 365일 전 **및** 동안 전자 메일이 전송되었으며 지난 180일 동안 아무도 해당 링크를 클릭하지 않은 경우 Marketo Engage이 데이터베이스에서 URL로 가는 경로를 프룬하므로 링크가 끊어집니다. 따라서 링크를 영구적으로 유지해야 하는 경우 추적을 비활성화해야 합니다.

1. 이메일을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/one-7.png)

1. 링크가 포함된 편집 가능 섹션을 두 번 클릭합니다.

   ![](assets/two-6.png)

1. 해당 링크를 클릭한 다음 **링크 삽입/편집** 단추를 클릭합니다.

   ![](assets/three-6.png)

1. 링크 편집 팝업에서 **링크 추적** 확인란의 선택을 취소합니다.

   ![](assets/four-4.png)

1. **mkt_tok 포함**&#x200B;이 사라집니다. **적용**&#x200B;을 클릭합니다.

   ![](assets/five-3.png)

   >[!TIP]
   >
   >**mkt_tok 포함**&#x200B;만 선택을 취소해도 링크가 계속 추적될 수 있지만, 리디렉션 후 대상 URL에는 mkt_tok 쿼리 문자열 매개 변수가 포함되지 않습니다. 이 매개 변수는 Marketo 랜딩 페이지 및 Munchkin에서 개인 활동을 적절히 추적하기 위해(예: 개인이 이메일에서 가입 해지하는 경우) 사용합니다. 매개 변수가 있기 때문에 웹 사이트에서 이상한 동작이 보이지 않는 한 이 기능을 사용하지 않아야 합니다.

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-17-22-3a25-3a20.png)

   >[!CAUTION]
   >
   >전자 메일 서식 파일 또는 전자 메일의 [텍스트 버전](/help/marketo/product-docs/email-marketing/general/creating-an-email/edit-the-text-version-of-an-email.md){target="_blank"}에서 링크 클릭 추적을 비활성화하려면 다음 예제와 같이 문자열의 끝이 아닌 *시작*&#x200B;에 `mktNoTrack`을(를) 추가하십시오. `<a class="mktNoTrack" href="https://www.mywebsite.com">This link does not have tracking</a>` 그렇지 않으면 링크가 사라질 수 있습니다. 위의 코드 구현에 도움이 필요한 경우 웹 개발자에게 문의하십시오.
