---
unique-page-id: 4720433
description: Marketo에 대한 프로토콜 구성 - Marketo 문서 - 제품 설명서
title: Marketo에 대한 프로토콜 구성
exl-id: cf2fd4ac-9229-4e52-bb68-5732b44920ef
feature: Getting Started
source-git-commit: 0d6507c251e2b7567483af8d75158f6bc6a1ca49
workflow-type: tm+mt
source-wordcount: '1028'
ht-degree: 3%

---

# Marketo에 대한 프로토콜 구성 {#configure-protocols-for-marketo}

허용 목록에 추가하다 제한적 방화벽 또는 프록시 서버 설정을 사용하는 경우, 사용자 또는 네트워크 관리자가 Adobe Marketo Engage이 예상대로 작동하도록 특정 도메인 및 IP 주소 범위를 설정해야 할 수 있습니다.

## 브랜드 캠페인 랜딩 페이지 및 이메일 {#branded-campaign-landing-pages-and-emails}

마케팅 그룹은 Marketo을 사용하여 브랜드 캠페인 랜딩 페이지 및 이메일을 만듭니다. 이러한 랜딩 페이지와 이메일이 작동하도록 하려면 IT의 도움이 약간 필요합니다. 마케팅 그룹에서 전자 메일로 보냈어야 하는 정보를 사용하여 다음 프로토콜을 설정하십시오.

이 문서는 이러한 프로토콜을 구현하려는 회사의 IT 부서와 공유해야 합니다.

