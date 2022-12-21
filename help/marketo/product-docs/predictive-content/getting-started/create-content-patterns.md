---
unique-page-id: 11385579
description: 컨텐츠 패턴 만들기 - Marketo 문서 - 제품 설명서
title: 컨텐츠 패턴 만들기
exl-id: 963529fb-1b30-486c-b97d-3ff697f91258
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 0%

---

# 컨텐츠 패턴 만들기 {#create-content-patterns}

컨텐츠 패턴을 설정하면 웹 방문자가 컨텐츠 패턴과 관련된 HTML 웹 페이지를 클릭하면 컨텐츠가 자동으로 검색됩니다. HTML 페이지(블로그 게시물, 보도 자료, 뉴스 기사)를 모든 컨텐츠 페이지에 컨텐츠 조각으로 추가하는 데 사용됩니다. 자동 검색이 컨텐츠 패턴을 기반으로 하는 경우 웹 방문자가 페이지를 보거나 페이지 링크를 클릭할 때 정의된 URL 패턴과 관련된 HTML 페이지를 검색 및 추적합니다. 이 컨텐츠 부분(이미지 URL, 페이지 이름 및 이미지 URL 및 설명을 포함하는 메타 데이터)은 예측 컨텐츠를 준비하기 위해 모든 컨텐츠 페이지에 추가됩니다. PDF 및 포함된 비디오와 같은 다른 컨텐츠를 자동으로 검색하려면 다음을 수행해야 합니다 [컨텐츠 검색 활성화](/help/marketo/product-docs/predictive-content/getting-started/enable-content-discovery.md).

1. 이동 **콘텐츠 설정**.

   ![](assets/settings-dropdown-hand-2.png)

1. 클릭 **URL 패턴**.

   ![](assets/click-url-patterns-hand.png)

1. 을(를) 클릭합니다. **+** 정보를 입력할 수 있는 행을 열려면

   ![](assets/content-settings-create-patterns-hand.png)

1. 웹 페이지가 있는 도메인의 URL 확장을 추가합니다. 범주(예: 블로그, 문서, Data Sheet, Press Release)를 선택합니다.

   ![](assets/content-settings-create-content-patterns-dm-hands.png)

   >[!NOTE]
   >
   >오른쪽 드롭다운 목록의 항목은 [생성된 카테고리](/help/marketo/product-docs/predictive-content/getting-started/set-up-categories.md).

1. 클릭 **+** 다른 경로를 추가하려면

   ![](assets/url-patterns-add2.png)

1. 추가 경로에 대한 확장 및 카테고리를 추가하고 을 클릭합니다. **저장**.

   ![](assets/url-patterns-save.png)

## 컨텐츠 패턴 규칙 {#content-pattern-rules}

* 표현식의 임의의 위치에서 와일드카드를 사용할 수 있습니다(예: _domain.com/&#42;_, _domain.com/&#42;블로그&#42;_)

* / 를 사용하는 것이 좋습니다&#42; 패턴 검색을 계속하기 위한 표현식 끝(예: _domain.com/blog/&#42;_ 블로그 폴더의 모든 게시물 검색)
* 컨텐츠 패턴은 대/소문자를 구분하지 않습니다(예: _domain.com/Blog/&#42;_ 모든 html 페이지 검색 _domain.com/Blog_ 및 _domain.com/blog_)

* URL 매개 변수는 검색되지 않습니다(따라서 콘텐츠 URL은 동일하지만 매개 변수는 다른 항목을 여러 개 찾을 수 없음)

## 예 {#examples}

대상 _domain.com_:

<table> 
 <tbody> 
  <tr> 
   <th>URL 패턴</th> 
   <th>결과</th> 
  </tr> 
  <tr> 
   <td>블로그/*</td> 
   <td><p>domain.com/blog/ 패턴과 일치하는 모든 컨텐츠를 검색합니다.</p><p>domain.com/blog/5-top-tricks</p><p>domain.com/blog/2017/new-year-solutions</p><p>domain.com/Blog/3-best-recipes</p></td> 
  </tr> 
  <tr> 
   <td>기사/2017/*</td> 
   <td><p>domain.com/article/2017/ 패턴과 일치하는 모든 컨텐츠를 검색합니다.</p><p>domain.com/article/2017/5-top-tricks</p></td> 
  </tr> 
  <tr> 
   <td><img alt="—" width="80" src="assets/image2017-3-24-10-3a38-3a46.png" data-linked-resource-id="12976559" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="11385579" title="--"></td> 
   <td><p>"데이터시트:"라는 단어가 포함된 URL을 검색합니다.</p><p>domain.com/datasheets/5-top-tricks</p><p>domain.com/blog/5-top-datasheets</p></td> 
  </tr> 
  <tr> 
   <td>보도 자료</td> 
   <td><p>한 개의 정확한 일치 HTML 페이지만 검색됩니다.</p><p>domain.com/press-release</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> </td> 
   <td colspan="1"><p>URL 표현식이 비어 있으면 URL 패턴은 홈 페이지만 검색합니다.</p><p>domain.com</p></td> 
  </tr> 
 </tbody> 
</table>
