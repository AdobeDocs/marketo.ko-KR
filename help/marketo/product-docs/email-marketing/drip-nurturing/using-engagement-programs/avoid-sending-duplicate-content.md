---
unique-page-id: 10096409
description: 참여 프로그램에서 중복 이메일을 방지하거나 허용하는 시나리오에 대해 알아봅니다. 프로그램 멤버십 및 CEE 규칙을 사용하여 반복을 방지하십시오.
title: 중복 콘텐츠 전송 방지
exl-id: fd7118e8-6e34-4973-8aa5-effb774447fd
feature: Engagement Programs
TQID: https://experienceleague.adobe.com/vJ0HguG6ad182v-Jkf-0DF6zAosaJG5B-me3ghxnYIM
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
source-git-commit: 39b6fecdc7aa16ab1205582d3bf372a8538a2d35
workflow-type: tm+mt
source-wordcount: 209
ht-degree: 7%

---

# 중복 콘텐츠 전송 방지 {#avoid-sending-duplicate-content}

다음은 참여 프로그램과 함께 동일한 메시지를 두 번 보내지 못하도록 해야 하는 7가지 가능한 시나리오와 결과입니다.

## 시나리오 {#scenarios}

| 이메일이 다음에서 전송됨: | 대상이 다음과 같음 | 개인 이메일 수신 |
|---|---|---|
| 별도의 독립 실행형 기본 프로그램의 캠페인 | 기본 프로그램의 구성원이 아님 | 예 |
| 별도의 독립 실행형 기본 프로그램의 캠페인 | 기본 프로그램의 구성원 | 아니요 |
| **same** CEE 프로그램 내의 캐스팅에서 트리거되는 기본 프로그램 내의 캠페인 | 기본 프로그램의 구성원 | 아니요 |
| **same** CEE 프로그램 내의 캐스팅에서 트리거되는 기본 프로그램 내의 캠페인 | 기본 프로그램의 구성원이 아님 | 예 |
| **다른** CEE 프로그램 내의 캐스팅에서 트리거되는 기본 프로그램 내의 캠페인 | 기본 프로그램의 구성원 | 아니요 |
| **다른** CEE 프로그램 내의 캐스팅에서 트리거되는 기본 프로그램 내의 캠페인 | 기본 프로그램의 구성원이 아님 | 예 |
| 스마트 스트림을 사용하는 **다른** CEE 프로그램 | 두 CEE 프로그램의 멤버 | 아니요 |
