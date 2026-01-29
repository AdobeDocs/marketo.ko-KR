---
description: Adobe 관리 콘솔로 Marketo 구독 및 사용자 마이그레이션 이해 - Marketo 설명서 - 제품 설명서
title: Adobe 관리 콘솔로 Marketo 구독 및 사용자 마이그레이션 이해
exl-id: 91e7b56b-2563-4986-a55c-f9760ea88b05
feature: Marketo with Adobe Identity
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: ht
source-wordcount: '1571'
ht-degree: 100%

---

# Adobe 관리 콘솔로 Marketo 구독 및 사용자 마이그레이션 이해 {#understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console}

Adobe는 Adobe Marketo Engage 구독 및 사용자 관리 방법을 개선하여 사용자와 조직의 생산성을 높입니다. 이 변화의 일부로 Adobe는 Marketo Engage 구독 및 사용자를 Adobe Admin Console로 마이그레이션하고 있습니다. 이는 필수 마이그레이션이며 마케팅 워크플로, 콘텐츠, 통합 또는 에셋에는 영향을 주지 않습니다.

>[!TIP]
>
>[Enterprise 및 Teams 관리자 안내서](https://helpx.adobe.com/kr/enterprise/admin-guide.html){target="_blank"}를 통해 Adobe Admin Console을 사용하여 전체 조직에서 Adobe 권한을 관리하는 방법을 알아보십시오.

## 변경되는 사항은 무엇입니까? {#what-is-changing}

마이그레이션의 일부로 구독 및 사용자 관리가 Marketo 애플리케이션에서 Adobe Admin Console로 이동합니다.

* **시스템 관리자가 Adobe Admin Console에서 구독을 관리하게 됩니다**. 한 콘솔에서 모든 Adobe 제품을 볼 수 있습니다.

* **제품 관리자는 Adobe Admin Console에서 사용자와 사용자의 액세스 권한을 관리합니다**. 모든 Adobe 구독의 사용자를 추가하고 제거합니다. Adobe Admin Console은 사용자 기반 액세스 만료를 지원하지 않습니다. 마이그레이션 후 만료되도록 예약된 Marketo Engage 액세스 권한이 있는 사용자는 마이그레이션되며 만료되지 않는 액세스 권한이 부여됩니다. 마이그레이션 후에는 원하는 만료일에(또는 이전에) 수동으로 제거해야 합니다.

* **사용자는 Adobe ID로 로그인하게 됩니다**. Adobe는 기존 사용자를 Adobe Admin Console로 마이그레이션합니다. 사용자는 새로운 Adobe ID(Adobe ID 또는 Adobe Federated ID(SSO))를 사용하여 Marketo 구독에 로그인합니다.

* **마이그레이션 후에는 URL이 다르게 보입니다**. experience.adobe.com에서 서비스되던 Marketo Engage는 Adobe Experience Cloud으로 제공되며, URL은 `https://experience.adobe.com/#/@tenantID/so:XXX-XXX-XXX/marketo-engage/classic/` 형식이 됩니다(XXX는 Munchkin ID를 나타내며, @tenantID는 Adobe 조직의 ID임). Marketo Engage 액세스가 중단되지 않도록 IT 팀과 함께 [이 문서 상단](/help/marketo/getting-started/initial-setup/configure-protocols-for-marketo.md){target="_blank"}에 나열된 모든 Adobe 도메인을 허용 목록에 추가해야 합니다.

에셋의 ID 번호는 그대로 유지됩니다. engage-xx.marketo.com 도메인의 Marketo Engage 에셋에 대한 이전 링크와 북마크는 _계속_ 작동합니다. 그러나 탐색하고 있는 URL의 Marketo Engage 인스턴스에 먼저 로그인해야 합니다. 예를 들어, Munchkin ID 123-ABC-456이 있는 인스턴스에서 스마트 캠페인에 해당하는 북마크로 이동하려면 먼저 Munchkin ID 123-ABC-456으로 Marketo Engage 인스턴스에 로그인해야 합니다.

계획에는 없지만 향후 개발 작업에서 이 리디렉션 기능이 중단될 수 있습니다. 예기치 않은 중단을 방지하려면 가능한 한 빨리 북마크를 업데이트하는 것이 좋습니다.

## 변경되지 않는 것은 무엇입니까? {#what-is-not-changing}

* Marketo Engage 애플리케이션 자체에서 기능, 사용자 역할, 작업 영역, 기능 및 비헤이비어 관리를 포함한 **다른 모든 기능을 관리하는 방법은 변경되지 않습니다**. 로컬(API 전용) 사용자 관리 기능은 Marketo 관리자 영역의 _사용자 및 역할_ 탭에 남아 있습니다.

## 마이그레이션 여정 타임라인 {#migration-journey-timeline}

Adobe는 먼저 Marketo Engage 구독을 Adobe Admin Console로 마이그레이션한 다음 이메일 주소가 확인된 기존 사용자를 모두 마이그레이션합니다. 시스템 관리자 또는 Marketo 제품 관리자인 경우에는 마이그레이션 여정을 안내하는 이메일을 받게 됩니다. 다음은 예상할 수 있는 작업의 타임라인입니다.

![](assets/understanding-marketo-subscription-and-user-migration-1.png){width="800" zoomable="yes"}

### 구독 마이그레이션 완료 {#subscription-migration-complete}

시스템 관리자는 Adobe Admin Console로의 구독 마이그레이션이 완료되면 이메일을 받게 됩니다.

시스템 관리자는 Marketo 사용자에게 미치는 영향을 최소화하기 위해 사용자 마이그레이션이 시작되기 전에 몇 가지 필요한 단계를 완료해야 할 수 있습니다.

* Marketo 사용자가 현재 SSO로 로그인한 경우에는 SSO로 계속 로그인할 수 있도록 Adobe Admin Console에서 SSO를 설정해야 합니다. Marketo 사용자가 현재 SSO를 활용하지 않지만 Adobe Admin Console에서 SSO를 설정하려는 경우에는 마이그레이션 여정의 이 시점에 설정할 수 있습니다.

* Adobe Admin Console에서 다른 Adobe 제품을 이미 관리하는 경우에는 Adobe에서 사용자를 기존 콘솔로 자동 마이그레이션하는 데 동의할 것을 요청할 수 있습니다. 이메일의 &quot;시작하기&quot; 버튼을 클릭하여 동의 페이지로 이동합니다.

현재로서는 사용자 관리에 대한 변경 사항은 없습니다. Marketo 제품은 Admin Console에 표시되지만 Marketo 관리자는 Marketo 관리 영역에서 사용자를 계속 관리하며, 사용자 마이그레이션이 완료될 때까지 사용자는 Marketo ID로 계속 로그인하게 됩니다. 이 기간 동안은 사용자 마이그레이션이 시작될 때까지 Admin Console에서 Marketo 제품을 관리할 수 없습니다. 여기에는 구독과 연결된 Dynamic Chat 인스턴스가 포함됩니다.

>[!NOTE]
>
>현재 SSO를 사용하고 있지 않지만 구현을 고려 중인 경우, 사용자 마이그레이션이 발생하기 전에 구현하는 것이 좋습니다. SSO를 구현하고자 하나 Adobe 조직에서 구현한 SSO 없이 구독이 Adobe ID로 온보딩되었다면 [Marketo 지원](https://nation.marketo.com/){target="_blank"}에 티켓을 제출하고 &quot;SSO를 구현하는 Admin Console의 Marketo&quot;로 주제를 지정하십시오.

### 사용자 마이그레이션 예약 {#schedule-user-migration}

시스템 관리자가 이전 섹션에서 설명한 사전 요구 사항을 완료하면 Adobe는 30일 전에 사용자 마이그레이션을 자동으로 예약하고 Marketo 제품 관리자와 소통하면서 사용자 마이그레이션을 관리합니다.

Marketo 제품 관리자는 다음 작업을 수행합니다.

* 예약된 사용자 마이그레이션 시작 날짜가 30일 앞으로 다가오면 이메일을 수신합니다.

* Marketo 관리 영역에 있는 Marketo 마이그레이션 콘솔에 액세스하여 구독의 마이그레이션 날짜를 변경할 수 있습니다.

>[!NOTE]
>
>마이그레이션의 복잡성으로 인해 날짜 변경은 예약된 날짜의 30일 이내로 제한됩니다. 그보다 나중 날짜가 필요한 경우에는 `marketocares@marketo.com`으로 이메일을 보내십시오.

* 사용자 마이그레이션 시작 날짜까지의 카운트다운이 표시되는 My Marketo 배너를 참조하십시오.

* 사용자 마이그레이션 시작일 전날에 미리 알림 이메일을 수신합니다.

### 사용자 마이그레이션 날 준비 {#prepare-users-for-migration-day}

Marketo 제품 관리자는 모든 사용자가 마이그레이션 날을 준비하게 해야 합니다.

* Marketo 관리자 영역에 포함되는 모든 사용자의 [이메일 확인](/help/marketo/product-docs/administration/users-and-roles/email-verification.md){target="_blank"} 상태를 확인하십시오. 이메일 주소를 확인하지 않은 사용자에게 이메일 주소를 확인하도록 권장하고, 사용자가 확인 프로세스를 완료하는 과정에서 발생할 수 있는 문제를 해결하도록 지원합니다.

* 이메일 받은 편지함에서 &quot;잠김&quot; 사용자 알림을 검색합니다. 잠긴 사용자에게 암호를 재설정하여 마이그레이션 날 전에 Marketo Engage에 대한 액세스 권한을 재설정하도록 알립니다.

* 모든 사용자가 Adobe ID로의 향후 마이그레이션을 준비하게 합니다.

>[!IMPORTANT]
>
>Marketo Engage 사용자가 이메일 주소를 확인하지 않거나 사용자 마이그레이션 시 잠겨 있는 경우, 그 사용자는 Adobe ID로 마이그레이션되지 않고 구독에 대한 마이그레이션이 완료된 후 Marketo 구독에 대한 액세스 권한을 잃게 됩니다. 액세스 권한을 다시 얻으려면 Marketo 제품 관리자가 그를 새 사용자로 추가해야 합니다.

### 마이그레이션 날에 발생하게 되는 일 {#what-to-expect-on-migration-day}

미국 시간대가 포함된 모든 Marketo 구독이 마이그레이션 시작일 자정(태평양 표준시)부터 마이그레이션됩니다. 기타 모든 구독에 대한 사용자 마이그레이션은 구독의 지정된 시간대 자정에 시작됩니다.

**Adobe는 먼저 표준 관리자 역할을 가진 Marketo 관리자를 자동으로 마이그레이션합니다**. Marketo 관리자가 Admin Console 제품 관리자 역할을 가진 Adobe ID로 마이그레이션되면, 이전에 갖고 있던 다른 역할과 함께 Marketo 애플리케이션 내에서 Adobe 제품 관리자 역할이 할당됩니다.

**Marketo 및/또는 Adobe 조직에서 Marketo 구독에 SSO가 없는 경우**, Adobe에서 나머지 사용자를 자동으로 마이그레이션합니다. 이 워크플로는 Adobe Marketo 사용자의 오버헤드를 최소화하기 위해 최고 수준의 자동화를 제공하는 것을 목표로 합니다. 마이그레이션을 실행하는 데 필요한 작업은 없습니다.

**Marketo 및/또는 Adobe 조직에서 Marketo 구독에 SSO가 있는 경우** Marketo 관리자는 Marketo 관리자 영역에 있는 Marketo 마이그레이션 콘솔의 셀프서비스 사용자 마이그레이션 영역에 액세스할 수 있습니다. 사용자 마이그레이션 프로세스 중에 더 세밀한 제어가 필요한 사용자를 위해 Marketo 관리자는 일괄적으로 마이그레이션하거나 동시에 마이그레이션할 사용자를 선택할 수 있습니다. 사용자가 선택되면 관리자는 &quot;지금 마이그레이션&quot; 또는 나중을 위한 &quot;마이그레이션 예약&quot; 옵션을 가지므로 극도의 유연성을 발휘하고 마이그레이션 시점을 제어할 수 있습니다.

>[!NOTE]
>
>사용자 마이그레이션 중에도 제품에 대한 액세스 권한은 사라지지 않습니다. 사용자를 마이그레이션하는 동안 사용자가 로그인하면 그 사용자는 로그아웃되고 마이그레이션이 완료된 후 Adobe ID를 사용하여 몇 분 안에 다시 로그인하라는 메시지가 표시됩니다. 사용자는 사용자 마이그레이션이 성공적으로 끝나면 전송되는 권한 이메일에 있는 링크를 클릭하여 초대를 수락해야 합니다.

사용자가 마이그레이션되면 Marketo에 로그인하는 방식의 변경을 알리는 이메일을 Adobe에서 받게 됩니다. 사용자는 처음에는 기존의 Adobe ID로 로그인하거나 동일한 이메일 주소를 사용해 새 Adobe ID를 설정하는 방법으로 Adobe Identity를 사용해 로그인하라는 초대를 **수락해야** 합니다.

자세한 내용은 [Adobe ID로 마이그레이션](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}, [Adobe에서 사용자 로그인](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"} 및 [Adobe Identity Management FAQ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}에서 확인할 수 있습니다.

## 사용자 마이그레이션 완료 {#user-migration-complete}

Adobe는 모든 관리자와 사용자가 마이그레이션되면 이메일을 통해 모든 시스템 관리자 및 제품 관리자에게 알립니다. 현재 해당 구독의 모든 Marketo 사용자는 Adobe ID를 사용하여 Marketo에 로그인하고 제품 관리자는 Adobe Admin Console에서만 사용자를 관리합니다.

## 지원 받기 {#get-support}

구독 또는 사용자 마이그레이션에 대한 추가 지원이 필요하면 `marketocares@marketo.com`에 이메일을 보내십시오.

>[!MORELIKETHIS]
>
>* [Adobe ID로 마이그레이션 개요](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/migrating-to-adobe-identity.md){target="_blank"}
>* [Adobe에서 사용자 로그인](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"}
>* [Adobe Identity Management FAQ](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}
>* [Adobe Identity Management 튜토리얼로 마이그레이션](https://experienceleague.adobe.com/ko/docs/marketo-learn/tutorials/fundamentals/migrating-to-adobe-identity-management){target="_blank"}
