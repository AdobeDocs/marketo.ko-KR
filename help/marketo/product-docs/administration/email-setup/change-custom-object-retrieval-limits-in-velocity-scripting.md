---
description: " [!DNL Velocity Scripting] - Marketo 문서 - 제품 설명서에서 사용자 지정 개체 검색 제한 변경"
title: " [!DNL Velocity Scripting]에서 사용자 지정 개체 검색 제한 변경"
exl-id: ef45205e-421d-4d1d-8c9d-7d627326a90c
feature: Email Setup
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '246'
ht-degree: 0%

---

# [!DNL Velocity Scripting]에서 사용자 지정 개체 검색 제한 변경 {#change-custom-object-retrieval-limits-in-velocity-scripting}

[!DNL Velocity Script]을(를) 사용하여 전자 메일에 사용자 지정 개체 데이터를 표시하는 경우 이 기능을 사용할 수 있습니다. 기본적으로 Velocity 스크립트에서 10개의 상위 사용자 지정 개체에 액세스할 수 있습니다. 추가 액세스 권한이 필요한 경우 계속 읽어 보십시오.

## [!DNL Velocity]이란? {#what-is-velocity}

[[!DNL Apache Velocity]](https://velocity.apache.org/)은(는) HTML 콘텐츠를 템플릿화하고 스크립팅하도록 설계된 [!DNL Java]에 빌드된 언어입니다. Marketo에서는 [스크립팅 토큰](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md)을 사용하여 전자 메일의 컨텍스트에서 사용할 수 있습니다. 무엇보다도 사용자 지정 개체에 저장된 데이터에 액세스할 수 있습니다.

리드 또는 연락처에 직접 연결된 상위 및 하위 사용자 지정 개체를 참조할 수 있지만 세 번째 수준의 사용자 지정 개체는 참조할 수 없습니다. 각 사용자 지정 개체에 대해 개인/연락처당 가장 최근에 업데이트된 레코드 10개는 런타임에 사용할 수 있으며 가장 최근에 업데이트된 레코드(0)에서 가장 오래 업데이트된 레코드(9)로 순서가 지정됩니다.

## 한도 변경 방법 {#how-to-change-the-limit}

1. **[!UICONTROL 관리자]** 섹션으로 이동합니다.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-1.png)

1. **[!UICONTROL 전자 메일]**&#x200B;을 클릭하세요.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-2.png)

1. [!UICONTROL 사용자 지정 개체 검색 제한] 테이블에서 새 [!UICONTROL 상위 검색 제한]을 입력하고 **[!UICONTROL 변경 내용 저장]**&#x200B;을 클릭합니다.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-3.png)

>[!NOTE]
>
>[!UICONTROL 상위 검색 제한] 값은 10에서 100 사이여야 합니다. [!UICONTROL 하위 검색 제한]이 자동으로 설정됩니다. 이 작업은 1000을 [!UICONTROL 상위 검색 제한] (으)로 나누어서 수행됩니다. 예를 들어 상위 제한을 50으로 설정하면 하위 제한이 20(1000 ÷ 50 = 20)이 됩니다.

좋네! 이제 [!DNL Velocity script]에서 더 많은 사용자 지정 개체에 액세스할 수 있습니다.
