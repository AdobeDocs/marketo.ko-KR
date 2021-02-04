---
unique-page-id: 2359746
description: CNAME - Marketing To Docs - 제품 설명서를 사용하여 랜딩 페이지 URL 사용자 정의
title: CNAME으로 랜딩 페이지 URL 사용자 정의
translation-type: tm+mt
source-git-commit: 2969e6f94f5fd781e2167ae2aa8680bb8d134754
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 0%

---


# 랜딩 페이지 URL을 CNAME {#customize-your-landing-page-urls-with-a-cname}으로 사용자 지정

Marketing에서 랜딩 페이지를 호스트하지만 URL을 완전히 사용자 지정할 수 있습니다. CNAME이 없는 모양:

`http://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html`

모양:

`http://go.YourCompany.com/UnsubscribePage.html`

## CNAME {#choose-a-cname} 선택

랜딩 페이지의 URL 시작 부분에서 이동할 단어를 선택합니다. 그것은 단지 한 단어이고 비교적 짧아야 합니다. 예:

* go.YourCompany.com/NameOfPage.html
* info.YourCompany.com/NameOfPage.html
* pages.YourCompany.com/NameOfPage.html

한 단어(더하기 YourCompany.com)를 CNAME이라고 합니다. 나중에 이걸 써야 하니까 메모해 주세요.

## 계정 문자열 {#find-your-account-string} 찾기

1. **관리** 영역으로 이동하여 **랜딩 페이지**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-18-16-3a2-3a45.png)

   >[!NOTE]
   >
   >**관리자 권한 필요**

1. **랜딩** **페이지** 탭에서 **계정** **Settings** 섹션의 **문자열을 복사합니다.**

   ![](assets/image2014-9-18-16-3a44-3a12.png)

1. 나중에 필요하실 테니 메모해 주세요

## IT {#send-request-to-it}에 요청 보내기

IT 직원에게 다음 CNAME을 설정하도록 요청합니다.(단어 [CNAME] 및 [ACCOUNT STRING]을 이전 단계의 텍스트로 바꿉니다.)

[CNAME].YourCompany.com >  [ACCOUNT STRING].mktoweb.com

## 전체 CNAME 설정 {#complete-cname-setup}

1. IT 팀에서 CNAME을 만들었으면 **관리**&#x200B;로 이동하여 **랜딩 페이지**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-18-17-3a15-3a11.png)

1. **설정** 섹션에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-18-17-3a15-3a18.png)

1. 랜딩 페이지의 도메인 이름&#x200B;**에 CNAME을 입력하고**&#x200B;폴백 페이지&#x200B;**를 입력한 다음**&#x200B;홈 페이지&#x200B;**를 입력하고**&#x200B;저장&#x200B;**을 클릭합니다.**

   ![](assets/image2014-9-18-17-3a15-3a25.png)

>[!NOTE]
>
>마케팅 랜딩 페이지를 사용할 수 없는 경우 페이지 리드가 리디렉션되는 폴백 페이지가 됩니다.

잘했어! 이제 랜딩 페이지가 회사 도메인으로 브랜드화됩니다.
