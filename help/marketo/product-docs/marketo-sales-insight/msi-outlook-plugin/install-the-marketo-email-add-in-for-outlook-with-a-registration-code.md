---
unique-page-id: 2949711
description: 등록 코드 - Marketo 문서 - 제품 설명서와 함께 Outlook용 Marketo 이메일 추가 기능 설치
title: 등록 코드와 함께 Outlook용 Marketo 이메일 추가 기능 설치
exl-id: d7a877c2-f71e-44da-b323-04f6cdb44eb0
source-git-commit: 0dec1dc142a7296ce9d5db91493f654dbe7ee99a
workflow-type: tm+mt
source-wordcount: '471'
ht-degree: 4%

---

# 등록 코드와 함께 Outlook용 Marketo 이메일 추가 기능 설치 {#install-the-marketo-email-add-in-for-outlook-with-a-registration-code}

사용자가 랩탑에서 관리 설정에 액세스할 수 있는 경우 등록 코드를 직접 해당 사용자에게 보낼 수 있습니다.

초대 이메일을 받지 못한 경우 Marketo 관리자에게 초대를 요청하십시오.

>[!PREREQUISITES]
>
>다음을 수행해야 합니다. [발급된 Marketo 이메일 추가 기능 라이선스](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/issue-a-marketo-email-add-in-license.md).

>[!IMPORTANT]
>
>Windows 사용자 폴더에 영어 이외의 문자가 포함된 PC에서는 설치가 지원되지 않습니다. 이 폴더는 아래의 Windows에서 자동으로 생성됩니다 <System Root>\Users\ Windows 사용자 이름을 기반으로 하며 Windows 사용자 이름이 영어가 아닌 경우 영어가 아닌 문자를 포함할 수 있습니다. IT 팀과 협력하여 설치 문제가 발생하는지 확인하십시오.

>[!NOTE]
>
>10/1/20에서 최신 버전의 Outlook 플러그인이 오프라인 모드 지원을 중지했습니다.

## 설치 프로그램 다운로드 {#download-installer}

1. 사용자 식별 [Microsoft Outlook 버전](https://support.office.com/en-us/article/what-version-of-outlook-do-i-have-b3a9568c-edb5-42b9-9825-d48d82b2257c)

1. 해당 버전의 Microsoft Outlook에 적합한 설치 프로그램을 다운로드하려면 링크를 클릭합니다.

   >[!NOTE]
   >
   >이때 아래 링크는 Microsoft Edge에서만 작동하거나 Chrome을 마우스 오른쪽 단추로 클릭합니다. 불편을 끼쳐드려 죄송합니다

   | Outlook 버전 | 32비트 Outlook | 64비트 Outlook |
   |---|---|---|
   | Outlook 2000 | 지원되지 않음 | 해당 없음 |
   | Outlook 2003 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | 해당 없음 |
   | Outlook 2007 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | 해당 없음 |
   | Outlook 2010 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2013 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2016 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Outlook 2019 | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |
   | Mac Outlook | 지원되지 않음 | 지원되지 않음 |
   | Outlook Web App | 지원되지 않음 | 지원되지 않음 |
   | Office 365* | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup32.msi) | [다운로드](https://munchkin.marketo.net/MarketoAddInSetup64.msi) |

   *Office 365 버전: Windows 클라이언트만(Windows 10, Enterprise 또는 Pro).

## 등록 코드 복사 {#copy-your-registration-code}

1. 받은 초대 이메일에서 등록 코드를 복사합니다.

   ![](assets/image2016-7-22-10-3a45-3a10.png)

1. Microsoft Outlook을 닫습니다.

   ![](assets/ent-key-close-outlook-hand.png)

## 설치 {#install}

1. 설치 관리자를 실행합니다.

   ![](assets/image2016-7-25-10-3a23-3a33.png)

   >[!NOTE]
   >
   >보안 경고가 나타나면 걱정하지 마십시오! 클릭 **실행**.

1. 클릭 **다음**.

   ![](assets/welcome-to-the-setup-wizard-hand.png)

1. 채우기 **이름**, **성**, **이메일 주소**&#x200B;를 복사한 다음 붙여넣습니다. **등록 코드** 이메일에서 폼으로 **다음**.

   ![](assets/enter-your-information-hands.png)

   >[!TIP]
   >
   >설치에 실패하는 경우 IT 부서에 문의하여 HTTPS 트래픽이 차단되지 않았는지 확인하십시오. 설치 관리자를 열려면 HTTPS 트래픽이 필요합니다.

1. 클릭 **다음** 를 클릭하여 기본 위치에 설치합니다.

   ![](assets/select-installation-folder-hand.png)

1. 클릭 **다음**.

   ![](assets/confirm-installation-hand.png)

   >[!NOTE]
   >
   >알 수 없는 게시자에 대한 보안 메시지가 나타나면 **예**.

1. 이제 설치가 완료되었으므로 **닫기**.

   ![](assets/image2014-9-23-15-3a52-3a11.png)

1. 이제 Microsoft Outlook을 열고 Marketo 단추를 확인합니다.

   ![](assets/image2016-8-24-15-3a47-3a38.png)

   훌륭해요! 이제 Marketo 버튼이 더 나은 위치에 있습니다.

Marketo 메시지 사용 및 Marketo 로그으로 작업에 대해 자세히 알아보십시오.

>[!MORELIKETHIS]
>
>* [Outlook용 Marketo 이메일 추가 기능을 사용하여 이메일 보내기 및 추적](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-an-email-with-the-email-add-in-for-outlook.md)
>* [Marketo 템플릿을 사용하여 Outlook에서 보내기 및 추적](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/send-and-track-from-outlook-using-a-marketo-template.md)

