---
description: Identity Management FAQ Adobe - Marketo 문서 - 제품 설명서
title: IDENTITY MANAGEMENT FAQ ADOBE
feature: Marketo with Adobe Identity
exl-id: 2401def7-1696-4d77-a8a3-96c490517121
source-git-commit: 19f60f58ae4de26536b304eb8ae9677ecc221993
workflow-type: tm+mt
source-wordcount: '1279'
ht-degree: 0%

---

# IDENTITY MANAGEMENT FAQ ADOBE {#adobe-identity-management-faq}

**Adobe ID란?**

Adobe Identity Management 시스템은 세 가지 구성 요소로 구성됩니다.

* [!DNL Adobe Identity Service]: 페더레이션 및 런타임 SSO(Single Sign-On)를 포함하여 최종 사용자의 인증 및 유효성 검사를 처리합니다.

* Adobe Admin Console: Admin Console은 전체 조직에서 Adobe 권한을 관리할 수 있는 중앙 위치를 제공합니다. 사용자 관리, 클라우드 서비스, 데스크톱 라이선스 자격, 페더레이션 구성을 처리하고 데이터 손실 방지 보안 기능을 제공합니다.

* UMAPI(Adobe 사용자 관리 API): 조직은 API 수준에서 Adobe Admin Console의 기업 사용자 및 권한을 관리할 수 있습니다.

**기존 Marketo Engage 구독은 언제 IMS와 통합됩니까?**

기존 Marketo 구독은 올해 말 Adobe Identity Management 시스템으로 마이그레이션됩니다. Marketo 지원에서는 Adobe IMS 마이그레이션과 관련된 업데이트를 제공할 수 없습니다. Adobe 계정 팀은 앞으로 몇 달 안에 예상 타임라인을 확인할 것입니다.

**마이그레이션 후에도 Marketo Engage URL은 그대로 유지됩니까?**

아니. 마이그레이션 후 URL은 다르게 표시됩니다. 그러나 에셋의 ID 번호는 그대로 유지됩니다. 또한 이전에 저장한 책갈피는 여전히 올바른 위치로 이동해야 합니다.

**URL 변경을 준비하기 위해 수행해야 할 작업이 있습니까?**

예. IT 팀에 문의하여 모든 Marketo Engage 리소스 및 웹 소켓을 허용하도록 아래(별표 포함) 도메인을 추가하는지 확인하십시오.

_*.experience.adobe.com_

**Adobe 제품 관리자와 Marketo Engage 관리자 간의 차이점은 무엇입니까?**

* Adobe 제품 관리자는 Marketo 플랫폼의 새로운 역할입니다.
* Adobe 제품 관리자 역할은 Adobe Admin Console에서 제품 관리자로 추가된 사용자에게 부여됩니다
* Adobe 제품 관리자는 읽기 전용 역할이며 Marketo Engage에서 편집하거나 삭제할 수 없습니다.
* Adobe 제품 관리자는 표준 Marketo 관리자와 동일한 권한과 권한을 갖습니다.
* Marketo Engage 관리자의 역할은 여전히 관리자이며 Marketo Engage의 사용자에게 부여됩니다.

**사용자 관리 API 클라이언트 지원에 변경 사항이 있습니까?**

