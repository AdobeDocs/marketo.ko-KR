---
unique-page-id: 7504238
description: Google Universal Analytics의 사용자 정의 RTP 대시보드 - Marketo 문서 - 제품 설명서
title: Google Universal Analytics의 사용자 정의 RTP 대시보드
exl-id: 712c71b6-74eb-4743-9ca8-50c912278e62
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '748'
ht-degree: 0%

---

# Google Universal Analytics의 사용자 정의 RTP 대시보드 {#custom-rtp-dashboards-in-google-universal-analytics}

>[!PREREQUISITES]
>
>[RTP를 Google Universal Analytics와 통합](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

이 게시물에서는 GUA(Google Universal Analytics)에서 RTP 대시보드를 설정하는 방법을 설명합니다. RTP에서 GUA로 전송되는 데이터는 라는 두 개의 별도 사용자 정의 대시보드로 설정할 수 있습니다.

* RTP B2B
* RTP 참여

## 사용자 정의 대시보드 설정 {#setting-up-a-custom-dashboard}

1. Google Analytics에 로그인합니다. 클릭 **보고** 을 클릭합니다. 클릭 **대시보드** 및 **+새 사용자 지정 대시보드**.

   ![](assets/image2015-3-22-16-3a41-3a29.png)

1. 선택 **빈 캔버스**, 추가 **대시보드 이름** 및 클릭 **대시보드 만들기**.

1. 클릭 **위젯 추가** 새 위젯을 만듭니다.

   ![](assets/image2015-3-22-16-3a46-3a48.png)

## RTP B2B 대시보드 {#rtp-b-b-dashboard}

이 대시보드를 통해 사용자는 B2B 관점에서 웹 사이트 성과를 분석할 수 있습니다.

업계, 매출, 규모, 계정 기반 목록 및 타겟 세그먼트별로 방문 소스 및 현장 행동과 같은 정보를 제공합니다.

대시보드는 3개의 열로 구성됩니다

* 트래픽 소스
* 세분화
* 그래픽 드릴다운

1. (이)라는 새 대시보드 만들기 **RTP B2B 대시보드** 및 다음 위젯을 정의합니다.

![](assets/image2015-3-22-16-3a50-3a3.png)

<table> 
 <thead> 
  <tr> 
   <th> 
    <div>
      열 1 - 트래픽 소스
    </div></th> 
   <th> 
    <div> <strong>열 2 - 세분화</strong> 
    </div></th> 
   <th> 
    <div> <strong>열 3 - 그래픽 드릴다운</strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul> 
     <li>이름: 세그먼트 및 채널별 세션</li> 
     <li>위젯 유형: 막대<br></li> 
     <li>다음을 보여주는 막대 차트 만들기: 세션</li> 
     <li>그룹화 기준: 이벤트 레이블</li> 
     <li>피벗 기준: 기본 채널 그룹화</li> 
     <li>필터: <br>표시만 | 이벤트 범주(포함) RTP-Segments</li> 
    </ul><p><img width="300" src="assets/image2015-3-23-11-3a32-3a13.png" data-linked-resource-id="7504247" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>이름: 세그먼트화된 RTP 사용자 수</li> 
     <li>유형: 2.1 지표</li> 
     <li>다음 지표 표시: 사용자<br></li> 
     <li>필터: <br>표시만 | 이벤트 범주(포함) RTP-Segments</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a6.png" data-linked-resource-id="7504249" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>이름: 산업별 세션</li> 
     <li>유형: 원형<br></li> 
     <li>다음을 보여주는 파이 차트 만들기: 세션</li> 
     <li>그룹화 기준: RTP-Industry</li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a33-3a27.png" data-linked-resource-id="7504250" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <th> 
    <ul> 
     <li><strong>이름: 업계 및 채널별 세션</strong></li> 
     <li><strong>위젯 유형: 막대</strong></li> 
     <li><strong>다음을 보여주는 막대 차트 만들기: 세션</strong></li> 
     <li><strong>그룹화 기준: RTP-Industry</strong></li> 
     <li><strong>피벗 기준: 기본 채널 그룹화</strong><br><img width="300" src="assets/image2015-3-23-11-3a33-3a52.png" data-linked-resource-id="7504252" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></li> 
    </ul></th> 
   <th> 
    <ul> 
     <li><strong>이름: 국가별로 세그먼트화된 세션</strong></li> 
     <li><strong>유형: Geomap</strong></li> 
     <li><strong>선택한 지표 플롯: 국가 | 세션</strong></li> 
     <li><strong>지역 선택: 세계</strong></li> 
     <li><strong>필터: 표시만 | 이벤트 범주(포함) RTP-Segments</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a34-3a18.png" data-linked-resource-id="7504253" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li><strong>이름: RTP 범주별 세션</strong></li> 
     <li><strong>유형: 원형</strong></li> 
     <li><strong>다음을 보여주는 파이 차트 만들기: 세션</strong></li> 
     <li><strong>그룹화 기준: RTP-Category</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a35-3a1.png" data-linked-resource-id="7504254" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>이름: 상위 Target 세그먼트</li> 
     <li>유형: 막대</li> 
     <li>다음을 보여주는 막대 차트 만들기: 사용자</li> 
     <li>그룹화 기준: 이벤트 작업</li> 
     <li>필터: 표시만 | 이벤트 범주(포함) RTP-Segments</li> 
    </ul><p><img width="350" src="assets/add-a-widget.png" data-linked-resource-id="11382874" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul> 
     <li>이름: RTP-그룹별 세션</li> 
     <li>유형: 막대<br></li> 
     <li>다음을 보여주는 막대 차트를 만듭니다. 세션</li> 
     <li>그룹화 기준: RTP-Group</li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a35-3a54.png" data-linked-resource-id="7504256" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
  </tr> 
  <tr> 
   <th> </th> 
   <th> 
    <ul> 
     <li>이름: 상위 세그먼트별 세션 및 목표</li> 
     <li>유형: 테이블<br></li> 
     <li>다음 열을 표시합니다. <br>이벤트 레이블 | 세션 | 목표 전환율</li> 
     <li>필터: <br>표시만 | 이벤트 범주(포함) RTP-Segments</li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a36-3a15.png" data-linked-resource-id="7504257" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
   <th> </th> 
  </tr> 
 </tbody> 
</table>

## RTP 참여 대시보드 {#rtp-engagement-dashboard}

이 대시보드를 사용하여 사용자가 자신의 RTP 캠페인 성능 및 권장 사항 엔진 참여를 분석할 수 있습니다. 평균 비교를 제공합니다. 세션 기간 및 다음 기간 사이의 세션당 페이지 수:

* 참여하지 않음
* 참여(개인화된 캠페인에 대한 노출 횟수 및 클릭 수)
* 추천 엔진 및 상위 추천 콘텐츠 클릭

(이)라는 새 대시보드 만들기 **RTP 참여 대시보드** 및 다음 위젯을 정의합니다.

![](assets/image2015-3-22-17-3a7-3a19.png)

<table> 
 <thead> 
  <tr> 
   <th> 
    <div> <strong>1열 캠페인 노출</strong> 
    </div></th> 
   <th> 
    <div> <strong>2열 캠페인 클릭스루</strong> 
    </div></th> 
   <th> 
    <div> <strong>3열 추천 엔진</strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul> 
     <li>이름: <strong>총 CTA(참여)</strong></li> 
     <li>유형: <strong>2.1메트릭 </strong></li> 
     <li>다음 지표를 표시합니다. <strong>총 이벤트 수</strong></li> 
     <li>필터:<br><strong>[only show] 이벤트 범주 (contains): RTP-Campaigns</strong><br><strong>[only show] 이벤트 작업(정확히 일치): 노출</strong><strong>[표시하지 않음] 이벤트 레이블(포함): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a37-3a55.png" data-linked-resource-id="7504259" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul> 
     <li>이름: <strong>총 CTA(클릭스루)</strong></li> 
     <li>유형: <strong>2.1메트릭 </strong></li> 
     <li>다음 지표를 표시합니다. <strong>총 이벤트 수</strong></li> 
     <li>필터:<br><strong>[only show] 이벤트 범주 (contains): RTP-Campaigns</strong><br><strong>[only show] 이벤트 작업(정확히 일치): 클릭 수</strong><strong>[표시하지 않음] 이벤트 레이블(포함): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a38-3a12.png" data-linked-resource-id="7504261" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul> 
     <li>이름: <strong>CRE - 총 클릭 수</strong></li> 
     <li>유형: <strong>2.1메트릭</strong><br></li> 
     <li>다음 지표를 표시합니다. <strong>페이지 보기 수</strong></li> 
     <li>필터: <strong>[only show] 페이지 (포함): rcmd</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a38-3a30.png" data-linked-resource-id="7504262" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> 
    <ul> 
     <li>이름: <strong>평균 세션 기간(참여)</strong></li> 
     <li>유형: <strong>2.1메트릭 </strong></li> 
     <li>다음 지표를 표시합니다. <strong>평균 세션 기간</strong></li> 
     <li>필터:<br><strong>[only show] 이벤트 범주(정확히 일치): RTP-Campaigns</strong><br><strong>[only show] 이벤트 작업(정확히 일치): 노출</strong><strong>[표시하지 않음] 이벤트 레이블(포함): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a41-3a21.png" data-linked-resource-id="7504264" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>이름: <strong>평균 세션 기간(클릭스루)</strong></li> 
     <li>유형: <strong>2.1메트릭 </strong></li> 
     <li>다음 지표를 표시합니다. <strong>평균 세션 기간</strong></li> 
     <li>필터:<br><strong>[only show] 이벤트 범주(정확히 일치): RTP-Campaigns</strong><br><strong>[only show] 이벤트 작업(정확히 일치): 클릭 수</strong><strong>[표시하지 않음] 이벤트 레이블(포함): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a41-3a37.png" data-linked-resource-id="7504265" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>이름: <strong>CRE - 상위 권장 콘텐츠</strong></li> 
     <li>유형: <strong>표</strong><br></li> 
     <li>다음 열을 표시합니다. <br><strong>페이지 제목 | 페이지 보기 수</strong><br></li> 
     <li>필터:<br>필터: <strong>[only show] 페이지 (포함): rcmd</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a41-3a51.png" data-linked-resource-id="7504266" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>이름: <strong>페이지 / 세션(참여)</strong></li> 
     <li>유형: <strong>2.1메트릭 </strong></li> 
     <li>다음 지표를 표시합니다. <strong>페이지 / 세션</strong></li> 
     <li>필터:<br><strong>[only show] 이벤트 범주(정확히 일치): RTP-Campaigns</strong></li> 
     <li><strong>[only show] 이벤트 작업(정확히 일치): 노출</strong></li> 
     <li><strong>[표시하지 않음] 이벤트 레이블(포함): #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a10.png" data-linked-resource-id="7504267" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>이름: <strong>페이지 / 세션(클릭스루)</strong></li> 
     <li>유형: <strong>2.1메트릭 </strong></li> 
     <li>다음 지표를 표시합니다. <strong>페이지 / 세션</strong></li> 
     <li>필터:<br><strong>[only show] 이벤트 범주(정확히 일치): RTP-Campaigns</strong></li> 
     <li><strong>[only show] 이벤트 작업(정확히 일치): 클릭 수</strong></li> 
     <li><strong>[표시하지 않음] 이벤트 레이블(포함): #</strong></li> 
    </ul><p><strong><img width="350" src="assets/image2015-3-23-11-3a42-3a32.png" data-linked-resource-id="7504268" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>이름: <strong>CTA별 노출 횟수</strong></li> 
     <li>유형: <strong>표</strong></li> 
     <li>다음 열을 표시합니다. <strong>이벤트 레이블 | 총 이벤트 | 사용자</strong></li> 
     <li>필터:<br><strong>[only show] 이벤트 범주(정확히 일치): RTP-Campaigns</strong><br><strong>[only show] 이벤트 작업(정확히 일치): 노출</strong><strong>[표시하지 않음] 이벤트 레이블(포함): #</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a42-3a48.png" data-linked-resource-id="7504269" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul> 
     <li>이름: <strong>CTA의 클릭스루</strong></li> 
     <li>유형: <strong>표</strong></li> 
     <li>다음 열을 표시합니다. <strong>이벤트 레이블 | 총 이벤트 | 사용자</strong></li> 
     <li>필터:<br><strong>[only show] 이벤트 범주(정확히 일치): RTP-Campaigns</strong><br><strong>[only show] 이벤트 작업(정확히 일치): 클릭 수</strong></li> 
    </ul><p><img width="350" src="assets/image2015-3-23-11-3a43-3a4.png" data-linked-resource-id="7504270" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[RTP를 Google Universal Analytics와 통합](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-reports-in-google-universal-analytics.md)
>
>[Google Universal Analytics의 사용자 정의 RTP 보고서](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/custom-rtp-reports-in-google-universal-analytics.md)
