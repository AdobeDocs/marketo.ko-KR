---
unique-page-id: 4719400
description: 영역 웹 캠페인 - Marketing Docs - 제품 문서에서 새 만들기
title: 영역에서 새 웹 캠페인 만들기
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '694'
ht-degree: 0%

---


# 영역에서 새 웹 캠페인 만들기 {#create-a-new-in-zone-web-campaign}

웹 캠페인은 특정 세그먼트와 연관된 사용자 지정 응답이며 웹 사이트의 [대화 상자](create-a-new-dialog-web-campaign.md) , 영역 교체, [위젯 기능](create-a-new-widget-web-campaign.md) 또는 이메일 경고일 수 있습니다. 영역 ID를 기반으로 하는 웹 사이트의 요소를 컨텐츠 또는 그래픽 배너로 영역 내 웹 캠페인으로 대체합니다.

## 영역 내 웹 캠페인 만들기 {#create-an-in-zone-web-campaign}

1. 웹 **캠페인으로 이동합니다**.

   ![](assets/image2016-8-18-15-3a54-3a21.png)

1. 새 **웹 캠페인 만들기를 선택합니다.**

   ![](assets/create-new-web-campaign-hand.png)

1. 영역 **내** 캠페인 유형을 선택합니다. 영역 ID를 사용자 정의하고 **추가합니다.** 캠페인을 고정 **으로** 설정하고 편집기에 크리에이티브를 추가합니다. 미리 볼 페이지의 URL을 추가하고 **미리** 보기를 클릭하여 캠페인이 사이트에서 어떻게 반응하는지 확인합니다.

   ![](assets/new-3-1.png)

   >[!NOTE]
   >
   >**정의**
   >
   >
   >**영역 ID란?**
   >
   >
   >영역 ID는 &quot;영역 내&quot; 웹 캠페인을 온사이트에 배치하려는 곳입니다. &quot;영역 ID&quot;를 찾으려면 웹 사이트로 이동하여 웹 캠페인으로 대체할 영역을 선택하고 마우스 오른쪽 단추를 클릭하면 됩니다. 크롬에서 옵션은 &quot;Inspect 요소&quot;이며, 다른 브라우저에서는 다를 수 있습니다.
   >
   >
   >그런 다음 웹 사이트의 이 섹션과 연관된 &quot;id&quot;를 찾을 수 있습니다. 이 ID는 해당 요소를 검사하므로 강조 표시됩니다. 예를 들어 Chrome에서 마우스 오른쪽 버튼을 클릭하면 강조 표시된 텍스트가 &quot; `<div id="featured-slider">` 특집 슬라이더&quot;로 표시되고 &quot;영역 id&quot; 섹션에 입력해야 하는 내용이 됩니다. 일반적으로 &quot;div id&quot;가 사용되지만 h1 id, p id 등과 같은 모든 ID도 사용할 수 있습니다.

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
   <td colspan="1" rowspan="1">고정 확인란은 기본적으로 시작 영역 캠페인에 대해 선택되어 있으며 웹 사이트의 방문자 세션 내내 영역 ID 위치에 있는 영역 내 캠페인을 유지합니다. 항상 [시작 영역]을 [고정]으로 설정하는 것이 좋습니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p><strong> 페이드</strong> </p></td> 
   <td colspan="1" rowspan="1">효과 사용 확인란 및 페이드를 선택하면 웹 사이트의 영역 ID 영역에 페이드 효과가 나타납니다. 시작 영역이 그래픽 배너인 경우 페이지가 먼저 로드되고 페이드 효과로 캠페인이 활성화됩니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong>슬라이딩</strong></td> 
   <td colspan="1">[효과 사용] 확인란 및 [슬라이딩] 옵션을 선택하면 웹 사이트의 영역 ID 영역에 슬라이딩이 적용됩니다. 인 존이 그래픽 배너인 경우, 페이지가 먼저 로드되고 나서 캠페인이 왼쪽에서 오른쪽으로 슬라이딩 효과로 활성화됩니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong> 리치 텍스트 편집기  </strong></td> 
   <td colspan="1">리치 텍스트 편집기를 사용하면 텍스트 서식, 연결 및 이미지 삽입 작업을 수행할 수 있습니다. <a href="using-the-web-personalization-rich-text-editor.md">자세한 내용을 살펴보십시오</a> .</td> 
  </tr> 
  <tr> 
   <td colspan="1"><strong> 사이트에서 미리 보기   </strong></td> 
   <td colspan="1">캠페인을 실행하기 전에 미리 봅니다. <br> 
    <ul> 
     <li> URL - 캠페인이 라이브로 표시되는 방식을 보여주는 미리 보기 예를 보려면 캠페인이 실행되는 예제 URL을 입력합니다.</li> 
     <li>장치 - 장치가 캠페인을 어떻게 표시할지 미리 봅니다.데스크탑, 모바일 세로, 모바일 가로, 태블릿 세로, 세로 가로</li> 
     <li> 미리 보기 - <strong>미리</strong> 보기를 클릭하여 예제 URL의 새 창을 열고 캠페인이 어떻게 반응하는지 확인합니다.</li> 
     <li> 공유 - 공유 단추를 사용하여 프록시 캠페인을 볼 수 있는 링크가 있는 이메일을 동료에게 보냅니다.</li> 
    </ul></td> 
  </tr> 
 </tbody> 
</table>

>[!TIP]
>
>내장된 템플릿을 [사용하거나 기존 캠페인을](../../../product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md) 템플릿으로 저장하여 재사용할 수 있으므로 캠페인 [](../../../product-docs/web-personalization/using-templates/using-templates-to-create-web-campaigns.md) 제작 프로세스를 가속화하고 간소화할 수 있습니다.

>[!NOTE]
>
>**웹 캠페인을 A/B 테스트하시겠습니까?** 하나 이상의 웹 캠페인을 [A/B로 테스트하여 최적의 결과를 얻을 수 있습니다](ab-test-your-web-campaign.md). 자동 조정 기능을 사용하면 플랫폼은 자동으로 더 나은 성과를 내는 캠페인을 인식하며 전환율이 가장 높은 캠페인을 지속하고 다른 캠페인을 일시 중지합니다.

## 웹 캠페인 편집 {#edit-a-web-campaign}

웹 **캠페인** 페이지에서 **캠페인에서** 편집을클릭합니다.

![](assets/in-zone-web-campaign-edit.png)

>[!NOTE]
>
>원하는 캠페인을 쉽게 찾으려면 [필터 기능을 사용하십시오](filter-web-campaigns.md).

## 웹 캠페인 미리 보기 {#preview-a-web-campaign}

1. 웹 캠페인 페이지에서 보려는 웹 캠페인에서 **미리 보기*를 클릭합니다.

   ![](assets/in-zone-web-campaign-preview.png)

## 웹 캠페인 복제 {#clone-a-web-campaign}

웹 [캠페인 복제를 참조하십시오](clone-a-web-campaign.md).

## 웹 캠페인 삭제 {#delete-a-web-campaign}

1. 웹 캠페인 페이지에서 삭제할 캠페인에서 **삭제 **를 클릭합니다.

   ![](assets/in-zone-web-campaign-delete.png)

1. 캠페인을 삭제할지 여부를 확인하는 확인 메시지가 나타납니다.

>[!MORELIKETHIS]
>
>* [새 위젯 웹 캠페인 만들기](create-a-new-widget-web-campaign.md)
>* [새 대화 상자 웹 캠페인 만들기](create-a-new-dialog-web-campaign.md)

