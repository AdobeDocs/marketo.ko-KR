---
unique-page-id: 7504218
description: Google Universal Analytics의 사용자 정의 RTP 보고서 - Marketo 문서 - 제품 설명서
title: Google Universal Analytics의 사용자 정의 RTP 보고서
exl-id: c8b1e653-03b8-48bc-b80d-3e6cdf3485c3
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '362'
ht-degree: 7%

---

# Google Universal Analytics의 사용자 정의 RTP 보고서 {#custom-rtp-reports-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[Google Universal Analytics와 RTP 통합](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

이 문서에서는 GUA(Google Universal Analytics)에 대한 RTP 사용자 지정 보고서를 설정하는 방법에 대해 설명합니다.  RTP에서 GUA로 전송되는 데이터는 라는 두 개의 별도 사용자 정의 보고서로 설정할 수 있습니다.

* RTP B2B
* RTP 참여

## [!UICONTROL Custom Report] 설정 중 {#setting-up-a-custom-report}

1. Google Analytics에 로그인.

1. 상단 메뉴에서 **[!UICONTROL Customization]**&#x200B;을(를) 클릭합니다.

1. **[!UICONTROL New Custom Report]**&#x200B;를 클릭합니다.

![](assets/image2015-3-22-16-3a10-3a48.png)

## RTP B2B 보고서 {#rtp-b-b-report}

1. 보고서 이름을 **RTP B2B 보고서**&#x200B;로 지정합니다.

1. 첫 번째 탭의 이름을 **[!UICONTROL Industry]**&#x200B;로 지정합니다.

>[!NOTE]
>
>**이 탭을 복제**&#x200B;하고 유사한 탭을 추가로 만듭니다. - 5단계)

1. **[!UICONTROL Explorer]** 보고서 유형을 선택하십시오.

   ![](assets/image2015-3-22-16-3a15-3a25.png)

1. **[!UICONTROL Metric Groups]** 섹션에서 비즈니스와 관련된 지표를 선택합니다.

   a. 다음 사항을 권장합니다.

   ![](assets/image2015-3-22-16-3a16-3a40.png)

1. 이 탭을 4번 복제하고 이름을 지정합니다.

   1. **업계**
   1. **그룹**
   1. **범주**
   1. **ABM**
   1. **조직**

   ![](assets/image2015-3-22-16-3a17-3a41.png)

1. **Dimension 드릴다운** 섹션에서 각 탭의 관련 차원을 아래와 같이 설정합니다.

<table>
 <thead>
  <tr>
   <th>
    <div>
      탭 이름
    </div></th>
   <th>
    <div>
      Dimension 드릴다운
    </div></th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>업종</td>
   <td><img src="assets/1.png" data-linked-resource-id="7514675" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
  <tr>
   <td>그룹</td>
   <td><img src="assets/2.png" data-linked-resource-id="7514674" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
  <tr>
   <td>카테고리</td>
   <td><img src="assets/3.png" data-linked-resource-id="7514673" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
  <tr>
   <td>ABM</td>
   <td><img src="assets/5.png" data-linked-resource-id="7514677" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
  <tr>
   <td>조직</td>
   <td><img src="assets/5.png" data-linked-resource-id="7514677" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
 </tbody>
</table>

1. 필터를 설정하지 말고 이 보고서를 **[!UICONTROL All Web Site Data]**&#x200B;에서 사용할 수 있도록 설정하십시오(또는 특정 Analytics 계정과 관련된 경우 변경하지 마십시오).

1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/image2015-3-22-16-3a21-3a23.png)

## RTP 참여 보고서 {#rtp-engagement-report}

1. 보고서 이름을 **RTP 참여 보고서**&#x200B;로 지정합니다.

1. 첫 번째 탭 이름을 **[!UICONTROL All Engagement]**(으)로 설정합니다.

>[!NOTE]
>
>이 탭을 복제하고 유사한 탭을 추가로 만듭니다(5단계).

1. **[!UICONTROL Explorer]** 보고서 유형을 선택하십시오.

   ![](assets/image2015-3-22-16-3a23-3a36.png)

1. [!UICONTROL Metric Groups] 섹션에서 비즈니스와 관련된 지표를 선택합니다. 권장 사항은 다음과 같습니다.

   ![](assets/image2015-3-22-16-3a24-3a57.png)

1. 이 탭을 4번 복제하고 이름을 지정합니다.

   1. **모든 참여**
   1. **업종별 참여**
   1. 그룹별 **참여**
   1. 범주별 **참여**
   1. ABM의 **참여**

   ![](assets/image2015-3-22-16-3a26-3a21.png)

1. **Dimension 드릴다운** 섹션에서 각 탭의 관련 차원을 아래와 같이 설정합니다.

<table>
 <thead>
  <tr>
   <th>
    <div>
      탭 이름
    </div></th>
   <th>
    <div>
      Dimension 드릴다운
    </div></th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>모든 참여</td>
   <td><img src="assets/a.png" data-linked-resource-id="7514683" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
  <tr>
   <td>ABM에 의한 참여</td>
   <td><img width="277" src="assets/4.png" data-linked-resource-id="7514678" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
  <tr>
   <td>범주별 참여</td>
   <td><img src="assets/a.png" data-linked-resource-id="7514683" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
  <tr>
   <td>그룹별 참여</td>
   <td><img src="assets/c.png" data-linked-resource-id="7514681" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
  <tr>
   <td>업종별 참여</td>
   <td><img src="assets/b.png" data-linked-resource-id="7514682" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504218"></td>
  </tr>
 </tbody>
</table>

1. 다음 필터를 설정합니다.

<table>
 <thead>
  <tr>
   <th>
    <div>
      Inc/Exc
    </div></th>
   <th>
    <div>
      필드
    </div></th>
   <th>
    <div>
      일치 유형
    </div></th>
   <th>
    <div>
      값
    </div></th>
   <th colspan="1">
    <div>
      댓글
    </div></th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td><p>포함</p></td>
   <td><p><span class="uicontrol">이벤트 범주</span></p></td>
   <td>Regex</td>
   <td>RTP-Campaigns|RTP-Recommendations|RTP-Segments</td>
   <td colspan="1">RTP와 관련이 없는 다른 모든 사용자 지정 이벤트를 필터링합니다.</td>
  </tr>
  <tr>
   <td>제외</td>
   <td><span class="uicontrol">이벤트 레이블</span></td>
   <td>Regex</td>
   <td>#</td>
   <td colspan="1">캠페인 이름에서 #을 사용하여 보고서 캠페인에서 필터링할 수 있습니다.</td>
  </tr>
 </tbody>
</table>

1. 이 보고서를 **[!UICONTROL All Web Site Data]**&#x200B;에서 사용할 수 있도록 설정합니다(필요한 경우 변경).

   ![](assets/image2015-3-22-16-3a29-3a5.png)

1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

![](assets/image2015-3-22-16-3a30-3a0.png)

>[!MORELIKETHIS]
>
>[Google Universal Analytics와 RTP 통합](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)
>
>[Google Universal Analytics의 사용자 지정 RTP 대시보드](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-dashboards-in-google-universal-analytics.md)