IT 팀이 허용 목록에 추가하다를 사용하여 웹 액세스를 제한하는 경우 모든 Marketo 리소스 및 웹 소켓을 허용하도록 다음 도메인(별표 포함)을 추가하도록 요청하십시오.

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`
* `*.experience.adobe.com`
* `*.adobe.net`

## 1단계: 랜딩 페이지 및 이메일에 대한 DNS 레코드 만들기 {#step-create-dns-records-for-landing-pages-and-email}

**링크 CNAME 추적**

마케팅 팀에서 새 CNAME 레코드에 대한 요청을 두 개 보냈어야 합니다. 첫 번째는 랜딩 페이지 URL에 대한 것이므로 랜딩 페이지는 Marketo(실제 호스트)가 아닌 도메인을 반영하는 URL에 표시됩니다. 두 번째는 Marketo에서 보내는 이메일에 포함된 추적 링크에 대한 것입니다.

`1` **랜딩 페이지용 CNAME 추가**

DNS 레코드로 보낸 랜딩 페이지 CNAME을 추가합니다. `[YourLandingPageCNAME]` 는 Marketo 랜딩 페이지에 할당된 고유한 계정 문자열을 가리킵니다. 도메인 등록자의 사이트에 로그인하고 랜딩 페이지 CNAME 및 계정 문자열을 입력합니다. 일반적으로 다음과 같은 세 가지 필드가 포함됩니다.

* 별칭: Enter `[YourLandingPageCNAME]` (마케팅에서 제공)
* 유형: CNAME
* 지정: 입력 `[MunchkinID].mktoweb.com` (마케팅에서 제공)

`2` **이메일 추적 링크에 대한 CNAME 추가**

CNAME 마케팅이 귀하에게 보낸 이메일을 추가하여 `[YourEmailCNAME]` 포인트 대상 [MktoTrackingLink]: Marketo이 할당한 기본 추적 링크로서, 다음과 같은 형식입니다.\
`[YourEmailCNAME].[YourDomain].com` CNAME `[MktoTrackingLink]`

For example:

`pages.abc.com IN CNAME mkto-a0244.com`

>[!NOTE]
>
>`[MktoTrackingLink]` 은(는) 기본 브랜딩 도메인이어야 합니다.

`3` **마케팅 팀에 알림**

이 프로세스를 완료하면 마케팅 팀에 알립니다.

`4` **연락처 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} 을 클릭하여 SSL 인증서 프로비저닝 프로세스를 시작합니다.**

이 프로세스를 완료하는 데 영업일 기준으로 최대 3일이 소요될 수 있습니다.

## 2단계: Marketo IP 허용 목록 {#step-allowlist-marketo-ips}

마케팅 그룹이 Marketo을 사용하여 테스트 이메일을 전송하는 경우(이메일 알림을 전송하기 전에 모범 사례), 이메일이 유효한지 확인하기 위해 발신자 IP 주소에 의존하는 스팸 방지 시스템에 의해 테스트 이메일이 차단되는 경우가 있습니다. 이러한 테스트 이메일이 도착하는지 확인하려면 Marketo에 허용 목록에 추가하다를 추가하십시오.

다음 IP 주소를 기업 허용 목록에 추가합니다.

94.236.119.0/26

103.237.104.0/22

130.248.172.0/24

130.248.173.0/24

130.248.244.88/29

185.28.196.0/22

192.28.144.0/20

192.28.160.0/19

199.15.212.0/22

일부 스팸 방지 시스템은 할당에 IP 주소 대신 이메일 반환 경로 필드를 사용합니다. 이러한 경우, 가장 좋은 접근 방법은 &#39;허용 목록 &#39; 입니다.&#42;Marketo에서 여러 사서함 하위 도메인을 사용하므로 .mktomail.com&#39; From 주소를 기반으로 하는 기타 스팸 방지 시스템 허용 목록에 추가하다. 이러한 경우 마케팅 그룹이 사람/리드와 통신하는 데 사용하는 모든 전송(&#39;보낸 사람&#39;) 도메인을 포함해야 합니다.

>[!NOTE]
>
>Postini는 고유한 기술을 사용하며 허용 목록에 추가 IP 범위가 필요합니다. 다음을 참조하십시오 [Postini와의 허용 목록에 추가](https://nation.marketo.com/docs/DOC-1066).

## 3단계: SPF 및 DKIM 설정 {#step-set-up-spf-and-dkim}

마케팅 팀이 DNS 리소스 레코드(또한 아래 목록)에 추가할 DKIM 정보도 보냈어야 합니다. DKIM 및 SPF를 성공적으로 구성하는 단계를 수행한 다음 마케팅 팀에 이것이 업데이트되었음을 알립니다.

1. SPF를 설정하려면 DNS 항목에 다음 줄을 추가하십시오.

   `[CompanyDomain]` TXT v=spf1 mx ip4:`[CorpIP]`\
   include: mktomail.com ~all

   DNS 항목에 기존 SPF 레코드가 이미 있는 경우 다음을 추가하기만 하면 됩니다.\
   포함: mktomail.com

   CompanyDomain을 웹 사이트의 주 도메인으로 바꾸기(예: &quot;`(company.com/)`&quot;) 및 회사 이메일 서버의 IP 주소가 있는 CorpIP(예: &quot;255.255.255.255&quot;). Marketo을 통해 여러 도메인에서 이메일을 전송하려면 IT 직원에게 각 도메인에 대해 한 줄에 이 줄을 추가하도록 해야 합니다.

1. DKIM의 경우 설정하려는 각 도메인에 대해 DNS 리소스 레코드를 만듭니다. 다음은 서명할 각 도메인의 호스트 레코드 및 TXT 값입니다.

   `[DKIMDomain1]`: 호스트 레코드: `[HostRecord1]` 그리고 TXT 값은 `[TXTValue1]`.

   `[DKIMDomain2]`: 호스트 레코드: `[HostRecord2]` 그리고 TXT 값은 `[TXTValue2]`.

   다음 단계를 수행하여 설정한 각 DKIMDomain의 HostRecord 및 TXTValue를 복사합니다. [여기에 있는 지침](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}. IT 직원이 이 단계를 완료한 후 관리 > 이메일 > DKIM에서 각 도메인을 확인하는 것을 잊지 마십시오.

## 4단계: 도메인에 대한 MX 레코드 설정 {#step-set-up-mx-records-for-your-domain}

MX 레코드를 사용하면 회신 및 자동 응답자를 처리하기 위해 전자 메일을 보내는 도메인으로 메일을 받을 수 있습니다. 회사 도메인에서 보내는 경우 이미 이 구성이 되어 있을 수 있습니다. 그렇지 않은 경우 일반적으로 회사 도메인의 MX 레코드에 매핑하도록 설정할 수 있습니다.

## 아웃바운드 IP 주소 {#outbound-ip-addresses}

아웃바운드 연결은 귀하를 대신하여 인터넷의 서버에 대한 Marketo Engage에 의해 수행됩니다. 함께 일하는 일부 파트너/공급업체 또는 자체 IT 조직은 허용 목록을 사용하여 서버에 대한 액세스를 제한할 수 있습니다. 그렇다면 Marketo Engage 아웃바운드 IP 주소 블록을 제공해야 해당 허용 목록에 추가할 수 있습니다.

**웹훅**

Marketo Engage [웹훅](/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md){target="_blank"} are an outbound integration mechanism. When a [Call Webhook](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/call-webhook.md){target="_blank"} 흐름 작업은 스마트 캠페인의 일부로 실행되고 외부 웹 서비스에 HTTP 요청이 수행됩니다. 웹 서비스 게시자가 외부 웹 서비스가 있는 네트워크의 방화벽에서 허용 목록에 추가하다를 사용하는 경우, 게시자는 아래 나열된 IP 주소 블록을 해당 허용 목록에 추가하다에 추가해야 합니다.

**CRM 동기화**

Marketo Engage [Salesforce CRM 동기화](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/add-an-existing-salesforce-field-to-the-marketo-sync.md){target="_blank"} and [Microsoft Dynamics Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md){target="_blank"} 는 CRM 공급업체에서 게시한 API에 대한 아웃바운드 HTTP 요청을 수행하는 통합 메커니즘입니다. IT 조직이 아래 IP 주소 블록이 CRM 공급업체 API에 액세스하는 것을 차단하지 않도록 해야 합니다.

**Marketo Engage 아웃바운드 IP 주소 블록**

다음 표는 아웃바운드 호출을 수행하는 모든 Marketo Engage 서버를 다룹니다. Marketo Engage에서 나가는 연결을 받도록 IP 허용 목록, 서버, 방화벽, 액세스 제어 목록, 보안 그룹 또는 서드파티 서비스를 구성하는 경우 아래 목록을 사용하십시오.

<table>
 <tbody>
  <tr>
   <th>IP 블록(CIDR 표기법)</th>
  </tr>
  <tr>
   <td>94.236.119.0/26</td>
  </tr>
  <tr>
   <td>103.237.104.0/22</td>
  </tr>
   <tr>
   <td>130.248.172.0/24</td>
  </tr>
   <tr>
   <td>130.248.173.0/24</td>
  </tr>
  <tr>
   <td>130.248.244.88/29</td>
  </tr>
  <tr>
   <td>185.28.196.0/22</td>
  </tr>
  <tr>
   <td>192.28.144.0/20</td>
  </tr>
  <tr>
   <td>192.28.160.0/19</td>
  </tr>
  <tr>
   <td>199.15.212.0/22</td>
  </tr>
 </tbody>
</table>

<table>
 <tbody>
  <tr>
   <th>개별 IP 주소</th>
  </tr>
  <tr>
   <td>13.237.155.207</td>
  </tr>
   <tr>
   <td>13.55.192.247</td>
  </tr>
  <tr>
   <td>18.200.201.81</td>
  </tr>
  <tr>
   <td>34.247.24.245</td>
  </tr>
  <tr>
   <td>35.165.244.220</td>
  </tr>
  <tr>
   <td>44.235.171.179</td>
  </tr>
  <tr>
   <td>52.20.211.99</td>
  </tr>
  <tr>
   <td>52.64.109.86</td>
  </tr>
  <tr>
   <td>54.160.246.246</td>
  </tr>
  <tr>
   <td>54.212.167.17</td>
  </tr>
  <tr>
   <td>54.220.138.65</td>
  </tr>
   <tr>
   <td>54.237.141.197</td>
  </tr>
  </tr>
   <tr>
   <td>130.248.168.16</td>
  </tr>
  </tr>
   <tr>
   <td>130.248.168.17</td>
  </tr>

</tbody>
</table>

