---
unique-page-id: 1900554
description: 이메일의 HTML 편집 - 마케팅 문서 - 제품 설명서
title: 이메일의 HTML 편집
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# 이메일의 HTML {#edit-an-emails-html} 편집

이메일의 기본 HTML을 수정해야 하는 경우가 있습니다. 이메일 코드를 디자인하고 작성하는 데 외부 시스템을 사용하는 경우가 있습니다. 이메일 편집기 내에서 코드를 쉽게 가져오거나 편집할 수 있습니다.

## HTML {#edit-html} 편집

1. 전자 메일을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/teamspidey.jpg)

1. **코드 편집**&#x200B;을 클릭합니다.

   ![](assets/two-4.png)

1. 모든 변경 완료되면 **저장**&#x200B;을 클릭합니다.

   ![](assets/three-3.png)

   >[!NOTE]
   >
   >원하는 대로 변경할 수 있습니다. 전체 HTML을 교체하거나 약간 조정할 수 있습니다.

1. **코드 작업** 드롭다운을 클릭하여 코드를 .html 파일로 다운로드하거나, CSS를 인라인으로 다운로드하거나, HTML의 유효성을 확인합니다.

   ![](assets/four-2.png)

   >[!NOTE]
   >
   >이메일의 우수 사례는 모든 스타일을 인라인으로 만드는 것입니다. 일부 이메일 클라이언트는 `<head>` 섹션 내에서 CSS를 지원하지 않습니다.

## 템플릿 {#breaking-an-email-from-its-template}에서 이메일 끊기

이러한 코드 변경 사항은 **이(가) 해당 템플릿에서 이메일을 교환하지 않습니다.**

* 모듈의 내용 편집(모듈에 새 요소 추가 포함)
* 컨테이너에 새 모듈 추가
* 컨테이너에서 모듈 삭제

* 모듈 외부 요소의 mktoName 또는 &quot;mktoImgUrl&quot;과 같은 mkto 특정 속성 변경
* 요소의 컨텐츠 편집(리치 텍스트, 이미지, 비디오 등) 모듈 외부

코드 편집기에서 수행할 수 있는 작업은 **이(가) 해당 템플릿에서 이메일을 구분합니다.**

* 요소 또는 모듈 외부의 코드 내용 변경
* 모듈 외부 요소의 비매핑 특성 추가 또는 변경(예: &quot;id&quot; 또는 &quot;스타일&quot;)
* 모듈 외부에 있는 요소 삭제

## 검색 코드 {#search-code}

검색 코드 기능을 사용하여 이메일의 HTML 코드 내에서 컨텐츠를 효율적으로 찾아 교체할 수 있습니다.

1. 이메일의 코드에서 **검색 코드**&#x200B;를 클릭합니다.

   ![](assets/five-2.png)

1. 찾을 내용을 입력하고 **다음 찾기**&#x200B;를 클릭하여 앞뒤로 검색하거나 **이전 찾기**&#x200B;를 클릭합니다. **바꾸기** 및 **모두 바꾸기**&#x200B;도 선택할 수 있습니다.

   ![](assets/six-1.png)

1. 완료되면 **닫기**&#x200B;를 클릭합니다.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >검색 코드는 [이메일 템플릿 편집기](http://docs.marketo.com/display/DOCS/Create+a+New+Email+Template)에서도 사용할 수 있습니다.

Marketing의 내장된 기능을 사용하여 이메일을 계속 편집하는 것이 좋지만 이 코드 편집기는 필요한 경우 유연하게 편집할 수 있습니다.
