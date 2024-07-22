---
unique-page-id: 10098134
description: 참여 프로그램 스트림에 프로그램 추가 - Marketo 문서 - 제품 설명서
title: 참여 프로그램 스트림에 프로그램 추가
exl-id: 44c2ce45-439b-4b29-8130-8cc218e04bbf
feature: Engagement Programs
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '461'
ht-degree: 0%

---

# 참여 프로그램 스트림에 프로그램 추가 {#adding-a-program-to-an-engagement-program-stream}

## 참여 프로그램 스트림에 중첩된 프로그램을 사용하는 이유는 무엇입니까? {#why-use-a-nested-program-in-an-engagement-program-stream}

참여 프로그램의 스트림에 전자 메일을 추가하는 것은 쉬우며 잘 작동합니다. 하지만 비즈니스 요구 사항이 더 복잡한 경우 이메일을 프로그램 내에 배치하는 것이 적절할 수 있습니다. 예를 들어 다음과 같은 작업을 수행할 수 있습니다.

* 스트림의 사용자 하위 그룹에 이메일 보내기
* 스트림 내의 하위 그룹에 *다른* 전자 메일 보내기
* 랜딩 페이지, 양식 또는 기타 에셋을 양육에 포함
* 멀티 터치 속성 활성화
* 경고 이메일과 같은 추가 흐름 단계 추가

## 스트림에서 프로그램을 사용하면 어떻게 됩니까? {#what-happens-when-you-use-a-program-in-a-stream}

중첩된 프로그램을 사용할 때 개인에게 이메일을 보내는 결정은 프로그램 멤버십과 프로그램 ID를 기반으로 합니다.

* 프로그램의 회원이 아닌 경우 프로그램의 일부인 모든 이메일을 한 번 받게 됩니다
* 프로그램의 회원인 경우 이메일을 받지 못합니다
* 더 이상 회원이 아니지만 해당 프로그램을 통해 이메일을 먼저 받은 경우 이메일을 받지 못합니다

스트림에서 프로그램을 사용할 때 이전에 해당 이메일을 수신했는지 여부는 중요하지 않습니다. 해당 특정 프로그램&#x200B;*에서* 전에 전자 메일을 보내지 않았다면 다시 받을 수 있습니다.

참여 프로그램에서 이메일과 프로그램을 혼합하는 데 문제가 생길 수 있습니다. 둘 중 하나를 사용할 수도 있습니다.

>[!TIP]
>
>스마트 목록에서 **참여 프로그램의 구성원** 필터를 사용하십시오.

## 스마트 목록 기준을 충족하지 않는 사람은 어떻게 됩니까? {#what-happens-to-people-who-dont-meet-the-smart-list-criteria}

중첩된 프로그램의 스마트 캠페인의 스마트 목록에서 필터링되는 경우, 현재 캐스트 중에는 다음 콘텐츠 조각으로 이동하지 않습니다. *다음* 캐스트에 대한 스트림의 다음 콘텐츠 조각으로 이동합니다.

## 중첩 프로그램에는 무엇이 포함되어 있습니까? {#what-does-a-nested-program-contain}

잘 설계된 중첩 프로그램에는 이메일, 보고서 및 스마트 캠페인이 포함되어 있습니다. 이것들을 함께 보관하는 것이 타당하다.

사용하는 이메일은 프로그램, 다른 프로그램 또는 Design Studio에서도 사용할 수 있습니다. 어디에 사느냐가 어떻게 사용하느냐에 달려 있다.

이메일 위치를 사용하여 변경 사항 보고 따라서, 예를 들어 이메일이 Design Studio에 있는 경우 이메일 성능 보고서에서 모든 지표가 한 행에 표시되고 다른 캐스트가 결합됩니다. 하지만 참여 스트림 성능 보고서에서는 서로 다른 전송이 별도로 표시됩니다.

>[!CAUTION]
>
>다시 보내려면 새 프로그램과 스마트 캠페인을 만드는 것이 가장 안전합니다.

>[!MORELIKETHIS]
>
>* [스트림에 콘텐츠 추가](/help/marketo/product-docs/email-marketing/drip-nurturing/creating-an-engagement-program/add-content-to-a-stream.md)
>* [프로그램 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
