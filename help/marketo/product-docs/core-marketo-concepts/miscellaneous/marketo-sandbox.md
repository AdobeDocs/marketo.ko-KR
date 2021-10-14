---
unique-page-id: 11386358
description: Marketo Sandbox - Marketo 문서 - 제품 설명서
title: Marketo 샌드박스
exl-id: c040fac6-2290-4de5-b27d-2c7cb28f6e30
source-git-commit: 84a285974de3bbcdf33e24befae323d3d82ef239
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Marketo 샌드박스 {#marketo-sandbox}

Marketo 샌드박스는 프로덕션 환경에서 구현하기 전에 테스트 목적으로 사용되는 추가 인스턴스입니다.

>[!AVAILABILITY]
>
>모든 고객이 이 기능을 구입한 것은 아닙니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

Marketo 샌드박스가 프로덕션 인스턴스에 이미 동기화된 경우 일반 CRM에 동기화할 수 없습니다. 동기화에 CRM의 샌드박스를 사용하고 원래 동기화와 동일한 단계를 모두 수행합니다.

## 샌드박스에 대해 알아야 할 사항 {#things-to-know-about-sandboxes}

* Customer Success Manager가 샌드박스를 설정하고 초대를 전송하면 Marketo 프로덕션 인스턴스와 다른 이메일 주소를 사용하여 로그인해야 합니다.
* 사용자를 추가하려면 이 프로세스는 프로덕션](/help/marketo/product-docs/administration/users-and-roles/managing-marketo-users.md#create-users)에서 사용자를 추가하는 것과 같습니다. [ 또한 이미 Marketo 로그인이 있는 경우 다른 이메일 주소를 사용해야 합니다.
* Marketo 샌드박스는 빈 상태로 시작되지만 프로덕션 인스턴스와 동일한 기능을 사용할 수 있습니다.
* 샌드박스에서 프로그램을 만들어 프로덕션으로 이동하려는 경우 [프로그램 가져오기](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md)를 수행할 수 있습니다.
* 샌드박스는 조절되므로 프로덕션 인스턴스가 테스트 환경의 영향을 받지 않습니다. 캠페인 실행당 최대 20개의 이메일을 보낼 수 있습니다.

>[!CAUTION]
>
>현재 Marketo Dynamics Sync에 대한 샌드박스 새로 고침을 지원하지 않습니다. Dynamics CRM 샌드박스를 새로 고쳐야 하는 경우 새 Marketo 샌드박스가 필요합니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

## 인스턴스 복사 {#instance-copy}

샌드박스를 채울 일회성 인스턴스 복사본을 요청하는 지원 사례를 제출할 수 있습니다. 그러나 인스턴스 복사본은 _모든_&#x200B;을 가져오지 않습니다. 자세한 내용은 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)을 참조하십시오.

>[!NOTE]
>
>* 소스 인스턴스가 Microsoft Dynamics와 통합된 경우 인스턴스 복사본이 지원되지 않는 **입니다.**
>* 기본 CRM을 변경하는 경우 새 Marketo 인스턴스가 필요하므로 새 Marketo 인스턴스에 대한 인스턴스 사본은 허용되지 않습니다. 대신 Marketo 지원 을 통해 프로그램 가져오기 기능을 살펴보십시오.

