---
unique-page-id: 2949711
description: 등록 코드 - Marketo 문서 - 제품 설명서와 함께  [!DNL Outlook] 용 Marketo 이메일 추가 기능 설치
title: 등록 코드를 사용하여  [!DNL Outlook] 용 Marketo 이메일 추가 기능 설치
exl-id: d7a877c2-f71e-44da-b323-04f6cdb44eb0
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '522'
ht-degree: 4%

---

# 등록 코드를 사용하여 [!DNL Outlook]용 Marketo 이메일 추가 기능 설치 {#install-the-marketo-email-add-in-for-outlook-with-a-registration-code}

사용자가 랩톱의 관리 설정에 액세스할 수 있는 경우 등록 코드를 직접 전송할 수 있습니다.

초대 이메일을 받지 못한 경우 Marketo 관리자에게 초대를 요청하십시오.

>[!PREREQUISITES]
>
>[Marketo 전자 메일 추가 기능 라이선스를 발급](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/issue-a-marketo-email-add-in-license.md)받아야 합니다.

>[!IMPORTANT]
>
>Windows 사용자 폴더에 영어가 아닌 문자가 포함된 PC에서는 설치가 지원되지 않습니다. 이 폴더는 Windows에서 Windows 사용자 이름을 기반으로 `<System Root>\Users\` 아래에 자동으로 생성되며 Windows 사용자 이름이 영어가 아닌 이름인 경우 영어가 아닌 문자가 포함될 수 있습니다. IT 팀과 협력하여 설치 문제가 있는지 확인하십시오.

>[!NOTE]
>
>판매 이메일 보내기, 판매 캠페인에 추가, 작업 등 판매 Insight 작업 기능은 Gmail 및 Outlook용 판매 Insight 이메일 플러그인에서 사용할 수 없습니다. 현재 사용자는 Sales Insight 이메일 플러그인을 사용할 때 이메일 클라이언트에서 Marketo 이메일 템플릿을 사용하거나 사용하지 않고 추적 가능한 이메일을 보낼 수 있습니다.

## 설치 관리자 다운로드 {#download-installer}

1. [Microsoft Outlook 버전](https://support.office.com/en-us/article/what-version-of-outlook-do-i-have-b3a9568c-edb5-42b9-9825-d48d82b2257c){target="_blank"}을 확인하세요.

1. 아래 표에서 링크를 클릭하여 사용 중인 Microsoft Outlook 버전에 맞는 .ZIP 파일을 다운로드합니다.

1. 파일의 압축을 풀고 필요한 .MSI 파일에 액세스하여 설치를 계속합니다.

   >[!NOTE]
   >
   >현재 아래 링크는 [!DNL Microsoft Edge]에서만 작동하거나 [!DNL Chrome]을(를) 마우스 오른쪽 단추로 클릭하여 작동합니다. 불편을 드려 죄송합니다.

<table><thead>
  <tr>
    <th>Outlook 버전</th>
    <th>32비트 Outlook</th>
    <th>64비트 Outlook</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Outlook 2000</td>
    <td>지원되지 않음</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>Outlook 2003</td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.zip">다운로드</a></td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>Outlook 2007</td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.zip">다운로드</a></td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>Outlook 2010</td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.zip">다운로드</a></td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.zip">다운로드</a></td>
  </tr>
  <tr>
    <td>Outlook 2013</td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.zip">다운로드</a></td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.zip">다운로드</a></td>
  </tr>
  <tr>
    <td>Outlook 2016</td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.zip">다운로드</a></td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.zip">다운로드</a></td>
  </tr>
  <tr>
    <td>Outlook 2019</td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.zip">다운로드</a></td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.zip">다운로드</a></td>
  </tr>
  <tr>
    <td>Mac용 Outlook</td>
    <td>지원되지 않음</td>
    <td>지원되지 않음</td>
  </tr>
  <tr>
    <td>Outlook Web App</td>
    <td>지원되지 않음</td>
    <td>지원되지 않음</td>
  </tr>
  <tr>
    <td>Office 365*</td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup32.zip">다운로드</a></td>
    <td><a href="https://munchkin.marketo.net/MarketoAddInSetup64.zip">다운로드</a></td>
  </tr>
</tbody></table>

*[!DNL Office] 365 버전: [!DNL Windows] 클라이언트만([!DNL Windows] 10, [!DNL Enterprise] 또는 [!DNL Pro]에).

>[!IMPORTANT]
>
>Microsoft에서 [Windows용 Outlook의 새 버전](https://techcommunity.microsoft.com/t5/outlook-blog/new-outlook-for-windows-now-available/ba-p/3932068){target="_blank"}을 릴리스했습니다. 이 새 버전은 기존 MSI Outlook 플러그인을 지원하지 않습니다. MSI Outlook 플러그인은 클래식 버전의 Outlook을 실행하는 Windows 데스크톱에서 계속 작동합니다. 새로운 Windows용 Outlook 조직에 대해 자세히 알아보려면 [여기를 클릭](https://techcommunity.microsoft.com/t5/outlook-blog/the-new-outlook-for-windows-for-organization-admins/ba-p/3929169){target="_blank"}하세요.

## 등록 코드 복사 {#copy-your-registration-code}

1. 받은 초대 이메일의 등록 코드를 복사합니다.

   ![](assets/image2016-7-22-10-3a45-3a10.png)

1. [!DNL Microsoft Outlook]을(를) 닫습니다.

   ![](assets/ent-key-close-outlook-hand.png)

## 설치 {#install}

1. 설치 관리자를 실행합니다.

   ![](assets/image2016-7-25-10-3a23-3a33.png)

   >[!NOTE]
   >
   >보안 경고를 받으면 걱정하지 마십시오! **실행**&#x200B;을 클릭하세요.

1. **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/welcome-to-the-setup-wizard-hand.png)

1. **[!UICONTROL First Name]**, **[!UICONTROL Last Name]**, **[!UICONTROL Email Address]**&#x200B;을(를) 입력한 다음 전자 메일의 **[!UICONTROL Registration code]**&#x200B;을(를) 복사하여 양식에 붙여 넣고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/enter-your-information-hands.png)

   >[!TIP]
   >
   >설치에 실패한 경우 IT 부서에 문의하여 HTTPS 트래픽이 차단되지 않았는지 확인하십시오. 설치 관리자를 열려면 HTTPS 트래픽이 필요합니다.

1. 기본 위치에 설치하려면 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/select-installation-folder-hand.png)

1. **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/confirm-installation-hand.png)

   >[!NOTE]
   >
   >알 수 없는 게시자에 대한 보안 메시지가 표시되면 **[!UICONTROL Yes]**&#x200B;을(를) 클릭합니다.

1. 이제 설치가 완료되었습니다. **[!UICONTROL Close]**&#x200B;을(를) 클릭하십시오.

   ![](assets/image2014-9-23-15-3a52-3a11.png)

1. 이제 [!DNL Microsoft Outlook]을(를) 열고 Marketo 단추를 확인합니다.

   ![](assets/image2016-8-24-15-3a47-3a38.png)

   훌륭합니다! 이제 Marketo 버튼이 더 나은 위치에 있습니다.

Marketo 메시지 및 Marketo으로 로그 작업 사용에 대해 자세히 알아보십시오.

>[!MORELIKETHIS]
>
>* [Outlook용 Marketo 전자 메일 추가 기능을 사용하여 전자 메일을 보내고 추적하기](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-an-email-with-the-email-add-in-for-outlook.md){target="_blank"}
>* [Marketo 템플릿을 사용하여 Outlook에서 전송 및 추적](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md){target="_blank"}
