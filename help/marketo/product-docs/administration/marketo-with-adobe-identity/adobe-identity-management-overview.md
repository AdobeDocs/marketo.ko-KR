---
description: Adobe Identity Management 개요 - Marketo 문서 - 제품 설명서
title: Adobe Identity Management 개요
exl-id: 18ddeebc-bc89-411c-9d2c-23df6841cb3a
feature: Marketo with Adobe Identity
source-git-commit: ab1ea483998d6cb37277b18adf2c1d3371bb40e6
workflow-type: tm+mt
source-wordcount: '402'
ht-degree: 0%

---

# Adobe Identity Management 개요 {#adobe-identity-management-overview}

모든 새 Adobe Marketo Engage 구독(2023년 7월 31일 이상)은 Adobe Identity Management 시스템과 통합됩니다. 기존 Marketo 구독은 현재 갱신 및/또는 이벤트 재계약 시 Adobe Identity Management 시스템으로 마이그레이션되고 있습니다. 갱신 또는 재계약 이벤트 이외의 마이그레이션은 현재 지원되지 않습니다.

>[!NOTE]
>
>Marketo 지원에서는 Adobe IMS 마이그레이션과 관련된 업데이트를 제공할 수 없습니다. Adobe 계정 팀은 앞으로 몇 달 안에 예상 타임라인을 확인할 것입니다. 자세한 내용은 다음을 참조하십시오. [이 문서](/help/marketo/product-docs/administration/marketo-with-adobe-identity/understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console.md){target="_blank"}, and the [Frequently Asked Questions](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}.

Adobe ID에 온보딩된 구독의 경우 사용자 관리에 Adobe Admin Console이 사용됩니다. 단일 사인온과 같은 ID 관련 개념도 Admin Console에서 관리됩니다.

* 에 대한 추가 정보 찾기 [Adobe Admin Console](https://helpx.adobe.com/enterprise/using/admin-console.html){target="_blank"}.
* 에 대한 추가 정보 찾기 [Marketo 구독과 관련된 Adobe 조직 설정](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}.

>[!NOTE]
>
>SSO를 Adobe 조직에서 구현하지 않고 구독이 Adobe ID에 온보딩되었으므로 단일 사인온을 구현하려면 다음에 대한 티켓을 제출하십시오. [Marketo 지원](https://nation.marketo.com/){target="_blank"} 그리고 항목을 &quot;Admin Console 시 Marketo, SSO 구현&quot;으로 지정합니다.

## 프로필 수준 {#profile-levels}

Adobe Identity Management 시스템에 온보딩된 Adobe Marketo Engage 구독은 다양한 프로필을 지원합니다. 다음은 이 통합과 관련된 사용자 프로필 유형입니다.

<table>
 <tr>
  <td><strong>Adobe Admin Console 시스템 관리자</strong></td>
  <td>Adobe Admin Console에서 Adobe 조직 및 Marketo Engage 제품에 대한 ID 개념 설정을 담당합니다. Adobe 조직 설정에서 부여된 역할.</td>
 </tr>
 <tr>
  <td><strong>Adobe Admin Console 제품 관리자</strong></td>
  <td>Adobe Admin Console에서 Marketo Engage 제품에 대한 사용자 권한을 부여합니다. Adobe Admin Console에서 부여된 역할.</td>
 </tr>
 <tr>
  <td><strong>Adobe Admin Console 제품 프로필 관리자</strong></td>
  <td>제품 프로필 내에서 사용자 관리를 담당합니다. 특정 프로필 이외의 사용자는 관리할 수 없습니다. 제품 프로필 관리자는 사용자로 제품 프로필에 추가되지 않으면 Marketo 애플리케이션에 액세스할 수 없습니다. 이들의 역할은 여전히 표준 사용자입니다(둘 이상의 작업 영역이 있는 경우 기본 작업 영역).
</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage 제품 관리자</strong></td>
  <td>관리자 권한을 가진 Marketo Engage에 대한 액세스 권한을 부여 받은 사람입니다. Adobe Admin Console이 아닌 Marketo Engage에서 부여된 역할.</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage 사용자</strong></td>
  <td>Marketo Engage에 대한 액세스 권한이 부여된 사람입니다. 관리 권한이 없습니다.</td>
 </tr>
</table>

## FAQ {#faq}

자주 묻는 질문 [은(는) 여기에서 찾을 수 있음](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}.

>[!MORELIKETHIS]
>
>* [관리자 설정](/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md){target="_blank"}
>* [제품 관리자 추가 또는 제거](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-product-admin.md){target="_blank"}
>* [사용자 추가 또는 제거](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md){target="_blank"}
