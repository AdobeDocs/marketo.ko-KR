---
title: Marketo Engage용 GenStudio 통합
description: Marketo Engage에서 GenStudio을 사용하는 방법을 알아봅니다.
solution: Marketo Engage
product: marketo
level: Beginner, Intermediate
feature: Email Designer
exl-id: bb15b18e-9a17-4dee-87f4-12f216dd3545
source-git-commit: bd1179a632c0363d62e262cb153b8f83dc0bfbf5
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 3%

---

# Marketo Engage용 GenStudio 통합 {#genstudio-integration-for-marketo-engage}

Adobe GenStudio for Performance Marketing은 고유한 광고 및 이메일을 만들어 브랜드 표준을 충족하고 엔터프라이즈 정책을 준수하는 영향력 있고 개인화된 마케팅 캠페인을 추진할 수 있는 생성 가능한 AI 우선 애플리케이션입니다. 컨텐츠 작성의 복잡성을 간소화하는 다양한 도구를 제공합니다.

>[!AVAILABILITY]
>
>이 기능을 활용하려면 다음 작업을 수행하십시오.
>
>* IMS 조직은 Marketo Engage과 동일한 IMS 조직에서 GenStudio for Performance Marketing으로 프로비저닝되어야 합니다(자세한 내용은 계정 관리자에게 문의)
>* GenStudio for Performance Marketing(시스템 관리자, 편집자 또는 공동 작업자 제품 프로필)에 대한 사용자 권한이 있어야 합니다.

>[!INFO]
>
>[GenStudio for Performance Marketing](https://experienceleague.adobe.com/ko/docs/genstudio-for-performance-marketing/user-guide/home){target="_blank"}에 대해 자세히 알아보세요.

## Marketo Engage의 GenStudio 기능 활용 {#leverage-genstudio-capabilities}

이 통합을 통해 Marketo Engage을 사용하여 이메일 캠페인을 개발 및 자동화하는 기술 마케터는 GenStudio을 사용하여 콘텐츠를 만드는 성능 마케터와 공동 작업을 수행할 수 있습니다. 이렇게 하면 GenStudio의 브랜드 내 콘텐츠를 Marketo Engage에 쉽게 통합할 수 있습니다.

## Marketo Engage에서 GenStudio으로 HTML 템플릿 내보내기 {#export-an-html-template}

브랜드의 지침이 포함된 템플릿을 GenStudio for Performance Marketing으로 쉽게 내보낼 수 있습니다.

1. Marketo Engage에서 이메일 콘텐츠에 액세스합니다.

1. 이메일 Designer에서 **자세히** 단추를 클릭하고 **HTML 내보내기**&#x200B;를 선택합니다.

   ![HTML 내보내기](assets/genstudio-integration-1.png)

1. [내보낸 템플릿을 HTMLGenStudio for Performance Marketing 에 업로드](https://experienceleague.adobe.com/ko/docs/genstudio-for-performance-marketing/user-guide/content/templates/use-templates#templates-from-ajo-and-marketo){target="_blank"}합니다.

1. GenStudio에서 이 템플릿을 사용하여 AI 프롬프트가 있는 [여러 개의 이메일 변형을 만들고](https://experienceleague.adobe.com/ko/docs/genstudio-for-performance-marketing/user-guide/create/create-email-experience){target="_blank"}을(를) 저장합니다.

## Marketo Engage에서 GenStudio 경험 활용 {#leverage-genstudio-experiences}

Marketo Engage으로 가져와서 만든 GenStudio 이메일 변형을 활용하려면 아래 단계를 수행합니다.

1. Marketo Engage에서 [전자 메일을 만듭니다](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#create-an-email).

1. 전자 메일 세부 정보 페이지에서 **전자 메일 콘텐츠 편집**&#x200B;을 클릭합니다.

   ![전자 메일 콘텐츠 편집 단추](assets/genstudio-integration-2.png)

1. **HTML 가져오기**&#x200B;를 선택합니다.

   ![HTML 가져오기 단추](assets/genstudio-integration-3.png)

1. **Adobe GenStudio for Performance Marketing** 단추를 클릭합니다.

   ![Adobe GenStudio for Performance Marketing 단추](assets/genstudio-integration-4.png)

1. GenStudio 경험을 탐색하여 콘텐츠 빌드를 시작합니다. 제품, 가상 사용자, 브랜드 또는 색상과 같은 기준으로 경험을 필터링할 수 있습니다.

1. 경험을 선택하고 **사용**&#x200B;을 클릭하세요.

   ![원하는 경험 선택](assets/genstudio-integration-5.png){width="800" zoomable="yes"}

1. 선택한 콘텐츠가 이메일 Designer에 표시됩니다.

   ![이메일 디자이너](assets/genstudio-integration-6.png){width="800" zoomable="yes"}

>[!NOTE]
>
>Marketo Engage 템플릿에서 만든 GenStudio 경험은 이메일 Designer으로 직접 가져옵니다. Marketo Engage 템플릿 없이 생성된 GenStudio 경험은 호환성 모드로 가져옵니다.

[전자 메일 콘텐츠 편집 도구](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#add-structure-and-content){target="_blank"} 및 [개인화 필드](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#personalize-content){target="_blank"}를 사용하여 원하는 대로 전자 메일을 편집하세요.
