---
unique-page-id: 2949711
description: 등록 코드가 있는 Outlook용 Marketo 이메일 추가 기능 설치 - Marketo 문서 - 제품 설명서
title: 등록 코드를 사용하여 Outlook용 Marketo 이메일 추가 기능 설치
exl-id: d7a877c2-f71e-44da-b323-04f6cdb44eb0
feature: Marketo Sales Insights
source-git-commit: 40fe81d465d04be97ae5e216250b7e06e6d3791e
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 1%

---

# 등록 코드를 사용하여 Outlook용 Marketo 이메일 추가 기능 설치 {#install-the-marketo-email-add-in-for-outlook-with-a-registration-code}

사용자가 랩톱의 관리 설정에 액세스할 수 있는 경우 등록 코드를 직접 전송할 수 있습니다.

초대 이메일을 받지 못한 경우 Marketo 관리자에게 초대를 요청하십시오.

>[!PREREQUISITES]
>
>다음을 수행해야 합니다. [Marketo 이메일 추가 기능 라이선스 발행](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/issue-a-marketo-email-add-in-license.md).

>[!IMPORTANT]
>
>Windows 사용자 폴더에 영어가 아닌 문자가 포함된 PC에서는 설치가 지원되지 않습니다. 이 폴더는 Windows에서 `<System Root>\Users\` windows 사용자 이름을 기반으로 하며 Windows 사용자 이름이 영어가 아닌 경우 영어가 아닌 문자를 포함할 수 있습니다. IT 팀과 협력하여 설치 문제가 있는지 확인하십시오.

>[!NOTE]
>
>Gmail 및 Outlook용 Sales Insight 이메일 플러그인에서 판매 이메일 보내기, 판매 캠페인에 추가, 작업 등 Sales Insight 작업 기능을 사용할 수 없습니다. 현재 사용자는 Sales Insight 이메일 플러그인을 사용할 때 이메일 클라이언트에서 Marketo 이메일 템플릿을 사용하거나 사용하지 않고 추적 가능한 이메일을 보낼 수 있습니다.

## 설치 관리자 다운로드 {#download-installer}

1. 다음 항목 식별 [Microsoft Outlook 버전](https://support.office.com/en-us/article/what-version-of-outlook-do-i-have-b3a9568c-edb5-42b9-9825-d48d82b2257c){target="_blank"}

1. 링크를 클릭하여 사용 중인 Microsoft Outlook 버전에 적합한 설치 관리자를 다운로드합니다.

   >[!NOTE]
   >
   >현재 아래 링크는 Microsoft Edge에서만 작동하거나 Chrome을 마우스 오른쪽 버튼으로 클릭하여 작동합니다. 불편을 드려 죄송합니다.

   | Outlook 버전 | 32비트 Outlook | 64비트 Outlook |
   |---|---|---|
   | Outlook 2000 | 지원되지 않음 | 해당 없음 |
   | Outlook 2003 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | 해당 없음 |
   | Outlook 2007 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | 해당 없음 |
   | Outlook 2010 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2013 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2016 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2019 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Mac용 Outlook | 지원되지 않음 | 지원되지 않음 |
   | Outlook Web App | 지원되지 않음 | 지원되지 않음 |
   | Office 365* | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |

   *Office 365 버전: Windows 클라이언트 전용(Windows 10, Enterprise 또는 Pro).

   >[!IMPORTANT]
   >
   >Microsoft이 [Windows용 Outlook의 새 버전](https://techcommunity.microsoft.com/t5/outlook-blog/new-outlook-for-windows-now-available/ba-p/3932068){target="_blank"}. This new version does not support the existing MSI Outlook plugin. The MSI Outlook plugin will continue to work for Windows desktops running the classic version of Outlook. To learn more about the new Outlook for Windows for organizations, [click here](https://techcommunity.microsoft.com/t5/outlook-blog/the-new-outlook-for-windows-for-organization-admins/ba-p/3929169){target="_blank"}.

## 등록 코드 복사 {#copy-your-registration-code}

1. 받은 초대 이메일의 등록 코드를 복사합니다.

   ![](assets/image2016-7-22-10-3a45-3a10.png)

1. Microsoft Outlook을 닫습니다.

   ![](assets/ent-key-close-outlook-hand.png)

## 설치 {#install}

1. 설치 관리자를 실행합니다.

   ![](assets/image2016-7-25-10-3a23-3a33.png)

   >[!NOTE]
   >
   >보안 경고를 받으면 걱정하지 마십시오! 그냥 클릭 **실행**.

1. 클릭 **다음**.

   ![](assets/welcome-to-the-setup-wizard-hand.png)

1. 채우기 **이름**, **성**, **이메일 주소**&#x200B;을(를) 복사한 다음 을(를) 붙여넣습니다. **등록 코드** 이메일에서 양식으로 전환한 다음 **다음**.

   ![](assets/enter-your-information-hands.png)

   >[!TIP]
   >
   >설치에 실패한 경우 IT 부서에 문의하여 HTTPS 트래픽이 차단되지 않았는지 확인하십시오. 설치 관리자를 열려면 HTTPS 트래픽이 필요합니다.

1. 클릭 **다음** 기본 위치에 를 설치합니다.

   ![](assets/select-installation-folder-hand.png)

1. 클릭 **다음**.

   ![](assets/confirm-installation-hand.png)

   >[!NOTE]
   >
   >알 수 없는 게시자에 대한 보안 메시지가 표시되면 **예**.

1. 이제 설치가 완료되었습니다. 다음을 클릭하십시오. **닫기**.

   ![](assets/image2014-9-23-15-3a52-3a11.png)

1. 이제 Microsoft Outlook을 열고 Marketo 버튼을 확인합니다.

   ![](assets/image2016-8-24-15-3a47-3a38.png)

   훌륭합니다! 이제 Marketo 버튼이 더 나은 위치에 있습니다.

Marketo 메시지 및 Marketo으로 로그 작업 사용에 대해 자세히 알아보십시오.

>[!MORELIKETHIS]
>
>* [Outlook용 Marketo 이메일 추가 기능을 사용하여 이메일 전송 및 추적](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-an-email-with-the-email-add-in-for-outlook.md){target="_blank"}
>* [Marketo 템플릿을 사용하여 Outlook에서 전송 및 추적](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md){target="_blank"}
