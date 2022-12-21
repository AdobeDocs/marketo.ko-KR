---
unique-page-id: 2359798
description: 추가 랜딩 페이지 CNAME 추가 - Marketo 문서 - 제품 설명서
title: 추가 랜딩 페이지 CNAME 추가
exl-id: eb5a7f69-552e-49a2-91db-a784f4639cd0
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---

# 추가 랜딩 페이지 CNAME 추가 {#add-additional-landing-page-cnames}

다른 URL이 Marketo 랜딩 페이지를 가리키도록 랜딩 페이지 CNAME을 추가할 수 있습니다. 아래 절차에 따라 여러 도메인을 관리하는 데 도움이 됩니다.

>[!CAUTION]
>
>쿠키는 도메인 간에 공유할 수 없습니다.

>[!TIP]
>
>**동일한 최상위 도메인 - 좋습니다! 쿠키가 공유됨**.<br/> **go**.mycompany.com > **info**.mycompany.com
>
>**다른 최상위 수준 도메인 - 잘못되었습니다! 쿠키는 _not_ 공유**.<br/> 가&#x200B;**mycompany**.com > 이동&#x200B;**mynewcompany**.com

>[!NOTE]
>
>**관리 권한 필요**

## 계정 문자열 찾기 {#find-your-account-string}

1. 로 이동합니다. **관리** 영역을 클릭하고 **랜딩 페이지**.

   ![](assets/image2014-9-16-15-3a19-3a54.png)

1. 를 복사합니다. **계정 문자열** 에서 **설정** 섹션을 참조하십시오.

   ![](assets/image2014-9-16-15-3a20-3a2.png)

1. 다음 단계를 위해 기록해 두십시오.

## IT에 요청 보내기 {#send-request-to-it}

1. IT 부서에 다음 CNAME을 설정하도록 요청하십시오. (단어 바꾸기 [CNAME] 원하는 CNAME으로 [계정 문자열] 이전 단계의 텍스트를 포함하는 경우입니다.

   [CNAME].YourCompany.com > [계정 문자열].mktoweb.com

## 새 CNAME 추가 {#add-a-new-cname}

1. IT 부서에서 CNAME을 만들면 다음 위치로 이동하십시오. **관리** 을 클릭한 다음 **랜딩 페이지**.

   ![](assets/image2014-9-16-15-3a20-3a20.png)

1. 클릭 **새로 만들기** 을(를) 선택합니다. **새 도메인 별칭**.

   ![](assets/image2014-9-16-15-3a20-3a28.png)

1. 을(를) 입력합니다. **도메인 별칭.** 다음 **기본 페이지** 방문자가 URL에 입력하지 않으면 표시됩니다. 해당 케이스의 이동 위치를 입력합니다.

   >[!NOTE]
   >
   >기본 페이지에서 랜딩 페이지나 공개 웹 사이트와 같은 외부 URL을 선택할 수 있습니다.

   ![](assets/image2014-9-16-15-3a20-3a36.png)

1. 을(를) 입력합니다. **기본 페이지** 을(를) 클릭합니다. **만들기**.

   ![](assets/image2014-9-16-15-3a20-3a43.png)

좋아! 이제 CNAME을 추가하려는 경우 어떻게 해야 하는지 알 수 있습니다.
