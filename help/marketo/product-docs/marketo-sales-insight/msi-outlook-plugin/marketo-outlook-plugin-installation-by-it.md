---
unique-page-id: 11382815
description: IT별 Marketo [!DNL Outlook] 플러그인 설치 - Marketo 문서 - 제품 설명서
title: IT에서 제공하는 Marketo [!DNL Outlook] 플러그인 설치
exl-id: c1ae1fb8-d1ad-4c1b-899b-29629fcb166b
feature: Marketo Sales Insights
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '168'
ht-degree: 1%

---

# IT에서 제공하는 Marketo [!DNL Outlook] 플러그 인 설치 {#marketo-outlook-plugin-installation-by-it}

경우에 따라 기업 정책에 따라 IT 팀이 직원의 컴퓨터에 모든 소프트웨어를 설치해야 합니다. 이러한 경우 IT 부서는 자체 배포 소프트웨어를 사용하여 원격으로 이 작업을 수행하는 경우가 많습니다. 이 문서는 Outlook 플러그인을 원격으로 설치하기 위해 배포 프로세스 동안 입력으로 사용할 명령줄을 제공합니다.

>[!PREREQUISITES]
>
>Enterprise 키를 [설정](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/install-the-marketo-add-in-for-outlook-with-an-enterprise-key.md)합니다.

다음 명령줄을 &#39;System&#39;으로 실행하거나 /i 스위치를 사용하여 관리자 계정을 실행하여 설치합니다.

`<pre>msiexec.exe /i [File Name] /qn REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn REG=ABC9-123y-WXYZ-4321</pre>`

문제 해결을 위해 로깅을 활성화하여 출력 로그 파일을 만들 수 있습니다.

`<pre>msiexec.exe /i [File Name] /qn /L*v MarketoAddin.log REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn /L*v MarketoAddin.log REG=ABC9-123y-WXYZ-4321</pre>`

로그 파일의 위치를 지정하려면 명령줄에서 파일 경로를 지정할 수 있습니다.

`<pre>msiexec.exe /i [File Name] /qn /L*v [File Path]MarketoAddin.log REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddin.log REG=ABC9-123y-WXYZ-4321</pre>`

>[!CAUTION]
>
>로그 파일의 저장소 위치가 있어야 합니다. 그렇지 않으면 설치가 중단됩니다.

다른 로깅 수준이나 사용자 인터페이스 수준을 시도하려면 [Microsoft의 전체 스위치 목록](https://support.microsoft.com/en-us/office/command-line-switches-for-microsoft-office-products-079164cd-4ef5-4178-b235-441737deb3a6)을 참조하십시오.

>[!MORELIKETHIS]
>
>[Marketo [!DNL Outlook] IT에서 플러그인 제거](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/marketo-outlook-plugin-uninstall-by-it.md)
