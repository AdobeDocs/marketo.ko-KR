---
unique-page-id: 11386358
description: 프로덕션 전 테스트를 위한 Marketo Engage 샌드박스에 대해 알아봅니다. 샌드박스 인스턴스를 사용하여 프로덕션에 영향을 주지 않고 테스트합니다.
title: Marketo Sandbox
exl-id: c040fac6-2290-4de5-b27d-2c7cb28f6e30
TQID: https://experienceleague.adobe.com/Cb1H0PKG-G0c4FkIcjI-erNzR0dwRtj7TwfqtwhFFMI
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 306
ht-degree: 3%

---

# Marketo Sandbox {#marketo-sandbox}

Marketo Engage 샌드박스는 프로덕션 환경에서 구현하기 전에 테스트 목적으로 사용되는 추가 인스턴스입니다.

>[!AVAILABILITY]
>
>모든 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

Marketo 샌드박스가 프로덕션 인스턴스에 이미 동기화된 경우 일반 CRM에 동기화할 수 없습니다. 동기화에 CRM의 샌드박스를 사용하고 원본 동기화와 동일한 단계를 모두 따릅니다.

## 샌드박스에 대해 알아야 할 사항 {#things-to-know-about-sandboxes}

* 사용자를 추가하려면 프로세스는 [프로덕션에서 사용자를 추가](/help/marketo/product-docs/administration/users-and-roles/add-or-remove-a-user.md#add-a-user)하는 것과 같습니다. 또한 Marketo 로그인이 이미 있는 경우 다른 이메일 주소를 사용해야 합니다.
* Marketo 샌드박스는 비어 있지만 프로덕션 인스턴스와 동일한 기능을 사용할 수 있습니다.
* 샌드박스에서 프로그램을 만들어 프로덕션으로 이동하려면 [프로그램 가져오기](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md)를 수행할 수 있습니다.
* 샌드박스가 제한되므로 프로덕션 인스턴스가 테스트 환경의 영향을 받지 않습니다. 캠페인 실행당 최대 20개의 이메일을 보낼 수 있습니다.

>[!CAUTION]
>
>Marketo Dynamics _또는_ Salesforce 동기화에 대한 샌드박스 새로 고침은 현재 지원되지 않습니다. CRM 샌드박스를 새로 고쳐야 하는 경우 새 Marketo 샌드박스가 필요합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

## 인스턴스 복사 {#instance-copy}

샌드박스를 채울 일회성 인스턴스 사본을 요청하는 지원 사례를 제출할 수 있습니다. 그러나 인스턴스 복사는 _모든 항목_&#x200B;을 가져오지 않습니다. 자세한 내용은 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하십시오.

>[!NOTE]
>
>기본 CRM을 변경하는 경우 새 Marketo 인스턴스가 필요하며 새 Marketo 인스턴스에 대한 인스턴스 복사가 불가능합니다. 대신 Marketo 지원 팀과 함께 프로그램 가져오기 기능을 살펴보십시오.
