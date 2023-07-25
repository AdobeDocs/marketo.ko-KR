---
unique-page-id: 1900554
description: 이메일의 HTML 편집 - Marketo 문서 - 제품 설명서
title: 이메일 HTML 편집
exl-id: 9dc8e44d-d9da-4bc2-950f-3ffbb976f5d5
feature: Email Editor
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---

# 이메일 HTML 편집 {#edit-an-emails-html}

이메일의 기본 HTML을 수정해야 하는 경우가 있습니다. 때때로 외부 시스템을 사용하여 이메일 코드를 디자인하고 빌드할 수 있습니다. 어느 방식이든 이메일 편집기 내에서 코드를 쉽게 가져오거나 편집할 수 있습니다.

## HTML 편집 {#edit-html}

1. 이메일을 선택하고 **초안 편집**.

   ![](assets/teamspidey.jpg)

1. 클릭 **코드 편집**.

   ![](assets/two-4.png)

1. 원하는 대로 변경합니다. 클릭 **저장** 완료 시.

   ![](assets/three-3.png)

   >[!NOTE]
   >
   >원하는 대로 변경하십시오. 전체 HTML을 바꾸거나 약간 조정할 수 있습니다.

1. 다음을 클릭합니다. **코드 작업** .html 파일로 코드를 다운로드하거나, CSS를 인라인하거나, HTML의 유효성을 검사하는 드롭다운입니다.

   ![](assets/four-2.png)

   >[!NOTE]
   >
   >이메일의 가장 좋은 방법은 모든 스타일을 인라인으로 만드는 것입니다. 일부 이메일 클라이언트는 `<head>` 섹션.

## 템플릿에서 이메일 깨기 {#breaking-an-email-from-its-template}

이러한 코드 변경 사항 **다음이 아님** 템플릿에서 이메일 세분화:

* 모듈의 내용 편집(모듈 내에 새 요소 추가 포함)
* 컨테이너에 새 모듈 추가
* 컨테이너에서 모듈 삭제

* 모듈 외부에 있는 요소의 mkto 관련 속성(예: &quot;mktoName&quot; 또는 &quot;mktoImgUrl&quot;) 변경
* 요소의 콘텐츠 편집(리치 텍스트, 이미지, 비디오 등) 모듈 외부

코드 편집기에서 수행할 수 있는 작업 **의지** 템플릿에서 이메일 세분화:

* 요소 또는 모듈 외부에 있는 코드의 모든 항목 변경
* 모듈 외부에 있는 요소의 mkto 속성이 아닌 특성(예: &quot;id&quot; 또는 &quot;style&quot;) 추가 또는 변경
* 모듈 외부에 있는 요소 삭제

## 코드 검색 {#search-code}

코드 검색 기능을 사용하여 이메일의 HTML 코드 내에서 콘텐츠를 효율적으로 찾고 바꿀 수 있습니다.

1. 전자 메일 코드에서 **코드 검색**.

   ![](assets/five-2.png)

1. 찾을 내용을 입력하고 클릭합니다. **다음 찾기** 앞으로 검색하거나 **이전 찾기** 뒤로 검색합니다. 또한 다음 옵션을 사용할 수 있습니다. **바꾸기** 및 **모두 바꾸기**.

   ![](assets/six-1.png)

1. 클릭 **닫기** 완료 시.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >검색 코드는에서 사용할 수도 있습니다. [이메일 템플릿 편집기](/help/marketo/product-docs/email-marketing/general/email-editor-2/create-an-email-template.md).

Marketo의 기본 기능을 사용하여 이메일을 계속 편집하는 것이 좋지만 이 코드 편집기는 필요한 경우 유연성을 제공합니다.
