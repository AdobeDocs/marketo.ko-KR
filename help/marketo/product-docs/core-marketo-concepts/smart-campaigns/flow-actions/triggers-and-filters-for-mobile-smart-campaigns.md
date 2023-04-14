---
unique-page-id: 9437991
description: 모바일 스마트 캠페인에 대한 트리거 및 필터 - Marketo 문서 - 제품 설명서
title: 모바일 스마트 캠페인에 대한 트리거 및 필터
exl-id: 76fc7a74-b27d-4898-a8ca-85c9c2828a28
source-git-commit: 98eac847e62df1e17a6abefde0f9097b12cbbf9c
workflow-type: tm+mt
source-wordcount: '818'
ht-degree: 0%

---

# 모바일 스마트 캠페인에 대한 트리거 및 필터 {#triggers-and-filters-for-mobile-smart-campaigns}

모바일 앱 스마트 캠페인에 대한 트리거 및 필터를 설정할 수 있습니다.

대부분의 활동에는 트리거, 필터 및 비활성 필터가 있습니다. 비활성 필터를 사용하여 푸시 알림 탭과 같은 작업을 추적합니다. *안 그랬어* 발생합니다.

* 모바일 앱이 설치됨/설치됨
* 모바일 앱이 열림/열림
* 모바일 앱 활동 있음/있음
* 모바일 앱 세션 있음/있음
* 탭/탭된 모바일 푸시 알림

이 활동에는 필터만 있습니다.

* 푸시 알림을 전송함 - 필터 및 비활성 필터

검색 대상 **모바일 앱** 오른쪽 패널에서 모든 모바일 앱 트리거와 필터를 나열할 수 있습니다.

![](assets/triggers-and-filters-for-mobile-smart-campaigns-1.png)

## 제한 {#constraints}

트리거 및 필터와 함께 제약 조건을 사용하여 데이터를 추가로 정렬할 수 있습니다.

![](assets/triggers-and-filters-for-mobile-smart-campaigns-2.png)

푸시 알림을 전송함 을 제외한 모든 트리거 및 필터에는 다음 두 가지 표준 제한 사항이 포함되어 있습니다.

* 장치 유형 - iPod, iPhone, iPhone 6 Plus, iPad mini, iPad, Android 스마트폰, Android 태블릿, 알 수 없음(사전 설정된 목록)

* 플랫폼 - iPhone 또는 Android

일부 트리거 및 필터는 다음과 같은 추가 제한을 제공합니다.

* 앱 버전 - 최신 버전이 아닌 사용자를 타깃팅하는 방법입니다. 예를 들어 최신 앱 버전이 2.0인 경우 이 버전을 사용하여 앱 버전 2.0에 없는 사용자를 찾을 수 있습니다

* 설치 소스 - 현재 유일한 옵션은 API입니다

* 로케일 - 장치의 설정

* 모바일 앱 - 특정 앱의 이름입니다. 둘 이상의 항목이 있는지 지정하는 데 유용합니다

* 플랫폼 버전 - OS 버전

* 세션 길이(초) - 앱이 포그라운드에 있을 때의 세션 시간입니다

* 푸시 활성화됨 - **True** 은(는) 푸시 알림을 전송할 수 있음을 의미합니다. **False** 그것은 그들이 할 수 없다는 것을 의미합니다. 예를 들어, 사용자가 푸시 알림 수신을 옵트아웃했을 수 있습니다

## 트리거 및 필터 {#triggers-and-filters}

**모바일 앱 있음**

이 필터를 사용하여 앱을 설치한 모든 사용자를 확인합니다. 필터로만 사용할 수 있습니다.

>[!NOTE]
>
>Marketo이 앱 설치를 추적하지 않으므로 이 필터는 현재 및 이전 설치를 모두 찾습니다.

**제한**: 장치 유형, 플랫폼, 모바일 앱, 모바일 앱 버전, 장치 유형, 설치 소스, 푸시 사용 및 로케일

![](assets/triggers-and-filters-for-mobile-smart-campaigns-3.png)

>[!TIP]
>
>푸시 알림을 받아야 하는 스마트 목록을 정의할 때 모바일 앱 포함 = true 및 푸시 활성화됨 = true와 모바일 앱 이름을 지정하는 것이 좋습니다.

모바일 앱이 설치됨/설치됨

* 모바일 앱이 설치됨 - 트리거

* 모바일 앱이 설치됨 - 필터

* 모바일 앱이 설치되지 않음 - 비활성 필터

