---
unique-page-id: 11382829
description: IT별로 Marketing Outlook 플러그인 제거 - Marketing Docs - 제품 설명서
title: IT에서 Marketing Outlook 플러그인 제거
translation-type: tm+mt
source-git-commit: 972cf9769ac751d9abfd5665975703dcd07930f0
workflow-type: tm+mt
source-wordcount: '122'
ht-degree: 0%

---


# Marketing Outlook 플러그인 제거(IT {#marketo-outlook-plugin-uninstall-by-it})

IT 팀이 Marketing Outlook 플러그인을 원격으로 제거하는 방법을 설명합니다.

제거할 /x 스위치를 사용하여 &quot;시스템&quot; 또는 관리 사용자 계정으로 다음 명령줄을 실행합니다.

`<pre>msiexec.exe /x [File Name] /qn </pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn </pre>`

문제 해결을 위해 로깅을 설정하여 출력 로그 파일을 만들 수 있습니다.

`<pre>msiexec.exe /x [File Name] /qn /L*v MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v MarketoAddinUninstall.log</pre>`

로그 파일의 위치를 지정하려면 명령줄에서 파일 경로를 지정할 수 있습니다.

`<pre>msiexec.exe /x [File Name] /qn /L*v [File Path]MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddinUninstall.log</pre>`

>[!CAUTION]
>
>플러그인을 원격으로 제거하면 사용자 컴퓨터의 Outlook이 강제로 닫힙니다.

다른 로깅 수준 또는 사용자 인터페이스 수준을 시도하려면 [Microsoft의 스위치 전체 목록](https://support.microsoft.com/en-us/kb/227091)을 참조하십시오.
