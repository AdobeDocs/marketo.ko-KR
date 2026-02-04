---
unique-page-id: 4720433
description: Marketo Engage에 대한 프로토콜 구성 - Marketo Engage 문서 - 제품 설명서
title: Marketo Engage에 대한 프로토콜 구성
exl-id: cf2fd4ac-9229-4e52-bb68-5732b44920ef
feature: Getting Started
source-git-commit: ee8b46179d9fe85c4d5f2ebd7c2d31b7fbf516c3
workflow-type: tm+mt
source-wordcount: '2129'
ht-degree: 100%

---

# Marketo Engage에 대한 프로토콜 구성{#configure-protocols-for-marketo-engage}

사용자 또는 사용자 조직에서 제한적 방화벽 또는 프록시 서버 설정을 사용하는 경우, 사용자 또는 네트워크 관리자는 Adobe Marketo Engage가 예상대로 작동하도록 특정 도메인 및 IP 주소 범위를 허용 목록에 추가해야 할 수 있습니다.

아래 프로토콜을 구현하는 데 도움이 필요하면 이 문서를 IT 부서와 공유하십시오. IT 부서에서 허용 목록을 사용하여 웹 액세스를 제한하는 경우, 다음 도메인(별표 포함)을 추가하여 모든 Marketo Engage 리소스 및 웹소켓을 허용하도록 해야 합니다.

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`
* `*.experience.adobe.com`
* `*.adobe.net`

## 1단계: 랜딩 페이지 및 이메일에 대한 DNS 레코드 만들기 {#step-create-dns-records-for-landing-pages-and-email}

**링크 CNAME 추적**

마케팅 팀에서 새 CNAME 레코드에 대한 두 가지 요청을 보냈어야 합니다. 첫 번째 요청은 랜딩 페이지 URL에 대한 것이므로 랜딩 페이지는 Marketo Engage(실제 호스트)가 아닌 도메인을 나타내는 URL에 표시됩니다. 두 번째 요청은 Marketo Engage에서 보내는 이메일에 포함된 추적 링크에 대한 것입니다.

`1` **랜딩 페이지의 CNAME 추가**

`[YourLandingPageCNAME]`이(가) Marketo Engage 랜딩 페이지에 할당된 고유한 계정 문자열을 가리키도록 사용자의 DNS 레코드에 보낸 랜딩 페이지 CNAME을 추가합니다. 도메인 등록자의 사이트에 로그인하여 랜딩 페이지 CNAME 및 계정 문자열을 입력합니다. 일반적으로 다음과 같은 세 가지 필드가 포함됩니다.

* 별칭: `[YourLandingPageCNAME]` 입력(마케팅에서 제공)
* 유형: CNAME
* 대상: `[MunchkinID].mktoweb.com` 입력(마케팅에서 제공)

`2` **이메일 추적 링크에 CNAME 추가**

`[YourEmailCNAME]`이(가) Marketo Engage이 할당한 기본 추적 링크인 [MktoTrackingLink]을(를) 가리키도록 CNAME 마케팅이 사용자에게보낸
`[YourEmailCNAME].[YourDomain].com` IN CNAME `[MktoTrackingLink]` 형식의 전자 메일 추가

예:

`pages.abc.com IN CNAME mkto-a0244.com`

>[!NOTE]
>
>`[MktoTrackingLink]`은(는) 기본 브랜딩 도메인이어야 합니다.

`3` **마케팅 팀에 알림**

이 프로세스를 완료하면 마케팅 팀에 알립니다.

`4` **SSL 인증서 프로비전을 시작하려면 [Adobe 지원 센터](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 문의하십시오.**

이 프로세스를 완료하는 데 영업일 기준 최대 3일이 소요될 수 있습니다.

## 2단계: Marketo Engage IP를 허용 목록에 추가 {#step-allowlist-marketo-ips}

마케팅 그룹이 Marketo Engage를 사용하여 테스트 이메일을 전송하는 경우(이메일 알림을 전송하기 전의 모범 사례), 발신자 IP 주소를 이용하여 이메일이 유효한지 확인하는 스팸 방지 시스템에 의해 테스트 이메일이 차단되는 경우가 있습니다. 이러한 테스트 이메일이 도착하는지 확인하려면 Marketo Engage를 허용 목록에 추가하십시오.

다음 IP 주소를 기업 허용 목록에 추가합니다.

130.248.172.0/24

130.248.173.0/24

130.248.244.88/29

185.28.196.0/22

192.28.144.0/20

192.28.160.0/19

199.15.212.0/22

일부 스팸 방지 시스템은 허용 목록 추가를 위해 IP 주소 대신 이메일 반환 경로 필드를 사용합니다. 이 경우 Marketo Engage에서는 여러 사서함 하위 도메인을 사용하므로 가장 좋은 방법은 &#39;&#42;.mtomail.com&#39;을 허용 목록에 추가하는 것입니다. 다른 스팸 방지 시스템은 발신 주소를 기반으로 허용 목록을 설정합니다. 이러한 경우 마케팅 그룹이 사람/리드와 통신하는 데 사용하는 모든 전송(&#39;발신&#39;) 도메인을 포함해야 합니다.

>[!NOTE]
>
>고유한 기술을 사용하는 Postini에서는 IP 범위를 허용 목록에 추가해야 합니다. [Postini에서 허용 목록에 추가](https://nation.marketo.com/docs/DOC-1066)를 참조하십시오.

## 3단계: SPF 및 DKIM 설정 {#step-set-up-spf-and-dkim}

마케팅 팀은 DNS 리소스 레코드에 추가할 DKIM(Domain Keys Identified Mail) 정보도 전송했어야 합니다. 다음 단계에 따라 DKIM 및 SPF(발신자 정책 프레임워크)를 올바로 구성한 후 업데이트되면 마케팅 팀에 알립니다.

1. SPF를 설정하려면 DNS 항목에 다음 줄을 추가합니다.

   `[CompanyDomain]` IN TXT v=spf1 mx ip4:`[CorpIP]`
include: mktomail.com ~all

   DNS 항목에 이미 기존의 SPF 레코드가 있는 경우에는
include: mktomail.com만 추가하면 됩니다.

   CompanyDomain을 웹 사이트의 도메인(예: &quot;`(company.com/)`&quot;)으로, CorpIP를 회사 이메일 서버(예: &quot;255.255.255.255&quot;)로 교체합니다. Marketo Engage을 통해 여러 도메인에서 이메일을 전송하려면 IT 직원이 각 도메인에 대해 한 줄에서 이 줄을 추가하게 해야 합니다.

1. DKIM의 경우 설정하려는 각 도메인에 대해 DNS 리소스 레코드를 만듭니다. 다음은 우리가 서명하려는 각 도메인에 대한 호스트 레코드 및 TXT 값입니다.

   `[DKIMDomain1]`: 호스트 레코드는 `[HostRecord1]`이고 TXT 값은 `[TXTValue1]`입니다.

   `[DKIMDomain2]`: 호스트 레코드는 `[HostRecord2]`이고 TXT 값은 `[TXTValue2]`입니다.

   [이 지침](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}에 따라 설정한 각 DKIMDomain에 해당하는 HostRecord 및 TXTValue를 복사합니다. IT 직원이 이 단계를 완료한 후에는 관리 > 이메일 > DKIM에서 각 도메인을 확인하는 것을 잊지 마십시오.

## 4단계: DMARC 설정 {#set-up-dmarc}

DMARC(도메인 기반 메시지 인증, 보고 및 적합성)는 무단 사용으로부터 도메인을 보호하기 위해 조직에서 사용하는 인증 프로토콜입니다. DMARC는 SPF 및 DKIM과 같은 기존의 인증 프로토콜을 확장하여 도메인에서 인증 실패가 발생할 경우 취해야 할 액션을 수신 서버에 알립니다. 현재 DMARC은 선택 사항이지만 조직의 브랜드와 평판을 더 잘 보호할 수 있다는 점에서 적극 권장합니다. Google 및 Yahoo와 같은 주요 제공업체는 2024년 2월부터 대량 발신자에게 DMARC 사용을 의무화할 예정입니다.

DMARC가 작동하려면 다음 DNS TXT 레코드 중 하나 이상이 있어야 합니다.

* 유효한 SPF
* 사용자의 FROM: 도메인에 대한 유효한 DKIM 레코드(Marketo Engage에 권장됨)

또한 FROM: 도메인에 대한 DMARC 고유의 DNS TXT 레코드가 있어야 합니다. 필요하다면 DMARC 보고서가 조직 내 어디로 전달되어야 하는지 표시하도록 원하는 이메일 주소를 정의하여 보고서를 모니터링할 수 있습니다.

DMARC의 잠재적 영향을 이해하기 위해 DMARC 정책을 p=none에서 p=quarantine, p=reject로 승격하고 SPF 및 DKIM에 대한 정렬을 완화하도록 DMARC 정책을 설정하여 DMARC 구현을 서서히 배포하는 것이 좋습니다.

### DMARC 워크플로 예시 {#dmarc-example-workflow}

1. DMARC 보고서를 받도록 구성되어 있으면 다음 작업을 수행해야 합니다.

   I. 받은 피드백 및 보고서를 분석하고 사용합니다(p=none). 이렇게 하면 수신자는 인증에 실패하는 메시지에 대해서는 아무 작업도 수행하지 않지만 발신자에게는 계속 이메일 보고서를 보냅니다.

   II. 정상적인 메시지가 인증에 실패하는 경우 SPF/DKIM 문제를 검토하여 수정합니다.

   III. 모든 정상적인 이메일에 대해 SPF 또는 DKIM이 정렬되어 인증을 통과하는지 확인합니다.

   IV. 보고서를 검토하여 SPF/DKIM 정책에 따라 예상되는 결과가 나오는지 확인합니다.

1. 정책을 (p=quarantine)으로 조정하면 인증에 실패한 이메일을 격리(일반적으로 스팸 폴더에 해당 메시지를 저장)하도록 수신 이메일 서버에 지시합니다.

   I. 보고서를 검토하여 결과가 기대에 부합하는지 확인합니다.

1. p=quarantine 수준에서 메시지의 비헤이비어에 만족하는 경우 정책을 (p=reject)로 조정할 수 있습니다. p=reject 정책은 수신자에게 인증에 실패한 도메인에 대한 모든 이메일을 완전히 거부(바운스)하도록 지시합니다. 이 정책을 활성화하면 도메인에서 100% 인증된 것으로 확인된 이메일만 받은 편지함에 배치될 수 있습니다.

>[!CAUTION]
>
>이 정책을 신중하게 사용하고 조직에 적합한지 확인합니다.

### DMARC 보고 {#dmarc-reporting}

DMARC는 SPF/DKIM에 실패한 이메일에 대한 보고서를 수신할 수 있는 기능을 제공합니다. ISP 서비스에 의해 생성된 두 개의 보고서가 있습니다. 이 보고서는 보낸 사람이 DMARC 정책에서 RUA/RUF 태그를 통해 받을 수 있는 인증 프로세스의 일부입니다.

* 집계 보고서(RUA): GDPR(일반정보보호 규정)에 따라 민감할 수 있는 PII(개인 식별 정보)를 포함하지 않습니다.

* 포렌식 보고서(RUF): GDPR에 따라 민감한 이메일 주소를 포함합니다. 활용하기 전에 GDPR 준수가 필요한 정보를 처리하는 방법을 내부적으로 확인하는 것이 가장 좋습니다.

이러한 보고서의 주요 용도는 스푸핑 시도가 있는 이메일에 대한 개요를 받는 것입니다. 이것들은 매우 기술적인 보고서이므로 서드파티 도구를 통해 이해하는 것이 가장 좋습니다.

### DMARC 레코드 예시 {#example-dmarc-records}

* 최소 레코드: `v=DMARC1; p=none`

* 보고서를 받기 위해 이메일 주소로 연결되는 레코드: `v=DMARC1; p=none;  rua=mailto:emaill@domain.com;     ruf=mailto:email@domain.com`

### DMARC 태그 및 작업 {#dmarc-tags-and-what-they-do}

DMARC 레코드에는 DMARC 태그라는 여러 구성 요소가 있습니다. 각 태그에는 DMARC의 특정 측면을 지정하는 값이 있습니다.

<table>
<thead>
  <tr>
    <th>태그 이름 </th>
    <th>필수/선택 사항 </th>
    <th>함수 </th>
    <th>예 </th>
    <th>기본 값 </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>v</td>
    <td>필수</td>
    <td>이 DMARC 태그는 버전을 지정합니다. 버전은 현재 하나만 있으므로 v=DMARC1이라는 고정 값을 갖게 됩니다.</td>
    <td>V=DMARC1 DMARC1</td>
    <td>DMARC1</td>
  </tr>
  <tr>
    <td>p</td>
    <td>필수</td>
    <td>수신자가 인증 확인에 실패한 이메일을 보고, 격리 또는 거부하도록 지시하는 선택된 DMARC 정책을 보여줍니다.</td>
    <td>p=없음, 격리 또는 거부</td>
    <td>-</td>
  </tr>
  <tr>
    <td>fo</td>
    <td>선택 사항입니다</td>
    <td>도메인 소유자가 보고 옵션을 지정할 수 있습니다.</td>
    <td>0: 모든 것이 실패하면 보고서 생성
    <br>1: 어떤 것이 실패하면 보고서 생성
    <br>d: DKIM 실패 시 보고서 생성
    <br>s: SPF 실패 시 보고서 생성</td>
    <td>1 (DMARC 보고서에 권장됨)</td>
  </tr>
  <tr>
    <td>pct</td>
    <td>선택 사항</td>
    <td>필터링 대상 메시지의 비율을 언급합니다.</td>
    <td>pct=20</td>
    <td>100</td>
  </tr>
  <tr>
    <td>rua</td>
    <td>선택 사항 (권장)</td>
    <td>집계 보고서가 전달될 위치를 식별합니다.</td>
    <td>rua=mailto:aggrep@example.com</td>
    <td>-</td>
  </tr>
  <tr>
    <td>ruf</td>
    <td>선택 사항 (권장)</td>
    <td>포렌식 보고서가 전달될 위치를 식별합니다.</td>
    <td>ruf=mailto:authfail@example.com</td>
    <td>-</td>
  </tr>
  <tr>
    <td>sp</td>
    <td>선택 사항</td>
    <td>상위 도메인의 하위 도메인에 대한 DMARC 정책을 지정합니다.</td>
    <td>sp=reject</td>
    <td>-</td>
  </tr>
  <tr>
    <td>adkim</td>
    <td>선택 사항</td>
    <td>엄격 (s) 또는 완화 ®일 수 있습니다. 완화된 정렬은 DKIM 서명에 사용되는 도메인이 "발신" 주소의 하위 도메인일 수 있음을 의미합니다. 엄격한 정렬은 DKIM 서명에 사용되는 도메인이 발신 주소에 사용된 도메인과 정확히 일치해야 함을 의미합니다.</td>
    <td>adkim=r </td>
    <td>r</td>
  </tr>
  <tr>
    <td>aspf</td>
    <td>선택 사항</td>
    <td>Strict (s) 또는 Relaxed ®일 수 있습니다. 완화된 정렬은 반환 경로 도메인이 발신 주소의 하위 도메인이 될 수 있음을 의미합니다. 엄격한 정렬은 반환 경로 도메인이 발신 주소와 정확히 일치해야 함을 의미합니다.</td>
    <td>aspf=r</td>
    <td>r</td>
  </tr>
</tbody>
</table>

DMARC 및 모든 옵션에 대한 자세한 내용은 [https://dmarc.org/](https://dmarc.org/){target="_blank"}을(를) 참조하십시오.

### DMARC 및 Marketo Engage {#dmarc-and-marketo-engage}

DMARC 정렬에는 DKIM 정렬과 SPF 정렬의 두 가지 유형이 있습니다.

>[!NOTE]
>
>Marketo Engage용 DKIM과 SPF에서 DMARC 정렬을 수행하는 것이 좋습니다.

* DKIM 정렬 DMARC—DKIM 정렬 DMARC을 설정하려면 다음을 수행해야 합니다.

   * 메시지의 발신: 도메인에 대한 DKIM을 설정합니다. [이 문서](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}에 나오는 지침을 사용합니다.
   * 이전에 구성된 FROM:/DKIM 도메인에 대한 DMARC를 구성합니다.

* DMARC 정렬 SPF—브랜드 반환 경로를 통해 DMARC 정렬 SPF를 설정하려면 다음을 수행해야 합니다.

   * 브랜드 반환 경로 도메인을 설정합니다.
      * 적절한 SPF 레코드를 구성합니다.
      * 메일을 보낸 데이터 센터의 기본 MX를 다시 가리키도록 MX 레코드를 변경합니다

   * 브랜드 반환 경로 도메인에 대해 DMARC를 구성합니다.

* 전용 IP를 통해 Marketo Engage에서 메일을 보내고 브랜드 반환 경로를 구현하지 않았거나 구현했는지 확실하지 않은 경우 [Adobe 지원 센터](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}를 통해 티켓을 개설하십시오.

* 공유 IP 풀을 통해 Marketo Engage에서 메일을 보내는 경우 [여기에서 적용](https://na-sjg.marketo.com/lp/marketoprivacydemo/Trusted-IP-Sending-Range-Program.html){target="_blank"}하여 신뢰할 수 있는 IP의 자격이 있는지 확인할 수 있습니다. 브랜드 반환 경로는 Marketo Engage의 신뢰할 수 있는 IP에서 전송하는 사용자에게 무료로 제공됩니다. 이 프로그램에 승인되면 Adobe 지원 센터에 연락하여 브랜드 반환 경로를 설정합니다.

   * 신뢰할 수 있는 IP: 월 75,000건 미만의 소량 전송을 하는 사용자 중 전용 IP를 사용할 자격이 없는 사용자를 위해 예약된 공유 IP 풀입니다. 이러한 사용자는 모범 사례 요구 사항도 충족해야 합니다.

* 공유 IP를 통해 Marketo Engage에서 메일을 보내며 신뢰할 수 있는 IP를 사용할 자격이 없고 매월 100,000개 이상의 메시지를 보내는 경우, Adobe 계정 팀(계정 관리자)에 연락하여 전용 IP를 구매해야 합니다.

* Marketo Engage에서는 엄격한 SPF 정렬이 지원되거나 권장되지 않습니다.

## 5단계: 도메인에 대한 MX 레코드 설정 {#step-set-up-mx-records-for-your-domain}

MX 레코드를 사용하면 이메일을 보내는 도메인으로 메일을 수신하여 답장과 자동 응답을 처리할 수 있습니다. 회사 도메인에서 보내는 경우 이미 구성되어 있을 수 있습니다. 그렇지 않은 경우, 일반적으로 회사 도메인의 MX 레코드에 매핑하도록 설정할 수 있습니다.

## 아웃바운드 IP 주소 {#outbound-ip-addresses}

아웃바운드 연결은 Marketo Engage가 사용자를 대신하여 인터넷 서버에 연결하는 것입니다. 함께 일하는 일부 파트너/공급업체 또는 자체 IT 조직은 허용 목록을 사용하여 서버에 대한 액세스를 제한할 수 있습니다. 그렇다면 허용 목록에 추가할 수 있도록 Marketo Engagement 아웃바운드 IP 주소 블록을 제공해야 합니다.

**웹후크**

Marketo Engage [웹후크](/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md){target="_blank"}은(는) 아웃바운드 통합 메커니즘입니다. 스마트 캠페인의 일부로 [웹후크 호출](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/call-webhook.md){target="_blank"} 흐름 작업이 실행되면 외부 웹 서비스에 HTTP 요청이 이루어집니다. 웹 서비스 게시자가 외부 웹 서비스가 있는 네트워크의 방화벽에서 허용 목록을 사용하는 경우, 게시자는 아래 나열된 IP 주소 블록을 해당 허용 목록에 추가해야 합니다.

**CRM 동기화**

Marketo Engage [Salesforce CRM 동기화](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/add-an-existing-salesforce-field-to-the-marketo-sync.md){target="_blank"} 및 [Microsoft Dynamics 동기화](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md){target="_blank"}는 CRM 공급업체에서 게시한 API에 대한 아웃바운드 HTTP 요청을 만드는 통합 메커니즘입니다. IT 조직이 아래 IP 주소 블록 중 어떤 것도 CRM 공급업체 API에 액세스하는 것을 차단하지 않도록 해야 합니다.

**Marketo Engage 아웃바운드 IP 주소 블록**

다음 표는 아웃바운드 호출을 수행하는 모든 Marketo Engage 서버를 망라한 것입니다. Marketo Engage에서 발신 연결을 수신하도록 IP 허용 목록, 서버, 방화벽, 액세스 제어 목록, 보안 그룹 또는 서드파티 서비스를 구성하는 경우 아래 목록을 사용하십시오.

<table>
 <tbody>
  <tr>
   <th>IP 블록 (CIDR 표기법)</th>
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
  <tr>
   <td>124.47.174.193</td>
  </tr>
  <tr>
   <td>130.248.168.16</td>
  </tr>
   <tr>
   <td>130.248.168.17</td>
  </tr>
  <tr>
   <td>199.15.213.245</td>
  </tr>
  <tr>
   <td>199.15.215.245</td>
  </tr>
 </tbody>
</table>
