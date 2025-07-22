---
unique-page-id: 11385579
description: 콘텐츠 패턴 만들기 - Marketo 문서 - 제품 설명서
title: 콘텐츠 패턴 만들기
exl-id: 963529fb-1b30-486c-b97d-3ff697f91258
feature: Predictive Content
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---

# 콘텐츠 패턴 만들기 {#create-content-patterns}

컨텐츠 패턴을 설정하면 웹 방문자가 컨텐츠 패턴과 관련된 HTML 웹 페이지를 클릭할 때 컨텐츠가 자동으로 검색됩니다. HTML 페이지(블로그 게시물, 보도 자료, 뉴스 기사)를 모든 컨텐츠 페이지에 컨텐츠 조각으로 추가하는 데 사용됩니다. 자동 검색은 콘텐츠 패턴을 기반으로 하는 경우 웹 방문자가 페이지 링크를 보거나 클릭할 때 정의된 URL 패턴과 관련된 HTML 페이지를 검색하고 추적합니다. 이 콘텐츠 조각(URL, 페이지 이름 및 메타데이터(이미지 URL 및 설명을 포함)은 모든 콘텐츠 페이지에 추가되어 예측 콘텐츠를 준비합니다. PDF 및 포함된 비디오와 같은 다른 콘텐츠를 자동으로 검색하려면 [콘텐츠 검색을 활성화](/help/marketo/product-docs/predictive-content/getting-started/enable-content-discovery.md)해야 합니다.

1. **[!UICONTROL Content Settings]**(으)로 이동합니다.

   ![](assets/settings-dropdown-hand-2.png)

1. **[!UICONTROL URL Patterns]**&#x200B;을(를) 클릭합니다.

   ![](assets/click-url-patterns-hand.png)

1. 정보를 입력할 수 있는 행을 열려면 **+**&#x200B;을(를) 클릭하십시오.

   ![](assets/content-settings-create-patterns-hand.png)

1. 웹 페이지가 있는 도메인의 URL 확장을 추가합니다. 범주(예: [!UICONTROL Blog], [!UICONTROL Article], [!UICONTROL Data Sheet], [!UICONTROL Press Release])를 선택하십시오.

   ![](assets/content-settings-create-content-patterns-dm-hands.png)

   >[!NOTE]
   >
   >오른쪽의 드롭다운 목록에 있는 항목은 [만든 범주](/help/marketo/product-docs/predictive-content/getting-started/set-up-categories.md)를 설정할 때 설정한 범주를 반영합니다.

1. 다른 경로를 추가하려면 **+**&#x200B;을(를) 클릭하십시오.

   ![](assets/url-patterns-add2.png)

1. 추가 경로에 대한 확장 및 범주를 추가하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/url-patterns-save.png)

## 콘텐츠 패턴 규칙 {#content-pattern-rules}

* 식의 어디에서나 와일드카드를 사용할 수 있습니다(예: _domain.com/&#42;_, _domain.com/&#42;블로그&#42;_).

* 패턴 검색을 계속하려면 식이 끝날 때 /&#42;을(를) 사용하는 것이 좋습니다(예: _domain.com/blog/&#42;_ 블로그 폴더의 모든 게시물을 검색)
* 콘텐츠 패턴은 대소문자를 구분하지 않습니다(예: _domain.com/Blog/&#42;_&#x200B;이(가) _domain.com/Blog_ 및 _domain.com/blog_&#x200B;에서 모든 html 페이지를 검색합니다).

* URL 매개 변수는 검색되지 않습니다(이렇게 하면 콘텐츠 URL은 동일하지만 매개 변수가 다른 여러 항목을 검색하지 않음).

## 예 {#examples}

_domain.com_&#x200B;의 경우:

<table> 
 <tbody> 
  <tr> 
   <th>URL 패턴</th> 
   <th>결과</th> 
  </tr> 
  <tr> 
   <td>blog/*</td> 
   <td><p>domain.com/blog/ 패턴과 일치하는 모든 콘텐츠를 검색합니다.</p><p>domain.com/blog/5-top-tricks</p><p>domain.com/blog/2017/new-year-solutions</p><p>domain.com/Blog/3-best-recipes</p></td> 
  </tr> 
  <tr> 
   <td>article/2017/*</td> 
   <td><p>domain.com/article/2017/ 패턴과 일치하는 모든 콘텐츠를 검색합니다.</p><p>domain.com/article/2017/5-top-tricks</p></td> 
  </tr> 
  <tr> 
   <td><img alt="—" width="80" src="assets/image2017-3-24-10-3a38-3a46.png" data-linked-resource-id="12976559" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="11385579" title="--"></td> 
   <td><p>"데이터시트:"라는 단어가 포함된 URL을 검색합니다.</p><p>domain.com/datasheets/5-top-tricks</p><p>domain.com/blog/5-top-datasheets</p></td> 
  </tr> 
  <tr> 
   <td>보도 자료</td> 
   <td><p>정확히 일치하는 하나의 HTML 페이지만 검색됩니다.</p><p>domain.com/press-release</p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> </td> 
   <td colspan="1"><p>URL 표현식이 비어 있는 경우 URL 패턴은 홈 페이지만 검색합니다.</p><p>domain.com</p></td> 
  </tr> 
 </tbody> 
</table>
