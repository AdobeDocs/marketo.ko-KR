---
unique-page-id: 2949469
description: 설정 단계 - Marketo 문서 - 제품 설명서
title: 설정 단계
exl-id: ef6b7311-55ca-4384-a24c-714eae89a57d
source-git-commit: 74da8ebbd564b11e2795da31321ca47493135f48
workflow-type: tm+mt
source-wordcount: '2043'
ht-degree: 0%

---

# 설정 단계 {#setup-steps}

**Marketo Engage 시작!**

Marketo 사용에 앞서 몇 가지 단계를 완료해야 합니다.

이러한 단계는 다음과 같습니다.

* 일부 기본 계정 설정
* 랜딩 페이지 URL 및 이메일 링크를 브랜딩하여 신뢰 및 전달성을 개선합니다.
* CRM 동기화 중
* 회사 웹 사이트에 추적 코드 추가

>[!NOTE]
>
>회사가 다음과 같은 경우에만 이 단계를 수행해야 합니다. **Marketo을 처음 사용**. 그렇지 않은 경우 설정이 이미 수행되었을 수 있습니다.

일부 단계는 IT 팀의 도움이 필요합니다.

>[!TIP]
>
>다음을 수행하는 경우 [이 체크리스트 인쇄](/help/marketo/getting-started/setup/setup-checklist.md){target="_blank"}, 항목을 완료하면 체크아웃할 수 있습니다.

## 로그인 및 추가 Marketo 사용자 만들기 {#log-in-and-create-additional-marketo-users}

