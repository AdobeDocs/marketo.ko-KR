---
unique-page-id: 1900585
description: 이메일 템플릿 v1.0 - 마케팅 문서 - 제품 문서에 편집 가능한 섹션 추가
title: 이메일 템플릿 v1.0에 편집 가능한 섹션 추가
translation-type: tm+mt
source-git-commit: f27e2bac90570f9f795dc6bdd5fcf208c446be14
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 0%

---


# 이메일 템플릿 v1.0 {#add-editable-sections-to-email-templates-v1.0}에 편집 가능한 섹션 추가

이메일 템플릿 편집기 v1.0에서 템플릿을 만드는 경우 그 주위에 특별한 `<div>`을 추가하여 모든 섹션을 편집할 수 있습니다.

>[!NOTE]
>
>**예**
>`<pre> <div class="mktEditable" id="UNIQUE_ID">This part is editable</div></pre>`

규칙:

1. HTML은 항상 유효해야 합니다.
1. **mktEditable**&#x200B;의 클래스를 포함해야 합니다.
1. ID는 해당 HTML에서 고유해야 합니다.
1. ID에 공백이 없습니다.

>[!CAUTION]
>
>mktEditable 문은 중첩할 수 없습니다.

이메일 템플릿 편집기 v2.0에서 이를 수행하는 방법을 알려면 [이메일 템플릿 구문](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md)을 확인하십시오.
