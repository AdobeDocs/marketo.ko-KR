---
description: Salesforce Lightning 사용자 지정 패키지 제거 - Marketo 문서 - 제품 설명서
title: Salesforce Lightning 사용자 지정 패키지 제거
exl-id: 4af89222-22b1-4c08-8081-3dab89d1985b
feature: Sales Insight Actions
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '993'
ht-degree: 11%

---

# [!DNL Salesforce Lightning] 사용자 지정 패키지 제거 {#uninstall-salesforce-lightning-customization-package}

MSI 작업 패키지 사용을 시작하면 [!DNL Sales Connect] 계정에서 Marketo [!DNL Salesforce] 패키지를 제거합니다.

## 페이지 레이아웃에서 [!DNL Sales Connect]개 필드 제거 {#remove-sales-connect-fields-from-page-layout}

1. [!DNL Salesforce Lightning]에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Setup]**&#x200B;을(를) 선택합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-1.png)

1. **[!UICONTROL Object Manager]**&#x200B;을(를) 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-2.png)

1. 아래로 스크롤하여 **[!UICONTROL Lead]**&#x200B;을(를) 선택합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-3.png)

1. **[!UICONTROL Page Layouts]**&#x200B;을(를) 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-4.png)

1. **[!UICONTROL Lead Layout]**&#x200B;을(를) 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-5.png)

   >[!NOTE]
   >
   >[!DNL Salesforce Lightning]에서 페이지 레이아웃 편집 보기가 아직 업데이트되지 않았습니다.

1. 콘솔에서 **[!UICONTROL Fields]**&#x200B;을(를) 선택합니다. 빠른 찾기에서 &quot;MSC&quot;를 검색합니다. 회색으로 표시된 모든 필드가 페이지 레이아웃에 추가되었습니다. 삭제해야 합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-6.png)

   >[!NOTE]
   >
   >어떤 필드도 회색으로 표시되지 않으면 페이지 레이아웃에 추가하지 않은 것입니다. 이 섹션은 건너뛸 수 있습니다.

1. [!DNL Sales Connect] 사용자 지정 필드가 있는 섹션으로 스크롤합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-7.png)

1. 이 섹션에 추가할 수 있는 10가지 유형의 MSC 필드가 있습니다. 추가한 필드를 모두 제거하거나 간단히 전체 섹션을 삭제합니다.

1. 완료되면 **[!UICONTROL Quick Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-8.png)

## 페이지 레이아웃에서 [!DNL Sales Connect]개 단추 제거 {#remove-sales-connect-buttons-from-page-layouts}

1. 콘솔(위의 4단계)에서 **[!UICONTROL Buttons]**&#x200B;을(를) 선택합니다. &quot;MSC&quot;를 검색합니다. 회색으로 표시된 모든 단추가 사용자 지정 단추 섹션에 추가되었습니다. 삭제해야 합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-9.png)

   >[!NOTE]
   >
   >회색으로 표시된 단추가 없으면 해당 단추를 추가하지 않은 것입니다. 이 섹션은 건너뛸 수 있습니다.

1. [!UICONTROL Custom Buttons] 섹션에서 콘솔로 MSC 단추를 끌어서 놓습니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-10.png)

1. 완료되면 **[!UICONTROL Quick Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-11.png)

## [!DNL Sales Connect] 섹션에서 [!UICONTROL Activity History] 필드 제거 {#remove-sales-connect-fields-from-activity-history-section}

1. 페이지 맨 아래로 스크롤하여 [!UICONTROL Activity History] 관련 목록 섹션으로 이동한 다음 렌치 아이콘을 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-12.png)

1. [!DNL Sales Connect] 영역에서 [!UICONTROL Selected Fields] 필드를 선택하고 [!UICONTROL Remove] 화살표를 클릭합니다. 완료되면 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-13.png)

   >[!NOTE]
   >
   >약어 MSE _is_ [!DNL Sales Connect]. 바로 이전 이름인 &quot;Marketo Sales Engage&quot;입니다.