Marketo에 로그인 [여기](https://app.marketo.com/){target="_blank"} 전자 메일로 받은 자격 증명을 사용합니다.

![](assets/setup-steps-1.png)

축하합니다! 현재 Marketo에 있으며 탐색을 시작할 수 있습니다. 마케팅 팀의 동료를 초대하여 함께 참여하도록 할 수 있습니다. 새 사용자를 추가하여 이 작업을 수행할 수 있습니다.

로 이동 **[!UICONTROL 관리자]** 영역입니다.

>[!TIP]
>
>여기 있는 동안 **[!UICONTROL 내 계정]** 계정 및 위치 설정을 변경하고 새 구독 이름을 설정합니다.

![](assets/setup-steps-2.png)

>[!NOTE]
>
>**관리자 권한 필요**

클릭 **[!UICONTROL 사용자 및 역할]**.

![](assets/setup-steps-3.png)

클릭 **[!UICONTROL 새 사용자 초대]**.

![](assets/setup-steps-4.png)

동료의 이메일 주소, 이름, 성을 입력합니다. _액세스 만료일 설정은 선택 사항입니다._. 클릭 **[!UICONTROL 다음]**.

![](assets/setup-steps-5.png)

>[!TIP]
>
>만료 날짜는 짧은 기간 동안 Marketo 액세스만 필요한 단기 외부 관련자 또는 컨설턴트에게 적합합니다.

>[!NOTE]
>
>만료 날짜가 되면 사용자가 만료 알림을 받고 계정이 잠깁니다.

역할을 선택하고 **[!UICONTROL 다음]**. 표준 사용자는 관리자를 제외한 모든 영역에 액세스할 수 있습니다.

![](assets/setup-steps-6.png)

>[!NOTE]
>
>5개의 기본 역할 외에도 사용자 정의 역할을 만들 수도 있습니다. 자세히 알아보기 [사용자 역할 및 권한 관리](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"}.

언제든지 초대 텍스트를 조정할 수 있습니다. 클릭 **보내기**.

![](assets/setup-steps-7.png)

이제 새 사용자가 **[!UICONTROL 사용자]** 및 을(를) 탭하여 암호 및 로그인을 만드는 링크가 포함된 이메일이 전송됩니다. 다음 단계!

![](assets/setup-steps-8.png)

## 공인 지원 담당자 설정 {#set-up-your-authorized-support-contacts}

Marketo 지원에서 귀하를 회사의 Marketo 고객 지원 관리자임을 알리는 이메일을 수신했을 수 있습니다. 이 경우 다음을 설정할 수 있습니다. **승인된 지원 담당자** 팀용입니다. 승인된 지원 담당자만 다음을 통해 Marketo 고객 지원에 직접 문의할 수 있습니다. [Marketo 지원 포털](https://support.marketo.com){target="_blank"}.

>[!NOTE]
>
>만들 수 있는 지원 연락처 수는 구입한 패키지에 따라 결정됩니다. 이 제한은 Marketo 지원 이메일에 명시되어 있습니다.

승인된 지원 담당자 문서가 Marketo 커뮤니티로 이동되었습니다. 다음을 참조하십시오. [이 문서](https://nation.marketo.com/t5/Knowledgebase/Managing-Authorized-Support-Contacts/ta-p/254341){target="_blank"}.

>[!NOTE]
>
>Marketo 커뮤니티에 로그인한 사용자만 목록에 표시됩니다. 해당 사용자를 찾을 수 없는 경우 먼저 해당 사용자가 커뮤니티에 로그인했는지 확인하십시오.

## CNAME으로 랜딩 페이지 URL 사용자 지정 {#customize-your-landing-page-urls-with-a-cname}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계는 건너뛸 수 있습니다. 컨설턴트는 킥오프 통화 중 IT 설치 지침 문서를 제공합니다.

>[!NOTE]
>
>**관리자 권한 필요**

랜딩 페이지의 CNAME을 선택합니다. 몇 가지 예:

    * **go**.[CompanyDomain].com
    * **www2**.[CompanyDomain].com
    * **lp**.[CompanyDomain].com

>[!TIP]
>
>짧게 유지하십시오! 짧은 URL을 기억하기가 더 쉽습니다. 도메인으로 &quot;go&quot;를 제안합니다.

첫 번째 부분(굵은 글꼴)은 `[LandingPageCNAME]`. 5단계에서 필요합니다.

랜딩 페이지 CNAME으로 바꿀 Munchkin ID를 검색하려면 관리 영역으로 이동합니다.

![](assets/setup-steps-9.png)

클릭 **내 계정**.

![](assets/setup-steps-10.png)

다음을 복사합니다. [!UICONTROL 계정 문자열] 랜딩 페이지 설정에서.

![](assets/setup-steps-11.png)

다음 은 `[Munchkin ID]`. 저장합니다. 5단계에서 IT에 제공해야 합니다.

랜딩 페이지에서 Marketo(호스팅된 위치) 대신 회사 도메인을 사용하도록 도메인 설정을 구성합니다.

## 이메일 전달성 확인 {#ensure-email-deliverability}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계는 건너뛸 수 있습니다. 컨설턴트는 킥오프 통화 중 IT 설치 지침 문서를 제공합니다.

이메일이 가능한 한 많은 사람에게 도달하도록 하기 위해 취할 수 있는 몇 가지 조치가 있습니다.

* **추적 링크 브랜딩**. Marketo의 이메일에 포함된 링크에서 자체 도메인(Marketo 대신)을 사용하도록 CNAME을 선택할 수 있습니다. 이렇게 하면 도메인 브랜딩이 강화되고 수신자와의 신뢰와 전달성이 높아집니다.
* **기업 이메일에 Marketo허용 목록에 추가하다 를 추가합니다.** 실제 사용자에게 이메일을 보내기 전에 테스트 계정으로 테스트 이메일을 보내는 것이 일반적인 모범 사례입니다. Marketo 허용 목록에 추가를 사용하면 이러한 테스트 이메일이 차단되거나 스팸으로 플래그가 지정되는 것을 방지할 수 있습니다.
* **SPF와 DKIM을 설정합니다.** 이러한 기술은 수신자에게 Marketo 이메일이 스팸이 아님을 보장합니다. 수신자의 스팸 필터가 Marketo 이메일을 거부하지 않도록 하려면 다음 단계를 따르십시오. [이메일 전달성을 위한 SPF 및 DKIM 설정](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md).
* **도메인에 대한 MX 레코드를 설정합니다.** MX 레코드를 사용하면 회신 및 자동 응답자를 처리하기 위해 전자 메일을 보내는 도메인으로 메일을 받을 수 있습니다. 회사 도메인에서 보내는 경우 이미 이 구성이 되어 있을 수 있습니다. 그렇지 않은 경우 일반적으로 회사 도메인의 MX 레코드에 매핑하도록 설정할 수 있습니다.
* **보낸 사람 주소에 대한 권장 설정.** 모든 이메일 캠페인의 보낸 사람 주소에서 유효하고 기존 및 작업 중인 이메일 도메인을 사용해야 합니다. 회사 도메인에서 전송하는 것보다 회사 도메인의 하위 도메인을 구성하는 것이 유용할 수 있습니다. 이렇게 하면 회사 메일 스트림의 문제가 Marketo 메일 스트림에 영향을 주지 않고 그 반대의 경우도 마찬가지입니다. 또한 다음에서 메일 보내기 `something@nonexistentdomain.com` 이(가) 이메일을 필터링하거나 차단합니다. 보낸 사람의 보낸 사람 주소에 사용되는 모든 도메인에는 유효하고 작동하는 postmaster@ 및 abuse@ 계정이 있어야 합니다.

Google 앱을 사용하여 회사 전자 메일을 호스팅하는 경우 도메인 아래에 abuse@ 또는 postmaster@ 전자 메일을 만들 수 없습니다. 이 문제를 해결하려면 &quot;abuse&quot; 및 &quot;postmaster&quot;라는 그룹을 만들어야 합니다. 이러한 그룹의 구성원인 사용자는 해당 주소(예: postmaster@domain.com)로 전송된 이메일을 받게 됩니다. 그룹 만들기에 대한 자세한 지침은 [여기](https://support.google.com/a/answer/33343#adminconsole){target="_blank"}.

이메일 추적 링크의 CNAME 선택(다음 중 하나 선택) _다름_ 3단계에서 선택한 CNAME 랜딩 페이지에서. 몇 가지 예:

* go2.[회사 도메인].com
* em.[회사 도메인].com
* 와.[회사 도메인].com

첫 번째 부분은 이메일 추적 CNAME, `[EmailTrackingCNAME]`. 5단계에서 IT에 제공해야 합니다.

>[!CAUTION]
>
>이메일 및 랜딩 페이지 CNAME은 달라야 합니다. 또한 &#39;track&#39; 또는 &#39;link&#39;와 같은 CNAME은 사용하지 마십시오. 종종 스팸으로 플래그가 지정됩니다

Marketo 추적 링크를 찾으려면 **[!UICONTROL 관리자]** 영역입니다.

![](assets/setup-steps-12.png)

클릭 **[!UICONTROL 이메일]**.

![](assets/setup-steps-13.png)

다음을 복사합니다. [!UICONTROL 링크 추적] 이메일 설정에서.

다음 [!UICONTROL 링크 추적] 은(는) 다음 형식을 갖습니다. `mkto-[a-z][4 digits].com`.

![](assets/setup-steps-14.png)

이 은(는) `[MktoTrackingLink]`. 저장합니다. 5단계에서 IT에 제공해야 합니다.

&quot;From&quot; 도메인을 수집합니다. 모든 &quot;From&quot; 도메인 목록 만들기(예: `[Sender]@[FromDomain].com`)을 사용하여 Marketo에서 이메일을 보낼 계획입니다. 대부분의 경우 하나만 있습니다.

예: &#39;marketo.com,&#39; &#39;info.marketo.com,&#39;. 이는 다음과 같습니다 `[FromDomain1]`,`[FromDomain2]`등 그들을 구해 5단계에서 IT에 제공해야 합니다.

이제 요청을 IT에 보내는 데 필요한 모든 정보가 준비되었습니다!

## IT에 프로토콜 구성 요청 {#ask-it-to-configure-protocols}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계는 건너뛸 수 있습니다. 컨설턴트는 킥오프 통화 중 IT 설치 지침 문서를 제공합니다.

필요한 모든 정보를 수집했으면 IT에 요청을 보낼 준비가 된 것입니다. 아래 텍스트를 템플릿으로 사용하여 굵은 텍스트를 고유한 정보로 바꿀 수 있습니다.

[이 문서에 대한 링크 포함](/help/marketo/getting-started/setup/configure-protocols-for-marketo.md).

이 텍스트를 전자 메일에 붙여넣고 굵은 자리 표시자를 바꿉니다.

>[!NOTE]
>
>자리 표시자를 대체할 텍스트를 결정하려면 위의 3단계와 4단계를 참조하십시오. 기억하십시오. `[LandingPageCNAME]` 및 `[EmailTrackingCNAME]` 은(는) 달라야 합니다.

`----------------------------------------------`

뛰어난 IT 관리자,

이제 마케팅 팀은 Marketo 플랫폼을 사용하여 사용자와 커뮤니케이션합니다. 우수한 이메일 전달성을 보장하려면 다음 사항을 변경해야 합니다.

`1)` 랜딩 페이지의 경우 DNS 항목(CNAME)을 추가합니다. **[랜딩 페이지 이름]**.**[회사 도메인]**.com, 가리키기 **[Munchkin ID]**.mktoweb.com입니다.

`2)` 이메일의 추적 링크에 대해 DNS 항목(CNAME)을 추가합니다. **[EmailTrackingCNAME]**.**[회사 도메인]**.com, 가리키기 **[MktoTrackingLink]**.

`3)` 허용 목록에 추가하다 Marketo

    * IP 주소를 사용하는 경우 허용 목록에 추가하다 이메일에 아래 나열된 IP를 추가합니다.
    199.15.212.0/22
    
    192.28.144.0/20
    
    192.28.160.0/19
    
    185.28.196.0/22
    
    130.248.172.0/24
    
    130.248.173.0/24
    
    103.237.104.0/22
    
    94.236.119.0/26

>[!NOTE]
>
>사용자 환경에 맞는 Marketo 허용 목록에 추가하다 IP의 축약된 목록을 원하는 경우 지원 팀에 문의하십시오.

    * 스팸 방지 시스템이 발신 도메인을 사용하는 경우 다음을 추가하십시오.

**`[FromDomain1]`**
**`[FromDomain2]`**

`4)` Marketo에서 대신 서명된 이메일을 보낼 수 있도록 SPF 및 DKIM을 설정해야 합니다.

`a.` SPF를 설정하려면 DNS 항목에 다음 줄을 추가하십시오.

TXT **[출처 도메인]**: v=spf1 mx ip4:**[회사 IP]**
<br/>include: mktomail.com ~all

DNS 항목에 기존 SPF 레코드가 이미 있는 경우 다음을 추가하기만 하면 됩니다.

include:mktomail.com

`[`바꾸기 **출처 도메인** (예: company.com) 및 **회사 IP** 회사 이메일 서버의 IP 주소(예: 255.255.255.255)로 바꿉니다.  Marketo을 통해 여러 도메인에서 이메일을 전송하려면 IT 직원에게 각 도메인에 대해 한 줄에 이 줄을 추가하도록 해야 합니다.`]`

`b.` DKIM의 경우 설정하려는 각 도메인에 대해 DNS 리소스 레코드를 만드십시오. 다음은 서명할 각 도메인의 호스트 레코드 및 TXT 값입니다.

**`[DKIMDomain1]`**: 호스트 레코드: **`[HostRecord1]`** 그리고 TXT 값은 **[TXTValue1]**.

**`[DKIMDomain2]`**: 호스트 레코드: **`[HostRecord2]`** 그리고 TXT 값은 **`[TXTValue2]`**.

`[`다음을 복사합니다. **호스트 레코드** 및 **TXTValue** 각 **디킴도마인** 다음을 수행한 후 을(를) 설정했습니다. [여기에 있는 지침](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md). 의 각 도메인을 확인하는 것을 잊지 마십시오. **관리자 > 이메일 > DKIM** IT 직원이 이 단계를 완료한 후.`]`

`5)` FROM 도메인에 대한 유효한 MX 레코드가 있는지 확인해야 합니다. **[도메인1 부터]**, **[도메인2]**&#x200B;등 확인해줄 수 있나요? 그렇지 않은 경우 회사 도메인 MX 레코드에 매핑되도록 를 구성하십시오. 이렇게 하면 Marketo 우편물에 대한 회신/자동 응답자를 처리할 수 있습니다.

Marketo으로 설정 프로세스를 완료할 수 있도록 이 단계를 완료하면 알려주십시오.

감사합니다! 네가 최고야!

사랑,

**`[Your Name]`**

`----------------------------------------------`

IT로 이메일을 전송합니다. IT에서 이러한 작업을 완료하는 데 시간이 다소 걸릴 수 있습니다. 7단계로 계속 진행할 수 있지만, Marketo 설정을 완료하려면 6단계를 반환해야 합니다.

## IT가 완료되면 Marketo 설정 완료 {#complete-your-marketo-setup-after-it-finishes}

IT 담당자가 작업을 완료하면 다음 단계에 따라 랜딩 페이지 및 이메일 CNAME를 추가하고 DKIM 서명을 활성화합니다.

로 이동 **[!UICONTROL 관리자]** 랜딩 페이지 CNAME을 추가할 영역

![](assets/setup-steps-15.png)

랜딩 페이지 를 선택하고 **[!UICONTROL 편집]** 다음에서 [!UICONTROL 설정] 영역입니다.

![](assets/setup-steps-16.png)

필드에 새 도메인 이름을 입력합니다 **[!UICONTROL 랜딩 페이지의 도메인 이름]**. 형식은 다음과 같아야 합니다.

`[LandingPageCNAME].[CompanyDomain].com`

![](assets/setup-steps-17.png)

다음에서 **[!UICONTROL 대체 항목]** 페이지 필드에 랜딩 페이지를 사용할 수 없는 경우 사람들이 이동할 URL을 입력합니다. 대체 페이지가 없는 경우 회사 홈 페이지를 사용할 수 있습니다. 다음에서 **[!UICONTROL 홈페이지]** 필드에 회사 웹 사이트를 입력합니다.

![](assets/setup-steps-18.png)

다음에서 [!UICONTROL 관리자] 영역, 선택 **[!UICONTROL 이메일]** 이메일 CNAME을 추가하려면

![](assets/setup-steps-19.png)

아래로 스크롤하여 [!UICONTROL 브랜딩 도메인]. 도메인을 선택하고 **[!UICONTROL 편집]**.

![](assets/setup-steps-20.png)

도메인 필드에 이메일 추적 도메인을 입력합니다. 형식은 다음과 같아야 합니다.

`[EmailTrackingCNAME].[CompanyDomain].com`. 클릭 **[!UICONTROL 저장]**.

![](assets/setup-steps-21.png)

## CRM 통합 {#integrate-your-crm}

이는 설정에서 가장 흥미로운 단계일 수 있습니다. CRM에 저장된 모든 리드 및 연락처로 Marketo을 채워야 할 때입니다.

회사에서 사용하는 CRM에 따라 다음 중에서 선택하십시오.

    * [통합: Marketo [!DNL Salesforce.com]](/help/marketo/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.md)
    * [통합: Marketo [!DNL Microsoft Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md)

>[!NOTE]
>
>이러한 단계를 완료하려면 회사의 CRM 관리자의 도움이 필요합니다.

## 웹 사이트에 추적 코드 추가 {#add-tracking-code-to-your-website}

>[!NOTE]
>
>다음 대상이 맞습니까? [!DNL Launch Pack] 고객? 이 단계는 건너뛸 수 있습니다. 컨설턴트가 다음을 제공합니다. [!DNL Munchkin] IT 설치 지침 문서의 코드 지침

Marketo에는 사용자 지정 추적 JavaScript(라고 함)가 있습니다 [!DNL Munchkin])를 사용하여 웹 페이지에서 개인 활동을 추적할 수 있습니다. [!DNL Munchkin] 웹 사이트를 Marketo에 통합하는 데 필요합니다. 다음 단계를 따라 [추가 [!DNL Munchkin] 웹 사이트에 대한 추적 코드](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}.

>[!NOTE]
>
>추적 코드를 추가하는 데 필요한 HTML 관련 경험입니다.

## 성능 기대치 {#performance-expectations}

Marketo의 성능 측면에서 기대할 수 있는 사항은 무엇입니까? 마케팅 캠페인의 크기와 복잡성에 따라 달라질 수 있습니다. 그러나 의 일부 표에서 &quot;표준&quot; 열에 요약된 것과 동일한 성능 수준을 기대할 수 있습니다. [Marketo Engage 제품 설명](https://helpx.adobe.com/legal/product-descriptions/adobe-marketo-engage---product-description.html){target="_blank"}. The "Performance" and "Performance Plus" columns refer to performance tier packages that provide [higher performance levels](https://nation.marketo.com/t5/product-documents/marketo-engage-performance-tiers/ta-p/328835){target="_blank"}.

모든 설정 단계가 끝났습니다. 이제 Marketo에 다이빙해서 사용하는 일만 남았습니다!