**제한**: 장치 유형, 플랫폼, 앱 버전, 로케일 및 설치 소스

![](assets/triggers-and-filters-for-mobile-smart-campaigns-4.png)

모바일 앱이 열림/열림

* 모바일 앱이 열려 있음 - 트리거

* 모바일 앱이 열림 - 필터

* 모바일 앱이 열리지 않음 - 비활성 필터

**제한**: 장치 유형 및 플랫폼

![](assets/triggers-and-filters-for-mobile-smart-campaigns-5.png)

모바일 앱 활동 있음/있음

따라서 사용자 지정 모바일 활동을 추적하는 강력한 방법을 제공합니다. 추적을 설정하려면 개발자와 작업해야 합니다 [Android용](https://developers.marketo.com/documentation/mobile/installation-instructions-on-android) 및 [iOS](https://developers.marketo.com/documentation/mobile/installation-instructions-on-ios).

* 모바일 앱 활동 있음 - 트리거

* 모바일 앱 활동 있음 - 필터

* 모바일 앱 활동이 없음 - 비활성 필터

**제한**: 장치 유형 및 플랫폼과 5개의 추가 장치:

* 작업 - 사용자 지정 모바일 활동

* 작업 유형 - (선택 사항) 여러 작업을 분류하는 데 사용되는 텍스트 필드입니다

* 작업 세부 사항 - (선택 사항) 작업에 대한 추가 정보를 제공하는 텍스트 필드입니다

* 작업 지표 - (선택 사항) 작업에 대한 추가 정보(예: 가격)를 제공하는 숫자 필드입니다

* 작업 길이(초) - (선택 사항) 사용자가 작업을 완료하는 데 걸린 시간을 캡처하는 데 사용할 수 있는 숫자 필드입니다

작업 제한을 사용하면 트리거 및 필터를 사용하여 모바일 활동을 매우 가깝게 추적할 수 있습니다.

>[!NOTE]
>
>**예**
>
>작업 유형 *쇼핑*&#x200B;여기에 을 정의하는 다른 제한 사항과 함께 매우 구체적인 작업이 있습니다.
>
>* 셔츠 샀어
   >   * 빨간색이었어요
   >   * 30달러예요
   >   * 사는 데 20초가 걸렸다


다음은 Marketo에서 필터를 보는 방법입니다.

![](assets/triggers-and-filters-for-mobile-smart-campaigns-6.png)

>[!NOTE]
>
>**예**
>
>동일한 작업 유형 아래에 여러 작업이 있을 수 있습니다. 실제로 일반적인 쇼핑 경험에는 쇼핑 아래에 몇 개의 열이 있을 수 있습니다. 양말 좀 가지고 가는 게 어때?
>
>| 작업 유형 | 쇼핑 | 쇼핑 |
>|---|---|---|
>| 액션 | 구매한 셔츠 | 바지를 샀어 |
>| 작업 세부 사항 | 색상 | 색상 |
>| 작업 지표 | 가격 | 가격 |


**모바일 앱 세션 있음/있음**

* 모바일 앱 세션 있음 - 트리거

* 모바일 앱 세션 있음 - 필터

* 모바일 앱 세션이 없음 - 비활성 필터

**제한**: 장치 유형, 플랫폼 및 세션 길이(초)

![](assets/triggers-and-filters-for-mobile-smart-campaigns-7.png)

탭/탭 푸시 알림

* 탭 푸시 알림 - 트리거

* 탭한 푸시 알림 - 필터

* 탭되지 않은 푸시 알림 - 비활성 필터

**제한**: 장치 유형, 플랫폼, 모바일 앱 버전, 푸시 알림 및 플랫폼 버전

![](assets/triggers-and-filters-for-mobile-smart-campaigns-8.png)

>[!TIP]
>
>탭되지 않은 푸시 알림 비활성 필터를 사용하여 최근에 전송된 푸시 알림을 탭하지 않은 사용자를 찾아 전자 메일을 통해 후속 작업을 수행할 수 있습니다.

**푸시 알림이 전송됨** 이 활동은 필터로만 사용할 수 있습니다.

* 푸시 알림을 전송함 - 필터

* 푸시 알림을 전송하지 않음 - 비활성 필터

**제한**: 푸시 알림 및 모바일 앱

![](assets/triggers-and-filters-for-mobile-smart-campaigns-9.png)

>[!MORELIKETHIS]
>
>* [스마트 목록 필터에 제한 추가](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md)
>* [스마트 목록에서 비활성 필터 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md)

