---
description: Adobe Identity Management FAQ - Marketo 설명서 - 제품 설명서
title: Adobe Identity Management FAQ
feature: Marketo with Adobe Identity
exl-id: 2401def7-1696-4d77-a8a3-96c490517121
source-git-commit: 95ed91736b7276dd7a5b9e09958c1f09832ae719
workflow-type: ht
source-wordcount: '1579'
ht-degree: 100%

---

# Adobe Identity Management FAQ {#adobe-identity-management-faq}

**Adobe Identity란?**

Adobe ID 관리 시스템은 세 가지 요소로 구성됩니다.

* [!DNL Adobe Identity Service]: 페더레이션 및 런타임 SSO(Single Sign-On)를 포함하여 최종 사용자의 인증 및 유효성 검사를 처리합니다.

* Adobe Admin Console: 관리 콘솔은 전체 조직의 Adobe 권한 부여를 관리하기 위한 중앙 위치를 제공합니다. 관리 콘솔은 사용자 관리, 클라우드 서비스, 데스크톱 라이선스 자격, 페더레이션 구성을 처리하고 데이터 손실 방지 보안 기능을 제공합니다.

* Adobe User Management API(UMAPI): 조직은 API 수준에서 Adobe Admin Console의 기업 사용자 및 자격을 관리할 수 있습니다.

**기존 Marketo Engage 구독은 언제 IMS와 통합됩니까?**

현재 기존의 Marketo Engage 구독은 갱신, 재계약 이벤트 및/또는 추가 사항이 포함된 모든 판매 이벤트에서 Adobe IMS로 마이그레이션되고 있습니다. 판매 이벤트 외의 마이그레이션은 2024년 10월부터 지원됩니다.

**마이그레이션 후에도 Marketo Engage URL은 그대로 유지됩니까?**

아니요. URL은 마이그레이션 후 다음과 같은 형식으로 표시됩니다. `https://experience.adobe.com/#/@tenantID/so:XXX-XXX-XXX/marketo-engage/classic/`(XXX는 Munchkin ID를 나타내며, @tenantID은 Adobe 조직에서 가져옴).

**URL 변경을 준비하기 위해 수행해야 할 작업이 있습니까?**

예. 마이그레이션 후 Marketo Engage는 experience.adobe.com에서 Adobe Experience Cloud로 서비스가 제공됩니다. Marketo Engage 액세스가 중단되지 않도록 IT 팀과 함께 [이 문서 상단](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md){target="_blank"}에 나열된 모든 Adobe 도메인을 허용 목록에 추가해야 합니다.

engage-xx.marketo.com 도메인의 Marketo Engage 자산에 대한 이전 링크와 북마크는 _계속_ 작동합니다. 그러나 탐색하고 있는 URL의 Marketo Engage 인스턴스에 먼저 로그인해야 합니다. 예를 들어, Munchkin ID 123-ABC-456이 있는 인스턴스에서 스마트 캠페인에 해당하는 북마크로 이동하려면 먼저 Munchkin ID 123-ABC-456으로 Marketo Engage 인스턴스에 로그인해야 합니다.

계획에는 없지만 향후 개발 작업에서 이 리디렉션 기능이 중단될 수 있습니다. 예기치 않은 중단을 방지하려면 가능한 한 빨리 북마크를 업데이트하는 것이 좋습니다.

**SSO으로 작동합니까?**

