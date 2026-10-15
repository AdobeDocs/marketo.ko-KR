---
description: 최신 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
hide: true
feature: Release Information
exl-id: 0ca5e844-c30b-4c86-a23d-d8f2c1bdddf5
TQID: 'https://experienceleague.adobe.com/RZsCx9HAyJuDLO46WfshT30be-rMMDZjnygvU32NGfk'
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: c942e9f6-ed06-481a-abdd-1195363d1452
    internal-label: Dynamic Chat
  - id: af97ce94-35fa-4fa9-b85a-46b752ac4028
    internal-label: Release information
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
source-git-commit: 9eb8c0e78a581bc9093f0f017a3ad3525d2b9667
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 18%
---
# 릴리스 노트: 2026년 10월 {#release-notes-oct-26}

아래에는 2026년 10월 릴리스에 포함된 모든 기능이 있습니다. 기능 사용 가능 여부는 Adobe Marketo Engage 에디션에서 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하며 **2026년 10월 23일**&#x200B;에 릴리스되기 시작합니다. 이후 몇 주 동안 나머지 기능은 단계적으로 롤아웃됩니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인하십시오.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>이 프로그램/폴더에 복제</strong>: 이제 Marketo Engage의 복제 작업은 복제된 자산의 대상을 선택할 때 첫 번째 선택으로 "이 폴더" 또는 "이 프로그램" 옵션을 일관되게 제공합니다. 이 옵션을 선택하면 에셋이 현재 에셋의 상위 프로그램 또는 폴더로 복제됩니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <tr>
   <td><strong>CRM 동기화에 대한 즉각적인 경고</strong>: 이제 환경에 대한 기본 CRM 동기화를 사용하거나 사용하지 않도록 설정하면 CRM 알림 채널을 구독하는 사용자에게 알림이 트리거됩니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **웹에서 Grab 이미지 사용 중단**: 최신 보안 및 개인 정보 보호 모범 사례를 준수하기 위해 [웹에서 Grab 이미지 사용 중단](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/demand-generation/images-and-files/grab-the-images-from-a-web-page){target="_blank"} 기능은 10월 릴리스부터 더 이상 사용되지 않습니다.

* **사용자 지정 활동 특성에 대한 API 이름 제한**: 이제 API 또는 UI를 통해 만든 사용자 지정 활동 특성에 대한 API 이름에는 영숫자와 밑줄만 포함될 수 있으며 영숫자로 시작해야 합니다.

* **잠재 고객 활동 가져오기 및 잠재 고객 변경 가져오기**: 2026년 9월 30일부터 대상 목록에 10,000개 이상의 잠재 고객이 포함된 경우 `listId` 매개 변수를 포함하는 잠재 고객 가져오기 활동 또는 잠재 고객 변경 가져오기 엔드포인트에 대한 호출이 1003 오류 코드(대상 정적 목록에 레코드가 너무 많음을 나타냄)로 실패하기 시작했습니다. 자세한 내용은 [마이그레이션 안내서](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"}를 참조하십시오.
