---
unique-page-id: 2949469
description: 설정 단계 - Marketo 문서 - 제품 설명서
title: 설정 단계
exl-id: ef6b7311-55ca-4384-a24c-714eae89a57d
source-git-commit: 865486a0ce31297d8cc96e5fbd97275d045664b2
workflow-type: tm+mt
source-wordcount: '2005'
ht-degree: 0%

---

# 설정 단계 {#setup-steps}

**Marketo 시작!**

Marketo을 사용하기 전에 완료해야 하는 몇 가지 단계가 있습니다.

이러한 단계는 다음과 같습니다.

* 기본 계정 설정
* 신뢰 및 게재 능력을 향상시키기 위해 랜딩 페이지 URL 및 이메일 링크 브랜딩
* CRM 동기화
* 회사 웹 사이트에 추적 코드 추가

>[!NOTE]
>
>회사가 **Marketo에**. 없는 경우 설정이 이미 수행되었을 수 있습니다.

일부 단계에는 IT 팀의 도움이 필요합니다.

>[!TIP]
>
>만약 [이 검사 목록 인쇄](/help/marketo/getting-started/setup-steps/setup-checklist.md){target=&quot;_blank&quot;} 항목을 완료할 때 항목을 체크 아웃할 수 있습니다.

## 로그인 및 추가 Marketo 사용자 만들기 {#log-in-and-create-additional-marketo-users}

