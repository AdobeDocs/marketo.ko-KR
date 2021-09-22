---
unique-page-id: 10100311
description: 구독 로그인에 범용 ID 사용 - Marketo 문서 - 제품 설명서
title: 구독 로그인에 범용 ID 사용
exl-id: 75cf1323-0468-49e9-83ca-e55aa30744ac
source-git-commit: d5c1c1d0ce2a521898eaa4f6610bf1ce04b4f66b
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 0%

---

# 구독 로그인에 범용 ID 사용 {#using-a-universal-id-for-subscription-login}

범용 ID를 사용하면 한 번의 로그인으로 여러 Marketo 가입에 액세스할 수 있으며 구독 간을 빠르게 전환할 수 있습니다. 원하는 경우 구독에 다른 로그인을 사용할 수 있습니다.

Universal ID를 사용해도 여전히 각 개별 구독에 대한 지원 티켓을 만듭니다.

구독 수준 설정은 역할, 권한 및 암호 정책 등 범용 ID를 사용하는 사용자에게 적용됩니다. 사용자 프로필 수준 변경 사항은 이름, 성 및 이메일 주소와 같은 모든 구독에 반영됩니다.

## 범용 ID 설정 {#setting-up-a-universal-id}

모든 Marketo 구독에는 선택적 범용 ID 기능이 포함되어 있습니다. 각 개별 인스턴스에서 Marketo 관리자가 동일한 로그인을 사용하는 각 서로 다른 구독에 사용자를 초대해야 합니다. Marketo은 기존 로그인을 자동으로 병합할 수 없습니다.

>[!NOTE]
>
>여러 구독 로그인 ID가 있는 경우 여러 커뮤니티 프로필이 있을 수도 있습니다. 사용하려는 프로필에 연결된 범용 ID에 대한 ID를 선택해야 하며, 이는 샌드박스가 아닌 프로덕션 인스턴스에 대한 ID입니다.

## 로그인하는 중 {#logging-in}

범용 ID를 사용하여 두 번째 구독에 대한 초대를 수락하기 위해 로그인하면 옵트인 로그인 페이지가 표시됩니다. 여기에서 약관에 동의하려면 확인란을 선택해야 합니다. 수락하면 후속 로그인에 대해 이 페이지가 아니라 일반 재설정 페이지가 표시됩니다. 약관에 동의하면 Marketo에서 기본 프로필 데이터(예: 이름, 성 및 이메일 주소)를 구독이 호스팅되는 다른 위치의 데이터 센터에 배포할 수 있습니다.

![](assets/new-login-reduced-hands-name.png)

>[!TIP]
>
>구독 관리자가 삭제하지 않는 한 더 이상 사용하지 않는 ID는 유지됩니다. 예를 들어, 해당 ID를 사용해야만 액세스할 수 있는 개인 보고서가 자신에게 할당된 경우 이 ID를 유지해야 합니다. 이 경우 이러한 개인 보고서를 새 범용 ID로 이동한 다음 기존 ID를 삭제하는 것이 적절합니다.

## 암호 {#passwords}

여러 가입에 대한 Universal ID를 사용하면 Marketo에서 가장 엄격한 암호 정책을 자동으로 적용합니다. 예를 들어, 일부 구독에 최소 암호 길이가 필요하고 다른 구독이 그렇지 않으면 모든 구독에 최소 길이가 적용됩니다.

여러 가입에 대한 범용 ID를 사용하면 암호를 변경할 수만 있습니다.

>[!NOTE]
>
>Marketo은 현재 구독의 암호가 초대를 받는 두 번째 구독의 암호 정책을 준수하지 않는 경우 범용 ID를 사용하여 암호를 재설정하도록 사용자에게 요청합니다.

## 구독 간 전환 {#switching-between-subscriptions}

범용 ID를 사용하면 로그인된 구독을 확인하고, 로그인 액세스 권한이 있는 다른 구독을 선택할 수 있습니다. 대부분의 경우 로그아웃한 후 다시 로그인하지 않아도 됩니다.

![](assets/image2016-11-3-15-3a10-3a16.png)

로그아웃한 후 다시 로그인하면 Marketo에서 마지막으로 로그인한 가입에 자동으로 로그인됩니다. 그런 다음 필요한 경우 다른 구독으로 전환할 수 있습니다.

## 커뮤니티 프로필 {#community-profiles}

여러 개의 구독이 있는 경우 여러 커뮤니티 프로필이 있을 수 있습니다. 가장 활성 커뮤니티 프로필과 연결된 로그인을 선택하는 것이 좋습니다.

## 모바일 플랫폼 {#mobile-platform}

Universal ID를 사용하는 사용자는 마지막으로 로그인한 구독에서 Marketo Moment 및 iPad 이벤트 체크인 애플리케이션의 데이터를 볼 수 있습니다. 모바일 플랫폼 자체에서는 구독을 변경할 수 없습니다.

>[!MORELIKETHIS]
>
>* [포털에 단일 사인온 추가](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [사용자 로그인을 SSO로만 제한](/help/marketo/product-docs/administration/additional-integrations/restrict-user-login-to-sso-only.md)
>* [범용 ID를 사용하여 Marketo 사용자를 두 인스턴스로 초대합니다.](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)