1. 리드 페이지를 완료하면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

## 리드 목록 보기에서 [!DNL Sales Connect] 일괄 작업 단추 제거 {#remove-sales-connect-bulk-action-buttons-from-lead-list-view}

1. [!DNL Salesforce Lightning]에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Setup]**&#x200B;을(를) 선택합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-14.png)

1. **[!UICONTROL Object Manager]**&#x200B;을(를) 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-15.png)

1. 아래로 스크롤하여 **[!UICONTROL Lead]**&#x200B;을(를) 선택합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-16.png)

1. **[!UICONTROL Search Layouts]**&#x200B;을(를) 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-17.png)

1. [!UICONTROL List View] 옆에 있는 화살표를 클릭하고 **[!UICONTROL Edit]**&#x200B;을(를) 선택합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-18.png)

1. **[!UICONTROL Add to MSC Campaign]**, **[!UICONTROL Email with MSC]** 및 **[!UICONTROL Push to MSC]**&#x200B;을(를) 선택하고 [!UICONTROL Remove] 화살표를 클릭합니다. 그런 다음 **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/uninstall-salesforce-lightning-customization-package-19.png)

더 이상 가망 고객 목록 보기에 단추가 표시되지 않습니다.

## 연락처에 대한 MSC 구성 제거 {#remove-msc-configuration-for-contacts}

1. [!DNL Salesforce Lightning]에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Setup]**&#x200B;을(를) 선택합니다.

1. **[!UICONTROL Object Manager]**&#x200B;을(를) 클릭합니다.

1. 아래로 스크롤하여 **[!UICONTROL Contact]**&#x200B;을(를) 선택합니다.

1. **[!UICONTROL Page Layouts]**&#x200B;을(를) 클릭합니다.

1. **[!UICONTROL Contact Layout]**&#x200B;을(를) 클릭합니다.

1. 세 섹션 모두에서 단계를 반복합니다.

## 영업 기회에 대한 MSC 구성 제거 {#remove-msc-configuration-for-opportunity}

1. [!DNL Salesforce Lightning]에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Setup]**&#x200B;을(를) 선택합니다.

1. **[!UICONTROL Object Manager]**&#x200B;을(를) 클릭합니다.

1. 아래로 스크롤하여 **[!UICONTROL Opportunity]**&#x200B;을(를) 선택합니다.

1. **[!UICONTROL Page Layouts]**&#x200B;을(를) 클릭합니다.

1. **[!UICONTROL Opportunity Layout]**&#x200B;을(를) 클릭합니다.

Opportunity 보기에는 &quot;MSE Email 보내기&quot; 버튼 및 다음 필드만 있습니다.

![](assets/uninstall-salesforce-lightning-customization-package-20.png)

## 계정에 대한 MSC 구성 제거 {#remove-msc-configuration-for-account}

1. [!DNL Salesforce Lightning]에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Setup]**&#x200B;을(를) 선택합니다.

1. **[!UICONTROL Object Manager]**&#x200B;을(를) 클릭합니다.

1. 아래로 스크롤하여 **[!UICONTROL Account]**&#x200B;을(를) 선택합니다.

1. **[!UICONTROL Page Layouts]**&#x200B;을(를) 클릭합니다.

1. **[!UICONTROL Account Layout]**&#x200B;을(를) 클릭합니다.

계정 보기에는 &quot;MSE 이메일 보내기&quot; 버튼과 다음 필드만 있습니다.

![](assets/uninstall-salesforce-lightning-customization-package-21.png)

## Marketo Sales Outbox 제거 {#remove-marketo-sales-outbox}

1. [!DNL Salesforce]에서 화면 상단의 **+** 탭을 클릭합니다.

1. **[!UICONTROL Customize My Tabs]**&#x200B;을(를) 클릭합니다.

