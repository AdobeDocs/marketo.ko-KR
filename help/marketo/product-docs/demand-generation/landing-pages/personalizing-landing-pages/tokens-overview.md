---
unique-page-id: 2950799
description: 토큰 개요 - Marketo 문서 - 제품 설명서
title: 토큰 개요
exl-id: d60816ce-33fb-4e18-8acd-71d4e90f47de
feature: Landing Pages
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '296'
ht-degree: 0%

---

# 토큰 개요 {#tokens-overview}

토큰은 Marketo 스마트 캠페인 흐름 단계, 이메일, 랜딩 페이지, 코드 조각 및 웹 캠페인에서 사용할 수 있는 변수입니다.

## 기본값 이해 {#understanding-default-values}

토큰을 사용할 때 기본값도 제공해야 합니다. 참조하고 있는 필드에 대한 값이 사람에게 없는지 보여 주는 텍스트입니다.

![](assets/image2014-12-2-13-3a16-3a48.png)

이 예에서 이메일에는 &quot;Greetings, (이름)&quot; 또는 &quot;Greetings, earthling&quot;(기본값)이 표시됩니다.

![](assets/two.png)

>[!CAUTION]
>
>Marketo의 이메일 편집기를 사용할 때 토큰이 사전 헤더에서 작동하지 않습니다. 프리 헤더에서 토큰을 사용하려면 이메일 템플릿에서 자체 HTML을 통해야 합니다.

>[!NOTE]
>
>이 목록은 완전하지 않습니다. 또한 Marketo에 있는 모든 사용자 지정 필드에 대해 토큰이 만들어집니다.

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
* 사용자 정의 사용자 필드는 표시 이름을 사용하는 경우에도 작동합니다(예: `{{lead.Custom Field Name}}`).

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
* 사용자 정의 회사 필드는 해당 표시 이름 ex를 사용하는 경우에도 작동합니다. `{{Company.Custom Field Name}}`

## 캠페인 토큰 {#campaign-tokens}

* `{{campaign.name}}`
* `{{campaign.id}}`
* `{{campaign.description}}`

## 시스템 토큰 {#system-tokens}

>[!NOTE]
>
>[시스템 토큰 용어집](/help/marketo/product-docs/email-marketing/general/using-tokens/system-tokens-glossary.md)에서 이러한 토큰에 대해 자세히 알아보세요.

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
>스마트 캠페인에 사용된 트리거를 기반으로 [즐거운 순간을 위한 토큰](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/interesting-moments/trigger-tokens-for-interesting-moments.md)에 대해 자세히 알아보세요.

## 프로그램 토큰 {#program-tokens}

* `{{program.Name}}`
* `{{program.Description}}`
* `{{program.id}}`

## [!UICONTROL My Tokens] {#my-tokens}

[!UICONTROL My Tokens]은(는) 프로그램 내에 정의되어 있으며 `{{my.`(으)로 시작하고 토큰에 대해 만든 이름이 옵니다. [프로그램의 내 토큰](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.md)에 대해 자세히 알아보세요.

## 구성원 토큰 {#member-token}

멤버 토큰은 통합 서비스 파트너의 고유 값을 삽입하는 데 사용됩니다. 멤버 토큰의 일반적인 용도는 웨비나 참석자의 고유 URL에 사용됩니다. 각 사용자에게는 `{{member.webinar url}}` 토큰을 사용하여 삽입할 수 있는 웨비나에 액세스할 수 있는 고유한 URL이 있습니다. `{{member.webinar url}}` 토큰은 서비스 공급자가 생성한 개인의 고유 확인 URL을 자동으로 확인합니다.

* `{{member.webinar url}}`

>[!CAUTION]
>
>`{{member.webinar url}}` 토큰은 이메일을 보내는 스마트 캠페인이 이벤트 프로그램의 하위 자산인 경우에만 채워집니다.
