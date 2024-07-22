---
unique-page-id: 4719400
description: 새 In Zone Web Campaign 만들기 - Marketo 문서 - 제품 설명서
title: Zone Web Campaign에서 새로운 기능 만들기
exl-id: 5cbe80a2-5e20-4e35-a722-b4cb479b4df7
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '693'
ht-degree: 0%

---

# Zone Web Campaign에서 새로운 기능 만들기 {#create-a-new-in-zone-web-campaign}

웹 캠페인은 특정 세그먼트와 연계된 사용자 지정 반응으로, 웹 사이트의 [대화 상자](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md), 영역 내 대체, [위젯 기능](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md) 또는 이메일 알림이 될 수 있습니다. 영역 내 웹 캠페인은 영역 ID를 기반으로 하는 웹 사이트의 요소를 콘텐츠 또는 그래픽 배너로 대체합니다.

## In Zone 웹 캠페인 만들기 {#create-an-in-zone-web-campaign}

1. **웹 캠페인**(으)로 이동합니다.

   ![](assets/image2016-8-18-15-3a54-3a21.png)

1. **새 웹 캠페인 만들기를 선택하십시오.**

   ![](assets/create-new-web-campaign-hand.png)

1. **영역** 캠페인 유형을 선택하십시오. **영역 ID를 사용자 지정하고 추가하십시오.** 캠페인을 **고정**(으)로 설정하고 편집기에 크리에이티브를 추가합니다. 미리 볼 페이지의 URL을 추가하고 **미리 보기**&#x200B;를 클릭하여 캠페인이 사이트에서 어떻게 반응하는지 확인합니다.

   ![](assets/new-3-1.png)

   >[!NOTE]
   >
   >**영역 ID란?**
   >
   >Zone ID 는 &quot;In Zone&quot; 웹 캠페인이 온사이트에서 위치하도록 하려는 위치입니다. &quot;영역 ID&quot;를 찾으려면 웹 사이트로 이동하여 웹 캠페인으로 바꿀 영역을 선택하고 마우스 오른쪽 버튼을 클릭하면 됩니다. Chrome에서 옵션은 &quot;Inspect Element&quot;이고, 다른 브라우저에서는 옵션이 다를 수 있습니다.
   >
   >그런 다음 해당 요소를 검사하고 있으므로 강조 표시된 웹 사이트의 이 섹션과 연결된 &quot;id&quot;를 찾으려고 합니다. 예를 들어 Chrome을 마우스 오른쪽 단추로 클릭하면 강조 표시된 텍스트에 `<div id="featured-slider">`이(가) 표시되면 &quot;featured-slider&quot;가 &quot;영역 id&quot; 섹션에 입력해야 하는 것입니다. 일반적으로 &quot;div id&quot;가 사용되지만 h1 id, p id 등과 같은 모든 ID도 사용할 수 있습니다.

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
   <td colspan="1" rowspan="1">고정 확인란은 영역 내 캠페인에 대해 기본적으로 선택되어 있으며 웹 사이트의 방문자 세션 전체에서 영역 내 캠페인을 해당 영역 id 위치에 유지합니다. 항상 [영역 내]를 [고정]으로 설정하는 것이 좋습니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong> 페이딩</strong> </p></td> 
   <td colspan="1" rowspan="1">[효과 사용] 확인란을 선택하고 [페이딩]을 선택하면 웹 사이트의 영역 ID 영역에 페이딩 효과가 제공됩니다. 영역 내 가 그래픽 배너인 경우 페이지가 먼저 로드되고 페이딩 효과로 캠페인이 활성화됩니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong>슬라이딩</strong></td> 
   <td colspan="1">[효과 사용] 확인란과 [슬라이딩] 옵션을 선택하면 웹 사이트의 Zone id 영역에 슬라이드가 적용됩니다. 영역 내 가 그래픽 배너인 경우 페이지가 먼저 로드되고 왼쪽에서 오른쪽으로 슬라이딩 효과와 함께 캠페인이 활성화됩니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong> 리치 텍스트 편집기  </strong></td> 
   <td colspan="1">리치 텍스트 편집기를 사용하면 텍스트 서식 지정, 연결 및 이미지 삽입이 가능합니다. <a href="/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md">자세한 내용</a> .</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong> 사이트에서 미리 보기   </strong></td> 
   <td colspan="1">캠페인을 시작하기 전에 미리 봅니다. <br> 
    <ul> 
     <li> URL - 캠페인이 실행되는 예제 URL을 입력하여 캠페인이 라이브로 표시되는 예제를 확인합니다.</li> 
     <li>장치 - 데스크탑, 모바일 세로, 모바일 가로, 태블릿 세로, 세로 가로 등 장치별로 캠페인이 어떻게 표시될지 미리 봅니다.</li> 
     <li> 미리 보기 - <strong>미리 보기</strong>를 클릭하여 예제 URL의 새 창을 열어 캠페인이 어떻게 반응하는지 확인합니다.</li> 
     <li> 공유 - 공유 버튼을 사용하여 프록시 캠페인을 볼 수 있는 링크가 있는 전자 메일을 동료에게 보냅니다.</li> 
    </ul></td> 
  </tr> 
 </tbody> 
</table>

>[!TIP]
>
>[기본 제공 템플릿](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md)을 사용하거나 [기존 캠페인을 다시 사용할 수 있도록 템플릿으로 저장](/help/marketo/product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md)하여 캠페인 만들기 프로세스를 가속화하고 간소화하십시오.

>[!NOTE]
>
>**A/B에서 웹 캠페인을 테스트하고 싶으십니까?** 하나 이상의 웹 캠페인을 [A/B 테스트하여 최적의 결과를 얻을 수 있습니다](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/ab-test-your-web-campaign.md). 자동 조정 기능을 사용하면 플랫폼은 성과가 더 좋은 캠페인을 자동으로 인식하고 가장 높은 전환 캠페인을 계속하며 다른 캠페인을 일시 중지합니다.

## 웹 캠페인 편집 {#edit-a-web-campaign}

**웹 캠페인** 페이지에서 캠페인의 **편집**&#x200B;을 클릭합니다.

![](assets/in-zone-web-campaign-edit.png)

>[!NOTE]
>
>원하는 캠페인을 더 쉽게 찾으려면 [필터 기능](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/filter-web-campaigns.md)을 사용하세요.

## 웹 캠페인 미리 보기 {#preview-a-web-campaign}

1. 웹 캠페인 페이지에서 보려는 웹 캠페인의 **미리 보기**&#x200B;를 클릭합니다.

   ![](assets/in-zone-web-campaign-preview.png)

## 웹 캠페인 복제 {#clone-a-web-campaign}

[웹 캠페인 복제](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/clone-a-web-campaign.md)를 참조하십시오.

## 웹 캠페인 삭제 {#delete-a-web-campaign}

1. 웹 캠페인 페이지에서 삭제할 캠페인에 대한 **삭제**&#x200B;를 클릭합니다.

   ![](assets/in-zone-web-campaign-delete.png)

1. 캠페인을 삭제할 것인지 확인하는 확인 메시지가 나타납니다.

>[!MORELIKETHIS]
>
>* [새 위젯 웹 캠페인 만들기](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md)
>* [새 대화 상자 웹 캠페인 만들기](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md)
