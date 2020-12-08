---
unique-page-id: 42762409
description: 마케팅 관리자를 위한 영업 인사이트 페이지 - 마케팅 문서 - 제품 설명서
title: 마케팅 관리자를 위한 영업 인사이트 페이지
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 0%

---


# 마케팅 관리자를 위한 영업 인사이트 페이지 {#sales-insight-page-for-marketo-admins}

마케팅 관리자는 Sales Insight에서 특정 권한을 갖습니다. 아래에 나와 있는 내용을 살펴보십시오.

## Soap API 구성 {#soap-api-configuration}

이러한 자격 증명은 Salesforce에서 MSI를 사용하기 위해 Salesforce 계정을 Marketing 인스턴스에 연결하는 데 사용됩니다.

![](assets/one-1.png)

## Rest API 구성 {#rest-api-configuration}

이러한 자격 증명은 Salesforce에서 MSI 인사이트 대시보드를 사용하기 위해 Salesforce 계정을 Marketing 인스턴스에 연결하는 데 사용됩니다.

![](assets/two-1.png)

SFDC에서 Rest API 자격 증명을 제거하고 Soap API만 사용하도록 선택할 수 있습니다. 인사이트 대시보드가 비활성화됩니다.

![](assets/three-1.png)

## 사람 점수 설정 {#person-score-settings}

| **별:** | 별은 다른 리드에 비해 총 리드 점수를 나타냅니다. |
|---|---|
| **불꽃:** | 화염은 시급함을 나타냅니다 - 최근 얼마나 많은 납이 변화되었는가. |

기본적으로 Marketing To Sales Insight는 리드 점수 필드를 사용하여 별과 화염을 계산합니다. 그러나 다른 분야를 선택하려면 다음 방법을 사용하십시오.

1. Marketing **의 관리** 영역에서 **Sales Insight를 클릭합니다**.

   ![](assets/four.png)

1. 리드 점수 설정에서 **편집을 클릭합니다**.

   ![](assets/five.png)

1. 별에 사용할 필드를 선택합니다.

   ![](assets/six.png)

1. 불길에 사용할 필드를 선택합니다.

   ![](assets/seven.png)

1. 저장을 **클릭합니다**. 재계산에는 약간의 시간이 소요됩니다. CRM에서 별과 화염을 확인할 수 있습니다.

   ![](assets/eight.png)

   >[!TIP]
   >
   >사용자 지정 점수 필드가 아직 없는 경우 이 필드를 [만드는 방법을 설명합니다](http://docs.marketo.com/x/3wMk).

   >[!NOTE]
   >
   >**관련 문서**
   >
   >
   >[별과 불꽃](http://docs.marketo.com/x/qgU6Ag)

## 설정 {#settings}

![](assets/nine.png)

**가입 해지 설정:**

템플릿 없음, 표준 이메일 및 운영 이메일에 대한 다음 구독 취소 설정 중에서 선택할 수 있습니다

* 수신 거부 설정 준수
* 수신자가 1명을 넘을 때 가입 해지 설정 준수
* 수신자가 5명 이상인 경우 가입 해지 설정 준수
* 구독 취소 설정 무시

**템플릿 잠금 기능 활성화:**

활성화되면 MSI 사용자는 Salesforce에서 이메일을 전송하는 동안 템플릿을 편집할 수 없습니다

**RSS 피드 사용:**

활성화되면 MSI 사용자는 자신의 리드 피드를 RSS 피드(Salesforce의 리드 피드 추가)로 볼 수 있습니다&#x200B;**.**
