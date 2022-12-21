---
unique-page-id: 7505310
description: 스마트 목록에 가입 - Marketo 문서 - 제품 설명서
title: 스마트 목록에 가입
exl-id: 4ea1664b-8178-41ae-a184-a8ebe090ef96
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '423'
ht-degree: 0%

---

# 스마트 목록에 가입 {#subscribe-to-a-smart-list}

스마트 목록을 구독하는 것은 받은 편지함에 바로 전송된 보고서를 사용하여 사용자를 추적하는 좋은 방법입니다.

스마트 목록 가입을 두 개의 별도 위치에 만들 수 있습니다.

* 마케팅 활동
* 데이터베이스

구독은 구독이 실행되는 시점에 전체 사람 목록을 사용합니다.

구독은 마케팅 활동 또는 데이터베이스에서 스마트 목록이 있는 위치에 있습니다.

동일한 스마트 목록에서 여러 구독을 만들 수 있습니다.

구독은 작업 공간별로 다릅니다. 예를 들어, 이 구독 목록은 이 문서의 나머지 부분에 표시된 작업 공간과 다른 작업 공간에 있습니다.

![](assets/one.png)

>[!NOTE]
>
>Adobe Campaign은 Marketo 인스턴스당 100개의 구독과 구독당 최대 100,000명의 구독자로 제한됩니다. 스마트 목록에 10만 개 이상의 이름이 포함된 경우 Marketo은 처음 10만 개에 대한 구독을 실행합니다.

## 스마트 목록 구독 만들기 {#create-a-smart-list-subscription}

1. 로 이동합니다. **데이터베이스** 또는 **마케팅 활동**.

   ![](assets/db.png)

1. 구독을 만들 스마트 목록을 선택합니다. 클릭 **작업 나열** 을(를) 선택합니다. **새 스마트 목록 구독**.

   ![](assets/three.png)

1. 구독에 **이름**&#x200B;를 선택한 다음 의 이메일 주소를 선택하거나 입력합니다 **수신자**.

   ![](assets/image2015-9-14-13-3a18-3a38.png)

1. 을(를) 클릭합니다. **빈도** 빈도를 나열하고 선택합니다.

   ![](assets/image2015-9-14-13-3a21-3a21.png)

1. 설정 **배달 종료** 날짜. 선택할 수 있습니다 **절대 안 함** 또는 달력 날짜입니다.

   ![](assets/image2015-9-14-13-3a23-3a37.png)

1. 클릭 **형식** 목록에서 을(를) 선택합니다.

   ![](assets/image2015-9-14-13-3a25-3a25.png)

1. Click **Create**.

   ![](assets/image2015-9-11-15-3a58-3a4.png)

1. 새 스마트 목록 구독이 구독 탭의 목록 맨 위에 표시됩니다. 클릭 **보내기** 지금 보내려면 예약된 이메일 게재까지 기다리지 않습니다.

   ![](assets/eight.png)

1. 스마트 목록 가입을 구독하지 않은 경우 활성 확인란을 선택 취소하여 스마트 목록 구독을 비활성화하는 것이 좋습니다.

   ![](assets/nine.png)

   쉬웠지?

## 이메일 메시지 {#email-message}

수신자는 보고서를 다운로드할 수 있는 옵션과 Marketo 인스턴스 내의 목록에 직접 대한 링크가 포함된 이메일을 받게 됩니다. 다운로드 링크는 4일 후에 만료됩니다.

>[!NOTE]
>
>만약 [보안 구독 관리자](/help/marketo/product-docs/reporting/basic-reporting/report-subscriptions/secure-the-subscription-admin-setting.md) 설정이 **예**&#x200B;로 설정되면 Marketo 인스턴스에 액세스할 수 있는 사용자만 보고서를 다운로드할 수 있습니다.

![](assets/image2015-4-17-15-3a46-3a47.png)

보고서에 0명의 사람이 있는 경우 수신자는 여전히 이메일을 수신하게 됩니다. 하지만, 이메일에는 보고할 사람이 없다고 간단히 언급되어 있습니다.

![](assets/image2015-4-17-16-3a11-3a8.png)

>[!NOTE]
>
>가입을 기반으로 하는 스마트 목록 필터를 수정하면 보고서도 업데이트됩니다.

또한 이메일을 통해 목록을 만드는 데 사용되는 필터에 대한 추가 정보를 제공합니다.

## 구독 삭제 {#delete-a-subscription}

구독을 삭제하려면 구독 탭에서 구독을 선택하고 구독 삭제를 클릭합니다.

![](assets/twelve.png)

>[!MORELIKETHIS]
>
>* [스마트 목록 구독 편집](/help/marketo/product-docs/reporting/basic-reporting/report-subscriptions/edit-a-smart-list-subscription.md)
>* [Subscription Admin 설정 보안](/help/marketo/product-docs/reporting/basic-reporting/report-subscriptions/secure-the-subscription-admin-setting.md)

