---
unique-page-id: 2359746
description: CNAME으로 랜딩 페이지 URL 사용자 지정 - Marketo 문서 - 제품 설명서
title: CNAME으로 랜딩 페이지 URL 사용자 지정
exl-id: 2cd87785-61e5-46cd-b1e0-6fbc145014d4
feature: Landing Pages
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# CNAME으로 랜딩 페이지 URL 사용자 지정 {#customize-your-landing-page-urls-with-a-cname}

Marketo이 랜딩 페이지를 호스팅하지만 URL을 완전히 사용자 지정할 수 있습니다. CNAME 제외:

`https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html`

표시되는 방식:

`https://go.YourCompany.com/UnsubscribePage.html`

## CNAME 선택 {#choose-a-cname}

랜딩 페이지의 URL 시작 부분에 사용할 단어를 선택합니다. 그것은 단지 한 단어이고 상대적으로 짧아야 한다. 예:

* go.YourCompany.com/NameOfPage.html
* info.YourCompany.com/NameOfPage.html
* pages.YourCompany.com/NameOfPage.html

한 단어(더하기 YourCompany.com)를 CNAME이라고 합니다. 나중에 필요할 테니 메모해 두십시오.

## Munchkin ID 찾기 {#find-your-munchkin-id}

1. **관리자** 영역으로 이동합니다.

   ![](assets/customize-your-landing-page-urls-with-a-cname-1.png)

1. **내 계정**&#x200B;을 클릭합니다.

   ![](assets/customize-your-landing-page-urls-with-a-cname-2.png)

   >[!NOTE]
   >
   >**관리자 권한 필요**

1. 아래로 스크롤하여 &quot;지원 정보&quot;를 확인하고 Munchkin ID를 복사합니다.

   ![](assets/customize-your-landing-page-urls-with-a-cname-3.png)

## IT에 요청 보내기 {#send-request-to-it}

IT 직원에게 다음 CNAME을 설정하도록 요청하십시오. ([CNAME] 및 [Munchkin ID] 단어를 이전 단계의 텍스트로 바꾸십시오.)

[CNAME].YourCompany.com > [Munchkin ID].mktoweb.com

## CNAME 설정 완료 {#complete-cname-setup}

1. IT에서 CNAME을 만들었으면 **관리자** 영역으로 이동하십시오.

   ![](assets/customize-your-landing-page-urls-with-a-cname-4.png)

1. **랜딩 페이지**&#x200B;를 클릭합니다.

   ![](assets/customize-your-landing-page-urls-with-a-cname-5.png)

1. **설정** 섹션에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/customize-your-landing-page-urls-with-a-cname-6.png)

1. **랜딩 페이지의 도메인 이름**&#x200B;에 CNAME을 입력하고, **대체 페이지**&#x200B;를 입력하고, **홈 페이지**&#x200B;를 입력하고, **저장**&#x200B;을(를) 클릭합니다.

   ![](assets/customize-your-landing-page-urls-with-a-cname-7.png)

>[!NOTE]
>
>Marketo 랜딩 페이지를 사용할 수 없는 경우, 대체 페이지는 페이지 리드를으로 리디렉션됩니다.

잘했어! 이제 랜딩 페이지의 브랜드가 회사 도메인으로 지정되었습니다.
