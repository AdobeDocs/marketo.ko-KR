---
unique-page-id: 10099102
description: ' [!DNL Microsoft Dynamics] MSI용 플러그인 릴리스 - Marketo 문서 - 제품 설명서'
title: ' [!DNL Microsoft Dynamics] MSI용 플러그인 릴리스'
exl-id: 830f7dc3-07fd-429b-b0fd-290ffdda88e6
feature: Microsoft Dynamics
source-git-commit: 6fb25aab33dfc0f6792950a7d5d802a9e4be8303
workflow-type: tm+mt
source-wordcount: '433'
ht-degree: 1%

---

# [!DNL Microsoft Dynamics] MSI의 플러그인 릴리스 {#plug-in-releases-for-microsoft-dynamics-msi}

[!DNL Microsoft Dynamics]에 처음 동기화하면 최신 버전의 Marketo Sales Insight(MSI)용 플러그인을 다운로드하여 설치합니다. Marketo은 이러한 플러그인을 정기적으로 업데이트하므로 동일한 위치로 돌아가서 새 버전을 다운로드할 수 있습니다.

Marketo의 기본 CRM 동기화 솔루션을 [!DNL Dynamics]에 사용하는 경우 [&#x200B; 릴리스에 해당하는 &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md){target="_blank"}최신 플러그인을 다운로드[!DNL Dynamics]하십시오. 사용자 지정 동기화가 있고 Marketo Sales Insight을 구입한 사용자의 경우 [패키지가 여기에 있습니다](https://mktg-cdn.marketo.com/community/MarketoSalesInsight_NonNative.zip){target="_blank"}.

>[!NOTE]
>
>이 버전은 [!DNL Dynamics]의 온-프레미스 및 온라인 버전에서 모두 사용할 수 있습니다.

## MSI 솔루션 업그레이드 {#upgrading-your-msi-solution}

1. _의_ 단추를 눌러 [!DNL Dynamics] CRM의 기존 버전&#x200B;**[!UICONTROL Import]**&#x200B;에서 최신 버전의 솔루션을 [!DNL Dynamics]가져옵니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-1.png)

>[!NOTE]
>
>예: [!DNL Dynamics] CRM의 버전이 2.0.0.20이고 최신 버전이 2.0.0.21인 경우 _over_ 버전 2.0.0.20을(를) 가져옵니다.

1. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-2.png)

1. **[!UICONTROL Stage for Upgrade]** 및 **[!UICONTROL Maintain customizations]**&#x200B;을(를) 선택한 다음 **[!UICONTROL Import]**&#x200B;을(를) 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-3.png)

1. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-4.png)

1. 가져오기에 성공하면 MarketoSalesInsight 및 MarketoSalesInsight_Upgrade 의 두 가지 MSI 솔루션이 표시됩니다. 이전 솔루션을 선택하고 솔루션 업그레이드 적용 을 클릭합니다.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-5.png)

다 됐습니다! 업그레이드 후에는 하나의 MSI 솔루션만 표시됩니다.

## 버전 업데이트 {#version-updates}

<table>
 <tbody>
  <tr>
   <th>릴리스 일자</th>
   <th>버전</th>
   <th>참고</th>
  </tr>
  <tr>
   <td>202/14/24</td>
   <td>2.00.31</td>
   <td>익명 웹 활동의 페이지 매김에 대한 변경 사항입니다.
   <p>
   사용자 보기에서 암호 키 정보. 암호화를 수행하려면 새 패키지를 가져온 후 암호를 변경해야 합니다.
   <p>
   Dynamics용 MSI 플러그인을 업데이트할 때 새 패키지가 설치될 때 액세스 권한이 발생하지 않도록 새로 고침 형식으로 SOAP API 비밀 키와 MSI 자격 증명을 모두 업데이트하는 것이 좋습니다.</td>
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
   <td>CRM에 기본 연결이 아닌 연결을 위해 MSI용 <a href="https://mktg-cdn.marketo.com/community/MarketoSalesInsight_NonNative.zip">새 패키지</a>를 만들었습니다.</td>
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
