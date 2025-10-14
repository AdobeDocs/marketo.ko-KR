---
unique-page-id: 4720758
description: 릴리스 노트 - 2015년 1월 - Marketo 설명서 - 제품 설명서
title: 릴리스 노트 - 2015년 1월
exl-id: f312ff87-6ac1-4167-be98-76600bb4b3cd
feature: Release Information
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '354'
ht-degree: 1%

---

# 릴리스 정보: 2015년 1월 {#release-notes-january}

다음 기능은 2015년 1월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오. 릴리스 후에 다시 돌아와 각 기능에 대한 자세한 문서에 대한 링크를 찾으십시오.

## Marketing Automation 업데이트 {#marketing-automation-updates}

**모바일 랜딩 페이지**

이제 랜딩 페이지 편집기 내에서 [랜딩 페이지의 모바일 보기를 빌드](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/add-a-mobile-view-for-your-free-form-landing-page.md)할 수 있습니다. 장치에 관계없이 메시지를 효과적으로 전달하고, 콘텐츠를 맞춤화하여 이동 중에도 쉽게 사용할 수 있도록 하여 참여도를 높이십시오. 이 기능은 릴리스 후 일주일 동안 점진적으로 롤아웃됩니다.

[&#x200B; 랜딩 페이지 워크스루 비디오-](https://youtu.be/aPQHlG2X6c0)

**새 REST API 호출**

리드 및 활동 REST API에 대한 세 가지 새로운 호출:

* 리드 삭제
* 프로그램 ID로 리드 가져오기
* 삭제된 리드 가져오기

또한 더 빠른 API 호출을 위해 리드 변경을 비동기식으로 작성하는 새로운 리드 동기화 옵션이 있습니다. 전체 세부 정보는 [https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/home](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/home)에 릴리스된 후에 사용할 수 있습니다.

**전자 메일 스크립팅 사용자 지정 개체 지원**

이제 이메일 스크립트 내에서 계정 개체와 연관된 사용자 정의 개체에 액세스할 수 있습니다!

## Real-Time Personalization {#real-time-personalization}

Google 및 **에 대해[!DNL Facebook]**&#x200B;개인화된 리마케팅

리마케팅은 웹 사이트를 방문한 사람에게 광고를 표시합니다. 이제 Real-Time Personalization의 데이터를 사용하여 [Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md) 및 [[!DNL Facebook]](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)에서 리마케팅 캠페인을 개인화할 수 있습니다. 다른 업계의 대상, 명명된 계정 목록, 회사 규모 또는 알려진 잠재 고객의 데이터를 리마케팅합니다.

[명명된 계정 목록 모듈](/help/marketo/product-docs/web-personalization/account-based-web-marketing/create-a-new-account-list.md)

Named Accounts 모듈의 개선 사항은 사용자의 일치율과 유효성 검사를 향상시킵니다. 추가 사항은 다음과 같습니다.

* 잠재 고객의 이메일 주소를 사용하여 명명 계정 목록에서 조직을 일치시킵니다(RTP 전용 고객도 해당).
* 계정당 최대 10만 개의 레코드 지원
* 보고 다운로드할 CSV 파일 템플릿

![](assets/image2015-1-14-11-3a12-3a16.png)

**업데이트된 RTP 태그 옵션**

계정 설정 아래의 RTP 태그 옵션이 다음을 포함하도록 업데이트되었습니다.

1. CDN 및 비동기(권장 태그)
1. CDN 및 동기(고속)
1. CDN이 없는 비동기 태그
1. CDN 없이 동기식 태그

최상의 성능을 위해 태그를 웹 페이지의 헤더 맨 위에 `<head>` 뒤에 배치하는 것이 좋습니다. 모든 태그는 [RTP API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/javascriptapi/rich-media-recommendation) 사용을 허용합니다. RTP 태그를 배포하는 방법에 대한 자세한 내용은 [여기](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md)를 참조하십시오.

![](assets/image2015-1-15-13-3a30-3a45.png)