1. Marketo에 로그인 [여기](https://app.marketo.com/)전자 메일로 받은 자격 증명을 사용하여 {target=&quot;_blank&quot;}.

   ![](assets/new-login-screen-hand.jpg)

축하합니다! 이제 Marketo에 오셔서 탐색을 시작할 수 있습니다. 마케팅 팀에 있는 동료들을 초대하여 여러분과 함께 할 수도 있습니다. 새 사용자를 추가하여 이 작업을 수행할 수 있습니다.

로 이동합니다. **관리** 영역.

>[!TIP]
>
>여기에 있는 동안 **내 계정** 계정 및 위치 설정을 변경하고 새 구독 이름을 설정합니다.

![](assets/admin.png)

>[!NOTE]
>
>**관리 권한 필요**

클릭 **사용자 및 역할**.

![](assets/image2015-1-6-13-3a14-3a43.png)

클릭 **새 사용자 초대**.

![](assets/image2015-1-6-13-3a14-3a6.png)

친구의 이메일 주소, 이름 및 성을 입력합니다.

![](assets/image2016-5-24-10-3a11-3a12.png)

달력 선택기를 사용하여 초대 사유와 액세스 만료 날짜를 입력합니다(선택적). 클릭 **확인**.

![](assets/image2016-5-24-10-3a13-3a9.png)

클릭 **다음**.

![](assets/image2016-5-24-10-3a14-3a9.png)

>[!TIP]
>
>만료 날짜는 짧은 시간 동안만 Marketo 액세스 권한이 필요한 단기 외부 이해 관계자 또는 컨설턴트에게 적합합니다.

>[!NOTE]
>
>만료 날짜가 되면 사용자는 만료 알림을 받고 계정이 잠깁니다.

역할을 선택하고 을(를) 클릭합니다 **다음**. 표준 사용자는 관리를 제외한 모든 영역에 액세스할 수 있습니다.

![](assets/image2016-5-24-10-3a14-3a51.png)

>[!NOTE]
>
>5개의 기본 제공 역할 외에도 사용자 지정 역할을 만들 수도 있습니다. 추가 정보 [사용자 역할 및 권한 관리](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target=&quot;_blank&quot;}.

언제든지 초대 텍스트를 수정할 수 있습니다. 클릭 **보내기**.

![](assets/image2016-5-24-10-3a15-3a52.png)

이제 새 사용자가 사용자 탭에 나열되며, 암호 및 로그인을 만들 수 있는 링크가 있는 이메일을 받게 됩니다. 다음 단계!

![](assets/image2016-5-24-10-3a23-3a10.png)

## 승인된 지원 연락처 설정 {#set-up-your-authorized-support-contacts}

Marketo 지원에서 귀사에 대한 Marketo 고객 지원 관리자임을 알리는 이메일을 수신했을 수 있습니다. 그럴 경우 **공인 지원 담당자** 팀용. 승인된 지원 담당자만 [Marketo 지원 포털](https://support.marketo.com){target=&quot;_blank&quot;}.

>[!NOTE]
>
>만들 수 있는 지원 연락처 수는 구입한 패키지에 의해 결정됩니다. 이 제한은 Marketo 지원 이메일에 지정됩니다.

승인된 지원 연락처 문서가 Marketo 커뮤니티로 이동되었습니다. 자세한 내용은 [이 문서](https://nation.marketo.com/t5/Knowledgebase/Managing-Authorized-Support-Contacts/ta-p/254341){target=&quot;_blank&quot;}.

>[!NOTE]
>
>Marketo 커뮤니티에 로그인한 사용자만 목록에 표시됩니다. 사용자를 찾을 수 없는 경우 먼저 커뮤니티에 로그인했는지 확인하십시오.

## CNAME을 사용하여 랜딩 페이지 URL 사용자 지정 {#customize-your-landing-page-urls-with-a-cname}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계를 건너뛸 수 있습니다. 컨설턴트가 킥오프 호출 중에 IT 설정 지침 문서를 제공합니다.

>[!NOTE]
>
>**관리 권한 필요**

랜딩 페이지의 CNAME을 선택합니다. 예:

    **go**.[CompanyDomain].com
    **www2**.[CompanyDomain].com
    **lp**.[CompanyDomain].com

>[!TIP]
>
>짧게 유지하십시오! 짧은 URL은 기억하기가 더 쉽습니다. 도메인으로 &quot;go&quot;를 사용하는 것이 좋습니다.

첫 번째 부분(굵은 글꼴)은 `[LandingPageCNAME]`. 5단계에서 필요합니다.

랜딩 페이지 CNAME으로 대체할 계정 문자열을 검색하려면 관리 영역으로 이동합니다.

![](assets/admin.png)

클릭 **랜딩 페이지**.

![](assets/image2015-1-6-13-3a52-3a6.png)

랜딩 페이지 설정에서 계정 문자열 을 복사합니다.

![](assets/image2015-1-6-13-3a53-3a19.png)

이것은 `[AccountString]`. 저장. 5단계에서 IT에 제공해야 합니다.

랜딩 페이지에서 Marketo(호스팅된 위치) 대신 회사 도메인을 사용하도록 도메인 설정을 구성합니다.

## 이메일 게재 기능 확인 {#ensure-email-deliverability}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계를 건너뛸 수 있습니다. 컨설턴트가 킥오프 호출 중에 IT 설정 지침 문서를 제공합니다.

이메일이 가능한 한 많은 사람에게 전달되도록 하기 위해 수행할 수 있는 몇 가지 방법이 있습니다.

* **추적 링크 브랜딩**. Marketo의 이메일에 포함하는 링크에서 고유한 도메인(Marketo의 도메인 대신)을 사용할 CNAME을 선택할 수 있습니다. 이렇게 하면 도메인 브랜딩이 강화되고 수신자와의 신뢰 및 게재 능력이 증가합니다.
* **회사 이메일 Marketo에를 허용 목록에 추가하다 추가합니다.** 실제 사용자에게 이메일을 보내기 전에 테스트 계정에 테스트 이메일을 보내는 것이 일반적인 우수 사례입니다. Marketo 허용 목록에 추가를 통해 이러한 테스트 이메일이 스팸으로 차단되거나 플래그가 지정되지 않도록 할 수 있습니다.
* **SPF 및 DKIM을 설정합니다.** 이러한 기술은 수신자에게 Marketo 이메일이 스팸이 아니라는 것을 보장합니다. 수신자의 스팸 필터가 Marketo 이메일을 거부한 것을 방지하려면 다음 단계를 수행하십시오 [전자 메일 게재 기능을 위한 SPF 및 DKIM 설정](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md).
* **도메인에 대한 MX 레코드를 설정합니다.** MX 레코드를 사용하면 회신과 자동 응답자를 처리하기 위해 이메일을 보내는 도메인으로 메일을 받을 수 있습니다. 회사 도메인에서 보내는 경우 이미 이 구성이 되었을 수 있습니다. 그렇지 않은 경우 일반적으로 회사 도메인의 MX 레코드에 매핑하도록 설정할 수 있습니다.
* **보낸 사람 주소에 대한 권장 설정.** 모든 이메일 캠페인의 보낸 사람 주소에서 유효하고 기존 및 작동하는 이메일 도메인을 사용해야 합니다. 회사 도메인에서 보내는 것보다 회사 도메인의 하위 도메인을 구성하는 것이 유용할 수 있습니다. 이렇게 하면 회사 메일스트림 문제가 Marketo 메일스트림에 영향을 주지 않고 그 반대의 경우도 마찬가지입니다. 또한 `something@nonexistentdomain.com` 은(는) 이메일을 필터링하거나 차단합니다. 보낸 사람의 보낸 사람 주소에 사용된 모든 도메인에 올바른 작업 postmaster@ 및 acabuse@ 계정이 있어야 합니다.

Google 앱을 사용하여 회사 전자 메일을 호스팅하는 경우 도메인 아래에 남용@ 또는 postmaster@ 전자 메일을 만들 수 없습니다. 이 문제를 해결하려면 &quot;남용&quot;과 &quot;postmaster&quot;라는 그룹을 만들어야 합니다. 이러한 그룹의 구성원인 사용자는 해당 주소(예: postmaster@domain.com)으로 보내진 이메일을 받게 됩니다. 그룹 생성에 대한 자세한 지침은 [여기](https://support.google.com/a/answer/33343#adminconsole){target=&quot;_blank&quot;}.

이메일 추적 링크의 CNAME을 선택합니다(CNAME을 선택 _different_ 랜딩 페이지 CNAME에서(3단계에서 선택한). 예:

* 이동2.[CompanyDomain].com
* em.[CompanyDomain].com
* 와.[CompanyDomain].com

첫 번째 부분은 이메일 추적 CNAME입니다. `[EmailTrackingCNAME]`. 5단계에서 IT에 제공해야 합니다.

>[!CAUTION]
>
>이메일 및 랜딩 페이지 CNAME은 달라야 합니다. 또한 &#39;track&#39; 또는 &#39;link&#39;와 같은 CNAME을 사용하지 마십시오. 스팸으로 플래그가 지정되는 경우가 많습니다

Marketo 추적 링크를 찾으려면 **관리** 영역.

![](assets/admin.png)

클릭 **이메일**.

![](assets/image2015-1-6-13-3a55-3a32.png)

이메일 설정에서 추적 링크를 복사합니다.

추적 링크는 다음과 같습니다. `mkto-[a-z][4 digits].com`.

![](assets/email-tracking-link-hand.jpg)

이건 네 거야 `[MktoTrackingLink]`. 저장. 5단계에서 IT에 제공해야 합니다.

&quot;보낸 사람&quot; 도메인을 수집합니다. 모든 &quot;보낸 사람&quot; 도메인 목록 만들기(예: `[Sender]@[FromDomain].com`) Marketo에서 이메일을 전송하는 데 사용할 계획입니다. 대부분의 경우 하나만 있습니다.

예를 들어 &#39;marketo.com,&#39; &#39;info.marketo.com,&#39;입니다. 이것들은 `[FromDomain1]`,`[FromDomain2]`등 저들을 저장하십시오. 5단계에서 IT에 제공해야 합니다.

이제 요청을 IT에 전송하는 데 필요한 모든 정보가 있습니다.

## IT에 프로토콜 구성 요청 {#ask-it-to-configure-protocols}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계를 건너뛸 수 있습니다. 컨설턴트가 킥오프 호출 중에 IT 설정 지침 문서를 제공합니다.

필요한 정보를 모두 수집하면 IT에 요청을 보낼 수 있습니다. 아래 텍스트를 템플릿으로 사용하여 굵은 텍스트를 사용자의 정보로 바꿀 수 있습니다.

[이 문서에 대한 링크 포함](/help/marketo/getting-started/setup-steps/configure-protocols-for-marketo.md).

이 텍스트를 전자 메일에 붙여넣고 굵게 표시된 자리 표시자를 바꿉니다.

>[!NOTE]
>
>자리 표시자를 바꿀 텍스트를 결정하려면 위의 3단계 및 4단계를 참조하십시오. 기억해 `[LandingPageCNAME]` 및 `[EmailTrackingCNAME]` 달라야 합니다.

`---------------------------------------------`

뛰어난 IT 관리자에게,

마케팅 팀은 이제 Marketo 플랫폼을 사용하여 사람들과 커뮤니케이션합니다. 우수한 이메일 게재 기능을 확보하려면 다음 사항을 변경해야 합니다.

`1)` 랜딩 페이지의 경우, **[LandingPageCNAME]**.**[CompanyDomain]**.com, **[AccountString]**.mktoweb.com

`2)` 전자 메일의 추적 링크에 대해 CNAME(DNS 항목)을 추가합니다. **[EmailTrackingCNAME]**.**[CompanyDomain]**.com, **[MktoTrackingLink]**.

`3)` Marketo허용 목록에 추가하다.

    * 이메일에서 IP 주소를 사용하는 허용 목록에 추가하다 경우 아래에 나열된 IP를 추가합니다.
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
>사용자 환경에 맞는 단축된 IP 목록을 원하는 허용 목록에 추가하다 경우 Marketo 지원 센터에 문의하십시오.

    * 스팸 방지 시스템에서 보낸 사람 도메인을 사용하는 경우 다음을 추가합니다.

**`[FromDomain1]`**
**`[FromDomain2]`**

`4)` Marketo이 Adobe를 대신하여 서명된 전자 메일을 보낼 수 있도록 SPF와 DKIM을 설정해야 합니다.

`a.` SPF를 설정하려면 DNS 항목에 다음 줄을 추가하십시오.

TXT에서 **[도메인에서]**: v=spf1 mx ip4:**[기업 IP]**
<br/>포함: mktomail.com ~all

DNS 항목에 이미 기존 SPF 레코드가 있는 경우 다음을 추가하기만 하면 됩니다.

include:mktomail.com

`[`바꾸기 **도메인에서** 도메인의 이메일 사용(예: company.com) 및 **CorpIP** 회사 이메일 서버의 IP 주소 사용(예: (255.255.255.255).  여러 도메인에서 Marketo을 통해 이메일을 보내려면 IT 직원이 각 도메인에 대해 이 줄을 추가(한 줄에서)해야 합니다.`]`

`b.` DKIM의 경우 설정하려는 각 도메인에 대한 DNS 리소스 레코드를 만드십시오. 다음은 Adobe가 서명할 각 도메인에 대한 호스트 레코드 및 TXT 값입니다.

**`[DKIMDomain1]`**: 호스트 레코드: **`[HostRecord1]`** 및 TXT 값 **[TXTValue1]**.

**`[DKIMDomain2]`**: 호스트 레코드: **`[HostRecord2]`** 및 TXT 값 **`[TXTValue2]`**.

`[`를 복사합니다. **호스트 레코드** 및 **TXTValue** 각 **DKIMDomain** 다음 절차를 수행한 후 [지침](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md). 에서 각 도메인을 확인하는 것을 잊지 마십시오 **관리자 > 이메일 > DKIM** IT 직원이 이 단계를 완료하면`]`

`5)` FROM 도메인에 유효한 MX 레코드가 있는지 확인해야 합니다 **[FromDomain1]**, **[FromDomain2]**&#x200B;등 확인해주시겠어요? 없는 경우 회사 도메인 MX 레코드에 매핑하도록 을 구성하십시오. 이렇게 하면 Marketo 메일링에 대한 회신/자동응답기를 처리할 수 있습니다.

Marketo으로 설정 프로세스를 완료할 수 있도록 이러한 단계를 완료하면 알려주십시오.

감사합니다! 넌 최고야!

사랑

**`[Your Name]`**

`---------------------------------------------`

IT로 이메일을 전송합니다. IT 부서에서 이러한 작업을 완료하는 데 시간이 걸릴 수 있습니다. 7단계로 계속할 수 있지만, Marketo 설정을 완료하려면 6단계를 반환해야 합니다.

## IT 완료 후 Marketo 설정 완료 {#complete-your-marketo-setup-after-it-finishes}

IT 부서에서 작업을 완료하면, 다음 단계에 따라 랜딩 페이지 및 이메일 CNAME을 추가하고, DKIM 서명을 활성화합니다.

로 이동합니다. **관리** 랜딩 페이지 CNAME 추가 영역

![](assets/admin.png)

랜딩 페이지 를 선택하고 을(를) 클릭합니다 **편집** 설정 영역에 있습니다.

![](assets/image2015-1-6-13-3a59-3a15.png)

랜딩 페이지의 도메인 이름 필드에 새 도메인 이름을 입력합니다. 다음 형식이어야 합니다.

`[LandingPageCNAME].[CompanyDomain].com`

![](assets/image2015-1-6-14-3a3-3a6.png)

대체 페이지 필드에서 랜딩 페이지를 사용할 수 없는 경우 사람들이 이동할 URL을 입력합니다. 대체 페이지가 없는 경우 회사 홈 페이지를 사용할 수 있습니다. 홈 페이지 필드에 회사 웹 사이트를 입력합니다.

![](assets/image2015-1-6-14-3a2-3a46.png)

관리 영역에서 이메일 CNAME 추가 를 선택합니다

![](assets/image2015-1-6-14-3a5-3a3.png)

아래로 스크롤하여 클릭 **편집**.

![](assets/edit-branding-domain.png)

도메인 필드에 전자 메일 추적 도메인을 입력합니다. 다음 형식이어야 합니다.

`[EmailTrackingCNAME].[CompanyDomain].com`. 클릭 **저장**.

![](assets/new-branding-domain-9-1.png)

## CRM 통합 {#integrate-your-crm}

이 단계는 가장 흥미로운 단계일 수 있습니다. CRM에 저장한 모든 리드 및 연락처로 Marketo을 채울 때가 되었습니다.

회사에서 사용하는 CRM에 따라 다음 중에서 선택합니다.

    * [Salesforce.com과 Marketo 통합](/help/marketo/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.md)
    * [Marketo과 Microsoft Dynamics 통합](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md)

>[!NOTE]
>
>이 단계를 완료하려면 회사의 CRM 관리자가 도움이 필요합니다.

## 웹 사이트에 추적 코드 추가 {#add-tracking-code-to-your-website}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계를 건너뛸 수 있습니다. 컨설턴트는 IT 설정 지침 문서에 Munchkin 코드 지침을 제공합니다.

Marketo에는 모든 웹 페이지에서 개인 활동을 추적하는 데 사용할 수 있는 사용자 지정 추적 JavaScript(Munchkin이라고 함)가 있습니다. Munchkin은 웹 사이트를 Marketo에 통합하기 위해 필요합니다. 다음 단계에 따라 다음을 수행합니다 [웹 사이트에 Munchkin 추적 코드 추가](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target=&quot;_blank&quot;}.

>[!NOTE]
>
>추적 코드를 추가하는 데 필요한 HTML 경험.

모든 설정 단계가 끝났습니다. 남은 것은 Marketo을 사용해 다이빙하는 것입니다!
