---
unique-page-id: 1146995
description: 흐름 단계에서 토큰 사용 - Marketo 문서 - 제품 설명서
title: 흐름 단계에서 토큰 사용
exl-id: 9b4c3d57-5906-4d7c-8215-4ba2271be3f8
source-git-commit: 46812deb41ed56328a4a64fbd36340d13c50dde4
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 0%

---

# 흐름 단계에서 토큰 사용 {#use-tokens-in-flow-steps}

>[!PREREQUISITES]
>
>[스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)

토큰은 변수입니다. 이메일, 랜딩 페이지 및 스마트 캠페인에서 이를 사용하여 보다 손쉽게 작업할 수 있습니다. 다음을 사용할 수 있습니다 [내 토큰](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md) (사용자 지정 토큰) 흐름 단계, 웹 후크, 이메일 및 랜딩 페이지의 . 토큰을 사용하여 다음 흐름 단계에 변수 콘텐츠를 포함할 수 있습니다.

* 데이터 값 변경
* 프로그램 멤버 데이터 변경
* 흥미로운 순간
* Salesforce 캠페인 단계(추가, 제거, 상태 변경)
* 작업 만들기
* 경고 보내기(트리거 캠페인만)

1. 흐름 단계에서 입력을 시작합니다 `{{` 토큰 카테고리를 가져오려면 다음을 수행하십시오.

   ![](assets/image2014-9-22-14-3a3-3a17.png)

   >[!NOTE]
   >
   >체크 아웃 [토큰 개요](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) 를 참조하십시오.

1. 원하는 토큰을 찾을 때까지 계속 입력하고 클릭하여 선택합니다.

   ![](assets/image2014-9-22-14-3a3-3a48.png)

   >[!TIP]
   >
   >흥미로운 순간, 작업 만들기 및 경고 흐름 보내기 단계에서 여러 토큰을 사용할 수 있습니다.

   >[!NOTE]
   >
   >프로그램 구성원 사용자 지정 필드 토큰은 다음 위치에서 사용할 수 있습니다. 작업 만들기, Microsoft에서 작업 만들기, 흥미로운 순간, 데이터 값 흐름 작업 변경 및 Webhooks.

   멋져요! 스마트 캠페인이 실행될 때 토큰에서 데이터를 가져옵니다.

   >[!MORELIKETHIS]
   >
   >* [내 토큰 관리](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md)
   >* [프로그램에서 내 토큰 이해](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md)

