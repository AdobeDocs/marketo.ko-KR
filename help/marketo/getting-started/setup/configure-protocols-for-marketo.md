---
unique-page-id: 4720433
description: Marketo에 대한 프로토콜 구성 - Marketo 문서 - 제품 설명서
title: Marketo에 대한 프로토콜 구성
exl-id: cf2fd4ac-9229-4e52-bb68-5732b44920ef
source-git-commit: 3d29cb4cf4af7d83a82d47cfd6b0c44d659ee82b
workflow-type: tm+mt
source-wordcount: '1046'
ht-degree: 2%

---

# Marketo에 대한 프로토콜 구성 {#configure-protocols-for-marketo}

사용자나 조직에서 제한적인 방화벽 또는 프록시 서버 설정을 사용하는 경우, 사용자나 네트워크 관리자가 특정 도메인과 IP 주소 범위를 허용 목록에 추가하다 탐색하여 Adobe Marketo Engage이 예상대로 작동하는지 확인해야 할 수 있습니다.

## 브랜드 캠페인 랜딩 페이지 및 이메일 {#branded-campaign-landing-pages-and-emails}

마케팅 그룹은 Marketo을 사용하여 브랜드 캠페인 랜딩 페이지 및 이메일을 만들고 있습니다. 그러한 랜딩 페이지와 이메일이 작동하도록 하려면 IT 부서의 도움이 필요합니다. 마케팅 그룹이 이메일로 전송해야 하는 정보와 함께 다음 프로토콜을 설정하십시오.

이 문서는 이러한 프로토콜을 구현하려는 회사의 IT 부서와 공유해야 합니다.

