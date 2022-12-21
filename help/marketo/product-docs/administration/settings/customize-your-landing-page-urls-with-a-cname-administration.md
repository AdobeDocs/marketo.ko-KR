---
unique-page-id: 2360189
description: CNAME(관리)을 사용하여 랜딩 페이지 URL 사용자 지정 - Marketo 문서 - 제품 설명서
title: CNAME(관리)을 사용하여 랜딩 페이지 URL을 사용자 지정합니다
exl-id: a5aa1c76-15f7-4e8c-a736-77c79f65c368
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '251'
ht-degree: 0%

---

# CNAME(관리)을 사용하여 랜딩 페이지 URL을 사용자 지정합니다 {#customize-your-landing-page-urls-with-a-cname-administration}

Marketo이 랜딩 페이지를 호스팅하지만 회사를 위해 URL을 사용자 지정해야 합니다.

>[!NOTE]
>
>CNAME 없음:
>
>https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html
>
>브랜드 CNAME:
>
>https://go **사용자 회사**.com/UnsuscribePage.html

>[!NOTE]
>
>**관리 권한 필요**

준비시켜!

1. CNAME을 선택합니다.

   URL의 앞부분이에요. 예:

   * **go**.YourCompany.com/NameOfPage.html
   * **info**.YourCompany.com/NameOfPage.html
   * **페이지**.YourCompany.com/NameOfPage.html

   한 단어(더하기 YourCompany.com)는 CNAME이라고 합니다. 나중에 이것을 쓰셔야 하니까 메모해 주세요.

1. 계정 문자열을 찾습니다.

1. 로 이동합니다. **관리** 영역을 클릭하고 **랜딩 페이지**.

   ![](assets/image2014-9-16-13-3a9-3a44.png)

1. 아래에 **랜딩 페이지** 탭에서 설정 섹션에서 계정 문자열을 복사합니다.

   ![](assets/image2014-9-16-13-3a9-3a57.png)

1. 나중에 필요하실 테니 메모해 주세요.

1. IT에 요청 보내기.

1. IT 직원에게 다음 CNAME(Replace the word)을 설정하도록 요청합니다 [CNAME] 및 [계정 문자열] 이전 단계의 텍스트를 사용하는 경우):

   [CNAME].YourCompany.com > [계정 문자열].mktoweb.com

1. CNAME 설정을 완료합니다.

1. IT에서 CNAME을 만들면 다음 위치로 이동합니다. **관리** 을(를) 클릭합니다. **랜딩 페이지**.

   ![](assets/image2014-9-16-13-3a10-3a14.png)

1. 아래에 **설정** 섹션을 클릭합니다. **편집**.

   ![](assets/image2014-9-16-13-3a10-3a31.png)

1. 에 CNAME을 입력합니다. **랜딩 페이지의 도메인 이름**&#x200B;를 입력합니다. **대체 페이지**&#x200B;를 입력합니다. **홈페이지**&#x200B;를 클릭하고 **저장**.

   ![](assets/image2014-9-16-13-3a10-3a45.png)

Marketo 랜딩 페이지를 사용할 수 없는 경우 대체 페이지에서 사람들이 리디렉션됩니다.

잘했어! 이제 랜딩 페이지가 회사 도메인으로 브랜딩됩니다.
