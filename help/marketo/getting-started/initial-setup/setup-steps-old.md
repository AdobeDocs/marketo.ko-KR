---
unique-page-id: 2949469
description: 설정 단계 - Marketo 설명서 - 제품 설명서
title: 설정 단계
hide: true
hidefromtoc: true
exl-id: ef6b7311-55ca-4384-a24c-714eae89a57d
feature: Getting Started
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '2052'
ht-degree: 1%

---

# 설정 단계 {#setup-steps}

**Adobe Marketo Engage 시작!**

Marketo 사용에 앞서 몇 가지 단계를 완료해야 합니다.

이러한 단계는 다음과 같습니다.

* 일부 기본 계정 설정
* 랜딩 페이지 URL 및 이메일 링크를 브랜딩하여 신뢰 및 전달성을 개선합니다.
* CRM 동기화 중
* 회사 웹 사이트에 추적 코드 추가

>[!NOTE]
>
>회사가 **Marketo을 처음 사용하는 경우**&#x200B;에만 이 단계를 수행하면 됩니다. 그렇지 않은 경우 설정이 이미 수행되었을 수 있습니다.

일부 단계는 IT 팀의 도움이 필요합니다.

>[!TIP]
>
>[이 체크리스트를 인쇄](/help/marketo/getting-started/initial-setup/setup-checklist.md){target="_blank"}하면 항목을 완료하면서 확인할 수 있습니다.

## 로그인 및 추가 Marketo 사용자 만들기 {#log-in-and-create-additional-marketo-users}

>[!IMPORTANT]
>
>Marketo 구독이 2023년 7월 31일 이후에 만들어졌거나 이미 [Adobe Identity Management](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md){target="_blank"}(으)로 마이그레이션된 경우 아래 설명된 사용자 추가 단계는 적용되지 않습니다. 대신 [이 문서](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md){target="_blank"}을(를) 참조하십시오.

