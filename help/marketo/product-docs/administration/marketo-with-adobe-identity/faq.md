---
description: Adobe Identity Management FAQ - Marketo 문서 - 제품 설명서
title: ADOBE IDENTITY MANAGEMENT FAQ
feature: Marketo with Adobe Identity
exl-id: 2401def7-1696-4d77-a8a3-96c490517121
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '1645'
ht-degree: 0%

---

# ADOBE IDENTITY MANAGEMENT FAQ {#adobe-identity-management-faq}

**Adobe ID란?**

Adobe Identity Management System은 세 가지 구성 요소로 구성됩니다.

* [!DNL Adobe Identity Service]: 페더레이션 및 런타임 SSO(Single Sign-On)를 포함하여 최종 사용자의 인증 및 유효성 검사를 처리합니다.

* Adobe Admin Console: Admin Console은 전체 조직에서 Adobe 권한을 관리할 수 있는 중앙 위치를 제공합니다. 사용자 관리, 클라우드 서비스, 데스크톱 라이선스 자격, 페더레이션 구성을 처리하고 데이터 손실 방지 보안 기능을 제공합니다.

* Adobe UMAPI(사용자 관리 API): 조직은 API 수준에서 Adobe Admin Console의 기업 사용자 및 권한을 관리할 수 있습니다.

**기존 Marketo Engage 구독은 언제 IMS와 통합됩니까?**

기존 Marketo Engage 구독은 현재 갱신, 재계약 이벤트 및/또는 추가 사항이 포함된 모든 판매 이벤트 시 Adobe IMS로 마이그레이션되고 있습니다. 영업 이벤트 이외 마이그레이션은 2024년 10월부터 지원됩니다.

**마이그레이션 후에도 Marketo Engage URL은 그대로 유지됩니까?**

아니요. URL은 마이그레이션 후 다음과 같은 형식으로 표시됩니다. `https://experience.adobe.com/#/@tenantID/so:XXX-XXX-XXX/marketo-engage/classic/`(XXX는 Munchkin ID를 나타내고 @tenantID은 Adobe 조직에서 가져옴).

**URL 변경을 준비하기 위해 수행해야 할 작업이 있습니까?**

예. 마이그레이션 후 Marketo Engage은 experience.adobe.com에서 Adobe Experience Cloud으로 제공됩니다. Marketo Engage 액세스가 중단되지 않도록 IT 팀과 함께 이 문서 상단의 [에 나열된 모든 Adobe 도메인을 허용 목록](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md){target="_blank"}해야 합니다.

engage-xx.marketo.com 도메인 _will_&#x200B;의 Marketo Engage 자산에 대한 이전 링크와 책갈피가 계속 작동합니다. 그러나 먼저 탐색 중인 URL의 Marketo Engage 인스턴스에 로그인해야 합니다. 예를 들어 Munchkin ID 123-ABC-456이 있는 인스턴스에서 스마트 캠페인에 대한 책갈피로 이동하려면 먼저 Munchkin ID 123-ABC-456으로 Marketo Engage 인스턴스에 로그인해야 합니다.

계획되지 않았지만 향후 개발 작업에서 이 리디렉션 기능이 중단될 수 있습니다. 예기치 않은 중단을 방지하려면 가능한 한 빨리 책갈피를 업데이트하는 것이 좋습니다.

**SSO에서 작동합니까?**