예. Adobe IMS와의 통합으로 범용 ID 사용자 및 SSO를 지원합니다. 이제 SSO는 Adobe IMS에 의해 구동되며 Adobe Admin Console의 조직 수준에서 설정됩니다. 그러나 Marketo Engage IdP가 제공하는 지원은 Adobe의 SP가 제공하는 지원과 차이가 있습니다([자세히 알아보기](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}). Admin Console로 마이그레이션한 후 SSO 차이점에 대한 도움이 필요한 경우 [Adobe 고객 지원 센터](https://helpx.adobe.com/kr/contact.html){target="_blank"}에 문의하십시오.

**Adobe 제품 관리자와 Marketo Engage 관리자의 차이점은 무엇입니까?**

* Adobe 제품 관리자는 Marketo 플랫폼에서의 새로운 역할입니다.
* Adobe 제품 관리자 역할은 Adobe Admin Console에서 제품 관리자로 추가된 사용자에게 부여됩니다.
* Adobe 제품 관리자는 읽기 전용 역할이며 Marketo Engage에서 편집하거나 삭제할 수 없습니다.
* Adobe 제품 관리자는 표준 Marketo 관리자와 동일한 권리와 권한을 갖습니다.
* Marketo Engage 관리자의 역할은 여전히 관리자이며 Marketo Engage의 사용자에게 부여됩니다.
* Marketo 기본 관리자 역할을 가진 사용자만 Admin Console에서 Marketo 제품 관리자로 지정됩니다.

**사용자 관리 API 클라이언트 지원에 변경 사항이 있습니까?**

예. Adobe IMS에 온보딩된 사용자라도 기존의 Marketo 사용자 관리 API 중 활용하지 못하는 것도 있습니다. 사용자 초대, 업데이트 및 삭제 작업의 경우에는 Adobe [IMS API](https://www.adobe.io/apis/experienceplatform/umapi-new.html){target="_blank"}를 사용해야 합니다. 역할 관리의 경우 Marketo 사용자 관리 API가 계속 적용됩니다. 이 외에 Marketo REST API 클라이언트 지원에 대한 다른 변경 사항은 없습니다.

**IMS와 통합되는 경우 지원을 받으려면 누구에게 연락해야 합니까?**

* 사전 사용자 마이그레이션: [Marketing Nation Community](https://nation.marketo.com/t5/support/ct-p/Support) 또는 이메일 `customercare@marketo.com`의 파일 지원 사례.

* 사후 사용자 마이그레이션: [Marketing Nation Community](https://nation.marketo.com/t5/support/ct-p/Support) 또는 이메일 `customercare@marketo.com`의 파일 지원 사례.

* 지원 후 마이그레이션 완료: 제품 지원 관리자는 Experience League 지원 포털을 통해 사례를 제출할 수 있습니다.

Ultimate Success가 있는 경우 Admin Console 마이그레이션 화이트 글러브 서비스에 액세스할 수 있습니다. 도움이 필요하면 Adobe 계정 팀(계정 관리자)에 문의하십시오.

**Adobe ID를 사용하여 다른 Adobe 애플리케이션에 액세스하는 경우 그 ID를 사용하여 Marketo에도 액세스할 수 있습니까?**

다른 Adobe 제품이 있더라도 구독이 IMS로 마이그레이션되기 전까지는 Adobe ID로 Marketo에 액세스할 수 없습니다.

**Adobe Admin Console에서 Marketo 사용자 역할(작업 영역 내)을 관리합니까?**

아니요. 사용자 역할 관리(작업 영역 내)는 Marketo Engage에서 완료됩니다.

**IMS 통합 구독의 Marketo 관리자인데 Admin Console에 액세스할 수 없습니다. 액세스 권한을 얻으려면 어떻게 해야 합니까?**

조직의 Admin Console에 대한 액세스 권한이 있는 모든 Adobe 시스템 또는 제품 관리자가 액세스 권한을 제공할 수 있습니다. 조직 내 콘솔 관리 권한을 가진 사람이 누구인지 모른다면 [Adobe 고객 지원](https://helpx.adobe.com/kr/contact.html){target="_blank"}에 문의하십시오.

**관리자가 Marketo [!DNL Sales Connect]에 사용자를 추가하려면 어떻게 해야 합니까?**

Admin Console에 [!DNL Sales Connect]용 제품 카드가 있겠지만 사용자를 추가/관리하는 데 Admin Console을 사용해서는 안 됩니다. 다음 링크에서 관리자는 Marketo [!DNL Sales Connect]을(를) 통해 사용자를 관리할 수 있습니다. [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management){target="_blank"}.

**Adobe Admin Console에 대한 자세한 내용은 어디에서 확인할 수 있습니까?**

[https://helpx.adobe.com/kr/enterprise/admin-guide.html](https://helpx.adobe.com/kr/enterprise/admin-guide.html){target="_blank"}.

**내 계정에 대한 사용자 계정 변경하려면 여전히 Marketo의 관리 섹션으로 이동합니까?**

아니요. [account.adobe.com](https://account.adobe.com){target="_blank"}으로 이동해야 합니다.

**Marketo의 범용 ID로 작동합니까?**

Adobe ID에 온보딩된 사용자는 제품의 구독 전환기를 통해 모든 IMS 기반 구독에 원활하게 액세스할 수 있습니다.

**SSO로 작동합니까?**

예. Marketo와 Adobe IMS의 통합으로 범용 ID 사용자 및 SSO를 지원합니다. 이제 SSO는 Adobe IMS에 의해 구동되며 Adobe Admin Console의 조직 수준에서 설정됩니다. [여기에서 자세히 알아보십시오](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}.

**이미 Adobe ID에 온보딩되었으며 이제는 SSO를 구현하려고 합니다. 어떻게 해야 합니까?**

SSO를 구현하고자 하나 Adobe 조직에서 구현한 SSO 없이 구독이 Adobe ID로 온보딩되었다면 [Marketo 지원](https://nation.marketo.com/){target="_blank"}에 티켓을 제출하고 &quot;SSO를 구현하는 Admin Console의 Marketo&quot;로 주제를 지정하십시오.

**장치 권한 부여는 어떻게 작동합니까?**

Adobe IMS는 현재 Marketo의 장치 권한 부여와 같은 기능을 지원하지 않습니다.

**&quot;사용자 초대 대화 상자에서 로그인&quot; 기능을 사용하여 사용자의 이메일에서 사용자의 로그인을 고유하게 만들 수 있습니까?**

아니요. 구독이 IMS를 사용할 수 있는 경우 사용자 초대 워크플로가 더 이상 활성화되지 않으므로 이 기능은 더 이상 유효하지 않습니다. Adobe ID를 사용하려면 사용자의 ID가 이메일에 의해 제어되어야 합니다.

**Adobe IMS의 경우 Adobe ID, Enterprise ID 또는 Federated ID를 사용할 수 있습니까?**

예. 사용자는 조직에서 지원할 ID 유형을 결정합니다. 추가 정보는 [ID 개요](https://helpx.adobe.com/kr/enterprise/using/identity.html) 및 [ID 설정](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}에서 확인할 수 있습니다.

**Adobe Admin Console에서 지원되는 제품 카드는 무엇입니까?**

지원되는 제품 카드는 Marketo Engage, Marketo Measure, Marketo Dynamic Chat, Marketo Sales Connect 및 Marketo Sales Insight Actions입니다.

**Adobe ID로 마이그레이션했을 때 사용자 로그인이 이메일과 일치하지 않으면 어떻게 합니까?**

이메일 주소와 다른 로그인을 사용하는 현재 Marketo Engage 사용자는 Adobe ID로 마이그레이션되면 더 이상 해당 자격 증명으로 로그인할 수 없습니다. Adobe ID는 항상 사용자의 이메일 주소로 인증됩니다. [account.adobe.com](https://account.adobe.com){target="_blank"}에서 Adobe ID 이메일 주소를 업데이트할 수 있습니다.

**구독에서 IP 제한 설정을 사용하는 경우에는 Adobe ID 마이그레이션 후 어떻게 됩니까?**

현재 IP 제한 설정은 2026년 1분기까지 활성 상태로 유지됩니다(마이그레이션 전에 활성화한 구독에 적용됨). 이러한 제한은 Adobe ID 사용자에게도 적용되므로 액세스 제어 기능은 예상대로 계속 작동할 것입니다.

2026년 1분기부터는 기존의 IP 제한이 중단됩니다. 그 시점부터 IP 기반 액세스는 Adobe Admin Console(AAC)에서만 독점 관리됩니다. 보안 액세스를 유지하려면 AAC에서 IP 제한을 구성해야 합니다. 자세한 내용은 이 [Marketing Nation 블로그 게시물](https://nation.marketo.com/t5/product-blogs/updated-important-update-ip-restrictions-feature-transition/ba-p/358420){target="_blank"}을 참조하십시오.

**&#39;SSO 우회&#39; 옵션이 포함된 역할을 가진 사용자가 있는 경우, Adobe ID 마이그레이션 후 어떻게 됩니까?**

Adobe Admin Console에는 기본 Business ID 디렉터리가 제공됩니다. Adobe 조직의 Federated ID 디렉터리에 있는 도메인 외부의 사용자는 Adobe ID라는 ID 유형으로 이 디렉터리에 할당됩니다. 이러한 사용자는 SSO(Single Sign-On)를 거치지 않고 Marketo Engage에 액세스할 수 있으며 라이선스 소유권은 개인이 아닌 회사가 유지합니다.

**구독이 두 개 이상 있지만 모든 구독에서 SSO를 사용할 수 있는 것은 아닙니다. Adobe ID 마이그레이션 후에는 어떻게 됩니까?**

구독이 Adobe ID에 온보딩되면 Adobe 조직 수준에서 SSO가 설정됩니다. 즉, SSO는 Adobe 조직의 모든 제품 인스턴스에 적용됩니다. SSO가 설정되면 이 값은 해당 Adobe 조직의 모든 Marketo 인스턴스에 적용됩니다. 이전에는 Marketo에서 인스턴스 수준에서 이 설정을 지원했습니다. 이것은 Adobe ID 관리 시스템에서 지원하지 않는 기능입니다.

**Adobe ID 마이그레이션 후 Marketo Engage에서 현재 사용하는 CNAME, SPF 또는 DKIM에 변동이 있습니까?**

아니요. 이러한 구성에는 영향을 주지 않습니다.

**세션 시간 초과를 방지하려면 어떻게 해야 합니까?**

[고급 설정](https://helpx.adobe.com/kr/enterprise/using/authentication-settings.html#advanced-settings){target="_blank"}에서 원하는 최대 세션 수명을 사용자 정의할 수 있습니다(시스템 관리자 권한 필요). 제품 마이그레이션 후, 사용자 마이그레이션 전에 이 설정을 지정하는 것이 좋습니다.

**이제 Marketo Engage에 액세스하려면 Experience Cloud으로 이동해야 합니다. 이 흐름을 간소화할 방법이 있습니까?**

예. 앞으로 해당 페이지를 건너뛰기 위해 Marketo Engage 인스턴스 시작 페이지에서 **시작** 버튼을 클릭한 후 시작되는 링크의 브라우저 북마크를 만들 수 있습니다.

![](assets/faq-1.png)
