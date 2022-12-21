---
unique-page-id: 2949279
description: Outlook용 Marketo 이메일 추가 기능 업그레이드 - Marketo 문서 - 제품 설명서
title: Outlook용 Marketo 이메일 추가 기능 업그레이드
exl-id: 079f1142-8062-448c-aa07-59ecd89a718f
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '405'
ht-degree: 8%

---

# Outlook용 Marketo 이메일 추가 기능 업그레이드 {#upgrade-your-marketo-email-add-in-for-outlook}

Outlook용 Marketo 전자 메일 추가 기능의 새 버전을 사용할 수 있는 경우 다음 지침에 따라 업그레이드하십시오.

>[!NOTE]
>
>10/1/20 현재 최신 버전의 Outlook 플러그인은 더 이상 오프라인 모드를 지원하지 않습니다. 이 기능은 10/1 또는 후에 설치/업그레이드한 후에 적용됩니다.

## 설치 프로그램 다운로드 {#download-installer}

사용 중인 Microsoft Outlook 버전에 적합한 설치 프로그램을 다운로드합니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><br></th> 
   <th colspan="2">단일 사용자 초대 설치</th> 
   <th colspan="2">Enterprise 키 설치</th> 
  </tr> 
  <tr> 
   <td><strong>Outlook 버전</strong></td> 
   <td><strong>32비트</strong></td> 
   <td><strong>64비트</strong></td> 
   <td><strong>32비트</strong></td> 
   <td><strong>64비트</strong></td> 
  </tr> 
  <tr> 
   <td>Outlook 2000</td> 
   <td>지원되지 않음</td> 
   <td>해당 없음</td> 
   <td>지원되지 않음</td> 
   <td>해당 없음</td> 
  </tr> 
  <tr> 
   <td>Outlook 2003</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td>해당 없음</td> 
   <td>지원되지 않음</td> 
   <td>해당 없음</td> 
  </tr> 
  <tr> 
   <td>Outlook 2007</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td>해당 없음</td> 
   <td>지원되지 않음</td> 
   <td>해당 없음</td> 
  </tr> 
  <tr> 
   <td>Outlook 2010</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
  </tr> 
  <tr> 
   <td>Outlook 2013</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
  </tr> 
  <tr> 
   <td>Outlook 2016</td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
  </tr> 
  <tr> 
   <td colspan="1">Outlook 2019</td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
  </tr> 
  <tr> 
   <td>Mac Outlook</td> 
   <td>지원되지 않음</td> 
   <td>지원되지 않음</td> 
   <td>지원되지 않음</td> 
   <td>지원되지 않음</td> 
  </tr> 
  <tr> 
   <td colspan="1">Outlook Web App</td> 
   <td colspan="1">지원되지 않음</td> 
   <td colspan="1">지원되지 않음</td> 
   <td colspan="1">지원되지 않음</td> 
   <td colspan="1">지원되지 않음</td> 
  </tr> 
  <tr> 
   <td colspan="1">Office 365*</td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup32.msi" rel="nofollow">다운로드</a></td> 
   <td colspan="1"><a href="https://munchkin.marketo.net/MarketoAddInSetup64.msi" rel="nofollow">다운로드</a></td> 
  </tr> 
 </tbody> 
</table>

&#42;Office 365 버전: Windows 클라이언트만(Windows 10, Enterprise 또는 Pro).

## 업그레이드 {#upgrade}

1. 사용자 식별 [Microsoft Outlook 버전](https://support.microsoft.com/en-us/office/what-version-of-outlook-do-i-have-b3a9568c-edb5-42b9-9825-d48d82b2257c?ui=en-us&amp;rs=en-us&amp;ad=us).

1. 위의 목록에서 버전을 선택합니다.

1. 설치 관리자를 실행합니다.

   ![](assets/image2014-9-23-16-3a53-3a56.png)

1. 클릭 **다음**.

   ![](assets/image2014-9-23-16-3a54-3a8.png)

   >[!NOTE]
   >
   >경우에 따라 데이터가 누락됩니다. 등록 이메일에서 복사한 다음 Outlook을 닫습니다.

1. Microsoft Outlook을 닫습니다.

   ![](assets/ent-key-close-outlook-hand.png)

1. 모든 정보가 미리 입력되어 있음을 알 수 있습니다. 간단히 **다음**.

   ![](assets/image2014-9-23-16-3a54-3a40.png)

   >[!TIP]
   >
   >설치에 실패하는 경우 IT 부서의 도움을 받아 HTTPS 트래픽이 차단되지 않도록 하십시오. 설치 관리자를 열려면 HTTPS 트래픽이 필요합니다.

1. 클릭 **다음** 를 클릭하여 기본 위치에 설치합니다.

   ![](assets/image2014-9-23-16-3a54-3a55.png)

1. 클릭 **다음**.

   ![](assets/image2014-9-23-16-3a55-3a20.png)

1. 이제 설치가 완료되었습니다. Click **Close**.

   ![](assets/image2014-9-23-16-3a55-3a34.png)

1. 이제 Microsoft Outlook을 열어 최신 버전의 Marketo 단추를 확인하십시오.

   ![](assets/image2016-8-24-15-3a47-3a38.png)

>[!MORELIKETHIS]
>
>* [Outlook용 Marketo 이메일 추가 기능을 사용하여 이메일 보내기 및 추적](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-an-email-with-the-email-add-in-for-outlook.md)
>* [Marketo 템플릿을 사용하여 Outlook에서 보내기 및 추적](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md)

