---
unique-page-id: 1146995
description: 흐름 단계 - Marketo 문서 - 제품 설명서에서 토큰 사용
title: 흐름 단계에서 토큰 사용
exl-id: 9b4c3d57-5906-4d7c-8215-4ba2271be3f8
feature: Smart Campaigns
source-git-commit: 2eeb7ea7fd43ba75a3c802a91ce07c90dc8abd91
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 0%

---

# 흐름 단계에서 토큰 사용 {#use-tokens-in-flow-steps}

>[!PREREQUISITES]
>
>[스마트 캠페인에 플로우 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}

토큰은 변수입니다. 이메일, 랜딩 페이지 및 스마트 캠페인에서 이를 사용하여 보다 편리한 작업을 수행할 수 있습니다. 다음을 사용할 수 있습니다. [내 토큰](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md){target="_blank"} (사용자 지정 토큰) 흐름 단계, 웹후크, 이메일 및 랜딩 페이지의 . 토큰을 사용하여 다음 흐름 단계에 변수 콘텐츠를 포함할 수 있습니다.

* 데이터 값 변경
* 프로그램 멤버 데이터 변경
* 즐거운 순간
* Salesforce 캠페인 단계(추가, 제거, 상태 변경)
* 작업 만들기
* 경고 보내기(트리거 캠페인에서만)

1. 흐름 단계에서 입력을 시작합니다. `{{` 토큰 범주를 가져옵니다.

   ![](assets/image2014-9-22-14-3a3-3a17.png)

   >[!NOTE]
   >
   >체크아웃 [토큰 개요](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"} 사용 가능한 여러 토큰 목록입니다.

1. 원하는 토큰을 찾을 때까지 계속 입력하고 클릭하여 선택합니다.

   ![](assets/image2014-9-22-14-3a3-3a48.png)

   >[!TIP]
   >
   >여러 토큰을 관심 있는 순간, 작업 만들기 및 경고 전송 흐름 단계에서 사용할 수 있습니다.

   >[!NOTE]
   >
   >프로그램 멤버 맞춤형 필드 토큰은 작업 만들기, Microsoft에서 작업 만들기, 즐거운 순간, 데이터 값 흐름 동작 변경 및 웹후크에서 사용할 수 있습니다.

   멋지다! 스마트 캠페인이 실행되면 토큰에서 데이터를 가져옵니다.

   >[!MORELIKETHIS]
   >
   >* [내 토큰 관리](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"}
   >* [프로그램의 내 토큰 이해](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md){target="_blank"}
