---
description: Adobe Identity Management 개요 - Marketo 문서 - 제품 설명서
title: Adobe Identity Management 개요
exl-id: 18ddeebc-bc89-411c-9d2c-23df6841cb3a
feature: Marketo with Adobe Identity
source-git-commit: 8d4a542687119e7e4044b26eeafcc71315609f19
workflow-type: tm+mt
source-wordcount: '445'
ht-degree: 0%

---

# Adobe Identity Management 개요 {#adobe-identity-management-overview}

모든 새 Adobe Marketo Engage 구독(2023년 7월 31일 이상)은 Adobe Identity Management 시스템과 통합됩니다. 기존 Marketo Engage 구독은 현재 갱신, 재계약 이벤트 및/또는 추가 사항이 포함된 모든 판매 이벤트 시 Adobe Identity Management 시스템으로 마이그레이션되고 있습니다. 영업 이벤트 이외 마이그레이션은 2024년 10월부터 지원됩니다. Marketo 관리자는 구독이 판매 이벤트 외부에서 마이그레이션되는 경우 2~4주 전에 알림을 받게 됩니다.

>[!NOTE]
>
>Marketo 지원에서는 Adobe IMS 마이그레이션과 관련된 업데이트를 제공할 수 없습니다. Adobe 계정 팀은 앞으로 몇 달 안에 예상 타임라인을 확인할 것입니다. 자세한 내용은 [이 문서](/help/marketo/product-docs/administration/marketo-with-adobe-identity/subscription-and-user-migration/understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console.md){target="_blank"} 및 [자주 묻는 질문](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}을 참조하세요.

Adobe ID에 온보딩된 구독의 경우 사용자 관리에 Adobe Admin Console이 사용됩니다. 단일 사인온과 같은 ID 관련 개념도 Admin Console에서 관리됩니다.

* [Adobe Admin Console](https://helpx.adobe.com/kr/enterprise/using/admin-console.html){target="_blank"}에 대한 자세한 정보를 찾으십시오.
* [Marketo 구독과 관련된 Adobe 조직 설정](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}에 대한 자세한 내용을 확인하세요.

>[!NOTE]
>
>Adobe 조직에서 SSO를 구현하지 않고 단일 사인온을 구현하고 구독이 Adobe ID로 온보딩되었다면 [Marketo 지원](https://nation.marketo.com/){target="_blank"}에 티켓을 제출하고 &quot;Marketo on Admin Console, SSO 구현&quot;이라는 주제를 지정하십시오.

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
  <td><strong>Marketo Engage 관리자</strong></td>
  <td>관리자 권한을 가진 Marketo Engage에 대한 액세스 권한을 부여 받은 사람입니다. Adobe Admin Console이 아닌 Marketo Engage에서 부여된 역할(<b>사용자 편집</b> 모달에서 "관리자"로만 표시됨).</td>
 </tr>
 <tr>
  <td><strong>Marketo Engage 사용자</strong></td>
  <td>Marketo Engage에 대한 액세스 권한이 부여된 사람입니다. 관리 권한이 없습니다.</td>
 </tr>
</table>

## FAQ {#faq}

FAQ [은(는) 여기에서 찾을 수 있습니다](/help/marketo/product-docs/administration/marketo-with-adobe-identity/faq.md){target="_blank"}.

>[!MORELIKETHIS]
>
>* [관리자 설정](/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md){target="_blank"}
>* [제품 관리자 추가 또는 제거](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-product-admin.md){target="_blank"}
>* [사용자 추가 또는 제거](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md){target="_blank"}
