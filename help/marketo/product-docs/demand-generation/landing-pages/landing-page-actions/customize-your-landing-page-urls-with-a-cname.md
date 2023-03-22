---
unique-page-id: 2359746
description: CNAME을 사용하여 랜딩 페이지 URL 사용자 지정 - Marketo 문서 - 제품 설명서
title: CNAME을 사용하여 랜딩 페이지 URL 사용자 지정
exl-id: 2cd87785-61e5-46cd-b1e0-6fbc145014d4
source-git-commit: 6c1699ce986608e8b9d991f21fd649f9330e3d12
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# CNAME을 사용하여 랜딩 페이지 URL 사용자 지정 {#customize-your-landing-page-urls-with-a-cname}

Marketo이 랜딩 페이지를 호스팅하더라도 URL을 완전히 사용자 지정할 수 있습니다. CNAME이 없는 것처럼 보이는 기능:

`https://na-sj02.marketo.com/lp/mktodemoaccount126/UnsubscribePage.html`

모양:

`https://go.YourCompany.com/UnsubscribePage.html`

## CNAME 선택 {#choose-a-cname}

랜딩 페이지의 URL 시작 부분에서 이동할 단어를 선택합니다. 그것은 단지 한 단어이고 비교적 짧아야 합니다. 예:

* go.YourCompany.com/NameOfPage.html
* info.YourCompany.com/NameOfPage.html
* pages.YourCompany.com/NameOfPage.html

한 단어(더하기 YourCompany.com)는 CNAME이라고 합니다. 나중에 이걸 써야 하니까 메모해 주세요.

## Munchkin ID 찾기 {#find-your-munchkin-id}

1. 로 이동합니다. **관리** 영역.

   ![](assets/customize-your-landing-page-urls-with-a-cname-1.png)

1. 클릭 **내 계정**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-2.png)

   >[!NOTE]
   >
   >**관리 권한 필요**

1. &quot;지원 정보&quot;로 스크롤한 다음 Munchkin ID를 복사합니다.

   ![](assets/customize-your-landing-page-urls-with-a-cname-3.png)

## IT에 요청 보내기 {#send-request-to-it}

IT 담당자에게 다음 CNAME을 설정하도록 요청합니다. (단어 바꾸기 [CNAME] 및 [Munchkin ID] 이전 단계의 텍스트를 사용하여)

[CNAME].YourCompany.com > [Munchkin ID].mktoweb.com

## CNAME 설정 완료 {#complete-cname-setup}

1. IT 부서에서 CNAME을 만들면 **관리** 영역.

   ![](assets/customize-your-landing-page-urls-with-a-cname-4.png)

1. 클릭 **랜딩 페이지**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-5.png)

1. 아래에 **설정** 섹션을 클릭합니다. **편집**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-6.png)

1. 에 CNAME을 입력합니다. **랜딩 페이지의 도메인 이름**&#x200B;를 입력합니다. **대체 페이지**&#x200B;를 입력합니다. **홈페이지** 을(를) 클릭합니다. **저장**.

   ![](assets/customize-your-landing-page-urls-with-a-cname-7.png)

>[!NOTE]
>
>Marketo 랜딩 페이지를 사용할 수 없는 경우 대체 페이지가 페이지 리드로 리디렉션됩니다.

잘했어! 이제 랜딩 페이지가 회사 도메인으로 브랜딩됩니다.
