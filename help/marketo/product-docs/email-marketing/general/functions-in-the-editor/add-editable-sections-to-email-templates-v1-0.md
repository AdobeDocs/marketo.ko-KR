---
unique-page-id: 1900585
description: v1.0에서 이메일 템플릿에 편집 가능한 섹션을 추가하는 방법을 알아봅니다. 사용자가 나머지 부분을 잠근 채 특정 영역을 편집할 수 있도록 허용합니다.
title: 이메일 템플릿 v1.0에 편집 가능한 섹션 추가
exl-id: f397aa8e-0d0b-4007-91e1-9b9158bd6432
feature: Email Editor
TQID: https://experienceleague.adobe.com/j2rwpy7Bq-HH3-mva5FkDb3kKH8cvlH2hMUp0ic7sno
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: f82558ea-6af5-44eb-a424-5b3389abb0a3
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 111
ht-degree: 13%

---

# 이메일 템플릿 v1.0에 편집 가능한 섹션 추가 {#add-editable-sections-to-email-templates-v1.0}

전자 메일 템플릿 편집기 v1.0에서 템플릿을 만드는 경우 특수 `<div>`을(를) 삽입하면 모든 섹션을 편집할 수 있습니다.

>[!NOTE]
>
>**예**
>
>`<pre> <div class="mktEditable" id="UNIQUE_ID">This part is editable</div></pre>`

규칙:

1. HTML은 항상 유효해야 합니다.
1. **mktEditable** 클래스를 포함해야 합니다.
1. ID는 해당 HTML에서 고유해야 합니다.
1. ID에 공백이 없습니다.

>[!CAUTION]
>
>mktEditable 문은 중첩될 수 없습니다.

전자 메일 템플릿 편집기 v2.0에서 이 작업을 수행하는 방법에 대해 알아보려면 [전자 메일 템플릿 구문](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md)을 확인하십시오.
