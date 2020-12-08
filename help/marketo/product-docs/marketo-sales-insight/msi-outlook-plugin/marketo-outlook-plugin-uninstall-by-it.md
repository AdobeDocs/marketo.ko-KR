---
unique-page-id: 11382829
description: IT별 Marketing Outlook 플러그인 제거 - Marketing Docs - 제품 설명서
title: IT에서 Marketing Outlook 플러그인 제거
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '122'
ht-degree: 0%

---


# IT에서 Marketing Outlook 플러그인 제거 {#marketo-outlook-plugin-uninstall-by-it}

IT 팀은 Marketing Outlook 플러그인을 원격으로 제거하는 방법을 설명합니다.

다음 명령줄을 &#39;시스템&#39;과 같이 실행하거나 /x 스위치를 사용하여 관리 사용자 계정을 제거합니다.
`<pre>msiexec.exe /x [File Name] /qn </pre>`

>[!NOTE]
>
>**예**
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn </pre>`

문제 해결을 위해 로깅을 설정하여 출력 로그 파일을 만들 수 있습니다.  `<pre>msiexec.exe /x [File Name] /qn /L*v MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**예**
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v MarketoAddinUninstall.log</pre>`

로그 파일의 위치를 지정하려면 명령줄에서 파일 경로를 지정할 수 있습니다.  `<pre>msiexec.exe /x [File Name] /qn /L*v [File Path]MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**예**
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddinUninstall.log</pre>`

>[!CAUTION]
>
>플러그인을 원격으로 제거하면 사용자의 컴퓨터에서 Outlook이 강제로 닫힙니다.

다른 로깅 수준 또는 사용자 인터페이스 수준을 시도하려는 경우 [Microsoft의 전체 스위치](https://support.microsoft.com/en-us/kb/227091) 목록을 참조하십시오.