---
unique-page-id: 11382815
description: IT별 Marketing Outlook 플러그인 설치 - Marketing Docs - 제품 설명서
title: IT별 Marketing Outlook 플러그인 설치
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 0%

---


# IT별 Marketing Outlook 플러그인 설치 {#marketo-outlook-plugin-installation-by-it}

기업 정책에 따라 IT 팀이 직원의 컴퓨터에 모든 소프트웨어를 설치해야 하는 경우가 있습니다. 이러한 경우 IT는 자체 배포 소프트웨어를 사용하여 원격으로 이러한 작업을 수행하는 경우가 많습니다. 이 문서는 Outlook 플러그인을 원격으로 설치하는 배포 프로세스 동안 입력으로 사용할 명령줄을 제공합니다.

>[!NOTE]
>
>**사전 요구 사항**
>
>[기업](http://docs.marketo.com/display/DOCS/Install+the+Marketo+Add-in+for+Outlook+with+an+Enterprise+Key) 키를 설정합니다.

다음 명령줄을 &#39;시스템&#39;으로 실행하거나 /i 스위치를 사용하여 관리자 사용자 계정으로 실행합니다.  `<pre>msiexec.exe /i [File Name] /qn REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**예**
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn REG=ABC9-123y-WXYZ-4321</pre>`

문제 해결을 위해 로깅을 설정하여 출력 로그 파일을 만들 수 있습니다.  `<pre>msiexec.exe /i [File Name] /qn /L*v MarketoAddin.log REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**예**
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn /L*v MarketoAddin.log REG=ABC9-123y-WXYZ-4321</pre>`

로그 파일의 위치를 지정하려면 명령줄에서 파일 경로를 지정할 수 있습니다.  `<pre>msiexec.exe /i [File Name] /qn /L*v [File Path]MarketoAddin.log REG=[Enterprise Key]</pre>`

>[!NOTE]
>
>**예**
>`<pre>msiexec.exe /i MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddin.log REG=ABC9-123y-WXYZ-4321</pre>`

>[!CAUTION]
>
>로그 파일의 저장소 위치가 존재해야 하며 그렇지 않으면 설치가 중단됩니다.

다른 로깅 수준 또는 사용자 인터페이스 수준을 시도하려는 경우 [Microsoft의 전체 스위치](https://support.microsoft.com/en-us/kb/227091) 목록을 참조하십시오.

>[!NOTE]
>
>**관련 문서**
>
>[IT에서 Marketing Outlook 플러그인 제거](marketo-outlook-plugin-uninstall-by-it.md)

