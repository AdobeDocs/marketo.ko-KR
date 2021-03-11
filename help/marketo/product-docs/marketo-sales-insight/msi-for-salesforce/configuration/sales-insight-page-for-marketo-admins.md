---
unique-page-id: 42762409
description: 마케팅 관리자를 위한 영업 인사이트 페이지 - 마케팅 문서 - 제품 설명서
title: 마케팅 관리자를 위한 영업 인사이트 페이지
translation-type: tm+mt
source-git-commit: a7c90193e5c934119fa3b6bdf864d1458d1aad7c
workflow-type: tm+mt
source-wordcount: '438'
ht-degree: 0%

---


# 마케팅 관리자를 위한 영업 인사이트 페이지 {#sales-insight-page-for-marketo-admins}

마케팅 관리자는 Sales Insight에서 특정 권한을 갖습니다. 아래에 표시되는 내용을 살펴보십시오.

## Soap API 구성 {#soap-api-configuration}

이러한 자격 증명은 Salesforce에서 MSI를 사용하기 위해 Salesforce 계정을 Marketing 인스턴스에 연결하는 데 사용됩니다.

![](assets/one-1.png)

## 나머지 API 구성 {#rest-api-configuration}

이러한 자격 증명은 Salesforce에서 MSI 인사이트 대시보드를 사용하기 위해 Salesforce 계정을 Marketing 인스턴스에 연결하는 데 사용됩니다.

![](assets/two-1.png)

SFDC에서 Rest API 자격 증명을 제거하고 Soap API만 사용하도록 선택할 수 있습니다. 인사이트 대시보드가 비활성화됩니다.

![](assets/three-1.png)

## 사람 점수 설정 {#person-score-settings}

* **별**:스타는 다른 리드에 비해 총 리드 점수를 나타냅니다.
* **불꽃**:불길은 급박함을 나타냅니다 - 최근 어느 정도의 점수가 바뀌었습니까.

기본적으로 Marketing To Sales Insight는 리드 점수 필드를 사용하여 별과 화염을 계산합니다. 그러나 다른 필드를 선택하려면 다음 방법을 사용합니다.

1. Marketing의 **관리** 영역에서 **영업 인사이트**&#x200B;를 클릭합니다.

   ![](assets/four.png)

1. 리드 점수 설정에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/five.png)

1. 별에 사용할 필드를 선택합니다.

   ![](assets/six.png)

1. 화염에 사용할 필드를 선택합니다.

   ![](assets/seven.png)

1. **저장**&#x200B;을 클릭합니다. 다시 계산하려면 세일즈 인사이트가 필요합니다. 나중에 CRM에서 별과 화염을 확인할 수 있습니다.

   ![](assets/eight.png)

   >[!TIP]
   >
   >사용자 지정 점수 필드가 아직 없는 경우 [만들어](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)는 다음과 같습니다.

   >[!MORELIKETHIS]
   >
   >[별과 불꽃](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md)

## 설정 {#settings}

![](assets/nine.png)

**가입 해지 설정:**

템플릿 없음, 표준 이메일 및 운영 이메일에 대한 다음 가입 해지 설정 중에서 선택할 수 있습니다

* 가입 해지 설정 준수
* 수신자가 1명을 초과하는 경우 가입 해지 설정 준수
* 수신자가 5명을 초과하는 경우 가입 해지 설정 준수
* 구독 취소 설정 무시

**템플릿 잠금 기능 활성화:**

활성화되면 MSI 사용자는 Salesforce에서 이메일을 보내는 동안 템플릿을 편집할 수 없습니다.

**RSS 피드 사용:**

활성화되면 MSI 사용자는 RSS 피드에서 리드 피드를 볼 수 있습니다(Salesforce의 리드 피드 추가). RSS 피드는 &quot;토큰 만료&quot; 기능이 비활성화된 경우에만 사용할 수 있습니다.

**토큰 만료:**

토큰 만료는 기능 관리자에서 제어합니다. 활성화/비활성화하려면 [Marketing Support](https://nation.marketo.com/t5/Support/ct-p/Support)에 도달합니다. 활성화되면 모든 마케팅 토큰이 10분 이내에 만료됩니다. 비활성화되면 마케팅 토큰이 만료되지 않습니다.

토큰 만료일을 활성화하기 전에 생성된 토큰은 유효성을 검사할 만료 시간이 없으므로 이 기능이 현재 활성화되어 있어도 만료되지 않습니다.

토큰 만료 활성화 후 생성된 토큰은 만료 시간이 10분이므로 이 기능이 비활성화된 후에도 10분 후에 만료됩니다.

토큰 동작은 생성일을 기준으로 합니다(토큰 만료 기능이 현재 기능 상태가 아닌 활성화/비활성화된 시기).
