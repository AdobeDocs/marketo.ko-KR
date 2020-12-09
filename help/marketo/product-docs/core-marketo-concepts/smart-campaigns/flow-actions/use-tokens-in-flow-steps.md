---
unique-page-id: 1146995
description: 흐름 단계의 토큰 사용 - Marketing To Docs - 제품 설명서
title: 흐름 단계에서 토큰 사용
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 0%

---


# 흐름 단계에서 토큰 사용 {#use-tokens-in-flow-steps}

>[!PREREQUISITES]
>
>* [스마트 캠페인에 흐름 단계 추가](add-a-flow-step-to-a-smart-campaign.md)


토큰은 변수입니다. 또한 [이메일](https://docs.marketo.com/pages/viewpage.action?pageId=557076), [랜딩 페이지](https://docs.marketo.com/pages/viewpage.action?pageId=2359689)및 [스마트한 캠페인](https://docs.marketo.com/display/DOCS/Smart+Lists+and+Lists) 으로 간편하게 작업할 수 있습니다. 흐름 단계, [웹](../../../../product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md) 후크, 이메일 및 랜딩 페이지에서 내 토큰(사용자 정의 토큰)을 사용할 수 있습니다.  토큰을 사용하여 다음과 같은 흐름 단계에 변수 컨텐츠를 포함할 수 있습니다.

* 데이터 값 변경
* 흥미로운 순간
* Salesforce 캠페인 단계(상태 추가, 제거, 변경)
* 작업 만들기
* 경고 보내기(트리거 캠페인에만 해당)

>[!NOTE]
>
>**가용성**
>
>모든 고객이 이 기능을 구입하지는 않았습니다. 자세한 내용은 영업 담당자에게 문의하십시오.

1. 흐름 단계에서 입력 작업을 시작하여 토큰 범주 `{{` 를 가져옵니다. ![](assets/image2014-9-22-14-3a3-3a17.png)>

   >[!NOTE]
   >
   >**딥 다이브**
   >
   >토큰 [개요](../../../../product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) (사용 가능한 여러 토큰 목록)를 확인하십시오.

1. 원하는 토큰을 찾을 때까지 입력을 유지하고 클릭하여 선택합니다.

   ![](assets/image2014-9-22-14-3a3-3a48.png)

   >[!TIP]
   >
   >흥미로운 순간, 작업 만들기 및 경고 보내기 흐름 단계에서 여러 토큰을 사용할 수 있습니다.

   >[!NOTE]
   >
   >**관련 문서**
   >
   >* [내 토큰 관리](../../../../product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md)
   >* [프로그램의 토큰 이해](../../../../product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md)


좋아! 스마트 캠페인이 실행될 때 토큰에서 데이터를 가져옵니다.