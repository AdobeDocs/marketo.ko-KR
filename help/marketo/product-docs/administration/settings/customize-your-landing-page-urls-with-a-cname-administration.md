---
unique-page-id: 2360189
description: CNAME(관리)으로 랜딩 페이지 URL 사용자 정의 - Marketo Docs - 제품 설명서
title: CNAME으로 랜딩 페이지 URL 사용자 지정(관리)
exl-id: a5aa1c76-15f7-4e8c-a736-77c79f65c368
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '251'
ht-degree: 0%

---

# 랜딩 페이지 URL을 CNAME(관리) {#customize-your-landing-page-urls-with-a-cname-administration}으로 사용자 지정

Marketo이 랜딩 페이지를 호스트하지만 URL은 회사에 맞게 사용자 정의되어야 합니다.

>[!NOTE]
>
>CNAME 없음:
>
>https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html
>
>브랜드 CNAME:
>
>https://go을 참조하십시오.**회사**.com/UnsuscribePage.html

>[!NOTE]
>
>**관리자 권한 필요**

준비시켜!

1. CNAME을 선택합니다.

   URL의 앞부분입니다. 예:

   * **이동**.YourCompany.com/NameOfPage.html
   * **info**.YourCompany.com/NameOfPage.html
   * **페이지**.YourCompany.com/NameOfPage.html

   한 단어(더하기 YourCompany.com)를 CNAME이라고 합니다. 나중에 이것을 필요하실 테니 메모해 주세요.

1. 계정 문자열을 찾습니다.

1. **관리** 영역으로 이동하여 **랜딩 페이지**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-16-13-3a9-3a44.png)

1. **랜딩 페이지** 탭의 설정 섹션에서 계정 문자열을 복사합니다.

   ![](assets/image2014-9-16-13-3a9-3a57.png)

1. 나중에 필요하실 테니 메모해 주세요

1. IT로 요청 보내기.

1. IT 직원에게 다음 CNAME을 설정하도록 요청합니다(단어 [CNAME] 및 [ACCOUNT STRING]을 이전 단계의 텍스트로 바꾸십시오).

   [CNAME].YourCompany.com >  [ACCOUNT STRING].mktoweb.com

1. 전체 CNAME 설정.

1. IT 팀에서 CNAME을 만들었으면 **관리**&#x200B;로 이동하여 **랜딩 페이지**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-16-13-3a10-3a14.png)

1. **설정** 섹션에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-16-13-3a10-3a31.png)

1. 랜딩 페이지의 도메인 이름&#x200B;**에 CNAME을 입력하고**&#x200B;폴백 페이지&#x200B;**를 입력한 다음**&#x200B;홈 페이지&#x200B;**를 입력하고**&#x200B;저장&#x200B;**을 클릭합니다.**

   ![](assets/image2014-9-16-13-3a10-3a45.png)

Marketo 랜딩 페이지를 사용할 수 없는 경우 대체 페이지가 사람들이 리디렉션되는 페이지입니다.

잘했어! 이제 랜딩 페이지가 회사 도메인으로 브랜드화됩니다.
