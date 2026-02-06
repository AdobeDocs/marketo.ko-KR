---
description: 릴리스 노트 - 2022년 10월 - Marketo 설명서 - 제품 설명서
title: 릴리스 정보 - 2022년 10월
exl-id: 1494b8b9-049c-4969-ab95-a4be41d886b0
feature: Release Information
source-git-commit: 8e72b24e18ae108ec74e6d4fa6b04f10130439a4
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 20%

---

# 릴리스 노트: 2022년 10월 {#release-notes-oct-22}

아래에는 2022년 10월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2022년 10월 14일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능의 상태를 아래에서 확인하십시오.

### 마케팅 데이터 환경 {#marketing-data-environment}

</br>

* **프로그램 구성원 사용자 지정 필드 동기화**: 프로그램 구성원에 대해 캡처된 확장 가능한 필드를 Salesforce의 캠페인 구성원 필드와 양방향 동기화(예: 음식, 세션, 트랙 등과 같은 이벤트 등록 시 참석자 환경 설정)하는 기능.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-field-sync.md">프로그램 멤버 사용자 정의 필드 동기화</a></td>
  </tr>
  </tbody>
</table>

* **Adobe Privacy Service 통합**: Privacy Service과 함께 사용하여 Experience Cloud 제품 전반에 걸친 데이터 개인 정보 보호 규정 준수를 자동화합니다. 현재 이 서비스는 Adobe Identity Management 시스템에 온보딩한 Marketo Engage 고객만 사용할 수 있습니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md">Adobe Identity Management</a></td>
  </tr>
  </tbody>
</table>

### 차세대 경험 {#modern-ux}

</br>

* **차세대 경험에서 업데이트된 Screens**: 전환 스위치를 통해 액세스할 수 있는 업데이트된 디자인 및 유용성 개선 사항을 제공하는 차세대 경험에서 새로 고친 화면을 추가로 제공합니다.

   * 랜딩 페이지 템플릿 세부 정보
   * 이메일 템플릿 목록

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/marketo-engage-modern-ux/toggle-switch.md">토글 스위치</a></td>
  </tr>
  </tbody>
</table>

* **전자 메일 템플릿 세부 정보의 향상된 사용 기능**: 새 경험에서 자산 상태, 마지막 수정자 및 마지막 수정자를 포함하여 전자 메일 템플릿을 사용하는 자산과 관련된 추가 정보를 볼 수 있습니다. 에셋에서 사용하는 목록을 검색, 정렬 및 필터링할 수도 있습니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td>해당 사항 없음</td>
  </tr>
  </tbody>
</table>

* **보고서 에셋 필터 모달**: 구성 메뉴에 새 에셋 트리와 생성 및 수정 날짜 필터를 표시하는 보고서 구성 모달의 새로운 디자인입니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td>해당 사항 없음</td>
  </tr>
  </tbody>
</table>

### API 개선 사항 {#api-enhancements}

</br>

* **일괄 리드 가져오기: 영업 사원 연결**: 일괄 리드 가져오기 프로세스 동안 영업 사원과 리드를 연결할 수 있도록 리드 REST API와 동등하므로 복잡성과 필요한 API 호출 수가 줄어듭니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="https://developer.adobe.com/marketo-apis/api/mapi/#tag/Bulk-Import-Leads">벌크 리드 가져오기</a></td>
  </tr>
  </tbody>
</table>

### Sales Insight {#sales-insight}

</br>

![(별)](assets/yellow-star.png)

* **Dynamic Chat과 Insight 통합**: 이제 Insights Dashboard에 주별 요약 및 세부 사항 카드와 함께 스마트 그리드의 Dynamic Chat 활동이 포함됩니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md">Dynamic Chat 통합</a></td>
  </tr>
  </tbody>
</table>

## 애자일 릴리스 기능

다음 기능은 애자일 형식을 따르며, 표준 릴리스 날짜 이전 또는 이후의 다양한 날짜에 릴리스됩니다. 각 기능의 상태를 아래에서 확인하십시오.

* **Dynamic Chat용 자동 정렬 대화 상자 스트림**: [자동 정렬]을 통해 단추를 눌러 캔버스의 모든 내용을 깔끔하고 읽기 쉬운 형식으로 구성하여 복잡한 대화 상자 캔버스를 개선합니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/stream-designer.md#stream-designer-icons">스트림 Designer 아이콘</a></td>
  </tr>
  </tbody>
</table>

* **Dynamic Chat의 모임 링크**: 방문자에게 보내는 모든 일정 초대에 Google 및 Outlook의 팀 또는 모임 링크를 자동으로 포함하는 옵션입니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/agent-settings.md">캘린더</a></td>
  </tr>
  </tbody>
</table>

* **Dynamic Chat에 대한 추가 데이터 형식 지원**: 3개의 새로운 데이터 형식(부울, 정수, 부동 소수점)을 사용하면 점수를 기반으로 타깃팅하거나 방문자에게 예/아니요 질문을 하는 것과 같은 작업에 대해 Dynamic Chat의 더 많은 기존 Marketo Engage 필드를 활용할 수 있습니다.

<table>
  <tr>
   <td><b>상태</b></td>
   <td><b>설명서 업데이트</b></td>
  </tr>
  <tr>
   <td>릴리스됨</td>
   <td>해당 사항 없음</td>
  </tr>
  </tbody>
</table>

## 공지 {#announcements}

* **Forms 1.0**: 10월 릴리스를 통해 Forms 1.0의 사용이 중단됩니다. Forms 1.0 Assets는 더 이상 Marketo Engage에 데이터를 제출할 수 없으며 시도하면 오류를 반환합니다.

* **스크립트가 없는 Forms**: 브라우저에서 Javascript가 비활성화되어 있으면 Forms이 더 이상 작동하지 않습니다. 양식 제출을 사용하려면 Javascript를 활성화해야 합니다.
