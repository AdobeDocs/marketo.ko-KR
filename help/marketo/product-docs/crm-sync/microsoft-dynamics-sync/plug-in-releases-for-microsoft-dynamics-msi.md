---
unique-page-id: 10099102
description: Microsoft Dynamics MSI용 플러그인 릴리스 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics MSI용 플러그인 릴리스
exl-id: 830f7dc3-07fd-429b-b0fd-290ffdda88e6
source-git-commit: 7b22aec56d15826c1fecd2cf026c561c4df8531c
workflow-type: tm+mt
source-wordcount: '306'
ht-degree: 6%

---

# Microsoft Dynamics MSI용 플러그인 릴리스 {#plug-in-releases-for-microsoft-dynamics-msi}

Microsoft Dynamics에 처음 동기화할 때 Marketo Sales Insight(MSI)용 플러그인의 최신 버전을 다운로드하여 설치합니다. Marketo은 정기적으로 이러한 플러그인을 업데이트하므로 동일한 위치로 돌아가 새 버전을 다운로드할 수 있습니다.

제발 [최신 플러그인 다운로드](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) 해당 섹션을 참조하십시오.

>[!NOTE]
>
>이러한 버전은 Dynamics의 온프레미스 및 온라인 버전 모두에서 작동합니다.

## MSI 솔루션 업그레이드 {#upgrading-your-msi-solution}

1. 솔루션의 최신 버전 가져오기 _기존 버전을 통해_ Dynamics CRM에서 **가져오기** Dynamics에서 단추를 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-1.png)

>[!NOTE]
>
>예: dynamics CRM에 버전 2.0.0.20이 있고 최신 버전이 2.0.0.21인 경우 가져오게 됩니다 _over_ 버전 2.0.0.20.

1. 클릭 **다음**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-2.png)

1. 선택 **업그레이드 단계** 및 **사용자 지정 유지 관리**&#x200B;를 클릭한 다음 **가져오기**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-3.png)

1. 클릭 **다음**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-4.png)

1. 가져오기에 성공하면 두 가지 MSI 솔루션이 표시됩니다. MarketoSalesInsight 및 MarketoSalesInsight_Upgrade입니다. 이전 솔루션을 선택하고 솔루션 업그레이드 적용 을 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-5.png)

그게 다야! 업그레이드 후 MSI 솔루션이 하나만 표시됩니다.

## 버전 업데이트 {#version-updates}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th colspan="1">릴리스 날짜</th> 
   <th colspan="1">버전</th> 
   <th colspan="1">참고</th> 
  </tr> 
  <tr> 
   <td colspan="1">02/03/22</td> 
   <td colspan="1">2.0.0.27</td> 
   <td colspan="1">인사이트에 대한 계정 레이아웃: 흥미로운 순간, 점수 변경 사항, 웹 활동, 이메일 활동</td> 
  </tr>
  <tr> 
   <td colspan="1">01/05/22</td> 
   <td colspan="1">2.0.0.26</td> 
   <td colspan="1">전자 메일 보내기에 대한 프로그램 채택 점수</td> 
  </tr>
  <tr> 
   <td colspan="1">10/28/21</td> 
   <td colspan="1">2.0.0.25</td> 
   <td colspan="1">제품 채택 점수 지표, 새 글로벌 대시보드(웹 활동, 이메일, 최상의 선택)</td> 
  </tr>
  <tr> 
   <td colspan="1">02/10/21</td> 
   <td colspan="1">2.0.0.22</td> 
   <td colspan="1">MSI 솔루션에서 자동 감사 사용 및 설명서 변경 제거</td> 
  </tr>
  <tr> 
   <td colspan="1">10/01/20</td> 
   <td colspan="1">2.0.0.21</td> 
   <td colspan="1">버그 수정: Sales Insight 역할을 가진 사용자를 위해 MSI API 구성 필드에 액세스 할당</td> 
  </tr> 
  <tr> 
   <td colspan="1">07/20/20</td> 
   <td colspan="1">2.0.0.20</td> 
   <td colspan="1">버그 수정: 동기화되지 않은 레코드에 대한 유효성 검사 메시지 추가</td> 
  </tr> 
  <tr> 
   <td colspan="1">06/12/20</td> 
   <td colspan="1">2.0.0.19</td> 
   <td colspan="1">버그 수정: MSD API 구성에서 MSI 암호 숨기기</td> 
  </tr> 
  <tr> 
   <td colspan="1">05/26/20</td> 
   <td colspan="1">2.0.0.18</td> 
   <td colspan="1">버그 수정: MSI 단추를 표시하기 위한 MSI 역할 ID 유효성 검사 변경</td> 
  </tr> 
  <tr> 
   <td colspan="1">05/21/20</td> 
   <td colspan="1">2.0.0.17</td> 
   <td colspan="1">버그 수정: 소유자 필드 숨기기 취소 및 필드 비필수 만들기</td> 
  </tr> 
  <tr> 
   <td colspan="1">04/28/20</td> 
   <td colspan="1">2.0.0.16</td> 
   <td colspan="1">버그 수정: MSD CRM 사이트 맵 설정 링크 종속성을 제거하는 중</td> 
  </tr> 
 </tbody> 
</table>