전자 메일로 받은 자격 증명을 사용하여 Marketo [여기](https://app.marketo.com/){target="_blank"}에 로그인합니다.

![](assets/setup-steps-1.png)

축하합니다! 현재 Marketo에 있으며 탐색을 시작할 수 있습니다. 마케팅 팀의 동료를 초대하여 함께 참여하도록 할 수 있습니다. 새 사용자를 추가하여 이 작업을 수행할 수 있습니다.

**[!UICONTROL Admin]** 영역으로 이동합니다.

>[!TIP]
>
>**[!UICONTROL My Account]**&#x200B;을(를) 클릭하여 계정 및 위치 설정을 변경하고 새 구독 이름을 설정할 수 있습니다.

![](assets/setup-steps-2.png)

>[!NOTE]
>
>**관리자 권한 필요**

**[!UICONTROL Users & Roles]**&#x200B;을(를) 클릭합니다.

![](assets/setup-steps-3.png)

**[!UICONTROL Invite New User]**&#x200B;을(를) 클릭합니다.

![](assets/setup-steps-4.png)

동료의 이메일 주소, 이름, 성을 입력합니다. _액세스 만료 날짜 설정은 선택 사항입니다_. **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

![](assets/setup-steps-5.png)

>[!TIP]
>
>만료 날짜는 짧은 기간 동안 Marketo 액세스만 필요한 단기 외부 관련자 또는 컨설턴트에게 적합합니다.

>[!NOTE]
>
>만료 날짜가 되면 사용자가 만료 알림을 받고 계정이 잠깁니다.

역할을 선택하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다. 표준 사용자는 관리자를 제외한 모든 영역에 액세스할 수 있습니다.

![](assets/setup-steps-6.png)

>[!NOTE]
>
>5개의 기본 역할 외에도 사용자 정의 역할을 만들 수도 있습니다. [사용자 역할 및 권한 관리](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"}에 대해 자세히 알아보세요.

언제든지 초대 텍스트를 조정할 수 있습니다. **보내기**&#x200B;를 클릭합니다.

![](assets/setup-steps-7.png)

이제 새 사용자가 **[!UICONTROL Users]** 탭에 나열되므로 암호 및 로그인을 만드는 링크가 포함된 이메일을 받게 됩니다. 다음 단계!

![](assets/setup-steps-8.png)

## 공인 지원 담당자 설정 {#set-up-your-authorized-support-contacts}

Marketo 지원에서 귀하를 회사의 Marketo 고객 지원 관리자임을 알리는 이메일을 수신했을 수 있습니다. 이 경우 팀에 대해 **승인된 지원 연락처**&#x200B;를 설정할 수 있습니다. 승인된 지원 담당자만 [Marketo 지원 포털](https://support.marketo.com){target="_blank"}을 통해 Marketo 고객 지원 센터에 직접 문의할 수 있습니다.

>[!NOTE]
>
>만들 수 있는 지원 연락처 수는 구입한 패키지에 따라 결정됩니다. 이 제한은 Marketo 지원 이메일에 명시되어 있습니다.

승인된 지원 담당자 문서가 Marketo 커뮤니티로 이동되었습니다. [이 문서](https://nation.marketo.com/t5/Knowledgebase/Managing-Authorized-Support-Contacts/ta-p/254341){target="_blank"}을(를) 참조하십시오.

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

    * **이동**.[CompanyDomain].com
    * **www2**.[CompanyDomain].com
    * **lp**.[CompanyDomain].com

>[!TIP]
>
>짧게 유지하십시오! 짧은 URL을 기억하기가 더 쉽습니다. 도메인으로 &quot;go&quot;를 제안합니다.

첫 번째 부분(굵은 글꼴)은 `[LandingPageCNAME]`입니다. 5단계에서 필요합니다.

랜딩 페이지 CNAME으로 바꿀 Munchkin ID를 검색하려면 관리 영역으로 이동합니다.

![](assets/setup-steps-9.png)

**내 계정**&#x200B;을 클릭합니다.

![](assets/setup-steps-10.png)

랜딩 페이지 설정에서 [!UICONTROL Account String]을(를) 복사합니다.

![](assets/setup-steps-11.png)

`[Munchkin ID]`입니다. 저장합니다. 5단계에서 IT에 제공해야 합니다.

랜딩 페이지에서 Marketo(호스팅된 위치) 대신 회사 도메인을 사용하도록 도메인 설정을 구성합니다.

## 이메일 전달성 확인 {#ensure-email-deliverability}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계는 건너뛸 수 있습니다. 컨설턴트는 킥오프 통화 중 IT 설치 지침 문서를 제공합니다.

이메일이 가능한 한 많은 사람에게 도달하도록 하기 위해 취할 수 있는 몇 가지 조치가 있습니다.

* **추적 링크 브랜딩**. Marketo의 이메일에 포함된 링크에서 자체 도메인(Marketo 대신)을 사용하도록 CNAME을 선택할 수 있습니다. 이렇게 하면 도메인 브랜딩이 강화되고 수신자와의 신뢰와 전달성이 높아집니다.
* **회사 전자 메일에 Marketo허용 목록에 추가하다 를 추가합니다.** 실제 사용자에게 전자 메일을 보내기 전에 테스트 계정으로 테스트 전자 메일을 보내는 것이 일반적인 모범 사례입니다. Marketo 허용 목록에 추가를 사용하면 이러한 테스트 이메일이 차단되거나 스팸으로 플래그가 지정되는 것을 방지할 수 있습니다.
* **SPF와 DKIM을 설정합니다.** 이러한 기술은 수신자에게 Marketo 이메일이 스팸이 아님을 보장합니다. 수신자의 스팸 필터가 Marketo 이메일을 거부하지 않도록 하려면 다음 단계에 따라 [이메일 전달성을 위해 SPF 및 DKIM을 설정](/help/marketo/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.md)하십시오.
* **도메인의 MX 레코드를 설정합니다.** MX 레코드를 사용하면 답글 및 자동 응답자를 처리하기 위해 전자 메일을 보내는 도메인으로 메일을 받을 수 있습니다. 회사 도메인에서 보내는 경우 이미 이 구성이 되어 있을 수 있습니다. 그렇지 않은 경우 일반적으로 회사 도메인의 MX 레코드에 매핑하도록 설정할 수 있습니다.
* **보낸 사람 주소에 대한 권장 설정입니다.** 모든 이메일 캠페인의 보낸 사람 주소에 유효하고 기존 및 작업 중인 이메일 도메인을 사용해야 합니다. 회사 도메인에서 전송하는 것보다 회사 도메인의 하위 도메인을 구성하는 것이 유용할 수 있습니다. 이렇게 하면 회사 메일 스트림의 문제가 Marketo 메일 스트림에 영향을 주지 않고 그 반대의 경우도 마찬가지입니다. 또한 `something@nonexistentdomain.com`에서 메일을 보내면 전자 메일이 필터링되거나 차단됩니다. 보낸 사람의 보낸 사람 주소에 사용되는 모든 도메인에는 유효하고 작동하는 postmaster@ 및 abuse@ 계정이 있어야 합니다.

Google 앱을 사용하여 회사 전자 메일을 호스팅하는 경우 도메인 아래에 abuse@ 또는 postmaster@ 전자 메일을 만들 수 없습니다. 이 문제를 해결하려면 &quot;abuse&quot; 및 &quot;postmaster&quot;라는 그룹을 만들어야 합니다. 이러한 그룹의 구성원인 사용자는 해당 주소(예: postmaster@domain.com)로 전송된 이메일을 받게 됩니다. 그룹 만들기에 대한 자세한 지침은 [여기](https://support.google.com/a/answer/33343#adminconsole){target="_blank"}에서 확인할 수 있습니다.

전자 메일 추적 링크의 CNAME을 선택하십시오(3단계에서 선택한 랜딩 페이지 CNAME에서 _다름_ 중 하나를 선택하십시오). 몇 가지 예:

* go2.[CompanyDomain].com
* em.[CompanyDomain].com
* 와.[CompanyDomain].com

첫 번째 부분은 전자 메일 추적 CNAME, `[EmailTrackingCNAME]`입니다. 5단계에서 IT에 제공해야 합니다.

>[!CAUTION]
>
>이메일 및 랜딩 페이지 CNAME은 달라야 합니다. 또한 &#39;track&#39; 또는 &#39;link&#39;와 같은 CNAME은 사용하지 마십시오. 종종 스팸으로 플래그가 지정됩니다

Marketo 추적 링크를 찾으려면 **[!UICONTROL Admin]** 영역으로 이동하십시오.

![](assets/setup-steps-12.png)

**[!UICONTROL Email]**&#x200B;을(를) 클릭합니다.

![](assets/setup-steps-13.png)

전자 메일 설정에서 [!UICONTROL Tracking Link]을(를) 복사합니다.

[!UICONTROL Tracking Link]은(는) `mkto-[a-z][4 digits].com` 형식입니다.

![](assets/setup-steps-14.png)

내 `[MktoTrackingLink]`입니다. 저장합니다. 5단계에서 IT에 제공해야 합니다.

&quot;From&quot; 도메인을 수집합니다. Marketo에서 전자 메일을 보내는 데 사용할 모든 &quot;보낸 사람&quot; 도메인(예: `[Sender]@[FromDomain].com`)의 목록을 만듭니다. 대부분의 경우 하나만 있습니다.

예: &#39;marketo.com,&#39; &#39;info.marketo.com,&#39;. `[FromDomain1]`,`[FromDomain2]` 등입니다. 그들을 구해 5단계에서 IT에 제공해야 합니다.

이제 요청을 IT에 보내는 데 필요한 모든 정보가 준비되었습니다!

## IT에 프로토콜 구성 요청 {#ask-it-to-configure-protocols}

>[!NOTE]
>
>Launch Pack 고객입니까? 이 단계는 건너뛸 수 있습니다. 컨설턴트는 킥오프 통화 중 IT 설치 지침 문서를 제공합니다.

필요한 모든 정보를 수집했으면 IT에 요청을 보낼 준비가 된 것입니다. 아래 텍스트를 템플릿으로 사용하여 굵은 텍스트를 고유한 정보로 바꿀 수 있습니다.

[이 문서에 대한 링크를 포함합니다](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md).

이 텍스트를 전자 메일에 붙여넣고 굵은 자리 표시자를 바꿉니다.

>[!NOTE]
>
>자리 표시자를 대체할 텍스트를 결정하려면 위의 3단계와 4단계를 참조하십시오. `[LandingPageCNAME]`과(와) `[EmailTrackingCNAME]`은(는) 달라야 합니다.

`----------------------------------------------`

뛰어난 IT 관리자,

이제 마케팅 팀은 Marketo 플랫폼을 사용하여 사용자와 커뮤니케이션합니다. 우수한 이메일 전달성을 보장하려면 다음 사항을 변경해야 합니다.

`1)` 랜딩 페이지의 경우 **[LandingPageCNAME]**&#x200B;에 대한 DNS 항목(CNAME)을 추가하십시오.**[CompanyDomain]**.com, **[Munchkin ID]**.mktoweb.com을 가리킴.

`2)` 전자 메일의 추적 링크에 대해 **[EmailTrackingCNAME]**&#x200B;에 대한 DNS 항목(CNAME)을 추가하십시오.**[MktoTrackingLink]**&#x200B;을(를) 가리키는 **[CompanyDomain]**.com.

허용 목록에 추가하다 `3)` Marketo.

    * 전자 메일 허용 목록에 IP 주소를 사용하는 경우 아래 나열된 IP를 추가하십시오.

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

    * 스팸 방지 시스템에서 From 도메인을 사용하는 경우 다음 항목을 추가합니다.

**`[FromDomain1]`**
**`[FromDomain2]`**

`4)` Marketo에서 대신 서명된 전자 메일을 보낼 수 있도록 SPF와 DKIM을 설정해야 합니다.

`a.` SPF를 설정하려면 DNS 항목에 다음 줄을 추가하십시오.

TXT **[도메인에서]**: v=spf1 mx ip4:**[회사 IP]**
<br/>포함: mktomail.com ~all

DNS 항목에 기존 SPF 레코드가 이미 있는 경우 다음을 추가하기만 하면 됩니다.

include:mktomail.com

`[`도메인에서 **바꾸기**&#x200B;를 도메인에서 보낸 전자 메일로 바꾸고(예: company.com) **CorpIP**&#x200B;을(를) 회사 전자 메일 서버의 IP 주소로 바꿉니다(예: 255.255.255.255).  Marketo을 통해 여러 도메인에서 전자 메일을 전송하려면 IT 직원이 각 도메인에 대해 한 줄에 이 줄을 추가하도록 해야 합니다.`]`

`b.` DKIM의 경우 설정하려는 각 도메인에 대해 DNS 리소스 레코드를 만드십시오. 다음은 서명할 각 도메인의 호스트 레코드 및 TXT 값입니다.

**`[DKIMDomain1]`**: 호스트 레코드는 **`[HostRecord1]`**&#x200B;이고 TXT 값은 **[TXTVvalue1]**&#x200B;입니다.

**`[DKIMDomain2]`**: 호스트 레코드는 **`[HostRecord2]`**&#x200B;이고 TXT 값은 **`[TXTValue2]`**&#x200B;입니다.

`[`여기에 있는 **지침**&#x200B;에 따라 설정한 각 **DKIMDomain**&#x200B;에 대해 **HostRecord** 및 [TXTValue](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md)를 복사합니다. IT 직원이 이 단계를 완료한 후 **관리자 > 전자 메일 > DKIM**&#x200B;에서 각 도메인을 확인하는 것을 잊지 마십시오.`]`

`5)` FROM 도메인 **[FromDomain1]**, **[FromDomain2]** 등에 대해 올바른 MX 레코드가 있는지 확인해야 합니다. 확인해줄 수 있나요? 그렇지 않은 경우 회사 도메인 MX 레코드에 매핑되도록 를 구성하십시오. 이렇게 하면 Marketo 우편물에 대한 회신/자동 응답자를 처리할 수 있습니다.

Marketo으로 설정 프로세스를 완료할 수 있도록 이 단계를 완료하면 알려주십시오.

감사합니다. 네가 최고야!

사랑,

**`[Your Name]`**

`----------------------------------------------`

IT로 이메일을 전송합니다. IT에서 이러한 작업을 완료하는 데 시간이 다소 걸릴 수 있습니다. 7단계로 계속 진행할 수 있지만, Marketo 설정을 완료하려면 6단계를 반환해야 합니다.

## IT가 완료되면 Marketo 설정 완료 {#complete-your-marketo-setup-after-it-finishes}

IT 담당자가 작업을 완료하면 다음 단계에 따라 랜딩 페이지 및 이메일 CNAME를 추가하고 DKIM 서명을 활성화합니다.

**[!UICONTROL Admin]** 영역으로 이동하여 랜딩 페이지 CNAME 추가

![](assets/setup-steps-15.png)

랜딩 페이지를 선택하고 **[!UICONTROL Edit]** 영역에서 [!UICONTROL Settings]을(를) 클릭합니다.

![](assets/setup-steps-16.png)

**[!UICONTROL Domain Name for Landing Pages]** 필드에 새 도메인 이름을 입력합니다. 형식은 다음과 같아야 합니다.

`[LandingPageCNAME].[CompanyDomain].com`

![](assets/setup-steps-17.png)

랜딩 페이지를 사용할 수 없는 경우 **[!UICONTROL Fallback]** 페이지 필드에 사람들이 이동할 URL을 입력합니다. 대체 페이지가 없는 경우 회사 홈 페이지를 사용할 수 있습니다. **[!UICONTROL Homepage]** 필드에 회사 웹 사이트를 입력합니다.

![](assets/setup-steps-18.png)

[!UICONTROL Admin] 영역에서 **[!UICONTROL Email]**&#x200B;을(를) 선택하여 전자 메일 CNAME을 추가합니다.

![](assets/setup-steps-19.png)

[!UICONTROL Branding Domains]&#x200B;(으)로 스크롤합니다. 도메인을 선택하고 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

![](assets/setup-steps-20.png)

도메인 필드에 이메일 추적 도메인을 입력합니다. 형식은 다음과 같아야 합니다.

`[EmailTrackingCNAME].[CompanyDomain].com` 질문에 답합니다. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

![](assets/setup-steps-21.png)

## CRM 통합 {#integrate-your-crm}

이는 설정에서 가장 흥미로운 단계일 수 있습니다. CRM에 저장된 모든 리드 및 연락처로 Marketo을 채워야 할 때입니다.

회사에서 사용하는 CRM에 따라 다음 중에서 선택하십시오.

    * [Marketo과 통합] [[!DNL Salesforce.com]](/help/marketo/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.md)
    * [Marketo과 통합] [[!DNL Microsoft Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/understanding-the-microsoft-dynamics-sync.md)

>[!NOTE]
>
>이러한 단계를 완료하려면 회사의 CRM 관리자의 도움이 필요합니다.

## 웹 사이트에 추적 코드 추가 {#add-tracking-code-to-your-website}

>[!NOTE]
>
>[!DNL Launch Pack] 고객입니까? 이 단계는 건너뛸 수 있습니다. 컨설턴트가 IT 설정 지침 문서에 [!DNL Munchkin] 코드 지침을 제공합니다.

Marketo에는 웹 페이지에서 개인 활동을 추적하는 데 사용할 수 있는 사용자 지정 추적 JavaScript([!DNL Munchkin])가 있습니다. [!DNL Munchkin]은(는) 웹 사이트를 Marketo에 통합하는 데 필요합니다. 다음 단계에 따라 [웹 사이트에 추적 코드를 추가 [!DNL Munchkin] 합니다](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}.

>[!NOTE]
>
>추적 코드를 추가하려면 HTML 경험이 필요합니다.

## 성능 기대치 {#performance-expectations}

Marketo의 성능 측면에서 기대할 수 있는 사항은 무엇입니까? 마케팅 캠페인의 크기와 복잡성에 따라 달라질 수 있습니다. 그러나 [Marketo Engage 제품 설명](https://helpx.adobe.com/kr/legal/product-descriptions/adobe-marketo-engage---product-description.html){target="_blank"}에 있는 여러 표의 &quot;표준&quot; 열에 요약된 내용과 동등한 성능 수준을 기대할 수 있습니다. &quot;성능&quot; 및 &quot;성능 플러스&quot; 열은 [더 높은 성능 수준](https://nation.marketo.com/t5/product-documents/marketo-engage-performance-tiers/ta-p/328835){target="_blank"}을 제공하는 성능 계층 패키지를 나타냅니다.

모든 설정 단계가 끝났습니다. 이제 Marketo에 다이빙해서 사용하는 일만 남았습니다!
