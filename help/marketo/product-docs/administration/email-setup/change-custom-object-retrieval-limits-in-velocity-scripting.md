---
description: Velocity 스크립팅의 사용자 지정 개체 검색 제한 변경 - Marketo 문서 - 제품 설명서
title: 속도 스크립팅에서 사용자 지정 개체 검색 제한 변경
exl-id: ef45205e-421d-4d1d-8c9d-7d627326a90c
source-git-commit: aeaf1f55b81da70ac8415cab265165a3848b5a0e
workflow-type: tm+mt
source-wordcount: '248'
ht-degree: 0%

---

# 속도 스크립팅에서 사용자 지정 개체 검색 제한 변경 {#change-custom-object-retrieval-limits-in-velocity-scripting}

Velocity Script를 사용하여 전자 메일에 사용자 지정 개체 데이터를 표시하는 경우 이 기능이 필요할 수 있습니다. 기본적으로 Velocity Script에서 10개의 상위 사용자 지정 개체에 액세스할 수 있습니다. 자세히 액세스해야 하는 경우 계속 읽으십시오.

## 속도 {#what-is-velocity}

[Apache 속도](https://velocity.apache.org/) 는 HTML 컨텐츠를 템플릿 및 스크립팅하도록 설계된 Java를 기반으로 구축된 언어입니다. Marketo을 사용하면 다음 작업을 통해 이메일 컨텍스트에서 사용할 수 있습니다 [스크립팅 토큰](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md). 특히 사용자 지정 객체에 저장된 데이터에 액세스할 수 있습니다.

Lead 또는 Contact에 직접 연결되지만 타사 사용자 지정 개체가 아닌 상위 및 하위 사용자 지정 개체를 참조할 수 있습니다. 각 사용자 지정 객체의 경우 1인/연락처당 가장 최근에 업데이트된 레코드 10개를 런타임 시 사용할 수 있으며 가장 최근에 업데이트한 레코드(0)부터 가장 오래된 업데이트(9)까지 순서가 지정됩니다.

## 제한을 변경하는 방법 {#how-to-change-the-limit}

1. 로 이동합니다. **관리** 섹션을 참조하십시오.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-1.png)

1. 클릭 **이메일**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-2.png)

1. 사용자 정의 객체 검색 제한 테이블에서 새 상위 검색 제한을 입력하고 **변경 내용 저장**.

   ![](assets/change-custom-object-retrieval-limits-in-velocity-scripting-3.png)

>[!NOTE]
>
>상위 검색 제한 값은 10 - 100 사이여야 합니다. 하위 검색 제한이 자동으로 설정됩니다. 이 작업은 1000을 상위 검색 제한으로 나누어 수행됩니다. 예를 들어 상위 제한을 50으로 설정하면 하위 제한은 20이 됩니다(1000 ÷ 50 = 20).

달콤해! 이제 Velocity 스크립트에서 더 많은 사용자 지정 개체에 액세스할 수 있습니다.