1. 오른쪽에서 Marketo Sales Outbox 옵션을 선택합니다. [!UICONTROL Remove] 화살표를 클릭한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

## [!DNL Sales Connect] 패키지 삭제 {#delete-sales-connect-package}

[!DNL Salesforce] 계정에서 개체를 모두 제거했으면 아래 단계를 따르십시오.

1. [!DNL Salesforce Lightning]에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Setup]**&#x200B;을(를) 선택합니다.

1. 빠른 찾기 상자에 &quot;Apex 클래스&quot;를 입력합니다.

1. 목록의 모든 &quot;MarketoSalesConnectionCustomization&quot; 또는 &quot;MarketoSalesEngageCustomization&quot; 항목 옆에 있는 **[!UICONTROL Delete]**&#x200B;을(를) 클릭합니다.

준비가 완료되었습니다!

다음은 [!DNL Salesforce] 인스턴스에서 제거해야 하는 모든 개체 목록입니다.

## [!DNL Sales Connect] 사용자 지정 세부 정보 {#sales-connect-customization-details}

<table>
 <tr>
  <th>사용자 정의 활동 필드</th>
  <th>설명</th>
  <th>유형</th>
  <th>데이터 유형</th>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Call Local Presence ID]</td>
  <td>사용자로서 MSC Phone에서 전화를 걸 때 Local Presence를 옵션으로 선택할 수 있습니다. 수신 전화에 수신자의 로컬 번호가 표시됩니다.</td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Call Recording URL]</td>
  <td>호출을 기록할 수 있으며 녹화에 대한 링크는 여기에 기록됩니다 </td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Campaign]</td>
  <td>연락처/잠재 고객이 속한 MSC 캠페인의 로그 이름</td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Campaign URL]</td>
  <td>MSC에서 생성된 캠페인에 대한 URL을 기록합니다. 이 아이콘을 클릭하면 MSC 웹 앱에서 캠페인이 열립니다</td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Campaign Current Step]</td>
  <td>연락처/잠재 고객이 캠페인에 있는 경우 이 필드에는 현재 진행 중인 단계의 이름이 기록됩니다</td>
  <td>활동</td>
  <td>확인란</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Attachment Viewed]</td>
  <td>수신자가 조회한 첨부 파일과 함께 이메일이 전송될 때 데이터를 기록합니다</td>
  <td>활동</td>
  <td>확인란</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Clicked]</td>
  <td>수신자가 이메일의 링크를 클릭하면 확인 표시를 기록합니다.</td>
  <td>활동</td>
  <td>확인란</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Replied]</td>
  <td>수신자가 전자 메일에 회신할 때 확인 표시를 기록합니다.</td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Status]</td>
  <td>이메일이 전송/진행 중/반송되었는지 여부를 표시합니다(반송된 이메일 추적은 사용된 게재 채널에 따라 다름).</td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Template]</td>
  <td>잠재 고객/담당자에게 전송된 전자 메일에 사용된 MSC 템플릿의 로그 이름</td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Template URL]</td>
  <td>MSC에서 생성된 템플릿에 대한 URL을 기록합니다. 이 아이콘을 클릭하면 MSC 웹 앱에서 템플릿이 열립니다</td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email URL]</td>
  <td>이 URL을 클릭하면 MSC에서 명령 센터를 열고 사용자가 전송된 전자 메일을 볼 수 있는 사람 세부 정보 보기 기록 탭을 가져옵니다.</td>
  <td>활동</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>[!UICONTROL MSC Email Viewed]</td>
  <td>수신자가 이메일을 볼 때 확인 표시를 기록합니다.</td>
  <td>활동</td>
  <td>확인란</td>
 </tr>
</table>