예. Adobe IMS에 온보딩한 사용자는 기존의 Marketo 사용자 관리 API를 모두 활용할 수 없습니다. 사용자 초대, 업데이트 및 삭제 작업의 경우 Adobe [IMS API](https://www.adobe.io/apis/experienceplatform/umapi-new.html){target="_blank"}을(를) 사용해야 합니다. 역할 관리의 경우 Marketo 사용자 관리 API가 계속 적용됩니다. 이 외에 Marketo REST API 클라이언트 지원에 대한 다른 변경 사항은 없습니다.

**IMS와 통합되는 경우 지원을 받으려면 누구에게 연락해야 합니까?**

[Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 문의하는 표준 절차를 따릅니다.

**Adobe ID를 사용하여 다른 Adobe 응용 프로그램에 액세스하는 경우 해당 ID를 사용하여 Marketo에 액세스할 수 있습니까?**

다른 Adobe 제품이 있어도 구독이 IMS로 마이그레이션되기 전까지는 Adobe ID로 Marketo에 액세스할 수 없습니다.

**Adobe Admin Console에서 Marketo 사용자 역할(작업 공간 내)을 관리합니까?**

아니. Marketo Engage 시 사용자 역할 관리(작업 공간 내)가 완료됩니다.

**IMS 통합 구독의 Marketo 관리자로서 Admin Console에 액세스할 수 없습니다. 액세스 권한을 얻으려면 어떻게 해야 합니까?**

조직의 Admin Console에 액세스할 수 있는 모든 Adobe 시스템 또는 제품 관리자가 액세스 권한을 부여할 수 있습니다. 조직의 콘솔 관리자 권한이 있는 사용자를 모를 경우 [고객 지원 Adobe](https://helpx.adobe.com/contact.html){target="_blank"}에 문의하세요.

**관리자가 Marketo [!DNL Sales Connect]에 사용자를 추가하는 방법은 무엇입니까?**

[!DNL Sales Connect]에 대한 Admin Console에 제품 카드가 있는 동안 사용자를 추가/관리하는 데 Admin Console을 사용하면 안 됩니다. 다음 링크를 통해 관리자는 Marketo [!DNL Sales Connect]을(를) 통해 사용자를 관리할 수 있습니다. [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management){target="_blank"}.

**Adobe Admin Console에 대한 자세한 내용은 어디에서 확인할 수 있습니까?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/kr/enterprise/admin-guide.html){target="_blank"}.

**내 계정에 대한 사용자 계정을 변경하기 위해 Marketo의 관리 섹션으로 계속 이동합니까?**

아니요. [account.adobe.com](https://account.adobe.com){target="_blank"}로 이동해야 합니다.

**Marketo의 Universal ID에서 어떻게 작동합니까?**

Adobe ID에 온보딩되는 사용자는 제품의 구독 전환기를 통해 IMS 지원 구독에 원활하게 액세스할 수 있습니다.

**SSO에서 작동합니까?**

예. Adobe IMS와 Marketo 통합은 범용 ID 사용자 및 SSO를 지원합니다. SSO는 이제 Adobe IMS에 의해 구동되며 Adobe Admin Console의 조직 수준에서 설정됩니다. [자세히 알아보기](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

**이미 Adobe ID에 온보딩되었으며 이제 SSO를 구현하려고 합니다. 어떻게 해야 합니까?**

Adobe 조직에서 SSO를 구현하지 않고 단일 사인온을 구현하고 구독이 Adobe ID로 온보딩되었다면 [Marketo 지원](https://nation.marketo.com/){target="_blank"}에 티켓을 제출하고 &quot;Marketo on Admin Console, SSO 구현&quot;이라는 주제를 지정하십시오.

**장치 권한 부여는 어떻게 작동합니까?**

Adobe IMS는 현재 Marketo의 장치 인증 기능과 같은 기능을 지원하지 않습니다.

**사용자 초대 대화 상자에서 로그인 기능을 사용하여 사용자의 전자 메일에서 사용자의 로그인을 고유하게 만들 수 있습니까?**

아니. 구독이 IMS를 사용할 수 있는 경우 사용자 초대 워크플로가 더 이상 활성화되지 않으므로 기능이 더 이상 유효하지 않습니다. Adobe ID를 사용하려면 사용자의 ID가 이메일에 의해 제어되어야 합니다.

**Adobe IMS의 경우 Adobe ID, Enterprise ID 또는 Federated ID을 사용할 수 있습니까?**

예. 조직에서 지원할 ID 유형을 결정합니다. 추가 정보는 [ID 개요](https://helpx.adobe.com/enterprise/using/identity.html) 및 [ID 설정](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}에서 찾을 수 있습니다.

**Adobe Admin Console에서 지원되는 제품 카드는 무엇입니까?**

지원되는 제품 카드는 Marketo Engage, Marketo Measure, Marketo Dynamic Chat, Marketo Sales Connect 및 Marketo Sales Insight Actions 입니다.

**Adobe ID로 마이그레이션했을 때 사용자 로그인이 전자 메일과 일치하지 않으면 어떻게 합니까?**

이메일 주소와 다른 로그인을 사용하는 현재 Marketo 사용자는 Adobe ID로 마이그레이션되면 더 이상 해당 자격 증명으로 로그인하지 않습니다. Adobe ID는 항상 사용자의 이메일 주소로 인증됩니다.

**내 구독에서 IP 제한 설정을 사용하는 경우 Adobe ID 마이그레이션 후 어떻게 됩니까?**

Adobe ID에 구독을 온보딩할 때 IP 제한 설정이 Adobe Admin Console으로 마이그레이션되지 않습니다. Marketo의 IP 제한 설정에는 특정 IP 주소에서의 액세스만 허용하고 특정 IP 주소의 액세스를 차단하는 것이 포함됩니다. 현재 Adobe Identity Management 시스템은 IP 제한 기능을 지원하지 않습니다.

2024년 Adobe Identity Management System은 특정 IP 주소만 허용하는 기능을 출시하며 현재 이 기능을 사용하는 Marketo 사용자에 대한 전환을 지원합니다. 현재 이 기능을 사용하는 사용자는 기능이 릴리스될 때까지 사용자 마이그레이션을 수행하지 않습니다. 기능이 전달되면 마이그레이션이 예약된다는 알림이 사용자에게 표시됩니다. 사용 가능한 경우 기능에 대한 자세한 정보가 제공됩니다.

현재 IP 제한을 사용하는 사용자는 특정 주소의 액세스를 차단하며, Adobe Identity Management 시스템에서 지원하지 않으므로 Adobe ID로 마이그레이션한 후에는 이 기능을 더 이상 사용할 수 없습니다.

**Adobe ID 마이그레이션 후 &#39;단일 사인온 우회&#39; 옵션이 있는 역할을 가진 사용자가 있으면 어떻게 됩니까?**

구독이 Adobe ID에 온보딩되면 모든 사용자에 대한 Adobe 조직 수준에서 SSO(Single Sign-On)가 설정됩니다. SSO가 설정되면 해당 Adobe 조직의 모든 Marketo 사용자/모든 Marketo 인스턴스에 대해 적용됩니다. 이전에는 Marketo에서 사용자 역할을 설정하여 &#39;단일 사인온 우회&#39; 옵션을 사용할 수 있도록 지원했습니다. Adobe Identity Management 시스템에서 지원되지 않습니다.

**구독이 두 개 이상 있지만 모든 구독에서 Single Sign-On을 사용할 수 있는 것은 아닙니다. Adobe ID 마이그레이션 후 어떻게 됩니까?**

구독이 Adobe ID에 온보딩되면 Adobe 조직 수준에서 SSO(Single Sign-On)가 설정됩니다. 즉, SSO는 Adobe 조직의 모든 제품 인스턴스에 적용됩니다. SSO가 설정되면 이 SSO는 해당 Adobe 조직의 모든 Marketo 인스턴스에 적용됩니다. 이전에는 Marketo에서 인스턴스 수준에서 이 설정을 지원했습니다. Adobe Identity Management 시스템에서 지원되지 않습니다.
