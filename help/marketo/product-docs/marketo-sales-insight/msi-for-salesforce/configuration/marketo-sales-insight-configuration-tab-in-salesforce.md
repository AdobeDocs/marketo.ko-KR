---
unique-page-id: 42762322
description: Salesforce - Marketo 문서 - 제품 설명서의 Marketo Sales Insight 구성 탭
title: Salesforce의 Marketo Sales Insight 구성 탭
exl-id: 4e2abd48-b0a5-4b71-939b-e66c7e39bb6c
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '615'
ht-degree: 1%

---

# [!DNL Marketo Sales Insight]의 [!DNL Salesforce] 구성 탭 {#marketo-sales-insight-configuration-tab-in-salesforce}

## 운영 설정 {#operational-settings}

SFDC에서 [!DNL Sales Insight]을(를) 사용하려면 이 설정을 해야 합니다.

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-1.png)

* MSI는 Soap 및 Rest API를 모두 사용합니다.
* Marketo 계정의 Sales Insight 페이지에는 Soap 및 Rest API 자격 증명이 있는 해당 패널 두 개가 있어 여기에 복사하여 붙여넣을 수 있습니다
* Soap 및 Rest API에는 조직의 필요에 따라 설정할 수 있는 별도의 시간 초과가 있습니다. 허용되는 최대 시간은 120초입니다.
* Insights 대시보드 비활성화: Rest API 자격 증명을 제거하고 Soap API만 사용할 수 있습니다. 이렇게 하면 모든 MSI visualforce 패널에서 인사이트 대시보드 탭이 비활성화됩니다.

## MSI 구성 {#msi-configuration}

구성은 모든 MSI 사용자에게 적용할 수 있으며 프로필에만 국한되지 않습니다.

**Visualforce 페이지 설정**

* 작업 활성화 드롭다운:
   * 리드 및 연락처 MSI 레이아웃에서 Marketo 이메일 보내기 드롭다운을 숨기는 기능
   * 리드 및 연락처 MSI 레이아웃에서 Marketo Campaign에 추가 옵션을 드롭다운에서 숨기는 기능
* 예정된 이벤트: 초대된 이벤트, 모든 이벤트를 사용자에게 표시하거나 이 탭을 완전히 숨기는 기능
* 예정된 캠페인: 모든 이메일 캠페인을 표시하거나 이 탭을 완전히 숨기는 기능
* 예정된 캠페인 및 이벤트 로드: 온디맨드 &quot;예정된 항목 로드&quot; 버튼 뒤에 이벤트 및 캠페인 탭을 배치하여 사용자의 Rest API 호출 수를 줄이는 기능
* 탭 설정: 기본적으로 5개의 탭을 모두 사용할 수 있습니다. Sales Insight 패널에서 탭 순서를 선택할 수 있습니다. 모든 레이아웃(리드, 연락처, 계정, 영업 기회)에 동일한 주문이 적용됩니다.

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-2.png)

**Marketo 전역 탭**

* RSS 피드 활성화됨: 활성화되면 MSI 사용자는 RSS 피드에서 (Salesforce의 리드 피드 외에도) 리드 피드를 볼 수 있습니다. RSS 피드는 &quot;토큰 만료&quot; 기능이 비활성화된 경우에만 작동할 수 있습니다. 이 설정은 Marketo Sales Insight 관리 페이지에서 제어합니다.
* 최상의 디버그 모드
* 기본 숨기기: 여기에서 선택하는 옵션은 &quot;숨기기&quot; 아이콘을 클릭할 때 Marketo의 최고 베트 탭에서 최고 베트가 숨겨지는 일 수입니다
* 연락처 상태 필드: 여기에서 선택하는 옵션은 Marketo의 최상의 선택 탭에 있는 상태 헤더 열에 채워지는 값이 됩니다
* 라이브 피드 설정: 라이브 피드(리드, 연락처, 계정 및 영업 기회 패널, 글로벌 Marketo 페이지)만, 리드 피드(Marketo 글로벌 페이지)만 또는 라이브 피드와 리드 피드를 모두 표시하도록 선택하는 옵션입니다
* 탭 설정: 기본적으로 5개의 탭을 모두 사용할 수 있습니다. Marketo 글로벌 페이지에서 탭 순서를 선택할 수 있습니다

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-3.png)

**제한**

* 활동(즐거운 순간, 웹 활동, 이메일)은 기본적으로 1000으로 설정되어 있습니다. 이메일 캠페인 및 이벤트는 기본적으로 200개로 설정됩니다
* 조직에서 시간 초과 문제가 발생하는 경우 한도를 줄일 수 있습니다.

**작업 설정**

* Marketo 이메일 보내기: 이 기능을 활성화하면 모든 Sales Insight 사용자가 Lead, Contact, Account, Opportunity 패널 및 Best Bets 탭(대량 작업 및 인라인 참여)에서 이메일을 보낼 수 있습니다.
* Marketo Campaign에 추가: 이 옵션을 활성화하면 모든 Sales Insight 사용자가 Lead, Contact, Account, Opportunity 패널 및 Best Bets 탭(일괄 작업 및 인라인 참여)에서 캠페인에 추가할 수 있는 액세스 권한을 부여합니다.

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-4.png)

## 지원 설정 {#support-settings}

이 확인란을 선택하면 Salesforce 인스턴스에서 디버그 로깅이 활성화됩니다. 문제를 해결하는 데 도움이 될 수 있습니다.

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-5.png)

## Marketo Sales Insight 재설정 {#reset-marketo-sales-insight}

이를 선택하면 SFDC의 모든 구성이 지워지며 복원할 수 없습니다. 모든 항목을 다시 구성해야 합니다.

![](assets/marketo-sales-insight-configuration-tab-in-salesforce-6.png)

>[!IMPORTANT]
>
>Sales Insights 작업 기능을 사용하지 않는 한 &quot;MSI 작업 사용&quot; 확인란을 선택하지 마십시오.

>[!MORELIKETHIS]
>
>[프로필에 판매 Insight 액세스 추가](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target="_blank"}