<table>
 <tr>
  <th>MSC 롤업 로깅 필드</th>
  <th>설명</th>
  <th>유형</th>
  <th>데이터 유형</th>
 </tr>
 <tr>
  <td>MSC - 마지막 마케팅 참여</td>
  <td>마케팅에서 마지막으로 들어오는 참여</td>
  <td>
  <p>계정
  <p>연락처
  <p>리드
  <p>기회</td>
  <td>데이터 및 시간</td>
 </tr>
 <tr>
  <td>MSC - 마지막 마케팅 참여 날짜</td>
  <td>마케팅 참여 타임스탬프</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
  <td>데이터 및 시간</td>
 </tr>
 <tr>
  <td>MSC - 마지막 마케팅 참여 설명</td>
  <td>약정에 대한 설명</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>MSC - 마지막 마케팅 참여 Source</td>
  <td>Source of Marketing 참여</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>MSC - 마지막 마케팅 참여 유형</td>
  <td>참여 유형(예: 웹 활동)</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>MSC - 영업별 마지막 활동</td>
  <td>영업 팀에서 마지막으로 수행한 활동</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
  <td>데이터 및 시간</td>
 </tr>
 <tr>
  <td>MSC - 마지막으로 회신함</td>
  <td>판매 이메일에 대한 마지막 이메일 회신</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
  <td>데이터 및 시간</td>
 </tr>
 <tr>
  <td>MSC - 현재 판매 캠페인</td>
  <td>연락처/잠재 고객이 속한 MSC 캠페인의 로그 이름</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
  <td>텍스트</td>
 </tr>
 <tr>
  <td>MSC - 마지막 판매 계약</td>
  <td>Sales에서 마지막으로 들어오는 참여</td>
  <td>
  <p>계정
  <p>연락처
  <p>리드
  <p>기회</td>
  <td>데이터 및 시간</td>
 </tr>
 <tr>
  <td>MSC - 옵트아웃</td>
  <td>옵트아웃 필드</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
  <td>확인란</td>
 </tr>
</table>

<table>
 <tr>
  <th>MSC 단추</th>
  <th>설명</th>
  <th>유형</th>
 </tr>
 <tr>
  <td>[!UICONTROL Send MSC Email]</td>
  <td>다음에서 판매 이메일 보내기 [!DNL Salesforce]</td>
  <td>
  <p>계정 
  <p>연락처 
  <p>리드 
  <p>기회</td>
 </tr>
 <tr>
  <td>[!UICONTROL Add to MSC Campaign]</td>
  <td>다음에서 MSC 캠페인에 추가 [!DNL Salesforce]</td>
  <td>
  <p>연락처
  <p>리드</td>
 </tr>
 <tr>
  <td>[!UICONTROL Push to MSC]</td>
  <td>[!DNL Salesforce]에서 MSC로 연락처 푸시</td>
  <td>
  <p>연락처
  <p>리드</td>
 </tr>
 <tr>
  <td>[!UICONTROL Call with MSC]</td>
  <td>다음으로 판매 전화 걸기 [!DNL Salesforce]</td>
  <td>
  <p>연락처
  <p>리드</td>
 </tr>
</table>

<table>
 <tr>
  <th>MSC 일괄 작업 단추</th>
  <th>설명</th>
  <th>유형</th>
 </tr>
 <tr>
  <td>[!UICONTROL Add to MSC Campaign]</td>
  <td>다음에서 MSC 캠페인에 추가 [!DNL Salesforce]</td>
  <td>
  <p>연락처
  <p>리드</td>
 </tr>
 <tr>
  <td>[!UICONTROL Push to MSC]</td>
  <td>[!DNL Salesforce]에서 MSC로 연락처 푸시</td>
  <td>
  <p>연락처
  <p>리드</td>
 </tr>
 <tr>
  <td>[!UICONTROL Email with MSC]</td>
  <td>MSC로 이메일 보내기 [!DNL Salesforce]</td>
  <td>
  <p>연락처
  <p>리드</td>
 </tr>
</table>
