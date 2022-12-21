---
unique-page-id: 10098134
description: 참여 프로그램 스트림에 프로그램 추가 - Marketo 문서 - 제품 설명서
title: 참여 프로그램 스트림에 프로그램 추가
exl-id: 44c2ce45-439b-4b29-8130-8cc218e04bbf
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '461'
ht-degree: 0%

---

# 참여 프로그램 스트림에 프로그램 추가 {#adding-a-program-to-an-engagement-program-stream}

## 참여 프로그램 스트림에 중첩된 프로그램을 사용하는 이유는 무엇입니까? {#why-use-a-nested-program-in-an-engagement-program-stream}

참여 프로그램의 스트림에 이메일을 추가하는 것이 쉬우며 잘 작동합니다. 그러나 비즈니스 요구 사항이 더 복잡하면 프로그램 내에 이메일을 배치하는 것이 적절할 수 있습니다. 예를 들어 다음 작업을 수행할 수 있습니다.

* 스트림의 사람 하위 그룹에 이메일 보내기
* 보내기 *different* 스트림 내의 하위 그룹에 전자 메일 보내기
* 육성에는 랜딩 페이지, 양식 또는 기타 자산을 포함합니다
* 다중 터치 속성 활성화
* 경고 이메일과 같은 추가 흐름 단계 추가

## 스트림에서 프로그램을 사용하면 어떻게 됩니까? {#what-happens-when-you-use-a-program-in-a-stream}

중첩된 프로그램을 사용할 때 개인에게 이메일을 보내는 결정은 프로그램 멤버십과 프로그램 ID를 기반으로 합니다.

* 프로그램의 구성원이 아닌 경우 프로그램에 포함된 모든 이메일을 한 번 받게 됩니다
* 프로그램의 회원인 경우 이메일을 받지 못합니다
* 더 이상 구성원이 아니지만 해당 프로그램을 통해 이전에 이메일을 받은 경우 이메일을 받지 못합니다

스트림에서 프로그램을 사용하는 경우 해당 특정 이메일을 수신했는지 여부는 중요하지 않습니다. 이메일이 전에 전송되지 않은 한 *특정 프로그램*&#x200B;다시 받을 수 있습니다.

참여 프로그램에서 이메일과 프로그램을 교묘하게 혼합할 수 있습니다. 하나 또는 다른 하나를 사용할 수 있습니다.

>[!TIP]
>
>를 사용해야 합니다. **참여 프로그램 구성원** 스마트 목록에 필터링합니다.

## 스마트 목록 기준을 충족하지 않는 사용자는 어떻게 됩니까? {#what-happens-to-people-who-dont-meet-the-smart-list-criteria}

중첩된 프로그램의 스마트 캠페인의 스마트 목록에서 필터링된 경우 현재 캐스트 중에 다음 콘텐츠 부분으로 이동하지 않습니다. 그러면 를 위해 스트림의 다음 컨텐츠 조각으로 이동합니다 *다음* 캐스트.

## 중첩 프로그램에는 어떤 내용이 포함됩니까? {#what-does-a-nested-program-contain}

이메일, 보고서 및 스마트 캠페인이 잘 디자인된 중첩 프로그램입니다. 이것들을 함께 유지하는 것이 이치에 맞는다.

사용하는 이메일은 프로그램, 다른 프로그램 또는 Design Studio에서도 사용할 수 있습니다. 어디에 사느냐에 따라 어떻게 사용할지에 따라 다릅니다.

전자 메일 위치를 사용하여 변경 사항을 보고합니다. 따라서 전자 메일이 Design Studio의 경우 전자 메일 성과 보고서에서 모든 지표가 한 줄로 표시되며 다른 캐스트가 결합됩니다. 그러나 참여 스트림 성과 보고서에서 다른 전송은 별도로 표시됩니다.

>[!CAUTION]
>
>무언가를 재전송하고 싶다면, 새로운 프로그램과 스마트 캠페인을 만드는 것이 가장 안전합니다.

>[!MORELIKETHIS]
>
>* [스트림에 컨텐츠 추가](/help/marketo/product-docs/email-marketing/drip-nurturing/creating-an-engagement-program/add-content-to-a-stream.md)
>* [프로그램 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)

