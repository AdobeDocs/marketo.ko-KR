---
unique-page-id: 12977439
description: 릴리스 노트 - 2017년 봄 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2017년 봄
exl-id: 61873d1f-41dd-4f5c-94d0-65f0bcacff75
source-git-commit: 74effe9f8078f8d71e6de01d6e737ddc86978abb
workflow-type: tm+mt
source-wordcount: '671'
ht-degree: 0%

---

# 릴리스 노트: 17년 봄 {#release-notes-spring}

다음 기능은 17년 봄 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo 버전을 확인하십시오.

각 기능에 대한 자세한 문서를 보려면 제목 링크를 클릭하십시오. **참고**: 항목에 여러 하위 제목이 있으면 링크가 해당 항목에 배치됩니다.

## [linkedIn Lead Gen Forms](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md) {#linkedin-lead-gen-forms}

[linkedIn Lead Gen Forms](https://business.linkedin.com/marketing-solutions/native-advertising/lead-gen-ads) 는 기업이 LinkedIn에서 리드 생성 캠페인을 실행하는 보다 직접적인 방법입니다. 사람들은 제품이나 서비스에 대한 관심을 표현하기 위해 양식을 작성할 수 있으므로, 비즈니스에서 개인의 세부 정보를 캡처하고 Marketo에 동기화하여 자동 후속 프로세스 및 리드 라우팅 활동이 발생할 수 있습니다.

LinkedIn Lead Gen Forms과 Marketo 통합하면 Lead Gen 양식 내에 제공하는 정보가 자동으로 캡처됩니다. 그런 다음 새로운 **LinkedIn 리드 세대 양식 채우기** 트리거 및 필터링.

![](assets/release-notes-image.png)

## [MSI 템플릿 만료](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/actions-in-the-msi-panel/send-marketo-email/publish-an-email-to-sales-insight.md) {#expire-msi-template}

Sales Insight에서 오래된 템플릿을 정리하던 시대는 지났습니다. 전자 메일을 게시할 때 만료 날짜를 설정하면 만료 날짜가 롤업될 때 게시 취소가 처리합니다.

>[!NOTE]
>
>5/31/17에 대한 만료 날짜를 설정하면 템플릿이 Sales Insight에서 5/31/17이 끝날 때 제거됩니다.

![](assets/four-281-29.png)

## [사람 및 활동용 벌크 추출 API](https://developers.marketo.com/rest-api/bulk-extract/) {#bulk-extract-apis-for-people-and-activities}

Marketo에서 외부 시스템으로 많은 개인 및 활동 데이터를 쉽게 전송할 수 있습니다.

## ABM 개선 사항 {#abm-enhancements}

**[ABM 명명 계정의 사용자 지정 필드](https://docs.marketo.com/x/1wnG)**

이제 Marketo ABM을 통해 지정된 계정에 최대 10개의 사용자 지정 필드를 만들 수 있습니다. 이러한 사용자 지정 필드를 CRM 계정 개체의 필드에 매핑할 수 있습니다. Marketo ABM이 데이터를 동기화하여 ABM 명명 계정을 확장하고 마케팅을 도울 수 있습니다.

**[ABM 명명된 계정의 백분위수 점수](https://docs.marketo.com/display/docs/assets/abmpercentiles.png)**

명명된 계정 점수는 매우 다를 수 있습니다. Marketo ABM은 이제 각 점수에 대한 백분위수를 자동으로 계산하므로 각 명명된 계정이 다른 명명 계정 사이에 있는 위치를 한 눈에 볼 수 있습니다.

**[ABM 계정 목록 API](https://developers.marketo.com/rest-api/lead-database/named-account-lists/)**

지정된 계정 목록에 대한 향상된 API 지원과 풍부하고 강력한 ABM 파트너 통합을 활용할 수 있습니다.

## 웹 개인화 개선 사항 {#web-personalization-enhancements}

![](assets/dialogoptions.png)

**[스크롤 시 웹 캠페인](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/set-how-your-web-campaign-displays.md)**

새로운 웹 캠페인 효과는 웹 방문자에게 보다 개인화된 경험을 제공합니다. 웹 방문자가 웹 페이지에서 아래로 스크롤할 때만 표시하도록 개인화된 웹 캠페인을 설정합니다. 다음을 기준으로 스크롤할 때 표시할 대화 상자 웹 캠페인을 설정할 수 있습니다.

* 스크롤한 페이지의 백분율
* 픽셀에 도달
* 페이지의 접힌 부분 아래로 스크롤하기

**[Exit Intent에 따른 웹 캠페인](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/set-how-your-web-campaign-displays.md)**

방문자가 페이지를 닫기 전에 방문자의 주의를 끌십시오. 마우스 제스처가 방문자가 페이지를 떠나고 있음을 나타내는 경우에만 표시하도록 개인화된 웹 캠페인을 설정합니다.

**[웹 캠페인에 대한 애니메이션 효과](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md)**

웹 페이지로 들어오거나 나갈 때 캠페인이 표시되는 방식을 사용자 지정하려면 대화 상자 웹 캠페인에 대한 애니메이션 효과를 설정합니다. 6가지 다른 효과 중에서 선택하고 대화 상자의 타이밍과 방향을 제어할 수 있습니다.

![](assets/animationoptins.png)

**[대화 상자 닫기 단추 사용자 지정](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md)**

대화 상자에 대한 닫기 단추 사용자 정의 투명 대화 상자 스타일 웹 캠페인에 사용되는 다양한 옵션 중에서 선택합니다. 닫기 단추의 아이콘, 색상 및 위치를 선택합니다. 자신만의 단추 이미지를 추가할 수도 있습니다.

![](assets/dialog-button-fill-5b1-5d.png)

**[웹 캠페인 아카이브](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/archive-a-web-campaign.md)**

아카이브는 웹 캠페인을 보관하고 기본 웹 캠페인 보기에서 숨길 수 있는 새로운 웹 캠페인 상태입니다. 따라서 가장 연관성이 높고 활성 상태인 캠페인에 집중할 수 있으며, 필요 시 오래된 보관된 캠페인을 검색할 수 있습니다.

![](assets/archive-campaign-5b2-5d.png)

**[로컬라이제이션](/help/marketo/product-docs/administration/settings/select-your-language-locale-and-time-zone.md)**

이제 웹 개인화는 Marketo에서 지원하는 모든 언어(영어, 일본어, 독일어, 스페인어, 프랑스어 및 포르투갈어)로 제공됩니다.

## 예측 개선 사항 {#predictive-enhancements}

**[로컬라이제이션](/help/marketo/product-docs/administration/settings/select-your-language-locale-and-time-zone.md)**

예측 컨텐츠는 이제 Marketo에서 지원하는 모든 언어(영어, 일본어, 독일어, 스페인어, 프랑스어 및 포르투갈어)로 제공됩니다.

## [기존 리치 텍스트 편집기 및 양식 편집기 1.0 사용 중단](https://nation.marketo.com/docs/DOC-4315) {#legacy-rich-text-editor-and-form-editor-deprecation}

2017년 8월 1일부터 여전히 기존 리치 텍스트 편집기와 양식 편집기 1.0을 사용하는 고객은 새 경험으로 자동 전환됩니다.
