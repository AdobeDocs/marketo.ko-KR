---
description: 개요 - Marketo 문서 - 제품 설명서
title: 개요
hide: true
hidefromtoc: true
source-git-commit: 1161d193261af10aaa7658e747ff6500ad4179d0
workflow-type: tm+mt
source-wordcount: '809'
ht-degree: 0%

---

# 개요 {#overview}

Adobe Marketo Engage 구독이 10/4/21 이후에 프로비저닝된 경우, Adobe Identity Management 시스템과 통합됩니다. 이 통합을 통해 사용자는 일반적인 Adobe ID를 사용하여 Marketo Engage 및 기타 Experience Cloud 애플리케이션에 로그인할 수 있습니다.

## 프로필 수준

Adobe Identity Management 시스템에 온보딩된 Adobe Marketo Engage 가입은 다양한 프로필을 지원합니다. 다음은 이 통합과 관련된 사용자 프로필 유형입니다.

<table>
 <tr>
  <td><strong>Adobe Admin Console 시스템 관리자</strong></td>
  <td>Adobe Admin Console에서 Adobe 조직 및 Marketo Engage 제품에 대한 ID 개념을 설정할 책임이 있습니다. Adobe 조직 설정에서 역할을 부여했습니다.</td>
 </tr>
 <tr>
  <td><strong>Adobe Admin Console 제품 관리자</strong></td>
  <td>Adobe Admin Console에서 Marketo Engage 제품에 대한 사용자 권한을 부여할 책임이 있습니다. Adobe Admin Console에서 역할을 부여했습니다.</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage 제품 관리자</strong></td>
  <td>관리자 권한이 있는 Marketo Engage에 대한 액세스 권한을 받은 사람. Adobe Admin Console이 아닌 Marketo Engage에서 부여된 역할.</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage 사용자</strong></td>
  <td>Marketo Engage에 대한 액세스 권한을 받은 사람. 관리 권한이 없습니다.</td>
 </tr>
</table>

## FAQ

**Adobe ID란?**

Adobe Identity Management 시스템은 세 가지 구성 요소로 구성됩니다.

* Adobe ID 서비스: 페더레이션 및 런타임 SSO(Single-Sign-On)를 포함하여 최종 사용자의 인증 및 유효성 검사를 처리합니다.

* Adobe Admin Console: Admin Console은 전체 조직에서 Adobe 자격을 관리할 중앙 위치를 제공합니다. 사용자 관리, 클라우드 서비스, 데스크탑 라이선스 권한, 페더레이션 구성을 처리하고 데이터 손실 방지 보안 기능을 제공합니다.

* Adobe 사용자 관리 API(UMAPI): 조직에서 API 수준에서 Adobe Admin Console에서 엔터프라이즈 사용자 및 자격을 관리할 수 있습니다.

**Adobe 제품 관리자와 Marketo Engage 관리자의 차이점은 무엇입니까?**

* Adobe 제품 관리자는 Marketo 플랫폼의 새로운 역할입니다.
* Adobe 제품 관리자 역할은 Adobe Admin Console에서 제품 관리자로 추가된 사용자에게 부여됩니다
* Adobe 제품 관리자는 읽기 전용 역할이며 Marketo Engage에서 편집하거나 삭제할 수 없습니다.
* Adobe 제품 관리자는 표준 Marketo 관리자와 동일한 권한과 권한을 갖습니다.
* Marketo Engage 관리자의 역할은 여전히 관리자이며, Marketo Engage의 사용자에게 부여됩니다.

**API 클라이언트 지원에 변경 사항이 있습니까?**

예. Adobe IMS에 온보딩된 사용자는 기존 Marketo 사용자 관리 API를 모두 활용할 수 없습니다. 사용자 초대, 업데이트 및 삭제 작업의 경우 [IMS API](https://www.adobe.io/apis/experienceplatform/umapi-new.html) 를 사용해야 합니다. 역할 관리의 경우 Marketo 사용자 관리 API가 계속 적용됩니다.

**지원을 받으려면 누구에게 연락해야 합니까?**

연락하는 표준 절차를 따릅니다 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support).

**Marketo 사용자 역할(작업 공간 내)이 Adobe Admin Console에서 관리됩니까?**

아니요. Marketo Engage에서 사용자 역할 관리(작업 공간 내)가 완료되었습니다.

**Marketo 관리자이며 Admin Console에 액세스할 수 없습니다. 액세스 권한을 받으려면 어떻게 해야 합니까?**

조직의 Admin Console에 액세스할 수 있는 모든 Adobe 시스템 또는 제품 관리자가 액세스 권한을 줄 수 있습니다. 조직의 구성원이 콘솔에서 관리자 권한을 가지고 있는지 확실하지 않은 경우 [고객 지원 Adobe](https://helpx.adobe.com/contact.html).

**관리자는 어떻게 Marketo Sales Connect에 사용자를 추가합니까?**

Sales Connect Admin Console에 제품 카드가 있을 경우 사용자를 추가/관리하는 데 Admin Console을 사용하지 않아야 합니다. 관리자는 다음 링크를 통해 Marketo Sales Connect를 통해 사용자를 관리할 수 있습니다. [https://toutapp.com/next#settings/admin/user-management](https://toutapp.com/next#settings/admin/user-management).

**Adobe Admin Console에 대한 자세한 내용은 어디에서 확인할 수 있습니까?**

[https://helpx.adobe.com/enterprise/admin-guide.html](https://helpx.adobe.com/enterprise/admin-guide.html).

**계정을 변경하기 위해 Marketo의 관리 섹션으로 계속 이동합니까?**

아니요. [account.adobe.com](https://account.adobe.com).

**Marketo의 범용 ID에서는 어떻게 작동합니까?**

Adobe ID로 온보딩되는 사용자는 제품의 구독 전환기를 통해 모든 IMS 지원 가입에 원활하게 액세스할 수 있습니다.

**SSO에서 작동합니까?**

예. Adobe IMS와 Marketo 통합은 범용 ID 사용자 및 SSO를 지원합니다. SSO는 이제 Adobe IMS에 의해 제어되며 Adobe Admin Console의 조직 수준에서 설정됩니다. [여기에서 추가 정보](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

**장치 인증은 어떻게 작동합니까?**

Adobe IMS는 현재 Marketo의 장치 인증 기능과 같은 것을 지원하지 않습니다.

**&quot;사용자 초대 대화 상자에 로그인&quot; 기능을 사용하여 이메일에서 로그인을 고유하게 만들 수 있습니까?**

아니요. 구독이 IMS를 사용할 수 있는 경우 사용자 초대 워크플로우가 더 이상 활성 상태가 아니므로 기능이 더 이상 유효하지 않습니다. Adobe id를 사용하려면 이메일에 의해 사용자의 ID가 제어되어야 합니다.

**Adobe IMS의 경우 Adobe ID, Enterprise ID 또는 Federated ID을 사용할 수 있는 옵션이 있습니까?**

예, 조직을 지원할 ID 유형을 결정합니다. 자세한 정보는 다음을 참조하십시오. [ID 개요](https://helpx.adobe.com/enterprise/using/identity.html) 여기에서 다음을 수행합니다. [ID 설정](https://helpx.adobe.com/enterprise/using/set-up-identity.html).

>[!MORELIKETHIS]
>
>* [관리 설정](/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md)
>* [제품 관리자 추가 또는 제거](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-product-admin.md)
>* [사용자 추가 또는 제거](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md)

