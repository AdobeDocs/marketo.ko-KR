---
unique-page-id: 10099102
description: Microsoft Dynamics MSI용 플러그인 릴리스 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics MSI용 플러그인 릴리스
exl-id: 830f7dc3-07fd-429b-b0fd-290ffdda88e6
feature: Microsoft Dynamics
source-git-commit: 6dcda9b86555c17b3492a02f3985db7d2acd8a32
workflow-type: tm+mt
source-wordcount: '400'
ht-degree: 0%

---

# Microsoft Dynamics MSI용 플러그인 릴리스 {#plug-in-releases-for-microsoft-dynamics-msi}

Microsoft Dynamics에 처음 동기화하면 Marketo Sales Insight(MSI)의 최신 버전의 플러그인을 다운로드하여 설치합니다. Marketo Engage은 이러한 플러그인을 정기적으로 업데이트하므로 동일한 위치로 돌아가서 새 버전을 다운로드할 수 있습니다.

Dynamics에 대한 Marketo 기본 CRM 동기화 솔루션을 사용하는 경우 [최신 플러그인 다운로드](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md){target="_blank"} corresponding to your Dynamics release. For those who have a custom sync and have purchased Marketo Sales Insight, the [package is here](https://mktg-cdn.marketo.com/community/MarketoSalesInsight_NonNative.zip){target="_blank"}.

>[!NOTE]
>
>이러한 버전은 Dynamics의 온-프레미스 및 온라인 버전 모두에 대해 작동합니다.

## MSI 솔루션 업그레이드 {#upgrading-your-msi-solution}

1. 최신 버전의 솔루션 가져오기 _기존 버전 이상_ 을 눌러 Dynamics CRM의 **[!UICONTROL 가져오기]** dynamics의 단추입니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-1.png)

>[!NOTE]
>
>예: Dynamics CRM의 버전이 2.0.0.20이고 최신 버전이 2.0.0.21인 경우 다음을 가져옵니다. _초과_ 버전 2.0.0.20.

1. 클릭 **[!UICONTROL 다음]**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-2.png)

1. 선택 **[!UICONTROL 업그레이드 단계]** 및 **[!UICONTROL 사용자 지정 유지]**&#x200B;을 클릭한 다음 을 클릭합니다 **[!UICONTROL 가져오기]**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-3.png)

1. 클릭 **[!UICONTROL 다음]**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-4.png)

1. 가져오기에 성공하면 MarketoSalesInsight 및 MarketoSalesInsight_Upgrade 의 두 가지 MSI 솔루션이 표시됩니다. 이전 솔루션을 선택하고 솔루션 업그레이드 적용 을 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-5.png)

다 됐습니다! 업그레이드 후에는 하나의 MSI 솔루션만 표시됩니다.

## 버전 업데이트 {#version-updates}

<table> 
 <tbody> 
  <tr> 
   <th>릴리스 날짜</th> 
   <th>버전</th> 
   <th>참고 사항</th> 
  </tr>
  <tr> 
   <td>202/14/24</td> 
   <td>2.00.31</td> 
   <td>익명 웹 활동의 페이지 매김에 대한 변경 사항입니다.
   <p>
   사용자 보기에서 암호 키 정보. 암호화를 수행하려면 새 패키지를 가져온 후 암호를 변경해야 합니다.</td> 
  </tr>
  <tr> 
   <td>10/18/23</td> 
   <td>2.00.30</td> 
   <td>MSI 오류 로그를 통합하고 Marketo 오류 엔티티에 표시되는 정보 알림을 제거하는 중입니다.</td> 
  </tr>
  <tr> 
   <td>05/19/23</td> 
   <td>2.00.29</td> 
   <td>전역 대시보드의 웹 활동 및 관심 순간 페이지 매김 문제를 수정했습니다.</td> 
  </tr>
  <tr> 
   <td>03/23/23</td> 
   <td>2.00.28</td> 
   <td>이(가) 다음을 생성함: <a href="https://mktg-cdn.marketo.com/community/MarketoSalesInsight_NonNative.zip">새 패키지</a> CRM에 기본 연결이 아닌 연결용 MSI의 경우.</td> 
  </tr>
  <tr> 
   <td>02/03/22</td> 
   <td>2.0.0.27</td> 
   <td>인사이트를 위한 계정 레이아웃: 즐거운 순간, 점수 변경, 웹 활동, 이메일 활동.</td> 
  </tr>
  <tr> 
   <td>01/05/22</td> 
   <td>2.0.0.26</td> 
   <td>이메일 전송에 대한 프로그램 채택 점수.</td> 
  </tr>
  <tr> 
   <td>10/28/21</td> 
   <td>2.0.0.25</td> 
   <td>제품 채택 점수 지표, 새 글로벌 대시보드(웹 활동, 이메일, 최상의 선택).</td> 
  </tr>
  <tr> 
   <td>21/02/10</td> 
   <td>2.0.0.22</td> 
   <td>MSI 솔루션에서 자동 감사 활성화 및 설명서 변경 내용을 제거합니다.</td> 
  </tr>
  <tr> 
   <td>10/01/20</td> 
   <td>2.0.0.21</td> 
   <td>버그 수정: Sales Insight 역할이 있는 사용자의 MSI API 구성 필드에 대한 액세스 권한을 할당합니다.</td> 
  </tr> 
  <tr> 
   <td>20/07/20</td> 
   <td>2.0.0.20</td> 
   <td>버그 수정: 동기화되지 않은 레코드에 대한 유효성 검사 메시지를 추가합니다.</td> 
  </tr> 
  <tr> 
   <td>2020년 6월 12일</td> 
   <td>2.0.0.19</td> 
   <td>버그 수정: MSD API 구성에서 MSI 암호 를 숨깁니다.</td> 
  </tr> 
  <tr> 
   <td>20/05/26</td> 
   <td>2.0.0.18</td> 
   <td>버그 수정: MSI 단추 표시에 대한 MSI 역할 ID 유효성 검사를 변경합니다.</td> 
  </tr> 
  <tr> 
   <td>20/05/21</td> 
   <td>2.0.0.17</td> 
   <td>버그 수정: 소유자 필드 숨김을 해제하고 필드를 필수가 아니도록 설정합니다.</td> 
  </tr> 
  <tr> 
   <td>20/04/28</td> 
   <td>2.0.0.16</td> 
   <td>버그 수정: MSD CRM 사이트 맵 설정 링크 종속성을 제거하는 중입니다.</td> 
  </tr> 
 </tbody> 
</table>