>[!NOTE]
>
>IT 팀이를 사용하여 웹 액세스를 제한하는 허용 목록에 추가하다 경우 모든 Marketo 리소스 및 웹 소켓을 허용하려면 다음 도메인(별표 포함)을 추가하도록 요청하십시오.

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`

## 1단계: 랜딩 페이지 및 전자 메일에 대한 DNS 레코드 만들기 {#step-create-dns-records-for-landing-pages-and-email}

**링크 CNAME 추적**

마케팅 팀이 새 CNAME 레코드에 대한 두 개의 요청을 보냈어야 합니다. 첫 번째 단계는 랜딩 페이지 URL에 대한 것으로서, 랜딩 페이지가 Marketo(실제 호스트)가 아니라 도메인을 반영하는 URL에 표시되도록 합니다. 두 번째는 Marketo에서 보내는 이메일에 포함된 추적 링크에 대한 것입니다.

`1` **랜딩 페이지용 CNAME 추가**

DNS 레코드로 보내는 랜딩 페이지 CNAME을 추가하여 `[YourLandingPageCNAME]` Marketo 랜딩 페이지에 지정된 고유한 계정 문자열을 가리킵니다. 도메인 등록자의 사이트에 로그인하고 랜딩 페이지 CNAME 및 계정 문자열을 입력합니다. 일반적으로 여기에는 세 가지 필드가 포함됩니다.

* 별칭: Enter 키 `[YourLandingPageCNAME]` (마케팅에서 제공)
* 유형: CNAME
* 가리키기: Enter 키 `[MarketoAccountString].mktoweb.com` (마케팅에서 제공)

`2` **이메일 추적 링크에 대한 CNAME 추가**

이메일 CNAME 마케팅을 보내어 `[YourEmailCNAME]` 점 [MktoTrackingLink], Marketo이 할당한 기본 추적 링크(형식:\
`[YourEmailCNAME].[YourDomain].com` CNAME에서 `[MktoTrackingLink]`

예:

`pages.abc.com IN CNAME mkto-a0244.com`

>[!NOTE]
>
>`[MktoTrackingLink]` 기본 브랜딩 도메인이어야 합니다.

`3` **마케팅 팀에 알림**

이 프로세스를 완료하면 마케팅 팀에 알립니다.

`4` **연락처 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target=&quot;_blank&quot;} 를 사용하여 SSL 인증서를 프로비전하는 프로세스를 시작합니다.**

이 프로세스를 완료하는 데 최대 3일이 걸릴 수 있습니다.

## 2단계: Marketo 허용 목록에 추가하다 IP {#step-allowlist-marketo-ips}

마케팅 그룹이 Marketo을 사용하여 테스트 이메일(이메일 발매 보내기 전 우수 사례)을 전송하는 경우, 테스트 이메일이 유효한지 확인하기 위해 발신자 IP 주소를 사용하는 스팸 방지 시스템에 의해 차단되는 경우가 있습니다. 해당 테스트 이메일이 도착하는지 확인하려면 Marketo을에 허용 목록에 추가하다 추가하십시오.

다음 IP 주소를 회사허용 목록에 추가하다에 추가합니다.

199.15.212.0/22\
192.28.144.0/20 192.28.160.0/19\
185.28.196.0/22\
130.248.172.0/24\
130.248.173.0/24\
103.237.104.0/22\
94.236.119.0/26

일부 스팸 방지 시스템에서는 허용되는 IP 주소 대신 이메일 반환 경로 필드를 사용합니다. 그런 경우 가장 좋은 접근 방법은 허용 목록에 추가하다 &#39; 입니다.&#42;Marketo은 여러 사서함 하위 도메인을 사용하므로 .mktomail.com&#39;. 보낸 사람 주소를 허용 목록에 추가하다 기반으로 하는 다른 스팸 방지 시스템. 이러한 경우 마케팅 그룹이 사람/리드와 통신하는 데 사용하는 모든 전송(&#39;보낸 사람&#39;) 도메인을 포함해야 합니다.

>[!NOTE]
>
>Postini는 고유한 기술을 사용하며 허용 목록에 추가 IP 범위가 필요합니다. 자세한 내용은 [Postini를 사용한 허용 목록에 추가](https://nation.marketo.com/docs/DOC-1066).

## 3단계: SPF 및 DKIM 설정 {#step-set-up-spf-and-dkim}

마케팅 팀이 DNS 리소스 레코드(아래 참조)에 추가할 DKIM 정보도 보냈어야 합니다. 단계에 따라 DKIM 및 SPF를 성공적으로 구성한 다음, 이 기능이 업데이트되었음을 마케팅 팀에 알립니다.

1. SPF를 설정하려면 DNS 항목에 다음 줄을 추가합니다.

   `[CompanyDomain]` TXT v=spf1 mx ip4:`[CorpIP]`\
   포함: mktomail.com ~all

   DNS 항목에 이미 기존 SPF 레코드가 있는 경우 다음을 추가하기만 하면 됩니다.\
   포함: mktomail.com

   CompanyDomain 을 웹 사이트의 주 도메인으로 바꿉니다(예: &quot;`(company.com/)`&quot;) 및 회사 이메일 서버의 IP 주소를 사용하는 CorpIP( 예: &quot;255.255.255.255&quot;). 여러 도메인에서 Marketo을 통해 이메일을 보내려면 IT 직원이 각 도메인에 대해 이 줄을 추가(한 줄에서)해야 합니다.

1. DKIM의 경우 설정하려는 각 도메인에 대해 DNS 리소스 레코드를 만듭니다. 다음은 Adobe가 서명할 각 도메인에 대한 호스트 레코드 및 TXT 값입니다.

   `[DKIMDomain1]`: 호스트 레코드: `[HostRecord1]` 및 TXT 값 `[TXTValue1]`.

   `[DKIMDomain2]`: 호스트 레코드: `[HostRecord2]` 및 TXT 값 `[TXTValue2]`.

   다음에 설정한 각 DKIDomain에 대한 HostRecord 및 TXTValue를 복사합니다. [지침](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target=&quot;_blank&quot;}. IT 직원이 이 단계를 완료한 후 관리 > 이메일 > DKIM에서 각 도메인을 확인하는 것을 잊지 마십시오.

## 4단계: 도메인에 대한 MX 레코드 설정 {#step-set-up-mx-records-for-your-domain}

MX 레코드를 사용하면 회신과 자동 응답자를 처리하기 위해 이메일을 보내는 도메인으로 메일을 받을 수 있습니다. 회사 도메인에서 보내는 경우 이미 이 구성이 되었을 수 있습니다. 그렇지 않은 경우 일반적으로 회사 도메인의 MX 레코드에 매핑하도록 설정할 수 있습니다.

## 아웃바운드 IP 주소 {#outbound-ip-addresses}

아웃바운드 연결은 Marketo Engage이 사용자를 대신하여 인터넷을 통해 서버에 연결하는 것입니다. 사용하는 일부 파트너/공급업체 또는 고유한 IT 조직은 허용 목록을 사용하여 서버에 대한 액세스를 제한할 수 있습니다. 그럴 경우 Marketo Engage 아웃바운드 IP 주소 블록을 허용 목록에 추가하여 제공해야 합니다.

**Webhooks**

Marketo Engage [Webhooks](/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md){target=&quot;_blank&quot;}은 아웃바운드 통합 메커니즘입니다. 다음의 경우 [Webhook 호출](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/call-webhook.md){target=&quot;_blank&quot;} 흐름 작업이 스마트 캠페인의 일부로 실행되며 외부 웹 서비스에 대한 HTTP 요청이 수행됩니다. 웹 서비스 게시자가 외부 웹 서비스가 있는 네트워크 방화벽에 있는을 사용하는 경우 게시자는 아래 나열된 IP 주소 블록을 해당 페이지에 추가해야 허용 목록에 추가하다 합니다.

**CRM 동기화**

Marketo Engage [Salesforce CRM 동기화](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/add-an-existing-salesforce-field-to-the-marketo-sync.md){target=&quot;_blank&quot;} 및 [Microsoft Dynamics 동기화](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md){target=&quot;_blank&quot;}는 CRM 공급업체가 게시한 API에 대한 아웃바운드 HTTP 요청을 수행하는 통합 메커니즘입니다. IT 조직이 아래 IP 주소 블록을 통해 CRM 공급업체 API에 액세스하지 못하도록 차단하지 않아야 합니다.

**Marketo Engage 아웃바운드 IP 주소 블록**

다음 표에는 아웃바운드 호출을 수행하는 모든 Marketo Engage 서버가 나와 있습니다. Marketo Engage에서 나가는 연결을 받도록 IP 허용 목록에 추가하다, 서버, 방화벽, 액세스 제어 목록, 보안 그룹 또는 타사 서비스를 구성하는 경우 아래 목록을 사용합니다.

<table>
 <tbody>
  <tr>
   <th>IP 블록(CIDR 표기법)</th>
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
   <tr>
   <td>185.28.196.0/22</td>
  </tr>
   <tr>
   <td>130.248.172.0/24</td>
  </tr>
   <tr>
   <td>130.248.173.0/24</td>
  </tr>
  <tr>
   <td>103.237.104.0/22</td>
  </tr>
  <tr>
   <td>94.236.119.0/26</td>
  </tr>
 </tbody>
</table>

<table>
 <tbody>
  <tr>
   <th>개별 IP 주소</th>
  </tr>
  <tr>
   <td>54.212.167.17</td>
  </tr>
   <tr>
   <td>44.235.171.179</td>
  </tr>
   <tr>
   <td>35.165.244.220</td>
  </tr>
   <tr>
   <td>52.20.211.99</td>
  </tr>
   <tr>
   <td>54.237.141.197</td>
  </tr>
  <tr>
   <td>54.160.246.246</td>
  </tr>
   <tr>
   <td>18.200.201.81</td>
  </tr>
  <tr>
   <td>34.247.24.245</td>
  </tr>
   <tr>
   <td>54.220.138.65</td>
  </tr>
  <tr>
   <td>13.237.155.207</td>
  </tr>
   <tr>
   <td>13.55.192.247</td>
  </tr>
  <tr>
   <td>52.64.109.86</td>
  </tr>
 </tbody>
</table>

