---
unique-page-id: 4720433
description: Marketing To - Marketing To Docs - 제품 문서 구성
title: Marketing에 대한 프로토콜 구성
translation-type: tm+mt
source-git-commit: 0ec525defbefe610f0bd1227b1c8f8e125d8e362
workflow-type: tm+mt
source-wordcount: '712'
ht-degree: 1%

---


# {#configure-protocols-for-marketo} 마케팅에 대한 프로토콜 구성

마케팅 그룹은 Marketing을 사용하여 브랜드화된 캠페인 랜딩 페이지와 이메일을 만들고 있습니다. 랜딩 페이지와 이메일이 제대로 작동하는지 확인하려면 IT 부서의 도움이 필요합니다. 마케팅 그룹이 이메일을 통해 보내야 하는 정보와 함께 다음 프로토콜을 설정하십시오.

이 아티클은 이러한 프로토콜을 구현하려는 회사의 IT 부서에서 공유해야 합니다.

>[!NOTE]
>
>IT 팀에서를 사용하여 웹 액세스를 제한하는 경우 모든 Marketing To 리소스 및 웹 소켓을 허용하도록 다음 도메인(별표 포함)을 추가하도록 요청하십시오.

* `*.marketo.com`

* `*.marketodesigner.com`

* `*.mktoweb.com`

## 1단계:랜딩 페이지에 대한 DNS 레코드 만들기 및 이메일 {#step-create-dns-records-for-landing-pages-and-email}

**추적 링크 CNAME**

마케팅 팀이 새 CNAME 레코드에 대한 2개의 요청을 보냈어야 합니다. 첫 번째 단계는 랜딩 페이지 URL에 해당하므로, 랜딩 페이지가 Marketing(실제 호스트)이 아니라 도메인을 반영하는 URL에 나타납니다. 두 번째 방법은 Marketing To에서 보내는 이메일에 포함된 추적 링크입니다.

`1` **랜딩 페이지에 대한 CNAME 추가**

DNS 레코드에 `[YourLandingPageCNAME]`이 Marketing 랜딩 페이지에 할당된 고유한 계정 문자열을 가리키도록 랜딩 페이지 CNAME을 추가합니다. 도메인 등록자의 사이트에 로그인하고 랜딩 페이지 CNAME 및 계정 문자열을 입력합니다. 일반적으로 이 작업에는 세 개의 필드가 포함됩니다.

* 별칭:`[YourLandingPageCNAME]` 입력(마케팅에서 제공)
* 유형:CNAME
* 포인트 위치:`[MarketoAccountString].mktoweb.com` 입력(마케팅에서 제공)

`2` **이메일 추적 링크에 대한 CNAME 추가**

`[YourEmailCNAME]`이(가) Marketing에서 할당한 기본 추적 링크인 [MktoTrackingLink]를 가리키도록 이메일 CNAME 마케팅을 추가합니다.\
`[YourEmailCNAME].[YourDomain].com` CNAME 내  `[MktoTrackingLink]`

예:

`pages.abc.com IN CNAME mkto-a0244.com`

`3` **마케팅 팀에 알림**

이 프로세스를 완료하면 마케팅 팀에 알립니다.

## 2단계:마케팅 허용 목록에 추가하다 IP {#step-allowlist-marketo-ips}

마케팅 그룹이 Marketing Cloud를 사용하여 테스트 이메일을 보내는 경우(이메일 폭발을 보내기 전 모범 사례), 발신자 IP 주소를 사용하여 이메일이 유효한지 확인하는 스팸 방지 시스템에 의해 테스트 이메일이 차단되는 경우가 있습니다. 이러한 테스트 이메일이 도착하는지 확인하려면 Marketing to를 사용자의에 허용 목록에 추가하다 추가하십시오.

다음 IP 주소를 회사에 허용 목록에 추가하다 추가합니다.

199.15.212.0/22\
192.28.144.0/20
192.28.160.0/19\
185.28.196.0/22\
130.248.172.0/24\
130.248.173.0/24\
103.237.104.0/22\
94.236.119.0/26

일부 스팸 방지 시스템에서는 할당을 위해 IP 주소 대신 이메일 반환 경로 필드를 사용합니다. 이러한 경우 Marketing에서 여러 사서함 하위 도메인을 사용하므로 가장 허용 목록에 추가하다 좋은 방법은 &#39;*.mktomail.com&#39;을 사용하는 것입니다. 보낸 사람 주소를 허용 목록에 추가하다 기반으로 하는 기타 스팸 방지 시스템 이러한 경우 마케팅 그룹이 사람/리드와 통신하는 데 사용하는 모든 전송(&#39;보낸 사람&#39;) 도메인을 포함해야 합니다.

>[!NOTE]
>
>Postini는 고유한 기술을 사용하며 허용 목록에 추가 IP 범위가 필요합니다. [Postini](https://nation.marketo.com/docs/DOC-1066)의 허용 목록에 추가를 참조하십시오.

## 3단계:SPF 및 DKIM {#step-set-up-spf-and-dkim} 설정

마케팅 팀은 DNS 리소스 레코드(아래 참조)에 추가할 DKIM 정보도 전송했어야 합니다. 단계에 따라 DKIM 및 SPF를 구성한 다음 이 내용이 업데이트되었음을 마케팅 팀에 알립니다.

1. SPF를 설정하려면 DNS 항목에 다음 줄을 추가하십시오.

   `[CompanyDomain]` TXT v=spf1 mx ip4:`[CorpIP]`\
   포함:mktomail.com ~all

   DNS 항목에 이미 기존 SPF 레코드가 있는 경우 SPF 레코드에 다음을 추가하면 됩니다.\
   포함:mktomail.com

   CompanyDomain을 웹 사이트의 주 도메인으로 바꿉니다(예:&quot;`(company.com/)`&quot;) 및 회사 이메일 서버의 IP 주소를 사용하는 CorpIP(예: &quot;255.255.255.255&quot;). Marketing To를 통해 여러 도메인에서 이메일을 보내는 경우 IT 직원이 각 도메인에 대해 이 라인을 추가하도록 해야 합니다(한 줄에).

1. DKIM의 경우 설정하려는 각 도메인에 대한 DNS 리소스 레코드를 만듭니다. 다음은 서명할 각 도메인에 대한 호스트 레코드 및 TXT 값입니다.

   `[DKIMDomain1]`:호스트 레코드 `[HostRecord1]` 는 이고 TXT 값은  `[TXTValue1]`입니다.

   `[DKIMDomain2]`:호스트 레코드 `[HostRecord2]` 는 이고 TXT 값은  `[TXTValue2]`입니다.

   [여기에 있는 ](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md)지침을 따라 설치한 각 DKIDomain에 대한 HostRecord 및 TXTValue를 복사합니다. IT 직원이 이 단계를 완료한 후 관리 > 이메일 > DKIM에서 각 도메인을 확인하는 것을 잊지 마십시오.

## 4단계:도메인 {#step-set-up-mx-records-for-your-domain}에 대한 MX 레코드 설정

MX 레코드를 사용하면 회신 및 자동 응답자를 처리하기 위해 이메일을 보내는 도메인에 메일을 수신할 수 있습니다. 회사 도메인에서 보내는 경우 이미 이 설정이 구성되어 있을 수 있습니다. 그렇지 않은 경우 회사 도메인의 MX 레코드에 매핑하도록 일반적으로 설정할 수 있습니다.
