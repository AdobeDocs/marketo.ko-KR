---
unique-page-id: 2359798
description: 추가 랜딩 페이지 CNAME 추가 - Marketo 문서 - 제품 설명서
title: 추가 랜딩 페이지 CNAME 추가
exl-id: eb5a7f69-552e-49a2-91db-a784f4639cd0
feature: Landing Pages
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 0%

---

# 추가 랜딩 페이지 CNAME 추가 {#add-additional-landing-page-cnames}

다른 URL이 Marketo 랜딩 페이지를 가리키도록 하기 위해 랜딩 페이지 CNAME을 추가할 수 있습니다. 아래 단계를 수행하면 여러 도메인을 관리하는 데 도움이 됩니다.

>[!CAUTION]
>
>쿠키는 도메인 간에 공유할 수 없습니다.

>[!TIP]
>
>**동일한 최상위 도메인 - 좋습니다! 쿠키가 공유됨**.<br/> **이동**.mycompany.com > **정보**.mycompany.com
>
>**다른 최상위 수준 도메인 - 잘못됨! 쿠키는 _아님_ 공유됨**.<br/> 가.**mycompany**.com > go.**mynewcompany**.com

>[!NOTE]
>
>**관리자 권한 필요**

1. 로 이동 **관리자** 영역입니다.

   ![](assets/add-additional-landing-page-cnames-1.png)

1. 클릭 **내 계정**.

   ![](assets/add-additional-landing-page-cnames-2.png)

1. 아래로 스크롤하여 &quot;지원 정보&quot;를 확인하고 Munchkin ID를 복사합니다.

   ![](assets/add-additional-landing-page-cnames-3.png)

## IT에 요청 보내기 {#send-request-to-it}

1. IT 부서에 다음 CNAME을 설정하도록 요청하십시오. (단어 바꾸기) [CNAME] 원하는 CNAME으로 [Munchkin ID] (이전 단계의 텍스트 포함).

   [CNAME].YourCompany.com > [Munchkin ID].mktoweb.com

## 새 CNAME 추가 {#add-a-new-cname}

1. IT 부서에서 CNAME을 생성했으면 **관리자** 영역입니다.

   ![](assets/add-additional-landing-page-cnames-4.png)

1. 클릭 **랜딩 페이지**.

   ![](assets/add-additional-landing-page-cnames-5.png)

1. 클릭 **신규** 그런 다음 선택 **새 도메인 별칭**.

   ![](assets/add-additional-landing-page-cnames-6.png)

1. 다음을 입력하십시오. **도메인 별칭.** 다음 **기본 페이지** 방문자가 URL을 입력하지 않으면 표시됩니다. 이 경우 이동해야 하는 위치를 입력합니다.

   >[!NOTE]
   >
   >기본 페이지의 경우 랜딩 페이지나 외부 URL(예: 공개 웹 사이트)을 선택할 수 있습니다.

   ![](assets/add-additional-landing-page-cnames-7.png)

1. 다음을 입력하십시오. **기본 페이지** 및 클릭 **만들기**.

   ![](assets/add-additional-landing-page-cnames-8.png)

좋네! 이제 CNAME을 추가하려면 어떻게 해야 하는지 알 수 있습니다.
