---
unique-page-id: 10100311
description: 구독 로그인에 범용 ID 사용 - Marketo 문서 - 제품 설명서
title: 구독 로그인에 범용 ID 사용
exl-id: 75cf1323-0468-49e9-83ca-e55aa30744ac
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '628'
ht-degree: 0%

---

# 구독 로그인에 범용 ID 사용 {#using-a-universal-id-for-subscription-login}

유니버설 ID를 사용하면 한 번의 로그인으로 여러 Marketo 구독에 액세스할 수 있으며, 구독 간을 빠르게 전환할 수 있습니다. 원하는 경우 구독에 다른 로그인을 사용할 수 있습니다.

유니버설 ID를 사용해도 각각의 개별 구독에 대한 지원 티켓을 만들 수 있습니다.

구독 수준 설정은 역할, 권한 및 암호 정책 등 유니버설 ID를 사용하는 사용자에게 적용됩니다. 사용자 프로필 수준 변경 사항은 모든 구독에 반영됩니다(예: 이름, 성 및 이메일 주소).

## 유니버설 ID 설정 {#setting-up-a-universal-id}

각 개별 인스턴스에서 Marketo 관리자는 동일한 로그인으로 각 서로 다른 구독으로 사용자를 초대해야 합니다. Marketo은 기존 로그인을 자동으로 병합할 수 없습니다. 유니버설 ID를 활성화하면 최대 30분 동안 **Marketo 인스턴스를 사용할 수 없습니다.** 사용자 기반이 더 큰 경우 좀 더 길어질 수 있습니다.

>[!CAUTION]
>
>사용자에 대해 단일 ID 또는 유니버설 ID가 활성화된 경우 사용자의 역할 및 작업 영역은 초기 설정 후 **편집할 수 없습니다**.

>[!NOTE]
>
>여러 개의 구독 로그인 ID가 있는 경우 여러 커뮤니티 프로필이 있을 수도 있습니다. 사용하려는 프로파일과 연결된 범용 ID의 ID를 선택해야 하며 이는 샌드박스가 아니라 프로덕션 인스턴스용이어야 합니다.

## {#logging-in}에 로그인

유니버설 ID를 사용하여 2차 구독에 대한 초대를 수락하기 위해 로그인하면 옵트인 로그인 페이지가 표시됩니다. 여기에서 약관에 동의하려면 확인란을 선택해야 합니다. 승인하면 이후의 로그인 모두에 대해 이 페이지가 아닌 일반 재설정 페이지가 표시됩니다. 약관에 동의하면 Marketo에서 기본 프로필 데이터(이름, 성 및 이메일 주소 등)를 구독이 호스팅되는 다른 위치의 데이터 센터에 배포할 수 있습니다.

![](assets/new-login-reduced-hands-name.png)

>[!TIP]
>
>구독 관리자가 삭제하지 않는 이상 더 이상 사용하지 않는 ID는 유지됩니다. 예를 들어 자신에게 할당된 비공개 보고서가 있을 경우 해당 ID를 통해서만 액세스할 수 있도록 비공개 보고서를 유지하는 것이 좋습니다. 이 경우 이러한 비공개 보고서를 새 유니버설 ID로 이동한 다음 기존 ID를 삭제하는 것이 적절합니다.

## 암호 {#passwords}

여러 구독을 위한 범용 ID를 사용하는 Marketo은 가장 엄격한 암호 정책을 자동으로 적용합니다. 예를 들어 일부 구독에 최소 암호 길이가 필요하고 다른 구독에는 그렇지 않은 경우 모든 구독에 대해 최소 기간이 적용됩니다.

여러 구독에 대한 유니버설 ID를 사용하는 경우 암호만 변경할 수 있습니다.

>[!NOTE]
>
>Marketo은 현재 구독의 암호가 초대를 받는 두 번째 구독의 암호 정책을 준수하지 않는 경우 범용 ID를 사용하는 사용자에게 암호를 재설정하도록 요청합니다.

## 구독 {#switching-between-subscriptions} 간 전환

범용 ID를 사용하면 로그인한 구독을 확인하고 로그인 액세스 권한이 있는 다른 구독을 선택할 수 있습니다. 대부분의 경우 로그아웃했다가 다시 로그인하지 않고도 두 그룹 간에 전환할 수 있습니다.

![](assets/image2016-11-3-15-3a10-3a16.png)

로그아웃했다가 다시 로그인하면 Marketo은 마지막으로 로그인한 구독에 자동으로 로그인됩니다. 필요한 경우 다른 구독으로 전환할 수 있습니다.

## 커뮤니티 프로필 {#community-profiles}

여러 번 구독하는 경우 여러 커뮤니티 프로필이 있을 수 있습니다. 가장 활성화된 커뮤니티 프로필과 연결된 로그인을 선택하는 것이 좋습니다.

## 모바일 플랫폼 {#mobile-platform}

유니버설 ID를 가진 사용자는 마지막으로 로그인한 구독에서 Marketo Moments 및 iPad 이벤트 체크인 응용 프로그램의 데이터를 볼 수 있습니다. 모바일 플랫폼 자체에서는 구독을 변경할 수 없습니다.

>[!MORELIKETHIS]
>
>* [포털에 단일 사인온 추가](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [사용자 로그인을 SSO로만 제한](/help/marketo/product-docs/administration/additional-integrations/restrict-user-login-to-sso-only.md)
>* [범용 ID로 2개의 인스턴스에 Marketo 사용자 초대](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)

