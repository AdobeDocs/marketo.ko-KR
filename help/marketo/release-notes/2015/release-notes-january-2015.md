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

다음 기능은 2015년 1월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 확인하려면 Marketing To Edition을 확인하십시오. 릴리스 후 다시 돌아와 각 기능에 대한 자세한 아티클에 대한 링크를 찾으십시오.

## 마케팅 자동화 업데이트 {#marketing-automation-updates}

**Rick DeCosta의 새로운 사진!**

Rick은 SmartBear의 Marketing To 고객이며 [믿을 수 없는 사진 컬렉션](https://www.flickr.com/photos/rickdecosta)을 보유하고 있습니다. 확인해!

## 모바일 친화적인 랜딩 페이지 {#mobile-friendly-landing-pages}

이제 랜딩 페이지 편집기 내에서 랜딩 페이지[에 대한 모바일 보기를 만들 수 있습니다. ](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/add-a-mobile-view-for-your-free-form-landing-page.md) 디바이스 유형에 상관없이 메시지를 효과적으로 전달하고 이동 중에도 간편하게 사용할 수 있도록 컨텐츠를 맞춤화하여 참여를 높일 수 있습니다. 이 기능은 출시 후 주 동안 점진적으로 롤아웃됩니다.

`<iframe width="420" height="315" src="//www.youtube-nocookie.com/embed/aPQHlG2X6c0" frameborder="0" allowfullscreen></iframe>`

**새로운 ReST API 호출**

리드 및 활동 ReST API에 대한 3개의 새로운 호출:

* 리드 삭제
* 프로그램 ID로 리드 가져오기
* 삭제된 리드 가져오기

또한 더 빠른 API 호출을 위해 리드 변경 내용을 비동기적으로 작성하는 새로운 리드 동기화 옵션이 있습니다. 자세한 내용은 [developers.markto.com](http://developers.marketo.com)에서 릴리스 후에 제공됩니다.

**이메일 스크립팅 사용자 정의 개체 지원**

이제 이메일 스크립트 내에서 계정 객체와 연관된 사용자 정의 객체에 액세스할 수 있습니다.

## 실시간 개인화 {#real-time-personalization}

**Google 및 Facebook에 대한 개인화된 리마케팅**

리마케팅은 웹 사이트를 방문한 사람에게 광고를 표시합니다. 이제 실시간 개인화의 데이터를 사용하여 [Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md) 및 [Facebook](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)에 리마케팅 캠페인을 개인화할 수 있습니다. 서로 다른 업계, 이름 있는 계정 목록, 회사 크기 또는 알려진 리드의 모든 데이터를 대상으로 리마케팅합니다.

[지정된 계정 목록 모듈](/help/marketo/product-docs/web-personalization/account-based-web-marketing/create-a-new-account-list.md)

지정된 계정 모듈이 개선되면 사용자에 대한 일치 비율과 유효성 검사가 개선됩니다. 추가 사항:

* 리드의 이메일 주소를 사용하여 지정된 계정 목록에서 조직 일치(RTP 전용 고객도)
* 계정당 최대 100K 레코드 지원
* 보고 다운로드할 CSV 파일 템플릿

![](assets/image2015-1-14-11-3a12-3a16.png)

업데이트된 RTP 태그 옵션

[계정 ](http://docs.marketo.com/display/docs/rtp+tag+implementation) 설정 아래의 RTP 태그 옵션이 다음을 포함하도록 업데이트되었습니다.

1. CDN 및 비동기(권장 태그)
1. CDN 및 동기(고속)
1. CDN이 없는 비동기 태그
1. CDN이 없는 동기 태그

최상의 성능을 위해 `<head>` 뒤에 웹 페이지의 헤더 맨 위에 태그를 배치하는 것이 좋습니다. 모든 태그는 [RTP API](http://developers.marketo.com/documentation/websites/rtp-js-api/)의 사용을 허용합니다. RTP 태그를 배포하는 방법에 대한 자세한 내용은 [여기](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md)를 참조하십시오.

![](assets/image2015-1-15-13-3a30-3a45.png)
