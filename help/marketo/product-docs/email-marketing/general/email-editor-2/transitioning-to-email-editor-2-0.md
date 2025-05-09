---
unique-page-id: 11373011
description: 이메일 편집기 2.0으로 전환 - Marketo 문서 - 제품 설명서
title: 이메일 편집기 2.0으로 전환
exl-id: eb9ec8cc-d6e8-4839-a4d9-608d2f264cbb
hide: true
hidefromtoc: true
feature: Email Editor
source-git-commit: b3bc6a7ec14a513e4b294852d066f9e3d0f74ef8
workflow-type: tm+mt
source-wordcount: '642'
ht-degree: 0%

---

# 이메일 편집기 2.0으로 전환 {#transitioning-to-email-editor}

1919년 6월 릴리스부터 모든 Marketo 구독이 이메일 편집기 2.0으로 전환되었습니다. 이메일 편집기 1.0 사용 중단에 대해 [자세히 알아보기](https://nation.marketo.com/docs/DOC-7038).

구독 내 이메일 및 이메일 템플릿에는 버전 번호가 있어야 합니다. 버전은 자산의 요약 페이지에서 찾을 수 있습니다.

![](assets/five-5.png)

기본적으로 모든 기존 이메일 및 이메일 템플릿은 16년 봄 릴리스 이전 또는 이메일 편집기 2.0이 비활성화되는 릴리스 이후에 생성된 경우 v1.0으로 표시됩니다. 이제 이메일 편집기 2.0이 자동으로 활성화되면 다음 동작이 표시됩니다.

* 새 전자 메일을 만들면 [전자 메일 템플릿 선택기](email-template-picker-overview.md)가 표시되고 v2.0 전자 메일 템플릿을 선택할 수 있습니다.
* 이메일 편집기 2.0을 사용하여 이메일을 만들거나 편집할 때마다 결과 이메일이 **always**&#x200B;로 표시됩니다(v1.0 이메일 템플릿을 사용한 경우에도).

이메일 편집기 2.0으로 이동하기 전에 구독에 v1.0 이메일이 있는 경우 에셋의 현재 상태를 기반으로 다음과 같은 동작이 발생합니다.

**승인됨** - &quot;초안 편집&quot;을 클릭하면 승인된 이메일의 v2.0 초안이 만들어집니다. 그런 다음 v2.0 초안을 승인하면 이메일의 승인됨 상태는 v2.0이 되며 v1.0으로 되돌릴 수 없습니다.\
**초안** - &quot;초안 편집&quot;을 클릭하면 해당 초안이 v2.0으로 자동으로 표시됩니다. 이 시점에서는 자산의 승인된 버전이 없기 때문에 v1.0으로 되돌리거나 삭제할 수 없습니다.
**초안으로 승인됨** - &quot;초안 편집&quot;을 클릭하면 자동으로 해당 초안이 v2.0으로 표시됩니다. 이러한 이유로 초안을 v1.0으로 되돌리는 방법도 없습니다.

이메일 편집기 2.0으로 이동하기 전에 구독에 v1.0 이메일 템플릿이 있는 경우 다음과 같은 동작이 발생합니다.

**승인됨** - &quot;초안 편집&quot;을 클릭하면 기존 전자 메일 템플릿의 v2.0 초안이 만들어집니다.
**초안** - &quot;초안 편집&quot;을 클릭하면 해당 초안이 v2.0으로 자동으로 표시됩니다. 이 시점에서는 자산의 승인된 버전이 없기 때문에 v1.0으로 되돌리거나 삭제할 수 없습니다.
**초안으로 승인됨** - &quot;초안 편집&quot;을 클릭하면 해당 초안이 v2.0으로 자동으로 표시됩니다. 이러한 이유로 초안을 v1.0으로 되돌리는 방법도 없습니다.

이전에 v1.0이었던 이메일 템플릿을 승인하면(위의 상태 중 하나에서) 다음 동작이 표시됩니다.

(이전 v1.0) 템플릿을 사용하는 기존 v1.0 이메일의 경우:\
**승인된 v1.0 전자 메일** - 새로 승인된 v2.0 템플릿을 사용하여 이 전자 메일에 대한 v2.0 초안이 만들어집니다. 또한 모든 템플릿 변경 사항을 수신하게 됩니다.\
**초안 v1.0 이메일** - &quot;초안 편집&quot;을 클릭할 때까지 초안이 v1.0으로 유지됩니다. 그런 다음 v2.0으로 자동 표시되고 템플릿 변경 사항이 수신됩니다.\
**초안 v1.0으로 승인됨** - &quot;초안 편집&quot;을 클릭할 때까지 초안이 v1.0으로 유지됩니다. 그런 다음 v2.0으로 자동 표시되고 템플릿 변경 사항이 수신됩니다.

(이전 v1.0) 템플릿을 사용하는 기존 v2.0 이메일의 경우:\
**승인된 v2.0 전자 메일** - 이 전자 메일에 대해 v2.0 초안이 만들어지지만 새로 승인된 템플릿을 &quot;사용&quot;하고 모든 템플릿 변경 사항을 받게 됩니다.\
**초안 v2.0 이메일** - 초안은 현재 상태(v2.0)로 유지되며 템플릿 변경 사항을 수신하게 됩니다.\
**초안 v2.0으로 승인됨** - 초안은 현재 상태(v2.0)로 유지되며 템플릿 변경 사항을 수신하게 됩니다.

>[!CAUTION]
>
>v1.0 이메일 템플릿의 v2.0 초안을 승인하면 템플릿은 v2.0이 됩니다. v1.0으로 되돌리는 방법은 **없습니다**.

참고할 사항

* 승인된 이메일은 **절대**&#x200B;변경되지 않습니다.

* 승인된 전자 메일 서식 파일이 **변경되지 않음**.

* 몇 가지 **드문**&#x200B;가지 경우 v1.0 전자 메일을 전자 메일 편집기 2.0에서 열 수 없습니다. 이 경우 초안을 취소하고 Marketo 지원 센터에 문의하십시오.

>[!MORELIKETHIS]
>
>* [전자 메일 편집기 2.0 개요](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md)
>* [전자 메일 템플릿 구문](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md)
