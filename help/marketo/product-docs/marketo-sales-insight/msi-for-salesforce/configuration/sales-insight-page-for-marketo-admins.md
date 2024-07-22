---
unique-page-id: 42762409
description: Marketo 관리자를 위한 Sales Insight 페이지 - Marketo 문서 - 제품 설명서
title: Marketo 관리자를 위한 Sales Insight 페이지
exl-id: d98bc9d8-1a72-405f-b1d7-b71ad88c8493
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '417'
ht-degree: 0%

---

# Marketo 관리자를 위한 Sales Insight 페이지 {#sales-insight-page-for-marketo-admins}

Marketo 관리자는 Sales Insight에서 특정 권한을 갖습니다. 아래에 있는 내용에 대해 알아보십시오.

## Soap API 구성 {#soap-api-configuration}

이러한 자격 증명은 Salesforce에서 MSI를 사용하기 위해 Salesforce 계정을 Marketo 인스턴스에 연결하는 데 사용됩니다.

![](assets/one-1.png)

## Rest API 구성 {#rest-api-configuration}

이러한 자격 증명은 Salesforce에서 MSI Insights 대시보드를 사용하기 위해 Salesforce 계정을 Marketo 인스턴스에 연결하는 데 사용됩니다.

![](assets/two-1.png)

## 개인 점수 설정 {#person-score-settings}

* **별**: 별점은 다른 잠재 고객 대비 총 잠재 고객 점수를 나타냅니다.
* **Flames**: Flames는 긴급도를 나타냅니다. 최근 잠재 고객 점수가 얼마나 변경되었는지 나타냅니다.

기본적으로 Marketo Sales Insight는 잠재 고객 스코어 필드를 사용하여 별과 불꽃을 계산합니다. 그러나 다른 필드를 선택하려면 다음 방법을 사용하십시오.

1. Marketo의 **관리자** 영역에서 **판매 인사이트**&#x200B;를 클릭합니다.

   ![](assets/four.png)

1. 잠재 고객 점수 설정에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/five.png)

1. 별표에 사용할 필드를 선택합니다.

   ![](assets/six.png)

1. 화염에 사용할 필드를 선택합니다.

   ![](assets/seven.png)

1. **저장**&#x200B;을 클릭합니다. Sales insight는 다시 계산하는 데 시간이 좀 걸릴 수 있습니다. 나중에 CRM을 확인하여 별과 불꽃을 볼 수 있습니다.

   ![](assets/eight.png)

   >[!TIP]
   >
   >사용자 정의 점수 필드가 없는 경우 [만드는 방법](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)을 참조하세요.

   >[!MORELIKETHIS]
   >
   >[별과 불꽃놀이](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md)

## 설정 {#settings}

![](assets/nine.png)

**구독 취소 설정:**

템플릿 없음, 표준 이메일 및 운영 이메일에 대한 다음의 구독 취소 설정 중에서 선택할 수 있습니다

* 구독 취소 설정 준수
* 수신자가 2명 이상일 때 구독 취소 설정 준수
* 수신자가 5명 이상인 경우 구독 취소 설정 준수
* 구독 취소 설정 무시

**서식 파일을 잠글 수 있는 기능 사용:**

활성화되면 MSI 사용자는 Salesforce에서 이메일을 보내는 동안 템플릿을 편집할 수 없습니다

**RSS 피드 사용:**

활성화되면 MSI 사용자는 RSS 피드에서(Salesforce의 리드 피드 외에도) 리드 피드를 볼 수 있습니다. RSS 피드는 &quot;토큰 만료&quot; 기능이 비활성화된 경우에만 작동할 수 있습니다.

**토큰 만료:**

토큰 만료는 기능 관리자에서 제어합니다. 활성화/비활성화하려면 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하세요. 활성화되면 모든 Marketo 토큰이 10분 내에 만료됩니다. 비활성화하면 Marketo 토큰이 만료되지 않습니다.

토큰 만료를 활성화하기 전에 생성된 토큰은 유효성 검사에 필요한 만료 시간이 없으므로 현재 기능이 활성화되어 있더라도 만료되지 않습니다.

토큰 만료를 사용하도록 설정한 후 생성된 토큰의 만료 시간은 10분이므로 기능을 사용하지 않도록 설정한 후에도 10분 안에 만료됩니다.

토큰 동작은 생성 시점(현재 기능 상태가 아닌 토큰 만료 기능이 활성화/비활성화되었을 때)을 기반으로 합니다.
