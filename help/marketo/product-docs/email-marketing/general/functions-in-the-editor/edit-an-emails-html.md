---
unique-page-id: 1900554
description: 이메일 HTML 편집 - Marketo 문서 - 제품 설명서
title: 이메일 HTML 편집
exl-id: 9dc8e44d-d9da-4bc2-950f-3ffbb976f5d5
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---

# 이메일 HTML 편집 {#edit-an-emails-html}

이메일의 기본 HTML을 수정해야 하는 경우가 있습니다. 경우에 따라 외부 시스템을 사용하여 이메일 코드를 디자인하고 작성할 수 있습니다. 어느 쪽이든 간에 이메일 편집기 내에서 코드를 쉽게 가져오거나 편집할 수 있습니다.

## HTML 편집 {#edit-html}

1. 이메일을 선택하고 을(를) 클릭합니다 **초안 편집**.

   ![](assets/teamspidey.jpg)

1. 클릭 **코드 편집**.

   ![](assets/two-4.png)

1. 변경 작업을 수행합니다. 클릭 **저장** 완료 시.

   ![](assets/three-3.png)

   >[!NOTE]
   >
   >원하는 대로 바꾸세요. 전체 HTML을 바꾸거나 약간 조정할 수 있습니다.

1. 을(를) 클릭합니다. **코드 작업** 드롭다운을 사용하여 코드를 .html 파일로 다운로드하거나 CSS를 인라인 또는 HTML의 유효성을 검사할 수 있습니다.

   ![](assets/four-2.png)

   >[!NOTE]
   >
   >이메일에 가장 좋은 방법은 모든 스타일을 인라인으로 만드는 것입니다. 여러 이메일 클라이언트는 `<head>` 섹션을 참조하십시오.

## 템플릿에서 이메일 분류 {#breaking-an-email-from-its-template}

이러한 코드가 변경됩니다 **안 함** 템플릿에서 이메일 브레이크:

* 모듈의 컨텐츠 편집(모듈 내에 새 요소 추가 포함)
* 컨테이너에 새 모듈 추가
* 컨테이너에서 모듈 삭제

* 모듈 외부 요소의 mkto-specific 속성(예: &quot;mktoName&quot; 또는 &quot;mktoImgUrl&quot;) 변경
* 요소의 컨텐츠 편집(리치 텍스트, 이미지, 비디오 등) 모듈 외부

코드 편집기에서 수행할 수 있는 작업은 다음과 같습니다 **will** 템플릿에서 이메일 브레이크:

* 요소나 모듈의 외부에서 코드에서 모든 항목 변경
* 모듈 외부 요소의 mkto 특성(예: &quot;id&quot; 또는 &quot;style&quot;)을 추가 또는 변경합니다
* 모듈 외부에 있는 요소 삭제

## 검색 코드 {#search-code}

검색 코드 기능을 사용하여 이메일의 HTML 코드 내에서 컨텐츠를 효율적으로 찾고 바꿀 수 있습니다.

1. 이메일 코드에서 **검색 코드**.

   ![](assets/five-2.png)

1. 찾을 내용을 입력하고 을(를) 클릭합니다 **다음 찾기** 앞으로 또는 **이전 찾기** 뒤로 검색하는 중입니다. 다음 작업도 수행할 수 있습니다 **바꾸기** 및 **모두 바꾸기**.

   ![](assets/six-1.png)

1. 클릭 **닫기** 완료 시.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >검색 코드는 [이메일 템플릿 편집기](/help/marketo/product-docs/email-marketing/general/email-editor-2/create-an-email-template.md).

Marketo의 기본 제공 기능을 사용하여 이메일을 계속 편집하는 것이 좋지만 필요할 경우 이 코드 편집기에 유연성이 제공됩니다.