예. Adobe IMS와의 통합은 범용 ID 사용자 및 SSO를 지원합니다. SSO는 이제 Adobe IMS에 의해 구동되며 Adobe Admin Console의 조직 수준에서 설정됩니다. 그러나 Marketo Engage IdP 시작 지원은 Adobe의 SP 시작 지원과 비교하여 다릅니다([자세히 알아보기](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}). Admin Console으로 마이그레이션한 후 SSO 차이점에 대한 도움이 필요한 경우 [Adobe 고객 지원 센터](https://helpx.adobe.com/contact.html){target="_blank"}에 문의하십시오.

**Adobe 제품 관리자와 Marketo Engage 관리자의 차이점은 무엇입니까?**

* Adobe 제품 관리자는 Marketo 플랫폼의 새로운 역할입니다.
* Adobe 제품 관리자 역할은 Adobe Admin Console에서 제품 관리자로 추가된 사용자에게 부여됩니다
* Adobe 제품 관리자는 읽기 전용 역할이며 Marketo Engage에서 편집하거나 삭제할 수 없습니다.
* Adobe 제품 관리자는 표준 Marketo 관리자와 동일한 권한과 권한을 갖습니다.
* Marketo Engage 관리자의 역할은 여전히 관리자이며 Marketo Engage의 사용자에게 부여됩니다.
* Marketo 기본 관리자 역할이 있는 사용자만 Admin Console에서 Marketo 제품 관리자로 할당됩니다.

**사용자 관리 API 클라이언트 지원에 변경 사항이 있습니까?**

예. Adobe IMS에 온보딩한 사용자는 기존의 Marketo 사용자 관리 API를 모두 활용할 수 없습니다. 사용자 초대, 업데이트 및 삭제 작업의 경우 Adobe [IMS API](https://www.adobe.io/apis/experienceplatform/umapi-new.html){target="_blank"}를 사용해야 합니다. 역할 관리의 경우 Marketo 사용자 관리 API가 계속 적용됩니다. 이 외에 Marketo REST API 클라이언트 지원에 대한 다른 변경 사항은 없습니다.

**IMS와 통합되는 경우 지원을 받으려면 누구에게 연락해야 합니까?**

* 사전 사용자 마이그레이션: [Marketing Nation Community](https://nation.marketo.com/t5/support/ct-p/Support)의 파일 지원 사례 또는 이메일 `customercare@marketo.com`.

* 사후 사용자 마이그레이션: [Marketing Nation Community](https://nation.marketo.com/t5/support/ct-p/Support)의 파일 지원 사례 또는 이메일 `customercare@marketo.com`.

* 지원 후 마이그레이션 완료: 제품 지원 관리자는 Experience League 지원 포털을 통해 사례를 제출할 수 있습니다.

Ultimate Success이 있는 경우 Admin Console 마이그레이션 화이트 글러브 서비스에 액세스할 수 있습니다. 도움이 필요하면 Adobe 계정 팀(계정 관리자)에 문의하십시오.

**Adobe ID를 사용하여 다른 Adobe 애플리케이션에 액세스하는 경우 해당 ID를 사용하여 Marketo에 액세스할 수 있습니까?**

다른 Adobe 제품이 있어도 구독이 IMS로 마이그레이션되기 전까지는 Adobe ID로 Marketo에 액세스할 수 없습니다.

**Adobe Admin Console에서 Marketo 사용자 역할(작업 공간 내)을 관리합니까?**

아니요. 사용자 역할 관리(작업 공간 내)가 Marketo Engage에서 완료되었습니다.

**IMS 통합 구독의 Marketo 관리자로서 Admin Console에 액세스할 수 없습니다. 액세스 권한을 얻으려면 어떻게 해야 합니까?**

조직의 Adobe에 액세스할 수 있는 모든 Admin Console 시스템 또는 제품 관리자에게 액세스 권한을 부여할 수 있습니다. 조직의 콘솔 관리자 권한이 있는 사용자를 모를 경우 [Adobe 고객 지원 센터](https://helpx.adobe.com/contact.html){target="_blank"}에 문의하십시오.

**관리자가 Marketo [!DNL Sales Connect]에 사용자를 추가하는 방법은 무엇입니까?**

[!DNL Sales Connect]용 Admin Console에 제품 카드가 있을 예정이지만 사용자를 추가/관리하는 데 Admin Console을 사용해서는 안 됩니다. 다음 링크를 통해 관리자는 Marketo [!DNL Sales Connect]을(를) 통해 사용자를 관리할 수 있습니다. [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management){target="_blank"}.

**Adobe Admin Console에 대한 자세한 내용은 어디에서 확인할 수 있습니까?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/kr/enterprise/admin-guide.html){target="_blank"}.

**내 계정에 대한 사용자 계정을 변경하기 위해 Marketo의 관리 섹션으로 계속 이동합니까?**

아니요. [account.adobe.com](https://account.adobe.com){target="_blank"}으로 이동해야 합니다.

**Marketo의 Universal ID에서 어떻게 작동합니까?**

Adobe ID에 온보딩되는 사용자는 제품의 구독 전환기를 통해 IMS 지원 구독에 원활하게 액세스할 수 있습니다.

**SSO에서 작동합니까?**

예. Adobe IMS와 Marketo 통합은 범용 ID 사용자 및 SSO를 지원합니다. SSO는 이제 Adobe IMS에 의해 구동되며 Adobe Admin Console의 조직 수준에서 설정됩니다. [자세히 알아보기](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}.

**이미 Adobe ID에 온보딩되었으며 이제 SSO를 구현하려고 합니다. 어떻게 해야 합니까?**

SSO를 구현하지 않고 Adobe 조직에서 SSO를 구현하지 않고 구독이 Adobe ID로 온보딩되었다면 [Marketo 지원](https://nation.marketo.com/){target="_blank"}에 티켓을 제출하고 &quot;SSO를 구현하는 Admin Console의 Marketo&quot;로 주제를 지정하십시오.

**장치 권한 부여는 어떻게 작동합니까?**

Adobe IMS는 현재 Marketo의 장치 인증 기능과 같은 기능을 지원하지 않습니다.

**사용자 초대 대화 상자에서 로그인 기능을 사용하여 사용자의 전자 메일에서 사용자의 로그인을 고유하게 만들 수 있습니까?**

아니요. 구독이 IMS를 사용할 수 있는 경우 사용자 초대 워크플로가 더 이상 활성화되지 않으므로 기능이 더 이상 유효하지 않습니다. Adobe id를 사용하려면 사용자의 id가 이메일에 의해 제어되어야 합니다.

**Adobe IMS의 경우 Adobe ID, Enterprise ID 또는 Federated ID을 사용할 수 있습니까?**

예. 조직에서 지원할 ID 유형을 결정합니다. 추가 정보는 [ID 개요](https://helpx.adobe.com/kr/enterprise/using/identity.html) 및 [ID 설정](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}에서 찾을 수 있습니다.

**Adobe Admin Console에서 지원되는 제품 카드는 무엇입니까?**

지원되는 제품 카드는 Marketo Engage, Marketo Measure, Marketo Dynamic Chat, Marketo Sales Connect 및 Marketo Sales Insight Actions입니다.

**Adobe ID로 마이그레이션했을 때 사용자 로그인이 전자 메일과 일치하지 않으면 어떻게 합니까?**

이메일 주소와 다른 로그인을 사용하는 현재 Marketo Engage 사용자는 Adobe ID로 마이그레이션되면 더 이상 해당 자격 증명으로 로그인하지 않습니다. Adobe ID는 항상 사용자의 이메일 주소로 인증됩니다. [account.adobe.com](https://account.adobe.com){target="_blank"}에서 Adobe ID 전자 메일 주소를 업데이트할 수 있습니다.

**구독에서 IP 제한 설정을 사용하는 경우 Adobe ID 마이그레이션 후 어떻게 됩니까?**

구독이 Adobe ID에 온보딩될 때 IP 제한 설정은 Adobe Admin Console으로 마이그레이션되지 않습니다. Marketo의 IP 제한 설정에는 특정 IP 주소에서의 액세스만 허용하고 특정 IP 주소의 액세스를 차단하는 것이 포함됩니다. 현재 Adobe Identity Management System에서는 IP 제한 기능을 지원하지 않습니다.

2025년 중반에 Adobe Identity Management System에서는 특정 IP 주소만 허용하는 기능이 출시되어 현재 이 기능을 사용하는 Marketo 사용자의 전환을 지원합니다. 현재 이 기능을 사용하는 사용자는 기능이 릴리스될 때까지 사용자 마이그레이션을 수행하지 않습니다. 기능이 전달되면 마이그레이션이 예약된다는 알림이 사용자에게 표시됩니다. 사용 가능한 경우 기능에 대한 자세한 정보가 제공됩니다.

현재 IP 제한을 사용하는 사용자는 특정 주소의 액세스를 차단하며, Adobe Identity Management 시스템에서 지원하지 않으므로 Adobe ID로 마이그레이션한 후 이 기능을 더 이상 사용할 수 없습니다.

**&#39;단일 사인온 우회&#39; 옵션이 있는 역할을 가진 사용자가 있는 경우, Adobe ID 마이그레이션 후 어떻게 됩니까?**

Adobe Admin Console에는 기본 Business ID 디렉터리가 제공됩니다. Adobe 조직의 Federated ID 디렉터리에 있는 도메인 외부의 사용자는 Adobe ID ID 유형으로 이 디렉터리에 할당됩니다. 이러한 사용자는 SSO(Single Sign-On)를 거치지 않고 Marketo Engage에 액세스할 수 있으며 라이선스 소유권은 개인이 아닌 회사에 유지됩니다.

**구독이 두 개 이상 있지만 모든 구독에서 Single Sign-On을 사용할 수 있는 것은 아닙니다. Adobe ID 마이그레이션 후 어떻게 됩니까?**

구독이 Adobe ID에 온보딩되면 Adobe 조직 수준에서 SSO(Single Sign-On)가 설정됩니다. 즉, SSO는 Adobe 조직의 모든 제품 인스턴스에 적용됩니다. SSO가 설정되면 이 값은 해당 Adobe 조직의 모든 Marketo 인스턴스에 적용됩니다. 이전에는 Marketo에서 인스턴스 수준에서 이 설정을 지원했습니다. Adobe Identity Management System에서는 지원되지 않습니다.

**Adobe ID 마이그레이션 후 Marketo Engage에서 현재 사용하는 CNAME, SPF 또는 DKIM에 변경 사항이 있습니까?**

아니요. 이러한 구성에는 영향을 주지 않습니다.

**세션 시간 초과를 방지하려면 어떻게 해야 합니까?**

[고급 설정](https://helpx.adobe.com/enterprise/using/authentication-settings.html#advanced-settings){target="_blank"}에서 원하는 최대 세션 수명을 사용자 지정할 수 있습니다(시스템 관리자 권한 필요). 제품 마이그레이션 후, 사용자 마이그레이션 전에 이 설정을 설정하는 것이 좋습니다.

**이제 Marketo Engage에 액세스하려면 Experience Cloud으로 이동해야 합니다. 이 흐름을 간소화할 방법이 있습니까?**

예. 앞으로 해당 페이지를 건너뛰기 위해 Marketo Engage 인스턴스 시작 페이지에서 **시작** 단추를 클릭한 후 시작되는 링크의 브라우저 책갈피를 만들 수 있습니다.

![](assets/faq-1.png)
