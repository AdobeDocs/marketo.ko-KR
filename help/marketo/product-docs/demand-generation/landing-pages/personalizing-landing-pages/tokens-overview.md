---
unique-page-id: 2950799
description: 토큰 개요 - Marketo 문서 - 제품 설명서
title: 토큰 개요
exl-id: d60816ce-33fb-4e18-8acd-71d4e90f47de
source-git-commit: 4fc3cf6e6458f07df7cced9399831b8c6b50e0ad
workflow-type: tm+mt
source-wordcount: '300'
ht-degree: 0%

---

# 토큰 개요 {#tokens-overview}

토큰은 Marketo 스마트 캠페인 흐름 단계, 이메일, 랜딩 페이지, 코드 조각 및 웹 캠페인에서 사용할 수 있는 변수입니다.

## 기본값 이해 {#understanding-default-values}

토큰을 사용하는 경우 기본값을 제공할 수도 있습니다. 참조하는 필드에 값이 없는 경우를 나타내는 텍스트입니다.

![](assets/image2014-12-2-13-3a16-3a48.png)

이 예제에서 이메일에는 &quot;Greetings, (first name)&quot; 또는 &quot;Greetings, earthling&quot;(기본값)이라고 표시됩니다.

![](assets/two.png)

>[!CAUTION]
>
>Marketo의 이메일 편집기를 사용할 때 토큰이 사전 헤더에서 작동하지 않습니다. 미리 헤더에서 토큰을 사용하려면 이메일 템플릿에서 자신의 HTML을 통해 해야 합니다.

>[!NOTE]
>
>이 목록은 완전하지 않다. 또한 Marketo에 있는 모든 사용자 지정 필드에 대해 토큰이 만들어집니다.

## 개인 토큰 {#person-tokens}

* `{{lead.Acquisition Date}}`
* `{{lead.Acquisition Program Name}}`
* `{{lead.Acquisition Program}}`
* `{{lead.Address}}`
* `{{lead.Anonymous IP}}`
* `{{lead.Black Listed}}`
* `{{lead.City}}`
* `{{lead.Country}}`
* `{{lead.Created At}}`
* `{{lead.Date of Birth}}`
* `{{lead.Department}}`
* `{{lead.Do Not Call}}`
* `{{lead.Do Not Call Reason}}`
* `{{lead.Email Address}}`
* `{{lead.Email Invalid}}`
* `{{lead.Email Invalid Cause}}`
* `{{lead.Fax Number}}`
* `{{lead.First Name}}`
* `{{lead.Full Name}}`
* `{{lead.Id}}`
* `{{lead.Inferred City}}`
* `{{lead.Inferred Company}}`
* `{{lead.Inferred Country}}`
* `{{lead.Inferred Metropolitan Area}}`
* `{{lead.Inferred Phone Area Code}}`
* `{{lead.Inferred Postal Code}}`
* `{{lead.Inferred State Region}}`
* `{{lead.Is Customer}}`
* `{{lead.Is Employee}}`
* `{{lead.Is Partner}}`
* `{{lead.Job Title}}`
* `{{lead.Last Name}}`
* `{{lead.Lead Source}}`
* `{{lead.Marketing Suspended}}`
* `{{lead.Middle Name}}`
* `{{lead.Mobile Phone Number}}`
* `{{lead.Original Referrer}}`
* `{{lead.Original Search Engine}}`
* `{{lead.Original Search Phrase}}`
* `{{lead.Original Source Info}}`
* `{{lead.Original Source Type}}`
* `{{lead.Person Notes}}`
* `{{lead.Phone Number}}`
* `{{lead.Registration Source Info}}`
* `{{lead.Registration Source Type}}`
* `{{lead.Salutation}}`
* `{{lead.SFDC Created Date}}`
* `{{lead.SFDC Is Deleted}}`
* `{{lead.SFDC Type}}`
* `{{lead.Unsubscribed}}`
* `{{lead.Unsubscribed Reason}}`
* `{{lead.Updated At}}`
* 사용자 지정 개인 필드는 표시 이름을 사용하는 경우에도 작동합니다(예: ). `{{lead.Custom Field Name}}`

## 회사 토큰 {#company-tokens}

* `{{Company.Account Owner Email Address}}`
* `{{Company.Address}}`
* `{{Company.Annual Revenue}}`
* `{{Company.City}}`
* `{{Company.Company Name}}`
* `{{Company.Company Notes}}`
* `{{Company.Country}}`
* `{{Company.Industry}}`
* `{{Company.Main Phone}}`
* `{{Company.Num Employees}}`
* `{{Company.Parent Company Name}}`
* `{{Company.Postal Code}}`
* `{{Company.SFDC Account Num}}`
* `{{Company.SFDC Created Date}}`
* `{{Company.SFDC Type}}`
* `{{Company.SIC Code}}`
* `{{Company.Site}}`
* `{{Company.State}}`
* `{{Company.Website}}`
* 사용자 지정 회사 필드는 표시 이름을 ex로 사용하는 경우에도 작동합니다. `{{Company.Custom Field Name}}`

## 캠페인 토큰 {#campaign-tokens}

* `{{campaign.name}}`
* `{{campaign.id}}`
* `{{campaign.description}}`

## 시스템 토큰 {#system-tokens}

>[!NOTE]
>
>에서 이러한 토큰에 대해 자세히 알아보십시오 [시스템 토큰 용어집](/help/marketo/product-docs/email-marketing/general/using-tokens/system-tokens-glossary.md).

* `{{system.date}}`
* `{{system.time}}`
* `{{system.dateTime}}`
* `{{system.forwardToFriendLink}}`
* `{{system.unsubscribeLink}}`
* `{{system.viewAsWebpageLink}}`

## 트리거 토큰 {#trigger-tokens}

* `{{trigger.Trigger Name}}`
* `{{trigger.Name}}`
* `{{trigger.Link}}`
* `{{trigger.Subject}}`
* `{{trigger.Category}}`
* `{{trigger.Details}}`
* `{{trigger.Web Page}}`
* `{{trigger.Client IP Address}}`
* `{{trigger.Sent By}}`
* `{{trigger.Received By}}`
* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!NOTE]
>
>에 대한 자세한 내용 찾기 [흥미로운 순간에 토큰](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/interesting-moments/trigger-tokens-for-interesting-moments.md) 스마트 캠페인에 사용된 트리거를 기반으로 합니다.

## 프로그램 토큰 {#program-tokens}

* `{{program.Name}}`
* `{{program.Description}}`
* `{{program.id}}`

## 내 토큰 {#my-tokens}

내 토큰은 프로그램 내에 정의되며 `{{my.` 뒤에 토큰에 대해 만든 이름이 옵니다. 추가 정보 [프로그램의 내 토큰](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md).

## 멤버 토큰 {#member-token}

멤버 토큰은 통합 서비스 파트너의 고유 값을 삽입하는 데 사용됩니다. 일반적인 구성원 토큰 사용은 웨비나 참석자의 고유한 URL을 위한 것입니다. 각 사용자는 를 사용하여 삽입할 수 있는 웨비나에 액세스할 수 있는 고유한 URL을 보유합니다. `{{member.webinar url}}` 토큰. 다음 `{{member.webinar url}}` 토큰은 서비스 공급자가 생성한 개인의 고유 확인 URL을 자동으로 확인합니다.

* `{{member.webinar url}}`

>[!CAUTION]
>
>다음 `{{member.webinar url}}` 토큰은 이메일을 보내는 스마트 캠페인이 이벤트 프로그램의 하위 자산인 경우에만 채워집니다.
