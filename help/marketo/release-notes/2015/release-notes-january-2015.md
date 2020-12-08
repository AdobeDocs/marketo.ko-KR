---
unique-page-id: 4720758
description: 릴리스 노트 - 2015년 1월 - Marketing Docs - 제품 설명서
title: 릴리스 노트 - 2015년 1월
translation-type: tm+mt
source-git-commit: dc20aede0894a09e6c0bcd3d1580859b5fecb5f1
workflow-type: tm+mt
source-wordcount: '385'
ht-degree: 0%

---


# 릴리스 노트:2015년 1월 {#release-notes-january}

다음 기능은 2015년 1월 릴리스에 포함되어 있습니다. 기능을 사용하려면 Marketing Edition을 확인하십시오. 릴리스 후 다시 돌아와 각 기능에 대한 자세한 아티클에 대한 링크를 찾으십시오.

## 마케팅 자동화 업데이트 {#marketing-automation-updates}

**Rick DeCosta의 새로운 사진!**

Rick은 SmartBear의 마케팅 고객으로 [믿을 수 없는 사진 컬렉션을 보유하고 있습니다](https://www.flickr.com/photos/rickdecosta). 확인해!

## 모바일 친화적인 랜딩 페이지 {#mobile-friendly-landing-pages}

이제 랜딩 페이지 편집기 내에서 랜딩 페이지에 [대한 모바일 보기를](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/add-a-mobile-view-for-your-free-form-landing-page.md) 만들 수 있습니다. 디바이스 유형에 상관없이 효과적으로 메시지를 전달할 수 있고 이동 중에도 간편하게 사용할 수 있도록 컨텐츠를 맞춤화하여 참여도를 높일 수 있습니다. 이 기능은 출시 후 주 동안 점진적으로 롤아웃됩니다.

`<iframe width="420" height="315" src="//www.youtube-nocookie.com/embed/aPQHlG2X6c0" frameborder="0" allowfullscreen></iframe>`

**새로운 ReST API 호출**

리드 및 활동 ReST API에 대한 세 가지 새로운 호출:

* 리드 삭제
* 프로그램 ID로 리드 가져오기
* 리드 삭제

또한 리드 동기화를 위한 새로운 옵션을 사용하여 더욱 빨라진 API 호출을 위해 리드 변경을 비동기식으로 작성할 수 있습니다. 자세한 내용은 [developers.marketing.com에서 릴리스 후 제공됩니다.](http://developers.marketo.com)

**이메일 스크립팅 사용자 정의 개체 지원**

이제 이메일 스크립트 내에서 계정 개체와 관련된 사용자 정의 개체에 액세스할 수 있습니다.

## 실시간 개인화 {#real-time-personalization}

**Google 및 Facebook을 위한 개인화된 리마케팅**

리마케팅은 웹 사이트를 방문한 사람에게 광고를 표시합니다. 이제 실시간 개인화의 데이터를 사용하여 [Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md) 및 [Facebook](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md) 에서 리마케팅 캠페인을 개인화할 수 있습니다. 서로 다른 업계, 이름 있는 계정 목록, 회사 규모 또는 알려진 리드의 모든 데이터를 대상으로 리마케팅합니다.

[지정된 계정 목록 모듈](/help/marketo/product-docs/web-personalization/account-based-web-marketing/create-a-new-account-list.md)

지정된 계정 모듈 기능이 개선되면 사용자에 대한 일치 비율과 유효성 검사가 개선됩니다. 추가 사항:

* 리드의 이메일 주소를 사용하여 지정된 계정 목록에서 조직 일치(RTP 전용 고객도)
* 계정당 최대 10만 개의 레코드 지원
* 보고 다운로드할 CSV 파일 템플릿

![](assets/image2015-1-14-11-3a12-3a16.png)

업데이트된 RTP 태그 옵션

[계정 설정 아래의 RTP 태그](http://docs.marketo.com/display/docs/rtp+tag+implementation) 옵션이 다음을 포함하도록 업데이트되었습니다.

1. CDN 및 비동기(권장 태그)
1. CDN 및 동기식(고속)
1. CDN이 없는 비동기 태그
1. CDN이 없는 동기식 태그

최상의 성능을 위해서는 다음 웹 페이지의 헤더 맨 위에 태그를 배치하는 것이 좋습니다 `<head>`. 모든 태그는 [RTP API를 사용할 수 있도록 허용합니다](http://developers.marketo.com/documentation/websites/rtp-js-api/). RTP 태그를 배포하는 방법에 대한 자세한 내용은 [여기를 참조하십시오](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md).

![](assets/image2015-1-15-13-3a30-3a45.png)
