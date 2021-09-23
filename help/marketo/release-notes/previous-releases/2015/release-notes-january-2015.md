---
unique-page-id: 4720758
description: 릴리스 노트 - 2015년 1월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2015년 1월
exl-id: f312ff87-6ac1-4167-be98-76600bb4b3cd
source-git-commit: 74effe9f8078f8d71e6de01d6e737ddc86978abb
workflow-type: tm+mt
source-wordcount: '361'
ht-degree: 0%

---

# 릴리스 노트: 2015년 1월 {#release-notes-january}

다음 기능은 2015년 1월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo Edition을 확인하십시오. 릴리스 후 다시 돌아와 각 기능에 대한 세부 문서에 대한 링크를 확인하십시오!

## 마케팅 자동화 업데이트 {#marketing-automation-updates}

**모바일 친화적 랜딩 페이지**

이제 랜딩 페이지 편집기 내에서 [랜딩 페이지용 모바일 보기를 작성할 수 있습니다](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/add-a-mobile-view-for-your-free-form-landing-page.md). 장치에 상관없이 효율적으로 메시지를 전달하고 이동 중에 쉽게 사용할 수 있도록 콘텐츠를 맞춤화하여 참여를 높일 수 있습니다. 이 기능은 릴리스 후 한 주 동안 점진적으로 롤아웃됩니다.

[-랜딩 페이지 연습 비디오-](https://youtu.be/aPQHlG2X6c0)

**새 Rest API 호출**

Lead 및 Activity ReST API에 대한 세 가지 새로운 호출:

* 리드 삭제
* 프로그램 ID별 리드 가져오기
* 삭제된 리드 가져오기

또한 더 빠른 API 호출을 위해 리드 변경을 비동기식으로 작성하는 Sync Lead에 대한 새로운 옵션이 있습니다. 전체 세부 사항은 [developers.marketo.com](https://developers.marketo.com)에서 릴리스 후에 사용할 수 있습니다.

**이메일 스크립팅 사용자 지정 개체 지원**

이제 이메일 스크립트 내에서 계정 개체와 연결된 사용자 지정 개체에 액세스합니다.

## 실시간 개인화 {#real-time-personalization}

**Google 및 Facebook을 위한 개인화된 리마케팅**

리마케팅은 웹 사이트를 방문한 사람에게 광고를 보여줍니다. 이제 실시간 개인화의 데이터를 사용하여 [Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md) 및 [Facebook](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)에서 리마케팅 캠페인을 개인화할 수 있습니다. 다양한 업계, 명명 계정 목록, 회사 규모 또는 알려진 리드의 모든 데이터를 대상으로 리마케팅합니다.

[명명된 계정 목록 모듈](/help/marketo/product-docs/web-personalization/account-based-web-marketing/create-a-new-account-list.md)

명명된 계정 모듈에 대한 개선 사항으로 사용자의 일치율 및 유효성 검사가 개선됩니다. 추가 사항은 다음과 같습니다.

* 리드의 이메일 주소를 사용하여 명명 계정 목록에서 조직 일치(RTP 전용 고객도)
* 계정당 최대 10만 개의 레코드 지원
* 보고 다운로드할 CSV 파일 템플릿

![](assets/image2015-1-14-11-3a12-3a16.png)

**업데이트된 RTP 태그 옵션**

계정 설정 아래의 RTP 태그 옵션이 다음을 포함하도록 업데이트되었습니다.

1. CDN 및 비동기(권장 태그)
1. CDN 및 동기식(고속)
1. CDN이 없는 비동기 태그
1. CDN이 없는 동기 태그

최상의 성능을 위해 `<head>` 뒤의 웹 페이지의 헤더 맨 위에 태그를 배치하는 것이 좋습니다. 모든 태그는 [RTP API](https://developers.marketo.com/documentation/websites/rtp-js-api/)를 사용할 수 있습니다. RTP 태그를 배포하는 방법에 대한 자세한 내용은 여기 [여기](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md)를 참조하십시오.

![](assets/image2015-1-15-13-3a30-3a45.png)
