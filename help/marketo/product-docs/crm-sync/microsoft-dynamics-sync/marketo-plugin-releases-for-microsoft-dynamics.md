---
unique-page-id: 10099389
description: Microsoft Dynamics용 Marketo 플러그인 릴리스 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics용 Marketo 플러그인 릴리스
exl-id: c9c25e11-bcf7-49bf-920a-4182af27d278
feature: Microsoft Dynamics
source-git-commit: f1fd9564abe4702c3a124442ee26027d4d22f23d
workflow-type: tm+mt
source-wordcount: '474'
ht-degree: 0%

---

# Microsoft Dynamics용 Marketo 플러그인 릴리스 {#marketo-plugin-releases-for-microsoft-dynamics}

Microsoft Dynamics에 처음 동기화하면 Marketo용 플러그인의 최신 버전을 다운로드합니다. Marketo은 이러한 플러그인을 정기적으로 업데이트하므로 동일한 위치로 돌아가서 새 버전을 다운로드할 수 있습니다.

Dynamics 릴리스에 해당하는 [최신 플러그인을 다운로드합니다](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}.

![](assets/marketo-plugin-releases-for-microsoft-dynamics-1.png)

## Dynamics 솔루션 업데이트 {#updating-your-dynamics-solution}

1. 기존 버전의 Dynamics CRM을 통해 최신 버전의 솔루션을 가져옵니다(예: Dynamics CRM에 버전 1.4가 있고 최신 버전이 1.5인 경우 _over_ 버전 1.4를 가져옵니다).

1. 다음 팝업이 표시됩니다. **업데이트** 및 **사용자 지정 유지 관리**&#x200B;를 선택한 다음 **가져오기**&#x200B;를 클릭합니다.

![](assets/marketo-plugin-releases-for-microsoft-dynamics-2.png)

## 최신 버전 {#latest-versions}

>[!NOTE]
>
>이러한 버전은 Dynamics의 온-프레미스 및 온라인 버전 모두에 대해 작동합니다.

<table> 
 <tbody> 
  <tr> 
   <th style="width:15%">버전</th> 
   <th style="width:20%">릴리스 날짜</th> 
   <th style="width:65%">참고 사항</th> 
  </tr>
  <tr> 
   <td>5.0.2.1</td> 
   <td>1/19/24</td> 
   <td>버그 수정: 사용자 지정 엔티티 동기화와 관련된 버그가 수정되었습니다.</td> 
  </tr> 
  <tr> 
   <td>5.0.2.0</td> 
   <td>03/24/23</td> 
   <td>버그 수정: MS Dynamics에서 연락처를 병합하지 못하는 버그를 수정했습니다.</td> 
  </tr> 
  <tr> 
   <td>5.0.1.8</td> 
   <td>03/27/23</td> 
   <td>버그 수정: 플러그인이 MS Dynamics의 UI 요소에서 다른 사용자 지정을 덮어쓰지 않도록 합니다.
   <p>
   버그 수정: 5.0.1.1에서 누락된 탐색 타일을 복원했습니다.</td> 
  </tr> 
  <tr> 
   <td>5.0.1.1</td> 
   <td>202/04/21</td> 
   <td>다중 선택 옵션 집합 필드 동기화 지원(이 기능은 V9.X 이상에서만 사용 가능).</td> 
  </tr> 
  <tr> 
   <td>4.2.0.0</td> 
   <td>10/16/20</td> 
   <td>MS Dynamics와의 Campaign 동기화에 대한 지원을 추가했습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.24</td> 
   <td>8/22/18</td> 
   <td>Microsoft Dynamics 버전 9.x에 대한 연락 프로세스를 위한 기본 검증 리드에 대한 지원을 추가했습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.23</td> 
   <td>6/27/18</td> 
   <td>버그 수정: Dynamics 2013용 Marketo 솔루션을 설치하는 동안 비즈니스 프로세스 오류가 발생했습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.22</td> 
   <td>9/29/17</td> 
   <td>버그 수정: 내부 수정.</td> 
  </tr> 
  <tr> 
   <td><p>4.0.0.21</p></td> 
   <td>11/9/16</td> 
   <td>버그 수정: 플러그인이 사용자 지정 개체의 상태 변경을 캡처하는 이벤트를 구독하지 않았습니다. 이 수정 사항은 Dynamics CRM On Premise 2011에만 해당됩니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.20</td> 
   <td>7/22/16</td> 
   <td>버그 수정: 영업 기회 연락처 역할의 업데이트가 완전히 캡처되지 않았습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.19</td> 
   <td>6/28/16</td> 
   <td>버그 수정: 영업 기회를 만들 때 marketo 로그의 customeropportunityrole에 대한 불필요한 업데이트 트랜잭션이 기록되었습니다.<p>버그 수정: customeropportunityrole 엔티티를 삭제할 때 추가 삭제 트랜잭션이 기록되었습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.18</td> 
   <td>5/31/16</td> 
   <td>버그 수정: 사용자 지정 개체의 업데이트 및 삭제를 비동기식으로 했습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.17</td> 
   <td>4/8/16</td> 
   <td>버그 수정: 잠재 고객에 동기화 필터가 NO로 설정되어 있고 영업 기회 및 연락처에 동기화 필터가 없는 경우 잠재 고객이 자격이 되었을 때 연락처 및 영업 기회에 대한 만들기 로그가 생성되지 않았습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.16</td> 
   <td>3/29/16</td> 
   <td>버그 수정: 동기화 필터가 꺼져 있을 때 할당 이벤트가 기록되었습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.15</td> 
   <td>3/3/16</td> 
   <td>버그 수정: 로그인 사용자에게 Marketo 구성 권한이 없기 때문에 고객이 CRM에서 리드를 만들 수 없습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.14</td> 
   <td>1/18/16</td> 
   <td>버그 수정: 일반 Dynamics 사용자가 보안 문제를 해결할 수 있도록 액세스 제한을 만들었습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.13</td> 
   <td>12/30/15</td> 
   <td>버그 수정: Dynamics의 업데이트가 단계 및 이미지에 대해 Marketo과 동기화되지 않았습니다.</td> 
  </tr> 
  <tr> 
   <td>4.0.0.12</td> 
   <td>11/12/15</td> 
   <td>버그 수정: 동기화 필터가 false로 설정되었을 때 잠재 고객 레코드가 Marketo으로 동기화되었습니다.</td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[Marketo 리드 관리 솔루션 다운로드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}
