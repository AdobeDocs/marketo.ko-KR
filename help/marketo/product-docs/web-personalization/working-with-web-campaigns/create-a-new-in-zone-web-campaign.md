---
unique-page-id: 4719400
description: Zone 웹 Campaign에서 새 만들기 - Marketo 문서 - 제품 설명서
title: 영역 웹 캠페인에서 새 만들기
exl-id: 5cbe80a2-5e20-4e35-a722-b4cb479b4df7
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '693'
ht-degree: 0%

---

# 영역 웹 캠페인에서 새 만들기 {#create-a-new-in-zone-web-campaign}

웹 캠페인은 특정 세그먼트와 연결된 사용자 지정된 반응이며, [대화 상자](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md) 웹 사이트에서, 영역 내 교체, [위젯 기능](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md) 또는 이메일 경고. 영역 내 웹 캠페인은 영역 ID를 기반으로 웹 사이트의 요소를 콘텐츠 또는 그래픽 배너로 바꿉니다.

## 영역 웹 캠페인 만들기 {#create-an-in-zone-web-campaign}

1. 이동 **웹 캠페인**.

   ![](assets/image2016-8-18-15-3a54-3a21.png)

1. 선택 **새 웹 캠페인을 만듭니다.**

   ![](assets/create-new-web-campaign-hand.png)

1. 을(를) 선택합니다 **영역** 캠페인 유형. 사용자 지정 및 추가 **영역 ID.** 캠페인을 (으)로 설정합니다. **고정** 편집기에서 크리에이티브를 추가합니다. 미리 볼 페이지의 URL을 추가하고 을(를) 클릭합니다 **미리 보기** 를 클릭하여 캠페인이 사이트에서 어떻게 반응하는지 확인합니다.

   ![](assets/new-3-1.png)

   >[!NOTE]
   >
   >**영역 ID란?**
   >
   >영역 ID는 &quot;In Zone&quot; 웹 캠페인이 온사이트에 있기를 원하는 곳입니다. 영역 ID를 찾으려면 웹 사이트로 이동하여 웹 캠페인으로 바꿀 영역을 선택하고 마우스 오른쪽 단추를 클릭하면 됩니다. Chrome에서 옵션은 다른 브라우저에서 &quot;Inspect 요소&quot;입니다.
   >
   >그런 다음 웹 사이트의 이 섹션과 연결된 &quot;id&quot;를 찾으려고 합니다. 이 id는 해당 요소를 검사하므로 강조 표시됩니다. 예를 들어, Chrome을 마우스 오른쪽 단추로 클릭하면 강조 표시된 텍스트가 표시됩니다 `<div id="featured-slider">` 그런 다음 &quot;영역 id&quot; 섹션에 &quot;featured-slider&quot;를 입력해야 합니다. 일반적으로 &quot;div id&quot;가 사용되지만 h1 id, p id 등과 같은 모든 ID도 사용할 수 있습니다.

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1">이름</th> 
   <th colspan="1" rowspan="1">설명</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1"><strong> 영역 ID </strong></td> 
   <td colspan="1" rowspan="1"><p>캠페인이 대체하는 웹 사이트 요소의 HTML 코드에 있는 ID의 이름을 입력합니다.</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong> 고정 </strong></p></td> 
   <td colspan="1" rowspan="1">고정 확인란은 기본적으로 영역 내 캠페인에 대해 선택되며, 웹 사이트에서의 방문자 세션 전체에서 영역 ID 위치에 영역 내 캠페인을 유지합니다. 항상 고정 영역으로 설정하는 것이 좋습니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong> 페이딩</strong> </p></td> 
   <td colspan="1" rowspan="1">[효과 사용] 확인란 및 [페이딩]을 선택하면 웹 사이트의 [영역 ID] 영역에 페이드 효과를 제공합니다. 인존이 그래픽 배너인 경우 페이지가 먼저 로드되고 페이드 효과로 캠페인이 활성화됩니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong>슬라이딩</strong></td> 
   <td colspan="1">[효과 사용] 확인란 및 [슬라이딩] 옵션을 선택하면 웹 사이트의 [영역 ID] 영역에 슬라이딩이 적용됩니다. 인존이 그래픽 배너인 경우 페이지가 먼저 로드되고 캠페인이 왼쪽에서 오른쪽으로 슬라이딩 효과로 활성화됩니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong> 리치 텍스트 편집기  </strong></td> 
   <td colspan="1">리치 텍스트 편집기를 사용하면 텍스트 형식 지정, 연결 및 이미지 삽입을 할 수 있습니다. <a href="/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md">자세한 내용은 여기 를 참조하십시오</a> .</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong> 사이트에서 미리 보기   </strong></td> 
   <td colspan="1">캠페인을 시작하기 전에 미리 봅니다. <br> 
    <ul> 
     <li> URL - 캠페인이 실행되는 예제 URL을 입력하여 캠페인이 라이브로 표시되는 방법의 미리 보기 예를 볼 수 있습니다.</li> 
     <li>장치 - 장치별로 캠페인이 표시되는 방식을 미리 봅니다. 데스크탑, 모바일 세로, 모바일 가로, 태블릿 세로, 세로 가로.</li> 
     <li> 미리 보기 - 클릭 <strong>미리 보기</strong> url 예제 의 새 창을 열어 캠페인이 어떻게 반응하는지 확인합니다.</li> 
     <li> 공유 - 공유 단추를 사용하여 링크를 사용하여 동료에게 전자 메일을 전송하여 프록시 캠페인을 볼 수 있습니다.</li> 
    </ul></td> 
  </tr> 
 </tbody> 
</table>

>[!TIP]
>
>Adobe의 [내장 템플릿](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md) 또는 [기존 캠페인 저장](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md) 을 템플릿으로 사용하여 다시 사용할 수 있습니다.

>[!NOTE]
>
>**A/B 웹 캠페인을 테스트하시겠습니까?** 하나 이상의 웹 캠페인이 [최적의 결과를 위해 테스트된 A/B](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/ab-test-your-web-campaign.md). 자동 조정 기능을 사용하여 플랫폼은 더 나은 성과를 자동으로 인식하고, 전환율이 가장 높은 캠페인을 계속하며, 다른 캠페인을 일시 중지합니다.

## 웹 캠페인 편집 {#edit-a-web-campaign}

에서 **웹 캠페인** 페이지를 클릭한 다음 **편집** 클릭합니다.

![](assets/in-zone-web-campaign-edit.png)

>[!NOTE]
>
>원하는 캠페인을 쉽게 찾으려면 를 사용하십시오 [필터 기능](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/filter-web-campaigns.md).

## 웹 캠페인 미리 보기 {#preview-a-web-campaign}

1. 웹 캠페인 페이지에서 **미리 보기** 웹 캠페인에서 보려는 작업입니다.

   ![](assets/in-zone-web-campaign-preview.png)

## 웹 캠페인 복제 {#clone-a-web-campaign}

자세한 내용은 [웹 캠페인 복제](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/clone-a-web-campaign.md).

## 웹 캠페인 삭제 {#delete-a-web-campaign}

1. 웹 캠페인 페이지에서 **삭제** 삭제할 캠페인을 삭제합니다.

   ![](assets/in-zone-web-campaign-delete.png)

1. 캠페인을 삭제할지 여부를 확인하는 확인 메시지가 나타납니다.

>[!MORELIKETHIS]
>
>* [새 위젯 웹 캠페인 만들기](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md)
>* [새 대화 상자 웹 캠페인 만들기](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md)

