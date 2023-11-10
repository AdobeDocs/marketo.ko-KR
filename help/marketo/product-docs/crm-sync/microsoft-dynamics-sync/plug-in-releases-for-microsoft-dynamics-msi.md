---
unique-page-id: 10099102
description: Microsoft Dynamics MSI용 플러그인 릴리스 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics MSI용 플러그인 릴리스
exl-id: 830f7dc3-07fd-429b-b0fd-290ffdda88e6
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 8%

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

1. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-2.png)

1. 선택 **[!UICONTROL 업그레이드 단계]** 및 **[!UICONTROL 사용자 지정 유지]**&#x200B;을 클릭한 다음 을 클릭합니다 **[!UICONTROL 가져오기]**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-3.png)

1. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-4.png)

1. 가져오기에 성공하면 MarketoSalesInsight 및 MarketoSalesInsight_Upgrade 의 두 가지 MSI 솔루션이 표시됩니다. 이전 솔루션을 선택하고 솔루션 업그레이드 적용 을 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-5.png)

다 됐습니다! 업그레이드 후에는 하나의 MSI 솔루션만 표시됩니다.

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
   <th colspan="1">참고 사항</th> 
  </tr> 
  <tr> 
   <td colspan="1">02/03/22</td> 
   <td colspan="1">2.0.0.27</td> 
   <td colspan="1">인사이트를 위한 계정 레이아웃: 즐거운 순간, 점수 변경, 웹 활동, 이메일 활동</td> 
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
   <td colspan="1">MSI 솔루션에서 자동 감사 사용 및 설명서 변경 내용 제거</td> 
  </tr>
  <tr> 
   <td colspan="1">10/01/20</td> 
   <td colspan="1">2.0.0.21</td> 
   <td colspan="1">버그 수정: Sales Insight 역할이 있는 사용자의 MSI API 구성 필드에 액세스 할당</td> 
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
   <td colspan="1">버그 수정: MSI 단추 표시에 대한 MSI 역할 ID 유효성 검사를 변경하려면</td> 
  </tr> 
  <tr> 
   <td colspan="1">05/21/20</td> 
   <td colspan="1">2.0.0.17</td> 
   <td colspan="1">버그 수정: 소유자 필드 숨기기 취소 및 필드를 필수가 아님</td> 
  </tr> 
  <tr> 
   <td colspan="1">04/28/20</td> 
   <td colspan="1">2.0.0.16</td> 
   <td colspan="1">버그 수정: MSD CRM 사이트 맵 설정 링크 종속성 제거</td> 
  </tr> 
 </tbody> 
</table>
